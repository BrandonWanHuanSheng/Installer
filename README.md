First, extract the setup file by using 7-zip
7-zip file can be download from https://www.7-zip.org

# AppsAndFeaturesEntries
Look at the  0 file or bin\*.exe*
Save it to AppsandFeaturesEntries\$FirstPascalCaseofPublisher\$Publisher\$AppName\$Version
Example: AppsandFeaturesEntries\I\Iobit\Uninstaller\13.1.0.3

# SetupInstructions
Look at the string.txt file in .rsrc\0
That one is the SetupInstruction
Save it to SetupInstruction\$FirstPascalCaseofPublisher\$Publisher\$AppName
Example: SetupInstruction\I\Iobit\Uninstaller\
