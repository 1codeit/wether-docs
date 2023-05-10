# The Backend

Some things to note

* Core Web App = The website at https://hnz.li
* Desktop = The brand new piece of the "stack" that makes the site a windows app

What are the core parts of the Core Web App?

1. Azure
2. Azure Web Apps
3. Azure Key Vault
4. Amazon S3 (The HuskyNZ CDN Backend)
5. Amazon Cloudfront (The HuskyNZ CDN Fronted)
6. Python
7. Flask
8. VS-Code
9. Github
10. Github Actions
11. OpenWeather API
12. HTML&#x20;
13. CSS
14. GIT

What are the core parts of the Desktop app?

1. Elctron
2. HuskyNZ Wether Core Web App
3. HTML
4. CSS
5. Chromium
6. VS-Code
7. Advanced installer
8. Git

Now on the technical bits

When I make a change that I want to push to the Azure web app I need to run 3 commands in my termanail git add filename then git commit -m "" then git push these commands with sync my github repo with my local copy of the repo&#x20;

After that GitHub Actions take over when the Action sees there is a new commit on thw master branch it will build the app then deploy it to the azure web app you can see the github actions logs for more evedince of the way it works

After that It displays on the website https://w.hnz.li and also updates in the desktop app

How doses the Desktop app work?

The desktop uses a frame work called [Electron ](https://www.electronjs.org/)as there website states its a Chromium based framework and it uses Node.js and allows you to make desktop apps useing web tech. The installer is made by useing a app called Avanced install because wile Electron has the option to make installers its not as fetchure rich and avanced install allows me to make installers the deploy more than one app in the futer and do updates.





