# Create a QnA Bot with Azure Bot Service
This tutorial walks you through building a QnA bot with Azure Bot service on the Azure portal.

## Prerequisite
Before you build, follow the steps in **Create and publish a knowledge base** to create a QnA Maker service with questions and answers.

The bot responds to questions from the knowledge base you created, via the QnAMakerDialog.

## Create a QnA Bot
1. In the Azure portal, select ```Create new resource``` in the menu blade, and then select ```See all```.
![bot1](https://github.com/jCho23/BotWorkshop/blob/master/Resouces/Images/bot1.png)

2. In the search box, search for **Web App Bot**.
![bot2](https://github.com/jCho23/BotWorkshop/blob/master/Resouces/Images/bot2.png)

3. In the **Bot Service blade**, provide the required information, and select ```Create```. This creates and deploys the bot service with QnAMakerDialog to Azure.
* Set **App name** to your bot’s name. The name is used as the subdomain when your bot is deployed to the cloud (for example, mynotesbot.azurewebsites.net).
* Select the ```subscription, resource group, App service plan, and location```.
* Select the ```Question and Answer``` (Node.js or C#) template for the Bot template field.
* Select the confirmation checkbox for the legal notice. The terms of the legal notice are below the checkbox.
![bot3](https://github.com/jCho23/BotWorkshop/blob/master/Resouces/Images/bot3.png)

4. Confirm that the bot service has been deployed. 
* Select ```Notifications``` (the bell icon that is located along the top edge of the Azure portal). The notification will change from **Deployment started** to **Deployment succeeded**.
* After the notification changes to **Deployment succeeded**, select ```Go to resource``` on that notification.

## Chat with the Bot
Selecting ```Go to resource``` takes you to the bot's resource blade.

Once the bot is registered, click ```Test in Web Chat``` to open the Web Chat pane. Type "Hi" in Web Chat.
![bot4](https://github.com/jCho23/BotWorkshop/blob/master/Resouces/Images/bot4.png)

Notice the bot responds with "Please set QnAKnowledgebaseId and QnASubscriptionKey in App Settings. This response confirms that your QnA Bot has received the message, but there is no QnA Maker knowledge base associated with it yet. We'll do that in the next step.

## Connect your QnA Maker knowledge base to the bot
1. Open Application Settings and edit the QnAKnowledgebaseId, QnAAuthKey, and the QnAEndpointHostName fields to contain the values of your QnA Maker knowledge base.
![bot5](https://github.com/jCho23/BotWorkshop/blob/master/Resouces/Images/bot5.png)

2. Get your knowledge base ID, host url, and the endpoint key from the settings tab of your knowledge base in [qnamaker.ai](https://qnamaker.ai).
* Log in to QnA Maker
* Go to your knowledge base
* Click on the ```Settings``` tab
* **Publish** your knowledge base, if not already done so
![bot6](https://github.com/jCho23/BotWorkshop/blob/master/Resouces/Images/bot6.png)

## Test your bot! :robot:
In the Azure portal, click on ```Test in Web Chat``` to test the bot.


