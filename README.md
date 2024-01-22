<https://lucas-c.github.io/blades-in-the-dark-what-kind-of-gang-are-you/demo/>

This is a [H5P](https://h5p.org) personality quiz for _Blades in the Dark_ TTRPG players, that aims to:
* guide players to define some aspects of their gang, with closed-ended questions
* invite players to do some world-building, with open-ended questions
* provide some visuals to build up some shared imaginary

It's based on <https://github.com/tunapanda/h5p-standalone/tree/1.3.x>

H5P template used: <https://h5p.org/personality-quiz>

## Generate a .h5p file

    cd workspace/bitd-gang-personality-quiz/
    zip -r ../../bitd-gang-personality-quiz.h5p .

## Run It (Gulp)

### Prerequisites
yarn (https://yarnpkg.com/lang/en/) is used as package management tool. Install yarn before proceeding.


To install dependencies:
```
yarn install
```

Unzip `.h5p` file into `workspace` directory

```
yarn start
```

## Run It (Other)

Unzip `.h5p` file into `workspace` directory

Run a simple http server e.g. `python -m SimpleHttpServer`

head to `http://localhost:8080/demo/`
