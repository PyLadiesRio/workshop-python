# Introdução a linha de comando

A janela, que normalmente é chamada de linha de comando ou interface de linha de comando, é um aplicativo baseado em texto para visualização, manipulação e manuseio de arquivos em seu computador (como por exemplo, o Windows Explorer ou o Finder no Mac, mas sem interface gráfica). Outros nomes para a linha de comando são: __cmd, CLI, prompt, console__ ou __terminal__.

Para conhecer um pouco mais sobre a linha de comando, vamos abri-la.

## Windows
Vá em Iniciar → Todos os Programas → Acessórios → Prompt de comando.

## Linux

### Sistemas com interface GNOME
Vá para o menu Atividades → Digite para pesquisar _Terminal_.

### Sistemas com interface KDE
Vá para Aplicativos → Acessórios → Terminal

## Mac OS X
Vá em Aplicativos → Utilitários → Terminal

Agora você deve ver uma janela branca ou preta que está à espera de seus comandos.
Se você estiver em Mac ou num Linux, você provavelmente verá um __$__, como este:
```sh
$
```

No Windows, é um sinal de __>__, como este:
```sh
>
```

## Conhecendo a linha de comando
Vamos começar com algo simples. Digite o seguinte comando:
```sh
> whoami
```

Depois aperte _Enter_. Devemos ver algo parecido com:
```sh
> whoami
jusbrasil
```

Como você pode ver, o computador só apresentou seu nome de usuário.

## Alguns comandos básicos

### Windows


#### Listando conteúdo da pasta atual
```sh
> dir
Directory of C:\Users\pgrangeiro
05/08/2014 07:28 PM <DIR>      Applications
05/08/2014 07:28 PM <DIR>      Desktop
05/08/2014 07:28 PM <DIR>      Downloads
05/08/2014 07:28 PM <DIR>      Music
```

#### Listando conteúdo da pasta atual | UNIX
```sh
> ls
Applications	Documents	Library		Music		Public
Desktop		Downloads	Movies		Pictures
```

#### Entrando em outra pasta
```sh
> cd Desktop
```

#### Criando uma pasta
```sh
> mkdir workshop-python
```

### Linux e Mac OS

#### Listando a pasta atual
```sh
$ pwd
/home/pgrangeiro
```

#### Listando conteúdo da pasta atual
```sh
$ ls
Applications
Desktop
Downloads
Music
```

#### Entrando em outra pasta
```sh
$ cd Desktop
```

#### Criando uma pasta
```sh
$ mkdir workshop-python
```

## Exercitando-se
Um pequeno desafio para você: na sua mais nova pasta criada _workshop-python_, crie uma outra pasta chamada _teste_. Use os comandos _cd_ e _mkdir_.

### Solução
Windows:
```sh
> cd workshop-python
> mkdir teste
> dir
05/08/2014 07:28 PM <DIR>      teste
```

Linux e Mac OS:
```sh
$ cd workshop-python
$ mkdir teste
$ ls
teste
```
