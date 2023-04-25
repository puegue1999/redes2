# Laboratório Elan - Manual de acesso ao Docker

Aqui você aprenderá como acessa o containêr com todos os elementos para o seu trabalho.

1. Verificação do Docker:

Para o primeiro passo, veja se o docker está devidamente instalado no seu sistema com o comando:

```
docker version
```

Se for mostrado a versão do docker, o tutorial pode ser continuado.

2. Procure o contêiner:

Para começar o trabalho liste todos os contêiners disponíveis na sua rede com o comando:

```
docker ps
```

Procure o container que gostaria de acessar e copie o seu nome, usaremos ele na próxima etapa.

3. Inicie o contêiner:

Copie o nome do contêiner e o inicie com o camando abaixo.

```
docker start <nome do contêiner>
```

4. Contêiner em execução:

Quando o contêiner executar, digite o comando abaixo.

```
docker exec -i -t <nome do contêiner> /bin/bash
```

5. Executando a imagem:

Com tudo ativado e executando, é possível digitar os comandos para ativar a imagem do contêiner.

Um exemplo de comando será mostrado abaixo.

```
python3 -m http.server 8000
```

6. Parada do contêiner:

Quando tiver feito tudo que quiser no contêiner, digite o seguinte comando e feche o projeto.

```
docker stop <nome do contêiner>
```
