**# ai_blog_generator**


**Introduction <br> <br>
Welcome to the AI-Powered YouTube Video Summarizer! This web application leverages cutting-edge technologies to provide users with AI-generated blog posts summarizing the content of YouTube videos. Our stack includes Django for web development,yt_dlp for downloading audio from youtube link, AssemblyAI for video transcription, and OpenAI for blog post generation.

## Key Features
- **Sleek Frontend**: The frontend is designed with HTML and TailwindCSS, ensuring an appealing and user-friendly interface.
  <br><br>
  ![image](https://github.com/user-attachments/assets/b41dbded-0d7b-4284-9175-b14a94d54494)




- **User Authentication**: We've implemented a robust authentication system for user registration and login.
  <br><br>
  ![image](https://github.com/user-attachments/assets/0d574131-3683-4f59-b314-62659cd7519e)



- **Seamless User Experience**: JavaScript and Ajax integration make using our app a breeze.
  <br><br>
![image](https://github.com/user-attachments/assets/0385e4f1-0d7c-443f-9135-23098d09f1ae)



- **Video Transcription**: AssemblyAI transcribes YouTube videos for accurate content analysis.

- **AI-Generated Blogs**: gen ai generates insightful blog posts from video transcriptions.
  <br><br>
![image](https://github.com/user-attachments/assets/2c9e8745-3e97-4252-af76-44c38df655f8)
<br><br>
![image](https://github.com/user-attachments/assets/964313a7-e622-4588-a3f5-4d61f1ef7fb8)



- **Data Persistence**: Blog posts are securely saved to the database for easy retrieval.
  <br><br>
![image](https://github.com/user-attachments/assets/dbc6b255-bb3a-46da-a34f-713862b18166)


## Installation
Follow these steps to get your AI-Powered YouTube Video Summarizer up and running:

1. Clone this repository to your local machine.
   > git clone 'https://github.com/Mayankingale123/AI-Blog-Generator'
3. Set up a virtual environment and install the required packages listed in `requirements.txt`.
   > pip install 'requirements.txt'
4. Configure Django settings, including database configuration.
5. Apply migrations and create a superuser for administrative access.
   > python manage.py createsuperuser
7. Obtain API keys for AssemblyAI and gen ai and configure them within the application.
8. Start the Django development server.
   > python manage.py runserver

## Usage
Getting started with our application is straightforward:

1. Register and log in to your account.
2. Input a YouTube video link of your choice.
3. The application will transcribe the video and generate a blog post summarizing its content.
4. Save the blog post for future reference.
5. Explore your saved blog posts in your account.

## Technologies Utilized
I harness the power of various technologies to deliver this functionality:

- Django
- HTML
- TailwindCSS
- JavaScript
- Ajax
- AssemblyAI
- OpenAI
- google gemini
**Implement user profiles for personalized experiences.
Enhance the UI/UX for a polished appearance.
Continuously improve summarization accuracy and AI-generated content.
**Notes
-During development, I used the free resources of AssemblyAI and google gemini. 
 Warning
-Please be mindful of potential issues:

*Ensure that you do not exceed the token limit of the OpenAI or gemini ai API key.
 Be aware that the free services of AssemblyAI may have limitations.
 Contributing
//I welcome contributions from the community. Feel free to submit issues or pull requests to help me improve.

**Acknowledgments
  I extend our gratitude to AssemblyAI and OpenAI and google gemini for providing powerful AI services that make this project possible.



