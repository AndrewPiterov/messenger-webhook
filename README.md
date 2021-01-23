# Messanger Webhook

## Setting Up Your Webhook

<https://developers.facebook.com/docs/messenger-platform/getting-started/webhook-setup>

curl -X GET "localhost:1337/webhook?hub.verify_token=<VERIFY_TOKEN>&hub.challenge=CHALLENGE_ACCEPTED&hub.mode=subscribe"

curl -H "Content-Type: application/json" -X POST "localhost:1337/webhook" -d '{"object": "page", "entry": [{"messaging": [{"message": "TEST_MESSAGE"}]}]}'

## Tutorial

<https://developers.facebook.com/docs/messenger-platform/getting-started/quick-start>

### Message Templates

<https://developers.facebook.com/docs/messenger-platform/send-messages/templates>
### PostBack Button
<https://developers.facebook.com/docs/messenger-platform/reference/buttons/postback>
