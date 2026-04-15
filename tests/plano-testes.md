# Plano de Testes - Rock Nation

## 1. Objetivo do Teste
Definir a estratégia para validar as funcionalidades da página institucional, garantindo que o layout seja responsivo e que todos os links de navegação funcionem corretamente.

## 2. Escopo
* O que será testado Navegação do menu superior, funcionamento do botão "Saiba Mais", responsividade em dispositivos móveis e carregamento das imagens de fundo.
* [cite_start]**O que não será testado:** Integração com bancos de dados externos ou APIs de terceiros (não contemplados neste projeto simples).

## 3. Ambiente de Teste
* Navegadores: Google Chrome e Firefox.
* Dispositivos: Desktop e emulação de dispositivos móveis via VS Code/Navegador.
* Sistema Operacional: Windows/Linux/MacOS.

## 4. Critérios de Aceitação
* O site deve carregar sem erros de console[cite: 78].
* Todos os links âncora (#sobre, #generos) devem levar o usuário à seção correta da página.
* O layout não deve apresentar quebras de elementos em telas menores que 480px.