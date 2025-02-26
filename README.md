# Sistema SolidoStore - Visão Geral

Bem-vindo ao repositório central do **Sistema SolidoStore**! Este é o ponto de entrada para entender e acessar todos os componentes que compõem o sistema. O SolidoStore é um aplicativo é a estratégia da Sólido Triade - Comércio e Serviços para o mercado de vendas online (ecommerce).

Sistema Multi-Vendedor, Múltiplos vendedor, em um só lugar. O cliente encontra vários productos de diferentes vendedores em um só lugar (Marketplace).

## Componentes do Sistema

Aqui estão os repositórios que fazem parte do Sistema XYZ:

- **[Frontend](https://github.com/inacio1975/SolidoStore_Frontend)**  
  Repositório contendo a interface de usuário do sistema, construída com React.  
  *Status*: Em desenvolvimento

- **[Backend](https://github.com/inacio1975/SolidoStore_Backend)**  
  Repositório com a lógica de servidor e APIs, desenvolvido em Node.js.  
  *Status*: Em desenvolvimento

- **[Admin](https://github.com/inacio1975/SolidoStore_AdminPanel)**  
  Repositório com a documentação do sistema, incluindo guias de instalação, uso e contribuição.  
  *Status*: Em desenvolvimento

## Como Começar

1. **Clone os repositórios**: Use os links acima para acessar cada componente.  
2. **Siga as instruções locais**: Cada repositório tem seu próprio README com passos para configuração e execução.  
3. **Requisitos gerais**: Certifique-se de ter Node.js e yarn instalados.

## Estrutura do Sistema

O Sistema XYZ funciona da seguinte forma:  
- O **Frontend** e o **Admin** se comunicam com o **Backend** via API REST.  

```mermaid
graph TD
    A[Frontend] -->|API| B[Backend] <-- C[Admin]
    B -->|Referência| D[Documentação]
