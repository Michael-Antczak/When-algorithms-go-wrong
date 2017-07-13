# When Algorithms Go Wrong
This is a collection of stories of when something went wrong because of the problem with an algorithm. 

## 1. TripAdvisor  

> My first project at TripAdvisor was to add **new sort options** to the web page
that listed **all the hotels in a city**. It was a quick task—just enough to become
familiar with the codebase—and I was able to get it done and pushed to production
in my first week. Shortly thereafter, I was in my manager’s office for our first
one-on-one meeting, and I watched as he clicked on the hotel listings for Paris,
selected the new sort option, and waited. And waited. And waited. It took nearly
two hours for the page to load. Well, it was probably closer to two minutes, (...) 
Later that night—much later—I figured out that my fancy new code was
**making two database calls every time it compared hotels during the sorting process.
It takes on the order of n log n comparisons to sort n items, so for Paris,
which has roughly 2,000 hotels, that works out to roughly 40,000 database calls
for a single page load**. I might not have melted that day, but our database server
nearly did. [4]

## 2. [Tay (bot)](https://en.wikipedia.org/wiki/Tay_(bot))
> Microsoft had not given the bot an understanding of inappropriate behavior.(...) 
> Because these tweets mentioned its own account (@TayandYou) in the process, they appeared in the feeds of 200,000+ Twitter followers, causing annoyance to some.
      
## 3. T-shirt company called [Solid Gold Bomb](http://www.bbc.com/future/story/20150820-the-bad-things-that-happen-when-algorithms-run-online-shops)
> Fowler had set up an algorithm to upload thousands upon thousands of T-shirt designs to his online stores. The designs were based on the infamous “keep calm and carry on” catchphrase, a slogan which was originally dreamt up as a way of preserving morale in the event of a Nazi invasion of Britain. Fowler had decided to “parody” it by getting a computer programme to come up with random variations such as “keep calm and dance on” or “keep calm and play football”.
      
## 4. Google Apologizes For [Tagging Photos Of Black People As ‘Gorillas’](http://www.huffingtonpost.com/2015/07/02/google-black-people-goril_n_7717008.html)
> When Jacky Alciné checked his Google Photos app earlier this week, he noticed it labeled photos of himself and a friend, both black, as “gorillas.”  
      
   ![alt text](https://github.com/Michael-Antczak/Intro-to-computer-science/blob/master/resources/Google-tagging.png "Google tagging")

   [Google apologises for Photos app's racist blunder](http://www.bbc.co.uk/news/technology-33347866)
   

