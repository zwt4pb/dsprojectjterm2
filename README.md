# dsprojectjterm2

# Sentiment Analysis of Pop Artists: Lady Gaga, The Weeknd, and Justin Bieber

## Research Question:
*How has the sentiment in Lady Gaga, The Weeknd, and Justin Bieber’s music evolved over time? Are there notable patterns across these three influential pop artists, and do these correlate with significant events in their lives?*

---

## Background Research:

We decided to explore the similarities and differences in sentiment patterns between three influential artists generally in the Pop music genre! Each group member selected an artist to analyze.  All three have heavily influenced pop music, and ultimately, we just thought it would be fun to analyze these iconic artists in the pop category.

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

## Albums and Major Events Plot
This project showcases a timeline of album releases and significant events for selected artists. The visualization was created using Plotly and exported as an interactive HTML file. This data was sourced from asking ChatGPT to compile a list of events most heavily covered in the media. 

<iframe src="https://zwt4pb.github.io/dsprojectjterm2/output_graph.html" 
        width="100%" height="600" style="border:none;"></iframe>

---

## Sentiment Analysis

- Sentiment analysis in our data is used to evaluate the emotional tone of song lyrics, scoring them on a scale of positive, neutral, and negative.
- Lyrics with ambiguous or mixed emotions are often scored as neutral (-0.05 to 0.05)
- Limitation: The sentiment analysis does not account for modifying factors, such as negations or contextual cues.

<img src="https://github.com/zwt4pb/dsprojectjterm2/raw/main/sentiment%20score%20defined.png" alt="Sentiment Score Defined" width="400">

Example: "I don't love..." would still contribute a positive sentiment to the word "love".

### Justin Bieber
The following plot illustrates the relationship between the sentiment scores of Justin Bieber's songs and their streaming numbers.
![Justin Bieber Sentiment Plot](https://raw.githubusercontent.com/zwt4pb/dsprojectjterm2/main/bieberplot.png)

### Lady Gaga
The following plot illustrates the relationship between the sentiment scores of Lady Gaga's songs and their streaming numbers.
![Lady Gaga Sentiment Plot](https://raw.githubusercontent.com/zwt4pb/dsprojectjterm2/main/gagaplot.png)

### The Weeknd
The following plot illustrates the relationship between the sentiment scores of The Weeknd's songs and their streaming numbers.
![The Weeknd Sentiment Plot](https://raw.githubusercontent.com/zwt4pb/dsprojectjterm2/main/weekndplot.png)

---

## Sentiment Analysis Over Time

### Justin Bieber
<iframe src="https://zwt4pb.github.io/dsprojectjterm2/bieber_SOT.html" 
        width="100%" height="600" style="border:none;"></iframe>

### Lady Gaga
<iframe src="https://zwt4pb.github.io/dsprojectjterm2/gaga_SOT.html" 
        width="100%" height="600" style="border:none;"></iframe>

### The Weeknd
<iframe src="https://zwt4pb.github.io/dsprojectjterm2/weeknd_SOT.html" 
        width="100%" height="600" style="border:none;"></iframe>

---

## Limitations

1. **Duplicates in the Top 100 List**  
   - Some songs appeared multiple times in the top 100 list, requiring manual removal to ensure the data was unique and accurate.

2. **Difficulties Pulling Lyrics**  
   - Retrieving lyrics from Genius was challenging due to inconsistencies in the structure of some song pages, making automated scraping unreliable for certain tracks.  
   - Some songs lacked a direct match between the API results and the desired song, leading to missing or incomplete data.

3. **API Token Expiration**  
   - The Genius API token had a short expiration period, necessitating frequent regeneration. This disrupted the data retrieval process and caused delays.

4. **Incomplete Discography Coverage**  
   - The API may not have returned all songs for some artists, particularly older or less popular tracks, resulting in gaps in the dataset.

5. **Time Constraints**  
   - Due to time limitations, the focus was on major hits and publicly available data, leaving some deeper insights unexplored.

6. **Events Data**  
   - ChatGPT was used to generate a list of the most media-covered events for the specified time periods. This approach may have introduced discrepancies or omitted certain data points.

7. **We Don't Know These Artists Personally**
---
