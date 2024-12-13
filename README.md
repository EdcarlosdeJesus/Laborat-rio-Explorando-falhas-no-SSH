# Laborat-rio-Explorando-falhas-no-SSH

 
### Ferramentas  :hammer_and_wrench:

- Kali Linux :desktop_computer:
- metasploit :space_invader:
- SSH

➡️ Para iniciar nosso ataque iremos usar o comando ```msconsole``` no kali para entrar no metasploit

Logo após inicializar nosso metasploit usaremos o comando ```search ssh_login``` para entrar no ssh que desejamos.

![image](https://github.com/user-attachments/assets/57d973c5-c81b-4e35-b573-6402abd5589e)

➡️ Utilizaremos o primeiro , precisamos de dois arquivos de usuario e senha.

➡️ Para realizar o comando apenas digitamos o ```use auxiliary/scanner/ssh/ssh_login```.

---
➡️Foi preciso de uma wordlist para que ele possa fazer o teste de força bruta, por essa razão foi criada uma pequena lista apenas para tal função.

<img src="https://github.com/user-attachments/assets/31ea8c6d-b807-4443-8d8a-de4657784ed6" width="400"/>


---


➡️ Foi realizado o caminho da wordlist e do ip alvo e dessa forma ele abriu uma seção para que eu me comunicasse com servidor remoto.

![image](https://github.com/user-attachments/assets/7ad93dbe-1e54-4f15-9d21-acafca9056e3)


---
➡️ Com a seção aberta, será possivel caminhar por dentro do alvo, como mostra a figura a baixo o ip do alvo como os caminhos que pode pecorrer dentro da máquina atacada.

<img src="https://github.com/user-attachments/assets/8bb8343b-918e-4a0b-8af2-5b9bedd4e33e" width="400"/>


<img src="https://github.com/user-attachments/assets/9d10e6ae-20c9-4a7b-93e3-2407212f07f3" width="400"/>






