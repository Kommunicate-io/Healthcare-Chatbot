<img src="https://s3.amazonaws.com/kommunicate.io/Header.jpg" />

# [Kommunicate ](https://www.kommunicate.io/?utm_source=github&utm_medium=readme&utm_campaign=web)Live Chat Plugin and Chatbot Integration For Web


## Overview

Healthcare chatbot is an AI-powered software application designed to interact with users in the healthcare domain. This chatbot is designed to assist users in retrieving medical information, scheduling appointments, and answering common health-related queries.


<img align="center" src="https://github.com/Kommunicate-io/Healthcare-Chatbot/assets/91717856/696953a7-fcb4-4bf8-a127-36365eb43aff" height="520" />



## Build a Healthcare Chatbot on Kommunicate and integrate it in your Website and Mobile Apps


### Step 1: Create a free Kommunicate account
Create a free account on [Kommunicate](https://dashboard.kommunicate.io/signup) and navigate to the [Bots section](https://dashboard.kommunicate.io/bots/bot-integrations). 

### Step 2: Create question and answer of the chatbot 




### Step 3: Install the chat widget on your website
You can install the Kommunicate chat widget on your website by adding a code snippet to your website. More information on how to integrate with your website [here](https://docs.kommunicate.io/docs/web-installation.html). 

> Note: Here's a [sample chatbot](https://docs.kommunicate.io/docs/bot-samples) for you to get started with Dialogflow. 


## Other Features

**Live chat widget:**  Make it easier for your visitors and users to reach you with an instant website and in-app support through chat. The widget is highly customizable. 

**Chatbots:** Automate and speed up your customer service by integrating AI-powered chatbots. Build your chatbots and deploy them using Kommunicate and seamlessly add them in the live chat.

**Conversations:** Manage all your customer queries coming from the live chat plugin. Easily manage and assign agents to cater to user conversations.

**Dashboard:** A powerful dashboard to see, analyze and act upon your customer conversation data. Helps you analyze the performance of support agents as well.

**Helpcenter:** Create your knowledge base and deploy on a dedicated page to cater to generic and recurring customer queries. Your customers will also be able to directly access FAQs in chat.

**Mailbox:** A simple and powerful team inbox for ticketing, managing, receiving and replying to all your customer support emails. 

**Integrations:** Easily move data between Kommunicate and your other favorite apps. Integrate your favorite CRM, knowledge base software and other apps.

**Conversation Routing:** Select routing rules for incoming conversations for both your agents and bots. Choose between automatic assignments or to notify all.

**Smart Rich Messaging:** Leverage rich messages using buttons, cards, carousels, forms or lists to provide an exquisite support chat experience to your customers.

**Appointment Scheduling:** Quickly respond to generic user queries using Quick Replies. Easily create and manage templated messages from your dashboard.

**Delivering prescriptions and lab test reports:** Real-time sharing and downloading of medication prescriptions and lab test reports on WhatsApp, Facebook, Instagram, Telegram, and more with Omnichannel Healthcare chatbot.

**Telemedicine:** Telemedicine bot for digital patient consultation, remote patient monitoring, and secured storage of personal data, all using a single platform made specifically for the healthcare industry.

**Reminders and Notifications:** Reduce no-shows for appointment bookings with reminders and notify patients to take medicines at prescribed hours. Keep them informed of new offers and updates.


### Example :

https://jsfiddle.net/Kommunicate/wgLuLLbu/

## Getting Started :

Create your account by [signing](https://www.kommunicate.io/?utm_source=github&utm_medium=readme&utm_campaign=web) up for Kommunicate. If you already have a Kommunicate account, log in to your account and go to [Settings -> Install](https://dashboard.kommunicate.io/settings/install) section and copy the script.

Or

You can copy the below script and replace the required parameters manually. Note: You will get your <APP_ID> in the [Install](https://dashboard.kommunicate.io/settings/install) section. 


```
<script type="text/javascript">
    (function(d, m){

    /*---------------- Kommunicate settings start ----------------*/

     var kommunicateSettings = {
      "appId": "<APP_ID>",  
      "automaticChatOpenOnNavigation": true,
      "popupWidget": true
      /*
      "onInit": function (){
        // paste your code here
      },
        "botIds":["<BOT_ID_1>","<BOT_ID_2>"]
      */
      };

    /*----------------- Kommunicate settings end ------------------*/

     var s = document.createElement("script");
      s.type = "text/javascript";
      s.async = true;
      s.src = "https://widget.kommunicate.io/v2/kommunicate.app";
      var h = document.getElementsByTagName("head")[0];
      h.appendChild(s);
      window.kommunicate = m;
      m._globals = kommunicateSettings;
    })(document, window.kommunicate || {});
</script>
```

## Technical Documentation:

Please check out the detailed [documentation](https://docs.kommunicate.io/docs/web-installation.html) for more features, implementation and customizations.
