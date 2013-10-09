Simple Web UI Status for PM2 Instances.

# Installation
````bash
$ git clone https://github.com/south11235/pm2dashboard.git
$ cd pm2panel
$ npm install
$ pm2 start pm2dashboard.js -- --port 4000
````
Point your browser towards
````bash
http://localhost:4000
````
![pm2dashboard](https://github.com/south11235/pm2dashboard/raw/master/pres/dashboard-screen1.png)

# Adding a Host
````bash
Enter a fully qualified domain name along with URL scheme with the PM2 port (default port is 9615)
![pm2dashboard](https://github.com/south11235/pm2dashboard/raw/master/pres/dashboard-screen2.png)
````
