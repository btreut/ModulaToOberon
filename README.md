# ModulaToOberon
Transpiler from Modula-2 to Oberon and Component Pascal

In the second half of the last decade of the last century, I found Niklaus Wirth's Modula to Oberon transpiler as binhex files on some ftp server, most probably it was the ftp server of the GWDG (Gesellschaft für wissenschaftliche Datenverarbeitung, part of the German Max Planck Society), where it is still (as of 26-Apr-2023) available at this directory https://ftp.gwdg.de/pub/languages/oberon/ftp.inf.ethz.ch/OberonV4/MacII/Sources/ModulaToOberon/.

Nw's original version skips comments and presents syntax errors as error numbers. That was compiler behavior in early Modula-2 times (at least for those compilers written by NW's group). There should have been also a list, which explaines the meaning of the error number. This list was missing for the transpiler. I contacted  NW for help, but he could not help either, so I used available Modula-2 compiler error lists and  guessed the meaning of the error numbers for the transpiler in the first version. Later I included BlackBox error elements for the error messages.

 At that time I used Oberon-V4 and BlackBox in parallel so I tried to keep two versions in sync and used the version elemts available in V4 for that. I include the BlackBox StdCoded file m2o.txt. Sorrily the importer for the *.Eth files of the current BlackBox version does not import the fold elements correcty and cannot handle version elements. I'll try my best in the next time to manually correct these problems.
