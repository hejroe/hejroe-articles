# Dates and Times

Dates, generally considered to be very useful things, hence there being so many of them. Do please note that the phrase dates here also includes time. There are a few issues that also come pre-packed with the application of dates and time in general. This piece is possibly more of a rant with regard to the use of dates within systems. Recently this nerve was poked again, and old wounds were opened. So, to save someone perhaps a little bit of frustration here are some very simple thoughts on dates and time.
Story image for the article: Dates and Times.
Once upon a time… 

From a perspective of language, it is necessary for certain elements to exist in order for time to be recorded. Even then the level of accuracy is still potentially very varied, subjective even. The elements required are symbols that represent a change in observable state to one degree or another. Day follows night, cycles of the moon, other events that have seemingly predictable and well measured intervals. 

Over time how we have used symbols to represent time and the level of precision required has altered. For much of human history it was sufficient to just know if it was day or night. A Boolean symbol would be required to represent everything that was needed to be known about time. It was, is, or soon to be day or night. Those were the only options available and more importantly the only options necessary. 

Time did not stop with such a simplistic view. Probably due to the utility it had already offered. People became hungry for time. Other parameters were also introduced depending on the problem to be solved. When is the best time to plant crops or when is the best time to invest in NFTs both require different definitions of time. Crops will rely on a change of state of the position of Earth in relation to the Sun, that is normally measured in seasons that are based on changes that can be repeatedly observed in nature. Investing in NFTs would require being able to better measure human belief over time. 

## The edge of time… 

Time as a number has a functional limit. In other words, the size of number required to hold “all of time” is mathematically well in reach. In computational terms this would mean if we were to store a level of precision of time down to a millionth of a second all the way through to the current estimated age of the Universe we end up with a number. And that number is 4.351968e+23, or there abouts. Agreed that this is a terrible way to treat time and that it is not fit for purpose in the real World. But it does show quite well one of the fundamental issues with recording time, and that is one of size/precision. 

Numbers take up space in computing. That can cause a number of issues which almost always can be reduced to efficiency of some sort or another. If you want a very precise timing system, then there has to be a cost for it somewhere. This problem was especially important in the infancy of computing. Times and dates took up space. Space was a very limited resource, especially true of Random Access Memory. 

To resolve this issue a very pragmatic approach was taken. It was not as if all the dates ever needed had to all be recorded. We could easily get by in the main on a very reduced set. One that perhaps starts from some arbitrary point in agreed history, as an epoch of sorts. The issue with people is that we tend to not want to agree with each other a lot of the time. As evidence of this I present this [https://en.wikipedia.org/wiki/Epoch_(computing)](https://en.wikipedia.org/wiki/Epoch_(computing)) Wikipedia link. 

This has led to an ecosystem where all manner of issues can present themselves. I have not even mentioned cultural “year Zero” instances or shifting time zones. Those also greatly can increase the complexity of tracking time. Then there is also the matter of people making up their own date standards. Frequently this can happen as a spreadsheet, EDI file, CSV file or similar evolves over time with it being a training ground for analysts and programmers of all backgrounds. I will not even mention the hacks made to make for corrections in simple occurrences as leap years or bank holidays. 

## Until the end of time… 

Thankfully UTC (Coordinated Universal Time, which was obvious right?) was developed to better serve our time and date needs. The name came about as a compromise. This seems quite fitting that the whole idea of a unified time is one of compromise at a philosophical level. But more on that on another day perhaps. 

UTC should be the go-to time format for pretty much everything you are likely to encounter. There are plenty of good reasons for this. Probably the biggest one for me is that many of the tools that are used in data analytics are all optimised to use that format. It also helps prevent human errors given the logical layout of the date/time. Those two benefits alone are compelling enough to make the choice easy. Especially with high availability and low-cost memory being ubiquitous. 

## Time to break the rules… 

If you should find yourself with something that is not in at least a partial UTC format then it is prudent to change that. This goes against my normal rules of making sure that all information is carried across exactly as it was. The benefits of just having a standardised time is just too useful to ignore. When done as an initial step of a ETL pipeline you are given confidence in processing later. You always know a date/time is a date/time that you have already inspected for oddness while doing any conversion for UTC standardisation. That alone makes any additional effort more than worthwhile. 

There is possibly an exception to the handling of dates and times when they are present in large amounts and require processing. This can happen when dealing with very large time series of data. At that point it will often be necessary to think of how to better approach the time/date element of the dataset you are looking at. If you are storing a full UTC encoding for a “Year Released” field than you already have some pruning you can easily do. Frequently just trimming information to its salient components is enough to solve your analytical needs. The number of milliseconds on an invoice does not matter and there are clear rules as to what does matter. 

How you define what pruning is to take place, as well as the methods to do so, will vary depending on the environment being described in the data. Using array elements as bins to simplify collections of events is a perfectly valid approach. Just not always. 

## Time is money… 

Processing big data costs. This gets a mention as it is more common for heavy processing to be offloaded to IaaS/PaaS/SaaS vendors. This comes into consideration as if it takes just 3 hours to process the data rather than 2 days then there are considerable cost savings to be had. Cost issues are further compounded by complex bespoke data models using the latest AI/ML techniques or whatever is popular at the time. 

Efficiency often results in lower costs and/or greater capacity. This is especially true in the field of data analytics. Even the transmission, or failure to transmit, of data has costs associated to it. 

Each time I find myself solving the date/time issue, this is perhaps the fourth iteration so far, there are new tools available and a different environment. The date/time issues of today are not the same as those of 20 years ago while remaining almost exactly the same. Perhaps the real difference is in how our understanding of dates and times has changed. Or perhaps a better way to describe it is that our perspective on time has changed more. For much of history it would be unthinkable to have to think beyond a hundred years into the past or future. But with the systems that are built today consideration of such timeframes are a necessity. Unlike the pioneers of the past we are no longer constrained in quite the same way when it comes to memory space as they were. The problem they kicked down the road is one we are still dealing with, and rightly so. 
