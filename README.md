# Tauri + React

This template should help get you started developing with Tauri and React in Vite.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)


## Build Examples Using pnpm (you can change it to your favorite node package manager)
Install dependencies
```
pnpm i
```

Run development live reload version
```
pnpm run tauri dev
```

Multiple build options 
```
pnpm run tauri build --no-bundle
```

```
pnpm run tauri build --bundles=deb
```

```
pnpm run tauri build --bundles=deb,appimage
```

