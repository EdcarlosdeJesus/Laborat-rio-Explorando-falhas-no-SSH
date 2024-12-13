# Laborat-rio-Explorando-falhas-no-SSH

 
### Ferramentas  :hammer_and_wrench:

- Kali Linux :desktop_computer:
- metasploit :space_invader:

Para iniciar nosso ataque iremos usar o comando ```msconsole``` no kali para entrar no metasploit

Logo após inicializar nosso metasploit usaremos o comando ```search ssh_login``` para entrar no ssh que desejamos.

![image](https://github.com/user-attachments/assets/57d973c5-c81b-4e35-b573-6402abd5589e)

Utilizaremos o primeiro , e precisamos de dois arquivos de usuario e senha.

Para realizar o comando apenas digitamos o ```use auxiliary/scanner/ssh/ssh_login```.

---
Precisamos de uma ordelist para que ele possa fazer um teste de força bruta então criei uma pequena apenas para teste.

![image](https://github.com/user-attachments/assets/31ea8c6d-b807-4443-8d8a-de4657784ed6)

---


![image](https://github.com/user-attachments/assets/91b6d47f-0d85-43b6-8656-9418c46f3b2e)


![image](https://github.com/user-attachments/assets/dbe72a76-5543-42c0-87dc-ef9cb2f2ad12)




Colocamos o caminho da nossa wordlist e do nosso ip alvo e dessa forma ele abriu uma seção para que eu me comunicasse com servidor remoto.
![image](https://github.com/user-attachments/assets/7ad93dbe-1e54-4f15-9d21-acafca9056e3)

---
Com a seção aberta escolhemos uma que nos da a oportunidade de caminhar por dentro do nosso alvo como mostra a figura a baixo o ip do alvo como os caminhos que posso pecorrer.

![image](https://github.com/user-attachments/assets/8bb8343b-918e-4a0b-8af2-5b9bedd4e33e)

![image](https://github.com/user-attachments/assets/9d10e6ae-20c9-4a7b-93e3-2407212f07f3)





