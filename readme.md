# Conceitos de Git e Github

Este arquivo tem como objetivo armazenar os comandos básicos para utilização
de Git e Github

## Configuração inicial
Rode os comandos abaixo no terminal(cmd) do seu computador.
```bash
git confi --global user.name "Jose Navarro Alves Junior"

git confi --global user.email jose.alves57@fatec.sp.gov.br
``` 

## Comando do Git
Para iniciar o Git em uma pasta do computador utilizamos o init.
**IMPORTANTE**: Só é exucutado  vez.

```bash
git init
```
Para vincular o projeto ao Github utilizamos o comando remote, basta o repositório estar criado no github e seguir a segunda opção da lista de comandos que aparece no site.
**IMPORTANTE** Depois do remote dese ser executados os outros 2 comandos da página
```bash
git remote add origin < url_github >
```

Para verificar a situação do repositório (pasta)
usamos o status a qualquer momento.
```bash
git status
```

Para adicionar os arquivos (versionamento).
```bash
git add .
```

Para salvar os arquivos no repositório.
```bash
git commit -m "Criação do Arquivo"
```



Para baixar as alterações que estão apenas no Github utilizamos o pull.<br>
**IMPORTANTE** Sempre deve baixar a ultima versão da nuvem antes de enviar a atual do computador
```bash
git pull
```

Enviar os commits do pc para o Github utilizamos o push.
```bash
git push
```

Baixa o repositório do Github em um novo computador utilizamos o clone.
```bash
git clone < url_repositorio_github >
```