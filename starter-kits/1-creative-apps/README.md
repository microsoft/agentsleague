# 🎨 Creative Apps - Starter Kit

**Track**: Battle #1 - Creative Apps with GitHub Copilot  

Welcome to the Creative Apps track! In this challenge, you will harness the power of **GitHub Copilot** and **VS Code** to build innovative, imaginative applications that push your creativity. Your goal is to create applications that showcase the potential of AI-assisted development while delivering unique, engaging user experiences. All application types are welcome — web apps, CLI tools, games, mobile apps, desktop applications, and beyond—**maximum creativity is encouraged!**

---

## 💡 Project Ideas

In this track, we encourage you to build creative applications that demonstrate the power of AI-assisted development with GitHub Copilot. Here are some categories and ideas to inspire your project:

### Content Generation

Build applications that create, transform, or enhance creative content:

- **Story Generator**: An AI-powered narrative engine that creates interactive fiction, short stories, or personalized bedtime stories based on user prompts and preferences
- **Music Composer**: A tool that creates melodies, chord progressions, or full musical arrangements
- **Script Writer**: An assistant for creating screenplays, dialogue, or theatrical scripts

### Visual Creativity

Develop tools that enable visual expression and design:

- **Design Assistant**: A tool that helps users create logos, color palettes, layouts, or design mockups
- **Image Manipulation Tool**: An application for creative photo editing, filters, or artistic transformations
- **ASCII Art Generator**: Convert images or text into creative ASCII or Unicode art

### Game Development

Create playful, interactive experiences:

- **Puzzle Generator**: Applications that create unique puzzles, riddles, or brain teasers
- **Game Asset Creator**: Tools for generating sprites, textures, or game dialogue

### Creative Productivity

Build tools that enhance creative workflows:

- **Content Remixer**: Transform existing content into new formats, styles, or mediums for various platforms
- **Idea Brainstormer**: An application that generates creative ideas, prompts, or concepts for writers, artists, or designers

### Interactive Experiences

Craft engaging, conversational, or immersive applications:

- **Character Chatbot**: Create conversational agents with unique personalities, backstories, or expertise
- **Educational Games**: Interactive learning experiences that make education engaging and fun

Feel free to combine categories, invent entirely new concepts, or explore areas not listed here. **There are no restrictions on application type or technology stack — web, CLI, mobile, desktop, embedded, VR/AR, and more are all welcome!**

---

## 🚀 Quick Start

Get started quickly by setting up VS Code and GitHub Copilot. Follow the official [VS Code Setup Guide](https://code.visualstudio.com/docs/setup/setup-overview) for detailed platform-specific instructions.

### Step 1: Download and Install VS Code

Download and install Visual Studio Code for your platform:

- [macOS](https://code.visualstudio.com/docs/setup/mac)
- [Linux](https://code.visualstudio.com/docs/setup/linux)
- [Windows](https://code.visualstudio.com/docs/setup/windows)

VS Code is lightweight (< 200 MB download) and ships monthly releases with auto-update support.

> **Note:** If you choose to use VS Code Insiders, you will have access to the latest features but you may encounter occasional instability.

### Step 2: Install Additional Components

Install development tools based on your project needs:

- [Git](https://git-scm.com/) for version control
- [Node.js](https://nodejs.org/) for JavaScript/TypeScript development
- Language runtimes for Python, Java, Go, or other languages you plan to use

See the full list of [additional components](https://code.visualstudio.com/docs/setup/additional-components).

### Step 3: Install VS Code Extensions

Customize VS Code with extensions from the [Visual Studio Marketplace](https://marketplace.visualstudio.com/VSCode):

- Formatters
- Language extensions and debuggers
- Tools for your favorite frameworks

### Step 4: Enable AI Features with GitHub Copilot

Follow the [Copilot Setup Guide](https://code.visualstudio.com/docs/copilot/setup) to enable AI-powered coding:

1. Hover over the **Copilot icon** in the Status Bar and select **Use AI Features**
2. Choose a sign-in method and follow the prompts
3. If you don't have a Copilot subscription, you'll be signed up for the [Copilot Free plan](https://github.com/github-copilot/signup) with a monthly limit of inline suggestions and chat interactions
4. Start using Copilot in VS Code!

Learn more about [GitHub Copilot plans](https://docs.github.com/en/copilot/get-started/plans).

### Step 5: Get Started with the VS Code Tutorial

Discover the user interface and key features of VS Code with the [Getting Started Tutorial](https://code.visualstudio.com/docs/getstarted/getting-started).

### Using GitHub Copilot

GitHub Copilot provides powerful AI capabilities directly in VS Code. Learn more in the [Copilot Overview](https://code.visualstudio.com/docs/copilot/overview).

#### Inline Suggestions

Copilot provides inline code suggestions as you type, from single line completions to entire function implementations:

- Type a function signature like `function calculateScore(` to get complete implementations
- Write comments like `// Create a particle system for visual effects` to generate code
- Begin a component with `const AnimatedCanvas = ({` to receive a complete implementation

Press `Tab` to accept suggestions or `Esc` to dismiss.

#### Natural Language Chat

Use natural language to interact with your codebase through the Chat view (`Ctrl+Shift+I` / `Cmd+Shift+I`):

- "How does this animation loop work?"
- "What's causing the rendering issue in the draw function?"
- "Add sound effects when the user clicks the canvas"
- "Create a color palette generator component"

Learn more about [using chat in VS Code](https://code.visualstudio.com/docs/copilot/chat/copilot-chat).

#### Autonomous Coding with Agents

Agents can autonomously plan and execute complex development tasks. Select **Agent** from the agent picker in the Chat view:

- "Implement a generative art canvas with multiple brush styles"
- "Create a music visualizer that responds to audio input"
- "Build a story generator with branching narrative paths"

The agent will iterate on the code, running commands and making coordinated changes across multiple files.

#### Inline Chat

For quick edits directly in the editor:

1. Select code and press `Ctrl+I` / `Cmd+I` to open inline chat
2. Ask Copilot to modify, refactor, or explain the selected code
3. Review and accept or reject proposed changes


### Understanding GitHub Copilot Modes

GitHub Copilot offers distinct modes, each designed to enhance your coding workflow in unique ways. Understanding when to use each mode will help you get the most out of Copilot for your creative projects:

#### Ask Mode

Ask Mode is a Q&A assistant that helps you understand code, solve problems, or learn concepts. It allows you to ask questions in natural language, and Copilot responds with explanations, snippets, or suggestions. It does not directly modify any code.

> **Tip**: Ask mode works best for quick clarifications, brainstorming creative solutions, and getting sample implementations for your project ideas.

**Example prompts for creative apps:**
- "How can I create a particle system effect in p5.js?"
- "What's the best approach for generating procedural music?"
- "Explain how color theory applies to generative art"

#### Edit Mode

Edit Mode enables direct code modifications based on natural language instructions. You can highlight specific code blocks or files, describe the desired changes, and Copilot will propose edits. These changes are presented as diffs for your review, ensuring you retain control over the final implementation.

> **Tip**: Try Edit mode for targeted updates, such as refactoring animation code or adding error handling to your creative application.

**Example prompts for creative apps:**
- "Add easing functions to this animation"
- "Refactor this drawing code to support multiple brush types"
- "Add input validation to the user prompt handler"

#### Agent Mode

Agent Mode is the most autonomous and powerful of the modes. It allows Copilot to analyze your entire project, plan tasks, make edits, run commands, and iterate until the goal is achieved. This mode is ideal for multi-step tasks, such as building features, fixing bugs, or scaffolding new components.

> **Tip**: Agent mode will carry out actions beyond just editing—it can write code, create new files, and run terminal commands. Best used for complex creative features that span multiple files.

**Example prompts for creative apps:**
- "Create a complete music visualizer component with audio analysis"
- "Build a story generator with save/load functionality and branching paths"
- "Implement a generative art canvas with multiple brush styles and export options"

#### Plan Mode

Plan Mode helps you outline your coding tasks and objectives more effectively. Copilot assists in creating a structured plan for your project, helping you break down complex creative tasks into manageable steps.

> **Tip**: Use Plan Mode when starting a new creative project to set clear objectives and receive tailored suggestions for your implementation approach.

**Example prompts for creative apps:**
- "Plan the architecture for an interactive fiction engine"
- "Help me break down building a procedural music generator"
- "Create a roadmap for implementing a collaborative art platform"

### Getting Started Checklist

1. ✅ Download and install VS Code for your platform
2. ✅ Install additional components (Git, Node.js, language runtimes)
3. ✅ Enable AI features and sign in to GitHub Copilot
4. ✅ Explore Copilot Chat and inline chat features
5. ✅ Choose your creative project idea and target platform
6. ✅ Start building and let Copilot accelerate your development!

---

## ✨ Prompting Tips

Effective prompting is key to getting the most out of GitHub Copilot for creative development. Here are tips and techniques to improve your results:

### Use File References for Context

When working with GitHub Copilot Chat, use the `#file:filename` syntax to provide specific file context:

1. Type `#` in the Copilot chat window
2. A file picker will appear automatically
3. Select the file you want to reference
4. Then type or paste the rest of your prompt

**Example**: Instead of asking "add an animation function", ask "#file:canvas.js add a smooth easing animation function for the particle system"

### Be Specific About Creative Intent

Vague prompts lead to generic results. Include details about style, mood, and technical requirements:

| ❌ Vague Prompt | ✅ Specific Prompt |
|----------------|--------------------|
| "Generate some art" | "Create a generative art function that draws flowing curves using Perlin noise with a cool color palette" |
| "Make music" | "Generate a chord progression in C major with jazz voicings using Tone.js" |
| "Write a story" | "Create a branching narrative function that generates mystery story segments with 3 choices per scene" |

### Iterate Incrementally

For complex creative features, break your requests into smaller steps:

1. **Start with the foundation**: "Create a basic canvas setup with a render loop"
2. **Add core functionality**: "Add a particle class with position, velocity, and lifespan"
3. **Enhance with creativity**: "Make particles leave colorful trails that fade over time"
4. **Polish the experience**: "Add mouse interaction so particles are attracted to the cursor"

### Validate AI Suggestions

When Copilot generates creative code:

- **Test incrementally**: Run the code after each significant change to catch issues early
- **Trust but verify**: AI suggestions are starting points—review for correctness and style
- **Learn from output**: If a suggestion doesn't match your intent, refine your prompt with more context
- **Use Cheatsheets**: Keep reference documentation handy to validate generated code against known patterns

### Prompt Templates for Creative Apps

Here are reusable prompt patterns for common creative tasks:

**For Visual Effects:**
```
Create a [effect type] effect using [library/framework] that [behavior description]. 
The visual style should be [aesthetic description] with [color/mood] tones.
```

**For Generative Content:**
```
Build a [content type] generator that creates [output description] based on [input/parameters]. 
Include options for [customization options] and output in [format].
```

**For Interactive Experiences:**
```
Implement [interaction type] that responds to [user input]. 
When the user [action], the application should [response] with [feedback type].
```

### Using Inline Chat Effectively

For quick edits directly in the editor (`Ctrl+I` / `Cmd+I`):

- Select the specific code you want to modify before opening inline chat
- Use follow-up prompts to refine without rewriting the whole request
- Ask for explanations of generated code to understand the approach

---

## 🤖 Available Models

GitHub Copilot supports a variety of AI models with varying capabilities. You can choose different models based on your needs:

- **GPT Models** - Strong general-purpose coding assistance
- **Claude Models** - Excellent for nuanced explanations and creative tasks  
- **Gemini Models** - Good for multimodal understanding

To learn more about GitHub Copilot's capabilities and plans, visit: [GitHub Copilot Plans](https://github.com/features/copilot/plans)

> **Note**: Model availability may vary based on your subscription plan. The techniques in this starter kit are model-agnostic and work across all supported models.

---

## 📋 Requirements & Evaluation

Your solution will be evaluated based on the following criteria. We're looking for projects that demonstrate both technical excellence and creative innovation:

### Core Requirements

#### 1. GitHub Copilot Usage (Required)

Your project **must** demonstrate meaningful use of **GitHub Copilot** during development. This includes:

- Using Copilot suggestions to accelerate code writing
- Leveraging Copilot Chat for problem-solving, debugging, or code explanation
- Documenting how Copilot assisted in your creative process

#### 2. Creative Application (Required)

Your submission **must** be a creative application that showcases innovation and imagination. The application should:

- Demonstrate a unique or novel concept
- Provide value, entertainment, or utility to users
- Show thoughtful design in user experience

### 🏆 Evaluation Criteria

Projects are evaluated by experts and product teams using this rubric:

- **Accuracy & Relevance (20%)** — Meets challenge requirements
- **Reasoning & Multi-step Thinking (20%)** — Clear problem-solving approach
- **Creativity & Originality (15%)** — Novel ideas or unexpected execution
- **User Experience & Presentation (15%)** — Clear, polished, demoable
- **Reliability & Safety (20%)** — Solid patterns, avoids obvious pitfalls
- **Community vote (10%)** via the Discord poll available at https://aka.ms/agentsleague/discord

---

## 📚 Resources

Explore the following resources to master GitHub Copilot and accelerate your creative development:

### GitHub Copilot Documentation

Official documentation and guides for GitHub Copilot:

- **Getting Started with GitHub Copilot**: [https://docs.github.com/en/copilot/getting-started-with-github-copilot](https://docs.github.com/en/copilot/getting-started-with-github-copilot)
- **GitHub Copilot in VS Code**: [https://docs.github.com/en/copilot/using-github-copilot/using-github-copilot-in-your-ide](https://docs.github.com/en/copilot/using-github-copilot/using-github-copilot-in-your-ide)
- **Copilot Chat Documentation**: [https://docs.github.com/en/copilot/using-github-copilot/asking-github-copilot-questions-in-your-ide](https://docs.github.com/en/copilot/using-github-copilot/asking-github-copilot-questions-in-your-ide)
- **GitHub Copilot Plans**: [https://github.com/features/copilot/plans](https://github.com/features/copilot/plans)

### Learning Resources

Tutorials and courses to enhance your skills:

- **GitHub Copilot Fundamentals**: [https://learn.microsoft.com/training/modules/introduction-to-github-copilot/](https://learn.microsoft.com/training/modules/introduction-to-github-copilot/)
- **GitHub Skills - Code with Copilot**: [https://github.com/skills/copilot-codespaces-vscode](https://github.com/skills/copilot-codespaces-vscode)
- **VS Code Tips and Tricks**: [https://code.visualstudio.com/docs/getstarted/tips-and-tricks](https://code.visualstudio.com/docs/getstarted/tips-and-tricks)

---

Questions? Join [Discord](https://aka.ms/agentsleague/discord) #creative-apps channel
