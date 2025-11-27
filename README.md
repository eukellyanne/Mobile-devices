# Programação de Dispositivos Móveis

## Descrição do Projeto

Desenvolver um site que funcione bem, seja fácil de usar e se adapte a diferentes tamanhos de tela, como computadores e celulares, garantindo uma boa experiência para todos os usuários.

## Objetivo do Projeto

Esse projeto foi desenvolvido como parte da disciplina de Desenvolvimento de Dispositivos Móveis, com o objetivo de aplicar conceitos de:

- Componentização com React Native
- Navegação entre telas
- Consumo de dados do Firebase
- Organização de pastas
- Boas práticas com variáveis de ambiente (.env)


## Funcionalidades 

- [x] Tela inicial (Home)
- [x] Listagem de cursos (dados vindos do Firebase)
- [x] Estrutura modular (screens, services, components)
- [x] Integração com Firebase
- [x] Uso de variáveis de ambiente com `.env`


## Estrutura da Branch

- `main`: Branch principal de desenvolvimento, onde todas as alterações e novas funcionalidades serão implementadas e testadas.

## Como Clonar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/eukellyanne/Mobile-devices.git

2. **Acesse o diretório:**
   ```bash
   cd  Mobile-devices

## Ferramentas e Linguagem utilizada
[![Minhas habilidades](https://skillicons.dev/icons?i=git,github,react,vscode,npm,javascript,nodejs,)](https://skillicons.dev)

## Descrição das Telas 

**LoginScreen** : A tela de login foi construída como um componente React Native que recebe o objeto navigation do React Navigation, possui dois estados controlados que são email e senha, e renderiza inputs e botões que permitem ao usuário interagir com a interface. Em seguida, a interface exibe um logo carregado da internet, um título simples, dois TextInput, e um botão “Entrar” que chama a função de navegação. A tela também apresenta dois textos informativos “Esqueceu a senha?” e “Registre-se”  que não são clicáveis. Abaixo disso, são exibidos dois botões sociais estilizados para GitHub e Google, que os cliques ainda não funcionam. Toda a aparência da tela, como tamanhos, espaçamentos e alinhamentos, é organizada pelo StyleSheet, que define estilos para o container, inputs, botões e os outros elementos.

**HomeScreen** : O processo de criação da HomeScreen começa configurando o Firebase. A HomeScreen é a tela responsável por buscar e exibir os cursos armazenados no Firestore (que no meu código tem um erro a ser corrigido). A ideia da lista via firebase é que esses dados são guardados e são usados para tornar a lista dinâmica.


<details>
<summary>📦 Ver todas as imagens em grade</summary>
<p align="center">
<img src="https://github.com/user-attachments/assets/d54a8850-21b0-4956-a5af-fb1dabcbe64f" alt="Img 1" width="240" />
<img src="https://github.com/user-attachments/assets/a86c3328-1862-4d98-a2dc-de7e57e78cab" alt="Img 2" width="240" />
<img src="https://github.com/user-attachments/assets/1a49f38e-b6f5-45fb-8e53-ce24ef340c15" alt="Img 3" width="240" />
</p>
<p align="center">
<img src="https://github.com/user-attachments/assets/d9837d47-7c0e-4145-8e5f-e8bd4e191142" alt="Img 4" width="240" />
<img src="https://github.com/user-attachments/assets/0555ffec-7778-4ee5-95a0-39481ee5be8f" alt="Img 5" width="240" />
<img src="https://github.com/user-attachments/assets/d0d65fde-c745-4c7e-b50c-90cd99bc31f7" alt="Img 6" width="240" />
<img src="https://github.com/user-attachments/assets/c5e46578-0c78-4761-99c2-3ad9cdb7a9a0" alt="Img 7" width="240" />
</p>
</details>

## Comandos necessários para rodar aplicação

- `npx create-expo-app@latest nome --template blank` 
- `npm start` / **W** (WEB)
- `npm start` 

## Firebase com .env

###  Exemplo de arquivo `.env`

FIREBASE_API_KEY=your_api_key
FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
FIREBASE_DATABASE_URL=https://your_project.firebaseio.com
FIREBASE_PROJECT_ID=your_project_id
FIREBASE_STORAGE_BUCKET=your_project.appspot.com
FIREBASE_MESSAGING_SENDER_ID=your_sender_id
FIREBASE_APP_ID=your_app_id

















