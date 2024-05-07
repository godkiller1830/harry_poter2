Welcome to the **Hogwarts Alumni: A Magical Android App**. An AI Assistant integrated with the ChatGPT API into this Android application for conversational AI features.

## Adding Your OpenAI API Key

To use the application, you'll need to replace the placeholder API key with your own. 

1. **Locate the Service File:**  
   - Navigate to the following path in your project:  
     `java/com/kenstarry/harrypotter/AIassistant/OpenAIService.kt`

2. **Replace the API Key:**  
   - In the `OpenAIService.kt` file, find the following line:  
     ```kotlin
     private const val API_KEY = "YOUR_API_KEY"
     ```
   - Replace `"YOUR_API_KEY"` with your personal API key obtained from OpenAI.

### Why Isn't My API Key Included?

For security reasons, the API key isn't included directly in the repository. Sharing an API key publicly could expose it to misuse, risking unauthorized usage and potential charges. We encourage all users to keep their keys private by:

- Using environment variables or secure storage mechanisms.
- Avoiding hard-coding sensitive information into source files.
- Not sharing API keys or other credentials on public platforms.

By following these practices, you'll help ensure that your API access remains secure and private.

### Don't you know how to create your personal API key? Don't worry

## Getting an OpenAI API Key

1. **Sign Up for OpenAI:** Visit the [OpenAI website](https://beta.openai.com/signup/) to sign up for an account.

2. **Access API Keys:**
   - Once signed in, go to the [API Keys page](https://platform.openai.com/account/api-keys).
   - Click on "Create new secret key".
   - Copy the generated key to your clipboard and keep it in a safe place.

3. **Secure Your API Key:**
   - Make sure you keep your API key private. Do not include it in public repositories.
   - Use environment variables or a secure secrets management tool to access the key in your development environment.
