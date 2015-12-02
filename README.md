# Online MNIST application using tensoflow #

- [MNIST For ML Beginners](http://tensorflow.org/tutorials/mnist/beginners/index.md)
- [Deep MNIST for Experts](http://tensorflow.org/tutorials/mnist/pros/index.md)

![screencast](https://cloud.githubusercontent.com/assets/80381/11339453/f04f885e-923c-11e5-8845-33c16978c54d.gif)

### Requirement ###

- Python 2.7
- Node >=4.0

### Setup ###

    $ pip install -r requirements.txt
    $ npm install
    $ gunicorn main:app --log-file=-


### Heroku ###

    $ heroku apps:create [NAME]
    $ heroku buildpacks:add heroku/nodejs
    $ heroku buildpacks:add heroku/python

or Heroku Button.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)
