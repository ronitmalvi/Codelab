# Codelab

Codelab is a real-time code collaboration tool that allows multiple users to work on the same codebase simultaneously. It features syntax highlighting, auto-suggestions, seamless file editing, saving, and downloading. Additionally, it includes an integrated group chat for easy communication.

## Features

- Real-time code collaboration
- Syntax highlighting
- Auto-suggestions
- Seamless file editing, saving, and downloading
- Integrated group chat
- Drawing editor for collaborative sketches
- File structure view
- Code execution support

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/<your_username>/Codelab.git
    cd Codelab
    ```

2. Install dependencies for the client:

    ```sh
    cd client
    npm install
    ```

3. Install dependencies for the server:

    ```sh
    cd ../server
    npm install
    ```

### Running the Application

1. Start the server:

    ```sh
    cd server
    npm run dev
    ```

2. Start the client:

    ```sh
    cd ../client
    npm run dev
    ```

3. Open your browser and navigate to .

## Project Structure
Codelab/
├── client/
│   ├── public/
│   │   ├── index.html
│   │   └── ...
│   ├── src/
│   │   ├── assets/
│   │   │   └── ...
│   │   ├── components/
│   │   │   ├── Editor/
│   │   │   │   ├── Editor.js
│   │   │   │   └── ...
│   │   │   ├── Chat/
│   │   │   │   ├── Chat.js
│   │   │   │   └── ...
│   │   │   ├── FileTree/
│   │   │   │   ├── FileTree.js
│   │   │   │   └── ...
│   │   │   └── ...
│   │   ├── contexts/
│   │   │   ├── AuthContext.js
│   │   │   └── ...
│   │   ├── hooks/
│   │   │   └── ...
│   │   ├── pages/
│   │   │   ├── Home.js
│   │   │   ├── Login.js
│   │   │   ├── Register.js
│   │   │   └── ...
│   │   ├── services/
│   │   │   ├── api.js
│   │   │   └── ...
│   │   ├── styles/
│   │   │   └── ...
│   │   ├── utils/
│   │   │   └── ...
│   │   ├── App.js
│   │   ├── index.js
│   │   └── ...
│   ├── .env
│   ├── .eslintrc.cjs
│   ├── .gitignore
│   ├── .prettierrc.json
│   ├── package.json
│   ├── postcss.config.cts
│   ├── tailwind.config.ts
│   ├── tsconfig.json
│   ├── tsconfig.node.json
│   ├── vite.config.mts
│   └── vercel.json
├── server/
│   ├── controllers/
│   │   ├── authController.js
│   │   ├── fileController.js
│   │   ├── chatController.js
│   │   └── ...
│   ├── models/
│   │   ├── User.js
│   │   ├── File.js
│   │   ├── Message.js
│   │   └── ...
│   ├── routes/
│   │   ├── authRoutes.js
│   │   ├── fileRoutes.js
│   │   ├── chatRoutes.js
│   │   └── ...
│   ├── services/
│   │   ├── authService.js
│   │   ├── fileService.js
│   │   ├── chatService.js
│   │   └── ...
│   ├── utils/
│   │   ├── db.js
│   │   ├── logger.js
│   │   └── ...
│   ├── .env
│   ├── .gitignore
│   ├── package.json
│   ├── server.js
│   └── tsconfig.json
├── .gitignore
├── CONTRIBUTING.md
├── LICENSE
└── README.md


## License

This project is licensed under the MIT License - see the [LICENSE](http://_vscodecontentref_/2) file for details.

## Acknowledgements

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Socket.IO](https://socket.io/)
- [CodeMirror](https://codemirror.net/)
