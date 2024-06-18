# To start a local webhook.
stripe listen --events checkout.session.completed --forward-to localhost:3000/api/payment/webhook