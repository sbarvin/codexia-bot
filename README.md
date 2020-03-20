# codexia-bot

[![CircleCI](https://circleci.com/gh/iakunin/codexia-bot.svg?style=shield)](https://circleci.com/gh/iakunin/codexia-bot)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=iakunin_codexia-bot&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=iakunin_codexia-bot)
[![Maintainability](https://api.codeclimate.com/v1/badges/9cf24ce4a8463375c811/maintainability)](https://codeclimate.com/github/iakunin/codexia-bot/maintainability)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/iakunin/codexia-bot/blob/master/LICENSE)
[![Hits-of-Code](https://hitsofcode.com/github/iakunin/codexia-bot)](https://hitsofcode.com/view/github/iakunin/codexia-bot)



Bots list:

- not-found: `The repo is absent on GitHub`
- too-small: `The repo is too small (LoC is 123)`
- too-many-stars: `The repo is already too popular (5K star)`
- stars-up: `The repo gained 120 stars in 7 days`
- forks-up: `The repo was forked 40 times in 7 days`
- seen-on-hn: `The repo was seen on Hacker News (link)` 
- seen-on-reddit: `The repo was seen on Reddit (link)`



### Ideas backlog

- Codexia review
    - Code quality requirements from @yegor256
    - Integration with CI
        - CI type (CircleCI, Travis, etc.)
        - CI status on master
    - Code coverage
    - Hits Of Code metrics
    - LICENSE type
    - Programming language


- Determine topic of github-repo (games, IoT, etc.)
    - Parse description и README
    - Topics stop-list
        * games
        * internet of things (iot)


- Create microservice for determining repo's programming language
    - Analogue of https://api.codetabs.com/v1/loc?github=jolav/betazone
    - https://stackoverflow.com/a/29012789/388916
    - https://github.com/cgag/loc


- Github parser
    - Search via api (https://developer.github.com/v3/search/)
    - Parse by repo-id
        - https://developer.github.com/v3/#rate-limiting
        - https://api.github.com/repositories/149106857
        - Use proxy


- Read articles about open-source best practices
