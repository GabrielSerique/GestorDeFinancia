# GestorDeFinancia
Gestor de Financias - (uso pessoal/portifólio) 

Este projeto vai ser feito inteiramente com a ajuda do chatGPT! 

Meu intuito com ele é colocar a mão na masssa. Apesar de eu utilizar IA como auxilio, acredito que ao decorrer do projeto irei me deparar com problemas que somente estudando a parte teórica eu não iria ter, e isso vai me ajudar a sair da zona de conforto e poderei evoluir como dev. Mesmo utilizando IA, muito do que eu vou precisar fazer nesse projeto eu não tenho ideia de como seja feito, então vai ser uma boa oportunidade de saber (mesmo sem entender direito) como as coisas funcionam. 

até os levantamentos de requisitos foram gerados pela IA:

---

### 🧩 1. Objetivo da aplicação

* Gerenciar entradas e saídas de dinheiro pessoais.
* Acompanhar saldo e categoria de gastos.
* Servir como um projeto de portfólio (com foco em código limpo, boas práticas e usabilidade).

---

### ✅ 2. Requisitos Funcionais (RF)

Esses são os recursos que o sistema deve oferecer:

#### RF01 – Cadastro de transações

* Tipo: entrada ou saída.
* Valor.
* Data.
* Categoria (ex: alimentação, transporte).
* Descrição (opcional).

#### RF02 – Visualização do saldo total

# 📊 Gestor de Finanças Pessoais

Aplicação web para controle de finanças pessoais, com funcionalidades de registro de entradas e saídas, categorização e visualização de saldo. Projeto desenvolvido inicialmente para uso próprio, com foco em se tornar um projeto de portfólio.

---

## 🎯 Objetivo

Desenvolver uma aplicação web simples e funcional para gestão de finanças pessoais, permitindo o controle de receitas e despesas, organização por categorias e visualização de saldo e gráficos de forma intuitiva. O projeto também serve como demonstração prática de habilidades em Java e desenvolvimento web full stack.

---

## ✅ Requisitos Funcionais (RF)

| Código | Descrição |
|--------|-----------|
| RF01 | Permitir o cadastro de transações financeiras (entrada ou saída), com valor, data, categoria e descrição. |
| RF02 | Exibir o saldo total calculado a partir das transações registradas. |
| RF03 | Listar todas as transações, com opção de filtro por data, tipo (entrada/saída) e categoria. |
| RF04 | Permitir a edição e exclusão de transações já cadastradas. |
| RF05 | Permitir o cadastro e gerenciamento de categorias personalizadas. |
| RF06 | Exibir um dashboard/resumo financeiro com totais por tipo e gráficos por categoria. |
| RF07 | (Opcional) Implementar login e autenticação de usuários para uso pessoal ou multiusuário no futuro. |

---

## ⚙️ Requisitos Não Funcionais (RNF)

| Código | Descrição |
|--------|-----------|
| RNF01 | A aplicação deve ser responsiva e funcionar bem em dispositivos móveis e desktop. |
| RNF02 | A interface deve ser intuitiva, com boa usabilidade e design simples. |
| RNF03 | O sistema deve apresentar desempenho satisfatório, com carregamento rápido das informações. |
| RNF04 | Caso haja autenticação, os dados devem ser protegidos com boas práticas de segurança. |
| RNF05 | O projeto deve ser estruturado de forma a permitir melhorias futuras e fácil manutenção. |

---

## 🧱 Tecnologias Utilizadas

### Backend
- Java 21
- Spring Boot
- Spring Data JPA (Hibernate)
- PostgreSQL 
- Maven ou Gradle

### Frontend (sugestão)
- React + Vite
- Tailwind CSS
- Axios (para chamadas HTTP)
- Recharts (para gráficos)

---

## 📈 Funcionalidades Futuras (Backlog)

- Exportar relatórios financeiros (CSV/PDF)
- Notificações de metas orçamentárias
- Planejamento orçamentário mensal
- Backup/sincronização com nuvem
- Modo escuro

---
