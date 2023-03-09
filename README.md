# trioses

## Triboot
Windows 10 v1903
macOS 10.13.6 High Sierra
Pop-OS 20.04 LTS

## Etapas

0. configurar a bios / sata AHCI / boot Legacy CSM disabled
1. 
2. Preparar as partições
3. Instalar o Windows com pedrive modo boot UEFI
4. Instalar o pop-OS 20.04
5. durante o boot teclar DEL para entrar na bios da mobo e teclar F8 para escolher o OS win10 pop22
6. instalar macOS  usando pendrive preparado com UEFI e boot inicial UEFI / entrar em disk utility, escolher erase, APFS, depois sair 
7. acesar o menu reinstall macOS, escolher e confirmar a partição
8. finder preferences  marcar hard disks
9. ao acessar o macOS usar o script mountefi para qualquer um discos pois o EFI é igual para ambos, renomear a pasta boot para boot-bkp e o arquivo  localizado em microsoft/Boot/  renomear bootmgfw.efi  para bootmgfw.efi-bkp 
10. copiar as pastas /BOOT e /os para o disco macOS e reiniciar o macOS, note que agora o aquivo bootmgfw.efi-bkp  renomeados deve ser restaurado para o nome original
11. desmontar o disco externo

Download da Quick Action para montar a EFI:
https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqblpSSk5TRnA5NHVyWFlqOUtqbXVLY0g2UDVzd3xBQ3Jtc0tsOXJqelAwd3hKd0RWN1A5RFE2cEJNZTd4aU8yTUpRRlJNblpqazNoMDVkS0F6V0xEMVQ1QklrZENnYjZRLVUxLUdkQnVYaFJwZ3NlMjEzaGdiY29RdExoeWNNclBhZEVBT0JYOUhtY1poMGg1SU5jVQ&q=https%3A%2F%2Fgithub.com%2Fluchina-gabriel%2Fyoutube-files%2Fraw%2Fmain%2FMountEFI.zip&v=AnOt5wqm6-U


videos

1) HACKINTOSH: COMO FAZER DUAL BOOT QUANDO JÁ TEMOS O WINDOWS INSTALADO https://youtu.be/AnOt5wqm6-U

2) Como instalar DRIVER da NVIDIA para seu HACKINTOSH em 2022! Nem tudo está perdido para a NVIDIA! https://youtu.be/VRxOzoZajEQ

atenção nos updates que podemr tavar o boot do high sierra sendo necessária a reinicialização.

