
# Test-CybellaAI Frontend

This is the **frontend** portion of the CybellaAI project, built using **React + Vite**. It interfaces with the backend for real-time emotion detection using facial and voice data.

---

## Clone the Repository

```bash
git clone https://github.com/hartonoosu/Final-Cybella.git
cd Final-Cybella
```

---

## Prerequisites

Ensure you have the following installed:

* **Node.js (v18 or above)**
* **npm (Node Package Manager)**

Download Node.js from: [https://nodejs.org/en/download](https://nodejs.org/en/download)

After installation, verify in your terminal:

```bash
node -v
npm -v
```

If the terminal does not recognize these commands, add Node.js to your system path:

1. Press `Windows + R`, type `sysdm.cpl`, and hit Enter.
2. Go to the **Advanced** tab → Click **Environment Variables**.
3. Under **System Variables**, find `Path` → Click **Edit**.
4. Ensure this path is listed (add if missing):

```bash
C:\Program Files\nodejs\
```

---

## Install Netlify CLI

Netlify CLI is required to serve the frontend locally using the Vite dev server.

Install it globally:

```bash
npm install -g netlify-cli
```

Verify the installation:

```bash
netlify --version
```

---

## Run the Frontend Locally

1. Open your terminal and navigate to the project root:

```bash
cd Test-CybellaAI-main
```

2. Start the Netlify development server:

```bash
npx netlify dev
```

3. When prompted, select:

```
[Vite] 'npm run dev'
```

This will launch the frontend at a local development URL (typically `http://localhost:8888` or similar).

---




# Speech Emotion Detection

Make sure you have *Python 3.11*

Go to https://www.python.org/downloads/release/python-3110/ and scroll down to download "Windows installer (64-bit)".

```bash
python --version
```

Press "Windows Logo + R" and search ```bash sysdm.cpl```. Select Advanced on the bar and then select Environment Variable. In the System Variables, select Path and then click Edit. Now add the new path 

```bash
C:\Users\pmant\AppData\Local\Programs\Python\Python310\
C:\Users\pmant\AppData\Local\Programs\Python\Python310\Scripts\
```

Replace `"yourusername"` and `"your-repo-name"` accordingly.

---

