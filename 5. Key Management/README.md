# Key Management
Your QnA Maker service deals with two kinds of keys, **subscription keys** and **endpoint keys**.

![km1](https://github.com/jCho23/BotWorkshop/blob/master/Resouces/Images/key-management1.png)

1. **Subscription Keys:** These keys are used to access the [QnA Maker management service APIs](https://westus.dev.cognitive.microsoft.com/docs/services/5a93fcf85b4ccd136866eb37/operations/5ac266295b4ccd1554da75ff). These APIs let you perform various CRUD operations on your knowledge base.

2. **Endpoint Keys:** These keys are used to access the knowledge base endpoint to get a response for a user question. You would typically use this endpoint in your chat bot/App code that consumes the QnA Maker service.
