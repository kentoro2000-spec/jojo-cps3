# JoJo CPS-3 Browser Emulator — Cloudflare Pages

このフォルダは Cloudflare Pages の Direct Upload 用です。

## Upload

Cloudflare Dashboard → Workers & Pages → Create application → Get started → Drag and drop your files

このZIPをそのままアップロードして Deploy site を押してください。

## Important

- `index.html` と `_headers` はサイトのルートにあります。
- `_headers` は WebAssembly threads / SharedArrayBuffer 用の COOP / COEP を設定します。
- ゲームROMは含まれていません。ブラウザ上の「ROM ZIPを選択」から、手元の対応ROMセットを選択してください。
- ROMの権利・使用許諾については利用者自身で確認してください。
- このWeb版は `@wasm-gaming/fbneo-wasm` をCDNから読み込みます。初回起動時にはインターネット接続が必要です。
