# kukkoro-bot

「くっころ」という言葉に反応して、「くっころ」してしまうBOTのソースコードです。

# クイックスタート（herokuにデプロイする場合）

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/reverinu/kukkoro)
```
git clone https://github.com/k-nakayama-pg/kukkoro-bot.git
git remote add heroku <https://dashboard.heroku.com/apps/kukkoro-bot-2018-12-19>
heroku config:set LINE_CHANNEL_SECRET="<ca4ba6076582073819407ef141ad5978
>"
heroku config:set LINE_CHANNEL_ACCESS_TOKEN="<YCmZX+bnPWHI0gYmtThLI9Zny5FHDMl2YVJSXeglTe77iaP92bOQyIBMXsp8d0D8EaiQmYpuP5OXun9+G+bJ8IP3l3EbEkwQbf+2+DwCmkn02xs0db0iFHN7omM+oeVfkbocBmI3gIxlT536HF0eeQdB04t89/1O/w1cDnyilFU=
>"
git push heroku master
```
