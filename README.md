# **VS Code Extension for Code Review with Ollama (Qwen 2.5 Coder)**

## **Overview**

This VS Code extension allows you to seamlessly integrate Ollama's Qwen 2.5 Coder model into your development workflow. It enables you to select a region of code in the editor, send it to Ollama for a detailed code review, and receive feedback directly within your VS Code environment. This extension helps improve your code quality by leveraging AI-driven insights and suggestions.

## **Features**

- **AI-Powered Code Review**: Get feedback on your selected code region from the Qwen 2.5 Coder model running on Ollama.
- **VS Code Integration**: Select any part of your code and request a review directly from within the editor.
- **Instant Feedback**: Receive real-time suggestions, improvements, and error fixes.
- **Customizable Settings**: Configure the extension to suit your specific code review preferences.

## **Installation**

### **Prerequisites**
- **VS Code**: Make sure you have Visual Studio Code installed.
- **Ollama**: Install Ollama and ensure the Qwen 2.5 Coder model is set up and running on your local machine.

### **Steps**

1. **Install the VS Code Extension**  
   - Open VS Code.
   - Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or pressing `Ctrl+Shift+X` (Windows/Linux) or `Cmd+Shift+X` (macOS).
   - Search for **Code Review with Ollama** and click **Install**.

2. **Configure Ollama**  
   - Ensure that Ollama is installed and running on your local machine.
   - Verify that the `Qwen 2.5 Coder` model is running. You can do this by running the following command in your terminal:
     ```bash
     ollama list
     ```
   - If the model is not listed, install it with:
     ```bash
     ollama pull qwen2.5-coder
     ```

3. **Configure the Extension**  
   - Once the extension is installed, open the **Command Palette** (`Ctrl+Shift+P` or `Cmd+Shift+P`).
   - Search for **Ollama: Configure API Endpoint**.
   - Set the endpoint URL for Ollama 

## **Usage**

1. **Select Code Region for Review**  
   - Open your code file in VS Code.
   - Highlight the region of code you want to be reviewed (can be a function, class, or any block of code).

2. **Call the Code Review**  
   - Right-click on the selected code region and choose **Send Code to Ollama for Review**.
   - The extension will send the selected code to Ollama's Qwen 2.5 Coder model for review.

3. **View Code Review**  
   - Once the model processes your code, the review feedback will appear in the **Output** pane or as a **Notification** in VS Code.
   - The feedback will include suggestions for improvements, error fixes, optimizations, and explanations.

