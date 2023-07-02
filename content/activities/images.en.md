---
title: "Intelligent image recognition"
description: "The major task of the system core - is converting images into descriptions, which artificial intelligence can operate. These descriptions allow the system to search, recognize, analyze image content, tag and perform other tasks, assigned by the user."
weight: 4
---

{{< paragraph align="center" size="50" >}}
{{<figure url="/media/activities/pic4.jpg">}}
{{< /paragraph >}}

{{< paragraph align="justify" size="50" >}}
{{% markdownify %}}
The project "Computer Vision" develops intelligent image analysis systems. Nowadays artificial intelligence has capability of recognizing both words and graphical images. Description of heterogeneous graphical data set in terms of human concepts allows us:

- to describe images semantically;
- to tag images automatically;
- to implement search and image ranking.
{{% /markdownify %}}
{{< /paragraph >}}

{{< paragraph align="justify" size="100" >}}
{{% markdownify %}}
## Operation description

The major task of the system core - is converting images into descriptions, which artificial intelligence can operate. These descriptions allow the system to search, recognize, analyze image content, tag and perform other tasks, assigned by the user.

The process of image analysis involves several stages. At the first stage pre-processing and preparation of the image for further work is performed. The image is entered into a database. Then the image is sent to the conveyor with processors where the main analysis is implemented. To ensure proper analysis dynamically linked modules are launched. These modules are segmentation module, detection module, classification module, the module of assigning properties and spatial relationships. Whereas some of the modules operate autonomously, the others are launched in a strict sequence and operate as a whole unit.

Modules – processors contain certain preprocessing (size and color conversion, bar chart harmonization, color reduction etc.). Then Computer Vision or Machine Learning algorithms start operating. The result of their operation is the graph "Thing-Property-Relation" (`VSO`) unified for all projects.

Processing results are entered into a database for further work.
{{% /markdownify %}}
{{< /paragraph >}}

{{< paragraph align="justify" size="100" >}}
{{% markdownify %}}
## The tasks it solves

The system core allows us to describe image content according to the following criteria:

- face recognition and face detection;
- identification of scenes and genres (portrait, nature, forest, town, texts);
- quality evaluation (accuracy and color);
- text definition and text recognition;
- data processing from exif: coordinates, date, parameters of shooting;
- duplicate finding.
{{% /markdownify %}}
{{< /paragraph >}}

{{< paragraph align="justify" size="100" >}}
{{% markdownify %}}
## The products developed on the basis of the system
{{% /markdownify %}}
{{< /paragraph >}}

{{< paragraph align="justify" size="100" >}}
{{< headerborder title="44to-archive" >}}
{{< /paragraph >}}

{{< paragraph align="justify" size="100" >}}
{{% markdownify %}}
The product allows for convenient storage, sort and personal photo gallery representation. By using Computer Vision or Machine Learning algorithms all the images in the database are indexed and prepared for fast sorting and selecting according to set parameters.

The main functions of 44to-archive:

- semantic image description;
- sorting, filtration, image selection;
- open API, available for other projects.
{{% /markdownify %}}
{{< /paragraph >}}

{{< paragraph align="justify" size="100" >}}
{{< headerborder title="FotoFabule" >}}
{{< /paragraph >}}

{{< paragraph align="justify" size="100" >}}
{{% markdownify %}}
After processing and indexing an image from the personal user’s gallery, vacant spaces in the template "history" are filled in automatic mode and then submitted to the user.

The main functions of the "Fotofabule":

- automated fotohistory formation;
- "smart" narration templates;
- automated foto selection according to the meaning.
{{% /markdownify %}}
{{< /paragraph >}}
