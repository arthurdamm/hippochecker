# The Hippochecker
### Access the Holberton School checker directly from the command line
### Quick Start
1. Install [Python 3](https://www.python.org/downloads/)
2. Install [Selenium for Python](https://selenium-python.readthedocs.io/)
3. Install [Chrome](https://www.google.com/chrome/)
4. Install [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/downloads) and add it to the PATH
5. Add your intranet email and password to config.py
6. Create an alias so the program can be accessed from other directories e.g. `alias hippochecker='/your/file/path/hippochecker/hippochecker.py'` 
### Usage

`$ hippochecker <project> <problem(s)>`

where `<project>` is the project number e.g. 272, 229, etc.
and `problem(s)` are separated by commas (4,1,5) or a single hyphen (0-10) or "all".

##### Examples:
`$ hippochecker 272 4,1,5`

`$ hippochecker 229 0-10`

`$ hippochecker 229 all`
    
    
### Options
Options can be turned on or off in config.py.

Turn on `headless` to run the headless version of Chrome (i.e. no browser window open).

-  I recommend turning this off during setup/troubleshooting or if you turn `results_in_terminal` off.

Turn on `results_in_terminal` to get results reported in the terminal.

Increase `max_wait_time` if a timeout has occurred or the checker delay has started.



### Known Issues
- [ ] Projects with manual reviews preceding checks will throw off reported results. 


### Author
[Josef Goodyear](https://github.com/JosefGoodyear)

### Contributors

