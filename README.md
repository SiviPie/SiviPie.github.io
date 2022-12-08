# SiviPie.github.io

Această pagină web reprezintă tema numărul 2 la materia _Tehnologii Web_.

Am ales tema Online Magazine, astfel că am realizat un website folosind HTML şi CSS.

## Structură

Fişierele sunt structurate în următoarea ierarhie:

index.html
/css -> style.css
/img -> toate imaginile si svg-urile conţinute
/pages -> home.html
       -> about.html
       -> catalog.html
       -> contact.html

## Landing Page
       
Prima pagina (index.html) are rolul de **Landing Page**. Pe aceasta se află un hiperlink centrat pe pagină şi acompaniat de o animaţie, ce ne va redirecţiona pe pagina /page/home.html. 

## Navbar 
Fiecare pagină din folderul /pages conţine un Navbar vertical, având următoarea structura:
Acasă
Despre
Catalog
Contact
Înapoi

Elementele enumerate anterior sunt hyperlink-uri ce ne vor redirecţiona spre paginile aferente denumirii lor. În cazul hyperlink-ului "Înapoi", acesta ne va redirecţiona spre Landing Page.

## Home
Pagina Home reprezintă primul contact al utilizatorului cu conţinutul website-ului. Acesta este întâmpinat de un mesaj aflat într-un chenar centrat în secţiunea dreaptă a paginii. 

## About
Pagina About cuprinde o mică descriere a website-ului, ce îi va oferi utilizatorului o imagine de ansamblu asupra acestuia. 

## Catalog
Pagina Catalog conţine o selecţie de jocuri afişate sub formă de carduri. Fiecare card este format dintr-o imagine şi un text ce reprezintă titlul jocului. Atunci când utilizatorul trece cu cursorul peste un card, se va declanşa o animaţie (realizată cu ajutorul selectorilor ::before şi ::after) 

## Contact
Pagina de Contact conţine un formular prin care utilizatorul va putea contacta creatorul paginii web, acesta având opţiunea de a introduce:
Nume, Adresă de email, Subiect, Gen, Mesaj.
Formularul este acompaniat de 2 butoare: **Submit** şi **Reset**. Butonul de Reset va şterge toate modificările aduse formularului, iar cel de Submit va trimite mesajul.

## Footer
Pe lângă Navbar, fiecare pagină din directorul /pages conţine şi un footer. Acesta conţine legături cu pagina de profil personal a creatorului pe diferite reţele sociale (Facebook, Twitter) şi o legătură tip mail. Acestea au fost afişate sub formă de iconiţe (imagini) modificate prin intermediul CSS.
