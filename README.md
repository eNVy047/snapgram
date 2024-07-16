# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list

- # 'npm run dev "
# Screenshot
![screencapture-localhost-5173-2024-07-16-22_30_54](https://github.com/user-attachments/assets/3c1f8168-a61b-4aec-bcca-dbc83a612424)

#git 
make .env.local ile
(
VITE_APPWRITE_PROJECT_ID='6584e3565d3da7967893'
VITE_APPWRITE_URL='https://cloud.appwrite.io/v1'
VITE_APPWRITE_STORAGE_ID='6585c558a26ffef76532'
VITE_APPWRITE_DATABASE_ID='6585c60a9e38f7b0b455'
VITE_APPWRITE_USER_COLLECTION_ID='6585c751caed1952fc4b'
VITE_APPWRITE_POST_COLLECTION_ID='6585c67a285de0edcc40'
VITE_APPWRITE_SAVES_COLLECTION_ID='6585c78a8dd4b2013b35'
)
