DWP Deployment Plan
====================
Staging Server http://104.131.164.114/
Production Server http://104.236.33.19/ 
Domain http://www.beyerbuilds.com/ (had issues with HostGator that's why it's not the production Server)

###All instructions take place in the Terminal

1. cd directory (where you're keeping your files)
2. cd local dev files

- Now you should be in your Git(Master)<br/>
- If you're happy with your local dev follow these steps <br/>

1. git add -A
2. git commit -m "detailed commit"
3. git push staging master
4. Check the staging ip address and just confirm that everythig is funtioning as you intended. (Ff everything is fine continue to step 5, if not fix in local dev and repeat steps)<br/>
5. git push production master
6. Check the production ip address and just confirm that everythig is funtioning as you intended. (If everything is then you're done and you can enjoy the fruits of you labor.)
7. If something is not working repeat all the steps until you're satisfied with the results.
