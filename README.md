<!DOCTYPE html>
<html lang="en">
<body>
    <h1 align="center">Drug Detection System Using OCR</h1>
    <p align="center">
        A web application that identifies text from uploaded images of medicines, provides detailed information about the medicine, translates the extracted text into different languages, and offers a text-to-speech feature.
    </p>

<h2>📜 Features</h2>
    <ul>
        <li><strong>Text Extraction:</strong> Uses OCR (Optical Character Recognition) to extract text from images of medicines using the Tesseract.js library.</li>
        <li><strong>AI Response:</strong> Generates detailed information about the extracted text using Google's Generative AI model (Gemini 1.5 Flash).</li>
        <li><strong>Translation:</strong> Supports translation of extracted text into multiple languages using MyMemory Translation API.</li>
        <li><strong>Text-to-Speech:</strong> Converts translated text into speech for supported languages using the Web Speech API.</li>
        <li><strong>Responsive Design:</strong> The UI is designed using Tailwind CSS to ensure compatibility across different devices.</li>
    </ul>

<h2>🚀 How It Works</h2>
    <ol>
        <li><strong>Upload Image:</strong> Users can upload an image of a medicine. The application extracts text from the image using OCR.</li>
        <li><strong>Generate Details:</strong> The extracted text is sent to Google's Generative AI, which provides detailed information about the medicine.</li>
        <li><strong>Translate:</strong> Users can select a target language to translate the extracted text into their preferred language.</li>
        <li><strong>Speak:</strong> The translated text can be converted to speech in the selected language.</li>
    </ol>

<h2>📦 Technologies Used</h2>
    <ul>
        <li><strong>Frontend:</strong> HTML, Tailwind CSS, JavaScript</li>
        <li><strong>OCR:</strong> Tesseract.js</li>
        <li><strong>Generative AI:</strong> Google Generative AI (Gemini 1.5 Flash)</li>
        <li><strong>Translation API:</strong> MyMemory Translated API</li>
        <li><strong>Text-to-Speech:</strong> Web Speech API</li>
    </ul>

<h2>📂 Project Structure</h2>
    <pre>
    ├── index.html        # Main HTML file
    ├── style.css         # Stylesheet (optional, Tailwind used via CDN)
    ├── script.js         # JavaScript for functionality
    └── README.html       # Project documentation
    </pre>

<h2>📖 Usage</h2>
    <ol>
        <li>Clone the repository to your local machine.</li>
        <li>Open the <code>index.html</code> file in a web browser.</li>
        <li>Upload an image of a medicine.</li>
        <li>Wait for the text to be extracted and detailed information to be generated.</li>
        <li>Optionally, translate the text and use the text-to-speech feature.</li>
    </ol>

<h2>⚠️ Limitations</h2>
    <ul>
        <li>Requires a clear image of the medicine for accurate OCR results.</li>
        <li>Limited to languages supported by MyMemory Translation API and Web Speech API.</li>
        <li>No backend; all functionality runs client-side.</li>
    </ul>

<h2>📧 Contact</h2>
    <p>If you have any questions or feedback, feel free to reach out!</p>
</body>
</html>
