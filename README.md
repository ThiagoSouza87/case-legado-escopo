# Do Legado ao Escopo

Estudo de caso sobre dimensionar a modernização de um sistema legado — sem documentação,
sem o desenvolvedor original e sem nenhum número confiável para começar.

**[Ler o estudo de caso](https://thiagosouza87.github.io/case-legado-escopo/)** ·
**[Abrir o protótipo navegável](https://thiagosouza87.github.io/case-legado-escopo/prototipo.html)**

---

## O problema

Um escritório de contabilidade pediu para "melhorar a intranet inteira". O sistema era
ASP.NET Web Forms, parado havia oito anos, sem documentação e com funcionalidades falhando
progressivamente.

Duas respostas dadas na mesma conversa governavam orçamentos que diferiam em três a quatro vezes:

> "170 telas, muitas não utilizadas."

> "A totalidade precisa ser atualizada em nova versão e funcionalidade."

Qualquer proposta fechada naquele momento seria chute.

## O que foi feito

| | |
|---|---|
| **Diagnóstico** | 11 achados classificados por severidade, extraídos de um vídeo de tela e de capturas — sem acesso ao código |
| **Protótipo** | Interface navegável construída antes do orçamento, herdando a identidade visual de outro sistema da empresa |
| **Levantamento** | Roteiro para o cliente conduzir internamente: contagem de arquivos, registros de acesso de 90 dias e entrevistas por setor |
| **Inventário** | Cada tela classificada em simples/média/complexa, com duplicatas e links externos marcados |
| **Proposta** | Seis ondas de entrega, com as iniciais a preço firme e as finais confirmadas ao fim da anterior |

**Resultado do dimensionamento:** 170 telas estimadas → 45 confirmadas em uso → 34 a construir.
Redução de 73% no escopo antes de escrever a primeira linha de código.

## Conteúdo deste repositório

```
index.html       estudo de caso completo
prototipo.html   protótipo navegável, autocontido
```

Ambos são HTML, CSS e JavaScript sem dependências externas, sem build e sem framework.
Funcionam offline, abrindo o arquivo direto no navegador.

## Sobre os dados

Este material é público e foi **inteiramente anonimizado**. Não há nome, domínio, marca ou
captura de tela do cliente. As pessoas, empresas, telefones e e-mails do protótipo são
fictícios, e o desenho da tela legada é uma reconstrução própria, não uma imagem original.

Os números de escopo e o método são reais.

## Contato

Thiago Souza — desenvolvedor sênior (Java, .NET, Vue)
