# dsprojectjterm2

# Sentiment Analysis of Pop Artists: Lady Gaga, The Weeknd, and Justin Bieber

## Research Question:
*How has the sentiment in Lady Gaga, The Weeknd, and Justin Bieber’s music evolved over time? Are there notable patterns across these three influential pop artists, and do these correlate with significant events in their lives?*

---

## Background Research:

We decided to explore the similarities and differences in sentiment patterns between three influential artists generally in the Pop music genre!

- **Lady Gaga**: Stefani Joanne Angelina Germanotta, 38 years old, is known for her versatility in music and her image reinventions. She has strong musical influences in pop, dance-pop, and electronic genres. She gained popularity in 2008 through her debut single “Just Dance.” She has also acted in *A Star is Born*, which featured her most popular song “Shallow,” as well as *Joker: Folie à Deux,* from which albums *Harlequin* and the Joker soundtrack originated.  

- **The Weeknd**: Abel Tesfaye, 34 years old, is a Canadian-born artist known for his wide range of themes—from love to heartbreak to self-discovery—woven through R&B, Synthwave, and Pop genres. His most streamed song "Blinding Lights" was released in 2020, reaching over 4 billion streams!

- **Justin Bieber**: A 30-year-old Canadian-born artist who became strikingly popular after his debut single “One Time” in 2009. Bieber has since become a household name in pop, dance-pop, and R&B. The all-time favorite “Baby,” featuring Ludacris, was released in 2010, while his most streamed song remains as "STAY" and “Love Yourself,” an acoustic pop track with introspective lyrics.  

---

## Similar Projects:

### Reference:
**[Sentiment Analysis](https://www.kaggle.com/code/deepshah16/sentiment-analysis#Importing-Library)**  
This project analyzes the lyrical content and sentimental tendencies of various artists. It examines the relationship between unique words and total word count for each artist. The project also explores annual song release trends, creates word clouds of frequently used words, and applies sentiment analysis to determine each artist's dominant sentiment.  

### Difference:
Our project differs because we are using text files retrieved via API calls for all lyrics, rather than pre-existing CSV datasets.

---

## Data Overview:

- **Data Source**: Genius API  
- **Artists**: Lady Gaga, Justin Bieber, The Weeknd  
- **Timeframe**:  
  - Lady Gaga: 2008 - Present  
  - Justin Bieber: 2010 - Present  
  - The Weeknd: 2013 - Present  
- **Key Features**:  
  - Lyrics  
  - Release Year  
  - Artist Name  
  - Song Title  

---

## Analysis Goals:

1. **Sentiment Analysis**: Quantify polarity (positive or negative sentiments) and subjectivity of song lyrics.  
2. **Sentiment Trends**: Track changes in sentiment scores over the years for each artist.  
3. **Overlay Trends**: Correlate sentiment trends with significant personal or professional events to analyze their influence on lyrical sentiment.  

---

## “New” Techniques:

- Working with text files rather than datasets.  
- Sentiment analysis on song lyrics.  
- Creation of word clouds.  

---

## A Word Cloud of Each Artist's Most Popular Song
Through API calls to Genius.com, we were able to gather lyrics of each artist's most popular song and create a word cloud to help identify themes within the song.

### Justin Bieber's "Love Yourself"
![Bieber Popular Song](https://raw.githubusercontent.com/zwt4pb/dsprojectjterm2/main/bieber%20popular%20song.png)

Common Words: "Love," "still," "think," "cause," "baby."
Focuses on themes of self-worth and detachment in relationships.
Lyrics are conversational and introspective, balancing vulnerability and empowerment.
### Lady Gaga's "Shallow"
![Gaga Popular Song](https://raw.githubusercontent.com/zwt4pb/dsprojectjterm2/main/gaga%20popular%20song.png)

Common Words: "Ha," "shallow," "far," "times," "need."
Highlights emotional depth and longing.
The dramatic and heartfelt delivery reflects themes of self-discovery and connection.
### The Weeknd's "The Hills"
![Weeknd Popular Song](https://raw.githubusercontent.com/zwt4pb/dsprojectjterm2/main/weeknd%20popular%20song.png)

Common Words: "Fucked," "real," "love," "touch," "feel."
Lyrics are raw and explicit, emphasizing authenticity and physicality.
The explicit nature suggests a darker tone, which we can hypothesize correlates with a more negative sentiment score.

--- 

## Discography Word Clouds
For each artist's entire discography, we were able to see what words were most commonly repeated to identify overall themes within the music they are making. 

### Justin Bieber
![Bieber Combined](https://raw.githubusercontent.com/zwt4pb/dsprojectjterm2/main/bieber%20combined.png)

### Lady Gaga
![Gaga Combined](https://raw.githubusercontent.com/zwt4pb/dsprojectjterm2/main/gaga%20combined.png)


### The Weeknd
![Weeknd Combined](https://raw.githubusercontent.com/zwt4pb/dsprojectjterm2/main/weeknd%20combined.png)

Universal Themes:
All three artists heavily use words like "love" and "know," reflecting the universal appeal of relationships and emotional storytelling.
The prominence of conversational words like "oh," "yeah," and "baby" across all clouds showcases their connection to pop and R&B influences.

--- 
