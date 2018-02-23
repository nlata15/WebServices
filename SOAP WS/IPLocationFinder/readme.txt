Steps for generating Servide Endpoint Interfaces(SEI):
1. go to command prompt
2. create a folder and go to that folder
3. enter the below command:
	wsimport -keep -s <source_folder_name> <WSDL_URL>
	
	eg. - 
	wsimport -keep -s src http://www.webservicex.net/country.asmx?WSDL
	
	