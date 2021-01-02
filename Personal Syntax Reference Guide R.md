# Personal Syntax Reference Guide R

**COTTON**, Richard. **Learning R**. Sebastopol, CA: O'Reilly, 2013.

**ISBN**: 9781449357108

## Preface



This is a Personal Syntax Reference Guide in R originated from the study of the respective language motivated by the growing interest in Data Science. It is important to note that the present literature is not intended for teaching data analysis, software development or programming; therefore, as a result, prior knowledge of the content is required to use it as a quick reference guide. This work has no commercial and/or profitable interest, is strictly linked to the educational and *non-selective collaboration* purpose, in addition to all copyrights remaining linked to [Richard Cotton](https://www.oreilly.com/library/view/learning-r/9781449357160/) through the bibliographic reference highlighted initially.

This work is not completed and will remain in constant development, review and additions over time with the aim of becoming comprehensive, accessible, well-edited, complete and efficient.

Feel challenged to research your own points of interest in this guide and find a brief descriptive presentation, as well as some pertinent observations, on how to use the syntax for the theme in developing your applications.

The initiative to prepare this guide arose from the absence of a copy that met my interests in presenting the content, formatting, organization and simplicity; I highlight the inspiration of Edgar Morin when developing and dealing with complex thinking in an associative, integrated and free from reductions.

**TABLE OF CONTENTS**

 1. **Help Functions**

 - Help Function, Model 01
 - Help Function, Model 02
 - Help Function, Model 03

 2. **Model Functions**

 - Demo Function, Model 01
 - Example Function, Model 01

 3. **Vignette Functions**

 - Vignette Function, Model 01
 - Vignette Function, Model 02

 4. **Apropos Function**

 - Apropos Function, Model 01

## Help Functions

The most important thing to know before you start is how to get help.

The `help` and `help.search` functions do the same things, but with them you always need to enclose your arguments in quotes.

### # Help Function, Model 01

    help("argument")

### # Help Function, Model 02

    help.search("argument")

### # Help Function, Model 03

    RSiteSearch("{argument}")

*Obs*.: use the `RSiteSearch` function if you want to search for any package in the documentation.

## Model Functions

Most functions have examples that you can run to get a better idea of how they work; use the `demo` and `example` functions for them.

### # Demo Function, Model 01

    demo(argument)

### # Example Function, Model 01

    example(argument)

## Vignette Functions

R is modular and is divided into *packages*, some of which contain *vignettes*, which are short documents on how to use the packages.

*Obs*.: the `browseVignettes` and `help.search` functions will only find items in packages that you have installed on your machine.

### # Vignette Function, Model 01

    vignette("argument", package = "argument")

### # Vignette Function, Model 02

    browseVignettes("argument")

## Apropos Function

The `apropos` function finds variables, including functions, that match your entry.

### # Apropos Function, Model 01

    apropos("argument")

*Obs*.: apropos is Latin for "A Unix program that finds manpages".


