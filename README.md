# Digit Guesser

**Machine learning from the browser; served from the Internet Computer Blockchain.**

## 📚 Description

Digit Guesser is a web application that demonstrates machine learning inference taking place directly in the browser. It uses a Support Vector Machine (SVM) classifier to predict hand-drawn digits. The application is built with Vue.js and leverages Pyodide to run Python code, including scikit-learn, in the browser using WebAssembly. The application is served directly from the Internet Computer Blockchain.

## ✨ Features

- Draw digits using an interactive canvas
- Real-time prediction of drawn digits using a pre-trained SVM model
- Client-side machine learning powered by Pyodide
- Served directly from the Internet Computer Blockchain

## 🛠️ Tech Stack

- **Frontend**: Vue.js, JavaScript
- **Machine Learning**: Python, scikit-learn, scikit-image
- **In-Browser Python**: Pyodide

## 🌟 Live Demo

Experience Digit Guesser in action:

**[https://avtg3-4iaaa-aaaal-ajqhq-cai.icp0.io/](https://avtg3-4iaaa-aaaal-ajqhq-cai.icp0.io/)**

## 🏗️ Local Development

To set up the project locally:

1. Clone the repository
2. Install dependencies:

   ```bash
   pnpm install
   ```

3. Compile and hot-reload for development:

   ```bash
   pnpm run serve
   ```

4. Compile and minify for production:

   ```bash
   pnpm run build
   ```

## 🧠 Machine Learning Model

The SVM classifier used in this project is trained on the MNIST dataset. For details on how the model was trained and exported, see the [train_model.ipynb](train_model.ipynb) notebook.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

For questions or feedback, please reach out:

- Email: [crabtr26@proton.me](mailto:crabtr26@proton.me)
- LinkedIn: [Jacob Crabtree](https://www.linkedin.com/in/jacob-crabtree-7ab72610a/)
- Twitter: [@crabtr26](https://x.com/crabtr26)

## 🙏 Acknowledgements

- [Pyodide](https://pyodide.org/en/stable/) for enabling Python in the browser
- [scikit-learn](https://scikit-learn.org/) for the machine learning algorithms
- [Juno](https://juno.build) for providing the hosting and development platform
- [Internet Computer](https://internetcomputer.org) for the underlying blockchain infrastructure
