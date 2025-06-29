To jest wersja doskonałego monitora napisanego przez Mustafę Parkera dla SBC Granta Searle http://searle.x10host.com/z80/SimpleZ80.html.  
Monitor umożliwia pisanie kodu asemblera w locie używając mnemoników Z80, deasemblować do postaci kodu, zrzucać obszary pamięci, ładować pliki itp.  
Moja robota polegała tylko na podmianie dwóch funkcji TXD oraz RXD do obsługi układu portu szeregowego MC6850.
Kod pobrałem z strony https://gitlab.com/8bitforce/retroshield-arduino/-/blob/fa79d49e44722a4271b96efe306ba491e47695e2/kz80/kz80_efex/firmware/efex.asm  
Program należy nagrać na kostkę EPROM i podmienić w SBC.
