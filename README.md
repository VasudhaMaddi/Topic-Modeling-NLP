## Data Collection
The dataset has been collected from kaggle.com .The JSON file contains a collection of news articles related to various technology topics. Each article in the JSON file has several fields such as "title", "content", "published_date", "author", "source", and "link".
- **title:** The title of the article.
- **content:** The content or main body of the article.
- **published_date:** The date when the article was published (in the format YYYYMMDD).
- **author:** The author or authors of the article.
- **source:** The source or publication where the article was originally published.
- **link:** The URL link to the original article.

## Information Extraction
The relevant information is extracted from each news article, including the title, publication date, author, and content. The text data is then cleaned and preprocessed to enhance its quality for further analysis.

### Extraction Process:
- **Title:** The title of each news article is extracted to provide a concise summary of its content
- **Publication Date:** The publication date indicates when the article was published and is crucial for understanding its temporal context
- **Author:** The author's name is extracted to attribute the article's content to its creator
- **Content:** The main body of the article, which contains the detailed information and analysis, is extracted for further processing.
### Text Preprocessing:
- **Stopwords Removal:** Commonly occurring words such as "the," "is," and "and" are removed from the text data as they do not carry significant meaning for analysis
- **Punctuation Removal:** Punctuation marks such as commas, periods, and exclamation marks are removed to ensure uniformity and consistency in the text
- **Stemming or Lemmatization:** Words are reduced to their base or root form using stemming or lemmatization techniques. This step helps in reducing word variations and standardizing the text for analysis.
The extraction and preprocessing steps ensure that the text data is clean, standardized, and ready for further analysis, such as topic modeling or sentiment analysis.



# LDA Topic Analysis Results

## Optimal Number of Topics
The optimal number of topics determined by the Latent Dirichlet Allocation (LDA) model is 7.

## Topics and Their Main Themes

### Topic 0
- **Main Themes:** new, also, via, system, release, feature, detail, year, improvement, developer
- **Insights:** This topic suggests discussions related to new features, system improvements, and developer-related updates.

### Topic 1
- **Main Themes:** ubuntu, kernel, release, code, also, new, system, change, work, wayland
- **Insights:** Discussions in this topic include developments in Ubuntu, kernel updates, and changes in system functionality, with a focus on Wayland.

### Topic 2
- **Main Themes:** driver, amd, code, performance, nan, graphic, intel, kernel, new, also
- **Insights:** This topic revolves around graphics driver development, performance optimization, and updates for AMD and Intel graphics.

### Topic 3
- **Main Themes:** release, fedora, gnome, change, improvement, new, via, work, developer, llvm
- **Insights:** Discussions in this topic involve releases, changes, and improvements in Fedora, GNOME, and LLVM, with a focus on developer-related updates.

### Topic 4
- **Main Themes:** driver, mesa, release, vulkan, opengl, new, also, graphic, amd, radeon
- **Insights:** This topic highlights discussions related to Mesa, graphics drivers, and updates for Vulkan and OpenGL, with a focus on AMD Radeon.

### Topic 5
- **Main Themes:** driver, opensource, also, kernel, game, new, hardware, graphic, work, code
- **Insights:** Discussions in this topic cover open-source driver development, kernel updates, gaming-related topics, and hardware advancements.

## Distribution of Articles Among Topics
The histogram below visualizes the distribution of articles among the identified topics. The x-axis represents the topics, and the y-axis represents the number of documents.
![histogram](https://github.com/VasudhaMaddi/nlp/assets/88607955/65e04f07-dd6e-485d-b9c3-72b2fcf5d625)


## Word Clouds for Each Topic
Word clouds have been generated for each topic to provide a visual representation of the most prominent words.

### Topic 0
![image](https://github.com/VasudhaMaddi/nlp/assets/88607955/a4be54d8-890e-4f41-be28-35546605976b)

### Topic 1
![image](https://github.com/VasudhaMaddi/nlp/assets/88607955/cbd04ee5-d8f2-47c7-8095-c4ef605f6d14)

### Topic 2
![image](https://github.com/VasudhaMaddi/nlp/assets/88607955/f8dbd8ce-4813-4bfc-b848-b5a636306dcd)

### Topic 3
![image](https://github.com/VasudhaMaddi/nlp/assets/88607955/1e798d84-01eb-449a-a9b6-578cfa3c75d1)

### Topic 4
![image](https://github.com/VasudhaMaddi/nlp/assets/88607955/582ef0ee-ab77-4fe7-841d-9bb360ed72ad)

### Topic 5
![image](https://github.com/VasudhaMaddi/nlp/assets/88607955/92fee8f3-9af2-446c-8ab2-5cd8e4c71461)

