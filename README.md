# KQuotes

This is a package intended to gather quotes to be used with the fortune linux package

# What?
- Install the fortunes package
- clone this repo into your /usr/share/games/fortunes folder
- Create the stringfile
- Get your fortunes with the "fortune kquotes" command!
- Hack the planet!

# Initialising
Clone the repo into your /usr/share/games/fortunes folder. Then give yourself sudo rights to the .git repository with 
```sudo chown -R <username>:<username> /usr/share/games/fortunes/.git```

# Building the .dat file
After changing the quotes, build the .dat file by using the command

``` strfile -c % kquotes ```


# Tips and tricks
fortune kquotes | cowsay
