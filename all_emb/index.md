---
hruid: test-v1
version: 3
language: nl
title: This is a title
description: This is a description
keywords: [voorbeeld, voorbeeld2]
educational_goals: [
    {source: Source, id: id}, 
    {source: Source2, id: id2}
]
copyright: Copyright by Jerro
licence: Licenced by Jerro
content_type: text/markdown
available: true
target_ages: [4, 3]
difficulty: 3
return_value: {
    callback_url: url/callback,
    callback_schema: {
        att: test,
        att2: test2
    }
}
content_location: content/location/http
---

# Test



[Dit is een link](momo.mp3 "Dit is de titel")

# Titel

![](@youtube/https://www.youtube.com/embed/dQw4w9WgXcQ)

[Vergadering pdf!](vergadering.pdf)


[Momo!](momo.mp3)


[Ricky!](https://www.youtube.com/watch?v=dQw4w9WgXcQ)


![](@pdf/vergadering.pdf)


![](@dwengo/blocks.xml)

# Jupyter notebook

![](@notebook/https://www.cantera.org/examples/jupyter/thermo/flame_temperature.ipynb)


![](@audio/momo.mp3)


![](@youtube/https://www.youtube.com/watch?v=dQw4w9WgXcQ)

[link](@learning-object/61095afee86675212fd03da7 "dit is een leerobject")


![](@learning-object/61095afee86675212fd03da7 )


