# Reverse-geocoder-without-api-key

## Reverse geocoding without the use of the Google API key.

This program utilises the [Google-Devsite](https://developers-dot-devsite-v2-prod.appspot.com/maps/documentation/utils/geocoder) to reverse the geocode.

Sends the request to the website and extracts the output and saves it in an Excel file.

## Prerequisites

- [Selenium Webdriver](https://chromedriver.chromium.org/downloads) (!pip install selenium)
- [pandas](https://pandas.pydata.org/) (!pip install pandas)

## Drawbacks

It has an apparent soft cap of around *100 - 115* requests per 10 ish minutes. So modify as per your own needs.
