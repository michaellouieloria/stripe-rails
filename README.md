Stripe Rails
============

Billing Subscription in Rails using Stripe

Based from [Railscasts](http://railscasts.com/) episode [Billing with Stripe](http://railscasts.com/episodes/288-billing-with-stripe)

1.  Create [Stripe plans](https://manage.stripe.com/test/plans) based from db seeds

        id: 1
        name: "Never Been Kissed"
        monthly: 5

        id: 2
        name: "Can't Get Enough"
        monthly: 12

        id: 3
        name: "Pure Bliss"
        monthly: 49

        id: 4
        name: "I'm in Heaven"
        monthly: 99

2. Enter secret and publishable key in [config\initializers\stripe.rb](https://github.com/michaellouieloria/stripe-rails/blob/master/config/initializers/stripe.rb)
