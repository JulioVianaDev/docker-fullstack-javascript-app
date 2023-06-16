# dar build 

```docker build -t goals-react .```

# rodar o container 

## indetectavel

```docker run --name goals-frontend --rm -d -p 3000:3000 goals-react```

## detectavel 

```docker run --name goals-frontend --rm -d -p 3000:3000 -it goals-react```