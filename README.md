~This is an example of a minimal Vite project where HMR doesn't appear to be working in Chrome.~

Edit: Got it working! Turns out you need to use `@vitejs/plugin-react` for HMR to work in React apps. Makes sense.

### Running the demo

```
yarn run start:dev
```

### Screencast

This screencast shows how a full page refresh happens when a TSX file is edited:

![Screencast](https://github.com/erikpukinskis/vite-hrm-test/blob/main/no-hmr.gif?raw=true)