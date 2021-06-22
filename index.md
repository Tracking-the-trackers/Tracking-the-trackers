# Tracking the Trackers: Ethical measurements of web privacy leakages in-the-wild <br> 22 June, 14:00 BST @ WebSci 2021

_[Nishanth Sastry](https://nishrs.github.io), [Guillermo Suarez De Tangil](https://nms.kcl.ac.uk/guillermo.suarez-tangil/), [Nicolas Kourtellis](https://scholar.google.com/citations?user=Q5oWwiQAAAAJ), [Mainack Mondal](https://cse.iitkgp.ac.in/~mainack/), [Xuehui (Rachel) Hu](https://rachelkcl.github.io/), [Pushkal Agarwal](https://pushkal17.github.io/)_
<br>
_University of Surrey, IMDEA Networks, King’s College London, Telefonica Research, IIT Kharagpur_


<hr>


First introduced in the mid-nineties as a way of recording client-side state, cookies have proliferated widely on the Web, and have become a fundamental part of the Web ecosystem. However, there is widespread concern that cookies are being abused to track and profile individuals online for commercial, analytical and various other purposes. Consequently, there has been an explosion of research into understanding the prevalence of tracking on the Web, and the resulting leakage of Personally Identifiable Information (PII). In this tutorial, we aim to introduce the audience to state-of-the-art empirical measurement methods and techniques that are being used to understand and quantify web tracking in-the-wild.



## Introduction (14:00 - 14:10 BST)
* Agenda & Overview
* Specify some familiarity with JS and Python
* Quick heads up about setup needed for the lab


### Types/means of tracking ([Slides](https://docs.google.com/presentation/d/1xN4eDoda5JVwajeW5RqkrpD09usYB8GQ_5nZ4r1ojfI/edit?usp=sharing)) (14:10 - 14:35 BST)
* Cookies
* Cookie Synchronization
* Invisible pixels
* Device Fingerprinting
* CNAME Cloaking Tracking


### GDPR and Consent Management on the Web ([Slides](https://docs.google.com/presentation/d/12iHy-H8nYRD7VYq74m6zTQEbsiV2tuogHsmC63pLIpQ/edit?usp=sharing)) (14:35 - 15:00 BST)
* Legal and regulatory basis for fighting back against trackers
* GDPR and other data privacy laws around the world
* Industry fightback (and ways to manage the regulatory burden)
     - IAB, ICC Categories and Consent Management Platforms
     - Dark Patterns to deceive users to consent to tracking



### Ethical and privacy-preserving internet-mediated research ([Slides](https://docs.google.com/presentation/d/1bCyiqwpBhBrHitSF7ttxD_p-N78Aj4es16XkJYfRylE/edit?usp=sharing)) (15:00 - 15:35 BST)
* Tracking as internet-mediated research 
* The Belmont Report 
* Basic ethical principles 
* Theories of data privacy 
* Ensuring ethics and privacy of Internet-mediated research


### Practical Session Teaser (15:35 - 15:45 BST)
* Automated measurements (OpenWPM and barebone Selenium) ([Slides](https://drive.google.com/file/d/1Y4Kdhy4viGHQ8dDkIOmT_IZUHK9V7Odf/view?usp=sharing)) ([Installations](https://docs.google.com/document/d/1CJQW2_0lBQenRbkB9gDy8sY7s8FBkfN8_pThHnfRDX0/edit?usp=sharing))
* Human-centered measurements (Browser extensions) ([Slides](https://drive.google.com/file/d/1IanDbMQU3ujs_gaKkJYzD2CdE87RBgAe/view?usp=sharing))


## Coffee Break (15:45 - 16:00 BST)

## Practical Session
Hands-on experience into state-of-the-art tools and techniques, including some developed by the tutorial organisers as well as some instructions for our github repositories and datasets. Most of the online activities will involve some light python scripting on Google Collab. Familiarity with Python will be helpful but not required. We will also build a basic browser extension to measure web privacy. Familiarity with Javascript and HTML will be helpful for this.
Optional requirements: 
- Chrome browser, to follow browser extension-related activities.
- Linux or Mac: to install OpenWPM (Not essential; but installation may provide additional insights into performing automated measurements)


### Automated measurements ([Slides](https://drive.google.com/file/d/1Y4Kdhy4viGHQ8dDkIOmT_IZUHK9V7Odf/view?usp=sharing)) ([Installations](https://docs.google.com/document/d/1CJQW2_0lBQenRbkB9gDy8sY7s8FBkfN8_pThHnfRDX0/edit?usp=sharing)) ([Google Collab](https://colab.research.google.com/drive/1flrWTgv9yMeSg9kL3Z1aBYtlJo110L2n?usp=sharing)) (16:00 - 16:45 BST)
* How to install / launch OpenWPM?
* What to do when anti-crawling mechanisms are deployed?
* What options / settings available?
* How to build synthetic profiles?
* What data should be collected?


### Human-centered measurements ([Slides](https://drive.google.com/file/d/1IanDbMQU3ujs_gaKkJYzD2CdE87RBgAe/view?usp=sharing)) ([Download](https://github.com/rachelkcl/Websci21Tutorial_Demo/blob/main/extensionDemo-HandOnSession.zip?raw=true)) ([Google Collab](https://colab.research.google.com/drive/1ZnrUxOUSfON_8FQ6z0UUT6r2LsN59p6p?usp=sharing)) (16:45 - 17:30 BST)
* How to create a browser extension?
* Monitoring and collecting user activity
* What data should be collected?
* Handling informed consent
* Aggregating and visualizing data
* Interpreting results
