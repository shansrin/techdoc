---
title: "Generating HTML and PDF Document"
date: 2017-10-17T15:26:15Z
draft: false
weight: 20
---

Generating HTML and PDF document
================================

1.  Open the window terminal and type the command to install asciidoctor
    and pdf folder:

        gem install asciidoctor
        gem install asciidoctor-pdf --pre

    ![Gem\_install\_asciidoctor](../Images/Gem_install_asciidoctor.png)

2.  Type the below command to generate html and pdf

        ascidoctor *.adoc
        .\[filename].html
        : asciidoctor -r asciidoctor-pdf -b pdf [name].adoc
