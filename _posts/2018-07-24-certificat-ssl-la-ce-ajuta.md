---
layout: post
title: "Ce este un certificat SSL și la ce ne ajută? Vrem un internet mai sigur!"
category: tutoriale
descriere: Ce este un certificat SSL? Cum funcționează și la ce ajută? Având în vedere că în ziua de astăzi frauda online este la mare căutare, este foarte important să știm cum ne putem securiza un site.
image: certificat-SSL.jpg
author: "Alexpintea"
comment-id: 8
canonical_url: '/certificat-ssl-la-ce-ajuta.html'

---

_Ce este un certificat SSL? Cum funcționează și la ce ajută? Având în vedere că în ziua de astăzi frauda online este la mare căutare, este foarte important să știm cum ne putem securiza site-ul, mai ales dacă prin intermediul acestuia se fac plăți și utilizatorii introduc date sensibile precum detalii de pe cardul de credit._

## CE SE ÎNTÂMPLĂ CU INFORMAȚIILE?
---

De fiecare dată când cineva intră pe site-ul nostru, pentru a fi afișate paginile, se fac schimburi de date între computerul utilizatorului, server și retur. Ba în funcție de serviciile pe care le avem pe site, informațiile pot trece prin mult mai multe noduri.

În mod normal, datele se transmit în format text și pot fi citite de oricine.  Același lucru este valabil și atunci când un utilizator cumpără un produs sau serviciu prin intermediul cardului sau introduce parola de la contul PayPal, etc.

## CONEXIUNEA SECURIZATĂ
---

Aici intervine conexiunea securizată. Datele sunt criptate de către certificatele SSL/TLS prin utilizarea unui sistem complex de schimb de parole și coduri între calculatoarele personale și servere.

Pe scurt, SSL-ul este tehnologia standard care face internetul mai sigur și păzește datele sensibile care se transmit între două sisteme. Așadar, eventualii tâlhari ai internetului, sunt opriți din a modifica sau citi informațiile transferate.

## SSL VERSUS TLS
---

La modul general, SSL și TLS sunt același lucru. TLS 1.0 a fost creat în 1990 și a fost o variantă mai avansată a SSL 3.0. SSL este o denumire mai populară și de obicei oamenii o folosesc și când se referă la variantele mai noi de TLS.

## COMPATIBILITATEA CU BROWSER-UL
---

Certificatul pe care îl instalezi pe site-ul tău trebuie să fie semnat digital cu un alt certificat care este în portofoliul de siguranță al browser-ului utilizatorului care îți vizitează site-ul. Așadar, browser-ul are încredere în certificatul de pe site-ul tău și nu afișează niciun avertisment utilizatorului.

În caz contrar, dacă nu există o semnătură digitală sau lipsesc link-uri din lanțul certificatului, browser-ul va emite un avertisment utilizatorului precum că există posibilitatea ca site-ul să nu fie sigur. Nu ne dorim asta, nu?

Așadar, atunci când vrei să achiziționezi un certificat SSL trebuie să acorzi o atenție deosebită la nivelul de compatibilitate cu majoritatea browser-elor. Un procent bun ar fi peste 90%. Însă dacă certificatul este foarte avansat, și trebuie să plătești o sumă foarte mare de bani lunar, ar trebui să fie compatibil cu peste 99% din totalul browser-elor.

## SIGILIUL DE SIGURANȚĂ
---

Un sigiliu de siguranță este un logo pe care poți să îl afișezi pe site-ul tău. În acest fel, notifici utilizatorii că activitatea lor pe site este protejată de un anumit provider de certificate SSL. Poate fi postat pe toate paginile, dar cel mai important este să îl afișezi pe paginile unde utilizatorii își introduc date personale sau sensibile.

## HTTP VERSUS HTTPS
---

<img src="{{ site.url }}/assets/images/certificat/certificat-ssl1.jpg" alt="{{ page.title }}"/>

HTTP vine de la Hypertext Transfer Protocol și este protocolul pe care internetul îl folosește pentru formatarea și transferul datelor. Acest protocol le spune browser-elor și serverelor ce trebuie să facă atunci când primesc diferite comenzi.

Litera ”S” din HTTPS vine de la secure (sigur)  și ne spune că protocolul de comunicare este criptat prin utilizarea fie a unu certificat SSL, fie a unui SSL.

Așadar, pentru a putea avea HTTPS pe site-ul tău este necesar un certificat SSL.

## Let's Encrypt, un certificat SSL gratuit
---

<img src="{{ site.url }}/assets/images/certificat/certificat-SSL3.jpg" alt="{{ page.title }}"/>

<a href="https://letsencrypt.org/">Let's Encrypt</a>, este un serviciu de securitate sprijinit de câteva companii IT gigant precum Google, Cisco, Facebook și Hewlett Packard Enterprise. Acest serviciu oferă certificate SSL gratuite.

Nu trebuie să ne îngrijorăm foarte mult pentru instalarea certificatului deoarece majoritate companiilor de găzduire și servere oferă un certificat la pachet. Instalarea se face doar prin câteva click-uri și ești gata să oferi conexiuni sigure pe site-ul tău.

<h3>Beneficiile certificatului Let's Encrypt</h3>

<ul>
 	<li>Securitate îmbunătățită, conexiunea dintre utilizator și server fiind criptată.</li>
 	<li>Fără avertismente de genul ”Nesigur” din partea browser-elor. Acestea pot alunga eventualii cititori și clienți de pe site-ul tău.</li>
 	<li>Clasare mai bună din punct de vedere SEO. Google a recunoscut oficial că Certificatele SSL apar printre criteriile de clasare.</li>
 	<li>Compatibilitate HTTP/2. Cu un site protejat SSL poți beneficia de avantajele protocolului HTTP/2. Asta înseamnă un site mai rapid și mai eficient.</li>
</ul>

## Dezavantaje
---

Cu atâtea beneficii de ce ar fi cineva care să nu vrea să folosească un certificat SSL? Există dezavantaje?

Desigur, cel mai mare dezavantaj este costul. Un ceritficat SSL complex vine cu verificări de identitate și alte validări, fapt ce implică o serie de costuri. Bineînțeles, nu este cazul dacă folosești un certificat Let's Encrypt gratuit. Însă, clar nu vei beneficia de aceleași funcționalități precum cele oferite de un certificat pentru care plătești peste 150$ pe lună.

Un alt dezavantaj implicit este performanța site-ului. Deoarece informațiile pe care le trimiți trebuie să fie criptate de server, crește numărul de procese care trebuie executate. Un număr mai mare de procese crește timpul de încărcare a site-ului. Și în același timp sunt consumate și mai multe resurse.

Cu toate astea, diferența în performanță este vizibilă doar în cazul site-urilor cu foarte mulți vizitatori. Însă, există dispozitive speciale care rezolvă această problemă.

## Concluzie
---

Per total, dezavantajele folosirii unui certificat SSL sunt mult mai puține decât avantajele. Utilizarea corectă a unui certificat SSL te va ajuta la protejarea clienților și utilizatorilor, te va proteja pe tine și te va ajuta să câștigi încrederea clienților și să vinzi mai mult.

Dacă ești la început de drum, alege de prima dată găzduire care oferă gratuit certificate SSL Let's Encrypt, pe care le vei putea instala ulterior cu un singur click. Site-ul tău va folosi protocolul HTTPS. Vizual, <span style="color: #339966;">https://</span> va fi scris cu verde, și în stânga va avea un lacăt verde și cuvântul <span style="color: #339966;">Secure</span> sau <span style="color: #339966;">Sigur.</span>

<a href="https://it-tuts.ro/cum-sa-faci-un-site/">Vezi și ghidul nostru pentru crearea unui site!</a>