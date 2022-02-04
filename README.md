# Scraping for Candidates
 Scraping for Congressional candidates' campaign sites and social pages

This repository scrapes [Ballotpedia.org/](https://www.ballotpedia.org/) for Congressional candidates' 2022 campaign sites and social pages using Selenium and Beautiful Soup. 


## Ballotpedia 

The notebook, [Scraping_for_candidates.ipynb](Scraping_for_candidates.ipynb) scrapes Ballotpedia for each campaign's website and social media profiles (facebook, instagram, twitter, etc.) in  a multi-step process:
Markup : 1. Scrapes the Ballotpedia 2022 Congressional Election main page for urls for pages of each state where a Congressional election occurs
         2. Scrapes the Ballotpedia pages for each state, gathering the urls for each candidate running for Congress
         3. Scrapes each candidate's page on Ballotpedia, gathering the urls for each campaigns's wesite and social media profiles (facebook, instagram, twitter, etc.)
 
### Licensing
All code in this repository is available under the [MIT License](https://opensource.org/licenses/MIT). Files in the output/ directory are available under the [Creative Commons Attribution 4.0 International (CC BY 4.0) license](https://creativecommons.org/licenses/by/4.0/).

