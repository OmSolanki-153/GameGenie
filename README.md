

---

````markdown
# 🔮 GameGenie – AI Copilot for Game Development

**GameGenie** is an open-source, modular AI research project designed to empower game developers and technical artists with AI-assisted workflows. It includes tools for:

- ✨ **Text to 3D Model Generation**
- 🧱 **Text-Based Procedural Level Design**
- 💡 **Code Debugging & Assistance via VS Code Extension**

GameGenie explores how large language models (LLMs) can help automate and enhance tasks in game development using open-source tools and inference APIs like Groq.

---

## 🧩 Project Structure

The repository contains three key modules, each in a separate `.rar` file for ease of setup:

| Folder | Utility | Description |
|--------|---------|-------------|
| `TextGenerator.rar` | 🧠 Text-to-3D Model Generator | Converts simple text prompts into basic 3D models using the SHAP-E model (runs locally). |
| `VSCODE_Copilot.rar` | 💻 VS Code Copilot | A fully functional VS Code extension using Groq API to get code suggestions and completions. Supports multiple model selections. |
| `LevelGenerator.rar` | 🏗️ Procedural Level Generator | Generates 3D level geometry based on text commands using `Trimesh`. |

---

## 🚀 Setup Instructions

> ✅ **Note:** Each module is self-contained. You can extract and run them independently.

### 🔧 1. Setup for `TextGenerator` (Text to 3D)

**Requirements:**
- Python 3.10+
- PyTorch
- SHAP-E model dependencies

**Steps:**
```bash
cd TextGenerator
pip install -r requirements.txt
python app.py  # or the appropriate script to launch the model
````

Modify or input your prompt to see `.glb` or `.obj` 3D outputs generated locally.

---

### 💻 2. Setup for `VSCODE_Copilot` (Groq AI Assistant)

**Features:**

* Multi-model selection (LLaMA3, Mixtral, Gemma)
* Markdown formatting + syntax highlighting
* Fast inference via [Groq API](https://groq.com)

**Steps to Use:**

1. Extract `VSCODE_Copilot.rar`.
2. Open the folder in **Visual Studio Code**.
3. Run:

   ```bash
   npm install
   npm run watch
   ```
4. Press `F5` to launch the extension in the Extension Development Host.
5. Add your **Groq API key** in `extension.ts` file or via `.env`.

---

### 🧱 3. Setup for `LevelGenerator` (Text-Based Level Design)

**Requirements:**

* Python 3.9+
* Trimesh, NumPy, Matplotlib

**Steps:**

```bash
cd LevelGenerator
pip install -r requirements.txt
python level_generator.py
```

Prompts like `generate castle layout` or `simple maze` trigger custom level structures via hardcoded logic + geometry.

---

## 🌐 Open Source & Contribution

This project is completely **open-source** and available under the MIT License.
Feel free to:

* Fork it
* Improve each module
* Merge the system into a unified platform
* Fine-tune LLMs or integrate voice/UI inputs

> 💬 For suggestions, bugs, or improvements—open an issue or submit a pull request!

---

## 📌 Future Roadmap

* 🔄 Merge all modules into a single interactive web app
* 🔍 Add real-time 3D preview using Three.js
* 🧠 Implement fine-tuned LLMs using LoRA for 3D domain
* 🎮 Extend support for Unity & Unreal integration

---

## 🧑‍💻 Developed By

**Om Solanki**
AI & Game Development Researcher
[LinkedIn]([https://linkedin.com/](https://www.linkedin.com/in/om-solanki-651924218/)) • [Instagram]([https://instagram.com/](https://www.instagram.com/omsoul15/)) • [GitHub]([https://github.com/](https://github.com/OmSolanki-153))

---

## ⭐ Star This Repo

If you found this useful, please consider starring 🌟 the repo to support development!

```

---

```
