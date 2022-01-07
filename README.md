# cdc-vaccination-scraped
A small tutorial on how to scrape and automate live vaccination data from [CDC](https://covid.cdc.gov/covid-data-tracker/#datatracker-home).   
Project inspired by [Simon Willison](https://simonwillison.net/2021/Mar/5/git-scraping/).

# Set up
1. Fork this repo.  
2. `git rm cdc_vaccination_data.json` to remove the already pushed data.
3. Commit your code.
4. See [.github/workflows/cdc_data_scraped.yml](/.github/workflows/cdc_data_scraped.yml) and modify the cron to what suits your purpose. 
5. Commit and push and Horra, you are done.

# Resources:
- To generate a cron expression, refer to [this amazing](https://crontab.cronhub.io/) online tool.
- If you are new to YAML, I recommend [cloudbees](https://www.cloudbees.com/blog/yaml-tutorial-everything-you-need-get-started) and [tutorialspoint](https://www.tutorialspoint.com/yaml/index.htm) tutorials to get you started. 
