## As a Writer



### Sentiment Analysis

I downloaded my writing notebook as a text file and ran it through sentiment analysis using the following code I wrote in Python:

> import requests
>  
> file = open('notebook.txt', 'r', errors='ignore')
>
> data = file.read().replace('\n', ' ').replace('â€', '').replace('œ', '').replace('™', '\'').replace('“', '')
>
> file.close()
>
> result = requests.post("http://text-processing.com/api/sentiment/", "text="+data).json()
>
> print('Label: ' + result.get('label'))
>
> print('Stats: ' + str(result.get('probability')))

The results were as follows:

> Label: neg
>
> Stats: {'neg': 0.5218397698752539, 'neutral': 0.15954812138732322, 'pos': 0.478160230124746}

I was suprised to find that my writing leaned slightly negative, especially with some of the light hearted exercises we did in class.
This may, however, be attributed to the more serious topics I chose to cover with my larger pieces.

### Project 1 (update name) - Revised



### Project 2 (update name) - Revised



### todo



### todo

