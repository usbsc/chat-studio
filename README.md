# Chat Studio - AI Creative Studio

A ChatGPT-like web interface for collaborative creative work with AI models. Upload images, chat with your AI model, and build on ideas together.

## 🆓 **FREE to use - No payment required!**

## ⚡ Quick Start (2 minutes)

1. **Get FREE API Token**: Go to https://huggingface.co/settings/tokens
   - Sign up for a free Hugging Face account (takes 1 minute)
   - Click "New token"
   - Copy the token
2. **Open Chat Studio**: Visit https://usbsc.github.io/chat-studio/
3. **Paste your token**: Paste into the "API Key" field
4. **Start chatting**: Type your message and hit Enter!

That's it! No credit card, completely free. 🎉

## 🎨 Features

- **Clean ChatGPT-style Interface**
  - Modern, intuitive chat UI
  - Message history sidebar
  - Real-time message streaming

- **Multi-Model Support**
  - OpenAI (GPT-4, GPT-3.5, etc.)
  - Claude (Anthropic)
  - Local/Custom API endpoints

- **Image Upload & Processing**
  - Upload multiple images
  - Image preview before sending
  - Full-size image viewer
  - AI can analyze and describe images

- **Customizable System Prompt**
  - Configure AI behavior
  - Set custom instructions
  - Adjust model parameters

- **Chat Management**
  - Multiple conversation threads
  - Auto-save conversations
  - Clear chat history
  - Persistent storage (localStorage)

- **Responsive Design**
  - Works on desktop, tablet, mobile
  - Sidebar collapses on small screens
  - Touch-friendly interface

## 🚀 Getting Started

### Setup

1. **Open the app**: Visit `index.html` in your browser
2. **Configure API**:
   - Select your AI provider (OpenAI or Claude)
   - Enter your API key
   - Set the model name
   - (Optional) Enter custom API endpoint
3. **Customize System Prompt** (optional)
   - Edit the system prompt in the sidebar
   - This defines how the AI behaves

### Using Chat Studio

1. **Type your message** in the input field
2. **Upload images** (optional) using the attachment button
3. **Press Enter** to send (Shift+Enter for new line)
4. **View responses** from your AI model
5. **Start new chats** with the "+ New Chat" button

## 🔑 API Configuration

### 🆓 Hugging Face (FREE - Recommended!)
- **Provider**: Hugging Face (default)
- **API Token**: Get FREE at https://huggingface.co/settings/tokens
- **Model**: mistralai/Mistral-7B-Instruct-v0.1 (default, very capable)
- **Cost**: Completely free, no payment required!
- **Why use it**: Works in browsers without CORS issues

### 🆓 Google Gemini (FREE - Alternative)
- **Provider**: Google Gemini
- **API Key**: Get FREE at https://makersuite.google.com/app/apikey
- **Model**: gemini-pro
- **Cost**: Completely free
- **Note**: May have CORS issues with some browsers

### OpenAI
- **Provider**: OpenAI
- **API Key**: Get from https://platform.openai.com/account/api-keys
- **Model**: gpt-4, gpt-4-turbo, gpt-3.5-turbo, etc.
- **Cost**: Paid (requires payment method)
- **Endpoint**: Leave blank (uses default)

### Claude (Anthropic)
- **Provider**: Claude
- **API Key**: Get from https://console.anthropic.com/
- **Model**: claude-3-opus, claude-3-sonnet, etc.
- **Cost**: Paid (requires payment method)
- **Endpoint**: Leave blank (uses default)

### Custom Endpoint
- Set provider to OpenAI or Claude format
- Enter your custom endpoint URL
- API Key must be compatible with your endpoint

## 🛡️ Privacy & Security

- **No backend storage**: All data stored locally in your browser
- **API keys are private**: Only stored in your browser's localStorage
- **Never shared**: Your conversations and API keys never leave your device
- **Clear cookies**: Clear browser data to delete all stored information

## 💡 Use Cases

- **Creative Brainstorming**: Generate and refine ideas
- **Image Analysis**: Upload images for AI feedback
- **Code Review**: Get AI feedback on code snippets
- **Writing Assistance**: Brainstorm, edit, and improve content
- **Design Feedback**: Get AI suggestions on visual work
- **Learning**: Ask questions and build on responses

## ⌨️ Keyboard Shortcuts

- **Enter**: Send message
- **Shift + Enter**: New line in input
- **Click image**: View full-size in modal

## 📋 System Prompt Examples

### Creative Writing Assistant
```
You are a creative writing assistant. Help the user develop stories, improve prose, and brainstorm narrative ideas. Provide detailed feedback and suggestions.
```

### Code Assistant
```
You are an expert programming assistant. Help with code reviews, debugging, optimization, and learning. Provide clear explanations and best practices.
```

### Design Feedback
```
You are a UI/UX design expert. Analyze images of designs, provide constructive feedback, suggest improvements, and discuss design principles.
```

## 🔄 How It Works

1. **Configuration**: Store API credentials and preferences
2. **Conversation**: Send messages and images to your AI model
3. **Processing**: AI analyzes text and images
4. **Response**: Receive AI-generated responses
5. **Storage**: Auto-save conversations locally

## 🌐 Deployment

This is a static HTML file that can be deployed anywhere:
- GitHub Pages
- Netlify
- Vercel
- Any web hosting
- Local file (just open in browser)

## 📱 Mobile Support

- Full mobile responsiveness
- Touch-friendly buttons
- Optimized for small screens
- Works on phones and tablets

## ⚠️ Important Notes

1. **API Costs**: Costs depend on your AI provider's pricing
2. **Rate Limits**: Check your provider's rate limits
3. **Data**: Configure your provider's data handling preferences
4. **Models**: Model availability may change - check your provider

## 🔐 Best Practices

- Use strong, unique API keys
- Never share API keys with others
- Clear localStorage periodically
- Review conversations for sensitive data
- Check your API provider's terms

## 🐛 Troubleshooting

### "API request failed"
- Check your API key is correct
- Verify your model name is valid
- Check API endpoint URL
- Ensure CORS is enabled (for custom endpoints)

### "Images not working"
- Check image file size
- Verify image format is supported (JPEG, PNG, etc.)
- Some models may not support images - check your provider

### "Conversations not saving"
- Check localStorage is enabled
- Verify browser hasn't disabled it
- Try clearing cache and reloading

## 📚 Resources

- [OpenAI Documentation](https://platform.openai.com/docs)
- [Anthropic Claude Documentation](https://docs.anthropic.com)
- [Web Storage API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API)

---

**Chat Studio v1.0** | AI-Powered Creative Workspace | Built with vanilla JavaScript
