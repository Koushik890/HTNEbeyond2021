# Browser Disguise

## Inspiration

Sometimes, the people whom we live with have no sense of privacy. Especially now with quarantine, we cannot even enjoy the deepest and darkest corners of the internet without the fear of someone else barging in. That’s why we came up with Browser Disguise. Through the usage of AI, as soon as the computer detects someone walking into your room, a website of your choice will pop up and block anything that you were previously browsing. You can choose from a variety of possibilities such as a randomized Wikipedia article or a specific link of your choice.


## How we built it

After being granted access to the user’s webcam, the hack starts taking pictures continuously and predicts whether or not there is a person behind the user: returning a number between 0 and 1, 0 meaning there is no one behind the user and 1 meaning that there is a person. We achieved this by adopting code from Google’s Teachable Machine which simplified the entire process. We each manually made a dataset to feed and teach this machine. Using this API, we were able to take pictures, predict, and even display a webcam preview on our website. Overall, we programmed the code by using HTML, CSS and JavaScript.



Group project at Hackathon: Hack the Northeast: Beyond(https://www.hackthenortheast.com/)

Date: 1/15/2021 - 1/17/2021

Product name: Browser Disguise

Devpost: https://devpost.com/software/browser-disguise

Presentation video: https://youtu.be/Mg4vGwsZvPg
