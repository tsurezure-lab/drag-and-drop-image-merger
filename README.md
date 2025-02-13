# つながりん (Tsunaga-rin) - Image Merger

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

**つながりん (Tsunaga-rin)** is a simple, drag-and-drop web application that allows you to combine multiple images (PNG or JPEG) into a single image, either vertically or horizontally. The name "Tsunaga-rin" comes from the Japanese word "tsunageru" (繋げる), which means "to connect" or "to link," reflecting the app's function of connecting images.

## Features

*   **Drag and Drop:** Easily add images by dragging and dropping them onto the designated area.  You can also click the drop area to select images using a file dialog.
*   **Paste from Clipboard:** Paste images directly from your clipboard.
*   **Reordering:** Rearrange the order of images using drag-and-drop before merging.
*   **Vertical and Horizontal Merging:** Choose to combine images vertically or horizontally.
*   **Preview:** See a preview of the combined image before downloading. The preview updates automatically when images are added, removed, or reordered.
*   **Progress Bar:** A progress bar indicates the image loading progress.
*   **Download:** Download the combined image as a PNG file.
*   **Responsive Design:** Works well on various screen sizes.
*  **File Name Handling:**  Long file names in the image list are truncated for better display, with the full name shown on hover (tooltip).
* **Image Resizing:** Images are automatically resized during the merging process to ensure consistent width (for vertical merging) or height (for horizontal merging).

## How to Use

![アプリのスクリーンショット](/images/screenshot.png)

1.  **Open `index.html` in your web browser.** (No server required!)
2.  **Add images:**
    *   **Drag and drop** PNG or JPEG images onto the "ここに結合したい画像をドロップ" area.
    *   **Click** the drop area to select files using the file dialog.
    *    **Paste** images from the clipboard (Ctrl+V or Cmd+V).
3.  **Reorder images** by dragging them within the image list.
4.  **Select the merge direction:** "縦に結合" (Vertically) or "横に結合" (Horizontally).
5.  **Click the "結合画像をダウンロード" button** to download the merged image.

## Technologies Used

*   HTML
*   CSS (with Google Fonts - Zen Maru Gothic)
*   JavaScript (no external libraries)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. (You should create a `LICENSE` file with the MIT License text.)

## Author

tsurezure_lab

---

# つながりん (Tsunaga-rin) - 画像結合ツール

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

**つながりん (Tsunaga-rin)** は、ドラッグ＆ドロップ操作で複数の画像（PNGまたはJPEG）を縦または横に結合し、1つの画像にすることができるシンプルなWebアプリケーションです。「つながりん」という名前は、日本語の「繋げる（つなげる）」という言葉に由来しており、画像を繋げるというアプリの機能を反映しています。

## 特徴

*   **ドラッグ＆ドロップ:** 指定されたエリアに画像をドラッグ＆ドロップすることで簡単に追加できます。ドロップエリアをクリックしてファイルダイアログから画像を選択することも可能です。
*   **クリップボードから貼り付け:** クリップボードから直接画像を貼り付けることができます。
*   **並べ替え:** 結合前にドラッグ＆ドロップで画像の順序を並べ替えることができます。
*   **縦/横結合:** 画像を縦または横に結合することを選択できます。
*   **プレビュー:** ダウンロード前に結合された画像のプレビューを確認できます。プレビューは、画像が追加、削除、または並べ替えられると自動的に更新されます。
*   **プログレスバー:** 画像の読み込み進捗状況を示すプログレスバーが表示されます。
*   **ダウンロード:** 結合された画像をPNGファイルとしてダウンロードできます。
*   **レスポンシブデザイン:** 様々な画面サイズで適切に表示されます。
*   **ファイル名の処理:**  画像リスト内の長いファイル名は、表示を改善するために省略され、ホバー時（ツールチップ）に完全な名前が表示されます。
*   **画像のリサイズ:**  結合処理中に画像は自動的にリサイズされ、幅（縦結合の場合）または高さ（横結合の場合）が均一になるように調整されます。

## 使い方

![アプリのスクリーンショット](/images/screenshot.png)

1.  **Webブラウザで `index.html` を開きます。** (サーバーは不要です！)
2.  **画像を追加:**
    *   **ドラッグ＆ドロップ:** PNGまたはJPEG画像を「ここに結合したい画像をドロップ」エリアにドラッグ＆ドロップします。
    *   **クリック:** ドロップエリアをクリックして、ファイルダイアログを使用してファイルを選択します。
    *   **貼り付け:** クリップボードから画像を貼り付けます (Ctrl+V または Cmd+V)。
3.  画像リスト内で画像をドラッグして **画像の順序を並べ替え** ます。
4.  **結合方向を選択します:** 「縦に結合」または「横に結合」。
5.  **「結合画像をダウンロード」ボタンをクリック** して、結合された画像をダウンロードします。

## 使用技術

*   HTML
*   CSS (Google Fonts - Zen Maru Gothic を使用)
*   JavaScript (外部ライブラリ不使用)

## ライセンス

このプロジェクトはMITライセンスの下で公開されています。詳細は [LICENSE](LICENSE) ファイルをご覧ください。(MITライセンスのテキストを記載した `LICENSE` ファイルを作成する必要があります。)

## 作者

tsurezure_lab