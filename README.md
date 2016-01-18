<img src="https://github.com/AdvaiyaLabs/Miva-Merchant-with-Nexmo-SMS/blob/master/Docs/image1.png" width=200>


##Introduction 

Miva Merchant with Nexmo SMS app will allow Miva Merchant’s shop owners and customers to stay updated on the orders and their status via SMS. Miva Merchant is the leading provider of Enterprise-class ecommerce platforms. Over the past years, mobile has become one of the most impactful communication platforms due to its massive adoption rate. Thus, Short Messaging Service (SMS) becomes an effective communication channel to deliver business-critical information in short timeframe to respective team members. SMS empowers shop owners and their customers to stay updated with the orders that matter and allow them to proactively respond to customers. 

##Use case

1.  Send SMS notification to customers and store owners on a new order placed.

2.  Send SMS notification to update customers and store owners with changes in order status.

3.  Send SMS notification to customers and store owners on order cancelled/returned.

##Prerequisites 

-   Miva Merchant environment with admin credentials.

-   Nexmo subscription and corresponding Nexmo API keys (Keys and Secret). To access the API keys, see appendix section.

-   Internet connectivity to configure the app.

-   Customer’s and store owner’s phone number in international format. E.g: 91xxxxxxxxxx.

##Features 

-   Allows to define threshold value for the order amount. 

-   Facilitates full control over SMS functionality by enabling and disabling SMS feature on the order status changed or when a new order is placed.

##Steps to deploy the NEXMO SMS App

1.  Visit the target Git repository using the [ URL ] (https://github.com/AdvaiyaLabs/Miva-Merchant-with-Nexmo-SMS/blob/master/Package/MivaMerchantwithNexmoSMS.zip). Click on **Raw**, the app's ZIP file will be downloaded.

	<img src="https://github.com/AdvaiyaLabs/Miva-Merchant-with-Nexmo-SMS/blob/master/Docs/image3.png" width=600>

2.  Extract ZIP file and use **MivaMerchantwithNexmoSMS.mvc** as explained below.

##Steps to install Miva Merchant with Nexmo SMS app

1.  Login into Miva Merchant with admin credentials.

2.  Navigate to **Quicklinks -&gt; Modules.**

    <img src="https://github.com/AdvaiyaLabs/Miva-Merchant-with-Nexmo-SMS/blob/master/Docs/image4.png" width=600>

3.  Click (+) icon to **Add Module : **

    <img src="https://github.com/AdvaiyaLabs/Miva-Merchant-with-Nexmo-SMS/blob/master/Docs/image5.png" width=600>

4.  Select and upload **MivaMerchantwithNexmoSMS.mvc**:

    <img src="https://github.com/AdvaiyaLabs/Miva-Merchant-with-Nexmo-SMS/blob/master/Docs/image6.png" width=600>

5.  Click the **+ Add** icon to add:

	<img src="https://github.com/AdvaiyaLabs/Miva-Merchant-with-Nexmo-SMS/blob/master/Docs/image7.png" width=600>

6.  Navigate to **Menu -&gt; Order Fulfillment** :

    <img src="https://github.com/AdvaiyaLabs/Miva-Merchant-with-Nexmo-SMS/blob/master/Docs/image8.png" width=600>

7.  Install **Miva Merchant with Nexmo SMS** from **Add/Remove Modules** tab:

	<img src="https://github.com/AdvaiyaLabs/Miva-Merchant-with-Nexmo-SMS/blob/master/Docs/image9.png" width=600>

8.  Provide credentials and other details on **Nexmo Settings** tab and **Update**:

    <img src="https://github.com/AdvaiyaLabs/Miva-Merchant-with-Nexmo-SMS/blob/master/Docs/image10.png" width=600>

9.  The app is configured and the customer and store owner will receive an SMS whenever an order is placed or the order status is changed.

10.  The SMS notification is sent when the admin has selected **Enabled SMS** setting and the total amount of order placed is greater than the **Order Threshold Amount**.

11.  For customers, the SMS format for a new order placed is: “**Dear Customer, Thank you for placing Order\#&lt;order id&gt;. Your order is in &lt;order status&gt; status.**”

12.  For other status changes in any order, the SMS notifications are sent to customers in the following format:

    1.  Dear Customer, Your Order\#&lt;order id&gt; is being processed.

    2.  Dear Customer, Your Order\#&lt;order id&gt; is shipped.

    3.  Dear Customer, Your Order\#&lt;order id&gt; is partially shipped.

    4.  Dear Customer, Your Order\#&lt;order id&gt; is cancelled.

    5.  Dear Customer, Your Order\#&lt;order id&gt; is back ordered.

    6.  Dear Customer, We are processing return request for your Order\#&lt;order id&gt;.

    7.  Dear Customer, We have received the returned product your Order\#&lt;order id&gt;.

13.  For store owners, the SMS format for a new order placed is: “**A new Order\#&lt;order id&gt; for amount &lt;amount&gt; is placed with &lt;order status&gt; status.**”

14.  For other status changes in the order, SMS notifications are sent to store owners in the following format:

    1.  The Order\#&lt;order id&gt; for amount &lt;amount&gt; is being processed.

    2.  The Order\#&lt;order id&gt; for amount &lt;amount&gt; is shipped.

    3.  The Order\#&lt;order id&gt; for amount &lt;amount&gt; is partially shipped.

    4.  The Order\#&lt;order id&gt; for amount &lt;amount&gt; is cancelled.

    5.  The Order\#&lt;order id&gt; for amount &lt;amount&gt; is back ordered.

    6.  The Order\#&lt;order id&gt; for amount &lt;amount&gt; is RMA issued.

    7.  The Order\#&lt;order id&gt; for amount &lt;amount&gt; is returned.

#Appendix

##Nexmo API Keys

-   To access the Nexmo keys, go to <https://www.nexmo.com/> and sign-in.

-   On the top right corner, click on the **Api Settings**.

-   Key and Secret will display in the top bar as shown in the below image:

	<img src="https://github.com/AdvaiyaLabs/Miva-Merchant-with-Nexmo-SMS/blob/master/Docs/image11.png" width=600>
