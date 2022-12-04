# User-Reviews-Vaccination-Centers-Berlin
Analysis of Online Reviews from users of the Berlin vaccination centers
##### For questions contact: Stella Danek - stella.danek@charite.de

## Objectives of the Project
Using Online Reviews from Vaccination Centers to understand how users feel about vaccination centers, what dimensions and factors drives satisfaction or dissatisfaction and to derive factors for optimal vaccination center design.
Short overview of research questions:
* What are recurring themes, themes that affect users with relation to vaccination centers and the vaccination process generally?
* How do “concerns” of users change over time?
* What themes, factors and vaccination center characteristics are associated with satisfaction, i.e. a high review rating?
* How does satisfaction change over time?
* Which conclusions can be drawn for the optimal design of vaccination centers, but also for the vaccination experience generally?

## Vaccination Centers in Berlin
### Definitions
* A vaccination center (“Impfzentrum”) is “a location, normally used for nonhealthcare activities, set up for high-volume and high-speed vaccinations during infectious disease emergencies” , in Germany, vaccination centers are set up and operated by the federal states or on behalf of the federal states 
* In Berlin, the vaccination centers are coordinated and organized by the DRK SWB (Deutsches Rotes Kreuz Sozialwerk Berlin gGmbH, engl. German Red Cross social work Berlin non-profit company with limited liability), a non-profit company set up by the German Red Cross Berlin, the KVB (Kassenärztliche Vereinigung Berlin, engl. Association of Statutory Health Insurance Physicians) and SenGPG (Senatsverwaltung für Gesundheit, Pflege und Gleichstellung, engl. Senate Department for Health, Nursing and Equality ), since December 2021 SenWGPG (Senatsverwaltung für Wissenschaft, Gesundheit, Pflege und Gleichstellung, engl. Senate Department for Science, Health, Nursing and Equality) 
* In addition, a number of vaccination points (“Impfstation” or “Impfstelle”) were and are operated in Berlin; these are smaller compared to the vaccination centers and organized not by the Senate, but by the district offices (“Bezirksämter”), e.g. Impfstation Freizeitforum Marzahn or Impfstation Einkaufszentrum ALEXA
* The analysis focuses exclusively on the vaccination centers in Berlin

## Description
* A total of 6 vaccination centers were operated in Berlin
* The vaccination centers were spread across the city to ensure reachability from all districts
* Organization lied with the SWB (coordination and administration), KVB (physician staffing) and SenGPG (financial and political responsibility)
* Operations lied with different air organizations based in Berlin, i.e., day to day running of the centers themselves, staffing, logistics, administration and recording of vaccination
* The first vaccination center opened in December 2020 , by December 2021 2 out of the 6 vaccination centers were still running
* The vaccination centers were open every day (7 days a week), usually between 09:00 and 17:00 o’clock; a few exceptional closings occurred:
o	closing of Tegel and Tempelhof 15/03/2021-18/03/2021 due to a temporary discontinuation of Astrazeneca vaccines while side effects were being reviewed 
  * 14-day closing of Tempelhof 21/04/2021-04/05/2021 in order to install new cooling devices for BionTechPfizer’s Comirnaty 
  * closing of Arena and Messe from 14:00 on 06/04/2021 due to supply shortages of BioNTech/Pfizer’s Comirnaty vaccine 
  * irregular opening times over Christmas and New Year 2021 (closed on 25/12/2021 and 01/01/2022, closed after 14:00 o’clock on 24/12/2021 and 31/12/2021)
* Daily capacity: Depending on the number of vaccines available and the number of appointments booked, a single vaccination center could perform up to around 4.000 vaccinations per day
* Appointments:
  * Booking: Until July 2021 vaccination appointments had to be booked
  * Walk-Ins: Since July 23 for Tegel, Messe and Erika-Heß and July 30 for Arena and Velodrom Walk-In vaccinations are possible
  * Vaccines available: Different vaccines were offered at the vaccination from December 2020 to December 2021, including BioNTech/Pfizer’s Comirnaty, Moderna’s Spikevax and Astrazeneca’s Vaxzevira
* In December 2021 the Messe Berlin vaccination center moved next door to the ICC (International Congress Center) due to additional event space needed at the trade fair building Messe , the google maps review website has stayed the same


Opening, closing
|Vaccination Center|Opening|Closing|Start Walk-Ins|
|---|---|---|---|
|Arena| 	27.12.20|	31.08.21|	30.07.21|
|Erika-Heß-Eisstadion|	14.01.21|	31.08.21|	23.07.21|
|Flughafen Tegel|	10.02.21|	31.05.22	|23.07.21|
|Flughafen Tempelhof|	08.03.21	|20.07.21|	/|
|Messe|	18.01.21|	31.05.22	|23.07.21|
|Velodrom|	17.02.21|	19.08.21	|30.07.21|

## Google Maps Online Reviews

### Who can leave a review and how?
* Any registered google user (having a google account) can leave a review
* Reviews consist at a minimum of a rating (see below), but can also contain text and pictures
* Registered google users can “like” reviews, i.e. mark them as helpful or “good”
* Registered owners of a business or a google maps location can comment on reviews

### What is the review scale?
* The review scale ranges from 1 to 5 with 1 being the lowest rating and 5 being the highest rating

## Scraping / Data Source
* Data scrape was performed using Outscraper (https://outscraper.com) on 27 dec 2021
* Online Reviews for 6 vaccination centers in Berlin scraped from google maps review websites in English from 27 dec 2020 00:00:00 to 27 dec 2021 00:00:00
* 5 vaccination centers had a review website dedicated specifically to the vaccination center, 1 vaccination center (Arena Berlin) did not have a review website dedicated specifically to the vaccination center; where a vaccination center specific review website existed, the reviews were scraped from the vaccination center review website; for Arena Berlin the reviews were scraped from the event space review website; 
