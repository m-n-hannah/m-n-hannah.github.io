---
title:  "Zotero and VosViewer"
mathjax: true
layout: post
categories: workshops, digital humanities
---

![Image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS2TWU2YSbuTE7ghzvYweUQ1z7Ibfsm4c7rWQ&usqp=CAU)

VosViewer is a tool for conducting bibliometric analysis. Bibliometrics is a field of study which focuses on the analysis of citations and keywords assocated with scholarly publishing. Such tools can help scholars understand the topography of the scholarly conversation as it appears in the literature. VosViewer works directly with several databases such as Scopus and Web of Science, but it also interfaces with Zotero or other citation management software. Users can collect their own library and then visualize the metadata using VosViewer.

Note: I have provided a sample dataset so you don't need to complete the Zotero step if you don't want to...

PART 1: ZOTERO
* Download [Zotero](https://www.zotero.org/download/) and the Chrome Extension.

![vos1](https://user-images.githubusercontent.com/22083340/156243570-6da9f0c8-1ee0-4612-b217-ebe85a1e75c7.png)

* Once you've downloaded the Zotero app and the Chrome extension, you can easily save the citation of any object to your Zotero Library. You will want to open Zotero, create a folder, and leave it open.

* Navigate to your library page and select a book or article. You can save the metadata to your Zotero by clicking the extension button in the top right corner of your browser.

![vos2](https://user-images.githubusercontent.com/22083340/156244019-6a104a92-1e05-458b-8359-eec8bfdffd5c.png)

* Once you've saved a few items to your library, select all and click export. You'll want to export as RIS file.

![vos3](https://user-images.githubusercontent.com/22083340/156244483-cf2f681d-5604-45ba-a9a2-0f621bdc6790.png)

* Download the RIS file. You can then upload it into VosViewer.

* PART 2: VOSVIEWER
* You can either download [VosViewer](https://www.vosviewer.com/download) or use the web based version [here](https://www.vosviewer.com/).
* Click Create and Select your Data Source.

![vos4](https://user-images.githubusercontent.com/22083340/156246651-6fc44e29-2738-4333-b859-01dea2ac672d.png)

* Then select RIS.

![vos5](https://user-images.githubusercontent.com/22083340/156246840-467ca69e-4841-4b31-81c1-841ab42abce8.png)

* You will need to select the folder on your computer where the RIS file is located and select it.

![vos6](https://user-images.githubusercontent.com/22083340/156247700-89408f16-f7e8-4f9d-81a4-c74f305d4ab6.png)

* Then select your analysis. Co-authors is useful for a collection with multiple authors publishing together to measure the biggest collaborators. Keyword co-appearance is useful for measuring the linkages between keywords i.e. keywords that appear together often.

![vos7](https://user-images.githubusercontent.com/22083340/156247923-aad5550e-a879-45ed-a9b5-ec68e9b3515e.png)

* Once done, you should see a network of connections between keywords or authors that appear together. VosViewer will automatically assign these nodes to clusters based on their mutual linkages, with each cluster receiving its own color.

![vos8](https://user-images.githubusercontent.com/22083340/156248206-8ce04fed-ab7b-4bba-a6f6-6e4d5aea5b4d.png)

* You can also look at a heatmap of the network or a temporal map, which shows the data based on publication year. Select the Overlay Visualization (time) or Density Visualization (heat map) to see these networks.

![vos9](https://user-images.githubusercontent.com/22083340/156248699-287e23a2-fb58-49b3-a0b3-989dd39d6f5f.png)

* You can also run some basic statistical analysis and view the items in your collection as VosViewer assigned them to clusters by selecting the side tabs.

![vos10](https://user-images.githubusercontent.com/22083340/156248915-078e571e-8d76-452a-9715-9fe21dc465e7.png)

* Colors and shapes can be customized in the visualization window along the right side of the screen. Once you're happy with your network visualization you can either take a screenshot or save the files used to create the visualization to be used next time you open VosViewer.

* PART 3: Using Web of Science or Scopus
* Navigate to a database your library has access and that VosViewer can access: Scopus, Web of Science, Dimensions, Lens, or PubMed.

![image](https://user-images.githubusercontent.com/22083340/158799663-8ad55732-f007-4b9e-8687-02dd3d8b9c3c.png)

* Search for articles in that database.

* Select the articles you want and select export.

![image](https://user-images.githubusercontent.com/22083340/158799813-03f092bc-c37c-47eb-9c16-2dd4cb086561.png)

* Export as plain text with Full Record and Cited References.

![image](https://user-images.githubusercontent.com/22083340/158799892-5b4c866b-1b8e-46c9-9047-c8e85560e2c2.png)

* Select "Create a Map Based on Bibliographic Data" in VosViewer.

![image](https://user-images.githubusercontent.com/22083340/158799985-7c8c3238-65b4-47f9-b08e-9a82d46d4951.png)

* Select "Read Data from Bibliographic Database File."

![image](https://user-images.githubusercontent.com/22083340/158800084-1cfb5b55-f74b-493b-8846-0970ad3fc979.png)

* Navigate to your text file.

* You should now have access to the database's data for citation and co-citation analysis in addition to the other metrics based on the full reference.

![image](https://user-images.githubusercontent.com/22083340/158800201-ff074719-f63d-454d-841c-16a098300f36.png)

* When you are done modifying your network, you can export it as VosViewer network and map files, which can be uploaded back into VosViewer. You can also take a screenshot of your network diagram:





