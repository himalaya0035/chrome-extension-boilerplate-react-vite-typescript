# React Chrome Extension Boilerplate with Vite and TypeScript

![GitHub license](https://img.shields.io/github/license/himalaya0035/chrome-extension-boilerplate-react-vite-typescript)
![React](https://img.shields.io/badge/react-18.x-blue)
![TypeScript](https://img.shields.io/badge/typescript-5.x-blue)
![Tailwind CSS](https://img.shields.io/badge/tailwindcss-3.x-blue)
![Vite](https://img.shields.io/badge/vite-4.x-blue)

This repository aims to provide an easy-to-use and minimilastic foundation for developing Chrome extensions using modern web technologies, including React for building the user interface, TypeScript for type-safe development, Tailwind CSS for effortless styling, and Vite as the module bundler for speedy development.

The focus is on providing a minimalistic and straightforward boilerplate for fast Chrome extension development, without unnecessary complexities.

## About

As a developer, I struggled to find a comprehensive and straightforward resource to kickstart building Chrome extensions with React, Vite, and TypeScript. To bridge this gap, I decided to build it on my own. This project is born out of the frustration I faced and my desire to make the development process easier for fellow developers.

 Explore this minimalistic boilerplate that includes the necessary tools for Chrome extension development while keeping things simple and approachable.


## Features

- 🚀 Fast development with Vite's hot module replacement.
- ⚙️ Dynamic manifest generation using the CRXJS vite plugin.
- ⚛️ React-based user interface for the extension's popup, options page, and other components.
- 🔧 TypeScript configuration for type-safe coding.
- 🎨 Integrated with Tailwind CSS for flexible styling (Feel free to remove tailwind, if not required).
- ⚡️ **Out-of-the-box support for background scripts, options pages, and content scripts. Customize them to fit your needs without the hassle of manual setup. Just start developing right away!**

## Prerequisites

Before you begin, make sure you have the following installed:

- Node.js (recommended version 16.x or higher)
- npm (comes with Node.js)

## Getting Started

Follow these steps to get the boilerplate code up and running:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/himalaya0035/chrome-extension-boilerplate-react-vite-typescript
    ```

2. **Navigate to the project folder:**

    ```bash
    cd chrome-extension-boilerplate-react-vite-typescript
    ```

3. **Install dependencies:**

    ```bash
    npm install
    ```

4. **Run the development server:**

    ```bash
    npm run dev
    ```

    This command will start the development server using Vite, enabling hot module replacement and allowing you to see your changes in real.
5. **Load the extension in Chrome:**

    - Open the Chrome browser.
    - Navigate to `chrome://extensions/`.
    - Turn on the "Developer mode" toggle in the top-right corner.
    - Click the "Load unpacked" button and select the `dist` folder inside your project directory.

6. **Start Developing:**

    - The popup UI can be found in the `src/App.tsx` directory.
    - Customize the manifest template in `src/manifest.json` and let CRXJS handle the dynamic manifest generation.
    - The support for background scripts, options page, content scripts is already configured. Customise them in their respective folder.

7. **Build for Production:**

    When you're ready to publish your extension, create a production build by running:

    ```bash
    npm run build
    ```

    The optimized files will be available in the `dist` folder. You can then package this folder to distribute your extension.

## Contributing

Contributions are welcome! If you encounter any issues or have ideas for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Support

⭐️ If you find this boilerplate helpful, consider giving it a star on [GitHub](https://github.com/himalaya0035/chrome-extension-boilerplate-react-vite-typescript).

---

Happy coding! If you have any questions or need further assistance, please don't hesitate to reach out.

**Disclaimer:** This project was created by [Himalaya Gupta](https://github.com/himalaya0035/), for the community, to address the lack of comprehensive resources for building Chrome extensions with React, Vite, TypeScript, and Tailwind CSS. It is not officially endorsed by any of the mentioned technologies or organizations.

---

