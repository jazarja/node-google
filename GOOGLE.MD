https://seoheronews.com/url-google

URL parameters of the Google search engine results page
20 April 2017

37450 site views

There is a possibility to adjust the results for the base query (which corresponds to the value of the parameter q or as_q ) using a number of get-parameters of the format variable=value used in the URL of the page of search results after the substring /search? . The use of these parameters can be very useful when parsing search results. 

A basic set of these parameters can be determined through the use of:

    Advanced search filters; 
    Search Tools; 
    And individual search settings. 

It is noteworthy that some of the URL parameters page results of Google are accompanied by the appearance of the corresponding search operators in the search form.
This is the set of parameters with a value in the search phrase: 

    as_epq a search phrase in the exact form analogue of the operator "" (quotation marks) 
    as_oq – search on any word phrase, an analog OR operator 
    as_eq – exclude from the query phrase, the analogue of the operator – (minus) 

Also, with other types of parameters values: 

    as_nlo and as_nhi – define beginning and end of the digital range, respectively, the analogue of the operator .. (two dots) 
    as_sitesearch – narrow the scope of the search to the specified site, an analogue of the operator site: 
    as_rq – looking pages similar to a given document (as the value is the URL of the document), the analogue of the operator related: 
    as_occt specifies the area of the document to search, takes values 
        as_occt=title (the title tag, the analogue of the operator allintitle: )
        as_occt=body (search in the page text, like an operator allintext: )
        as_occt=url (search in the page URL, the analogue of the operator allinurl: )
        as_occt=links (search in texts page references, an analogue of the operator allinanchor: )
        as_filetype specifies the format of documents to search (the analogue of the operator filetype: ) and taking values                                                                           pdf, ps, dwf, kml, kmz, xls, ppt, doc, rtf, swf.

Other types of parameters do not produce changes in the search line. 

Language settings: 

    lr – the language of the document (accept values in the form lr=lang_ru where the last two letters indicate the language index, in this example – Russian) 
    hl – language interface (adopts values in the form of a two-letter index of language such as hl=ru – for Russian). It is noteworthy that this parameter affects the results, some advantage get documents in the language of the interface. 

Regional settings:

    cr – country paper (accepts values in the form cr=countryRU where the last two letters indicate the country index, in this example Russia). 
    gl is the country of the document, accepts values in the form of a two-letter code of the country (for example, gl=ru for Russia), an analogue of the operator cr, however, builds great results from it). It is worth noting that when you use the operators cr and gl in top issue are mixed sites of the region or country of the user if it does not match with the country specified by the operator 
    near – very interesting undocumented parameter that you can specify as a value the name of the settlement (in English or Russian language, for example, near=moscow or near=москва ). However, this results is no results for the specified locality. Apparently, this option in the results constructed for the region of the user, gives the sites specified in the value of the settlement some advantage. 

Time parameters: 

    as_qdr and tbs – search for documents with a specific date of the update (when used together, the setting takes precedence tbs). 

Take baseline values: 

                                                              as_qdr                                                                                                                      
	
                                                              tbs                                                                                                                      
                                                              over the last hour                                                            
	
                                                              h                                                                                                                      
	
                                                              qdr:h                                                                                                                      
                                                              in the last 24 hours                                                            
	
                                                              d                                                                                                                      
	
                                                              qdr:d                                                                                                                      
                                                              over the last week                                                             
	
                                                                w                                                                                                                          
	
                                                                qdr:w                                                                                                                          
                                                                for the last month                                                               
	
                                                                  m                                                                                                                              
	
                                                                  qdr:m                                                                                                                              
                                                                  over the past year                                                                
	
                                                                  y                                                                                                                              
	
                                                                  qdr:y                                                                                                                              
                                                                  for all time                                                                                                                              
	
                                                                  all                                                                                                                              
	
                                                                  qdr:all                                                                                                                              

If the underlying values (except for the time), add the number, you can get the results for a few relevant time intervals, for example, the combination as_qdr=h9 narrows the results to documents updated in the past 9 hours, and the combination oftbs= qdr:m24 – in the last 24 months.
Also by using tbs you can specify a date range update of the document, in this case, it takes the following format:  
tbs=cdr:1,cd_min:01.07.2016,cd_max:01.08.2016 (in this example, the range from 01.07.1016 to 01.08.2016)
If you are using time parameters with the specified values to set the parameter tbs extra value sbd:1 , the results will be ranked not by relevance, but by the time the updates. This method does not work only in case if the parameter as_qdr has the value all. So to get the results for all time, sorted by update time, you can only use a combination of tbs=sbd:1,qdr:all
The tbs operator, being versatile, can also take value li:1 – search for in fine form (similar operator “”), but in this case, the search form is no occurrence of the operator concerned.

Settings content filtering: 

    safe values are active and on includes filtering obscene results with safe search. Set to off disables the filter if the search setting was enabled, a "Safe search"; this option can be very useful for determining if a specific website or document under this filter 
    as_rights – setting various options the rights to use the content 
    tbm – search for different types of content that takes values 
        app – search for apps
        bks – search for books
        isch – search by image
        nws – news search
        pts – Google patents
        shop – search by shops
        vid – video search

The parameters control the search results:

    num – number of results per page the search takes values from 1 to 100
    start – display issue, starting at the specified position (for example, start=100)
    newwindow=1 to open links in a new window
    filter=0 show hidden results that are very similar to the already presented
    pws – the personal search results, accepts values 0 (personal results are hidden) and 1 (personal included)