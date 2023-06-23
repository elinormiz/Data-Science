1. Overview

	The data set describes a sample of users' clicks over apps collected during two months.
	
	Click-through rate (CTR) is the ratio of users who click on a specific link to the number of total
	users who view a page, email, or advertisement. It is commonly used to measure the success of an 
	online advertising campaign for a particular website as well as the effectiveness of email campaigns.
	
	As CTR is a very important metric for evaluating ad performance, click prediction systems are essential
	and widely used for sponsored search and real-time bidding.
	
	Data set Summary
	
	2,204,174 total examples.
	149,239 positive examples.
	2,054,935 negative examples.
	
	
2. Data attribute information

	op_id: operation ID (str)
	timestamp: unix time stamp (int)
	state: user's state name (str)
	user_isp: user's Internet Service Provider (str)
	app_id: application ID (str)
	app_cat: application category (str)
	banner_pos: the position of the banner (str)
	manufacturer: device manufacturer (str)
	device_model: device model (str)
	device_version: device version (int)
	device_height: device height (int)
	device_width: device width (int)
	resolution: resolution state (bool - True if defualt settings were used; False otherwise)
	clicked: click indicator (bool - True if there was a click; False otherwise)
	
