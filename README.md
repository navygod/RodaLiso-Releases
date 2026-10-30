# RodaLiso — Downloads oficiais

Desenvolvedor: Tiago C. Correa (navygod).

Diagnóstico, monitoramento e manutenção do Windows x64, com ações controladas pelo usuário.

## Baixar

- Site oficial: https://wda-apps.netlify.app/apps/rodaliso
- Versão atual e instaladores: https://github.com/navygod/RodaLiso-Releases/releases/latest

Baixe o arquivo Setup.exe para instalar. O instalador inclui o runtime .NET e instala para o seu usuário. Feche a versão anterior antes de abrir a nova. Para a edição portátil, extraia o ZIP completo e mantenha os arquivos juntos.

## Atualizações

A edição 0.5.2 ou posterior consulta o manifesto assinado enquanto aberta, no máximo uma tentativa automática por dia. Você pode desativar a consulta automática ou verificar manualmente em Relatório e Atualizações. O download exige sua ação e a instalação pede confirmação. As versões anteriores e os dados locais são preservados.

Manifesto oficial: https://raw.githubusercontent.com/navygod/RodaLiso-Releases/main/updates/stable.json

O aplicativo verifica assinatura RSA-PSS, validade, tamanho e SHA-256 do pacote. A assinatura do manifesto é distinta da assinatura Authenticode do executável, que ainda não foi configurada nesta edição.

## Interface

Tema Escuro com fundo preto e painéis quase pretos. Os indicadores de CPU, GPU e RAM usam verde abaixo de 90% e vermelho a partir de 90%. Leituras ausentes ficam em cinza. Uso elevado, isoladamente, não comprova falha.

## Sobre esta distribuição

Este repositório contém somente arquivos de distribuição e informações públicas. O código-fonte é mantido em repositório privado. As licenças e os avisos das dependências acompanham os pacotes. Sensores e funções avançadas dependem do hardware e das permissões disponíveis.