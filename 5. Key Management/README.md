# Key Management
Your QnA Maker service deals with two kinds of keys, **subscription keys** and **endpoint keys**.

![km1](https://github.com/jCho23/BotWorkshop/blob/master/Resouces/Images/key-management1.png)

1. **Subscription Keys:** These keys are used to access the [QnA Maker management service APIs](https://westus.dev.cognitive.microsoft.com/docs/services/5a93fcf85b4ccd136866eb37/operations/5ac266295b4ccd1554da75ff). These APIs let you perform various CRUD operations on your knowledge base.

2. **Endpoint Keys:** These keys are used to access the knowledge base endpoint to get a response for a user question. You would typically use this endpoint in your chat bot/App code that consumes the QnA Maker service.

## Subscription Keys
You can view and reset your subscription keys from the Azure portal where you created the QnA Maker resource.

1. Go to the QnA Maker resource in the Azure portal.
![km1](https://github.com/jCho23/BotWorkshop/blob/master/Resouces/Images/km1.png)

2. Go to **Keys**.
![km2](https://github.com/jCho23/BotWorkshop/blob/master/Resouces/Images/subscription-key.png)
