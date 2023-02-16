<h1 align="center">Gitnuro é um cliente Git parar Linux</h1>

<p align="center">
  <img alt="Projeto Habits" src=".github/preview.png" width="100%">
</p>

<h2 align="center">Sobre o Gitnuro</h2>
<p>O principal objetivo do Gitnuro é fornecer um cliente Git de código aberto multiplataforma sem qualquer tipo de restrição de como você pode usá-lo nem depender de tecnologias da web.</p>

<h2 align="center">Instalando o Gitnuro no Linux:</h2>
<hr>

**Istale o flatpak:**
```
sudo apt install flatpak
```

**Instale o Plugin flatpak**
```
sudo apt install gnome-software-plugin-flatpak
```

**Instale o GitNuro**
```
flatpak install flathub com.jetpackduba.Gitnuro
```

<h3 align="center"><strong>Abrindo o Gitnuro</strong></h3>
<p align="center">Existem duas maneiras para você abrir o Gitnuro</p>

A primeira maneira é digitando no seu terminal o seguinte comando:
```
flatpak run com.jetpackduba.Gitnuro
```
Podemos observar que escrever esse comando toda hora fica um pouco "chato", então temos uma segunda maneira muito mais fácil, so super usuário do seu sistema, podemos abrir um editor de texto como o *vi* ou *vim* o arquivo *.bashrc* e digitar o seguinte comando:
```
alias gitnuro="flatpak run com.jetpackduba.Gitnuro" 
```
Ele faz o comando ser executado quando digitarmos a palavra ***gitnuro***

<h2 align="center">Links oficiais do Gitnuro:</h2>
<hr>
<p align="right">
  <a href="https://gitnuro.jetpackduba.com/">Site Oficial</a>
</p>
<p align="right">
  <a href="https://github.com/JetpackDuba/Gitnuro">GitHub</a>
</p>
<p align="right">
  <a href="https://git-scm.com/download/gui/linux">Outros GUI Clients</a>
</p>