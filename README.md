# Smart light - IOT project
## About
Source code for my IOT project which allows controlling light from a website. This project uses Node MCU as microcontroller and firebase real-time database as backend (NoSQL database) for data synchronisation. The light is connected to Node MCU via a relay. The website is hosted using Firebase hosting.
## Deployment
Upon every commit, a CI/CD pipeline setup on GitHub action deploys the website to the live channel on Firebase.

![CI](https://github.com/sid-r-singh/fb-hosting/workflows/CI/badge.svg?branch=main)
