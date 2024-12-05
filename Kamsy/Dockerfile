# Use the official Selenium standalone-chrome image as a base image
FROM selenium/standalone-chrome:latest

# Set up environment variables for proxy configuration (only if you want to handle it in the Dockerfile)
ENV HTTP_PROXY="socks5://mr65193OMCi:MnnZoJjzZs_country-us_city-houston_fast-1_stable-1_ultraset-1"
ENV HTTPS_PROXY="socks5://mr65193OMCi:MnnZoJjzZs_country-us_city-houston_fast-1_stable-1_ultraset-1"
ENV NO_PROXY="localhost,127.0.0.1"

# By default, Selenium standalone Chrome is ready to run in headless mode
