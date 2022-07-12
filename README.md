# Global CLSB List
Using the Meta's URL Shares Dataset, a collection of URLs shared on the platform between January 2017 and December 2021 with respective aggregated engagement metrics, user feedback and 3rd-party fact-checkers rating, we obtained a global list of 25,870 news stories (original URLs) rated as problematic (“false”, "missing context", "mixture or false headline" or “missing context”) by Facebook’s third-party fact-checkers (see “Third Party Fact-Checker Ratings and Precedence Rules Explained” section of the URLs Data Set documentation).

Please note that the distribution of “ per country is uneven. US URLs are in fact largely over-represented (49.4%). The other countries with more than 1,000 URLs are France (7.2%), Brazil (4.5%), the Philippines (4.5%) and Germany (3.8%). Other 23 countries pass the mark of 100 URLs rated as problematic. The total number of countries with at least one URL rated as such is 116.

We then used CooRnet to collect all the 7-days-after-publication Facebook public shares of these URLs returned by CrowdTangle API (link endpoint). CrowdTangle returned 300,836 shares for 14,187 news stories in our original URLs dataset.

Using a coordination interval of 10 seconds, we identified 818 coordinated accounts (115 pages and 703 groups organized in 95 networks) that performed “coordinated link sharing behavior” by rapidly sharing at least four different news stories rated as problematic by Facebook third-party fact-checkers.

Given the global nature of the starting dataset, it’s not surprising to observe that the returned networks are primarily geographically clustered. More specifically, we identified CLSB networks in 45 distinct countries.

Due to the large amount of not-anymore-available original URLs and to avoid directly linking known problematic news stories, we display links to the Way Back Machine archived version of the article (when available) in the list of top shared false news.

The map displays networks composed of three or more coordinated accounts (49). The size of the nodes corresponds to the weighted degree SNA metric. Each component is separated, thus the relative position of the component in the chart is random and thus meaningless.

# Authors

Fabio Giglietto (University of Urbino Carlo Bo), Roberto Mincigrucci (University of Perugia), Sawood Anwar (University of Urbino Carlo Bo)

# Aknowledgment

Nicola Righetti (University of Vienna) for setting up this space.
