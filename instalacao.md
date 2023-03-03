# Instalação

Nós vamos usar a versão mais recente do Python, então precisamos instalá-lo.

## Windows
Você pode baixar o Python para Windows [aqui](https://www.python.org/downloads/). Depois de fazer o download do arquivo *.msi, você precisa executá-lo (dando um duplo-clique nele) e seguir as instruções. É importante lembrar o caminho (a pasta) onde você instalou o Python. Ela será útil depois!

Atenção: na segunda tela do assistente de instalação, marque a opção _Customize_ e certifique-se de rolar para baixo e escolher a opção _Adicionar python.exe para ao Path_.
![Adicionando Python ao Path](/images/windows-python-path.png)

## Linux
Em muitas distribuições Linux, o Python já vem pré instalado. Para verificar se ele se encontra na sua máquina, abra o terminal e digite:

```sh
python --version
```

Caso ele não esteja instalado, seguem os comandos de instalação de acordo com algumas distribuições:

### Distribuições Red Hat (Fedora, CentOS)

```sh
sudo dnf install python
```

### Distribuições Debian (Debian, Ubuntu)

```sh
sudo apt-get install python
```

### Distribuições Arch (Arch, Manjaro)

```sh
sudo pacman -S python
```

## Mac OS
Primeiro, você deve baixar o instalador do Python que pode ser encontrado [aqui](https://www.python.org/downloads/release/python-342/). Depois de realizar o download, dê um duplo-clique para abri-lo e dê um duplo-clique no Python.mpkg para executar o instalador. Verifique se a instalação foi bem sucedida abrindo o terminal e digitando o comando:

```sh
python --version
```
