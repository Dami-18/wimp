![Compatibility](https://img.shields.io/badge/compatible%20with-python2.7x-blue.svg)
# WIMP - Where Is My Prof?

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
![Screenshot](https://github.com/themousepotato/wimp/blob/master/static/screenshot.png)

Alwin is a wimpy kid. What? Is he lazy? Not at all! He always asks me, 'Where is my Prof?'. He is in search of his project and sick of waiting for hours in front of his Prof's office. Boom! He got an idea. He started to search the Prof's timetable and decided to meet him after his class. He went to ERP. Wow! What a beautiful place it is! He found the Prof's department and checked department time table, found out his slots, compared his slots with time and finally, he met him. But, alas! He was late. The Prof gave his project to another stud. Alwin asked him, 'Bro, how did you find him earlier?'. He replied, 'Use WIMP kid!'.

## Development
### Host machine

```
$ git clone https://github.com/themousepotato/wimp.git
$ cd wimp
$ sudo pip2 install -r requirements.txt
$ python2.7 main.py # To populate data
$ python2.7 app.py # Locate your browser to the local address
```

### Docker container

```
$ git clone https://github.com/themousepotato/wimp.git
$ cd wimp
$ docker build -t wimp .
$ docker run -p 8888:5000 wimp
```

### Pretty printing `data.json`

You can use any JSON utility that is installed on your computer.
[`jq`](https://stedolan.github.io/jq/) is recommended.

```sh
$ jq '' data/data.json > data/data2.json
$ mv data/data2.json data/data.json
```

## Wiki
We've a list of FAQ [here](https://github.com/metakgp/wimp/wiki/FAQ). If you've any queries, find the answer from there. If your question is not there, add it by yourself. We would love to answer.

## Contributions

PRs are most welcome!

[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html)


## Maintainer

[Navaneeth Suresh](https://github.com/themousepotato) (@themousepotato on [metakgp Slack](https://slack.metakgp.org).)

