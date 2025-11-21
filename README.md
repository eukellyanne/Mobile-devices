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

## Descrição das Práticas

**Aula 1 (MeuPrimeiroApp)**

O objetivo das práticas nessa aula foi para a gente aplicar os conceitos fundamentais e mais básicos da criação de componentes funcionais, uso de propriedades, gerenciamento de estado e renderização. O componente Exercicio1 recebe uma propriedade chamada nome e mostra “Olá, {nome}”, centralizando o conteúdo na tela com o uso das propriedades justifyContent, alignItems e padding para espaçamento. O Exercicio2 e 3 utiliza o useState para controlar um contador numérico, com dois botões que permitem incrementar e decrementar o valor, mantendo o layout centralizado da mesma forma que o 1. Já no Exercicio4, foi criada uma lista de times de futebol definida em um array, exibida pelo método map(), de forma que cada clube é mostrado em uma nova linha.


**Aula 2**

No primeiro momento utilizamos um contêiner principal para estruturar a tela, integrando o cabeçalho, o conteúdo central e o rodapé, a intenção era que ocupasse todo o espaço disponível na tela e deixasse os elementos centralizados, deixando o cabeçalho na parte superior, o conteúdo no centro e o rodapé na parte inferior da tela. O App.js é o arquivo principal e mostra o LayoutResponsivo, que divide a tela nessas três partes e se ajusta a diferentes tamanhos de tela. O CartaoApresentacao mostra um cartão com imagem, nome, descrição e botões para GitHub e LinkedIn. Já o CartaoPerfil exibe um cartão interativo, onde ao clicar no botão “Ver Mais” aparecem detalhes como e-mail, localização e hobbies.


**Aula 3 (Inacabado)**

Aqui, o App.js exibe a tela de login centralizada usando View como nas outras aulas. Diferente das outras aulas que o App renderizava de dentro dos components, nessa foi criada uma pasta screens, que foi usada para organizar as telas do aplicativo que é a  LoginScreen, onde será desenvolvida a interface de login do usuário. A prática ainda está em andamento (iniciamos e ficamos seguir desenvolvendo) e seguirá com a construção completa da tela. Os botões da tela de loggin também ficaram inacabados por enquanto.


<details>
<summary>📦 Ver todas as imagens em grade</summary>
<p align="center">
<img src="https://github.com/user-attachments/assets/d54a8850-21b0-4956-a5af-fb1dabcbe64f" alt="Img 1" width="240" />
<img src="https://github.com/user-attachments/assets/a86c3328-1862-4d98-a2dc-de7e57e78cab" alt="Img 2" width="240" />
</p>
<p align="center">
<img src="https://github.com/user-attachments/assets/1a49f38e-b6f5-45fb-8e53-ce24ef340c15" alt="Img 3" width="240" />
<img src="https://github.com/user-attachments/assets/d9837d47-7c0e-4145-8e5f-e8bd4e191142" alt="Img 4" width="240" />
<img src="https://github.com/user-attachments/assets/0555ffec-7778-4ee5-95a0-39481ee5be8f" alt="Img 5" width="240" />

</p>
</details>

## Comandos necessários para rodar aplicação

- npm install (caso seja feito um clone do repositório, só roda o projeto com o npm instalado)
- npx create-expo-app@latest nome --template blank (criar projeto do zero)
- npm start 















