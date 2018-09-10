# Bot Workshop
This workshop is designed for developers to Build, Train and Publish a simple question and answer bot based on FAQ URLs, structured documents, product manuals or editorial content.

# What is a bot?
A bot is an app that users interact with in a conversational way using text, graphics (cards), or speech. It may be a simple question and answer dialog, or a sophisticated bot that allows people to interact with services in an intelligent manner using pattern matching, state tracking and artificial intelligence techniques well-integrated with existing business services. 

# What is QnA Maker?
QnA Maker enables you to power a question and answer service from your semi-structured content like FAQ (Frequently Asked Questions) documents or URLs and product manuals. You can build a model of questions and answers that is flexible to user queries, providing responses that you'll train a bot to use in a natural, conversational way.

An easy-to-use graphical user interface enables you to create, manage, train and get your service up and running without any developer experience.
![QNA](https://github.com/jCho23/BotWorkshop/blob/master/Resouces/Images/overview.png)

## Highlights
* A complete no-code experience to create a FAQ bot.
* No more network throttling. Pay for hosting the service and not for the number of transactions. 
* Scale as per your needs. Choose the appropriate SKUs of the individual components that suit your scenario. 
* Full data compliance. The data and runtime components are deployed in the user's Azure subscription and within their compliance boundary. Read below for more details.

# Key QnA Maker processes
A QnA Maker provides two key services for your data:
* **Extraction:** Structured question-answer data is extracted from semi-structured data sources like FAQs and product manuals. This extraction is done when creating the knowledge base.
* **Matching:** Once your knowledge base has been trained and tested, you publish it. This enables an endpoint to your QnA Maker knowledge base, which you can then use in your bot or app. This endpoint accepts a user question and responds with the best question/answer match in the knowledge base, along with a confidence score for the match.

# QnA Maker Architecture
The QnA Maker stack consists of the following parts:
1. **QnA Maker management services (control plane):** The management experience for a QnA Maker knowledge base, which includes the initial creation, updating, training, and publishing. These activities can be done through the portal or the management APIs. The management services talk to the runtime component below.

2. **QnA Maker runtime (data plane):** The data and runtime are deployed in the user's Azure subscription in a region of their choosing. Customer question/answer content is stored in Azure Search, and the runtime is deployed as an App service. Optionally, you can also choose to deploy an Application Insights resource for analytics.
![Arch](https://github.com/jCho23/BotWorkshop/blob/master/Resouces/Images/architecture.png)

# Azure Bot Service
Azure Bot Service speeds up development by providing an integrated environment that’s purpose-built for bot development with the Microsoft Bot Framework connectors and BotBuilder SDKs. Developers can get started in seconds with out-of-the-box templates for scenarios including basic, form, language understanding, question and answer, and proactive bots.
![BotService](https://github.com/jCho23/BotWorkshop/blob/master/Resouces/Images/bot-service-overview.png)

# Intelligence with Cognitive Services
Give your bot some super powers. Go beyond a great conversationalist to a bot that can recognize a user in photos, moderate content, make smart recommendations, translate language and more. Cognitive Services enable your bot to see, hear, and interpret in more human ways. Bot Service leverages the Bot Builder SDK with support for .NET and Node.js. 

# Multi-Channel
Your users talk in many places, your bot should too. Azure Bot Service can be integrated across multiple channels to increase interactions and reach more customers using your website or app to email, GroupMe, Facebook Messenger, Kik, Skype, Slack, Microsoft Teams, Telegram, text/SMS, Twilio, Cortana, and Skype for Business.

