# Vendas
repositorioVendas
C:\testevendas>git clone git@github.com:cwbedsonmoreira/Vendas.git
Cloning into 'Vendas'...
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (4/4), done.

C:\testevendas>dir
 O volume na unidade C é Acer
 O Número de Série do Volume é 9028-A48E

 Pasta de C:\testevendas

13/09/2021  21:54    <DIR>          .
13/09/2021  21:54    <DIR>          ..
13/09/2021  21:54    <DIR>          Vendas
               0 arquivo(s)              0 bytes
               3 pasta(s)   757.549.367.296 bytes disponíveis

C:\testevendas>cd Vendas

C:\testevendas\Vendas>git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

C:\testevendas\Vendas>git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        teste.txt

nothing added to commit but untracked files present (use "git add" to track)

C:\testevendas\Vendas>git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        teste.txt

nothing added to commit but untracked files present (use "git add" to track)

C:\testevendas\Vendas>git add .

C:\testevendas\Vendas>git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   teste.txt


C:\testevendas\Vendas>git commit -m "primeiro arquivo"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'cwbed@LAPTOP-6B2BOKN1.(none)')

C:\testevendas\Vendas> git config --global user.email "cwbedson@gmail.com"

C:\testevendas\Vendas>git commit -m "primeiro arquivo"
[main 5f28875] primeiro arquivo
 1 file changed, 1 insertion(+)
 create mode 100644 teste.txt

C:\testevendas\Vendas>git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 322 bytes | 161.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:cwbedsonmoreira/Vendas.git
   b7fc381..5f28875  main -> main

C:\testevendas\Vendas>git pull
Already up to date.

C:\testevendas\Vendas>git pull
Already up to date.

C:\testevendas\Vendas>git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 661 bytes | 3.00 KiB/s, done.
From github.com:cwbedsonmoreira/Vendas
   5f28875..8854554  main       -> origin/main
Updating 5f28875..8854554
Fast-forward
 teste.txt | 1 +
 1 file changed, 1 insertion(+)

C:\testevendas\Vendas>
