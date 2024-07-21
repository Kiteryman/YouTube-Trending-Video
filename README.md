# YouTube Trending Video Analysis
## Problem Statement
This project aims to identify and analyze the key attributes that contribute to making YouTube videos trend in the Hong Kong region. The trending video lists for Hong Kong from February 10, 2024, to March 31, 2024, are used.

## Research Objectives
1. Analyze Trending Attributes:
  - To explore and identify the critical parameters that influence a video’s likelihood of appearing on YouTube's trending list.
2. Utilize Data Science Techniques:
  - To apply data science measures such as exploratory data analysis (EDA) and machine learning for examining the data extracted from the YouTube API.
3. Understand Cultural Preferences:
  - To investigate the unique cultural and linguistic preferences of Hong Kong viewers by analyzing the attributes of trending videos, including language usage, tags, and video categories.

## Results
### Category
#### Most Trending Video Category
<img width="850" alt="image" src="https://github.com/user-attachments/assets/4079c3e0-d21b-41c4-90da-c89578009dc7">

#### Average Days to Trend Across Categories
<img width="841" alt="image" src="https://github.com/user-attachments/assets/ddc1f367-6c25-413c-a408-4a720234ed32">

#### Language Distribution Among Different Categories
<img width="867" alt="image" src="https://github.com/user-attachments/assets/7e5d6f25-5789-4f92-91fc-1b5617ed05b4">

- Importance of Category Selection: Selecting the right category is crucial for video visibility and engagement.
  
- Popular Categories in Hong Kong: The categories People & Blogs, Entertainment, and News & Politics are the most popular among viewers in Hong Kong.
  
- Trend Timing: Videos in the popular categories typically take about 20 days to feature on the trending list, indicating gradual popularity build-up.
  
- Language Preferences: There is a dominant preference for Chinese language in trending videos, particularly in the News & Politics and People & Blogs categories.
  
- Strategic Alignment: Aligning video content with local language preferences boosts viewership and increases the likelihood of trending status.

### Title
#### Language Distribution for Titles of Trending Videos
<img width="541" alt="image" src="https://github.com/user-attachments/assets/2ff35989-ea2a-4ccd-9c27-c031538891fe">

#### Language Distribution for Titles Against Average View
<img width="594" alt="image" src="https://github.com/user-attachments/assets/24bedd74-f556-4943-ad4a-6771e022b0a1">

#### Attributes in The Title of Trending Video
<img width="541" alt="image" src="https://github.com/user-attachments/assets/733d3838-ecb1-41cd-8346-49cd154fb57a">

#### Attributes in The Title Plot Against Average View Count
<img width="631" alt="image" src="https://github.com/user-attachments/assets/e0e711db-b61b-406e-a262-818f9c252172">
<img width="629" alt="image" src="https://github.com/user-attachments/assets/0f21c1b0-5a20-4400-8394-d0a7326fdedf">
<img width="633" alt="image" src="https://github.com/user-attachments/assets/53748b0d-34ad-430c-bee5-b1393e07d588">

- Importance of Titles: Titles capture viewers' attention and significantly enhance a video's visibility and likelihood of trending.
  
- Language Preference: Approximately 70% of trending videos in Hong Kong use Chinese characters in their titles, indicating a local preference for the Chinese language.

- Bilingual Titles: Only about 20% of videos feature bilingual titles, showing that this approach has little impact on differentiating trending from non-trending videos.

- Rare Non-Chinese/English Titles: Titles in languages other than Chinese and English are exceedingly rare, reflecting the audience's focus on these two languages.

- Higher Average Views for English Titles: Videos with titles exclusively in English attract a much higher average view count than those with Chinese titles, likely due to their broader global appeal.

- Title Content Elements: Over 75% of trending videos include at least one of three elements: hashtags, numbers, and emojis, with emojis having a more significant effect on enhancing views.

### Tags
#### Percentage of Video With or Without Tags
<img width="536" alt="image" src="https://github.com/user-attachments/assets/18d19ecd-788b-43e4-b734-c45b3f266715">

#### Percentage Distribution of Video Against Number of Tags
<img width="567" alt="image" src="https://github.com/user-attachments/assets/940c9c5e-bc96-4fc6-8db9-6e682895aeb6">

#### Distribution of Number of Tags Video Against Average View Count
<img width="624" alt="image" src="https://github.com/user-attachments/assets/6a5d3d1e-9c2e-46d8-ad53-05531b248a02">

#### Top 5 Most Popular Tags with Categories’ Names
<img width="970" alt="image" src="https://github.com/user-attachments/assets/1db391cb-a6e8-4f68-832e-e7c2771c8037">

#### Language Distribution of Tags in Trending Videos
<img width="539" alt="image" src="https://github.com/user-attachments/assets/0b7c2d0f-800e-4e77-8efb-cd502467a46d">

- Importance of Tags: Tags are crucial in influencing the YouTube algorithm and significantly impact a video’s likelihood of being recommended.

- Tag Usage: Approximately 80% of videos utilize tags, with the majority including between 2 and 30 tags.

- Optimal Number of Tags: The optimal number of tags ranges from 20 to 30.

- Popular Tags: The five most popular tags are "hilarious," "shorts," "funny," "daily," and "amusement," which are generally positive or neutral.

- Linguistic Analysis of Tags: Most trending videos integrate tags in both Chinese and English, with over 50% of tags in Chinese, aligning with the preferences of the Hong Kong audience.

### Duration
#### Percentage Distribution of Shorts and Video
<img width="566" alt="image" src="https://github.com/user-attachments/assets/54eba70d-d99b-4231-b1a3-3fefc7fc4e86">

#### Percentage Distribution of Shorts Length
<img width="556" alt="image" src="https://github.com/user-attachments/assets/5f3a3456-710e-45db-82e8-c6f4030a412b">

#### Percentage Distribution of Video Length
<img width="586" alt="image" src="https://github.com/user-attachments/assets/461af4b4-13d8-4df3-873e-84812a577a4a">

#### Video Types Plot Against Average View, Like and Comment Count
<img width="589" alt="image" src="https://github.com/user-attachments/assets/6443049b-1e50-4606-ba6a-72b9d6cfba88">
<img width="580" alt="image" src="https://github.com/user-attachments/assets/f0c7ba08-0cb2-4a77-900d-03046f4ce368">
<img width="548" alt="image" src="https://github.com/user-attachments/assets/85c4a807-e87b-4f0e-9061-38a124a6a74c">

- Distribution of Shorts and Videos: The distribution between shorts and videos on the Hong Kong trending leaderboard is approximately 50:50.

- Duration of Trending Shorts: 1-minute long trending shorts has the highest portion.

- Duration of Trending Videos: Most trending videos are between 1 to 25 minutes long, with many exceeding 30 minutes or even an hour.

- View and Engagement Metrics: Shorts have significantly higher views and likes on average compared to videos, while videos have more comments.

- Promotion and Viewing Preferences: Shorts may be promoted more by YouTube since they are recently introduced, or audience viewing preferences differ, as viewers can watch many more shorts per hour compared to videos.

- Engagement Differences: It is easier for shorts to gain views and likes due to their length, while videos receive more comments as commenting takes longer relative to the video's duration.
