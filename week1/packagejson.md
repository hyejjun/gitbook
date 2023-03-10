```javascript
{
  "name": "react-demo",
  "version": "1.0.0",
  "description": "React Application Demo",
  "source": "./index.html",
  "scripts": {
    "start": "parcel --port 8080",
    "build": "parcel build",
    "check": "tsc --noEmit",
    "lint": "eslint --fix --ext .js,.jsx,.ts,.tsx .",
    "test": "jest",
    "coverage": "jest --coverage --coverage-reporters html",
    "watch:test": "jest --watchAll"
  },
  "keywords": [],
  "author": "hyejjun",
  "license": "ISC",
  "devDependencies": {
    "@swc/core": "^1.3.30",
    "@swc/jest": "^0.2.24",
    "@testing-library/jest-dom": "^5.16.5",
    "@testing-library/react": "^13.4.0",
    "@types/jest": "^29.4.0",
    "@types/react": "^18.0.27",
    "@types/react-dom": "^18.0.10",
    "@typescript-eslint/eslint-plugin": "^5.49.0",
    "@typescript-eslint/parser": "^5.49.0",
    "eslint": "^8.33.0",
    "eslint-config-xo": "^0.43.1",
    "eslint-config-xo-typescript": "^0.55.1",
    "eslint-plugin-react": "^7.32.2",
    "jest": "^29.4.1",
    "jest-environment-jsdom": "^29.4.1",
    "parcel": "^2.8.3",
    "process": "^0.11.10",
    "typescript": "^4.9.4"
  },
  "dependencies": {
    "react": "^18.2.0",
    "react-dom": "^18.2.0"
  }
}

```
#
[TypeScript + React + Jest + ESLint + Parcel 개발 환경 세팅](setting.md)