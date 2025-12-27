# Convertly 🚀

**Convertly** is a modern, web-based file conversion tool built with
**Next.js** that allows users to convert images, audio, and video files
directly in the browser.

All conversions run **locally on the user's device** using
WebAssembly-powered FFmpeg --- meaning your files never leave your
computer.

------------------------------------------------------------------------

## ✨ Features

-   🔄 **Multimedia Conversion**\
    Convert images, audio, and video files to multiple formats.

-   🖥️ **Client-Side Processing**\
    All conversions are performed locally in the browser using
    `@ffmpeg/ffmpeg`.

-   🔐 **Privacy First**\
    No uploads, no servers, no tracking --- your files stay on your
    device.

-   ⚡ **Fast & Responsive UI**\
    Built with React, Tailwind CSS, and Radix UI components.

-   📦 **Batch Conversion**\
    Upload and convert multiple files at once.

-   ⬇️ **One-click Download**\
    Download individual files or all converted files at once.

------------------------------------------------------------------------

## 🛠️ Tech Stack

-   **Framework:** Next.js 14
-   **Language:** TypeScript
-   **UI:** Tailwind CSS, Radix UI
-   **File Handling:** react-dropzone
-   **Media Processing:** FFmpeg (WebAssembly)
-   **Icons:** lucide-react

------------------------------------------------------------------------

## ▶️ Running Locally

``` bash
git clone https://github.com/nysuri/File-converter.git
cd fileconverter
npm install
npm run dev
```

Open http://localhost:3000
