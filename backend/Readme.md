# Criar o container 

``` docker build -t goals-node . ```

# startar o container

```docker  run --name goals-backend --rm -p 80:80 goals-node```