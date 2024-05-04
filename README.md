# Docker com Python
O intuito deste repositorio é de ser utilizado em uma Oficina de docker que estou aplicando para a turma da ADS da ETEC de Atibaia e de Bragança PT.

Nesta Oficina  estarei ensinando os conceitos por trás do Docker e como utilizar o docker da melhor forma.

## Pré Requisitos
- Docker Instalado ( https://www.docker.com/products/docker-desktop/ )
- Cli do Git Instalado( https://github.com/git-guides/install-git )

## Como Utilizar
- Clone o Repositório
```Shell
git clone https://github.com/AleTavares/dockerPython.git
```

- Acesse a pasta do projeto
```shell
cd dockerPython
```

- Criar imagem docker
```
docker build -t oficinaDocker .
```

- Inicialize a Maquina Docker
```
docker-compose -f docker-compose.yml up -d
```

## Links Uteis
- Docker Hub ( https://hub.docker.com/ )
- Documentação Docker ( https://docs.docker.com/reference/ )
- Shell Script ( http://www.inf.ufes.br/~vitorsouza/archive/2020/wp-content/uploads/teaching-lp-20132-seminario-shell.pdf )

