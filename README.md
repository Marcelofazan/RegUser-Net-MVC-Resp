# Registro Conta Usuario AdminLTE

Exemplo de utilização do AdminLte com criação de Conta de Usuário em MVC com banco de dados Mysql acessando por dicionário de dados

* Template AdminLTE 3.2 - 


## Disponivel em (https://adminlte.io/ )

  - [AdminLTE](https://github.com/ColorlibHQ/AdminLTE/archive/refs/tags/v3.2.0-rc.zip)


## Requisitos

Baixar Pacote de Distribuição de Download da Biblioteca e descompactar

Criar uma nova pasta chamada adminlte na raiz do projeto

- Na Pasta AdminLTE-3.2.0-rc /dist -> Copiar as pastas css, img e js e Colar dentro da pasta adminlte
- Na Pasta AdminLTE-3.2.0-rc /plugins -> Copiar as pasta plugins e Colar dentro da pasta adminlte

# O que você vai encontrar neste projeto

- **AdminLTE** - Layout Responsivo JavaScript e uso de biblioteca. 
- **Dicionário de Dados** - Contexto definido realizado manualmente com T-SQL.


## Execução da aplicação

Para executar a aplicação é necessário a execução do Script do MySql. 


## String de conexão do banco


Se já possuir um banco de dados MySql e deseja utilizá-lo na aplicação, modifique a string de conexão no arquivo **Web.config**, no trecho indicado:

```bash
...
		server=127.0.0.1;userid=root;password=SUASENHA;database=SEUBANCO;persistsecurityinfo=True
...

```

O script para criação da tabela do exemplo e alguns dados iniciais encontra-se na pasta **Database**.
