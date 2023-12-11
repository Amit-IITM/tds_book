## Lec 1.1 Discover the data - Introduction

3 things to learn :
- What are the different sources of datasets, where can you find them ?
- What are the different kinds of data sets ?
	- Structured
	- Unstructured
	- Semi-structured
- In each data set what kind of values you can find.

## Lec 1.2 Sources of Data

3 type of sources of datasets
- Public Data
	- Open and free
	- search online and find it
	- But this is mostly unorganized, so maybe the specific data which you are looking for is not there.
	- Even if it's there then there is a possibility that it's not in the desired format.
	- Source of Public datasets :
		- Awesome Public datasets catalogue on GitHub
		- GADM have data sets of every country about it's shapefiles of country, state and district level.
		- another source is "Google dataset search", kind of search engine for datasets. It finds datasets from other websites.
		- Kaggle datasets.
		- Govt data sites, e.g. dava.gov.in for India
			-  These datasets are approved by govt of that country, these are the official datasets. 
				- but not necessarily that these datasets are entirely true. there may be some human mistake, some masking or manipulation of data, error in data gathering. but still these results are official.
			- Their URL generally have first 2 characters of their country name as extension.
		- Some data community, E.g. DataMeet. 
- Private Data
	- Available to few people, inside some organization, generally not accessible to common masses. But sometimes they are for sale.
	- corporate
		- Maybe you need to pay for it, buy it from some organization.
		- It can include Salary of employees, attendance record, list of employees, product details, performance etc.
		- These datasets are very organized
      -  Paid datasets, There are many organization which collects and sell data on demand.
	      - They are more reliable and useful.
- Personal Data
	- very interesting and emerging field.
	- data in you or in your devices. Your call log, music and video history, shopping history etc. messages, used words, 
	- only that person has full access to this data.
	- It can include not only digital data but other data too, like habits, pen-paper journal, sleep data, food eating , everything imaginable.
	- All apps are collecting data,

## Lec 1.3 Type of datasets

3 types of data sets
- Structured
	- Where you know the schema, Structure, fields, type are defined and there is no ambiguity and uncertainty. Example table in database
	- Schema is a must
	- we know columns and also the type of values of data in columns
	- sometimes Structured data also have inter-relationship, example : one common column in many tables, which works as an element of relationship.. With help of this common column we can join all tables of whole dataset.
	- Most Spread-sheets are also an example of structured dataset. but not always.
	- Shapefiles. ( geographic data ). very structured
- Semi Structured
	- Json file, which have fields and values, but it's not necessary that they have some logic.
	- PDF file and document files.
		- these tables contain different kind of information but it's structure may be complex. it may not entirely tabular format.
	- Wikipedia page is also an example of Semi-structured dataset. A wiki page contains text and images and table. tables are structured but text part is not structured. 
	- another example is Emails and messages. on surface email looks like just a written text but on software level it have structure. structure about sender, receiver, ip address etc. but written text have no structure.
	-  Container format, Zip files, archive. these are folders. in these folders you can have one highly structured spreadsheet and one unstructured text file in a same folder. so it's semi structured.
	- 
- Unstructured
	- When we know nothing about data. e.g. photo or text.
	- Audio, video.
	- It's hard to find meaningful information from such files.
	- 


* But this datasets classification is not binary classification
* one of our main task is to extract meaningful information from unstructured data. for it we need to convert unstructured data into structured data.

## Lec 1.4 Types of Data

fields in datasets belongs to several types. we can roughly bucket them in 3 categories.
- categorical
	- Mostly text.
	- few computations, you can list them, sort them.
	- example
		- Boolean : true or false, yes or no, 0 or 1.
		- Unordered categorical : red, green, blue. just categories, you can't sequence them in anyway.
		- ordered categorical : Low, medium, high
		- cyclical sequences : days of week, months
		- Unstructured. similar to unordered but they don't have specific set of values. It can be anything.
- numerical
	- numbers, follows rules of mathematics.
	- you can apply series of operations on them
	- add, subtract, multiply etc.
	- example
		- simple numbers, integers, floats, real numbers. any mathematical numbers
- composite
	- You can perform even more operations
	- they can have special characters.
	- have multiple elements in some structure.
	- Structure is important here.
	- it may have an array. so u can apply list operations here.
	- example :
		- date / time. they have different values like date, months, year combined in one structure.
		- Spatial structure, latitude, longitute
		- Specialized data like, currency, IP address.
			- currency are just numbers but specialized with some prefix.
	- Composite can have all properties of categorical and numerical, plus a whole lot more.

## Extra :
