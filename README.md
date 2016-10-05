# Portfolio-Site
This is Werner Chao's Portfolio Site where it show cases all of the projects he has done.

## Table of Contents
- Quick Start
- What's Included
- Creators
- References
- Copyright and License

## Quick Start

To start using this repository

>  ```> $ git clone https://github.com/wernerchao/Portfolio-Site.git```

For a [demo] of the website (https://portfolio-site-6e87d.firebaseapp.com)

## What's Included

Within the download you'll find the following directories and files:

```
├── public/
├── .firebaserc
├── database.rules.json
├── firebase.json
└── README.md
```

The firebase files are used to host on firebase. Please do not edit any firebase related files.

The main file to look at is:

```
/public/index.html
```

Where Werner Chao's projects are presented. You will also find a snippet of code near the end for Firebase configuration. 
Please do not edit that part as well. It looks like this:

```
    <script src="https://www.gstatic.com/firebasejs/3.4.1/firebase.js"></script>
    <script>
    // Initialize Firebase
    var config = {
        apiKey: "AIzaSyBV3VOVzXjzJrnVxtazostum2alcTtHdJg",
        authDomain: "portfolio-site-6e87d.firebaseapp.com",
        databaseURL: "https://portfolio-site-6e87d.firebaseio.com",
        storageBucket: "",
        messagingSenderId: "87593566719"
    };
    firebase.initializeApp(config);
    </script>
```

## Creators

**Werner Chao**

- <https://github.com/wernerchao>

## Copyright and License

Code and documentation copyright 2016 Portfolio Site
Authors and released under the MIT license.

