# LojasGO! (Mobile frontend)

Welcome to the LojasGO! Mobile frontend repository

## Getting Started

These instructions will help you get a copy of the project up and running on your local machine.

### Prerequisites

- [Node.js + npm](https://nodejs.org/en/download/package-manager)
- [Android SDK Command Line Tools](https://developer.android.com/tools) or [Android Studio](https://developer.android.com/studio)
- [EAS CLI](https://docs.expo.dev/build/setup/#install-the-latest-eas-cli)

### Installing Dependencies

1. Clone the repository:

   ```bash
   # HTTPS
   git clone https://github.com/Geezgus/lojas-go-mobile.git

   # SSH
   git clone git@github.com:Geezgus/lojas-go-mobile.git

   # GitHub CLI
   gh repo clone Geezgus/lojas-go-mobile
   ```

2. Navigate to the project directory and install dependencies with locked versions:
   ```bash
   cd lojas-go-mobile
   npm ci
   ```

### Running the App

To start the development server:

```bash
npm run start --platform android
```

The web app will be available at `http://localhost:8081`

### Building and Publishing the Expo App

To build the Expo app for Android:

```bash
# To build as Android App Bundle (AAB)
eas build --platform android --profile production

# To build directly as Android Package Kit (APK)
eas build --platform android --profile preview
```

## License

This project is licensed under the MIT License - see below for details:

MIT License

Copyright (c) 2024 Duarte, Gustavo H. M.,

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
