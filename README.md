# Reverse-geocoder-without-api-key

## Reverse geocoding without the use of the Google API key.

This program utilises the [Google-Devsite](https://developers-dot-devsite-v2-prod.appspot.com/maps/documentation/utils/geocoder) to reverse the geocode.

Sends the request to the website and extracts the output and saves it in an Excel file.

## Prerequisites

- [Python](https://www.python.org/)
- [Selenium Webdriver](https://chromedriver.chromium.org/downloads) ```!pip install selenium```
- [pandas](https://pandas.pydata.org/) ```!pip install pandas```

## How to run

- Go through **Prerequisites** and install all the necessary items required.
- Download the program.
- Place the *file_name.xlsx* file, the *chrome webdriver* and *the program* in a new folder.
- Rename the place holder column names and file name in the program to the required specification.
- Run the program.
- Open the *Output.xlsx*
- Profit

## How it works

- The program reads the excel file and converts it into a dataframe.
- The program launches chrome webdriver and navigates to [Google-Devsite](https://developers-dot-devsite-v2-prod.appspot.com/maps/documentation/utils/geocoder).
- The geocode is input into the search field and the output is saved in another dataframe.
- The program loops until all the geocodes are entered one by one and the output is obtained.
- The output is then exported as an excel file.


## Drawbacks

It has an apparent soft cap of around *100 - 115* requests per 10 ish minutes. So modify as per your own needs.
