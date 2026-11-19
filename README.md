# 🧭 Compass — Gestão de Crises e Apoio a Vítimas de Desastres Ambientais

\<p align="center">   \<img src="docs/screenshots/banner.png" alt="Banner do Compass" width="100%"> \</p>

\<p align="center">   \<strong>Conectando pessoas, organizando recursos e fortalecendo comunidades em situações de emergência.\</strong> \</p>

\<p align="center">   \<img src="[https://img.shields.io/badge/Status-Em%20desenvolvimento-2E8B57?style=for-the-badge](https://img.shields.io/badge/Status-Em%20desenvolvimento-2E8B57?style=for-the-badge)" alt="Status">   \<img src="[https://img.shields.io/badge/PHP-8.1%2B-777BB4?style=for-the-badge&logo=php&logoColor=white](https://img.shields.io/badge/PHP-8.1%2B-777BB4?style=for-the-badge\&logo=php\&logoColor=white)" alt="PHP">   \<img src="[https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white](https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge\&logo=mysql\&logoColor=white)" alt="MySQL">   \<img src="[https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)" alt="JavaScript"> \</p>

---

## 📌 Sobre o projeto

O **Compass** é uma plataforma web desenvolvida com o propósito de auxiliar na gestão de crises ambientais e oferecer suporte às pessoas afetadas por desastres naturais.

A aplicação busca centralizar informações, facilitar a comunicação entre cidadãos, organizações não governamentais (ONGs) e administradores, além de organizar solicitações de ajuda, denúncias, recursos e pontos de apoio.

A plataforma possui uma área pública e ambientes internos destinados a diferentes perfis de usuários, proporcionando uma experiência organizada de acordo com as responsabilidades de cada participante.

## 🌎 Problema que o projeto busca resolver

Em situações de desastres ambientais, como enchentes, alagamentos e deslizamentos, a comunicação e a organização dos recursos são fundamentais para agilizar o atendimento às comunidades afetadas.

Entretanto, informações descentralizadas, dificuldades de comunicação e falta de organização podem comprometer a identificação das necessidades e a distribuição de ajuda.

O Compass surge como uma proposta tecnológica para centralizar essas informações e facilitar a integração entre pessoas, organizações e equipes responsáveis pelo atendimento das ocorrências.

## 🎯 Objetivo da plataforma

Desenvolver um sistema que facilite a gestão de crises ambientais por meio da centralização de informações e da comunicação entre os envolvidos.

Entre seus objetivos estão:

- Facilitar o registro e acompanhamento de solicitações de ajuda.
- Permitir o registro e a verificação de denúncias.
- Aproximar cidadãos e organizações de apoio.
- Organizar recursos e movimentações de estoque.
- Divulgar alertas e informações relevantes.
- Disponibilizar pontos de apoio.
- Facilitar a comunicação entre usuários.

## ⚙️ Funcionalidades

### 🌐 Área pública

- Página inicial com informações sobre a plataforma.
- Divulgação de avisos e comunicados.
- Exibição de alertas meteorológicos.
- Visualização de pontos de apoio.
- Publicações e avaliações da comunidade.
- Cadastro e autenticação de usuários.

### 👤 Área do cidadão

- Gerenciamento de perfil e endereço.
- Registro de solicitações de ajuda.
- Registro e acompanhamento de denúncias.
- Consulta de avisos e publicações.
- Participação na comunidade.
- Envio de avaliações.
- Chat para comunicação com outros usuários.

### 🏢 Área das ONGs

- Ambiente destinado às organizações cadastradas.
- Cadastro sujeito à aprovação administrativa.
- Gerenciamento de informações do perfil.
- Participação nos recursos de comunicação da plataforma.

### 🛡️ Área administrativa

- Dashboard de gerenciamento.
- Gestão de usuários e organizações.
- Moderação de denúncias.
- Gerenciamento de alertas e comunicados.
- Gerenciamento de publicações e conteúdo do site.
- Controle de recursos e estoque.
- Histórico de movimentações.
- Gerenciamento de avaliações.
- Relatórios e acompanhamento de informações.
- Chat e notificações.

## 🖥️ Demonstração visual

As imagens abaixo apresentam os principais ambientes da plataforma.

### Página inicial



### Autenticação



### Dashboard administrativo



### Painel do cidadão



### Painel das ONGs



### Comunicação e chat



### Pontos de apoio



> As imagens de demonstração serão adicionadas conforme a documentação visual do projeto for organizada.

## 🛠️ Tecnologias utilizadas

As principais tecnologias utilizadas no desenvolvimento são:

\<p align="left">   \<img src="[https://skillicons.dev/icons?i=html,css,js,php,mysql,git,github,vscode](https://skillicons.dev/icons?i=html,css,js,php,mysql,git,github,vscode)" alt="Tecnologias utilizadas"> \</p>

| Tecnologia      | Utilização                                   |
| --------------- | -------------------------------------------- |
| HTML5           | Estrutura das páginas                        |
| CSS3            | Estilização e responsividade                 |
| JavaScript      | Interatividade e funcionalidades do frontend |
| PHP             | Backend e processamento das requisições      |
| MySQL / MariaDB | Armazenamento e gerenciamento dos dados      |
| Git             | Controle de versão                           |
| GitHub          | Hospedagem do código-fonte                   |

## 📁 Estrutura do projeto

A organização principal dos arquivos está dividida em módulos:

```text
compass/
│
├── api/
│   ├── admin/
│   ├── auth/
│   ├── includes/
│   ├── clima.php
│   ├── sistema.php
│   └── upload.php
│
├── assets/
│   ├── css/
│   │   ├── admin/
│   │   ├── cidadao/
│   │   ├── site/
│   │   └── solicitacoes/
│   │
│   ├── img/
│   │   ├── admin/
│   │   ├── cidadao/
│   │   ├── site/
│   │   └── solicitacoes/
│   │
│   └── js/
│       ├── admin/
│       ├── cidadao/
│       └── site/
│
├── database/
│   ├── migrations/
│   └── compass.sql
│
├── pages/
│   ├── admin/
│   ├── cidadao/
│   ├── ong/
│   └── ...
│
├── tests/
│
├── index.php
└── README.md
```

## 💻 Requisitos para instalação

Para executar o projeto localmente, são necessários:

- Windows, Linux ou macOS.
- PHP 8.1 ou superior.
- MySQL 5.7+ ou MariaDB 10.3+.
- Apache.
- Extensões PHP: PDO MySQL, MBString e OpenSSL.
- Navegador atualizado.
- XAMPP ou ambiente equivalente.

## 🚀 Como executar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/SouzaGuui/Compass.git
```

### 2. Acessar a pasta

```bash
cd Compass
```

### 3. Configurar o servidor

Se estiver utilizando XAMPP:

- Copie a pasta do projeto para `C:\xampp\htdocs\compass`.
- Abra o painel do XAMPP.
- Inicie os serviços Apache e MySQL.

### 4. Configurar o banco de dados

- Acesse `http://localhost/phpmyadmin`.
- Crie ou selecione o banco de dados `compass`.
- Importe o arquivo `database/compass.sql`, utilizando uma versão de demonstração previamente sanitizada.

### 5. Configurar a conexão

Configure as variáveis de ambiente ou os parâmetros locais de conexão:

```env
COMPASS_DB_HOST=localhost
COMPASS_DB_NAME=compass
COMPASS_DB_USER=root
COMPASS_DB_PASS=
```

Para o envio de e-mails, configure também as variáveis SMTP necessárias, conforme a documentação do projeto.

**Atenção:** não publique senhas, credenciais SMTP ou dados pessoais no repositório.

### 6. Acessar a aplicação

Abra o navegador e acesse:

```text
http://localhost/compass/
```

## 🗄️ Banco de dados

O Compass utiliza MySQL/MariaDB para armazenar as informações da plataforma.

O banco de dados é responsável por organizar informações relacionadas a:

- Usuários e perfis.
- Solicitações de ajuda.
- Denúncias e histórico de atualizações.
- Alertas e comunicados.
- Organizações.
- Recursos e movimentações de estoque.
- Mensagens e conversas.
- Publicações e interações.
- Avaliações.
- Pontos de apoio.

O projeto também possui arquivos de migrations para atualização da estrutura do banco de dados.

## 🔐 Segurança

O sistema possui mecanismos de proteção e controle de acesso, incluindo:

- Autenticação por sessão.
- Controle de permissões conforme o perfil.
- Proteção CSRF.
- Validação de dados.
- Confirmação de e-mail.
- Recuperação de senha por código.
- Validação de arquivos enviados.
- Restrição de acesso às funcionalidades administrativas.

## 🎓 Contexto acadêmico

O Compass foi desenvolvido como projeto acadêmico no contexto do curso Técnico em Desenvolvimento de Sistemas do SENAI-SP.

O projeto tem como finalidade aplicar conhecimentos de desenvolvimento web, programação, banco de dados, organização de sistemas e resolução de problemas por meio da tecnologia.

**Instituição:** SENAI-SP
**Curso:** Técnico em Desenvolvimento de Sistemas
**Ano:** 2026
**Categoria:** Projeto acadêmico

### Integrantes e colaboradores

- **Desenvolvimento:** Guilherme Souza
- **Colaboradores:** [Adicionar nomes, se aplicável]
- **Orientação:** [Adicionar nome do orientador, se aplicável]

## 📈 Status do desenvolvimento

O Compass encontra-se em desenvolvimento contínuo.

Novas funcionalidades, melhorias de interface, ajustes técnicos e aprimoramentos de segurança podem ser incorporados ao longo da evolução do projeto.

## 📄 Licença

Projeto desenvolvido para fins acadêmicos.

A utilização, reprodução ou distribuição do código deve respeitar as condições de autorização dos autores e colaboradores.

---

\<p align="center">
&#x20; \<strong>🧭 Compass — Tecnologia, organização e apoio para comunidades.\</strong>
\</p>

\<p align="center">
&#x20; Desenvolvido com dedicação em 2026.
\</p>
