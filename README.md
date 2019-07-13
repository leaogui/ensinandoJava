# LEIAM ANTES DE COMEÇAR!

# ensinandoJava
Ensinando um pouco do Java pro pessoal do IF e alguns amiguinhos.

Link do primeiro episódio no YouTube: https://www.youtube.com/watch?v=knqAEvmCbjg&feature=youtu.be

Lembrando que também comecei a pouco tempo no Java, então além disso vamos aprender muitas coisas juntos.

# Pontos extras:

No vídeo, como eu disse, não tenho certeza se é necessário, porém instalem o Java e o JDK (Java Development Kit), são importantes para desenvolver, mesmo que a IDE já resolva tudo.

Enviem de alguma forma o feedback, só pra eu saber o que deve melhorar para ensinar do melhor jeito pra vocês.

## Usando o GIT no IF.

Precisamos configurar o proxy no IF para usar o GIT.

Os comandos são:

-- git config --global http.proxy IP

-- git config --global https.proxy IP

## Como linkar um repositório local com um repositório no GitHub

-- git remote add origin urldoprojetoaqui.git

## Dando push no git 

Primeiramente precisamos adicionar o que vai no nosso commit.

-- git add .

Após isso, vamos fazer o próprio commit.

-- git commit -m (para adicionar uma mensagem) "O que mudei no projeto"

Com nosso commit feito podemos enviar para o GitHub (Lembrando, commitem alterações importantes de pouco em pouco tempo. Não é uma boa prática fazer um commit com mudanças gigantes, como fazer o projeto inteiro em um commit, pois com eles você pode corrigir erros.)

-- git push -u origin master

(nisso estamos enviando para o branch master do nosso repositório, entraremos em detalhes sobre branches nos vídeos.)

## Como pegar as alterações para um repositório local

-- git pull

## Como trabalhar com um repositório em um local novo

-- git clone url.git

(Com isso clonamos o repositório já iniciado no local novo, e podemos trabalhar direto com pull e push.)