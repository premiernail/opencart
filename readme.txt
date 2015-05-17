---------------------------
First Data Connect Module
Version 1.0.6
Written by Hailstorm Commerce
---------------------------

Demo:		firstdata.dev2.hailstormcommerce.com

Features:
v1.0
	- Ability to enable/disable payment module
	- Ability to edit front end payment gateway text displayed to customer
	- Ability to switch between live/test mode payment gateways
	- Ability to select payment mode (payonly, fullpay, payplus)
	- Ability to specify and enable/disable URL overrides
	- Ability to select supported cards
	- Ability to customise the status of an order based on transaction result
	- Ability to restrict the geozone to which this gateway will be available
	- Ability to set the default transaction timezone
	- Ability to view transaction logs  

Upcoming features:

	
License:


Installation:
-Extract the firstdataConnectModule.zip
-Using an FTP program upload the admin and catalog directories to your site.
-There should not be any file conflict warning messages.
-To enable the plugin please login to the admin portal
-Navigate to the Extensions -> Payment section, within which show be a link to install the firstdata Connect Module. To install please click the install link.
-To configure please click the edit link.
-Configure the module as desired.

Compatibility
- supports opencart v1.5.x
- fully working and tested on 1.5.3.1 and 1.5.5.1
- module only includes English language
- non-english users can edit the translation file located at "admin/language/english/payment/firsdataconnect.php" and "catalog/language//english/payment/firsdataconnect.php"

Version history:
2013.30.08 	- 	1.0 	- 	initial release
2013.10.02	-	1.0.1 	-	removed requested cards
2013.10.23	-	1.0.3	-	Issue with success/ Failure URLS
2013.11.13	-	1.0.4	-	Issue with custom db prefixes
2013.11.14	-	1.0.5,6	-	Fixes relating to timezones, 
2013.11.20	-	1.0.7	-	Fixes relating to timezones, 
2014.01.31	- 	1.0.8	-	Fixes error messages being displayed, and blank error if fail_reason is not populated. (e.g. Declined Card)