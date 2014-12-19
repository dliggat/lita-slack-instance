## README.md

Set the `SLACK_TOKEN` as a Heroku environment variable. Slack takes care of the rest.

## Deployment

    git push heroku master

## Scaling dynos

    heroku ps:scale web=1

## Logs

    heroku logs --tail

## Endpoint

    https://$SLACK_DOMAIN_ABBREVIATION-lita.herokuapp.com/lita/info
