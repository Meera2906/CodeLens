# CodeLens: Story-Based Code Explainer

CodeLens is a sophisticated educational tool designed for teachers and educators to bridge the gap between complex technical logic and human understanding. It transforms abstract algorithms into engaging stories and analogies, making computer science concepts accessible to non-technical audiences.

![CodeLens Preview](https://picsum.photos/seed/codelens/1200/600)

## ✨ Features

- **Algorithm Pastebin**: A clean, high-fidelity code editor for pasting snippets in various languages (Python, Java, C++, JavaScript, etc.).
- **Story-Based Explanations**: Uses the power of Google Gemini AI to translate code into intuitive narratives and analogies.
- **Progressive Disclosure**: Breaks down complex logic into digestible parts, focusing on the "why" and "how" rather than just the syntax.
- **Premium Aesthetic**: Features a beautiful dark-themed interface with a starry background, fluid animations, and a custom-designed UI.
- **Multi-Language Support**: Supports automatic language detection or manual selection for precise analysis.
- **Teacher-First Design**: Includes helpful tips and a layout optimized for classroom presentations.

## 🚀 Tech Stack

- **Framework**: [React 19](https://react.dev/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **AI Engine**: [Google Gemini API](https://ai.google.dev/) (`gemini-3-flash-preview`)
- **Code Editor**: [react-simple-code-editor](https://github.com/satya164/react-simple-code-editor)
- **Syntax Highlighting**: [Prism.js](https://prismjs.com/)
- **Build Tool**: [Vite](https://vitejs.dev/)

## 🛠️ Getting Started

### Prerequisites

- Node.js (v18 or higher)
- A Google Gemini API Key

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/codelens.git
   cd codelens
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory and add your Gemini API key:
   ```env
   GEMINI_API_KEY=your_api_key_here
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📖 Usage Guide

1. **Paste Your Code**: Enter the algorithm or code snippet you want to explain into the "Algorithm Pastebin".
2. **Select Language**: Choose the programming language or let the "Auto Detect" feature handle it.
3. **Explain as a Story**: Click the "Explain as a Story" button to trigger the AI analysis.
4. **Review the Story**: Read the generated analogy and breakdown in the results section.
5. **Toggle Theme**: Use the theme switcher to alternate between the premium dark mode and a clean light mode.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

*Built for the next generation of educators.*
