q# Karen GPT - "I Want To Speak To Your Manager!"

Karen GPT is a single-page web application that simulates a conversation with "Karen," a chatbot embodying the stereotypical 'Karen' persona. She's impatient, condescending, frequently demands to speak to a manager, and believes she's incredibly important. If you ask for an image, she'll reluctantly generate one using DALL-E 3, but be sure, a 'Karen' will be prominently featured in it!

This application is built with HTML, CSS, and vanilla JavaScript, using the OpenAI GPT-4o model for chat responses and DALL-E 3 for image generation. It's designed to be run directly in a browser with no build steps and can be easily hosted on services like GitHub Pages.

## Features

*   **Authentic Karen Persona:** Interacts with a superior, condescending, and impatient tone.
*   **Signature Phrases:** Frequently uses "ask to speak to a manager," "do you know how important I am?", "this is UNACCEPTABLE!", etc.
*   **GPT-4o Powered Chat:** Utilizes OpenAI's GPT-4o model for dynamic and context-aware Karen-esque replies.
*   **DALL-E 3 Image Generation:** If asked for an image, Karen GPT will instruct DALL-E 3 to generate one, ensuring a "Karen" character is included in the scene.
*   **Secure API Key Handling:** Prompts for your OpenAI API key on first use and stores it securely in your browser's `localStorage`. The key is **never** sent to any server other than OpenAI's.
*   **Modern UI:** A bold, dark-themed, and responsive user interface.
*   **No Build Required:** Runs directly from the `index.html` file.
*   **CDN Hosted Assets:** Uses Google Fonts from a CDN.

## How to Use

### 1. Get an OpenAI API Key

To use Karen GPT, you need an API key from OpenAI. This key allows the application to make requests to the GPT-4o and DALL-E 3 models.

*   **Sign up/Log in:** Go to the [OpenAI Platform](https://platform.openai.com/).
*   **Navigate to API Keys:** Once logged in, go to the [API keys section](https://platform.openai.com/api-keys).
*   **Create a new secret key:** Click on "+ Create new secret key". Give it a name (e.g., "KarenGPTKey") and click "Create secret key".
    ![Create API Key Screenshot](https://i.imgur.com/your_screenshot_of_create_key.png) <!-- You'll need to replace this with an actual screenshot URL if you want an image here -->
*   **Copy your key:** Your new API key will be displayed. **Copy it immediately and store it somewhere safe.** You will not be able to see it again after closing the dialog.
*   **Set up billing:** Ensure you have a payment method added to your OpenAI account and sufficient credits/spending limits, as API usage is not free. You can check your usage and set limits in the [Usage section](https://platform.openai.com/usage) of your OpenAI account.

**Important:** Your API key is a secret. Do not share it publicly. This application stores it only in your browser's local storage.

### 2. Run Karen GPT Locally

1.  **Download:** Download the `index.html` file from this project.
2.  **Open in Browser:** Open the `index.html` file directly in a modern web browser (e.g., Chrome, Firefox, Edge, Safari).
3.  **Enter API Key:** On the first load, a modal will appear prompting you to enter your OpenAI API key. Paste the key you obtained in Step 1 and click "Save & Unleash Karen".
4.  **Chat:** Start typing your inquiries in the input field and witness Karen's delightful responses!

## Hosting on GitHub Pages (Optional)

You can host this application for free on GitHub Pages:

1.  **Create a GitHub Repository:** Create a new public repository on GitHub.
2.  **Upload `index.html`:** Add the `index.html` file to this repository.
3.  **Enable GitHub Pages:**
    *   Go to your repository's "Settings" tab.
    *   In the left sidebar, click on "Pages" (under "Code and automation").
    *   Under "Build and deployment", for "Source", select "Deploy from a branch".
    *   Choose the branch where `index.html` is located (e.g., `main` or `master`).
    *   Select `/(root)` for the folder.
    *   Click "Save".
4.  **Access Your Page:** GitHub Pages will build and deploy your site. A link to your live Karen GPT page (e.g., `https://your-username.github.io/your-repo-name/`) will be displayed on the Pages settings screen after a minute or two.

## Tech Stack

*   **HTML5**
*   **CSS3**
*   **Vanilla JavaScript (ES6+)**
*   **OpenAI API:**
    *   GPT-4o for chat completions.
    *   DALL-E 3 for image generation.
*   **Google Fonts** (via CDN)

## Important Notes

*   **API Costs:** Interacting with Karen GPT will make calls to the OpenAI API, which incurs costs based on your usage of the GPT-4o and DALL-E 3 models. Monitor your usage on the [OpenAI dashboard](https://platform.openai.com/usage).
*   **Entertainment Purposes:** This application is for entertainment purposes only. The "Karen" persona is satirical.
*   **Rate Limits:** Be mindful of OpenAI API rate limits. If you make too many requests too quickly, you might encounter errors.

---

Now, if you'll excuse me, I have some *very important* complaints to file. This README better be up to my standards!