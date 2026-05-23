# AnyFlip Downloader (Desktop & Android)

A fast, lightweight, and modern desktop & mobile application designed to securely and efficiently download AnyFlip books as high-quality, lossless PDF documents.

## 📱 New: Android Pro Version!
We have officially released the **Android Pro** version (`com.funkydonke.anyflipdownloader`), featuring:
- **Batch Processing**: Paste dozens of links at once and let the engine handle them automatically.
- **Smart Queue & History**: The text input intelligently removes successfully downloaded URLs. If you stop halfway, your remaining queue is automatically saved and remembered!
- **Active Job Cancellation**: Safely stop an active batch download with the Stop button. The deep Coroutine cancellation completely aborts generation and purges half-finished junk files to protect your storage.
- **Dynamic Theme Engine**: A seamless Dark/Light mode toggle for eye comfort.
- **Lossless Quality PDF Building**: Native rendering using Android's Bitmap and PdfDocument classes.

You can download the compiled APK from the [Releases](#) section!

## ✨ New in v2.0
* **Advanced Session History:** Every batch of links you paste is saved into a permanent history grouped by the time you started. 
* **Pause & Resume:** Stop a download at any time without losing your progress. You can easily inject full batches back into your queue and pick up exactly where you left off.
* **Network Dropout Recovery:** If your internet disconnects, the downloader instantly pauses your active downloads and saves them to history, waiting for you to resume later!
* **Dynamic Color Queues:** As files download, they are tagged with a status (Pending, Paused, Downloading). Fully downloaded items automatically turn Gray in your URL box!
* **Live Title Injection:** The app dynamically fetches the true title of the PDF from the website and seamlessly injects it into your URL box as soon as it's discovered.
* **Smart Deduplication:** If you download multiple books with the identical title, it automatically saves them safely as `_1`, `_2`, so you never overwrite your files.
* **Serial Numbers:** Each file in your list gets its own tracked `[1]`, `[2]` ID for easy monitoring.

## ⚡ Core Features
* **Dual Engines:** Choose **High Quality** for perfect prints or **Compressed** for smaller file sizes.
* **Batch Downloads:** Paste as many URLs as you want into the massive text box queue.
* **Custom File Names:** Type your URL, press Space, and type the name. *(Example: `https://anyflip... MyBook`)*
* **Format Choice:** Keep the raw images, build a PDF, or do both!
* **Speed Control:** Increase threads to download faster (⚠️ *Keep it at 5 or below to avoid getting blocked by AnyFlip!*)
* **Clear Downloaded:** Click a single button to wipe all the finished (gray) links from your list, leaving only what you still need.

## 🖱️ How to Use
1. **Choose a Folder:** Select where to save your files.
2. **Set Options:** Pick your quality, speed, and output format.
3. **Paste Links:** Drop your AnyFlip links into the box.
4. **Click Start!** The text box will color-code your progress, and you can view full logs below. Use the **View History** button to restore past sessions or resume incomplete batches!

*(Note: The application may be encrypted to protect the source code. If your antivirus flags it, it is a false positive!)*
