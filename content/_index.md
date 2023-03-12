---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    id: features
    content:
      title: Skills
      items:
        - name: Java
          description: 
          icon: java
          icon_pack: fab
        - name: Data Science
          description: 
          icon: atom
          icon_pack: fas
        - name: Scrum
          description: 
          icon: agil
          icon_pack: custom
  - block: experience
    id: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Verband der Vereine Creditreform e.V.
          company: "Rollen: Java Backend Developer / Data Scientist"
          company_url: ''
          company_logo: user
          location: Neuss
          date_start: '2019-09-01'
          date_end: ''
          description: |2-
             <b>Backend Entwicklung für eine Plattform im Inkassoumfeld</b>
             <ul><li>Tägliche Arbeit nach agilen Methoden, Schnittstellen nach Kundenabsprache entwickeln.</li></ul>
             <br>
             Tech: <i>REST Services, Data Science, TDD, agil, Chapter Lead, Pair-Programming, IntelliJ IDEA, Java 17, SpringBoot 2, Docker, OpenAPI, JUnit5, Maven, Git, Jenkins, JIRA, Confluence</i>
             <br>
             <b>Vorhersagemodelle für Kundenverhalten erstellen</b>
             <ul><li>Arbeit nach CRISP Standard und mithilfe von Machine-Learning Methoden einschl. Datenanalyse, -modellierung und -visualisierung</li></ul>
             <br>
             <b>Arbeit als Chapter Lead für ein Team von Software-Entwickler</b>
             <ul>
                 <li>Weiterentwicklung von Entwicklern betreuen</li>
                 <li>Erstellen von Qualitätsstandards und Best Practices</li>
                 <li>Teamziele erarbeiten und umsetzten</li>
            </ul>

             <br>Tech: <i> Python, Scikit-learn, Tensorflow, PyCharm, CRISP, NLP, Statistik, XGBoost, OLS</i> 
        - title: Accenture
          company: Software Developer
          company_url: ''
          company_logo: user
          location: Düsseldorf
          date_start: '2017-08-01'
          date_end: '2019-08-31'
          description: |2-
             <b>Einführung eines Abrechnungssystem für EVU (Energieversorgungsunternehmen)</b>
             <ul><li>Tägliche Arbeit nach agilen Methoden, Schnittstellen nach Kundenabsprache entwickeln.</li></ul>
             <br>
             <b>Schulungen und Einarbeitungen für neue Mitarbeiter bereitstellen und durchführen</b>

            <br>Tech: <i> REST Services, PHP, PHP Storm, Bamboo, Jenkins, Sonar, JIRA, Confluence
    design:
      columns: '2'
  - block: experience
    id: academic
    content:
      title: Academic
      date_format: Jan 2006
      items:
        - title: Hochschule für Oekonomie und Management
          company: M.Sc. Big Data & Business Analytics
          company_url: ''
          company_logo: book
          location: Düsseldorf
          date_start: '2020-09-01'
          date_end: '2023-09-01'
          description:
        - title: Hochschule Bochum
          company: B. Eng. Geoinformatik
          company_url: ''
          company_logo: book
          location: Bochum
          date_start: '2012-08-01'
          date_end: '2017-07-31'
          description:
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
    design:
      columns: '2'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      email: mariusklug [at] live.de
      address:
        city: Köln
        postcode: 50167
    design:
      columns: '2'
---

