# Elementary Plugin Renderer SSCCE

## Developing

Add `elem.key.pem` and `elem.pem` with your private key and certificate respectively.

Install dependencies:

```sh
npm install
```

Start the dev server:

```sh
npm run dev
```

## Error reproduction

The error can be reproduced with the following steps on macOS:

- Open the Elementary Dev Kit in a DAW
- Attach Safari for remote debugging
- Select the Start button
- Check the console for the error message which reads `Failed to reach the plugin backend. Are you running with the correct renderer?`