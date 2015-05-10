hubot-backlog-slack
===================

forked by [webhookとHubotを使ってBacklogをslack対応させる - Hacking My Way ～ itogのhack日記](http://d.hatena.ne.jp/itog/20150226/1424939686)

Require
-------

### Environments

~~~ bash

heroku config:set HUBOT_HEROKU_KEEPALIVE_URL=http://your_herokuapp_name.herokuapp.com --app your-herokuapp-name
heroku config:set HUBOT_SLACK_TOKEN=your_slack_token --app your_herokuapp_name
heroku config:set BACKLOG_URL=https://your-backlog.backlog.jp --app your_herokuapp_name

~~~

### Addons

~~~ bash

heroku addons:create redistogo:nano

~~~
