# Nicolas' Mid-Bootcamp Project | A Gastro-Scene Showdown!

**WHICH CITY WILL BE CROWNED GOURMET-CAPITAL OF EUROPE?**

We have 10 exciting cities competing for this most glamorous title! As for our contender selection, I oriented myself by the (European) countries (and cities) of residence of my fellow Ironhack students and from there selected one city (except for Germany) that is sure to offer exciting culinary delights:
- Dusseldorf, Germany - my city of residence with some fantastic dining options, especially Asian food. But how will it stack up against these major contenders? I promise no bias on my part, just stone-cold data wrangling!
- Amsterdam, Netherlands - some fantastic (international) eateries here, home of the NL Ironhack remote campus. Thankfully the Dutch West India Company imported more than just goods!
- Barcelona, Spain - Madrid would also be a fantastic choice for restaurants, tough call but Barceló is just a special kind of cool!
- Berlin, Germany - bringing in a 2nd German contender against this overbearing cosmopolitan competition, chosen because several from my cohort live here, but also as it has what is probably Germany's most experimental restaurant scene.
- Istambul, Turkey - a major metropol straddling Europe and Asia, a fusion of east and west! We can expect an exciting culinary scene.
- Lisbon, Portugal - the cultural and political heart of Portugal, would expect nothing short of fantastic here! 
- London, UK - London breaks conventions, not just with the image of British food in general. A real dine-out heavyweight champ!
- Milan, Italy - no dining competition complete without some Italian flair. Chosen over Rome for it's fashion fame and economical strength - recipe for a stellar restaurant scene. Carpe Diem!
- Paris, France - what pan-european food competition would be complete without some 'joie de vivre'? 
- Zurich, Switzerland - no fellow students from here, chosen for my love of Switzerland and Zurich. Honestly cannot remember ever having had a disappointing meal anywhere in CH. 

**Questions we seek to answer with the research that follows:**

1. Which competing city will win the title 'Gourmet Capital of Europe'?
2. What is the probability of having a positive dining experience by randomly selecting any restaurant in our contestant cities?
3. Which restaurants are the best in each city?
4. City Restaurant Heatmaps - Where am I most likely to find a good restaurant? Are there any clusters?
5. "Ceap&Cheerful-Meter" (TM) - Which restaurants offer a good bang for your buck?

**INTRODUCTORY NOTE ON DATA METHODOLOGY:** 

I had attempted to code a webcrawler to parse Google Maps and scrape restaurant information using Python, but ran into several issues that I was unable to resolve by myself. Instead, I used outscraper.com, an online scraping tool to do the job for me. 

Doing so unfortunately limited my sample size to 500 restaurants/rows per city as that was the maximum free query size allowed by the tool. A smaller city target like Dusseldorf or Zurich may or may not actually have around that many restaurants, but major cities like Berlin, Paris or London would likely have far more. Additionally, I had little control over the logic applied by the tool (or rather Google Maps) in giving me my 500 'restaurant' search results per city - though I assume Google would use it's considerable AI clout to deliver results of the most searched/selected/popular restaurants in any given location in descending order. Yet, not all values in each dataset may actually be fully-fledged restaurants - some may be cafés, bakeries or delicacy shops (Et al.) that sell meals, and even some (*shudders*) fast-food franchises. 

**GitHub Repository:** https://github.com/NicolasVollmer/My_Ironhack_Mid-Bootcamp_Project

**Presentation on Tableau Online:** https://public.tableau.com/app/profile/nicolas.vollmer/viz/NicolasMid-BootcampProjectAGastro-SceneShowdown/Milan?publish=yes