

## • How To Install and Use

`$ pkg install -y git python`

`$ git clone https://github.com/NoOneSystemIsSafe/RoughGRIP`

`$ cd RoughGRIP`

* Install requierments

`$ python3 setup.py -i`

* setup configration file ( apiID, apiHASH )

`$ python3 setup.py -c`

* To Genrate User Data

`$ python3 scraper.py`

* ( members.csv is default if you changed name use it )
* Send Bulk sms To Collected Data 

`$ python3 smsbot.py members.csv`

* add members to group

`$ python3 add2group.py members.csv`

* Update Tool

`$ python3 setup.py -u`
