# Avaliação IA Generativa: Assistente de Saúde e Bem-estar (IoB)

## Integrantes
- Diego Andrade dos Santos (RM566385)
- Grazielle de Alencar Silva (RM561529)
- Vinicius Soteras Braga (RM566230)

## Tema
**Tema 4: Assistente de saúde e bem-estar (IoB).**

O assistente ajuda o usuário a interpretar dados de wearables (passos, sono e frequência cardíaca) e dá dicas gerais de hábitos saudáveis, **sem dar diagnóstico médico**.

Modelo usado: `gemini-3.5-flash-lite` (Google Gemini). O Hugging Face retornou erro `402 Payment Required` (créditos gratuitos esgotados), por isso todas as etapas foram feitas com o Gemini.

## System prompt usado
```
Você é um assistente de saúde e bem-estar.
Ajude o usuário a entender dados de wearables (passos, sono e frequência cardíaca) e dê dicas gerais de hábitos saudáveis.
Responda sempre em português, de forma clara, em no máximo 5 frases.
Nunca dê diagnóstico médico nem indique remédios. Se os dados parecerem fora do normal, recomende procurar um profissional de saúde.
Se a pergunta não tiver relação com saúde e bem-estar, diga educadamente que não pode ajudar.
```

## Etapas realizadas
- [ ] Etapa 1: Assistente com guardrails
- [ ] Etapa 2: Comparação com temperatura
- [ ] Etapa 3: Chat com memória
- [ ] Etapa 4: Interface Gradio com temperatura
- [ ] Etapa 5 (bônus): API com sessões independentes
