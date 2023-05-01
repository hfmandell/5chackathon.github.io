# 5CHack.com
A website host for the 5C Hackathon occuring April 14-15, 2023! See us live at [5CHack.com](https://www.5chack.com/). Reach out to 5chackathon@gmail.com with ay questions, comments, ideas!

Our site is running on a a t3.medium AWS server, maintained by [Jack Terwillinger](https://github.com/jterwilliger30). We configured Nginx with a proxy server to redirect specific hostname requests to a folder containing the static site files. We also have HTTPS encryption certificate via [certbot](https://certbot.eff.org/). 

We use auto-deployment to the server via GitHub Actions. 
