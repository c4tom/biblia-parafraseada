# Projeto Bíblia Estudos - Parafraseados

[![GitHub](https://img.shields.io/badge/GitHub-Reposit%C3%B3rio-blue?logo=github)](https://github.com/c4tom/biblia-parafraseada/)

## Sobre o Projeto

O Projeto Bíblia Estudos é uma iniciativa que visa proporcionar recursos abrangentes para o estudo da Bíblia, com o objetivo de auxiliar qualquer pessoa a compreender melhor as Escrituras. Este projeto foi desenvolvido com o compromisso de manter-se fiel ao texto bíblico original, evitando vieses teológicos enraizados que possam contradizer a teologia bíblica fundamental. A regra fundamental é a própria Bíblia se explicar. Porém, também sabemos que para um melhor entendimento (pode não ser completo), devemos também conhecer o contexto histórico e cultural do local.

A versão inicial foi gerada pela IA Gemini 2.5 flash, [`ficha.md`](ficha.md) e [`parafraseadas.md`](parafraseadas.md) são os arquivos usados para auxiliar a IA na geração do conteúdo.

## Conteúdo do Projeto

O projeto contém os seguintes recursos:

1. **Fichas de Estudo**: Documentos detalhados para cada livro da Bíblia, contendo informações sobre autor, data, contexto histórico, temas centrais, lições espirituais, aplicações práticas e muito mais.
2. **Textos Parafraseados**: Versões parafraseadas de capítulos bíblicos que mantêm fidelidade ao sentido original, mas apresentam o texto em linguagem mais acessível, incluindo:

   - Contexto histórico
   - Blocos temáticos
   - Paráfrases verso a verso
   - Referências cruzadas
   - Comentários explicativos
   - Temas e personagens identificados
3. **Resumos**: Sínteses concisas de livros ou capítulos bíblicos para facilitar a compreensão geral.
4. **Dados Estruturados**: Arquivos JSON contendo informações detalhadas sobre os livros da Bíblia, incluindo número de capítulos e versículos.

## Propósito

Este projeto tem como propósito:

- Facilitar o acesso ao conteúdo bíblico em formato estruturado e compreensível
- Fornecer contexto histórico e cultural para melhor entendimento do texto
- Apresentar conexões entre diferentes partes da Bíblia
- Destacar temas e ensinamentos centrais
- Promover o estudo bíblico baseado no texto original, evitando interpretações tendenciosas

## Como Utilizar

Os arquivos estão organizados da seguinte forma:

- [`ficha.md`](ficha.md): Template para criação de fichas de estudo de livros bíblicos
- [`pt/livros.json`](pt/livros.json): Dados estruturados de todos os livros da Bíblia
- [`parafraseadas.md`](parafraseadas.md): Instruções para criação de paráfrases bíblicas
- [`pt/bible_downloads.json`](pt/bible_downloads.json): Referência para desenvolvedores de aplicativos bíblicos, contendo links para diferentes traduções da Bíblia em formato SQLite. Útil para implementação de recursos de comparação entre traduções em aplicativos.
- `pt/parafraseadas/`: Diretório contendo paráfrases de capítulos bíblicos em formato JSON
- `pt/parafraseadas/\<livro abreviado\>/resumo.json`: Arquivo contendo resumos de livros ou capítulos bíblicos

## Idiomas Suportados

Para facilitar a internacionalização do projeto, utilizamos as seguintes siglas de idiomas (ISO 639-1) para os idiomas mais falados no mundo:

| Sigla | Idioma     | Nome Local                      |
| ----- | ---------- | ------------------------------- |
| en    | Inglês    | English                         |
| zh    | Chinês    | 中文 (Zhōngwén)               |
| hi    | Hindi      | हिन्दी (Hindī)           |
| es    | Espanhol   | Español                        |
| fr    | Francês   | Français                       |
| ar    | Árabe     | العربية (al-ʿarabīyah) |
| bn    | Bengali    | বাংলা (Baṅla)             |
| ru    | Russo      | Русский (Russkiy)        |
| pt    | Português | Português                      |
| id    | Indonésio | Bahasa Indonesia                |
| ja    | Japonês   | 日本語 (Nihongo)                |
| de    | Alemão    | Deutsch                         |
| pa    | Punjabi    | ਪੰਜਾਬੀ (Pajābī)         |
| jv    | Javanês   | Basa Jawa                       |
| ko    | Coreano    | 한국어 (Hangugeo)               |
| vi    | Vietnamita | Tiếng Việt                    |
| te    | Telugu     | తెలుగు (Telugu)           |
| tr    | Turco      | Türkçe                        |
| it    | Italiano   | Italiano                        |
| fa    | Persa      | فارسی (Fārsi)             |

Ao contribuir com traduções, utilize estas siglas para nomear os arquivos e diretórios, seguindo o padrão: `[sigla_idioma]/[nome_arquivo]`

## Como Contribuir

Contribuições para este projeto são muito bem-vindas! Siga estas etapas para contribuir:

1. **Fork do Repositório**

   - Acesse o repositório no GitHub
   - Clique no botão "Fork" no canto superior direito
   - Isso criará uma cópia do repositório em sua conta GitHub
2. **Clone o Repositório**

   ```bash
   git clone https://github.com/seu-usuario/biblia-parafraseada.git
   cd biblia-parafraseada
   ```
3. **Crie uma Branch para sua Contribuição**

   ```bash
   git checkout -b minha-contribuicao
   ```
4. **Faça suas Alterações**

   - Para adicionar uma nova paráfrase, siga o formato em [`parafraseadas.md`](parafraseadas.md)
   - Para corrigir conteúdo existente, mantenha a estrutura original
   - Certifique-se de que os arquivos JSON sejam válidos e estejam em formato UTF-8
5. **Teste suas Alterações**

   - Verifique se os arquivos JSON são válidos
   - Certifique-se de que o conteúdo está de acordo com as diretrizes do projeto
6. **Commit e Push**

   ```bash
   git add .
   git commit -m "Descrição clara da sua contribuição"
   git push origin minha-contribuicao
   ```
7. **Crie um Pull Request**

   - Acesse o repositório original
   - Clique em "New Pull Request"
   - Selecione sua branch com as alterações
   - Descreva detalhadamente suas alterações
   - Envie o Pull Request

### Diretrizes para Contribuição

1. **Fidelidade ao Texto Bíblico**: Mantenha-se fiel ao sentido original do texto bíblico.
2. **Neutralidade Teológica**: Evite inserir interpretações teológicas específicas que não estejam claramente expressas no texto.
3. **Clareza e Acessibilidade**: Busque tornar o texto compreensível para leitores de diferentes níveis de conhecimento bíblico.
4. **Precisão Histórica**: Ao fornecer contexto histórico, baseie-se em fontes acadêmicas confiáveis.
5. **Formatação Consistente**: Mantenha a estrutura e formatação consistentes com o restante do projeto.

## Tipos de Contribuições Bem-vindas

- Correções de erros ortográficos ou gramaticais
- Melhorias na clareza das paráfrases
- Adição de referências cruzadas relevantes
- Expansão de comentários explicativos
- Adição de novos capítulos parafraseados
- Melhorias na estrutura dos arquivos JSON
- Traduções para outros idiomas

## Direitos Autorais

Este projeto não possui restrições de direitos autorais específicas. O responsável pelo projeto é Candido H Tominaga.

O conteúdo deste projeto pode ser utilizado, compartilhado e adaptado livremente, desde que seja dado o devido crédito ao projeto original e seu responsável.

## Contato

Para dúvidas, sugestões ou mais informações sobre o projeto, entre em contato com o responsável, Candido H Tominaga, através do GitHub. Você pode fazer isso de várias maneiras:

1. **Abrindo uma Issue**:

   - Acesse a aba "Issues" no repositório
   - Clique no botão "New Issue"
   - Preencha um título descritivo e detalhe sua dúvida ou sugestão
   - Adicione as etiquetas (labels) apropriadas, se disponíveis
   - Envie a issue
2. **Comentando em Issues existentes**:

   - Procure por issues relacionadas ao seu tema
   - Adicione seu comentário contribuindo para a discussão
3. **Através de Pull Requests**:

   - Ao enviar um Pull Request, você pode incluir perguntas ou comentários na descrição
   - Use a seção de comentários do PR para discussões específicas
4. **Discussions** (se habilitado):

   - Verifique se a aba "Discussions" está ativa no repositório
   - Inicie uma nova discussão na categoria apropriada

---

*"Toda a Escritura é inspirada por Deus e útil para o ensino, para a repreensão, para a correção, para a educação na justiça." - 2 Timóteo 3:16*
