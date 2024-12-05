### 🛡️ Atividade N2

---

### 🌟 **Funcionalidades**
- 📝 **Cadastro de Usuários:**  
  Usuários podem se registrar e criar seus perfis com credenciais seguras.  

- 🔐 **Configuração de Acesso por Papel:**  
  - **Administrador (ADM):**  
    🔧 Pode habilitar/desabilitar usuários do sistema.  
  - **Gerente:**  
    👀 Pode visualizar a lista completa de usuários cadastrados.  
  - **Usuário Comum:**  
    🏠 Após login, será automaticamente redirecionado(a) para sua página de perfil.  

---

### ⚙️ **Tecnologias Utilizadas**
- **Back-End:**  
  - Java 17 ☕  
  - Spring Boot 🖥️  
  - JPA/Hibernate para persistência de dados 📂  
  - Banco de Dados H2 (ambiente de teste) 🛢️  

- **Front-End:**  
  - Angular 17 ⚡  
  - TypeScript 🟦  
  - PrimeNG para UI/UX moderna 🎨  

---

### 🚀 **Como Executar o Projeto**

1. **Clone o Repositório**  
   ```bash
   git clone https://github.com/seuprojeto.git
   cd seu-projeto
   ```

2. **Back-End**  
   - Navegue até a pasta `backend`.  
   - Configure o arquivo `application.yml` se necessário.  
   - Execute o projeto:  
     ```bash
     ./mvnw spring-boot:run
     ```

3. **Front-End**  
   - Navegue até a pasta `frontend`.  
   - Instale as dependências:  
     ```bash
     npm install
     ```  
   - Inicie o servidor de desenvolvimento:  
     ```bash
     ng serve
     ```  

4. **Acesse o Sistema**  
   - Front-End: `http://localhost:4200`  
   - Back-End: `http://localhost:8080`  

---

### 🔑 **Roles e Acessos**

| **Papel**      | **Permissão**                                |
|-----------------|---------------------------------------------|
| **Administrador** | Desabilitar usuários, acessar todas as áreas. |
| **Gerente**       | Visualizar a lista de usuários.            |
| **Usuário Comum** | Acessar página de perfil pessoal.          |

---
