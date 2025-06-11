# mapsindoors-gemini-chatbot-example

## Getting Started

Follow these steps to set up and run the sample code locally:

### Prerequisites

* A web browser (e.g., Chrome, Firefox, Edge)

* A text editor

### 1. Obtain API Keys

You will need API keys for both MapsIndoors and Google Gemini:

* **MapsIndoors API Key:** Obtain this from your MapsIndoors account.

* **Gemini API Key:**

  1. Go to [Google AI Studio](https://aistudio.google.com/app/apikey).

  2. Sign in with your Google account.

  3. Create a new API key.

### 2. Download the Sample Code

Clone this repository or download the `index.html` file directly:

```bash
git clone https://github.com/MapsPeople/mapsindoors-gemini-chatbot-example.git
cd mapsindoors-gemini-chatbot-example
```

### 3. Configure API Keys

Open the `index.html` file in your text editor. Locate the configuration section and replace the placeholder API keys with your actual keys:

```javascript
// Configuration & Settings ---
const YOUR_GEMINI_API_KEY = "YOUR_GEMINI_API_KEY_HERE";   // <--- PASTE YOUR GEMINI API KEY HERE =--!
const MAPSINDOORS_API_KEY = "YOUR_MAPSINDOORS_API_KEY_HERE"; // <PASTE YOUR MAPSINDOORS API KEY HERE ---!
```
**Important Security Note:** For production environments, your Gemini API key should **NEVER** be exposed client-side. It must be securely managed on a backend server that proxies requests to the Gemini API. This example places the key client-side for demonstration purposes only.

### 4. Run the Application

Simply open the `index.html` file in your web browser. There is no need for a local server for this basic example.

## Usage

Once the application is running in your browser, you can interact with the chatbot by typing messages into the input field at the bottom and pressing "Send" or Enter.

**Note:** The results of the chatbot may vary depending on the specific MapsIndoors solution and the data available in your MapsIndoors account.

Try asking questions like:

* "Where is the nearest coffee shop?"

* "How do I get to meeting room B from the main entrance?"

* "Are there any restrooms on this floor?"

* "Give me walking directions to the cafeteria."

## Key Files and Structure

* `index.html`: Contains the full HTML structure, CSS styling (using Tailwind CSS), and JavaScript logic for the chatbot. This single file is self-contained for simplicity.
