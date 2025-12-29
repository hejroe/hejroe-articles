# Large Language Models are a Mirror
 
With the UK government calling for a [Pro Innovation Approach to AI Regulation](https://www.gov.uk/government/publications/ai-regulation-a-pro-innovation-approach) and technology leaders calling for a ["Pause Giant AI Experiments: An Open Letter"](https://futureoflife.org/open-letter/pause-giant-ai-experiments/), I thought it would be useful to give a primer of sorts. It is necessary first to understand my motivations in this matter. As contrary as it may seem to some, your success is my success.

With the UK government calling for a Pro Innovation Approach to AI Regulation and technology leaders calling for a "Pause Giant AI Experiments: An Open Letter", I thought it would be useful to give a primer of sorts. 

It is necessary first to understand my motivations in this matter. As contrary as it may seem to some, your success is my success. If you are doing well in life then there is a greater probability that I will also be doing better. As much as some humans like to "own all the things" that is in reality quite hard to do. Even if that is the case it is only fleeting when compared to the whole history of humanity. So if I have easy access to food, water, clean air, space, time, security and all the other things someone may aspire to then any surplus is something that I am able to at least consider offering to others. There is variance as to how much someone is willing to let go of. But generally, most people will happily share, even when times are hard. In fact, I would go so far to say that some of the most generous people and communities I have ever met are the ones with the least resources. Anyone who has studied child development can also attest to sharing as being a fundamental part of our humanity. Hopefully my motivation in the rest of this piece is abundantly clear, it is one of self-interest, my families interest, society and humanity as a whole. I am being selfish. 

## What is LLM, NLP, Chat-GPT? 

The buzz around Chat-GPT has been immense, and rightly so. With the fastest uptake of 100 million users yet seen there has to be a good reason for its success. But what is Chat-GPT made of and how do such technologies work? The following is a very simplistic view of how the technology works and there are some excellent resources that give far greater depth available by whatever media format suits you best. A simple search will provide huge lists, even courses on how to build your own version of Chat-GPT. If you have any interest in this field I would urge you to go and investigate more as it is simply fascinating stuff. 

Let's first start with the GPT bit. This stands for Generative Pre-trained Transformer. The clue as to what it does is in the name. Just as with the predictive spelling functions on your phone or word processor it will try to anticipate the word you want to type and provide you with a quick way to autofill the entire conversation. The differences are more to do with the scale of prediction being made. The phone is only trying to predict the word you are spelling and uses the letters already inputted as a prompt for what it suggests next. The GPT models take this concept much further. They try to predict the text that corresponds with a whole sentence, paragraph and more.  

Both of these methods have commonalities with each other. The prediction of the word being typed into a phone only uses the current letters as a prompt. The source of its predictions can be as simple as a list of words. So you search for "w" and "e" you will only get a selection of words that start with "we". Now this could be "weekend", "welcome" or a host of other choices. This is where the more complex predictive text solutions come into play. They actually have some awareness of the words used prior to the word currently being typed. So if you were talking about a social event a good prediction would be that "weekend" is the word being sought after and not "welcome".  

Now imagine a super version of this functionality and you are likely starting to imagine a thing called a Large Language Model (LLM). Chat-GPT is simply one version of an LLM and there are many others. In fact, many of the leading technology companies either have their own version or are working on making their own. Meta, formerly Facebook, have LLaMA for instance. Google has Pathways Language Model (PaLM) that uses 540 billion parameters. These are but a couple, but the weight of the names involved should tell you that it is something being backed by many major players in the IT landscape.  

To explain a little more what a LLM is and what parameters mean is going to be useful. Imagine you have every book ever published at your disposal. Now think about feeding all of those books into "something" that builds relationships between all the words (tokens/parameters) entered. This would mean that you can end up with a tool that can use probability to predict the next piece of text. Now what if you were to ask this tool to predict a large amount of text back? Say you provide it with the first part of a conversation and to let it predict what the rest of the conversation would be. In essence this is that LLMs do. 

If this seems a little fanciful then consider for a moment the types of conversations you may have on a regular basis. You may fill your car at the petrol station and the human interactions you have can seem scripted. An exchange of information is made but there are similarities for almost every time the transaction is made. Although you have likely not really considered it too much there is a framework for the transaction that follows a path. If you were to take all the conversations you have ever had when getting petrol you could likely discern a pattern of sorts. Now if you added this to everyone else's petrol typed conversations you could have even greater confidence in what was likely to be said next at any point in the transaction.  

An LLM does not record every single conversation and use a lookup method. It takes each conversation and then associates a token to each word. AI techniques are then used to process each conversation and to generate a neural network model. When you then ask the generated model to predict the next word in the conversation it will do so based on the input it has already received. This entire process is probabilistic. The output given is based on the probability of words occurring based on the initial input and nothing else. 

To confirm this, I asked "Bard" from Google a simple question:  

Q - If I was to ask you a complex question what is the probability that you would repeat exactly an answer you had already given?  

A1 - The probability of me repeating exactly an answer I have already given to a complex question is low. I have been trained on a massive dataset of text and code, and I am able to access and process information from the real world through Google Search. This means that I am able to generate new and unique answers to even the most complex questions. However, there is always a chance that I may repeat an answer if I have been asked a similar question before. This is because I am still under development, and I am not always able to distinguish between two questions that are slightly different. If you are concerned about me repeating an answer, please feel free to rephrase your question or provide more context. I will do my best to understand your question and provide a unique and informative answer.

A2 - The probability that I would repeat exactly an answer I had already given to a complex question is very low. I am trained on a massive dataset of text and code, which means that I have access to a vast amount of information. When I am asked a question, I use this information to generate a response that is both informative and comprehensive. I also try to avoid repeating myself, as I want to provide my users with fresh and original content. However, there is always a chance that I may repeat an answer if I am asked the same question multiple times in a short period of time. This is because I am still under development, and I am not always able to remember all of the information that I have been trained on. If you are concerned about me repeating myself, please feel free to ask me to rephrase my answer or to provide additional information.

A3 - The probability of me repeating exactly an answer I had already given to a complex question is very low. I am trained on a massive dataset of text and code, and I am able to access and process information from the real world through Google Search. This means that I am able to generate new and unique answers to your questions, even if they are complex or challenging. However, there is always a chance that I may repeat an answer if I have been asked the same question before. This is because I am still under development, and I am always learning new things. If I am asked a question that I have not been asked before, I may not be able to generate a new answer. In this case, I may repeat an answer that I have given to a similar question in the past. I am always working to improve my ability to generate new and unique answers, and I hope that one day I will be able to answer any question you ask me, no matter how complex or challenging it may be.

In this example I used "Bard" as they generate several responses at a time. If I was to prompt "Bard" to answer the same question in a new session it would again give very similar but different answers. Over time it is possible that other features of the LLM rules being used may refine an answer to something that is more consistent. But at least for now it would seem that "Bard" agrees with the premise I have made. I suspect that other LLM models provide similar results, but I think I have pushed this bit of humour as far as I can for now. 

## So what does this all mean? 

The really big thing being missed or played down at this time about Large Language Models is that they are fundamentally imperfect. Now as much as some are positing this as an incredible threat to humanity it ignores completely the fact that this is no different from human knowledge also being imperfect. Then there is the probabilistic dimension that also needs to be included into this. Just because a word or series or words are considered to be probable in the response formed by an LLM does not mean that it is correct. In fact, depending on the training data used to create your LLM it could return all sorts of nonsensical rubbish. 

LLMs are created by taking existing information and processing that with some specific implementation that then generates a model. So, what if your training data is sourced only from Reddit? Or perhaps from some other internet forum that has a more unusual audience? Again, when considering the probabilistic element of this we can even see what some are describing as "hallucinations". This is a bit of a misnomer in my mind. These "hallucinations" are when the LLM returns a result that you know is incorrect, but it insists is correct. There is some concern that humans will become convinced by the generated hallucinations given the assuredness that the LLMs often seem to have. 

The interesting thing about the "hallucinations" is that in another sense they could be seen as a form of "creativity". Again, this would be wrong in a strict sense, but a human could easily be convinced to disagree. If you asked a LLM to write a poem that is quite abstract about how rock feels in the desert it would give you a response. But the LLM does not know anything about the desert, rocks or anything else aside from the prompts it has been given. It only knows the probability of one word following another. 

There was no way I could resist using "write a short abstract poem about how a rock feels in the desert" as a writing prompt, so here are the results from Bard: 

Version 1 

The Rock 

I am a rock, 
I stand alone, 
I am strong, 
I am tall, 
I am proud, 
I am silent, 
I am still, 
I am eternal, 
I am the desert, 
I am the world, 
I am everything, 
I am nothing. 

Version 2 

The Rock 

I am a rock, 
I am solid and strong. 
I am rooted in the earth, 
I am a part of the land. 
I have seen the sun rise and set, 
I have felt the wind blow through my hair. 
I have seen the rain fall, 
I have seen the snow melt. 
I have been here for a long time, 
I will be here for a long time to come. 
I am a rock, 
I am a part of the desert. 

Version 3 

The Rock 

I am a rock, 
A solid mass of stone. 
I am rooted to the earth, 
Unmoved by the wind and rain. 
I am a witness to time, 
Seeing the rise and fall of civilizations. 
I am a reminder of the power of nature, 
Unyielding in the face of adversity. 
I am a rock, 
A symbol of strength and endurance. 
I am a part of the earth, 
And I will be here long after you are gone. 

You may find the results laughable, or you may be reminded of a 70s prog-rock album. The thing is it kind of looks convincing even with the obvious flaws. If you add a little belief to the mix, it is very easy to see how us humans can be convinced that there is something intelligent/creative within the LLMs. Note that I did not need to add any copyright notice, the rest of that is a discussion for another day. 

## The Most Interesting of Times 

If you have read some of the other pieces on this site, then you may already have seen that there are indeed oddities that the Universe creates. I have touched upon some of the easier ones to write about. Conway's Game of Life is one I have written about that alludes to emergent behaviour from very simplistic rules. This is perhaps where LLMs get a bit more interesting. LLMs hint at something else happening. Something very interesting that seems to be coupled very closely to at least one core part of what we consider to be intelligence. A singular definition of intelligence still eludes me, although I did work out a way to establish if one system was more intelligent than another, but again that is for another day. LLMs consist of a body of knowledge. At this time the public facing versions are mainly limited to text, but there is no reason why it needs to be for text alone. It can include music and art, after all the phrase "a picture paints a thousand words" is most certainly a truism. There is something quite wonderful being exposed with LLMs and for the life of me I cannot explain exactly what it is. It is something I will undoubtedly give more thought too when I can. 

What does concern me though is the current implementations of LLMs. You see the companies that are funding the larger models at this time are not doing so with altruistic motives. They are often required by law to seek profitability and that means that somehow the tools created need to be monetized. How this may be expressed is yet to be seen. Will LLMs be used as a vehicle for advertising or for control of perception of the very World we live in? I find it hard to think that this will not be the case and am reminded of the AI Toaster from Red Dwarf. Imagine a human asking, “What will make me happy?” and for the toaster to simply reply “A heated bread product.”. 

## A New Hope 

But with this concern there is also a certain amount of hopefulness that this blooming of LLM technology will create a paradigm shift in human behaviour that is ultimately beneficial to us all as a species and as individuals. This comes from seeing some LLMs being reduced to a size that can run on hardware available to a general consumer. No need for a supercomputer to take advantage of LLM technology which means creating your own LLM is more than viable. You could even select the sources of information that you want as opposed to using sources selected by someone else. 

This could mean that we have an opportunity to develop our own personal LLMs that can assist us with things using data we have specifically selected. This by no means makes them, or our perceived knowledge, perfect. But it does offer us a platform by which we can discern the world in a more independent way. 

## Wrapping Up 

I have already written far more than I was expecting to with this short essay. But it is very hard not to write about something so interesting as all the activity happening in the Natural Language Processing (NLP) space. In time I am sure I will write more on this subject, and I hope to be able to express myself to you in more precise terms. 

At the start of this piece, I spoke of at least three entities; the UK Government, technology companies and myself. The reason in doing so is simply to try and convey the immediate complexity that presents itself when talking about controlling any form of emergent technology. That is namely, what are the interests being catered for? The following is a remarkably simplistic view that I hope simply demonstrates this potential for a conflict of interests a little better.  

Goal alignment is a constant consideration for those who work in the field of Artificial Intelligence. One of the hardest elements of this is to work out what the goals actually are and who they belong to. Are the goals of an individual, family, community, government and species all aligned? Is it even possible for them to even ever be aligned? With the opposing statements from the UK Government and some industry leaders it would seem that there is some way to go in aligning the respective goals of at least some. 

I can be confident in stating that NLP, LLMs and GPT typed technologies are going to force us to accelerate our thinking. This is no bad thing, but it is important to understand that the results being offered by language programs at this time is very much a reflection of existing human knowledge in all of its forms. This includes the good, the bad and everything in between. There is still much to be learnt, but I think that the final quote in this article is probably apt: 

"The greatest enemy of knowledge is not ignorance. It is the illusion of knowledge." 

- Stephen Hawking
