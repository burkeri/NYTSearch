NYT API Key: 7cb27f959b1a42e7a52b704024239909

how to structure queryURL: https://developer.nytimes.com/article_search_v2.json#/Documentation/GET/articlesearch.json

---

Request example:

REQUESTS
Searches for documents containing 'new york times' and returns results 20-29. Results are sorted by oldest to newest:
http://api.nytimes.com/svc/search/v2/articlesearch.json?q=new+york+times&page=2&sort=oldest&api-key=####

---

*Object Properties we will need:*
1. .headline
2. .main
3. .byline
4. byline.original
5. .section_name
6. .pub_date
7. .web_url (...as in the .web_url will be the property you need for the link)
