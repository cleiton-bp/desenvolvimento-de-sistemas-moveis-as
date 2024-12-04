# Trabalho AS

## Descrição
Este projeto é uma aplicação Flutter que permite aos usuários registrar-se e fazer login utilizando o Firebase Authentication, depois dos usuários estarem autenticados eles podem explorar uma lista de países.

## Funcionalidades
- **Autenticação de Usuário**: Registro, login e logout utilizando Firebase.
- **Visualização de Países**: Lista de países com detalhes como nome, capital, população, bandeira, etc.
- **Navegação**: Navegação entre telas de login, registro, lista de países e detalhes do país.

## Tecnologias Utilizadas
- **Flutter**: Framework para desenvolvimento do aplicativo.
- **Firebase**: Utilizado para autenticação de usuários.
- **REST API**: Para obter dados dos países.

## Estrutura do Projeto
- **screens**: Contém as telas principais do aplicativo (`LoginScreen`, `RegisterScreen`, `HomeScreen`, `CountryDetailScreen`).
- **models**: Define os modelos de dados (`Countrie`).
- **services**: Contém os serviços para autenticação e obtenção de dados dos países (`AuthService`, `CountrieService`).
- **widgets**: Componentes reutilizáveis como inputs personalizados e carregamento (`CustomInput`, `CustomInputPassword`, `CustomLoading`, `ErrorAuth`).
- **main.dart**: Ponto de entrada do aplicativo.

## Como Executar o Projeto
### Pré-requisitos
- Flutter instalado na máquina.
- Conta no Firebase configurada com um projeto.

### Passos para Execução
1. **Clonar o Repositório** 
   ```bash
   git clone https://github.com/cleiton-bp/desenvolvimento-de-sistemas-moveis-as.git
   ```

2. **Instalar Dependências** - *as dependências do projeto.*
    ```bash
      flutter pub get
    ```
  
3. **Configurar Firebase**
      - Certifique-se de configurar o Firebase para que funcione o login/register

4. **Executar o Projeto** - *para iniciar a aplicação.*
    ```bash
      flutter run 
    ```

### Comandos Úteis

- **Atualizar Dependências**  
  ```bash
    flutter pub upgrade 
  ```
- **Build**
  ```bash
    flutter build apk 
  ```
