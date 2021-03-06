---
layout: api-documentation
title : 'Vehicle Inventory Listings by Dealer ID'
title_active_left_menu: 'Vehicle Listings'
title_parent: Api documentation

amount_version: 1
title-endpoint: 'Get Inventory Listings by Dealer ID'
spec: vehicle_listings
version: v1
api: inventory
dropdown-link: 'api/inventory/v1/getall'


level: 4
description_edpoint: 'Get Inventory Listings by Dealer ID'
title_md : Response format
number: 3

---

###Response format

	{
	  "totalCount": {integer},
	  "resultsList": [
	    {
	      "year": {integer},
	      "features": {array},
	      "options": {array},
	      "make": {string},
	      "model": {string},
	      "bodyType": {string},
	      "trim": {string},
	      "modelYearId": {integer},
	      "styleId": {integer},
	      "transmission": {string},
	      "modelLinkCode": {string},
	      "submodelId": {integer},
	      "combinedMpg": {integer},
	      "styleName": {string},
	      "submodel": {string},
	      "inventoryType": {string},
	      "engineSize": {integer},
	      "driveTrain": {string},
	      "franchiseId": {integer},
	      "exteriorColor": {string},
	      "interiorColor": {string},
	      "carfaxes": {array},
	      "hasBuildDataAndFullyMatched": {boolean},
	      "vin": {string},
	      "mileage": {integer},
	      "inventoryId": {integer},
	      "cityMpg": {integer},
	      "hwyMpg": {integer},
	      "msrpPrice": {integer},
	      "inventoryPrice": {float},
	      "stockNumber": {string},
	      "vehicleComments": {string},
	      "exteriorGenericColor": {string},
	      "interiorGenericColor": {string},
	      "guaranteedPrice": {float},
	      "gpexperiationDate": {date},
	      "tmvinventoryPrice": {float},
	      "tmvdealerCash": {flot},
	      "tmvcustomerIncentives": {float},
	      "invoicePrice": {float},
	      "dealerInPDP": {boolean},
	      "dealerName": {string},
	      "dealerAddress": {string},
	      "dealerPhone": {string},
	      "dealerLatitude": {float},
	      "dealerLongitude": {float},
	      "dealerDistinace": {float},
	      "dealerServiceRating": {float},
	      "dealerSaleRating": {float},
	      "countMatchedVehicles": {integer},
	      "countAllVehicles": {integer},
	      "dealerLocationId": {integer},
	      "dealerSalesReviewsCount": {integer},
	      "dealerServiceReviewsCount": {integer},
	      "dealerMake": {string},
		  "f34PhotoUrlsE": {string},
		  "f34PhotoUrlsSE": {string},
		  "f34PhotoUrlsT": {string},
		  "photoUrlsST": {array},
		  "photoUrlsST": {array},
		  "photoUrlsST": {arrat},
		  "tmvPrice": {float}
		  "premierDealer": {boolean}
	    }
	  ]
	}


| Property      				| Description                         						| Visibility    	|
|:------------------------------|:----------------------------------------------------------|:----------------- |
| totalCount    		   		| Total count of results			 						| Edmunds, Partners |
| year		    		    	| The car year												| Edmunds, Partners |
| features	    		    	| Array of features this car has	 						| Edmunds, Partners |
| options	    		    	| Array of options this car has								| Edmunds, Partners |
| make		    		    	| The car make						 						| Edmunds, Partners |
| model		    		    	| The car model						 						| Edmunds, Partners |
| bodyType	    		    	| The car type or category (see Vehicle API overview)		| Edmunds, Partners |
| trim		    		    	| The car trim												| Edmunds, Partners |
| modelYearId    		    	| The Model Year ID of this car								| Edmunds, Partners |
| styleId	    		    	| The style ID of this car									| Edmunds, Partners |
| transmission    		    	| The transmission type on this car 						| Edmunds, Partners |
| modelLinkCode    		    	| The manufacturer's model code for this car				| Edmunds, Partners |
| submodelId    		    	| The submodel ID for this car (i.e. Sedan, ..etc)			| Edmunds, Partners |
| combinedMpg    		    	| The combined MPG for this car								| Edmunds, Partners |
| engineSize    		    	| The size of this car's engine								| Edmunds, Partners |
| driveTrain    		    	| The drivetrain of this car								| Edmunds, Partners |
| styleName	    		    	| The style name of this car								| Edmunds, Partners |
| submodel	    		    	| The car's submodel										| Edmunds, Partners |
| inventoryType    		    	| Is this car NEW, USED or CPO?		 						| Edmunds, Partners |
| franchiseId    		    	| The dealer ID						 						| Edmunds, Partners |
| exteriorColor    		    	| The car's exterior color			 						| Edmunds, Partners |
| interiorColor    		    	| The car's interior color			 						| Edmunds, Partners |
| hasBuildDataAndFullyMatched   | Is the built data available for this car?					| Edmunds			|
| carfaxes	    				| The Carfax data for this car								| Edmunds, Partners |
| mileage	    				| The number of miles this car has on it					| Edmunds, Partners |
| vin		    				| The total count of car makes/brands 						| Edmunds, Partners |
| inventoryId    				| The inventory ID											| Edmunds			|
| cityMpg	    				| The car's City MPG				 						| Edmunds, Partners |
| HwyMpg	    				| The car's Highway MPG										| Edmunds, Partners |
| msrpPrice	    				| The MSRP of this car										| Edmunds, Partners |
| inventoryPrice   				| The price set for this car		 						| Edmunds, Partners |
| stockNumber    				| The stock number of the car								| Edmunds, Partners |
| vehicleComment   				| Comments on this vehicle			 						| Edmunds			|
| exteriorGenericColor			| Exterior generic color			 						| Edmunds, Partners |
| interiorGenericColor			| Interior generic color			 						| Edmunds, Partners |
| guaranteedPrice 				| Edmunds.com's guaranteed price	 						| Edmunds, Partners |
| gpexperiationDate				| Guaranteed Price expiration date	 						| Edmunds			|
| tmvinventoryPrice				| TMV price for this car									| Edmunds, Partners |
| tmvdealerCash    				| Dealer cash for this car			 						| Edmunds, Partners |
| tmvcustomerIncentives			| Customer incentives for this car	 						| Edmunds, Partners |
| invoicePrice    				| The invoice price on this car		 						| Edmunds, Partners |
| dealerInPDP    				| Is this dealership in Edmunds PDP?						| Edmunds			|
| dealerName    				| The name of the dealership selling this car				| Edmunds, Partners |
| dealerAddress    				| The dealership address			 						| Edmunds, Partners |
| dealerPhone    				| The dealership phone number		 						| Edmunds, Partners |
| dealerLatitude    			| The dealership location coordinates 						| Edmunds, Partners |
| dealerLongitude    			| The dealership location coordinates  						| Edmunds, Partners |
| dealerDistinace    			| Distance from the zipcode supplied						| Edmunds, Partners |
| dealerServiceRating  			| Dealership Service rating			 						| Edmunds, Partners |
| dealerSaleRating    			| Dealership Sale rating									| Edmunds, Partners |
| countMatchedVehicles 			| Number of matched cars at the dealership					| Edmunds, Partners |
| countAllVehicles    			| All vehicle count at the dealership						| Edmunds, Partners |
| dealerLocationId    			| Dealership location ID 			 						| Edmunds, Partners |
| dealerSalesReviewsCount		| Number of sales reviews this dealer has					| Edmunds, Partners |
| dealerServiceReviewsCount		| Number of service reviews this dealer has					| Edmunds, Partners |
| dealerMake	    			| The car make						 						| Edmunds, Partners |
| f34PhotoUrlsE	    			| Car photos						 						| Edmunds			|
| f34PhotoUrlsST    			| Car photos						 						| Edmunds			|
| f34PhotoUrlsT	    			| Car photos						 						| Edmunds			|
| photoUrlsST	    			| Car photos						 						| Edmunds			|
| photoUrlsE	    			| Car photos						 						| Edmunds			|
| photoUrlsT	    			| Car photos						 						| Edmunds			|
| tmvPrice		    			| The TMV Price						 						| Edmunds, Partner	|
| premierDealer	    			| Is this dealership a premier dealer? 						| Edmunds			|











