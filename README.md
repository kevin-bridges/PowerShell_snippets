# PowerShell_snippets

## File Manipulation

### Replace text in text file:
*(In this case, find the text: '##THAT' and replace it with '%%I CHANGED!!!!')*

`(Get-Content .\testfile.txt) -replace '\[##THAT\]', '%%I CHANGED!!!!' | Set-Content .\testfile.txt`
