0x04. Files manager
===================

Back-end JavaScript ES6 NoSQL MongoDB Redis NodeJS ExpressJS Kue

-   By: Guillaume, CTO at Holberton School
-   Weight: 1


This project is a summary of this back-end trimester: authentication, NodeJS, MongoDB, Redis, pagination and background processing.

The objective is to build a simple platform to upload and view files:

-   User authentication via a token
-   List all files
-   Upload a new file
-   Change permission of a file
-   View a file
-   Generate thumbnails for images

You will be guided step by step for building it, but you have some freedoms of implementation, split in more files etc... (`utils` folder will be your friend)

Of course, this kind of service already exists in the real life - it's a learning purpose to assemble each piece and build a full product.

Enjoy!

Resources
---------

**Read or watch**:

-   [Node JS getting started](https://alx-intranet.hbtn.io/rltoken/kZHDWCu20EsKxKzi51yWeg "Node JS getting started")
-   [Process API doc](https://alx-intranet.hbtn.io/rltoken/uYPplj2cPK8pcP0LtV6RuA "Process API doc")
-   [Express getting started](https://alx-intranet.hbtn.io/rltoken/SujfeWKCWmUMomfETjETEg "Express getting started")
-   [Mocha documentation](https://alx-intranet.hbtn.io/rltoken/FzEwplmoZiyGvkgKllZNJw "Mocha documentation")
-   [Nodemon documentation](https://alx-intranet.hbtn.io/rltoken/pdNNTX0OLugbhxvP3sLgOw "Nodemon documentation")
-   [MongoDB](https://alx-intranet.hbtn.io/rltoken/g1x7y_3GskzVAJBTXcSjmA "MongoDB")
-   [Bull](https://alx-intranet.hbtn.io/rltoken/NkHBpGrxnd0sK_fDPMbihg "Bull")
-   [Image thumbnail](https://alx-intranet.hbtn.io/rltoken/KX6cck2nyLpQOTDMLcwxLg "Image thumbnail")
-   [Mime-Types](https://alx-intranet.hbtn.io/rltoken/j9B0Kc-4HDKLUe88ShbOjQ "Mime-Types")
-   [Redis](https://alx-intranet.hbtn.io/rltoken/nqwKRszO8Tkj_ZWW1EFwGw "Redis")

Learning Objectives
-------------------

At the end of this project, you are expected to be able to [explain to anyone](https://alx-intranet.hbtn.io/rltoken/88vbnogJmkEoxqu-6wAXEw "explain to anyone"), **without the help of Google**:

-   how to create an API with Express
-   how to authenticate a user
-   how to store data in MongoDB
-   how to store temporary data in Redis
-   how to setup and use a background worker

Requirements
------------

-   Allowed editors: `vi`, `vim`, `emacs`, `Visual Studio Code`
-   All your files will be interpreted/compiled on Ubuntu 18.04 LTS using `node` (version 12.x.x)
-   All your files should end with a new line
-   A `README.md` file, at the root of the folder of the project, is mandatory
-   Your code should use the `js` extension
-   Your code will be verified against lint using ESLint
