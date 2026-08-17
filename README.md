# Simulador AWS Cloud Practitioner — CLF-C02

Simulador de provas para a certificação **AWS Cloud Practitioner (CLF-C02)** com 32 questões oficiais e sistema de geração de questões por IA a partir de aulas do dia a dia.

## Funcionalidades

- **10 questões diárias** com distribuição proporcional aos domínios da prova (Conceitos 24%, Segurança 30%, Tecnologia 34%, Cobrança 12%)
- **Sistema de progresso** — pontuação estimada, acertos por domínio e por tema, identificação de pontos fracos
- **Geração de questões por IA** — cole o texto de uma aula e gere perguntas automaticamente usando o Google Gemini (chave gratuita)
- **Edição manual** — crie e edite perguntas diretamente no aplicativo
- **Backup/restore** — exporte e importe seu banco de perguntas em JSON
- **Prática por aula** — pratique questões de uma aula específica isoladamente

## Como usar

1. Abra `aws-trainer.html` no navegador
2. Para usar a IA, configure a chave gratuita do Google Gemini em **Banco > Configurações da IA**
   - Crie sua chave em [AI Studio](https://aistudio.google.com/app/apikey) (gratuito)
3. **Fluxo diário**: cole o texto da aula em **Nova Aula** → gere questões → revise → salve → pratique

## Tecnologias

- HTML, CSS e JavaScript puros (sem dependências externas)
- Google Gemini API para geração de questões
- Salvamento local via localStorage (funciona offline)
