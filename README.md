# get_mars_data
A test script framework to interface the automatic retrieval and archiving of meterological data from MARS.

This actual script is written on the BOM embery interface but this is a test. The test script will:
 - Take in either the name of a project with existing retrieval OR the specs of a new project
 - Create a data directory and log directory
 - "Interface with the MARS request bash script" - this will just be a proxy function pretending to call the script
 - Keep tabs of progress with log files
 - Check that data files have been retrieved + update an archive log
 - Convert the files to a format (netCDF)
 
 Usage: 
  - python get_mars_data --project=projectname model startdate enddate 
  
  
