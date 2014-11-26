comparetext
===========

Compare Text Api to Compare Text 


Usage
==========

**Base URL:** [https://comparetext.herokuapp.com/](https://comparetext.herokuapp.com/)

**Output:** JSON


Three Main REST operations
====================
	
###Get delta between two text strings
#### GET `/getdelta/< string1 >/<string2>/` 
		
			for eg. 
			*[https://comparetext.herokuapp.com/getdelta/melvin/philips](https://comparetext.herokuapp.com/getdelta/melvin/philips) 	 

**Parameters:**

| Name | Type | Description |
| ---- | ---- | ----------- |
| `string1` | string | text 1 |
| `string2` | string | text2 |
		 
###Get similarity in percentage 
#### GET `/getsimilarity/< string1 >/< string2 >/` 
		 
			for eg. 
			*[https://comparetext.herokuapp.com/getsimilarity/melvin/philips](https://comparetext.herokuapp.com/getsimilarity/melvin/philips)
		 
**Parameters:**

| Name | Type | Description |
| ---- | :----: | :-----------: |
| `string1` | string | text1 |
| `string2` | string | text2 |

