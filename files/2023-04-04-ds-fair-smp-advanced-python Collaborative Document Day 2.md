![](https://i.imgur.com/iywjz8s.png)


# 2023-04-04-ds-fair-smp-advanced-python Collaborative Document Day 2

Welcome to The Workshop Collaborative Document.

This Document is synchronized as you type, so that everyone viewing this page sees the same text. This allows you to collaborate seamlessly on documents.

----------------------------------------------------------------------------

This is the Document for today: https://tinyurl.com/uva-library-2

Collaborative Document day 1: https://tinyurl.com/uva-library-1

Collaborative Document day 2: https://tinyurl.com/uva-library-2


## 👮Code of Conduct

Participants are expected to follow these guidelines:
* Use welcoming and inclusive language.
* Be respectful of different viewpoints and experiences.
* Gracefully accept constructive criticism.
* Focus on what is best for the community.
* Show courtesy and respect towards other community members.
 
## ⚖️ License

All content is publicly available under the Creative Commons Attribution License: [creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/).

## 🙋Getting help

To ask a question, just raise your hand.

If you need help from a helper, place a pink post-it note on your laptop lid. A helper will come to assist you as soon as possible.

## 🖥 Workshop website

https://esciencecenter-digital-skills.github.io/2023-04-04-ds-fair-smp-advanced-python-UvA/

🛠 Setup

https://esciencecenter-digital-skills.github.io/2023-04-04-ds-fair-smp-advanced-python-UvA#setup

Syllabus technical part:
https://esciencecenter-digital-skills.github.io/python-intermediate-development-uva/


## 👩‍🏫👩‍💻🎓 Instructors

Sven van der Burg, Ole Mussmann



## 🗓️ Agenda
Morning part: support staff + engineers
09:30	Welcome and icebreaker
09:45	Software Management Plans
10:30	Break
10:40	Software Management Plans
11:00	Q&A SMP + FAIR software
11:30	Break

Afternoon part:
11:40	Section 2: Ensuring Correctness of Software at Scale
12:30	Lunch Break
13:30	Intermezzo: section 3: Software Development as a Process
14:30	Break
15:00	Section 4: Collaborative Software Development for Reuse
15:30	Break
15:40	(Optional) Section 5: Managing and Improving Software Over Its Lifetime
16:15	Wrap-up + Q&A
16:30	END


## 🏢 Location logistics
* Coffee and toilets ?
* In case of an emergency?
* **Wifi**: ?

## 🎓 Certificate of attendance
If you attend the full workshop you can request a certificate of attendance by emailing to training@esciencecenter.nl .

## 🔧 Exercises
### Writing a Software Management Plan (1h10)
Together choose one of your research software projects that everyone in the group knows well. If you do not have such a project you can use [the sample project on inflammation](https://bitbucket.org/svenvanderburg1/python-intermediate-inflammation/src/main/): A detailed description of the project can be found [here](https://carpentries-incubator.github.io/python-intermediate-development/11-software-project/index.html). Try to answer the following questions (one person makes notes, rotate the note-taker role halfway): 

* Please provide a brief description of your software, stating its purpose and intended audience. 
* How will you manage versioning of your software? Which versioning scheme are you using? Why?
* How will you make your software publicly available? If you do not plan to make it publicly available, you should provide a justification. 
* How will your software be documented for users? Please provide a link to the documentation if available. 
* How will the installation requirements of your software be documented? Please provide a link to the installation documentation if available.
* How will your software be documented for future developers? 
* How will you document your software’s contribution guidelines and governance structure? 
* What license will your software have? Why did you choose that license?
* How will users of your software be able to cite your software? Please provide a link to your software citation file (CFF) if available. 
* How will your software be tested? Please provide a link to the automated testing results. 
* How will you check that your software respects the licenses of libraries and dependencies it uses? 
* How will your software be packaged and distributed? Please provide a link to available packaging information (e.g. entry in a packaging registry, if available).
* How do you plan to procure long term maintenance of your software?

## 🧠 Collaborative Notes
**welk team/software?**
brief description: Pure data beschikbaar maken voor UvA-DATA.
Versiebeheer software: Git Bitbucket
afhankelijk v.h. aantal personen dat eraan gaat werken -> afspraken over maken
publicly available: n.v.t.
Documenteren software: Confluence
installation requirements of your software be documented: readme + Confluence

## Feedback
Schrijf 1 ding op dat goed ging, en 1 ding wat we beter kunnen doen (vanmiddag of de volgende keer dat we deze cursus geven)
### Wat ging goed?
*
*

### Wat kan beter?
*
*

## Recap exercise
Vul eerst de [post-workshop survey](https://www.surveymonkey.com/r/8ZVJ9DL) in :pray:

Denk aan wat je hebt geleerd de afgelopen 2 weken
1.  Welke vragen heb je nog?


2.  Zijn er bepaalde verbeteringen die je ziet in je projecten?
3.  Wat is interessant dat je hebt geleerd maar is overkill voor je huidige werk?
4.  We hebben resources om nog 1 ochtend of middag terug te komen, hoe lijkt je dat het meest nuttig om die tijd te besteden?

- Bekijken in welke projecten unit testing en CI interessant kan zijn. Het lijkt mij nuttig om verder te gaan met het programma. 
- Hoe om te gaan met development/accepatie/productie configuratie, (pipeline)testen, nog een vervolgmiddag is nuttig
- pipelines - volledige ci/cd implementatie inclusief ook sast / beveiliging  checks. Test frameworks per taal. Integratie tests. 
- Vooral geautomatiseerd testen zie ik als verbetering in onze projecten, en ook in design/software architectuur. Voor een vervolgmiddag lijkt mij het nuttig om verder te gaan met het programma.
- Ik sluit me aan bij. Use cases uit onze praktijk omzetten naar praktische opdrachten voor met name testen en opstellen van requirements.


## 📚 Resources
[post-workshop survey](https://www.surveymonkey.com/r/8ZVJ9DL) (Dit is de correcte link, de vorige link was incorrect)
[example SMP](https://docs.google.com/document/d/1sgqMzQycaZeoxfQ5bK4USS3Uu0lutL6uBwG59Iuwq28/edit)
[Software Management Plan Guide](https://zenodo.org/record/7248877/files/Practical%20guide%20to%20Software%20Management%20Plans.pdf?download=1)
[Slides](https://ole.mn/uva_2023/)
[pre-commit hooks](https://coderefinery.github.io/git-collaborative/hooks/)
[Git course 1](https://swcarpentry.github.io/git-novice/), [Git course 2](https://ole.mn/estp2022/slides/practical_git/index.html)
[python template](https://github.com/NLeSC/python-template)
[Research Software Engineering with Python](https://merely-useful.tech/py-rse/)