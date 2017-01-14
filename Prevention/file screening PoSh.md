#Microsoft Windows File Screening


**Server 2012**

    New-FsrmFileGroup -Name "Malware Files" –IncludePattern @("*.FUN","*.KKK","*.GWS","*.BTC","_DECRYPT_INFO_*","_Locky_recover_instructions.txt","DECRYPT_INSTRUCTIONS.TXT", "DECRYPT_INSTRUCTIONS.HTML", "DECRYPT_INSTRUCTION.TXT", "DECRYPT_INSTRUCTION.HTML", "HELP_DECRYPT.TXT", "HELP_DECRYPT.HTML", "DecryptAllFiles.txt", "enc_files.txt", "HowDecrypt.txt", "How_Decrypt.txt", "How_Decrypt.html", "HELP_TO_DECRYPT_YOUR_FILES.txt", "HELP_RESTORE_FILES.txt", "HELP_TO_SAVE_FILES.txt", "restore_files*.txt", "restore_files.txt", "RECOVERY_KEY.TXT", "how to decrypt aes files.lnk", "HELP_DECRYPT.PNG", "HELP_DECRYPT.lnk", "DecryptAllFiles*.txt", "Decrypt.exe", "ATTENTION!!!.txt", "AllFilesAreLocked*.bmp", "MESSAGE.txt","*.locky","*.ezz", "*.ecc", "*.exx", "*.7z.encrypted", "*.ctbl", "*.encrypted", "*.aaa", "*.xtbl", "*.abc", "*.JUST", "*.EnCiPhErEd", "*.cryptolocker","*.micro")

**Server 2008/R2**

    filescrn Filegroup Add /Filegroup:"Ransomware Files" /Members:"*.FUN|*.KKK|*.GWS|*.BTC|_DECRYPT_INFO_*|_Locky_recover_instructions.txt|DECRYPT_INSTRUCTIONS.TXT|DECRYPT_INSTRUCTIONS.HTML|DECRYPT_INSTRUCTION.TXT|DECRYPT_INSTRUCTION.HTML|HELP_DECRYPT.TXT|HELP_DECRYPT.HTML|DecryptAllFiles.txt|enc_files.txt|HowDecrypt.txt|How_Decrypt.txt|How_Decrypt.html|HELP_TO_DECRYPT_YOUR_FILES.txt|HELP_RESTORE_FILES.txt|HELP_TO_SAVE_FILES.txt|restore_files*.txt|restore_files.txt|RECOVERY_KEY.TXT|how to decryp t aes files.lnk|HELP_DECRYPT.PNG|HELP_DECRYPT.lnk|DecryptAllFiles*.txt|Decrypt.exe|ATTENTION!!!.txt|AllFilesAreLocked*.bmp|MESSAGE.txt|*.locky|*.ezz|*.ecc|*.exx|*.7z.encrypted|*.ctbl|*.encrypted|*.aaa|*.xtbl|*.abc|*.JUST|*.EnCiPhErEd|*.cryptolocker|*.micro"