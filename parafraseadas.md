# 🔧 PROMPT 📜

Gere um arquivo JSON para representar um capítulo da Bíblia para um projeto de Bíblia parafraseada com fidelidade ao sentido original. Inserir contextualizações e explicações quando necessário. Apontar versículos paralelos que reforçam ou esclarecem o entendimento. Manter respeito e reverência ao texto sagrado. O mais importante, não usar doutrina Trinitária ou expressões que que indicam essa doutrina, pois ela não é bíblico e nem outra doutrina não bíblica.

## 📖 Instruções para Geração de Capítulos Parafraseados
A estrutura deve seguir o padrão `parafraseadas/<livro>/<capitulo>.json`, contendo:

```json
{
  "livro": "Nome do Livro",
  "capitulo": 1,
  "contexto_historico": "Explique de forma resumida o pano de fundo histórico relevante para entender esse capítulo. Se o contexto já foi explicado antes, substitua por 'Ver contexto anterior em <referência>'.",
  "bloco_tematico": "Título ou descrição do bloco temático (Ex: 'Chamado de Abraão', 'Lei moral', 'Sermão da Montanha')",
  "versiculos": {
    "1": {
      "parafrase": "Texto parafraseado com linguagem fiel e clara ao sentido original",
      "referencias": ["Gênesis 12:1-3", "Hebreus 11:8"],
      "comentario": "Explique o sentido do verso, contexto imediato e doutrinas envolvidas, se houver",
      "temas": ["Espírito Santo", "ordem", "vida"],
      "personagens": ["Deus", "Espírito de Deus"]
    },
    "2": {
      "parafrase": "...",
      "referencias": [],
      "comentario": "",
      "temas": [],
      "personagens": []
    }
    // E assim por diante
  }
}
```

Regras para a geração:

* Não inclua o texto bíblico original.
* Use uma linguagem reverente, fiel e compreensível.
* Adicione comentários e referências cruzadas onde houver relação doutrinária, tipológica ou profética.
* Se um versículo depende do anterior ou do contexto, deixe isso claro no comentário.
* Seja objetivo, mas permita riqueza interpretativa.
* Não use doutrinas não bíblicas, especialmente a Trindade ou trinitárias ou expressões que indiquem essa doutrina.
* Mantenha a estrutura JSON válida e bem formatada e seja salvo com o formato UTF-8
* Use o arquivo `livros.json` para referenciar referenciar a ordem dos livros e capítulos da Bíblia.
* Nunca sobrescreva um capítulo já existente, apenas adicione novos capítulos ou atualize os existentes se faltaram versículos ou informações.

Gere o conteúdo do capítulo: `<livro<capítulo>`

---

## 📌 Exemplo do arquivo JSON, com Gênesis 12

```json
{
  "livro": "Gênesis",
  "capitulo": 12,
  "contexto_historico": "Neste ponto da narrativa, a história da humanidade se afunila para um único homem: Abrão. Após a torre de Babel e a dispersão dos povos, Deus escolhe Abrão para formar um povo separado que levará Sua verdade ao mundo.",
  "bloco_tematico": "Chamado de Abrão",
  "versiculos": {
    "1": {
      "parafrase": "O Senhor falou com Abrão, dizendo: 'Saia da sua terra, do meio dos seus parentes e da casa de seu pai, e vá para a terra que Eu lhe mostrarei.'",
      "referencias": ["Atos 7:2-4", "Hebreus 11:8"],
      "comentario": "O chamado de Deus envolve separação e fé. Abrão não recebeu um mapa, apenas uma ordem e uma promessa. Isso tipifica a obediência da fé."
      "temas": ["Espírito Santo", "ordem", "vida"],
       "personagens": ["Deus", "Espírito de Deus"]

    },
    "2": {
      "parafrase": "Farei de você uma grande nação. Abençoarei você, engrandecerei seu nome, e você será uma bênção.",
      "referencias": ["Gálatas 3:8"],
      "comentario": "Promessa messiânica e missionária. Deus inicia Seu plano de redenção por meio de uma linhagem santa."
    }
  }
}
```

