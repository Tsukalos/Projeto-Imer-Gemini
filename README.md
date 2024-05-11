# Gerando ganchos para aventuras de RPG!
Projeto da Imersão Inteligência Artificial 2ª Edição da Alura.

## 💭 Motivação

Decidi criar este projeto devido a uma necessidade própria: costumo mestrar diversas aventuras *one-shot* para grupos iniciantes, e a parte de iniciar uma aventura geralmente requer planejamento prévio, especialmente na construção de cenários, personagens, etc. A capacidade generativa do Gemini foi uma das características mais atrativas para ajudar na geração de conteúdo, auxiliando na descrição de ambientes e personagens. Em outras palavras, me ajudaria a economizar tempo de planejamento, pelo menos para *one-shots* e inícios de aventuras 😅. O modelo também foi instruído a gerar descrições baseados no cenário de Arton, cenário brasileiro do sistema Tormenta! 🇧🇷

## ❗ Como funciona

Utilizei a abordagem de *few-shot prompting*, incluindo exemplos no início de cada prompt para ditar a estrutura geral do markdown. Alguns exemplos foram gerados previamente com o próprio Gemini. Inicialmente, usava o `gemini-1.5-pro-latest`, mas acredito que o usei demais em outros projetos e recebi muitos *timeouts*. Mudei para o `gemini-1.0` e, apesar de fornecer descrições menos longas que o `1.5-pro-latest`, especialmente em características e detalhes, ele tem um desempenho razoável para o projeto. Para testar, basta mudar o modelo utilizado.
