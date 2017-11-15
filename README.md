# Vatron
Vatron is an open source, fast, and accesable [VATSIM](https://www.vatsim.net/) radar client built with [Electron](https://electron.atom.io/).

## Installation  
```bash
# Clone the repo
https://gitlab.com/andrewward2001/vatron.git
cd vatron
# Install dependencies:
```

Yarn is recommended:  
```bash
yarn
```  
npm:  
```bash
npm install
```

## Run
Yarn:  
```bash
yarn start
```  
npm:  
```bash
npm start
```

## Build
I've taken care to make sure that building is as easy as possible on whatever platform you're using  
Please see [electron-builder](https://www.electron.build/) documentation for extra information on building Vatron

### macOS
Yarn:  
```bash
yarn run build-darwin
```  
npm:  
```bash
npm run build-win64
```

### Windows
I found that Windows builds were only possible via Yarn  
```bash
yarn run build-win64
```