<https://lucas-c.github.io/blades-in-the-dark-what-kind-of-gang-are-you/>

This is a [H5P](https://h5p.org) personality quiz for _Blades in the Dark_ TTRPG players, that aims to:
* guide players to define some aspects of their gang, with closed-ended questions
* invite players to do some world-building, with open-ended questions
* provide some visuals to build up some shared imaginary

It's based on <https://github.com/tunapanda/h5p-standalone/tree/1.3.x> for self-hosting the H5P content.

The H5P template used to build the quiz: <https://h5p.org/personality-quiz>

Contributions are welcome to:
* **add translations**: in new `workspace/bitd-gang-personality-quiz/content/content-$lang.json` files
* **add new _Blades in the Dark_ quizzes**: you can copy `workspace/bitd-gang-personality-quiz/` into another directory and then edit `content-$lang.json` directly, or else edit the `.h5p` file using a H5P editor like [Lumi](https://app.lumi.education/)

## The .h5p file

A version from January 2024 is available there: [bitd-gang-personality-quiz.h5p](https://github.com/Lucas-C/blades-in-the-dark-what-kind-of-gang-are-you/raw/main/bitd-gang-personality-quiz.h5p).

It can be rebuilt from the sources by running those commands:

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

head to `http://localhost:8080/`
