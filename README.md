# Acesso-remoto-windows-cmd

```
C:\Install\PSTools>PsExec.exe \\mffs01 -c cmd.exe

PsExec v2.4 - Execute processes remotely
Copyright (C) 2001-2022 Mark Russinovich
Sysinternals - www.sysinternals.com


O sistema não pode encontrar o texto correspondente à mensagem de número 0x2350 no arquivo de mensagens para Application.
Não há recursos de memória disponíveis suficientes para processar este comando.

(c) Microsoft Corporation. Todos os direitos reservados.

C:\WINDOWS\system32>hostname
MFFS01

c:\Install\util>install.bat

c:\Install\util>msiexec /i "C:\Install\util\suporte-remoto.msi" SILENTMODE=1 /L*v+ "C:\Install\util\suporte-remoto.log" 

c:\Install\util>hostname
MFFS01

c:\Install\util>shutdown /r /t 0
````
