<h1>IGStoryDL-Automated</h1>

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) [![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

<h3>What is this repo about?</h3>
<p>This is a simple script written in python to automate downloading stroies from Instagram. This will send you the downloaded files via a Telegram Bot<p>

<h3>How to deploy?</h3>

1) Fork this repo.
2) Edit bot.py <br>
   `token` : Bot token from the @BotFather. <br>
   `chat_id` : Your telegram chat ID. <br>
   `user_ids` : User ID of the Instagram profiles you want to download stories. <br>
   `src_dir` : Download directory. <br>
   `USER` : Your Instagram username. <br>
   `PASSWORD` : Your Instagram password <br>
3) Click deploy

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/NandiyaLive/IGStoryDL-Automated)

4) Get your Heroku app URL.
5) Create an account on [cron-job.org](https://cron-job.org)
5) Create a new cronjob<br>
   `Address` : {your-heroku-app-name}.herokuapp.com<br>
   `Schedule` : Add the time you want to send the request to download stories

<br>
© Neranjana Prasad 2020.
