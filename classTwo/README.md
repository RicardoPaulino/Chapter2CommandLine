## Para criar um executável e referenciar arquivos externo ao programa criado
```
csc /r:System.Windows.Forms.dll HelloMessage.cs /Target:exe Program.cs
```