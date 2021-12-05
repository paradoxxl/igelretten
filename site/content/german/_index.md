---
############################### Banner ##############################
banner:
  enable: true
  bg_image: "images/bg.png"
  bg_overlay: true
  title: "Igel <br/> Retten"
  content: "Hilf auch Du den stachligen Insektenvertilgern!"
  button:
    enable: false
    label: "Discover Our Project"
    link: "project"

############################# About #################################
about:
  enable: true
  title: "Igelstation"
  description: "Wir kämpfen jeden Tag ums Überleben von kranken, verletzten Igeln oder Igelbabys ohne Mutter. Wir sind die grösste Igelstation der Schweiz. "
  content: "
  <ul>
    <li>Standort: Oberentfelden</li>
    <li>Leitung: Danielle Lenzin</li>
    <li>Kontakt: 079 740 26 31</li>
  </ul>
  "
  image: "images/company/station.jpeg"
  button:
    enable: true
    label: "Über uns"
    link: "about"


######################### Helfer ###############################
volunteer:
  enable: true
  bg_image: "images/volunteer-bg.png"
  title: "Helfer werden!"
  content: " Wir suchen Helfer für die grösste Igelstation der Schweiz: füttern, shoppen geben, misten!
<br>
<ul>
<li>Keine Vorkenntnisse nötig</li>
<li>Wir arbeiten Hand in Hand, ehrenamtlich</li>
<li>Dein Einsatz ist flexibel planbar (vormittags auch Wochenende) </li>
<li>Regelmässige Einsätze sind erwünscht</li>
<li>Dein Lohn ist die Rettung vieler Igel</li>
</ul>
<br>
Hast Du im Haus oder im Gartenhaus Platz für einen Igel? 
Wir suchen immer wieder Winterquartiere für notleidende Igel!

Bitte meldet euch telefonisch oder per WhatsApp bei Danielle: 079 740 26 31
  "
  button:
    enable: true
    label: "Ich möchte helfen!"
    link: "project"



######################### Spenden ###############################
donate:
  enable: true
  bg_image: "images/spenden-bg.png"
  title: "Spenden"
  content: "<p>Du hast zu wenig Zeit um vorort zu helfen? Mit einer Spende kannst du uns auch unterstützen!</p>
  Die Rettung von Igeln braucht in erster Linie viele Helfer, die ehrenamtlich arbeiten. 
  Das ist aber nur ein Teil der Geschichte. Wir benötigen Medikamente und das richtige Futter, damit wir verletzten 
  und kranken Igeln helfen können. Mit einer Spende hilfst du uns, ein paar Sorgen bezüglich los zu werden.
  <br>
  <br>
  <br>
  "
  button:
    enable: true
    label: "Ich möchte spenden!"
    link: "project"

  sponsorship:
    enable: false
    label: "Ich möchte Pate werden!"
    link: "project"


######################### Das wichtigste zu Igeln ###############################
tldr:
  enable: true
  bg_image: "images/tldr-bg.jpg"
  title: "Die wichtigsten Informationen auf einen Blick"


  tldr_table:
  # pricing table loop
  - name : "Fütterung"
    content : "1/3 getrocknete Mehlwürmer<br>2/3 trockenes Katzenfutter (kein Nassfutter)"
    link : "#"
    services:
    - "In eine flache Schale geben"
    - "Frisches Wasser"
    - "Nur nachts füttern"
    - "Keine Milch"

  # pricing table loop
  - name : "Bitte keine Igel am Tag füttern!"
    content : "Bei der Fütterung am Tag wechselt der Igel seinen
Rhythmus und ist den Fliegen ausgeliefert, diese
legen Eier am Igel, die Maden schlüpfen innert
24 Stunden und fressen die Igel von innen aus."
    link : "#"
    services:

  - name : "Rette Leben!"
    content : ""
    link : "#"
    services:
    - "Keine Schneckenkörner streuen"
    - "Keine Netze, offene Teiche oder Pools"
    - "Vorsicht beim Wenden von Komposthaufen (keine Kompostgabeln verwenden!)"
    - "Suche das Gebüsch vor dem Mähen ab"
    - "Nur Rasenroboter mit Sensor einsetzen"

  - name : "Wann muss ein Igel in Behandlung?"
    content : ""
    link : "#"
    services:
    - "Verletzte Igel"
    - "Am Tag gesichtete Igel"
    - "Junge Igel ohne Mutter"
    - "Igel, die an der prallen Sonne liegen"
    - "Hustende Igel"
    - "Igel, die im Herbst/Winter weniger als 800g wiegen"
    - "Von Fliegen oder Parasiten befallene Igel"
  
  - name : "Hilfbedürftigen Igel gefunden?"
    content : "Packe den Igel in eine Schachtel mit Luftlöchern.
  Wasser und Futter geben und umgehend anrufen,
  nicht einige Tage warten! Igel immer mit Handschuhen
  anfassen. Nie einen Igel mit Nest stören, die Mutter
  verlässt ihre Jungen umgehend oder tötet sie."
    link : "#"
    services:

  button:
    enable: false
    label: "Ich möchte spenden!"
    link: "flyer"




############################# Service ############################
service:
  enable: false
  # service content comes from "service.md" file


############################ call to action ###########################
cta:
  enable: false
  bg_image: "images/call-to-action-bg.jpg"
  title: "We design delightful digital experiences."
  content: "Read more about what we do and our philosophy of design. Judge for yourself The work and results <br> we’ve achieved for other clients, and meet our highly experienced Team who just love to design."
  button:
    enable: true
    label: "Tell Us Your Story"
    link: "contact"

############################# Funfacts ###############################
funfacts:
  enable: true
  title: "Fakten über uns"
  description: "'Lerne etwas über unsere Igelstation und unsere Schützline'"
  funfact_item:
  # funfacts item loop
  - icon: "fas fa-glass-cheers" #https://fontawesome.com/v5.15/icons
    name: "Fressen Insekten/Tag"
    count: "99"

  # funfacts item loop
  - icon: "fas fa-glasses" #https://fontawesome.com/v5.15/icons
    name: "Stacheln"
    count: "8000"

  # funfacts item loop
  - icon: "fas fa-keyboard" #https://fontawesome.com/v5.15/icons
    name: "Kapazität"
    count: "125"

  # funfacts item loop
  - icon: "fas fa-clock" #https://fontawesome.com/v5.15/icons
    name: "Durchschnittliche Auslastung"
    count: "96"

  testimonial_slider:
  # testimonial item loop
  - name: "Raymond Roy"
    image: "images/clients/avater-1.jpg"
    designation: "Igelstation-Helfer"
    content: "Ich helfe Igeln weil sie durch uns ihren Lebensraum verlieren"

  # testimonial item loop
  - name: "Randi Renin"
    image: "images/clients/avater-1.jpg"
    designation: "Spender"
    content: "Mein Zeitbudget ist sehr beschränkt. Ich leiste meinen Beitrag über regelmässige Spenden, damit verletzte Igel medizinisch behandelt werden können und genug zu fressen bekommen"

  # testimonial item loop
  - name: "Rose Rio"
    image: "images/clients/avater-3.jpg"
    designation: "Lebensraum-Verbesserin"
    content: "Ich benutze keine Pestizide im Garten und schaffe aktiv Lebensraum mit einer naturnahen Gestaltung. Ausserdem habe ich zwei bewohnte Igelhäuser!"


---
