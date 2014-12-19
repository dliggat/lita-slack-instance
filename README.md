## README.md

Set the `SLACK_TOKEN` as a Heroku environment variable - available once you configure `lita` in Slack Services. Deploy, and everything else should just work.

### Initializing with Heroku

Inside the [forked] repo, do: `heroku create`

### Deployment

    git push heroku master

### Scaling dynos

    heroku ps:scale web=1

### Logs

    heroku logs --tail

### Endpoint

    https://$SLACK_DOMAIN_ABBREVIATION-lita.herokuapp.com/lita/info
