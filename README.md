# CeneoScraper

https://www.ceneo.pl/136115744;48082-0v.htm#tab=reviews

##  Algorithm for exstracting opinions about single product on ceneo
1. Send the request fir acessing firs webpage with opinions about product
2. If response is ok, parse HTML page content into DOM structure
3. Extract  opinions and their components from DOM structure
4. Asign opinions with their components to complex data structures
5. If there are more pages with opinion, repeat steps from 1-5
6. Save data structures with opinions into database

## Structure of single opinion in ceneo.pl
Component|Variables|Selector|
|---------|---------|-------|
|opinion|opinion||
|opinion ID|opinion ID||
|opinion’s author|aithor||
|author’s recommendation|recommend||
|score expressed in number of stars|stars||
|opinion’s content|content||
|list of product advantages|pros||
|list of product disadvantages|cons||
|how many users think that opinion was helpful|up_vote||
|how many users think that opinion was unhelpful|down_vote||
|publishing date|publish||
|purchase date|purchased||

 