SELECT ?citingArticle ?citingArticleLabel ?citedArticle ?citedArticleLabel ?intention ?intentionLabel ?cito WHERE {
  ?citingArticle p:P2860 ?citationStatement .
  ?citationStatement pq:P3712 ?intention ;
                     ps:P2860 ?citedArticle .
  ?intention wdt:P31 wd:Q96471816 ;
             wdt:P2888 ?cito .
  SERVICE wikibase:label { bd:serviceParam wikibase:language "[AUTO_LANGUAGE],en". }
}
