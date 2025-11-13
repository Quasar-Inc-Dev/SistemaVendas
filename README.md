> ```markdown
> # Sistema de Vendas - Java Swing & MySQL
> ```

> 
>
> <p align="center">
> <img src="https://img.shields.io/badge/Java-8+-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java 8+"/>
> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
> <img src="https://img.shields.io/badge/NetBeans-8.2-1B6AC6?style=for-the-badge&logo=apache-netbeans&logoColor=white" alt="NetBeans 8.2"/>
> </p>

> 
>
> -----

> ## Sobre o Projeto

> Este projeto é uma aplicação de desktop para gerenciamento de vendas, desenvolvida em Java com a biblioteca gráfica Swing. O sistema demonstra conceitos fundamentais de desenvolvimento de software, como a criação de interfaces de usuário (UI), a manipulação de eventos e a integração com um banco de dados relacional (MySQL) através de JDBC.

> A arquitetura do projeto separa as responsabilidades em pacotes, contendo as classes da interface (view), os objetos de acesso a dados (DAO) e as classes de modelo (beans), facilitando a manutenção e a compreensão do código.

> 
>
> -----

> ## Principais Funcionalidades

>   * Lançamento de Vendas: Interface intuitiva para criar uma nova nota de venda, selecionando um cliente e adicionando múltiplos produtos.
>   * Integração com Banco de Dados: Carregamento dinâmico de clientes e produtos a partir do banco de dados para preenchimento de componentes da UI.
>   * Gerenciamento de Itens: Adição e exclusão de itens do "carrinho" de vendas antes da persistência final.
>   * Lógica de Negócio no Banco (Triggers): O cálculo do valor total da nota é automatizado por meio de triggers no MySQL, garantindo a consistência dos dados diretamente no banco.

> 
>
> -----

> ## Como Executar

> ### 1\. Pré-requisitos

>   * JDK 8 ou superior
>   * Servidor MySQL (XAMPP, WAMP, etc.)
>   * NetBeans IDE 8.2 ou superior

> ### 2\. Configuração do Banco de Dados

>   * Inicie seu servidor MySQL.
>   * Crie um novo banco de dados com o nome `SisVendas`.
>   * Importe o script SQL contido no arquivo `SisVendas.sql` (disponível na raiz deste repositório) para criar as tabelas e os triggers necessários.

> ### 3\. Configuração do Projeto

>   * Abra o projeto na IDE NetBeans.
>   * Adicione o driver MySQL Connector/J às bibliotecas do projeto.
>   * Verifique e, se necessário, ajuste as credenciais de acesso ao banco de dados na classe de conexão (por padrão, user='root' e password='').

> ### 4\. Execução

>   * Execute o arquivo principal da interface (`CadastroNota.java`) para iniciar a aplicação.

> 
>
> -----
