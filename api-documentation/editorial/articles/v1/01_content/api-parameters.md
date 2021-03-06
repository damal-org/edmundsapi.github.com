---
layout: api-documentation
title : 'Get Edmunds Articles by Category and/or car make/model/year'
title_active_left_menu: 'Articles'
title_parent: Api documentation

amount_version: 1
title-endpoint: 'Get Edmunds Articles by Category and/or car make/model/year'
spec: articles
version: v1
api: editorial
dropdown-link: 'v1/content'


level: 4
description_edpoint: 'Get Edmunds Articles by Category and/or car make/model/year'
title_md : Parameters
number: 2

---


###Parameters

| Parameter  	| Description                           | Possible Values   	| Default Value | Required                                                  |
|:--------------|:--------------------------------------|:----------------------|:------------- |:----------------------------------------------------------|
| category	 	| The article category          		| (see below)			| 		        | Yes/No (Not required if car make/model/year is supplied)  |
| fmt        	| Response format                       | json, xml         	| json          | Yes                                                       |
| make  	 	| The car make                  		| 						| 		        | No                                                        |
| model		 	| The car model                     	| 						| 		        | No                                                        |
| year  	 	| The car year                      	| 						| 		        | No                                                        |
| limit 	 	| Pagination range (from, to)			| 						| 0, 10	        | No                                                        |

### Available Article Categories

* auto finance
* awards
* best cars lists
* car news
* car buying
* car leasing
* car technology
* driving
* editor reviews
* extended warranties
* fuel economy
* how-to advice
* insurance
* maintenance & repair
* road tests
* selling
* top 10 lists
* vehicle safety
* warranties

