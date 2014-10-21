CentOS Installation of Python Syncro Data Tool
=============================================

### General

[Software Home Page](https://forge.ipsl.jussieu.fr/prodiguer/wiki/docs/synchro-data)

### Installation CentOS

####Automatic Installation:
Follow instruction on [Software Home Page](https://forge.ipsl.jussieu.fr/prodiguer/wiki/docs/synchro-data)

####Manual Installation

Packages Needed:
1. sqlite-devel-3.6.20-1.el6.x86_64
2. python-devel-2.6.6-52.el6.x86_64
3. libxml2-devel-2.7.6-14.el6_5.2.x86_64
4. libgpg-error-devel-1.7-4.el6.x86_64
5. libgcrypt-devel-1.4.5-11.el6_4.x86_64
6. libxslt-devel-1.1.26-2.el6_3.1.x86_64
7. openssl-1.0.1e-30.el6_5.2.x86_64
8. openssl-devel-1.0.1e-30.el6_5.2.x86_64


#### Yum Install
<code>sudo yum install python-devel
sudo yum install libxslt libxslt-devel
sudo yum install openssl-devel </code>

####Python Pagckage Installation
<code>
virtualenv synchro_data
source synchro_data/bin/activate
pip install -r requirements.txt
<code>

Download Syncro Data Package and install in python virtualenv

1. wget http://dods.ipsl.jussieu.fr/jripsl/synchro_data/synchro_data-<APPVERSION>.tar.gz
2. tar xzvf synchro_data-<APPVERSION>.tar.gz
3. cd synchro_data-<APPVERSION>
4. source $HOME/synchro_data/bin/activate
5. python setup.py install


Final adjust login and config files and setup user selections

 


