# Redis #

Instalando:

``` 
brew install redis

redis-server
```

Ou 

```
docker pull redis

docker run --name some-redis -d redis -p 6379
```


# Conectando no servidor #

Depois de instalar com o redis rodando digite 

redis-cli 

Ele irá conectar no banco do redis e para um teste execute os seguintes comandos:

***Para adicionar uma chave***

```
set "nome_chave" "valor_chave"
```

***Para recuperar uma chave***

```
get "nome_chave"
```


***Para deletar uma chave***

```
del "nome_chave"
```


