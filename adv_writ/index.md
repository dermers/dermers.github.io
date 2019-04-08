## As a Writer



### Sentiment Analysis

I downloaded my writing notebook as a text file and ran it through sentiment analysis using the following code I wrote in Python:

> import requests
>  
> file = open('notebook.txt', 'r', errors='ignore')  
> data = file.read().replace('\n', ' ').replace('â€', '').replace('œ', '').replace('™', '\'').replace('“', '')  
> file.close()  
> result = requests.post("http://text-processing.com/api/sentiment/", "text="+data).json()  
> print('Label: ' + result.get('label'))  
> print('Stats: ' + str(result.get('probability')))

The results were as follows:

> Label: neg  
> Stats: {'neg': 0.5218397698752539, 'neutral': 0.15954812138732322, 'pos': 0.478160230124746}

I was suprised to find that my writing leaned slightly negative, especially with some of the light hearted exercises we did in class.
This may, however, be attributed to the more serious topics I chose to cover with my larger pieces.  
I was also suprised at how little neutrality was found in my writing as I tried to keep a professional, academic tone for my projects.

### Project 1 (update name) - Revised

  Computer Science is a modern, technical, field focused on the use, abilities, and theory behind computational devices and processes. The field has been used to tackle issues ranging from basic calculations, to sending data simultaneously around the globe, to intelligent and flexible robots. While Computer Science is widely regarded as a relatively new, up-and-coming realm of study, the principles behind it have been around almost as long as other traditional sciences / mathematics. The abacus for example, was (albeit primitive) technically a computer. Algorithms for encrypting data have been around since Julius Ceasar when the aptly names Ceasar Cipher was used to keep military messages secret if the courier was captured. In fact, in the early 1800s Ada Lovelace wrote what is considered to be the first computer program (thus making her the first computer programmer) to run on a machine invented by Charles Babbage (The Editors of Encyclopaedia Britannica, 2019).
	
  In Computer Science, there is unique value in problem solving. Computers are great at following instructions, but just that. If one does not know how to talk to a Computer, one will not truly be able to use a computer. Problems need to be broken down both to their individual pieces and the steps needed to solve them. In doing so, computer scientists are also concerned with efficiency. Even with a correct set of steps to solve a problem, the algorithm may be useless if it cannot be solved in large / real cases in a reasonable amount of time. Some algorithms can even take longer than the inevitable heat death of the universe if given only a few thousand pieces of information to analyze (Bendanan, 2016). The more operations a computer must perform, the slower it takes (computers can only do a limited number of things at a time), so if an algorithm requires exponentially more operations per piece of input, it will take effectively forever. Because of this, Computer Science is, to put it simply, primarily concerned with solving the problem of solving problems quickly and correctly. 
	
  The writing within this field often varies widely in target audience, ranging anywhere from the casual consumer to the tech-savvy professor. Often times, Computer Scientists tend to shift their genre and style greatly to adapt to said audience groups based on their goals. When arguing for widespread adoption of a new technology, for example, it is important to appeal to a common member of the public. On the other hand, when introducing a new set of algorithms / technology and proving its effectiveness, it is important to get to the “meat” of the argument, sacrificing background information in exchange for brevity and keeping the reader’s attention. To see some of this in action, one can look at a “whitepaper” for new technologies, especially cryptocurrencies, a simple op-ed on CNN’s tech section, or even a blog post from a well-versed tech enthusiast like the piece I will be analyzing. 
	
  I have been studying Computer Science since high school but have learned most of what I know in the two years I have been at Northeastern. I am majoring in Computer Science here and have also taken an interest in Cyber Security classes / topics. As such, I am primarily concerned with solving the subset of the aforementioned problems pertaining to privacy and security issues. Data privacy has been all over the news recently, and with the increased use of both traditional computers as well as “Internet of Things” devices such as the Amazon Alexa, it is becoming more and more important that the technology we use is founded on secure and safe practices, lest our personal information become free reign for corporations, criminals, and even our friends to use against us. Many computer scientists take to the Internet to share their ideas and proposals in regard to these issues, and I have enjoyed reading a wide range of perspectives on the topic. 
	
  Last year, Bitcoin was all the rage, rising in traded value at unprecedented rates to an all time high of almost twenty thousand dollars. Getting involved just after Bitcoin buzz calmed down again, Ali Qamar attempted to convince the average crypto user to switch over from Bitcoin to Monero (Qamar, 2018). In a blog post on a tech site, Qamar was able to assume basic knowledge of cryptocurrency: most users were familiar with at least what it was, and of those, his target audience was likely already a fan of Bitcoin. Qamar is not inexperienced in his topic of choice either, having built a career around both privacy and cryptocurrency. 
	
  Qamar starts his piece, first and foremost, by enthusiastically introducing Monero. He sets the tone for the rest of his article, explaining how Monero is a relatively new coin still climbing at the same rate of Bitcoin but with additional features worth taking a look at. His excitement is contagious and encourages the viewers to read on. They are set up to carry the momentum into the bulk of his argument. Right away, Qamar hits a key point, following up from his introduction in speed by comparing Monero directly to Bitcoin. Monero, he explains, enforces untraceable transactions between users, as opposed to Bitcoin’s, which are only anonymous (Qamar, 2018). 
	
  At this point, the reader is left wondering “why” and “how” Monero is able to pull this off? After all, these are still financial transactions, and Bitcoin is still considered revolutionary despite lacking in these features. Qamar knows this and does not hesitate to clarify: Monero uses what is referred to as ring signatures to scramble the “addresses” involved in each transaction (Qamar, 2018). This means that a user’s address is harder to discern, and even if it is discovered, can’t be tracked. No information on the user’s behavior with Monero can slip through the cracks. Now that Qamar has established the credibility of his first point (Monero offers more privacy by simply hiding more information about its users), he steps up a concession – and refutation – of the most likely counter-argument. Monero may have some advantages, but Bitcoin is the most popular (and valuable) coin for a reason. Qamar admits this, Bitcoin established the entire market and Monero likely wouldn’t exist without it; however, he also argues that the primary reason for Bitcoin being able to maintain that popularity is not from quality but from ignorance (Qamar, 2018). Most people simply do not know much about alternative coins if at all.
  
  Qamar positioned himself well here. He knows that the reader is likely coming down off the original excitement he conveyed and acted to perk them back up. By focusing on ignorance as the primary reason to prefer Bitcoin over Monero, he re-captures his readers’ attention. They themselves are most likely biased towards Bitcoin and may even use it themselves. What is it that Qamar knows that they don’t? He uses this opportunity to jump into a list of reasons to prefer Monero. These are more concrete than those he’s mentioned before and are listed back to back, upping the pace. In doing so, he sets up the viewer to both absorb the reasons they are reading and to feel compelled to keep reading. 
  
  Qamar begins this list simply, re-emphasizing the security / privacy advantages of Monero. In doing so, the reader has a chance to keep up with the increased pace dragging them in. There’s no risk of information overload, despite getting right to the point. Qamar also elaborates on the non-privacy benefits of Monero’s privacy features: value. Although uncited, Qamar appeals to authority, claiming that sources show Monero is bound to raise in price even more than it already has as word of its existence spreads (Qamar, 2018). 
  
  The mention of value also provides a perfect segue into Qamar’s next point. While, this part of his article is series of short and to the point paragraphs, smooth transitions prevent a jarring tone and keep the reader from being taken out of the moment. Qamar has been tantalizing the reader with potential financial gains, and here he makes good on those hints, claiming Monero is projected to reach $1000 or more (Qamar, 2018). Although this is also uncited, the excitement this puts in the reader’s mind is undeniable, especially for crypto enthusiasts riding the high of Bitcoin’s recent rollercoaster ride of an investment strategy. 
  
  Qamar ends his series of points poignantly, referencing a financial critique Bitcoin had been struggling to deal with: high transaction fees for slow transactions. In order to effectively use cryptocurrency as a currency, “money” needs to move hands often. High transaction fees discourage users from making transactions, and the slow transaction times make it harder for Bitcoin to be used in day to day sales – people want some assurance that they will get their money. Monero, on the other hand, has significantly faster transaction times and much lower fees (Qamar, 2018). This means, cryptocurrency enthusiasts who switch to Monero can actually use it! They may even make a hefty profit while doing so. 
  
  The ending of Qamar’s post is intended as a qualifying closer. He ties up his argument in a few words: “Monero is superior” (Qamar, 2018) and adds in a simple reference to timing. He relates the reader right at the end, pointing out that this is simply how he feels, and in doing so sets up the following pressure point. Qamar points out that adoption of crypto is at its peak, and now is the time to act. A small, but almost friendly, push towards his side of things leaves the reader with a lingering feeling that maybe he is right, maybe Monero truly is the next best thing. 
  
  
  
##### Works Cited  
Bendanan, H. (2016, May 17). Polynomial time and exponential time. Retrieved from Stack Overflow: https://stackoverflow.com/questions/4317414/polynomial-time-and-exponential-time
Qamar, A. (2018, April 15). Why Monero (XMR) should be Preferred over Bitcoin (BTC). Retrieved from Global Coin Report: https://globalcoinreport.com/why-monero-xmr-should-be-preferred-over-bitcoin-btc/
The Editors of Encyclopaedia Britannica. (2019, January 3). Ada Lovelace BRITISH MATHEMATICIAN. Retrieved from Britannica: https://www.britannica.com/biography/Ada-Lovelace




### Project 2 (update name) - Revised



### todo



### todo

