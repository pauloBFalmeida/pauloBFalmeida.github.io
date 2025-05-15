# Particle Jekyll Theme

Cloned theme from [Particle Theme in git](https://github.com/nrandecker/particle.git)

## License

This theme is free and open source software, distributed under the The MIT License. So feel free to use this Jekyll theme anyway you want.

## Running locally
`jekyll serve` to compile and start server on localhost

# Adding a project

Create a html file in

`/_projects_professional/` for professional work

`/_projects_personal/` for personal projects
```
---
layout: post
section: "html section name, cant be repeated"
order: 1

title_en: "Title En"
title_pt: "Title Pt"
title_long_en: "Longer Title En"
title_long_pt: "Longer Title Pt"

image: "/assets/img/image_name.jpg"
image_alt: "alt description image"

description_en: "A fast description for the test project, its text, and can't be too short. In en"
description_pt: "A fast description for the test project, its text, and can't be too short. In pt"
description_long_en: "long description in en"
description_long_pt: "long description in pt"

made: "Unity"
time_en: "1 week"
time_pt: "1 semana"
year: "2024"
team: "3"

access_link: "https:// link"
---
```

add the image in `/assets/img/`

image width needs to be 512px, whatever height

After that the jekyll will add automagically to the home-page and galery :)
