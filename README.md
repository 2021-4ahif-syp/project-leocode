# LeoCode C#

## Autoren: 
Besic Benjamin, Ignjatovic David, Raid Yimne, Spasenovic Bozida

## GH-Pages

[Projektauftrag](https://2021-4ahif-syp.github.io/project-leocode/Projektauftrag.html)

## Publish GH-Pages

> ``.\part1.sh``

> ``docker run --rm -v ${PWD}/docs:/documents asciidoctor/docker-asciidoctor /bin/bash -c "asciidoctor -r asciidoctor-diagram -a icons=font -a experimental=true -a source-highlighter=rouge -a rouge-theme=github -a rouge-linenums-mode=inline -a docinfo=shared -a imagesdir=images -a toc=left -a toclevels=2 -a sectanchors=true -a sectnums=true -a favicon=themes/favicon.png -a sourcedir=src/main/java -b html5 '*.adoc' && rm -rf ./.asciidoctor && echo Done"``

> ``.\part2.sh``

> ``.\finisher.sh``
