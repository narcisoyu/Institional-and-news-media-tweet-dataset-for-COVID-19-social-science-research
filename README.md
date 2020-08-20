# Institutional-and-news-media-tweet-dataset-for-COVID-19-social-science-research
Open access data repository for institutional/news media tweet dataset in the time of COVID-19 pandemic

Detail information pre-print avaliable at: https://arxiv.org/abs/2004.01791

---------------------
#UPDATE EVERY THURSDAY
---------------------

News media and government/international organization tweets across different countries (eg. US, UK, China, Spain, France, Germany etc)
Feel free to share this repo.

Data collected using twitter REST API.

First data collection at March 12, 2020 (updated on my PC every week).
This means the first time I collect the most recent 3200 tweets (official limits) of all the target accounts, then update weekly.

##V1.20
update data from Aug 13 to Aug 19
* `@BrazilGovNews`, `@Itamaraty_EN`. `@socialstyrelsen` and `@French_Gov` tweet 0 message

##Extra update 1
* `example_doc_classifier.R` is the example (election_us) script I used to subset all the collected data

##V1.19
update data from Aug 6 to Aug 12
* `@BrazilGovNews`, `@socialstyrelsen` and `@French_Gov` tweet 0 message

##V1.18
update data from Jul 30 to Aug 5
* `@BrazilGovNews` and `@French_Gov` tweet 0 message

##V1.17
update data from Jul 23 to Jul 29
* `@BrazilGovNews`, `@French_Gov`, `@SwedishPM` tweet 0 message

##V1.16:
update data from Jul 16 to Jul 22
* `@BrazilGovNews`, `@Itamaraty_EN`, `@French_Gov`, `@socialstyrelsen` tweet 0 message

##V1.15:
update data from Jul 9 to Jul 15
* `@BrazilGovNews` and `@French_Gov` tweeted 0 message

##V1,14:
update data from Jul 2 to Jul 8
* `@BrazilGovNews`, `@Itamaraty_EN`, `@French_Gov`, `@socialstyrelsen`, `@SwedishPM` tweeted 0 message

##V1.13:
update data from Jun 25 to Jul 1
* New added: Two Italian news media: `@LaStampa` and `@Corriere`
* `@BrazilGovNews` and `@French_Gov` tweeted 0 message

##V1.12:
update data from Jun 18 to Jun 24
* New added: `SE_tweet_id` Swedish gov, PM and news media tweets
* Attention: During 0618-0624 `@BrazilGovNews` tweeted 0 message
* Attention: During 0618-0624 `@French_Gov` tweeted 0 message

##V1.11:
update data from Jun 11 to Jun 17
* New added: `TR_tweet_id` Turkish gov, president and news media tweets
* Attention: During 0611-0617 `@BrazilGovNews` tweeted 0 message
* Attention: During 0611-0617 `@Itamaraty_EN` tweeted 0 message
* Attention: During 0611-0617 `@French_Gov` tweeted 0 message

##V1.10:
update data from Jun 4 to Jun 10
* Attention: During 0604-0610 `@BrazilGovNews` tweeted 0 message
* Attention: During 0604-0610 `@Itamaraty_EN` tweeted 0 message
* Attention: During 0604-0610 `@French_Gov` tweeted 0 message

##V1.09:
update data from May 28 to Jun 3
* Attention: During 0528-0603 `@BrazilGovNews` tweeted 0 message

##V1.08:
update data from May 21 to May 27
* Attention: During 0521-0527 `@BrazilGovNews` tweeted 0 message

##V1.07:
update data from May 14 to May 20
* Attention: During 0514-0520 `@BrazilGovNews` tweeted 0 message

##V1.06:
update data from May 7 to May 13.
* Attention: During 0507-0513 `@BrazilGovNews` tweeted 0 message
* Attention: During 0507-0513 `@French_Gov` tweeted 0 message

##V1.05:
update data from April 30 to May 6.
* Attention: During 0430-0506 `@BrazilGovNews` tweet 0 message

##V1.04:
update data from April 23 to April 29.
* Attention: During 0423-0429 `@BrazilGovNews` tweeted 0 message
* Attention: During 0423-0429 `@French_Gov` tweeted 0 message

##V1.03:
update data from April 16 to April 22.
* New added: `BR_tweets` Brazilian government, president, news media
* Attention: During 0416-0422 `@French_Gov` tweeted 0 message
* Attention: During 0416-0422 `@BorisJohnson` tweeted 0 message

##V1.02: 
update data from April 9 to April 15.
* New added: `EU_leadership` (`@BorisJohnson`, `@EmmanuelMacron`, `@GiuseppeconteIT`, `@sanchezcastejon`)<br>
* New added: `election_us` (`@BernieSanders`, `@JoeBiden`, `@realDonaldTrump`, `@POTUS`)<br>
* New added: `national_gov_foreign_office` (you can see this as a huge update to the previous gov file, which include 14 European/US/Chinese government/foreign office accounts)<br>
* Minor changes: `@globaltimesnews` moved from `ADDITIONAL_news_tweet_id` to `CHINA_news_tweet_id`.<br>
* Minor changes: `@spiegelonline` stop tweeting at 20200108, it was removed from my collection query, tweet_id were saved on V1.0.

##V1.01: 
update data from April 2 to April 8.

##First online: April 2, 2020


----------
IMPORTANT:
----------
Data crawled by twitter account user name (same as txt file name), some of the accounts may lost maintaince for long time (for example @SanidadPublicaEs, stop tweeting at 2014, but activate this account again when COVID-19 became global crisis).

I did NOT remove the historical data before coronavirus outbreak. Any questions please contact with me (see email below).

--------------
How to Hydrate
--------------
Two recommendations:
by Hydrator
https://github.com/DocNow/hydrator

or twarc
https://github.com/DocNow/twarc

Please follow the instructions

----------
Contact me
----------
Jingyuan Yu  
jingyuan[dot]yu[at]e-campus[dot]uab[dot]cat

-------
License
-------
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
