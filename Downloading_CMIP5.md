Downloading CMIP5 Output from Earth System Grid Federation
=============================================

### Getting Started

Follow instructions on [PCMDI Portal](http://cmip-pcmdi.llnl.gov/cmip5/data_getting_started.html)

### Downloading CMIP5 Files
Follow instructions on [ESGF Page](
climatedata: /opt/synchro_data/user_selections

#### Edit 'default.txt'

* projects=”CMIP5"
* models=”all"
* experiments=”historical rcp26 rcp45 rcp60 rcp85”
* ensembles=”all”
* variables[*][mon]=”tas pr”
* variables[*][day]=”tas pr”



#### Download
* all commands must be run from bin directory ◦cd /opt/synchro_data/bin 
* display models ◦./start.sh -i 
* update models list ◦./start.sh -e 
* display models again ◦./start.sh -i 
* search for files ◦./start.sh -a 
* start the download ◦./start.sh -b 
* stop the download ◦./stop.sh 
* downloaded files location ◦$HOME/synchro_data/data 


#### View selections in SQLite
* See:  /opt/synchro_data/db
* Copy synchro_data.db onto local computer
* Open in Firefox - Tools/SQLite Manager
* once the program completed, we have the following in $HOME/synchro_data





#### Derek Openid:  
https://pcmdi9.llnl.gov/esgf-idp/openid/DHRosendahl
