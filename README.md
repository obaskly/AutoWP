# AutoWP

AutoWP is an application designed to automate the generation and posting of SEO-friendly articles to a WordPress website, as well as Social media. The application utilizes OpenAI's GPT models for content generation and provides a user-friendly interface for managing article creation.

![7](https://github.com/obaskly/AutoWP/assets/11092871/1534ca36-88fb-4b82-8caa-fcbb201924ee)


## Features

### Article Generation

- **Keyword Generation**: Users can generate a list of unique keywords on various subjects using OpenAI's GPT models. You can also put your desired keywords within `keywords.txt`.
- **Customizable Article Count**: Users can specify the number of articles to be generated for each keyword.
- **SEO-Friendly Articles**: The application is capable of generating SEO-friendly articles based on the provided keywords.

![3](https://github.com/obaskly/AutoWP/assets/11092871/b3197edf-c433-4087-95fa-474d062f4764)

### Openai integration

- **Model Selection**: Users can choose between different OpenAI GPT models for content generation.
- **Tone Selection**: Users can choose between different tones to use for content generation.

![2](https://github.com/obaskly/AutoWP/assets/11092871/54a1c979-f5d1-49db-bbf3-57ca1d7e0a87)

### WordPress Integration

- **Automated Posting**: Generated articles are automatically posted to the user's WordPress website. Posted articles links are saved to `posted_articles.txt` so that you can keep track.
- **WordPress Credentials Management**: The application allows users to input their WordPress website URL, username, and application password for seamless integration.

![1](https://github.com/obaskly/AutoWP/assets/11092871/bd0c5212-d28f-4bc1-8f62-665679f5fffb)


### Image Integration

- **Multiple Sources**: Images can be generated using DALL-E 3, or scrapped from Pixabay, Unsplash, Pexels.
- **Multiple Images**: User can generate up to 20 image per article.
- **Different Images**: Each time an article is generated, a new set of images will be generated/scrapped to avoid posting the same images.

  ### Watermark Integration

  - You can add a watermark to the bottom right of your images.

  ![4](https://github.com/obaskly/AutoWP/assets/11092871/49edd92d-66e4-43af-b94d-c31a72b96a13)

### Social media Integration

- **Facebook**: Every article generated will be summarized and posted to a facebook page of your choice. (You must be an admin in that page)
- **Instagram**: Every article generated will be summarized and posted to an Instagram account of your choice, along with a picture from the keyword image folder.
- **Twitter**: Every article generated will be summarized and posted to a Twitter account of your choice.
- **Hashtags**: Hashtags will be generated each time according to your article and added to the facebook post.

![11](https://github.com/obaskly/AutoWP/assets/11092871/e5e9a862-456c-4562-aa00-35b570c46a7c)
![12](https://github.com/obaskly/AutoWP/assets/11092871/5b79a414-346e-4e59-887d-2cb6940e029e)

### Scheduling

- **Article Generation Scheduling**: Users can schedule the generation and posting of articles at specified intervals, ranging from every 15 minutes to weekly.
- **Start/Stop Functionality**: The application provides the ability to start and stop the article generation process as needed.

![6](https://github.com/obaskly/AutoWP/assets/11092871/1b443a49-a8a4-46cb-a203-00d46be101fb)

### User Interface

- **Dark and Light Mode**: The application comes with a toggle feature for switching between dark and light themes.
- **Error Handling**: The GUI includes error messaging to inform users of any issues during the article generation or posting process.

![9](https://github.com/obaskly/AutoWP/assets/11092871/e89f5f44-4816-44bc-8679-5cf288359083)
![8](https://github.com/obaskly/AutoWP/assets/11092871/56bf5085-e58a-4a8b-ac03-5728f50381b8)

## Requirements

- OpenAI API Key
- WordPress website with REST API access
- Facebook page access token (in case used)
- Twitter account with an app ready to use (in case used)
- Instagram account (in case used)

## Installation

To use AutoWP, contact me on Telegram: @Anon040

## Usage

- Run the application

- Follow the on-screen instructions to input your OpenAI API key, WordPress credentials, and other settings.

## Free Version

The Free version include the keywords generation only. Default model is set to `gpt-3.5-turbo`. If you want the Full version, contact me on Telegram: @Anon040

Get the Free version from here: https://www.mediafire.com/file/yanxd8jmuq6f17g/AutoWP+Free.rar/file

- rar password: 167

## AutoWP in action

### Current version:

https://www.youtube.com/watch?v=ExCj5r_0xcI

### Previous versions:

First version of the script: https://www.youtube.com/watch?v=ZXOUZcLMp4s

Second version of the script: https://www.youtube.com/watch?v=zyPUQQRHVuM

## About

AutoWP is developed by Obaskly.
