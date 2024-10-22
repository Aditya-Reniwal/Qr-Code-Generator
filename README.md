📱 QR Code Generator
A simple QR Code Generator built with Node.js using inquirer to capture user input and qr-image to generate QR codes. This tool takes a URL from the user and generates a corresponding QR code image.

🚀 Features
🖥 Command-line interface using inquirer
📸 QR code generation using qr-image
📄 Saves user input and generates QR code as qr-img.png
🛠 Installation
Make sure you have Node.js installed on your machine. Then follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/your-username/qr-code-generator.git
cd qr-code-generator
Install dependencies:

bash
Copy code
npm install
📦 Dependencies
This project uses the following npm packages:

inquirer: For capturing user input via CLI
bash
Copy code
npm install inquirer
qr-image: For generating QR codes as PNG images
bash
Copy code
npm install qr-image
⚙️ Usage
Run the application:

bash
Copy code
node index.js
Enter the URL when prompted:

arduino
Copy code
? Type your URL: https://example.com
A QR code image (qr-img.png) will be generated in your project folder.

🖼 Example Output
Here’s what the generated QR code looks like:

(Replace this example image with the actual QR code image generated.)

🐛 Error Handling
TTY Error: If the prompt can’t be rendered in the current environment, ensure you’re running the script in a supported terminal.
File System Issues: Make sure you have write permissions to create the qr-img.png file in the project directory.
🤝 Contributing
Fork the repository.
Create a new branch:
bash
Copy code
git checkout -b feature-branch
Make your changes and commit:
bash
Copy code
git commit -m "Add new feature"
Push the changes:
bash
Copy code
git push origin feature-branch
Create a pull request.
📜 License
This project is licensed under the MIT License.

💡 Future Improvements
 Add validation for the URL input.
 Allow users to customize the QR code (size, color, etc.).
 Generate multiple QR codes in bulk.
📧 Contact
For any questions, feel free to contact:

Your Name
GitHub: your-username
