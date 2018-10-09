# Lisk Auto-Toggler

A script that checks the forging status of your node and enables it if required. Appends a new log entry each time it is run. 

Only compatible with Lisk Core 1.0 and up.

If you find my tools useful, please consider voting for my delegate `lemii` or donating to `5222060513855166167L`. Thanks!

## Installation & configuration
```
git clone https://github.com/Lemii/lisk-autotoggler
cd lisk-autotoggler
pip install -r requirements.txt
```

Open script and enter your public key and password.

## Usage
#### Create a Cron Job
```
crontab -e
```
Add line (run script every minute):

```
* * * * * /usr/bin/python [path to lisk-autotoggler.py here]
```

#### ..or run the .py script manually:
$ python lisk-autotoggler.py

## License
Licensed under the [MIT license](https://github.com/Lemii/lisk-autotoggler/blob/master/LICENSE)
