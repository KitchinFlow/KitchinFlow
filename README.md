# KitchinFlow 🍕

> **Status do Projeto:** 🛠️ MVP em desenvolvimento:
> <a href="https://github.com/KitchinFlow"> Repositório Público Atual (apenas intaladores) </a>

O **KitchinFlow** é uma solução administrativa integrada projetada especificamente para o setor alimentício, atendendo desde pizzarias e restaurantes até sorveterias. O objetivo é centralizar a gestão do negócio e automatizar o atendimento ao cliente de forma personalizável. 

## 🚀 Sobre a Solução

O diferencial do KitchinFlow será a união de uma interface robusta, mas de simples operação para o usuário gerenciador com o auxílio de ChatBots e menu online para o consumidor final.

* **(Projeto B2B)**
* **Gestão Administrativa:** Controle total de pedidos, estoque e fluxo de caixa em uma única tela.
* **Automação de Atendimento:** Integração com chatbots de whathsapp para agilizar pedidos e suporte.
* **Flexibilidade:** Adaptável para diferentes nichos do ramo alimentício.

## 🔧 Pré-requisitos do software (Mínimos)
- Sistema operacional ```Windows 10 64-bits``` ou superior;
- .NET 10.0 Desktop Runtime;
- Processador ```2 Núcleos, 2 Threads ```;
- 4GB Memória RAM;
- 1GB de armazenamento disponível em SSD;
<br><br>Os pré-requisitos devem ser atendidos para um bom funcionamento do sistema, mas basicamente qualquer máquina atualmente (salvo raras exceções), cumprem os pré-requisitos listados até com alguma sobra.

## 🛠️ Tecnologias Utilizadas

O projeto utilizará de um stack híbrido para garantir performance e facilidade na automação:

* **Desktop:** [.NET](https://dotnet.microsoft.com/) com **WPF (Windows Presentation Foundation)** para uma interface rica e responsiva.
* **Banco de Dados:** [SQLite](https://www.sqlite.org/) (leve e sem necessidade de servidor externo), mas com API ASP.NET integrada para permitir o uso em mais de uma máquina. 
* **Comandas em qualquer lugar:** Sistema da API gera endpoints com páginas web para que o usuário consiga acessar de qualquer dispositivo com acesso à rede local em que o sistema está inserido, afim de visualizar (e criar), comandas do estabelecimento.
* **Cardápio digital:** Futuramente, a solução contará com site para Cardápio digital do cliente.

## 🔧 Como Executar (Fase de Desenvolvimento)

Atualmente, o projeto está em fase de MVP e requer uma configuração manual simples para o banco de dados:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/KitchinFlow/KitchinFlow/MVP/V1.git
    ```

2.  **Configuração de inicialização:**
    * Crie um perfil de inicialização que abranja as duas soluções do sistema (app desktop e API REST);

3.  **Execução:**
    * Abra a solução no Visual Studio e pressione `F5` ou utilize o comando:
    ```bash
    dotnet run
    ```

## 🛤️ Roadmap (MVP)

- [x] Estrutura base da interface WPF.
- [x] Modelagem inicial do banco de dados SQLite.
- [ ] Implementação do módulo de PDV (Ponto de Venda).
- [ ] Dashboards de fechamento diário.
<br><br>

Desenvolvido por [IzequielAlves](https://github.com/IzequielAlves), [KitchinFlow](https://github.com/KitchinFlow)
