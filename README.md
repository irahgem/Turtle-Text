# Turtle-Text
# ![turtletext](https://firebasestorage.googleapis.com/v0/b/react-firechat-ae4bf.appspot.com/o/icons8-turtle-48.png?alt=media&token=3ad49069-a9ad-436c-aecc-920fe816909d) Turtle-Text

[![ReactJS](https://img.shields.io/static/v1?label=builtwith&message=ReactJS&color=purple)]()
[![npm](https://img.shields.io/static/v1?label=npm&message=8.11.0&color=red)]()
[![yarn](https://img.shields.io/static/v1?label=yarn&message=1.22.19&color=blue)]() 
[![chakra ui](https://img.shields.io/static/v1?label=chakraui&message=2.2.3&color=orange)]()

## Inspiration
With the rise of digital media and ever increasing publication, who has the time to see videos , read complete news items, documents, books, to determine whether they are beneficial or not?

## Abstract

One of the challenges in natural language processing and understanding is text generation that could be applied for example in text summarization. Actually, it involves understanding the information a text conveys and summarizing it into a brief summary that incorporates the essential, relevant information. Numerous investigations are carried out in this field to create extractive summaries based on frequentist methodology. Automatic summarization has emerged as a crucial technique for quickly and efficiently discovering important information in massive amounts of text," according to research . The advent of vast volumes of textual data is driving up demand for automatic summarization technologies . In the midst of the day-to-day hustle, it can be challenging to watch videos for prolonged periods of time and understand their information, therefore it would be beneficial if we could pull out the key points of the video. People can use this to quickly summarise the contents of both blogs and videos within seconds.

## Novelty

Users can quickly summarize their blogs and videos on our centralized platform, which we offer. In order for them to quickly eloborate texts, we additionally provide text eloborator. The product's availability as a browser extension, which allows users to complete all actions with a single click, makes it stand distinct.

## What it does

For summarization we will be using deep learning model and NLP techniques to process the text . We will be using transformers to train state-of-the-art of pretained models. Transformers can be used in text , image , audio classification and processing. Summarization creates a shorter version of a document or an article that captures all the important information. Along with translation, it is another example of a task that can be formulated as a sequence-to-sequence task.

**User Authentication :** Auth0 was used which helped to provide an efficient user authentication with various features.

![image](https://user-images.githubusercontent.com/72067722/222942690-45fb221e-3603-4f7c-b9c1-bea57502ec1a.png)

![image](https://user-images.githubusercontent.com/72067722/222942702-138030f6-3a14-408e-9e68-32d1eb6cbc18.png)

**Summarize video :** Enter the video url in the input field which you want to summarize . The video will be processed by the NLP model and will send the summarized text as response .

*WebApplication*

**BrowserExtension**

![image](https://user-images.githubusercontent.com/72067722/222942729-31a02394-6459-4cd6-bc96-b0335d6dd73c.png)

![image](https://user-images.githubusercontent.com/72067722/222942746-3c139f9c-4ae1-4706-b0b2-29475905721c.png)

**Summarize blogs :** Put the url of the blog you wish to summarise in the input area. The NLP model will analyse the blog and delivers the text-summarized in response.

*WebApplication*

**BrowserExtension**

![image](https://user-images.githubusercontent.com/72067722/222942762-6c520687-0cde-4d36-849a-aa0af94e9da2.png)

To generate text we will be using GPT2 model which helps to generate large texts .GPT2 (Generative Pre-trained Transformer ) is a state-of-the-art machine learning architecture for Natural Language Processing (NLP).

**Eloborate texts :** Enter a short passage of text that you are familiar with, and our model will analyse it and produce a detailed summary.

*WebApplication*

**BrowserExtension**

![image](https://user-images.githubusercontent.com/72067722/222942796-795b9829-8787-4863-ad3d-0d9639998aa2.png)

**Share :** We have implemented share your content feature using twilio api. It provided us to share our content at ease to any person all around the world with just a mobile number.

![WhatsApp Image 2023-03-05 at 11 44 11 AM](https://user-images.githubusercontent.com/72067722/222948399-4d9ca560-8781-4dbd-b371-5ebb1e0be8c2.jpeg)

## How we built it

NLP and Deep learning approaches can be used to execute operations on text, and they offer improved consistency. We used 'Auth0' to implement user authentication. Users can input links to their blogs or videos, which our deep learning model will then process and output a text summary of. For processing our text, we use the DistilBERT deep learning model, which was trained on a very large corpus of unlabeled text, including the entirety of Wikipedia (2,500 million words) and the Book Corpus (800 million words). Also, users can input text documents that can be summarised. Furthermore we provide a text eloborating feature where users can input a small text which will be eloborated to large texts. Working with GPT-2 (Generative Pre-trained Transformer) models that were trained using the WebText data set will help us achieve this. We'll offer multiple interfaces, including a web application, a mobile app, and a browser extension, so customers can easily complete their desired actions with a single click.

## Challenges we ran into

- Working with the pretrained NLP models made it harder. 
- One of the astetic parts was creating API to handle queries.
- Using Chakra UI to design a web interface was intriguing.
- It was challenging to create extensions using NodeJS.

## Accomplishments that we're proud of

- Utilization of pretrained models
- Built a web application and a chrome extension using Python to provide an API.
- Using Twilio to share our content world wide
- Implementing User Authentication at ease with help of Auth0.

## What we learned

- Acquired knowledge of NLP models and approaches.
- Gained knowledge about transformers.
- Acquired knowledge about Chakra UI's frontend.
- Acquired knowledge about FastAPI for building APIs.
- Acquired knowledge about NodeJs browser extension development.
- Learnt to use Auth0 for implementing user authentication.
- Learnt to use Twilio for sharing contents using message.

## What's next for Turtle Text

- Creating a mobile app using Flutter to make it easy for people to access in mobile interface .
- Improving the model's performance . 
- Adding additional features such as audio summarization and gesture summarization .
