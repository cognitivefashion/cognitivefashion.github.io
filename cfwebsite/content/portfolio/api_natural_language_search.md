+++
date = "2016-11-05T19:41:01+05:30"
title = "Natural Language Semantic Search"
draft = false
image = "img/portfolio/nls_1.jpg"
showonlyimage = false
weight = 2
+++

Search the product catalog in natural language.
<!--more-->

The Natural Language Semantic Search (NLS) for fashion allows the user to search a fashion e-commerce catalog using complex natural language queries. 

<img src="/img/portfolio/abofnls_2.jpg" width="600">

Below are a few sample queries that NLS can handle:

* Show me some black graphic print cotton tees under 1k in small size on sale.
* Can you show me some red dresses for my girlfriend for around 100 dollars ?
* Show me some red mandarin collar shirts.
* Show me some edgy longline tees for a party tonight.
* Show me some monochrome athleisure for my brother.

NLS enables the user to query the product catalog in a more natural language as you would have a conversation with seasoned sales assistant. This functionality enables a user to ask his query (requirements) in a more natural manner than the conventional keywords and filter based search. NLS can be seen as replacement for conventional search based on filters and a precursor to a full conversation system. NLS will work on existing product text attributes in catalog.

70% of shoppers use some form of digital site search.  Of those shoppers, 50% go straight to the search bar and shoppers who successfully use search are 2x more likely to convert, because they are often shopping with greater intent and in a late-stage buying mode.  

The increase in voice-based search and intelligent in-home speakers, like Alexa and Google Home, have started to disrupt the general search paradigm.  Consumers expect to search naturally, which usually means searching with questions words or searching with more complex queries, including everyday phrases.  If a retail site search returns and error page, or hundreds of irrelevant results when a customers searches “men’s white indoor running shoes under $100”, that retailer will surely experience lower click-through and conversions through search, and in many cases, a higher abandonment rate.


[API documentation](https://cognitivefashion.github.io/slate/#natural-language-search) 

</br>
## NLS features

1. Leverages the underlying IBM Fashion Taxonomy 
2. Understands various fashion attributes and user constraints
3. Internally handles query synonyms 
4. Appropriate semantic query back off 
5. Color Substitution 
6. Brand Substitution 
7. Spelling and phonetic corrections tuned to fashion taxonomy
8. Themes and collections capsules
9. Dynamically evolving fashion taxonomy 

> IBM fashion taxonomy is a semi-automatically curated comprehensive hierarchical fashion taxonomy for apparel, footwear, and accessories along with their attributes and relations. The taxonomy is curated from several fashion resources and then hand tuned by domain experts. This enables NLS to a very nuanced understanding of user requirements in the domain of fashion.
Fashion evolves constantly and hence IBM fashion taxonomy is dynamically updated at regular intervals to include the current fashion terms and trends. NLS will be delivered as a REST API on IBM cloud and hence the user will always have access to the latest fashion taxonomy.

</br>
