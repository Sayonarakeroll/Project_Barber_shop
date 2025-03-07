```markdown
# Barber Shop

Projeto é simula uma aplicação completa para gerenciamento de horários em uma barbearia. O sistema é dividido em **backend** e **frontend**, utilizando tecnologias modernas para garantir eficiência e usabilidade.

## Tecnologias Utilizadas

### Backend
- **Java Spring Boot (JDK 21)**
- **PostgreSQL**
- **Gradle 8.12.1**
- **Flyway**

### Frontend
- **Angular**
- **Node.js 18.x**
- **npm**
- **Angular CLI**

---

## Pré-requisitos

### Backend
1. **JDK 21 ou superior** - [Download Oracle JDK](https://www.oracle.com/java/technologies/javase-jdk21-downloads.html) ou [Adoptium](https://adoptium.net/).
2. **PostgreSQL** - Banco de dados versão 12 ou superior.
   - Crie o banco de dados no PostgreSQL e configure a conexão no arquivo `application.yml`.
3. **Gradle** - O projeto já contém o **Gradle Wrapper**, não sendo necessário instalar manualmente.

### Frontend
1. **Node.js 18.x ou superior** - [Download Node.js](https://nodejs.org/)
2. **Angular CLI**
   ```bash
   npm install -g @angular/cli
   ```

---

## Como Rodar o Projeto

### Backend

1. Clone o repositório:
   ```bash
   git clone https://github.com/Sayonarakeroll/Project_Barber_shop.git
   cd backend
   ```

2. Configure o banco de dados PostgreSQL no arquivo `application.yml`.

3. Rode o projeto:
   ```bash
   ./gradlew bootRun
   ```

---

### Frontend

1. Clone o repositório:
   ```bash
   git clone https://github.com/Sayonarakeroll/Project_Barber_shop.git
   cd front
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Rode o projeto:
   ```bash
   ng serve
   ```

Acesse a aplicação pelo navegador em: `http://localhost:4200/`

---




