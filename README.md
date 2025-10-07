# alx-project-0x05-setup

> A Next.js web app that lets users generate AI images from text prompts using the GPT-4 Image Generation API.

---

## 🧩 Table of Contents

1. [Features](#features)  
2. [Tech Stack](#tech-stack)  
3. [Getting Started](#getting-started)  
   - [Prerequisites](#prerequisites)  
   - [Installation](#installation)  
   - [Environment Variables](#environment-variables)  
   - [Running Locally](#running-locally)  
4. [Usage](#usage)  
5. [Project Structure](#project-structure)  
6. [Contributing](#contributing)  
7. [License](#license)  
8. [Author](#author)  

---

## Features

- Generate images using AI from user-supplied text prompts  
- Clean, responsive UI with interactive feedback  
- State management & custom React hooks  
- Integration with GPT-4 Image Generation API  
- Tailwind CSS styling for modern UI  

---

## Tech Stack

- **Next.js** — React framework for hybrid static & server rendering  
- **TypeScript** — static typing  
- **Tailwind CSS** — utility-first styling  
- **React Hooks** — for state & side effects  
- **GPT-4 Image Generation API** — backend AI integration  

---

## Getting Started

### Prerequisites

You’ll need:

- Node.js (v16+ recommended)  
- npm or yarn  
- Access / API keys to the GPT-4 Image Generation service  

### Installation

```bash
# Clone the repo
git clone https://github.com/Aalphakeem-Adroit/alx-project-0x05-setup.git

cd alx-project-0x05-setup

# Install dependencies (choose npm or yarn)
npm install
# or
yarn install
````

### Environment Variables

Create a `.env.local` file in the root and add:

```
GPT4_API_KEY=your_api_key_here
NEXT_PUBLIC_API_BASE_URL=https://api.example.com
# add any other required env variables...
```

Be sure **not** to commit `.env.local`.

### Running Locally

```bash
# Development mode
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

For a production build:

```bash
npm run build
npm run start
# or with yarn
yarn build
yarn start
```

---

## Usage

Once the app is running:

1. Enter a descriptive text prompt in the input area
2. Submit the prompt
3. The backend calls the GPT-4 API to generate an image
4. The image is displayed in the UI

> You can expand on this with screenshots or gif animations to show the flow.

---

## Project Structure

Here’s a simplified directory view:

```
/
├── public/                # static assets  
├── src/
│   ├── components/        # React components  
│   ├── hooks/             # custom hooks  
│   ├── pages/             # Next.js pages & API routes  
│   ├── styles/            # global + Tailwind configs  
│   └── utils/              # helper functions  
├── .env.local              # local env vars (not committed)  
├── next.config.js          # Next.js config  
├── tsconfig.json           # TypeScript config  
├── package.json  
└── LICENSE  
```

You can adjust this to exactly reflect your folder names.

---

## Contributing

Contributions are welcome! To contribute:

1. Fork this repository
2. Create your feature branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -m "Add some feature"`
4. Push to your branch: `git push origin feature/YourFeature`
5. Open a Pull Request

Please ensure code style consistency and include tests where applicable.

---

## License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## Author

**Busari Akeem Tunde**
GitHub: [Aalphakeem-Adroit](https://github.com/Aalphakeem-Adroit)

---

> *“The best way to predict the future is to create it.”*