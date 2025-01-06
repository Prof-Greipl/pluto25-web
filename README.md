# Pluto25-Web

Pluto25-Web ist ein Projekt für Studierende der HAW-Landshut im Wintersemester 24/25.
Inhalte
- Teil A: Einführung in HTML, CSS, Javascript
- Teil B: Anwendung für Pluto25Web

## Inhalte der einzelnen Vorlesungen

## Teil A (Einführung in HTML, CSS, Javascript)

### 14.10.2024
Intro.

### 15.10.2024
- Aufbau von index.html,
- Einfache Elements, 
- Attribute: style, href, src

### 22.10.2024
- Zusätzliche Elements: input
- css
  - What is CSS? 
  - CSS Ruleset

- css selectors
  - ID selector
  - Class selector
  - Element  selector

### 29.10.2024
- Bootstrap als UI Framework
  - Durchsicht der Webseite
  - exemplarische Einbindung in index.html

- JS (Teil A)
  - script-Element
  - Variablen, if-else, Schleifen, Funktionen, console.log

### 05.11.2024

- JS (Teil B)
  - const
  - addEventListener("click" , ), auch mit "mouseenter", "mouseout"
  - style.display
  - document.createElement()
  - document.body.appendChild( )

## Teil B (Pluto25Web)

### (auch am ) 05.11.2024
  - Start von Pluto25-Web

### 12.11.2024
  - Areas und Navigation
  - Modal
  - SignIn UI (teilweise)
  - Main UI (teilweise)
  - Übung: ManageAccount UI, Create Account UI
    
### 19.11.2024
  - Klärung: Listener direkt an Element-id anhängen
  - Update the HomeArea - add Listgroup 
  - Add Element for `Template`
  - Erzeugen von `mPostList`  mit Testeinträgen 
  - Anzeigen der Testeinträge in der Listgroup

### 26.11.2024 (30 mins, Rest Fragestunde)
  - Promises
    
### 03.12.2024
  - Web-Apps allgemein
    -  Modularisieriung on JS Programmen
    -  http-Server mit Python: `python.exe -m http.server`
  - Pluto25Web
    - Added Firebase to WebApp (see https://firebase.google.com/docs/web/setup?continue=https%3A%2F%2Ffirebase.google.com%2Flearn%2Fpathways%2Ffirebase-web%23article-https%3A%2F%2Ffirebase.google.com%2Fdocs%2Fweb%2Fsetup) 
    - Link zu Web-API https://firebase.google.com/docs/reference/js 
    
### 10.12.2024
Link: https://firebase.google.com/docs/reference/js/auth
  - Sign in/ sign out mit Firebase
    - signInWithEmailAndPassword(mAuth, email, password) [in SignIn]
    - signOut( mAuth ) [in ManageAccount]
  - onAuthStateChanged()
    - Modifikation des Navbars nach Anmeldestatus
  - Offen: Create Account 

### 17.12.2024
  - Cleanup in der Navigation (Update in OnAuth..)
  - Verbesserung von ManageAccount
  - CreateAccount implementiert
  - "Send" (Posting) implementiert
  - Homework: SendVerificationMail
  - Offen: Delete Account

### 07.12.2024 (Programm)
  - Display Posts  

## Identfiers in HTML Part

### Navigation Bar Links

- navHome
- navSignIn
- navManageAccount
- navCreateAccount

### Areas 
- areaMain
  - ah_ul
  - ah_message
  - ah_send
- areaSignIn
- areaManageAccount
- areaCreateAccount





