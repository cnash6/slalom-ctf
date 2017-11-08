# Congrats to the winners! Team DonnieScottBasil!  Solutions to all problems can be found below.  Don't check if you want to keep working! 

https://bkimminich.gitbooks.io/pwning-owasp-juice-shop/content/part2/

# Slalom CTF

Welcome to Slalom's first ever Capture The Flag competition!  Getting set up and ready to hack is easy.  We'll be hacking the [OWASP](https://www.owasp.org) Juice Shop

1) Navigate to http://ctf.slalomatlanta.com/ and create your team!  There will be one login per team, and team members will share that login, so make sure to use a password you can all remember. This website will act as our score server where you will track your completed challenges.  More on that in a minute...

2) Go to [the juice shop gihub repo](https://github.com/bkimminich/juice-shop#deploy-on-heroku-free-0month-dyno) and click "Deploy to Heroku".  If you don't have a Heroku account, setting one up is easy and won't cost you anything.  Every team member must deploy an instance of the Jucie Shop to hack against.  Once your instance is deployed, go to `Settings > Reveal Config Vars` and add a variable:

Key | Value
------------ | -------------
NODE_ENV | ctf

Open your app and you should be faced with a brand new instance of the OWASP Juice Shop! 

**WARNING:**  Once you've deployed your heroku instance, there should be no reason to visit the `bkimminich/juice-shop` repo again.  Yes, the answers to challenges can be found in the source code, and the solutions have been posted elsewhere online.  While the internet is absolutely necessary to solve these challenges, please, for the sake of the competition, refrain from searching for any solutions.   You will be expected to show how you came upon any solution to a given problem, so no cheating! 

Tools you will need to complete the challenges: 

* Chrome Dev tools or similar 
* Postman or another interceptor

And that's it! If you want to get serious with some tools Like OWASP ZAP or Kali Linux, that's up to you.  They're not necessary for this competition.  

Now that you've got your team set up and your instance of the Juice Shop running, you're ready to start hacking!  Your goal is to exploit the Juice Shop in every way possible, and you can start with challenge #1, *Finding the Score Board*. Hint: if you don't see a link for it on the page, do the simple thing and check the page source!  Finding the scoreboard should be easy, and once there you can view a list of all available challenges, as on the score server.  Every time you complete a challenge, you should receive a "challenge code".  Enter this code on the score server to see your teams score updated! The team with the most points at the end of the competition wins! 

Because this is a learning experience for all of us, there is included a companion guide to get you started on all the challenges.  See [juice-shop-sliced](https://github.com/cnash6/slalom-ctf/blob/master/juice-shop-sliced.pdf).  This is a striped down version of the official walk through guide for the Juice Shop that skips all the event setup stuff and excludes the `Appendix A: Challenge Solutions`.  Obviously the real version is easy to find, so again, please refrain from cheating and stick to this PDF when looking for hints. 

That's all there is to it!  Happy hacking and may the best team win! 


