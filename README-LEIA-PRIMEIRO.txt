MACIA ZERO — PROJETO COMPLETO PARA ABRIR NO VS CODE E RODAR NA WEB

Este ZIP já contém a estrutura do projeto Expo, o App.tsx, package.json e as configurações. NÃO é para substituir arquivos de outro projeto. Use esta pasta como projeto novo.

PASSO A PASSO (Windows):
1. Baixe este ZIP.
2. Clique com o botão direito no ZIP > Extrair tudo... (é necessário extrair o projeto para o computador para o VS Code conseguir executar os arquivos).
3. Abra o VS Code.
4. Vá em File/Arquivo > Open Folder/Abrir Pasta e selecione a pasta macia-zero-web-pronto que foi extraída.
5. No VS Code, abra Terminal > New Terminal/Novo Terminal.
6. Confira se o terminal está dentro da pasta macia-zero-web-pronto. Se não estiver, use cd seguido do caminho da pasta.
7. Execute: npm install
   Aguarde terminar. Isso instala as dependências descritas em package.json.
8. Execute: npx expo start --web
9. Aguarde o Expo abrir o navegador. Se não abrir automaticamente, use o endereço local que aparecer no terminal (normalmente http://localhost:8081).

REQUISITOS:
- Node.js LTS instalado no computador. Se o comando npm não for reconhecido, instale o Node.js LTS pelo site oficial https://nodejs.org/ e depois feche e reabra o VS Code.
- Internet na primeira instalação para baixar as dependências.

TELAS E FUNÇÕES DEMONSTRATIVAS:
Boas-vindas; início; cardápio com busca e categorias; detalhes do produto; monta-sabor; carrinho com quantidades; finalização demonstrativa; pedidos; clube de pontos; perfil; chat automático; painel administrativo demonstrativo; gerenciamento de disponibilidade de produtos e status de pedidos.

IMPORTANTE:
- Este é um protótipo de interface. Não possui backend, autenticação segura, cobrança, pagamento ou envio real de pedidos.
- Os dados ficam apenas na memória enquanto o app está aberto.
- O código usa Expo/React Native Web e não exige instalar bibliotecas extras manualmente além do npm install.
- Se já houver um Expo rodando em outro terminal, pare-o com Ctrl+C antes de iniciar este projeto.
