---
layout: api-documentation
title : 'Spec: Engine and Transmission'
title_active_left_menu: "Spec: Engine and Transmission"
title_parent: Api documentation

amount_version: 2
spec: spec_engine_and_transmission
version: v2
api: vehicle
dropdown-link: 'Select an Endpoint'


level: 2
overview: page_version

---

<div class="info-message">
 This resource provides engine and transmission details for a specific vehicle. Both engine and transmission are in essence a vehicle <a href="{{ PATH }}/api-documentation/vehicle/spec_equipment/v2/">equipment</a>.
</div>

### Engine Details

	{
		"id": {string},
		"name": {string},
		"equipmentType": "ENGINE",
		"availability": {string},
		"compressionRatio": {float},
		"cylinder": {integer},
		"size": {float},
		"displacement": {integer},
		"configuration": {string},
		"fuelType": {string},
		"horsepower": {integer},
		"torque": {integer},
		"totalValves": {integer},
		"manufacturerEngineCode": {string},
		"type": {string},
		"code": {string},
		"compressorType": {string}
	}

### Transmission Details

	{
		"id": {integer},
    	"name": {string},
		"equipmentType": "TRANSMISSION",
		"availability": {string},
    	"automaticType": {string},
    	"transmissionType": {string},
    	"numberOfSpeeds": {integer}
	}
	
