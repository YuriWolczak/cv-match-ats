# NexoCV — análise de currículo e vaga

Protótipo de portfólio para comparar o texto de um currículo com os requisitos de uma vaga. O NexoCV destaca termos coincidentes e pontos para revisar em uma interface original, responsiva e acessível.

## O que funciona

- Carregar, arrastar ou colar um currículo em texto.
- Comparar com uma descrição de vaga e ver termos coincidentes e não encontrados.
- Usar um exemplo guiado para conhecer o fluxo.
- Copiar ou baixar um resumo em `.txt`.
- Processar tudo localmente no navegador, sem enviar ou armazenar currículos em servidor.
- Usar em telas grandes ou celulares, com navegação por etapas e movimento reduzido respeitado.

## Limites do protótipo

A estimativa é uma comparação simples de palavras-chave, sem modelo de IA, leitura de PDF/DOCX ou integração com sistemas ATS. Ela não prevê contratação, não mede qualidade profissional e não deve ser interpretada como pontuação oficial.

## Executar

Abra `index.html` em um navegador moderno. Não há dependências nem etapa de build.

## Próximas etapas possíveis

- Adicionar extração segura de PDF e DOCX no próprio navegador.
- Criar testes para a análise de termos e acessibilidade.
- Projetar uma API opcional, com consentimento explícito e política de retenção, antes de conectar qualquer modelo de IA.
