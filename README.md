# KitchinFlow
![logo do app](https://github.com/IzequielAlves/KitchinFlow/blob/Develop/Assets/Color%20Icon%20NoBG.png)

# KitchinFlow 🍕

> **Status do Projeto:** 🛠️ MVP em Desenvolvimento

O **KitchinFlow** é uma solução administrativa integrada projetada especificamente para o setor alimentício, atendendo desde pizzarias e restaurantes até sorveterias. O objetivo é centralizar a gestão do negócio e automatizar o atendimento ao cliente.

## 🚀 Sobre a Solução

O diferencial do KitchinFlow é a união de uma interface robusta para o gerenciador com a inteligência de chatbots para o consumidor final.

* **Gestão Administrativa:** Controle total de pedidos, estoque e fluxo de caixa.
* **Automação de Atendimento:** Integração com chatbots para agilizar pedidos e suporte.
* **Flexibilidade:** Adaptável para diferentes nichos do ramo alimentício.

## 🔧 Pré-requisitos do software (Mínimos)
- Sistema operacional ```Windows 10 64-bits``` ou superior;
- .NET 10.0 Desktop Runtime;
- Processador 2 Núcleos, 2 Threads;
- 4GB Memória RAM;
- 1GB de armazenamento disponível;

## 🛠️ Tecnologias Utilizadas

O projeto utiliza um stack moderno e híbrido para garantir performance e facilidade de automação:

* **Desktop:** [.NET](https://dotnet.microsoft.com/) com **WPF (Windows Presentation Foundation)** para uma interface rica e responsiva.
* **Banco de Dados:** [SQLite](https://www.sqlite.org/) (leve e sem necessidade de servidor externo).
* **Automação & Inteligência:** [Python](https://www.python.org/) e [N8N](https://n8n.io/) para a orquestração de fluxos e chatbots.

## 🔧 Como Executar (Fase de Desenvolvimento)

Atualmente, o projeto está em fase de MVP e requer uma configuração manual simples para o banco de dados:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/IzequielAlves/KitchinFlow.git
    ```

2.  **Configuração do Banco de Dados:**
    * Localize o arquivo do banco de dados (`database.db`). (encontra-se por padrão na pasta Data).
    * Copie o arquivo para a pasta de saída do compilador: `.../bin/Debug/net10.0-windows/` (ou a versão do .NET que estiver usando).
    * **Importante:** O banco deve estar no mesmo diretório que o executável (`KitchinFlow.exe`), pois o sistema está configurado para realizar a conexão relativa automaticamente.

3.  **Execução:**
    * Abra a solução no Visual Studio e pressione `F5` ou utilize o comando:
    ```bash
    dotnet run
    ```

## 🛤️ Roadmap (MVP)

- [x] Estrutura base da interface WPF.
- [x] Modelagem inicial do banco de dados SQLite.
- [ ] Implementação do módulo de PDV (Ponto de Venda).
- [ ] Integração dos fluxos N8N com o banco de dados local.
- [ ] Dashboards de fechamento diário.

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE).

---
Desenvolvido por [IzequielAlves](https://github.com/IzequielAlves)
