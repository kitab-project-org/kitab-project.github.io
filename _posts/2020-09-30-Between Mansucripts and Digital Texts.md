---
header:
  image: /images/posts/2020-9-30/Image-4.jpg
  caption: "**Photo credit**: The beginning of Shaykh Ahmad al-Ahsaʾi’s Sharh from a composite manuscript (Rasaʾil, mostly by al-Ahsaʾi, copied in 1821, in Rubat-i Pusht-i Badam village, Yazd province) with Saʿid al-Qummi’s commentary written on the margins of fol. 126b-142a more than a century later in Tehran (1934). Courtesy of Princeton University Library."
title:			"Between Manuscripts and Digital Texts: Commentaries on Hadith Raʾs al-Jalut"
author:		aslisho_qurboniev
layout:		single
categories:
  - Text reuse
  - Arabic
tags:
  - Blogpost
---

As digital historians and corpus curators, faced with the complex history of reception and transmission as well as the distinct approach to learning and authorship, attributing authors to premodern Islamicate texts and representing this complexity within our corpus metadata is often a challenging task. Especially daunting for composite texts, commentaries, and super-commentaries, the task is no less challenging when it comes to working with printed editions and online digital libraries, since we face the risk of reproducing editorial choices, and biases, whether knowingly or unknowingly.

Most scholars are as cautious about digital editions as they are about uncritical printed editions. The manuscript, not the printed edition, is seen as the least mediated and most reliable link with the author, because even the most carefully edited texts are not free from editorial interventions. Most readers will be inclined to ignore the critical apparatus and go with the editor’s preference. Digital editions and e-books, however, tend to omit the critical apparatus. Moreover, many digital texts are typed by hand, and their origin and ‘witness’ printed editions are obscure. This adds to the challenges of curating a digital corpus with reliable metadata. In addition to text reuse data, accurate metadata is essential for mapping the Islamicate written heritage in a way that reflects its intertextuality and discursiveness. During the ongoing pandemic physical libraries were not accessible for several months, which created a perfect occasion to reflect on the reliability of digital texts available on the Internet. I will share the case of a modern gloss (taʿliqa) on a seventeenth-century hadith commentary (sharh hadith) in the OpenITI, and follow its journey from manuscript libraries to print, to online digital libraries, and finally to our corpus.

## **Al-Taʿliqa ʿala al-Fawaʾid al-Radawiyya: A Gloss on a Commentary**

Author assignment issues are common in OpenITI corpus metadata, and are often settled easily. However, my chance encounter with a text titled al-Taʿliqa ʿala al-Fawaʾid al-Radawiyya took me on a longer journey than expected.  The Taʿliqa (Gloss), which originated from the Shia Online Library (http://shiaonlinelibrary.com), was assigned in the metadata to the Safavid polymath Qadi Saʿid al-Qummi (d. after 1107/1695), known as Hakim-i Kuchek (The Lesser Sage), who was a student of the famous traditionist Mulla Muhsin Fayd-i Kashani (d. ca. 1091/1680), and personal physician to Shah ʿAbbas II (r. 1052-77/1642-66). After going through the text, I realised that the metadata, as captured below in Figure 1, was misleading. The text was dominated by glosses by the leader of the Islamic Revolution of Iran, Ayatollah Ruhollah Khomeini (d. 1989), on Qadi Saʿid al-Qummi’s original text. Qadi Saʿid al-Qummi’s  text was a commentary on a short dialogue between the eighth Twelver Shi’i imam ʿAli b. Musa al-Rida (d. 203/818) and a Jewish Exilarch (Raʾs al-Jalut = Resh Galuta in Hebrew). The intriguing glosses by the young Ruhollah Khomeini, written in August 1929 during a summer retreat “from the glorious Qum, due to the heat  and suspension of classes,” in his hometown of Khomein, included an introduction and a conclusion, as well as substantial comments and even objections to Qadi Saʿid al-Qummi. It was clear that the Taʿliqa should be attributed to Khomeini, the last commentator, rather than to Saʿid al-Qummi. The metadata of the digital library thus omitted the history of the commentary tradition, and only partially corresponded to the manuscript and to the printed edition. If we take a closer look at the reception of the Sharh and the manuscript tradition, it will become clear why metadata matters for corpus analysis.

(See  below screenshots from Shia Online Library and OpenITI corpus).

![Figure 1](/images/posts/2020-9-30/Image-1.png)

> **Figure 1.** Shia Online Library assigns the Taʿliqa to Saʿid al-Qummi despite the printed edition’s attribution of the text to Ruhollah Khomeini.

![Figure 2](/images/posts/2020-9-30/Image-2.png)

> **Figure 2.** A screenshot of the OpenITI corpus metadata prior to correction. Now the application has Ruhollah Khomeini as the author, since we list the final author within the application. (See the [KITAB Corpus Arabic Metadata App]( https://kitab-corpus-metadata.azurewebsites.net)). Users can also report similar mistakes via the system.

![Figure 3](/images/posts/2020-9-30/Image-3.jpg)

> **Figure 3.** The completed YML-form of the Taʿliqa in the OpenITI corpus. Curating the corpus includes annotating, creating reliable metadata, reporting issues, and vetting by the KITAB team. The updated URI is 1409RuhAllahKhumayni.TacliqaCalaFawaidRadawiyya.Shia04006-ara1.

## **The Manuscript Tradition**

Sharh Hadith Raʾs al-Jalut, originally titled al-Fawaʾid al-Radawiyya, is a treatise by Saʿid al-Qummi from his incomplete Arbaʿinat (forty treatises on various subjects), which has been published separately. It constitutes al-Qummi’s commentary on ʿAli b. Musa al-Rida’s answers to questions asked by the Jewish Exilarch. While overwhelming and converting a Jewish scholar is a known topos in Muslim literature, the presence of a Jewish Exiliarch in a medieval Muslim society is not a fiction. Geniza materials testify that the office of Exiliarch continued at least until the fall of Baghdad to the Mongols in 1258 (Gafni, 1999). More elaborate versions of the interreligious debates of Imam Rida at the court of al-Maʾmun were first related by Ibn Babawayh (d. 329/991) in his Kitab al-Tawhid and ʿUyun akhbar al-Rida. These debates are well known and have been analysed by several scholars (Wassertrom, 1995; Wasserstein, 1999; Cooperson, 2004; Sahner, 2019). It is however this short enigmatic version preserved by al-Qummi that gave rise to a separate commentary tradition.

Only nine commentaries on Hadith Raʾs al-Jalut had been previously identified (Muhammad Rida Husayni, 1999). Via the recently launched online manuscript catalogue by the National Library and Archives of Iran (NLAI) (https://hmi.nlai.ir/), I have located 15 different commentaries bringing the total number of records of different manuscripts of the commentaries to 132, most of them authored and copied during the 19th century (12th-13th centuries AH) in Iran. This online catalogue, which is based on previously published catalogues, is very rich, but still lacks some essential metadata information, such as the authors’ dates of death or the language of the text. There are also identical records, for no apparent reason, such as 8 duplicates for various manuscripts of the Sharh Hadith Raʾs  al-Jalut. Of course, given the challenges of this material and the current state of research, one assumes that not all manuscripts included in compilations have been correctly identified and catalogued. Nonetheless, the “National  Memory of the Iranians” Project of the NLAI, which catalogues more than 1 million manuscripts from 1,868 libraries around the world, is unparalleled in its scope and ambition and I think the present exercise proves this point.

To have an idea about the diversity and complexity of the hadith commentary tradition, let us look at the following example (Figure 4). Here, Saʿid al-Qummi’s late 17th-century commentary is written on the margins of Ahmad b. Zayn al-Din al-Ahsaʾi’s 19th-century commentary, in 1934 (1313 Persian solar calendar) by a certain Murtada b. Muhammad Sadiq al-Tabasi, known as Farhang. This use of the margins is hardly because of the shortage of paper in Tehran at the time. Farhang clearly thought the two texts should be read together. However, this kind of intertextuality, fluidity, and discursiveness, which is characteristic of the manuscript culture, almost always becomes obsolete after the transition to printing.

![Figure 4](/images/posts/2020-9-30/Image-4.jpg)

> **Figure 4.** The beginning of Shaykh Ahmad al-Ahsaʾi’s Sharh from a composite manuscript (Rasaʾil, mostly by al-Ahsaʾi, copied in 1821, in Rubat-i Pusht-i Badam village, Yazd province) with Saʿid al-Qummi’s commentary written on the margins of fol. 126b-142a more than a century later in Tehran (1934). Courtesy of Princeton University Library.

| | Commentators | Date of death | Titles | Number of manuscript copies|
|---|---|---|---|---|
|1|Qadi Saʿid al-Qummi Muhammad-Saʿid b. Muhammad-Mufid|1107/1695|Al-Fawaʾid al-Radawiyya|63|
|2|Mulla ʿAbd al-Rahim b. Muhammad-Yunus  al-Damawand| 1158/1745|Sharh Hadith  Raʾs al-Jalut|7|
|3|Mulla Mahdi b. Abi Dhar al-Naraqi|1210/1795|Sharh Hadith  Raʾs al-Jalut|2|
|4|Mirza Abu’l-Qasim b. Hasan al-Jilani al-Qummi|1231/1816|Sharh Hadith  Raʾs al-Jalut|18|
|5|Muhammad-Baqir b. Muhammad, Mullabashi Shirazi|1240/1824|Sharh Hadith  Raʾs al-Jalut|3|
|6|Shaykh Ahmad b. Zayn al-Din al-Ahsaʾi|1243/1826|Sharh Hadith  Raʾs al-Jalut|19|
|7|Shaykh Muhammad b. Haj Muhammad-Hasan al-Mashhadi al-Tusi|1257/1841|Ghanimat al-Hijaz fi hall al-alghaz|1|
|8|Muhammad-Ismaʿil b. Muhammad-Jaʿfar al-Isfahani|1280/1863|Sharh Hadith  Raʾs al-Jalut|2|
|9|Mulla Muhammad b. Ahmad b. Mulla Mahdi al-Naraqi, known as ʿAbd al-Sahib|1297/1880|Sharh Hadith  Raʾs al-Jalut|5|
|10|Muhammad-Hasan b. Ahmad Nazari|fl. 13th/19th century|Sharh Hadith Raʾs al-Jalut|2|
|11|Najafquli Anjudani|fl. 13th/19th century|Sharh Hadith  Raʾs al-Jalut|1|
|12|Sayyid-ʿAli b. Muhammad-ʿAli, Husayni Meybudi|1313/1895|Sharh Hadith  Raʾs al-Jalut|2|
|13|Muhammad-Husayn b. ʿAbd Allah al-Isfahani|1362/1943?|Sharh Hadith  Raʾs al-Jalut|3|
|14|Anonymous| |Sharh Hadith  Raʾs al-Jalut|3|
|15|Ayatollah Ruhollah Khomeini|1409/1989|al-Taʿliqa ʿala al-Fawaʾid al-Radawiyya|1|
| |**Total**| | |132|

> **Table 1.** A list of all known commentaries on Hadith Raʾs al-Jalut with the  number of manuscripts that I could locate for each commentary in manuscript libraries (including multitext compilations). The earliest was written by Qadi Saʿid al-Qummi in 1099/1688, while the last one, Khomeini’s Taʿliqa, was written in 1348/1929.

To my knowledge, only three of the above-listed commentaries, including Khomeini’s Taʿliqa,  have been published  (see References below). These are also available in digital format. Some manuscripts are probably still uncatalogued and unknown. For instance, just 5 commentaries were identified by Agha Buzurg Tehrani (d. 1970) in his comprehensive al-Dhariʿa ila Tasanif al-Shiʿa. Only with the rapid digitalisation we are beginning to get a better view of the Islamicate textual tradition. But we have yet to fully realise how our understanding  of premodern book culture has been formed, and in many  ways limited, by what is available in print. Let us consider some of these limitations taking the Taʿliqa as an example.

## **The Digital Text of the Taʿliqa in the OpenITI corpus**

The digital text of the Taʿliqa fin our corpus has inherited several deficiencies from the printed edition, on which it is based, and adds more:

 .The text of the original commentary by Saʿid al-Qummi and the gloss by Ruhollah Khomeini are not marked clearly.
 .The original colophon by the author and a note by the copyist, a certain al-Lawasani, are both present, but they are not marked clearly. In this case, the printed edition follows the manuscript copy.
 .In the manuscript, the glosses are reproduced on the margins of the original commentary, which is not how they are reproduced in printed editions. Glosses are either moved to footnotes, or printed on the same page  following  the main text, sometimes without proper visual signposts, which is the case with the present edition. This makes it difficult to see where the Sharh ends and where the Taʿliqa begins. The digital text in the OpenITI, which is based on this edition, thus presents challenges for computational analysis. On the other hand, digital technology provides exciting possibilities for visual presentation of the text, including side by side reading, which will be available for the  OpenITI in the future.
 .The metadata consists only of the title of the book and the name of the original commentator (Qadi Saʿid al-Qummi). Other essential information about him and the second commentator (Ruhollah Khomeini); the dates and places of writing and copying (i.e. Isfahan, 14 Rabiʿ al-Awwal 1099 AH or Khomein, 22 Rabiʿ al-Awwal, 1348 AH); the provenance of the manuscript; genre; topics; etc. is not provided.

In the ideal case scenario, all extant texts and commentaries of the ‘hadith Raʾs al-Jalut’ should be included in the corpus, including the version preserved and commented upon by Saʿid al-Qummi, and the more distant and complete versions of the debates by Shaykh Saduq in his Kitab al-Tawhid and ʿUyun akhbar al-Rida. Secondly, all the commentaries (more than a dozen, mostly in manuscript form) should be transcribed and converted  into machine-readable format, added to the corpus, and the relationship between the texts should be recorded in the metadata. It is worth noting that the commentaries engage with other material besides strictly Shiʿi doctrines. As we can see from the citations and references in al-Qummi’s Commentary and Khomeini’s Gloss, the authors are not only in conversation with the Qur’an, the Prophet and the Shiʿi imams, but are also in conversation with Aristotle, Neo-Platonists, the Ikhwan al-Safa, Ibn ʿArabi, post-classical Muslim philosophers and mystics among others. This is where the strength of text reuse method in mapping the intellectual tradition comes in. The real potential of the corpus approach and distant reading, of course, lies in the ability to go through a vast number of books and return all potentially related material.

In this case, after I raised the issue via an online system, the corpus manager, Lorenz Nigst, implemented the changes to the authorship of the work in the URI and metadata. In more ambiguous cases, the issue would be discussed at one of the corpus meetings with team members. To facilitate further research, all relevant information about the transmission of the text, authorship, provenance, and its explicit relationship to other texts in the corpus (e.g. between al-Ghazali’s Tahafut al-falasifa and Ibn Rushd’s response, Tahafut al-Tahafut) are recorded in the metadata. That being said, the attribution of a unique identifier (URI) and metadata constitutes neither a final verdict nor a scholarly position on the authorship of a given text. By checking for quality and consistency of the metadata, the project team  hopes to ensure the reliability of the corpus as a starting point for researchers.

The case of Hadith Raʾs al-Jalut thus illustrates the challenges of corpus-building and referencing of Islamicate texts in a way that reflects the history of their reception and transmission. Specifically, it highlights the complexities of assigning authorship to composite materials such as commentaries and glosses. Engaging with the content of the commentaries, while beyond the scope of this blog, would also reveal that hadith commentaries are highly intertextual and engage with a variety of topics and disciplines, including philosophy and mysticism. Moreover, hadith commentary is a living and discursive Islamic tradition that flourishes to date. Finally, this example reminds us of the fact that most hadith commentaries are still in manuscript form, while modern commentaries, especially those on the digital platforms and TV channels, are  increasing by the day.

## **References to  primary sources**

Khomeini, Ruhollah. *al-Taʿliqa ʿalā al-Fawaʾid al-Radawiyya*, 2nd edition, Tehran, 1378/1999.

Husayni, Sayyid Muhammad-Rida. “Sharh-i Hadith-i Raʾs al-Jalut”, *Mirath-i Hadith-i Shiʿa* 2 (1378/1999), pp. 233-54. This is an edition of  Mulla ʿAbd al-Sahib al-Naraqi’s commentary with a short introduction by the  editor.

al-Qummi, Ibn Babawayh. *Kitab al-Tawhid*, ed. Sayyid Hashim al-Husayni al-Tihrani, Beirut, n.d., pp. 417-41; ʿUyun akhbar al-Rida, Qum,  1378/1999, vol. 1, pp. 139-82. For the earliest records of debates between Imam Rida and the Jewish Exilarch.

al-Qummi, Qadi Saʿid. *al-Arbaʿinat li-kashf anwar qudsiyyat*, ed. Najafquli Habibi, Tehran, 1381/2002. The treatise discussed in this blog was published in this collection.  Al-Qummi’s magnum opus, a three-volume commentary on Ibn Babawayh’s hadith collection, the Sharh Tawhid al-Saduq, exists in a digital edition and is currently being added to the OpenITI corpus.

## **Studies and reference works**

Cooperson, Michael. *Classical Arabic Biography: The Heirs of the Prophet in the Age of al-Maʾmun*, Cambridge, 2004, pp. 70-106.

Gafni, Isaiah M. “Exilarch,” *Encyclopaedia Iranica*, online edition, 199, available online at https://www.iranicaonline.org/articles/exilarch (accessed on 24 September 2020).

Rizvi, Sajjad H. “Qāżi Saʿid Qomi,” *Encyclopaedia Iranica*, online edition, 2005, available at http://www.iranicaonline.org/articles/qazi-said-qomi (accessed on 20 September 2020).

Sahner, Christian. “A Zoroastrian Dispute in the Caliph’s Court: The Gizistag Abalis in its Early Islamic Context,” *Iranian Studies* 52:1-2 (2019), pp. 61-83, 69-70.

Tehrani, Agha Buzurg. *al-Dhariʿa ila Tasanif al-Shiʿa*, Beirut, 1983. A comprehensive mid-twentieth century bibliography of Shiʿi works, which includes some of the commentaries known to the author. See volumes 13: 199/696, 16: 70/349, 16: 340/1581, 26: 285/1423.

Wasserstein, David J. “The ‘Majlis of al-Rida’: A Religious Debate in the Court of the Caliph al-Maʾmun as Represented in a Shiʿi Hagiographical Work about the Eighth Imam ʿAli ibn Musa Al-Rida,” in Hava Lazarus-Yafeh et al (eds), *The Majlis: Interreligious Encounters in Medieval Islam*, Wiesbaden, 1999, pp. 108-119.

Wasserstrom, Steven M. *Between Muslim and Jew: The Problem of Symbiosis Under Early Islam*, Princeton, 1995, pp. 113-119.