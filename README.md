Astrolytes.com built with Harp.js
=================================


## Getting started

1) Install Harp and Surge on your computer

```
$ sudo npm install -g harp
$ sudo npm install -g surge
```

2) Clone this repository
```
$ git clone git@github.com:Astrolytes/astrolytes.com.git
```

3) Start Harp server from within the `_harp` directory
```
$ npm start
```

4) Visit [http://localhost:9000/](http://localhost:9000/) to see the local version of the site.

> Tip: Comas and quotes are important when writing JSON. Follow the same structure as the sample data to avoid syntax issues.

## Publishing & Deploying

To publish the site, first compile your changes:

```
$ npm run compile
```

Next, you'll push the site to [Surge.sh](http://surge.sh) – to do this, run:

```
$ surge www
```

You'll get something like:

```

    Surge - surge.sh

              email: isaac@ike.io
              token: *****************
       project path: www
               size: 26 files, 851.8 KB
             domain: astrolytes.com
             upload: [====================] 100%, eta: 0.0s
   propagate on CDN: [====================] 100%
               plan: Free
              users: isaac@ike.io
         IP Address: 45.55.110.124

    Success! Project is published and running at astrolytes.com

```
