# AutoShare - Monitor de Loot

**AutoShare** é um aplicativo Windows que fica na bandeja do sistema e monitora a área de transferência para processar automaticamente relatórios de hunts do jogo **Tibia**.  
Ele reconhece textos do **Hunt Analyzer** e **Party Hunt**, gera históricos organizados em CSV e faz a divisão de loot de forma justa.

## 📦 Baixe a versão mais recente
[📥 **Clique aqui para baixar o AutoShareInstaller.exe**](https://github.com/Grodrigues1998/AutoShare/releases/download/v1.0/AutoShareInstaller.exe)

## ✨ Funcionalidades

- 📋 **Monitoramento automático** da área de transferência.
- 🔍 Detecção de logs do *Hunt Analyzer* e *Party Hunt*.
- 📊 Salvamento automático de históricos no diretório `Documentos/AutoShare`.
- ⚖️ Cálculo de divisão de loot com instruções claras de pagamento.
- 💬 Notificações via bandeja para cada operação concluída.
- 📂 Acesso rápido ao histórico pelo menu de contexto.


## 📦 Requisitos

- **Windows** com .NET Framework compatível.
- Permissão para executar aplicações em segundo plano.

PartyHunt <data>.csv
Arquivo JSON contendo a lista de pagamentos no formato:

"[Jogador Pagador] paga para [Jogador Recebedor] [quantia]gps: transfer [quantia] to [Jogador Recebedor]"


💡 Para melhor visualização dos históricos, recomenda-se abrir os arquivos no Excel ou Google Planilhas.

🚀 Como usar

Baixe e instale o AutoShare.

Copie para a área de transferência o texto do Hunt Analyzer ou Party Hunt no formato padrão do jogo.

O AutoShare processará e salvará no histórico automaticamente.

Para Party Hunt, clique na notificação para ver os detalhes de pagamento, ou selecione a opção Loot split que carregará o ultimo split salvo

📦 Requisitos

Windows com .NET Framework compatível.

Permissão para executar aplicações em segundo plano.
