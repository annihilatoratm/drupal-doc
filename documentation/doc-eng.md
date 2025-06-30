# PaynetEasy Payment Plugin for OsCommerce 4

# 1. [Plugin Download and Installation](https://github.com/annihilatoratm/drupal-doc/blob/main/documentation/doc-eng.md#plugin-download-and-installation-1)
# 2. [Plugin Configuration](https://github.com/annihilatoratm/drupal-doc/blob/main/documentation/doc-eng.md#plugin-configuration-flow-1)
# 3. [Payment Processing](https://github.com/annihilatoratm/drupal-doc/blob/main/documentation/doc-eng.md#payment-flow-1)

## 1. Plugin Download and Installation

1.1. Download the Plugin. Download the **Payneteasy** plugin repository and copy its contents to the following directory: site_directory/modules.  
1.2. Access Plugin List. Click the _Extend_ button in the admin menu to open the list of available plugins.  
     
<img src="/images/drupal-download-1.png" width=60% height=60%>
  
1.3. Install the Plugin. Locate **Payneteasy Payment** in the list and click the _Install_ button.  

<img src="/images/drupal-download-2.png" width=60% height=60%>
<img src="/images/drupal-download-3.png" width=60% height=60%>

## 2. Plugin Configuration
2.1. Clear System Caches (Prerequisite). Navigate to:  
  * Configuration → Performance.
Click Clear all caches to ensure the system recognizes the newly added plugin.

  <img src="/images/drupal-1-1-1.png" width=60% height=60%>
  <img src="/images/drupal 1-4-2.png" width=60% height=60%>
  <img src="/images/drupal-1-4-3.png" width=60% height=60%>

2.2. Add a Payment Gateway. Go to:  
  * Commerce → Configuration → Payment Gateways.
  Click **Add payment gateway** to begin the setup process.

<img src="/images/drupal-1-1.png" width=60% height=60%>
<img src="/images/drupal-1-2.png" width=60% height=60%>
<img src="/images/drupal-1-3.png" width=60% height=60%>
<img src="/images/drupal-1-4-1.png" width=60% height=60%>
  
2.3. Configure Payment Gateway. Once the **Payneteasy** plugin is installed, two payment options will be available:  
  * Paynet direct method – for direct on-site payments.  
  * Paynet form method – for off-site (redirect) form-based payments.

<img src="/images/drupal-1-4.png" width=60% height=60%>
<img src="/images/drupal-1-5.png" width=60% height=60%>
<img src="/images/drupal-1-6.png" width=60% height=60%>

# 3. Payment Processing

3.1. Select a Product. On the homepage, browse and select a product category. After choosing a product, click **Add to Cart**. A pop-up will confirm the addition and provide a link to **Your Cart**.

<img src="/images/drupal-1.png" width=60% height=60%>
<img src="/images/drupal-2.png" width=60% height=60%>
  
3.2. Proceed to Checkout. Click the Checkout button to begin the checkout process.

<img src="/images/drupal-3.png" width=60% height=60%>

3.3.  Choose Payment Method. On the **Order Information** page, scroll to the **Payment Method** section and select **PsynetEasyForm** form as your gateway. Click Continue to Review, then on the Review page, click _Pay_ and _Complete Purchase_.

<img src="/images/drupal-4.png" width=60% height=60%>
<img src="/images/drupal-5.png" width=60% height=60%>

3.4. Complete the Payment. Fill in all required fields in the payment form and click _Process Payment_ to finalize the transaction.

<img src="/images/drupal-6.png" width=60% height=60%>
