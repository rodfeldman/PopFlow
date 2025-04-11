# POPflow

Sistema de gerenciamento de Procedimentos Operacionais Padrão (POPs) para empresas de varejo, desenvolvido para a consultoria Caos a Liberdade.

## Sobre o Projeto

O POPflow é uma plataforma SaaS que permite aos usuários criar, gerenciar e compartilhar Procedimentos Operacionais Padrão (POPs) de forma intuitiva e eficiente. O sistema utiliza inteligência artificial para ajudar na criação de procedimentos completos e estruturados a partir de informações básicas fornecidas pelo usuário.

### Principais Funcionalidades

- Criação guiada de POPs usando assistente com IA
- Organização por departamentos/setores
- Visualização em formato de documento e fluxograma
- Compartilhamento e controle de versões
- Exportação para PDF e Google Docs
- Dashboard intuitivo para gerenciamento

## Tecnologias Utilizadas

- React.js
- Tailwind CSS
- Firebase (Autenticação, Firestore, Storage)
- OpenAI API / Anthropic API

## Instalação e Configuração

### Pré-requisitos

- Node.js (v14 ou superior)
- NPM ou Yarn
- Conta Firebase
- Chave de API OpenAI ou Anthropic

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/popflow.git
cd popflow
```

2. Instale as dependências:
```bash
npm install
```

3. Configure as variáveis de ambiente:
   - Renomeie o arquivo `.env.example` para `.env.local`
   - Preencha as variáveis com suas credenciais

4. Inicie o servidor de desenvolvimento:
```bash
npm run dev
```

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## Contato

Para mais informações sobre a consultoria Caos a Liberdade ou sobre este projeto, entre em contato através do [website](https://caosaliberdade.com) ou email.
