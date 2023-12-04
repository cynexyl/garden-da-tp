---
{"dg-publish":true,"permalink":"/como-instalar-o-syncthing/"}
---

# Syncthing
O Syncthing é um software que sincroniza pastas entre diferentes aparelhos.
No caso, utilizamos ele para que a vault do Obsidian seja compartilhada entre todos os usuários.

### Download e Instalação
Utilizaremos uma versão com GUI do Syncthing pra maior facilidade de uso.

[SyncTrayzor](https://github.com/canton7/SyncTrayzor/releases/tag/v1.1.29) (Windows)
[syncthing-macos](https://github.com/syncthing/syncthing-macos/releases/latest) (MacOS)

>[!info] 
>Usando o Homebrew pelo terminal: 
>`brew install --cask syncthing`

### Configuração
Após a Instalação, abra a UI web do Syncthing, clique em "Add Remote Device" e coloque o Device ID indicado. 


![Pasted image 20231204184330.png](/img/user/Images/Pasted%20image%2020231204184330.png)

Com isso, a pasta da vault deve sincronizar e aparecer localmente no seu dispositivo.

Tendo isso feito, basta abrir a pasta como uma vault no Obsidian.

![Pasted image 20231204184702.png](/img/user/Images/Pasted%20image%2020231204184702.png)