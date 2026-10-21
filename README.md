# AI Sinhala Translator - Document Translation Interface

A pixel-perfect reverse engineered web application matching the AI PDF Document Translator interface using modern **HTML5 / PHP**, **Vanilla CSS**, and **JavaScript**.

---

## 🎨 Features & Design Match

- **Canvas Background**: Elegant isometric graph grid pattern (`32px` grid lines on subtle off-white `#f8fafc`).
- **Drag & Drop Upload Zone**:
  - Cloud outline with upload arrow icon in royal blue.
  - Dashed border (`2px dashed #cbd5e1`) with interactive hover and drag-active glow.
  - Format pill: `PDF files supported · Max 20MB`.
  - Quota and capacity indicators: `Remaining pages ⓘ : 600` and `Up to 3 parallel tasks ⓘ` with tooltip explanations.
- **Controls & Selection Bar**:
  - **Source Language**: Interactive selector with auto-detect and multi-language support (English, Sinhala, Tamil, etc.).
  - **Swap Button**: Circular blue exchange button with micro-animation.
  - **Target Language**: Interactive selector with Sinhala, English, Tamil, and more.
  - **Translation Style**:
    - **General**: Best for everyday documents, manuals, and general reports.
    - **Academic**: Best for papers, research reports, and course materials.
    - **Legal**: Best for contracts, terms, policies, and regulations.
    - **Business**: Best for business plans, emails, quotes, and operations or finance reports.
  - **Network Check**: Wi-Fi status button that pings the server and displays real-time latency feedback.
- **Action & Task Processing**:
  - **Start Translation Button**: Gradient/soft blue primary CTA with loading state and progress bar animation.
  - **Bottom Card**: Live translation task queue displaying processed documents, page usage, and PDF download buttons.

---

## 🚀 How to Run

### Option 1: Using PHP Server (Recommended)
You can run the application with the PHP CLI using:
```bash
php -S localhost:8085
```
Or with XAMPP's PHP:
```powershell
& "C:\xampp\php\php.exe" -S localhost:8085
```
Then navigate to: `http://localhost:8085`

### Option 2: Direct Browser Viewing (Static)
Double-click `index.html` to open it in any web browser without needing a server.
