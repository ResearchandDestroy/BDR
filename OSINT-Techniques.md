## OSINT Techniques

This documentation is for educational and research purposes only. The information obtained from this documentation can be used to discover potential sensitive and private information publicly available on the internet. While cyberstalking is illegal (for civilians), the act of sleuthing through public information, known as Open-Source Intelligence (OSINT) gathering is not. What makes the use of the information obtained through OSINT illegal is whether the researcher uses any information discovered within the public domain in malice or otherwise a harmful way to disrupt or invade the privacy of an individual. Research discretion is advised. 

While the clever advanced search operators used for finding people's information are out of scope for this documentation, much of these same techniques can be used to perform said operations. The goal of this documentation is to express a comprehensive start to "Dorking" and advanced search techniques to discover breach data and other publicly available information on the internet. You'll notice as you read through this, there are no shown example output from any of these search queries. This is by design as information online changes rapidly and what shows little today, could show an abundance tomorrow.

## DORK!: What is it?

The term "Dork" has been around for quite some time (More on the history here: https://en.wikipedia.org/wiki/Johnny_Long#Google_hacking). While the techniques mentioned seem foreign to the average user, those of us who've been on the internet for quite some time, and remember the techniques we had to use to find research back in the day, remember clever filter operators coupled with literal and figurative quotations to obtain the precise results we were looking for. These advanced search operators, or dorks are still around to this day, and have adapted to the plethora of information which has grown since the dawn of the internet. The average search query has a lot of these filters surrounding the initial request, where the search engine is effectively "dorking" for you. While helpful to the laymen using the average search platform, we as hackers and researchers prefer to carve that pumpkin with a scalpel, rather than a spoon.

## SLEUTHS & LETTERS: Select all that apply!

While there are tons of resources out there which go over each dork operator and it's specific function, a great resource from Cyb_Detective: https://github.com/cipher387/Dorks-collections-list, our goal is to demonstrate which functions apply to the discovery of publicly available breach data. In order to find breach data, one doesn't simply type "breach data" into their favorite search engine. You have to learn the lingo.

As with most criminal syndicates, they tend to share code words and their own language when sharing information with each other. More experienced hackers may be familiar with the term "combolists" or "fresh fullz", where the data shared is either in email:password format, or simply a CSV file listing full names, addresses, phone numbers, and sometimes credit card numbers or Social Security numbers. There's other lingo worth mentioning here, but most can be simply thought out using a bit of common sense and OSINT. What would you call breach data in your own language? 👻

## HUMINT RESOURCES: Google me, baby; are you crazy? - Jay-Z

Human Intelligence (HUMINT) is the subtle art of gathering information about a human being and collectives. Hackers, especially Black-hat hackers, have their own language to describe their enemies, new comers, the Feds, and even their loot. Without going too deep into the weeds, there are various resources out there to start learning some of the language used to describe whatever plunder is being shared and the datasets specifically leaked. Use your resources where we all know hackers hang out, such as Twitter (Now: X 🤮🤦🏽), Reddit, and deep within the Fediverse. This is not limited to the more private channels on several platforms such as Telegram, Discord and other chat platforms, as well as exclusive hacker forums found all around the world in various languages. The moral of this story is: the internet is big... like really BIG... it's so big, you wouldn't believe just how big it really is! ...and it was all made by humans. Learn what these humans call the things they share, and you can learn how to find them too.

## ARE YOU A ROBOT?: Aren't we all nowadays?

After doing some HUMINT into the criminal underbelly of the internet, learning the lingo and where data tends to be leaked, we can change our focus back to the dorks. Let's take a simple term, like combolist, and plug it into our search engine like so:
`intext:"combolist"`
This should yield quite the result... if you weren't just stopped by your search engine to prove you're not a robot. 🤖 We go through motions carefully selecting the STOP signs, crosswalks, and bicycles until we get a ✅ and we're able to see the results... or at least what that particular search engine showed you based on your current location, query format, and sensitivity in some cases. The results may seem numerous, but that's likely not all the results you could possibly get from around the world from various search engines. 

## ENTER DORXNG: Shameless plug 😏

Ok, you had to see this one coming. Check out our [DorXNG](https://github.com/researchanddestroy/dorxng) project. The goal of DorXNG was to solve the exact issue mentioned above. While other search engines (who shall not be named... *cough G👀gle) tend to police and limit your results based on your location, DorXNG gets around this by routing requests over TOR and effectively around the world... and also through 7 primary search engines outside the great Noodle Oracle. 🧙‍♂️ Leveraging this resource, standing up our own instances, we're able to maximize our results from every dork we throw at it!

## MOAR RESOURCES IS YES: And how!

While working on the DorXNG project, we happened to discover a new AI powered resource to be used for dork generation. Check out [DorkGPT](https://dorkgpt.com/) for more details.
Obviously this is basically why this documentation doesn't show you how to dork for specific information, even breach data, but rather details the steps necessary to familiarize yourself with the latest lingo and resources where threat actors are sharing this leaked data, so you can use tools like DorkGPT and DorXNG to find it all!

## CONCLUSION: Is it over yet?

Go forth sleuths, researchers, consultants, and hackers alike. Use this guidance as a map to plot your own course into the vast treasure trove of information that is the internetz. As always, stay safe, practice your OpSec, and...

# HACK THE PLANET! 💻🖧🌍
