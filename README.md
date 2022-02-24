# Scraping for Candidates
 Scraping for 2022 Texas Primary House candidates' campaign sites and social pages

This repository scrapes [Ballotpedia.org/](https://www.ballotpedia.org/) for Congressional candidates' 2022 campaign sites and social pages using Selenium and Beautiful Soup. 


## Ballotpedia 

The notebook, [Scraping_for_Candidates_TX_2022_House_Primaries.ipynb](scraping/TX-primaries/Scraping_for_Candidates_TX_2022_House_Primaries.ipynb) scrapes Ballotpedia for urls for each 2022 Texas Primary Candidate's campaign website and social media pages (facebook, instagram, twitter, etc.) in a multi-step process:
 1. Scrapes the Ballotpedia 2022 Congressional Election main page for urls for pages of each state where a Congressional election occurs
 2. Scrapes the Ballotpedia pages for each state, gathering the urls for each candidate running for Congress
 3. Scrapes each candidate's page, gathering the urls for each candidate's campaign website and social media links (facebook, instagram, twitter, etc.)

## Taking Screenshots of Candidates' Campaign Websites + Social Profiles
The notebook, [Scraping_for_Candidates_TX_2022_House_Primaries_websites_socials.ipynb](scraping/TX-primaries/Scraping_for_Candidates_TX_2022_House_Primaries_websites_socials.ipynb) takes a screenshot of each candidate's URL links for their website and social profiles (gathered from the prior notbook). As there are barriers on a number of the social sites, such as Instagram and Facebook, much of the time the screenshot didn't capture the actual profile, just the social platform landing page.  

## Candidates' Facebook (In-Progress)

## Candidates' Instagram (In-Progress) 
 
### Licensing
All code in this repository is available under the [MIT License](https://opensource.org/licenses/MIT). Files in the output/ directory are available under the [Creative Commons Attribution 4.0 International (CC BY 4.0) license](https://creativecommons.org/licenses/by/4.0/).

