![image](https://github.com/user-attachments/assets/4138075e-9320-44fd-aa20-f2096e82711a)# A.I-Mail

A.I-Mail is a web-based platform that integrates AI-powered content generation and email sending services. It provides users with a suite of tools for chatting with AI, generating text, analyzing images, translating languages, and sending emails, all within a modern, user-friendly interface.

## Pics 
![image](https://github.com/user-attachments/assets/d14e7270-862d-4c7d-a515-d8b87d0ff1ec)
![image](https://github.com/user-attachments/assets/506e288b-03e1-4a18-a2f8-8f951e99e4a8)
![image](https://github.com/user-attachments/assets/067983c5-f9fc-4663-b98d-f37da8b72a2d)
![image](https://github.com/user-attachments/assets/316df11b-d7f1-4121-a6a6-0b2bd469c881)
![image](https://github.com/user-attachments/assets/93c9783d-1b68-4202-9ba3-287769c2107d)
![image](https://github.com/user-attachments/assets/f7f263e2-291d-4143-b6fc-7264ad0230b2)
![image](https://github.com/user-attachments/assets/9dba41a1-e594-4e73-abd1-7ccd468d2661)
![image](https://github.com/user-attachments/assets/97c5bfbd-d380-4434-bcca-c2ca84937770)
![image](https://github.com/user-attachments/assets/3c807103-f7ea-4f86-909d-db4ff7e46eea)
![image](https://github.com/user-attachments/assets/d436b582-1987-4747-85eb-96032076b6e4)
![image](https://github.com/user-attachments/assets/3ac66b01-e3ef-462f-b279-bc3a044ace27)
![image](https://github.com/user-attachments/assets/f924bd6e-15e3-41b5-b5ca-d4e286814970)
![image](https://github.com/user-attachments/assets/aff800a4-1a5d-479a-b960-2d3f5ff4b497)
![image](https://github.com/user-attachments/assets/379071b7-dfd8-4d61-818a-56100cedd0e4)
![image](https://github.com/user-attachments/assets/f6d514c2-9ed6-4d36-9902-7b2a99a2727f)
![image](https://github.com/user-attachments/assets/04b1c70b-fe89-4f42-ab96-8ad67106414f)
![image](https://github.com/user-attachments/assets/a6e0b7af-a134-42a1-831a-b319f1b63068)
![image](https://github.com/user-attachments/assets/1073e583-a79b-460e-993c-c6d169613d50)

## Features

- **AI Chat Assistant:** Chat with an AI assistant for help, information, or conversation.
- **Text Generation:** Generate professional emails, blog posts, creative stories, and summaries using AI.
- **Image Analysis:** Upload images for AI-powered analysis and insights.
- **Code Assistant:** Get code generation, debugging, and explanations from AI.
- **Language Translation:** Translate text between multiple languages using AI.
- **Email Sending:** Send emails directly from the platform using EmailJS integration.
- **Modern UI:** Responsive, visually appealing interface with dark mode and user-friendly navigation.

## Technologies Used

- **HTML5 & CSS3** for structure and styling
- **JavaScript** for interactivity and AI integration
- **OpenAI API** for AI-powered chat and content generation (API key required, not included in repo)
- **EmailJS** for sending emails from the web interface (public key required, not included in repo)

## Setup & Usage

1. **Clone the repository:**
   ```sh
   git clone https://github.com/050903/A.I-Mail.git
   cd A.I-Mail
   ```

2. **Configure API Keys:**
   - The code is designed to prompt users to enter their OpenAI API key and EmailJS public key at runtime. **No secrets are stored in the repository.**
   - For production, use environment variables or secure input methods to provide API keys.

3. **Open the HTML files in your browser:**
   - Main entry points: `webai.html`, `email.ai.html`, `aimeil.html`, etc.
   - No server setup required; all features run client-side.

4. **Security Notice:**
   - **Never commit API keys or secrets to the repository.**
   - This repository has been scrubbed of all secrets using `git filter-repo`.

## Removing Secrets from Git History

If you accidentally commit a secret, follow these steps to remove it from your git history:

1. Create a `replacements.txt` file with the secret and replacement:
   ```
   your-secret-value==>REMOVED
   ```
2. Run:
   ```sh
   git filter-repo --replace-text replacements.txt --force
   git remote add origin <your-repo-url> # if needed
   git push -u origin main --force
   ```

See [GitHub's documentation](https://docs.github.com/code-security/secret-scanning/working-with-secret-scanning-and-push-protection/about-push-protection-for-secrets) for more details.

## License

MIT License

Copyright (c) 2024 Tran The Hao

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
