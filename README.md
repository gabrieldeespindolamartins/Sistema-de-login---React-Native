📱 Sistema de Login - React Native (Expo)
Este projeto é um exemplo simples de aplicativo em React Native com Expo que implementa um sistema de login com navegação entre duas telas.

🚀 Funcionalidades
Tela de Login com campos de usuário e senha.

Validação de credenciais hardcoded:

Usuário: aluno

Senha: 123

Exibição de mensagem de erro em caso de credenciais inválidas.

Navegação para a tela de Sucesso quando o login é realizado corretamente.

📂 Estrutura do Projeto
Código
/App.js
/screens/LoginScreen.js
/screens/SuccessScreen.js
App.js → Configuração da navegação com React Navigation.

LoginScreen.js → Tela inicial com formulário de login e validação.

SuccessScreen.js → Tela exibida após login bem-sucedido.

🛠️ Tecnologias Utilizadas
Expo

React Native

React Navigation

⚙️ Instalação e Execução
1. Clonar o repositório
bash
git clone https://github.com/seu-usuario/loginSistem.git
cd loginSistem
2. Instalar dependências
bash
npm install
3. Instalar pacotes necessários para navegação
bash
npm install @react-navigation/native @react-navigation/stack
npx expo install react-native-screens react-native-safe-area-context react-native-gesture-handler react-native-reanimated
4. Rodar o projeto
No celular (Expo Go):

bash
npx expo start
Escaneie o QR Code com o app Expo Go.

No navegador (Web):

bash
npx expo start --web
📸 Fluxo do App
Usuário abre o app → Tela de Login.

Digita usuário e senha.

Se correto (aluno / 123) → vai para SuccessScreen.

Se incorreto → aparece mensagem "Credenciais inválidas".

📌 Observações
Este projeto é apenas um exemplo didático.

Em aplicações reais, nunca use credenciais hardcoded.

Para produção, utilize APIs seguras e armazenamento criptografado.
