# Fokus - App de Produtividade (Pedro Costa)

## Descrição
O **Fokus** é um aplicativo de produtividade desenvolvido em React Native com Expo. Ele ajuda os usuários a otimizar sua produtividade através de técnicas como o Pomodoro, gerenciamento de tarefas e outras funcionalidades focadas em foco e eficiência. 

Este é um projeto fictício sem fins comerciais, desenvolvido por Aluno. Para contribuições avaliativas.

## Funcionalidades Principais
- **Tela Inicial**: Apresentação do app com chamada para ação.
- **Login**: Autenticação de usuários.
- **Pomodoro**: Temporizador para técnica Pomodoro (trabalho focado e pausas).
- **Gerenciamento de Tarefas**: Adicionar, visualizar e gerenciar tarefas.
- **ViaCEP**: Integração com API do ViaCEP para busca de endereços por CEP.

## Estrutura do Projeto
- **app/**: Contém as telas principais do app (index.jsx, login.jsx, pomodoro.jsx, etc.).
- **src/components/**: Componentes reutilizáveis como FokusButton, ActionButton, TaskItem, Timer, etc.
- **src/assets/**: Imagens, fontes e SVGs utilizados no app.

## Como Funciona
O app utiliza navegação baseada em Expo Router para transitar entre telas. Cada tela é um componente React Native que renderiza interfaces específicas. Por exemplo:
- A tela inicial (`app/index.jsx`) exibe o logo, uma mensagem motivacional e um botão para iniciar.
- O componente `FokusButton` é usado para ações interativas.
- O temporizador Pomodoro (`src/components/Timer`) gerencia sessões de trabalho e pausa.

## Como Rodar o Projeto
### Pré-requisitos
- Node.js instalado.
- Expo CLI instalado globalmente: `npm install -g @expo/cli`.
- Um dispositivo físico ou emulador para iOS/Android, ou navegador para web.

### Passos para Executar
1. Clone o repositório e navegue até a pasta do projeto.
2. Instale as dependências:
   ```
   npm install
   ```
3. Inicie o servidor de desenvolvimento:
   ```
   npm start
   ```
   Ou para web especificamente:
   ```
   npm run web
   ```
4. Para acessar no localhost:8081, use o comando web. O Expo abrirá o navegador automaticamente, mas você pode acessar manualmente em `http://localhost:8081`.

### Scripts Disponíveis
- `npm start`: Inicia o Expo DevTools.
- `npm run android`: Executa no Android.
- `npm run ios`: Executa no iOS.
- `npm run web`: Executa no navegador web.
- `npm test`: Executa os testes com Jest.

## Tecnologias Utilizadas
- **React Native**: Framework para desenvolvimento mobile.
- **Expo**: Plataforma para facilitar o desenvolvimento React Native.
- **Expo Router**: Navegação baseada em arquivos.
- **Jest**: Para testes.

## Licença
Projeto sem licença específica.
