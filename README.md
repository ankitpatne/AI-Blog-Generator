# AI based YouTube to Blog Converter

## Overview

This application is a powerful tool that allows users to convert YouTube videos into blog articles effortlessly. Leveraging the capabilities of various technologies such as TailwindCSS, Django, JavaScript, OpenAI API, AssemblyAI, and PostgreSQL, this application ensures a seamless user experience.

## Demonstration


https://github.com/ankitpatne/AI-Blog-Generator/assets/50258606/3e42d1c1-64e2-4523-91a7-7ee7e82386be





## Features

1. **YouTube Video to Audio:** The user provides a YouTube video link, and the application uses Python libraries to extract the audio from the video.

2. **Audio Transcription with AssemblyAI:** The extracted audio is sent to AssemblyAI through its API for transcription, converting spoken words into text.

3. **Blog Post Generation with ChatGPT:** The transcribed text is then utilized with the ChatGPT OpenAI API to generate a coherent and well-structured blog article.

4. **User Authentication:** Users can sign up and log in to the application. Their generated blog articles are stored securely in the PostgreSQL database, providing easy access to their content.

## Technologies Used

- **Frontend:**
  - TailwindCSS
  - JavaScript

- **Backend:**
  - Django

- **APIs:**
  - OpenAI API (ChatGPT)
  - AssemblyAI

- **Database:**
  - PostgreSQL

## Getting Started

1. **Prerequisites:**
   - Ensure you have Python installed (version X.X.X).
   - Set up a virtual environment and install dependencies using `pip install -r requirements.txt`.

2. **Database Setup:**
   - Set up PostgreSQL and update the database configurations in the `settings.py` file.

3. **Environment Variables:**
   - Create a `.env` file with the necessary environment variables (API keys, database credentials, etc.).

4. **Running the Application:**
   - Run the Django development server using `python manage.py runserver`.

5. **Access the Application:**
   - Open your web browser and navigate to `http://localhost:8000` to use the application.

## Usage

1. **User Registration/Login:**
   - Users need to sign up or log in to access the YouTube to Blog converter.

2. **Input YouTube Video Link:**
   - Provide the link to the YouTube video you want to convert.

3. **Blog Article Generation:**
   - Sit back and relax as the application extracts audio, transcribes it, and generates a blog article using advanced AI technologies.

4. **Access Generated Blogs:**
   - All generated blog articles are saved in the user's profile, accessible upon logging in.

## Future Improvements

- Implement real-time progress updates during the conversion process.
- Enhance the user interface for a more intuitive experience.
- Allow users to edit and customize the generated blog articles.

## Contributing

I welcome contributions! If you have ideas for improvements or bug fixes, please create an issue or submit a pull request.

