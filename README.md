A simple message box that counts characters in real time. It stops typing at 200 characters and shows a warning when the limit is reached. You can also copy the text or clear it with one click.

✨ Features
🔢 Live counter: Shows how many characters are typed and how many are left (example: 150/200 characters, 50 remaining)
🚫 Character limit: Stops typing at 200 characters, and pasted text is cut to the limit too
⚠️ Warning message: Appears when the limit is reached
📋 Copy button: Copies the text to your clipboard and shows a "Copied!" message
🧹 Clear button: Empties the text box in one click
🎨 Tailwind CSS styling: Clean and responsive design
🛠️ Built With
🌐 HTML5: Page structure
🎨 Tailwind CSS: Styling
⚡ JavaScript: Counter, copy, and clear logic
🔤 Google Fonts (Poppins): Typography
📁 Project Structure
character-counter/
├── index.html        # Main page
├── src/
│   ├── input.css     # Tailwind source file
│   └── output.css    # Generated CSS (created by Tailwind)
├── package.json      # Project info and dependencies
└── README.md         # This file
🚀 Getting Started
1. Clone the repository
bash
git clone https://github.com/your-username/character-counter.git
cd character-counter
2. Install Tailwind CSS
bash
npm install
npm install -D tailwindcss @tailwindcss/cli
3. Build the CSS

Run this in the terminal and keep it open. It updates the CSS whenever you save a file:

bash
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
4. Open the app

Open index.html in your browser. For a quicker setup, you can use the Live Server extension in VS Code.

📖 How to Use
⌨️ Type your message in the text box.
👀 Watch the counter update as you type.
📋 Click Copy to copy the message.
🧹 Click Clear to start again.
