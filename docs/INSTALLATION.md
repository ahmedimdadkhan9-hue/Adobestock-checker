# Installation Guide

## Prerequisites

### 1. LM Studio
- Download: https://lmstudio.ai
- Size: 500MB + 5-10GB (model)
- Supported: Windows, Mac, Linux

### 2. Node.js
- Download: https://nodejs.org
- Version: 14+ or higher

### 3. System Requirements
- RAM: 4GB minimum
- Disk: 15GB+

## Installation Steps

### Step 1: Clone Repository
```bash
git clone https://github.com/YOUR-USERNAME/adobe-stock-checker-lm.git
cd adobe-stock-checker-lm
```

### Step 2: Install Dependencies
```bash
npm install
```

### Step 3: Start LM Studio
1. Open LM Studio app
2. Search model (llama-2, mistral)
3. Download model
4. Load model
5. Start Local Server (localhost:1234)

### Step 4: Run Application
```bash
npm start
```

Open: http://localhost:3000

### Step 5: Analyze Images!
1. Upload image
2. Click "Analyze"
3. Get results!

## Troubleshooting

### "LM Studio not running"
- Make sure LM Studio app is open
- Start Local Server
- Check port 1234

### "Cannot find module 'express'"
```bash
npm install
```

### Port Already Used
```bash
PORT=3001 npm start
```

---

Done! Happy analyzing! 🎯
