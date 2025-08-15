# AutoShare - Monitor de Loot

**AutoShare** é um aplicativo Windows com ícone na bandeja que monitora a área de transferência e processa automaticamente relatórios de hunts do jogo **Tibia**.  
Ele identifica automaticamente textos do **Hunt Analyzer** e **Party Hunt**, gera arquivos CSV com o histórico e até divide o loot de forma justa entre os integrantes.

## 📦 Baixe a versão mais recente do **AutoShare** no link abaixo:

[📦 **Clique aqui para baixar o AutoShare.exe**](https://github.com/Grodrigues1998/AutoShare/AutoShare.exe)

## ✨ Funcionalidades

- 📋 **Monitoramento automático** da área de transferência.
- 🔍 Detecção de logs do *Hunt Analyzer* e *Party Hunt*.
- 📊 Geração de relatórios CSV organizados no diretório `Documentos/AutoShare`.
- ⚖️ Cálculo automático de divisão de loot entre os jogadores.
- 💬 Notificações na bandeja para cada operação.
- 📂 Acesso rápido ao histórico pelo menu de contexto do ícone.

## 📁 Estrutura de Saída

Ao processar dados, o programa salva arquivos CSV em:



## 📊 Documentos/AutoShare
- HuntAnalyzer.csv # Histórico das hunts solo
- PartyHunt.csv # Histórico de hunts em grupo

paramelhor visualização do histórico é recomendado utilizar o excel ou planilhas do google


### Formatos:

**HuntAnalyzer.csv**

**PartyHunt.csv**



## 🚀 Como usar
1. Baixe e instale o AutoShare
1. Copie para a área de transferência o texto do **Hunt Analyzer** ou **Party Hunt** no formato padrão do jogo.
2. O AutoShare processará automaticamente e salvará no histórico.
3. No caso de Party Hunt, o cálculo de divisão de loot será copiado para a área de transferência.

## 📦 Requisitos

- **Windows** com .NET Framework compatível.
- Permissão para executar aplicações em segundo plano.
