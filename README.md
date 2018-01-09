[![Build Status](https://travis-ci.org/chupacabra007/otus-php-parenthesis-app.svg?branch=master)](https://travis-ci.org/chupacabra007/otus-php-parenthesis-app)

[OTUS](http://otus.ru) PHP course homework.

This folder contains PHP console application that can be used to check whether parentheses are balanced or not.

# Requirements

- docker

# Installation

Download [Dockerfile](https://github.com/chupacabra007/otus-php-parenthesis-app/blob/master/Dockerfile).

# Usage

$ docker build -t checker .
$ docker run checker php cli.php '()(((()()'