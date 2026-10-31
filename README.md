# CV Match — Analisador de Currículo ATS

Protótipo de portfólio inspirado em ferramentas de comparação de currículo com vagas. A interface ajuda a visualizar correspondências textuais e oportunidades de revisão.

## O que funciona

- Carregar ou arrastar arquivos `.txt` e `.md` (até 2 MB).
- Colar a descrição de uma vaga e conferir uma estimativa de termos encontrados.
- Usar um exemplo demonstrativo para explorar o fluxo.
- Processar o texto localmente no navegador; o protótipo não envia nem armazena currículos em servidor.
- Interface responsiva, com avisos claros sobre as limitações da pontuação.

## Limites do protótipo

A nota é uma comparação simples de palavras-chave, sem modelo de IA, parsing de PDF/DOCX ou integração com sistemas ATS. Ela não prevê contratação, não mede qualidade profissional e não deve ser interpretada como pontuação oficial.

## Executar

Abra `index.html` em um navegador moderno. Não há dependências nem etapa de build.

## Próximas etapas possíveis

- Adicionar extração segura de PDF e DOCX no próprio navegador.
- Criar testes para a análise de termos e acessibilidade.
- Projetar uma API opcional, com consentimento explícito e política de retenção, antes de conectar qualquer modelo de IA.
