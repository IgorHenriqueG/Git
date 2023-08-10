# Comandos GIT

- Login
```
(Entre aspas insira seu nome de usuário do github)
git config --global user.name "Seu Usuário" 



(Entre aspas insira seu email da conta git)
git config --global user.email "Seu Email"
```
- Comandos de clone & pull
```
(Clona um repositório do git ao seu computador) 
git clone (link) 

(Atualiza um repositório já existente em seu computador)
git pull
```
- Comandos de push
```
(Menciona a pasta .git para referenciar o repositório a ser atualizado)
git add .


(entre aspas insira a mensagem que deseja ser exibida ao atualizar o repositório)
git commit -m "mensagem"


(Envia as atualizações de seu computador ao repositório git)
git push
```

- Exemplo dos comandos.
    - 1- Git Login
    - 2- Git clone & pull
    - 3- Git push

<br>

Utilize GitBash para executar os comandos.

|GitBash|
|--|

- 1 - Git login
    - git config --global user.name " "
    ![GitLogin1](https://github.com/IgorHenriqueG/Git/assets/111847209/ff1c0329-8547-4a78-a3b0-74d2dc558896)

    - git config --global user.email " "
    ![GitLogin2](https://github.com/IgorHenriqueG/Git/assets/111847209/c7c364c4-5b15-4461-b1aa-ed2b463a164e)

<br>
<hr>
<br>

- 2 - Git clone & pull
    - Git clone

    Utilize caso você ainda NÃO possua seu repositório em seu computador
    - Vá ao repositório criado em seu github

    ![Screenshot_1](https://github.com/IgorHenriqueG/Git/assets/111847209/8683280d-8286-4e03-b6ad-1166253d21fb)

    - Copie o código de seu repositório

    ![Screenshot_2](https://github.com/IgorHenriqueG/Git/assets/111847209/41102a35-e921-4eb0-b525-cf9834d724dc)

    Após copiado o código de seu repositório com o botão direito abra o gitbash no local em que deseja seu repositório

    ![GitCloneOP](https://github.com/IgorHenriqueG/Git/assets/111847209/9d819df4-84a0-4e52-ae38-330b38067fb2)


    Com o GitBash aberto utilize o comando git clone e cole sua url

    - git clone (url)
    ![Screenshot_3](https://github.com/IgorHenriqueG/Git/assets/111847209/413a0a0f-231b-4315-95c3-3b67d332741d)

    Após concluido será criada uma pasta com o nome de seu repositório
    ![Screenshot_4](https://github.com/IgorHenriqueG/Git/assets/111847209/d5d5566a-b3e4-4212-85e8-e10eb4e27a70)

    Dentro dessa pasta você poderá colocar seus arquivos a serem enviados para seu repositório

<br>
<br>

- 2 - Git clone & pull
    - git pull

    Abra o Gitbash dentro da pasta de seu repositório, no mesmo local que a pasta oculta .git

    Caso não veja a pasta .git tenha certeza que a opção de itens ocultos está ativada
    ![Screenshot_5](https://github.com/IgorHenriqueG/Git/assets/111847209/2d8ddcf1-8dbd-4790-9355-5487f1e4de68)

    No mesmo local que sua .git abra o GitBash com o botão direito

    ![Screenshot_6](https://github.com/IgorHenriqueG/Git/assets/111847209/b8ce8597-12e7-410f-8e10-a52de3c258f7)

    Para atualizar de seu repositório git para seu computador utilize o commando git pull, este comando puxa somente itens que você tem de diferentes entre seu repositório e seu computador

    ![Screenshot_7](https://github.com/IgorHenriqueG/Git/assets/111847209/d5bc972d-89b1-471c-ad98-fb51ed469248)

<br>
<hr>
<br>

```diff
- Os comandos de push devem ser usados em ordem
```

- 3 - git push
    - git add .

    Para enviar arquivos de seu computador ao repositório git utilize git add . no mesmo local que a pasta oculta .git

    No mesmo local que sua .git abra o GitBash com o botão direito
    ![Screenshot_6](https://github.com/IgorHenriqueG/Git/assets/111847209/b8ce8597-12e7-410f-8e10-a52de3c258f7)

    Primeiramente utilize o comando git add .
    ![Screenshot_8](https://github.com/IgorHenriqueG/Git/assets/111847209/6438b03d-f616-4bca-95cc-0db99f78b61a)

    - git commit -m " "

    Após utilize o comando git commit -m " " para adicionar uma mensagem a push de seu repositório
    ![Screenshot_10](https://github.com/IgorHenriqueG/Git/assets/111847209/b7ef71ab-a562-4fe4-8346-7c1903cf8154)

    - git push

    Utilize o comando git push quando quiser enviar os arquivos de seu pc ao repositório git
    ![Screenshot_11](https://github.com/IgorHenriqueG/Git/assets/111847209/3677ceed-1c52-42a5-864a-b2d32b124c0a)

```diff
- Os comandos de push devem ser usados em ordem
```