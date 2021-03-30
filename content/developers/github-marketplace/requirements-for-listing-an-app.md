---
title: Requirements for listing an app
intro: 'Apps on {% data variables.product.prodname_marketplace %} must meet the requirements outlined on this page before the listing can be published.'
redirect_from:
  - /apps/adding-integrations/listing-apps-on-github-marketplace/requirements-for-listing-an-app-on-github-marketplace/
  - /apps/marketplace/listing-apps-on-github-marketplace/requirements-for-listing-an-app-on-github-marketplace/
  - /apps/marketplace/getting-started-with-github-marketplace-listings/requirements-for-listing-an-app-on-github-marketplace/
  - /apps/marketplace/creating-and-submitting-your-app-for-approval/requirements-for-listing-an-app-on-github-marketplace/
  - /apps/marketplace/getting-started/requirements-for-listing-an-app-on-github-marketplace/
  - /marketplace/getting-started/requirements-for-listing-an-app-on-github-marketplace
versions:
  free-pro-team: '*'
topics:
  - marketplace
---

<!--UI-LINK: Displayed as a link on <dependencies>
  <dependency>
    <groupId>com.example</groupId>
    <artifactId>test</artifactId>
    <version>1.0.0-SNAPSHOT</version>
  </dependency>
</dependencies>
**Note:** {% data reusables.marketplace.app-transfer-to-org-for-verification %} For information on how to transfer an app to an organization, see: "[Submitting your listing for publication](/developers/github-marketplace/submitting-your-listing-for-publication#transferring-an-app-to-an-organization-before-you-submit)."

{% endnote %}

### Billing requirements for paid apps

Your app does not need to handle payments but does need to use {% data variables.product.prodname_marketplace %} purchase events to manage new purchases, upgrades, downgrades, cancellations, and free trials. For information about how integrate these events into your app, see "[Using the {% data variables.product.prodname_marketplace %} API in your app](/developers/github-marketplace/using-the-github-marketplace-api-in-your-app)."

Using GitHub's billing API allows customers to purchase an app without leaving GitHub and to pay for the service with the payment method already attached to their {% data variables.product.product_name %} account.

- Apps must support both monthly and annual billing for paid subscriptions purchases.
- Listings may offer any combination of free and paid plans. Free plans are optional but encouraged. For more information, see "[Setting a {% data variables.product.prodname_marketplace %} listing's pricing plan](/marketplace/listing-on-github-marketplace/setting-a-github-marketplace-listing-s-pricing-plan/)."
