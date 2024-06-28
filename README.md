# Mini Aplicativo de Linha de Comando em Golang

Este é um mini aplicativo de linha de comando desenvolvido em Golang, que permite buscar o IP e os servidores associados a um host informado. 

## Funcionalidades

O aplicativo possui dois comandos básicos:
1. **Buscar IP**: Busca o IP de acordo com o host informado.
2. **Buscar Servidores**: Busca os servidores associados ao host.

## Instalação

Para instalar o aplicativo, você precisa ter o Go instalado em sua máquina. Siga os passos abaixo:

1. Clone este repositório:
    ```sh
    git clone https://github.com/diego-ronan-felix/busca-ip-e-servidores.git
    ```
2. Acesse o diretório do projeto:
    ```sh
    cd busca-ip-e-servidores
    ```
3. Compile o aplicativo:
    ```sh
    go build 
    ```

## Uso

Após a instalação, você pode usar os seguintes comandos:

### Buscar IP

Para buscar o IP de um host específico, utilize o comando abaixo:
```sh
./linha-de-comando ip --host sitequalquer.com.br
```

### Buscar Servidores

Para buscar os servidores de um host específico, utilize o comando abaixo:
```sh
./linha-de-comando servidores --host sitequalquer.com.br
```
