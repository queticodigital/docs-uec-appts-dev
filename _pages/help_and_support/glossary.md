---
title: Glossary
keywords: abbreviations, definitions, glossaries, terms
tags: [getting_started]
sidebar: overview_sidebar
permalink: glossary.html
summary: "Glossary of terms used in the UEC Appointment booking standards"
toc: false
---
{% include note-notpublished.html %}

### Consumer
The IT system that is searching for and placing bookings on behalf of the patient 

### Provider
The IT system that holds the appointments being searched for and booked into 

### SDS
This stands for "Spine Directory Service"

### SSP
This stands for "Spine Secure Proxy"

### PDS
This stands for "Patient Demographic Service"

### SMSP
This stands for "Spine Mini Service Provider"

### FHIR
This stands for "Fast Health Information Resources"

### DoS
This stands for "Directory of Services"

### JWT
This stands for "Java Web Tokens"

### OAuth
This is an Open Authentication Standard

### SA

### GP Connect

### RESTful

### NHS Identity (**Strat**egic **Auth**entication)
The NHS Identity service provides a digital identity that can be consumed many times from a single logon. It can also be linked with every day devices to provide extra contextual information about that user (e.g. location, nearby services) and it can profile the characteristics of the owner(usual times of sign-on, services normally used, location, devices linked to the user).

For this booking standard, NHS Identity could validate credentials passed by the consuming system, and subject to this check, issue a short lived (1 hour) access token which the consuming system must include in an http Authorization header in all requests to the provider system.
