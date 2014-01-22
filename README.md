meteor-bootstrap3-sass-test
===========================

Meteor site for testing the [bootstrap3-sass](https://github.com/reywood/meteor-bootstrap3-sass) meteorite package

---------------------------------------

To clone and set up for the first time:

```sh
$ git clone https://github.com/reywood/meteor-bootstrap3-sass-test.git
$ cd meteor-bootstrap3-sass-test
$ git submodule update --init --recursive packages/bootstrap3-sass
$ cd packages/bootstrap3-sass
$ git checkout -b develop --track origin/develop
```

To simply run the app and see if everything looks kosher:

```sh
$ mrt
```

To run package tests, execute:

```sh
$ mrt test-packages bootstrap3-sass
```

Then browse to <http://localhost:3000/>.
