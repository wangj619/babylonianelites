---
title: Methodology
layout: about
permalink: /methodology.html
---
{% include feature/nav-menu.html sections="Methodology; Applying SNA to Cuneiform Archives" %}

## Methodology

Social Network Analysis (SNA) is used as the basic tool. Networks are built of individuals attested in the texts linked by their co-occurrence within the same text. These networks are meaningful because the individuals who appear together in a text are in some sort of contact with each other. All of them are involved in the same transaction, whether as parties to it, or as witnesses or scribe. The more frequently they appear together, the closer the relationship. Through the network visualization, individuals and families of special network positions, such as centers and bridges between communities will be detected. Properties of networks of certain individuals or comminities, for example, density, will be compared. 

## Applying SNA to Cuneiform Archives

The family archives consist of contracts and court documents, sometimes letters. The individuals are attested in the archives as the principal parties, such as debtor, creditor, guarantor, buyer or seller of properties; and they served as witnesses and scribes as well. Therefore, individuals in the same text are in some sort of relationship. If some of them appear together in multiple texts, they have a closer relationship. I will take one text as an example to detail the process.

{% include feature/card.html text="[1/3(?)] mina 6 1/2 shekels [of white silver belonging to Ina]-Esagil-ramat, daughter of Balaṭu, descendant of Egibi, is the debt of [Iq]iša-Marduk, son of Nabu-balassu-iqbi, [descendant of] Nappahu. In the month of Ululu he will pay the 1/3(?) mina 6 1/2 shekels of silver. Witnesses: Bel-iddin, son of Nadin-ahi, descendant of Maštukku; Remutu, son of Šulaya, descendant of Baʾiru; Nabu-mukin-zeri, son of Mušallim-Marduk, descendant of Nappahu; [Mušallim-Marduk], scribe, son [of Š]uzubu, [descendant of Kanik-babi]. Babylon, [19th(?) day of] Abu, [2nd(?) year of] Dari[us, king of Babylon, king of the lands]. (VAT 518)" header="Example text" width="50" centered=true %}

From this text, we can get data like this. This form is made through the website Prosobab. So we have seven persons attested in this text. We can omit the king, because he did not actually participate in the network. His name was just used in the date. Therefore, we have six persons. Each of them is connected with others in this text.

{% include feature/image.html objectid="/assets/img/prosobabdata.jpg" width="50" %}

Importing the data into the software Gephi, we can have a network like this.

{% include feature/image.html objectid="/assets/img/sixpersons.jpg" width="50" %}