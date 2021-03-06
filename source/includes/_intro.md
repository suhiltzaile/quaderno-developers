# Introduction

Quaderno is a set of APIs to automate and improve tax management in businesses of all sizes. Here are some resources that will help you understand the basics of all of them.

The documentation is organized into three major areas:

- **Quaderno.js** is a javascript library that allows you to calculate sales taxes in your own checkout form.
- **Quaderno Checkout** is a checkout form that you can use on your site to sell products and subscriptions.
- **Quaderno Billing** is a small plugin that you can use on your site to let your customers access their receipts and edit their billing data.
- **Quaderno API** is our billing and tax API that you can use to calculate taxes and manage receipts from your backend.

**Not a developer?**

A custom Quaderno integration requires you to either be or hire a developer. But you can use Quaderno through any number of [third-parties plugins and libraries](https://quaderno.io/integrations/) built by our community, such as for Shopify, Amazon FBA, and WooCommerce.

**Need more help?**

Just [send us an email](mailto:support@quaderno.io). We’re always happy to help out with code or any other questions you might have. 

## The Sandbox

The Quaderno Sandbox mirrors the features found on the Quaderno Production servers and let you to test our API and/or connect your trial accounts from other services like Stripe, PayPal, Braintree, etc.

The Sandbox has parity with the Quaderno main feature set supported by the live environment. This means you can test your Quaderno processes and know they will behave the same on the production servers as they do in the Sandbox environment.

**Your credentials for the Production environment does not work on the Sandbox.** You need to [create a new account](https://sandbox-quadernoapp.com/signup).

By using your Sandbox account, you can test and debug your application without referencing any real Quaderno users or their live Quaderno accounts. The Sandbox lets you operate your application in a safe environment and provides you a way to fine tune your Quaderno routines before moving your product into production.

We’re always happy to help out with code or any other questions you might have. Please [drop us a line](mailto:support@quaderno.io).

<aside class="warning">
Please keep in mind that while you test all the API methods and plugins against the sandbox it has some limitations most notably:
<ul>
<li>Emails are delivered to the account email rather than to the specified recipient. </li>
<li>There's a global 50 documents cap. If you need to create more you'll have to remove some of your previous documents.</li>
<li>VAT numbers are not validated.</li>
</ul>
</aside>
