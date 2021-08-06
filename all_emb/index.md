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

# yt

![](@youtube/https://www.youtube.com/embed/dQw4w9WgXcQ)

# link pdf

[Vergadering pdf!](vergadering.pdf)

# link audio

[Momo!](momo.mp3)

# link yt

[Ricky!](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

# pdf

![](@pdf/vergadering.pdf)

# blocks

![](@blockly/blocks.xml)

# Jupyter notebook

![](@notebook/https://www.cantera.org/examples/jupyter/thermo/flame_temperature.ipynb)


# audio

![](@audio/momo.mp3)


# link leerobj

[link](@learning-object/61095afee86675212fd03da7 "dit is een leerobject")


# leerobj
![](@learning-object/61095afee86675212fd03da7 )


