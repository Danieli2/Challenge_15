# Challenge_15


**Background**

I have been hired as a digital transformation consultant by one of the most prominent retirement plan providers in the country. They want to increase their client portfolio—especially by engaging young people. Because machine learning and NLP are disrupting finance to improve the customer experience, I decided to create a robo advisor. Both the existing and potentially new customers will be able to use this robo advisor to get investment portfolio recommendations for retirement.

**What You're Creating**

In this Challenge, I combined your new AWS skills with my existing Python superpowers to create a bot that will recommend an investment portfolio for a retirement plan.
I accomplished the following main tasks:
1. I Configured the initial robo advisor: I defined an Amazon Lex bot with a single intent that establishes a conversation about requirements to suggest an investment  portfolio for retirement.
2. Build and test the robo advisor: Make sure that your bot works and accurately responds during the conversation with the user.
3. Enhanced the robo advisor with an Amazon Lambda function: 
4. Created an Amazon Lambda function that validates the user's input and returns the investment portfolio recommendation. This includes testing the Amazon Lambda    function and integrating it with the bot.


**Instructions**

-I configured the initial robo advisor

-I built and test the robo advisor

- I enhanced the robo advisor with an Amazon Lambda function

***
**Step 1: Configure the Initial Robo Advisor**
In this section, I created the robo advisor bot and added an intent with its corresponding slots.

I used the following criteria:

<img width="734" alt="Screen Shot 2021-10-13 at 8 03 56 PM" src="https://user-images.githubusercontent.com/85910138/137243871-be9c6e4e-f0aa-4a21-ad6f-ce9ce210320f.png">

I create four slots, as the following image specifies:

<img width="1048" alt="Screen Shot 2021-10-12 at 4 57 38 PM" src="https://user-images.githubusercontent.com/85910138/137243542-04224dbc-a828-4730-aee2-822eb513587e.png">

***

**Step 2: Build and Test the Robo Advisor**


In this section, I built and tested the robo advisor. I completed the following steps:
1. I built my bot.
2. When the build finished, I tested it in the “Test bot” pane. 
3. Recorded a video or create an animated GIF of the working bot.


https://user-images.githubusercontent.com/85910138/137245168-5773ac4b-48cc-4468-8030-be5ae56f1ac4.mp4



Testing the Bot 

<img width="1346" alt="Screen Shot 2021-10-11 at 6 51 32 PM" src="https://user-images.githubusercontent.com/85910138/137244032-99c08bda-1ae3-42e4-a2d8-6bf740060da2.png">

<img width="1324" alt="Screen Shot 2021-10-11 at 6 53 53 PM" src="https://user-images.githubusercontent.com/85910138/137244044-b96388c7-b67a-4862-a4cf-92fad1f59521.png">

<img width="1311" alt="Screen Shot 2021-10-11 at 6 55 12 PM" src="https://user-images.githubusercontent.com/85910138/137244047-4e3f13ef-ebf4-40db-aa72-b6dffcef5711.png">

<img width="1310" alt="Screen Shot 2021-10-11 at 6 56 55 PM" src="https://user-images.githubusercontent.com/85910138/137244056-ab9c88ae-1539-431e-a760-8af0ae742bd4.png">


***

**Step 3: Enhance the Robo Advisor with an Amazon Lambda Function**

In this section, I created an Amazon Lambda function to validate the data that a user supplies during a conversation with the robo advisor. To do so, I completed the following steps:
I created a new Lambda function from scratch, and name it recommendPortfolio.
In the online code editor, I deleted the AWS-generated default lines of code, and then paste in the provided starter code from lambda_function.py.

I completed the recommend_portfolio function by adding the following validation rules:

<img width="596" alt="Screen Shot 2021-10-13 at 8 07 29 PM" src="https://user-images.githubusercontent.com/85910138/137244210-42f3e3f9-adcf-44db-ac1e-bce70f0f73c9.png">

<img width="522" alt="Screen Shot 2021-10-13 at 8 07 56 PM" src="https://user-images.githubusercontent.com/85910138/137244251-456a4ed7-5ad2-4d45-ab1a-2f2858a17f62.png">


I finished coding my Lambda function, I tested it by using the provided test events. Then recorded a video demonstrating the bot.


https://user-images.githubusercontent.com/85910138/137245130-e1fd5b66-a147-48ec-94c2-5382c9d69add.mp4






