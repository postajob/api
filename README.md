# Table of contents




# Overview 

## Introduction
Our API simplifies how developers and businesses publish jobs into their software. PostAJob's API is a tool for web developers to build HR solutions. If you don't have easy access to development resources, we can recommend excellent third-party partners. To learn more about postajob and how you can use our solution to transform your business, please contact our sales team.

## How it works
Postajob is a simple concept - you submit your jobs description and properties into our API, and we dispatch it to the best channels. The API returns a bunch of useful data about the reach, clic estimation and application estimation. All channels available are visible [here](https://directory.postajob.io/). 

![HOME POSTAJOB](https://github.com/postajob/api/blob/master/images/home.png)

# Making your first API call

We've written a quick step-by-step guide to walk you through how to create a PostAjob Developer account, make your first API call, and interpret the results.

## STEP 1: Register as a Developer 

 If you are an existing Postajob user, log in to your dashboard. If not, sign-up for postajob  - it's free to test.

## STEP 2: Get your APP ID and API Key

Once you’ve registered, and confirmed your email, you’ll be able to access your Dashboard. Here you’ll find your ‘(API) Key’. Make a note of these key, you will use them in the next step.

![APIKEY POSTAJOB](https://github.com/postajob/api/blob/master/images/apikey.png)

Oh, and we automatically created your first campaign, to save you some time. You can rename this anytime.

## STEP 3: Make your first API call
The most simple method to make your first API call is to use cURL.

```herte```

# API reference

## Campaign

| name | type | description |
| --- | --- | --- |
|name (required)|String|Name of your job|
|category|String|Category of the job. Is mandatory for publising the campaign|
|description|String|Full text description of your job. Can contain html tags. Must be at least 100 caracters for publishing.|
|company_name|String|Name of the recruiting company|
|company_website|String|Website of the recruiting company|
|company_country|String|Country of the recruiting company|
|company_logo|String|Logo of the recruiting company. Should be a valid url to a .png or .jpg image|
|contract|String|Under which contract is this job. Contract is mandatory for publishing|
|education|String|The education the applicant should have|
|experience|String|The experience the applicant should have|
|salary.min|Number|Minimum salary for the job|
|salary.max|Number|Maximum salary for the job|
|salary.unit|String|The unit fo the salary|
|salary.currency|String|The currency of the salary|
|budget|Number|Budget you want to set for your campaign. You need to add a budget on your campaign from our dashboard|
|age_range.min|Number|Age minimum for the job ( useful for google ads and facebook ads job posting ) |
|age_range.max|Number|Age maximum for the job ( useful for google ads and facebook ads job posting ) |
|cities|Array||
|locations|Array||
|skills|Array|Skills for the needed. Useful to target niche dashboard of for a google ads or facebook ads job |
|interests|Array|Interest of the candidate. Useful to target niche dashboard of for a google ads or facebook ads job |
|language|Array|Language spoke by the applicant. Useful to check in multiple country which this languages|
|banner|String|Background image of your ads. It will be the image for your google ads, linkdin ads, or instagram ads or google for jobs etc ...|
|title|String|Title of your ads. It will be the image for your google ads, linkdin ads, or instagram ads or google for jobs etc ...|
|text_1|String|Main text of your ads. It will be the image for your google ads, linkdin ads, or instagram ads or google for jobs etc ...|
|text_2|String|Secondary text of your ads. It will be the image for your google ads, linkdin ads, or instagram ads or google for jobs etc ...|
|url|String|Url of the job on your website. Mantory for the campaign publishing|
|status|String|Status of your campaign. Is read only value|
|user_id (required)|String|User id. Auto-generated|
|client_id|String|If you represent multiple employers|
|created_at|Date|Auto-generated|
|updated_at|Date|Auto-generated|
|live_at|Date|Auto-generated|
|end_at|Date|Auto-generated. 30 days after the live at date|


# OTHER

## Pricing & Billing

### How much does it cost to use Post a job ?
We offer straightforward pricing that compliments your usage needs and business goals.
We have a freemium version you can try who will post on more than 10 differents channels (Google for job, Indeed, Joblift, Jooble etc ....) . You can try without credit card.
Then , you can add a budget to your campaign and we will start to advertise your job, on top of free channels on paid channels ( facebook , google , linkedin depending the profil and the localisation )

## FAQ 

### What is Postajob?

Postajob provides state-of-the-art, api to post your job on multiple platforms to hire peoples worldwide. Through one API, you can reach thousand of channels : jobboard, facebook ads for job, google ads for job, reddit ads, quora ads, niche jobboards etc. 
Founded in 2018, we’re headquartered in Amsterdam office offices in Netherlands. We’re a venture backed organization with customers all over the world. [Learn more about Postajob.](https://postajob.io/)

### How to use Post a job

Post a job is designed for software developers and we’ve made it simple to interact with our technology via an API (ask your tech team). Just integrate with our easy to code endpoints to get up and running.

### What features does Postajob offer?

We’re deeply focused on easy and smart job diffusion 

### Do you have a Demo?

We do demo on demand [Ask for a demo](https://www.postajob.io/get-a-demo/) 


## Help and support

We'd love to hear feedback from you and we're also here to help if you have any challenges. We have lots of answers to popular questions in our [FAQ](https://github.com/postajob/api/blob/master/README.md#faq). Failing that, feel free to contact our [Support team](mailto:contact@postajob.io) .



# Channels list

Please find bellow all channels we gathered from differents sources. If you want to suggest a new channel, please go here [Suggest a new channel](https://sebastien168902.typeform.com/to/R0mm81) 


* [Facebook group] React Native Jobs [More info](https://directory.postajob.io/channel/react-native-jobs)
* [Freelance Platform] Virtualstaff [More info](https://directory.postajob.io/channel/virtualstaff)
* [Freelance Platform] Freelancer [More info](https://directory.postajob.io/channel/freelancer)
* [Freelance Platform] FreshGigs [More info](https://directory.postajob.io/channel/freshgigs)
* [Freelance Platform] Guru [More info](https://directory.postajob.io/channel/guru)
* [Freelance Platform] Jellow [More info](https://directory.postajob.io/channel/jellow)
* [Freelance Platform] Fiverr [More info](https://directory.postajob.io/channel/fiverr)
* [Freelance Platform] Malt [More info](https://directory.postajob.io/channel/malt)
* [Freelance Platform] Onlinejobs [More info](https://directory.postajob.io/channel/onlinejobs)
* [Freelance Platform] Upwork [More info](https://directory.postajob.io/channel/upwork)
* [Freelance Platform] Truelancer [More info](https://directory.postajob.io/channel/truelancer)
* [Job Board] Jobs77 PK [More info](https://directory.postajob.io/channel/jobs77-pk)
* [Job Board] Careertrotter [More info](https://directory.postajob.io/channel/careertrotter)
* [Job Board] Craigs List Amsterdam [More info](https://directory.postajob.io/channel/craigs-list-amsterdam)
* [Job Board] Craigs List Manila [More info](https://directory.postajob.io/channel/craigs-list-manila)
* [Job Board] Craigs List Paris [More info](https://directory.postajob.io/channel/craigs-list-paris)
* [Job Board] Dice [More info](https://directory.postajob.io/channel/dice)
* [Job Board] hitmarkerjobs [More info](https://directory.postajob.io/channel/hitmarkerjobs)
* [Job Board] ExpatRu [More info](https://directory.postajob.io/channel/expatru)
* [Job Board] Work [More info](https://directory.postajob.io/channel/work)
* [Job Board] Jobstreet PH [More info](https://directory.postajob.io/channel/jobstreet-ph)
* [Job Board] Whitetruffle [More info](https://directory.postajob.io/channel/whitetruffle)
* [Job Board] Apec [More info](https://directory.postajob.io/channel/apec)
* [Job Board] Apnijobs [More info](https://directory.postajob.io/channel/apnijobs)
* [Job Board] Gigajob [More info](https://directory.postajob.io/channel/gigajob)
* [Job Board] Glassdoor [More info](https://directory.postajob.io/channel/glassdoor)
* [Job Board] Google for Jobs [More info](https://directory.postajob.io/channel/google-for-jobs)
* [Job Board] Authentic Jobs [More info](https://directory.postajob.io/channel/authentic-jobs)
* [Job Board] HeadHunter.ru [More info](https://directory.postajob.io/channel/headhunterru)
* [Job Board] Hello Linda [More info](https://directory.postajob.io/channel/hello-linda)
* [Job Board] Indeed [More info](https://directory.postajob.io/channel/indeed)
* [Job Board] Infoempleo [More info](https://directory.postajob.io/channel/infoempleo)
* [Job Board] Bayrozgar [More info](https://directory.postajob.io/channel/bayrozgar)
* [Job Board] Jobisland  [More info](https://directory.postajob.io/channel/jobisland)
* [Job Board] Joblift [More info](https://directory.postajob.io/channel/joblift)
* [Job Board] Jobrapido [More info](https://directory.postajob.io/channel/jobrapido)
* [Job Board] Adzuna [More info](https://directory.postajob.io/channel/adzuna)
* [Job Board] Jobsinmoscow [More info](https://directory.postajob.io/channel/jobsinmoscow)
* [Job Board] Bossjob [More info](https://directory.postajob.io/channel/bossjob)
* [Job Board] Jooble [More info](https://directory.postajob.io/channel/jooble-nl)
* [Job Board] Jora [More info](https://directory.postajob.io/channel/jora)
* [Job Board] Le bon coin [More info](https://directory.postajob.io/channel/le-bon-coin)
* [Job Board] Learn4good [More info](https://directory.postajob.io/channel/learn4good)
* [Job Board] Linkedin [More info](https://directory.postajob.io/channel/linkedin)
* [Job Board] Career.ru [More info](https://directory.postajob.io/channel/careerru)
* [Job Board] Monster France [More info](https://directory.postajob.io/channel/monster-france)
* [Job Board] Monster NL [More info](https://directory.postajob.io/channel/monster-nl)
* [Job Board] Mustakbil [More info](https://directory.postajob.io/channel/mustakbil)
* [Job Board] Mynimo [More info](https://directory.postajob.io/channel/mynimo)
* [Job Board] Nationale vacature bank [More info](https://directory.postajob.io/channel/nationalevacaturebank)
* [Job Board] Naukri [More info](https://directory.postajob.io/channel/naukri)
* [Job Board] Naukri junction [More info](https://directory.postajob.io/channel/naukri-junction)
* [Job Board] Neuvoo [More info](https://directory.postajob.io/channel/neuvoo)
* [Job Board] Offre emploi madagascar [More info](https://directory.postajob.io/channel/offre-emploi-madagascar)
* [Job Board] Careerist [More info](https://directory.postajob.io/channel/careerist)
* [Job Board] Paris job [More info](https://directory.postajob.io/channel/paris-job)
* [Job Board] Pole Emploi [More info](https://directory.postajob.io/channel/pole-emploi)
* [Job Board] Portaljob madagascar [More info](https://directory.postajob.io/channel/portaljob-madagascar)
* [Job Board] Careerjet [More info](https://directory.postajob.io/channel/careerjet)
* [Job Board] Rabota [More info](https://directory.postajob.io/channel/rabota)
* [Job Board] Careerjet Ru [More info](https://directory.postajob.io/channel/careerjet-ru)
* [Job Board] Careers24 [More info](https://directory.postajob.io/channel/careers24)
* [Job Board] Trovit NL [More info](https://directory.postajob.io/channel/trovit-nl)
* [Job Board] Recruiter [More info](https://directory.postajob.io/channel/recruiter)
* [Job Board] Reddit [More info](https://directory.postajob.io/channel/reddit)
* [Job Board] Reed [More info](https://directory.postajob.io/channel/reed)
* [Job Board] Transport.nl [More info](https://directory.postajob.io/channel/transportnl)
* [Job Board] Trabahotayo [More info](https://directory.postajob.io/channel/trabahotayo)
* [Job Board] TipTopJob [More info](https://directory.postajob.io/channel/tiptopjob)
* [Job Board] Rozee.pk [More info](https://directory.postajob.io/channel/rozeepk)
* [Job Board] Russiastartupjobs [More info](https://directory.postajob.io/channel/russiastartupjobs)
* [Job Board] Superjob [More info](https://directory.postajob.io/channel/superjob)
* [Job Board] TalentHunters [More info](https://directory.postajob.io/channel/talenthunters)
* [Niche Job Board] Dutchstartupjobs [More info](https://directory.postajob.io/channel/dutchstartupjobs)
* [Niche Job Board] icrunchdata [More info](https://directory.postajob.io/channel/icrunchdata)
* [Niche Job Board] Accounting jobs today [More info](https://directory.postajob.io/channel/accounting-jobs-today)
* [Niche Job Board] Botjobs [More info](https://directory.postajob.io/channel/botjobs)
* [Niche Job Board] Ycombinator [More info](https://directory.postajob.io/channel/ycombinator)
* [Niche Job Board] Kaggle [More info](https://directory.postajob.io/channel/kaggle)
* [Niche Job Board] Ux Jobs Board [More info](https://directory.postajob.io/channel/ux-jobs-board)
* [Niche Job Board] Workreactnative [More info](https://directory.postajob.io/channel/https-wwwworkreactnativecom)
* [Niche Job Board] AngelList [More info](https://directory.postajob.io/channel/angellist)
* [Niche Job Board] Angularhire [More info](https://directory.postajob.io/channel/angularhire)
* [Niche Job Board] Angularjobs [More info](https://directory.postajob.io/channel/angularjobs)
* [Niche Job Board] Mashable [More info](https://directory.postajob.io/channel/mashable)
* [Niche Job Board] Jobs.nrf [More info](https://directory.postajob.io/channel/jobsnrf)
* [Niche Job Board] Android Weekly [More info](https://directory.postajob.io/channel/android-weekly)
* [Niche Job Board] FrontendDeveloperJob [More info](https://directory.postajob.io/channel/frontenddeveloperjob)
* [Niche Job Board] Frontendrocket [More info](https://directory.postajob.io/channel/frontendrocket)
* [Niche Job Board] Fullstackjob [More info](https://directory.postajob.io/channel/fullstackjob)
* [Niche Job Board] Futurejobs [More info](https://directory.postajob.io/channel/futurejobs)
* [Niche Job Board] Geoawesomeness [More info](https://directory.postajob.io/channel/geoawesomeness)
* [Niche Job Board] Arstechnica [More info](https://directory.postajob.io/channel/arstechnica)
* [Niche Job Board] Github [More info](https://directory.postajob.io/channel/github)
* [Niche Job Board] Codepen [More info](https://directory.postajob.io/channel/codepen)
* [Niche Job Board] Welovegolang [More info](https://directory.postajob.io/channel/welovegolang)
* [Niche Job Board] CoolWorks [More info](https://directory.postajob.io/channel/coolworks)
* [Niche Job Board] kotlin-jobs [More info](https://directory.postajob.io/channel/kotlin-jobs)
* [Niche Job Board] Product Hunt [More info](https://directory.postajob.io/channel/product-hunt)
* [Niche Job Board] Producthire [More info](https://directory.postajob.io/channel/producthire)
* [Niche Job Board] Productschool [More info](https://directory.postajob.io/channel/productschool)
* [Niche Job Board] Python [More info](https://directory.postajob.io/channel/python)
* [Niche Job Board] Python jobs hq [More info](https://directory.postajob.io/channel/python-jobs-hq)
* [Niche Job Board] Android jobs [More info](https://directory.postajob.io/channel/android-jobs)
* [Niche Job Board] Blocktribe [More info](https://directory.postajob.io/channel/blocktribe)
* [Niche Job Board] IOS dev jobs [More info](https://directory.postajob.io/channel/ios-dev-jobs)
* [Niche Job Board] React jobboard [More info](https://directory.postajob.io/channel/react-jobboard)
* [Niche Job Board] React jobs [More info](https://directory.postajob.io/channel/react-jobs)
* [Niche Job Board] Vuejobs [More info](https://directory.postajob.io/channel/vuejobs)
* [Niche Job Board] ReactEurope [More info](https://directory.postajob.io/channel/reacteurope)
* [Niche Job Board] Crunchboard [More info](https://directory.postajob.io/channel/crunchboard)
* [Niche Job Board] Cryptojobslist [More info](https://directory.postajob.io/channel/cryptojobslist)
* [Niche Job Board] It Job Pro [More info](https://directory.postajob.io/channel/it-job-pro)
* [Niche Job Board] DataJobs [More info](https://directory.postajob.io/channel/datajobs)
* [Niche Job Board] Jobfony [More info](https://directory.postajob.io/channel/jobfony)
* [Niche Job Board] Designernews [More info](https://directory.postajob.io/channel/designernews)
* [Niche Job Board] Developpez.com [More info](https://directory.postajob.io/channel/developpezcom)
* [Niche Job Board] ihaterecruiters [More info](https://directory.postajob.io/channel/ihaterecruiters)
* [Niche Job Board] Ruby now [More info](https://directory.postajob.io/channel/ruby-now)
* [Niche Job Board] Jobs React Native Gallery [More info](https://directory.postajob.io/channel/jobs-react-native-gallery)
* [Niche Job Board] Scotch.io [More info](https://directory.postajob.io/channel/scotchio)
* [Niche Job Board] Stackoverflow [More info](https://directory.postajob.io/channel/stackoverflow)
* [Niche Job Board] Startuponly [More info](https://directory.postajob.io/channel/startuponly)
* [Niche Job Board] Student job [More info](https://directory.postajob.io/channel/student-job)
* [Niche Job Board] AI Jobs [More info](https://directory.postajob.io/channel/ai-jobs)
* [Niche Job Board] Swift Lang Jobs [More info](https://directory.postajob.io/channel/swiftlangjobs)
* [Niche Job Board] SwissDev Jobs [More info](https://directory.postajob.io/channel/swissdev-jobs)
* [Niche Job Board] Dribbble [More info](https://directory.postajob.io/channel/dribbble)
* [Niche Job Board] weloveangular [More info](https://directory.postajob.io/channel/weloveangular)
* [Programmatic Ad] Google Ad [More info](https://directory.postajob.io/channel/google-ad)
* [Programmatic Ad] Facebook Ads [More info](https://directory.postajob.io/channel/facebook-ads)
* [Programmatic Ad] Quora [More info](https://directory.postajob.io/channel/quora)
* [Reddit community] Androiddev [More info](https://directory.postajob.io/channel/androiddev)
* [Remote Job Board] Remote.co [More info](https://directory.postajob.io/channel/remoteco)
* [Remote Job Board] Jobspresso [More info](https://directory.postajob.io/channel/jobspresso)
* [Remote Job Board] Remotive [More info](https://directory.postajob.io/channel/remotive)
* [Remote Job Board] Weworkremotely [More info](https://directory.postajob.io/channel/weworkremotely)
* [Remote Job Board] Remoteok [More info](https://directory.postajob.io/channel/remoteok)
* [Slack channel] FranceJS [More info](https://directory.postajob.io/channel/francejs)
* [Slack channel] Kotlin lang [More info](https://directory.postajob.io/channel/kotlinlangslackcom)
* [Slack channel] Reactiflux [More info](https://directory.postajob.io/channel/reactiflux)
* [Slack channel] Android chat [More info](https://directory.postajob.io/channel/android-chat)
* [Slack channel] Firebase community [More info](https://directory.postajob.io/channel/firebase-community)
* [Slack channel] IOS developers.io [More info](https://directory.postajob.io/channel/ios-developersio)
* [Slack channel] Expo Slack [More info](https://directory.postajob.io/channel/expo-slack)
* [Slack channel] botkit.ai [More info](https://directory.postajob.io/channel/botkitai)
* [Slack channel] Elixir  [More info](https://directory.postajob.io/channel/elixir)
* [Slack channel] Bot Developer Hangout [More info](https://directory.postajob.io/channel/bot-developer-hangout)
* [Slack channel] WeLearnJs [More info](https://directory.postajob.io/channel/welearnjs)
* [Slack channel] Threejs [More info](https://directory.postajob.io/channel/threejs)
* [Twitter feed] React native job twitter [More info](https://directory.postajob.io/channel/react-native-job-twitter)
* [University Job Board] The Limoges Computer Sciences Engineering School [More info](https://directory.postajob.io/channel/the-limoges-computer-sciences-engineering-school)
* [University Job Board] ENSMM [More info](https://directory.postajob.io/channel/ensmm)
* [University Job Board] EPITECH [More info](https://directory.postajob.io/channel/epitech)
* [University Job Board] IMT Atlantique [More info](https://directory.postajob.io/channel/imt-atlantique)
* [University Job Board] Traineeshipplaza [More info](https://directory.postajob.io/channel/traineeshipplaza)
* [University Job Board] ESEO [More info](https://directory.postajob.io/channel/eseo)
* [University Job Board] ESIEA [More info](https://directory.postajob.io/channel/esiea)
* [University Job Board] ISEP [More info](https://directory.postajob.io/channel/isep)
* [University Job Board] Efrei Paris [More info](https://directory.postajob.io/channel/efrei-paris)
* [University Job Board] 42 [More info](https://directory.postajob.io/channel/42)
* [University Job Board] L'étudiant [More info](https://directory.postajob.io/channel/letudiant)
* [University Job Board] Institut Mines-Télécom Business School et Télécom SudParis [More info](https://directory.postajob.io/channel/institut-mines-telecom-business-school-et-telecom-sudparis)
* [University Job Board] Isima [More info](https://directory.postajob.io/channel/isima)
* [University Job Board] Epita [More info](https://directory.postajob.io/channel/epita)
* [University Job Board] Bordeaux-inp [More info](https://directory.postajob.io/channel/bordeaux-inp)
* [University Job Board] Centrale Nantes [More info](https://directory.postajob.io/channel/centrale-nantes)
* [University Job Board] Association des diplômés de Télécom SudParis et de Institut Mines-Télécom Business School [More info](https://directory.postajob.io/channel/association-des-diplomes-de-telecom-sudparis-et-de-institut-mines-telecom-business-school)
* [University Job Board] Studyrama emploi [More info](https://directory.postajob.io/channel/studyrama-emploi)
* [University Job Board] EISTI [More info](https://directory.postajob.io/channel/eisti)
* [University Job Board] Young Capital [More info](https://directory.postajob.io/channel/youngcapital)
* [University Job Board] Supinfo [More info](https://directory.postajob.io/channel/supinfo)
* [University Job Board] ENSEEIHT [More info](https://directory.postajob.io/channel/enseeiht)
* [University Job Board] Groupe-insa [More info](https://directory.postajob.io/channel/groupe-insa)
* [University Job Board] ENSEIRB-MATMECA [More info](https://directory.postajob.io/channel/enseirb-matmeca)
* [University Job Board] Telecom ParisTech [More info](https://directory.postajob.io/channel/telecom-paristech)
* [University Job Board] Telecom Physique Strasbourg [More info](https://directory.postajob.io/channel/telecom-physique-strasbourg)
* [University Job Board] École nationale supérieure d'ingénieurs de Caen [More info](https://directory.postajob.io/channel/ecole-nationale-superieure-dingenieurs-de-caen)
* [University Job Board] École nationale supérieure d'ingénieurs en informatique, automatique, mécanique, énergétique et électronique [More info](https://directory.postajob.io/channel/ecole-nationale-superieure-dingenieurs-en-informatique-automatique-mecanique-energetique-et-electronique)

