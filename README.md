{
  "name": "hardware-repairing-store",
  "version": "1.0.0",
  "private": true,
  "scripts": {
    "dev": "node ace serve --watch",
    "build": "node ace build --production",
    "start": "ENV_SILENT=true node server.js",
    "test": "node ace test",
    "lint": "eslint . --ext=.ts",
    "format": "prettier --write ."
  },
  "eslintConfig": {
    "extends": [
      "plugin:adonis/typescriptApp",
      "prettier"
    ],
    "plugins": [
      "prettier"
    ],
    "rules": {
      "prettier/prettier": [
        "error"
      ]
    }
  },
  "eslintIgnore": [
    "build"
  ],
  "prettier": {
    "trailingComma": "es5",
    "semi": false,
    "singleQuote": true,
    "useTabs": false,
    "quoteProps": "consistent",
    "bracketSpacing": true,
    "arrowParens": "always",
    "printWidth": 100
  },
  "devDependencies": {
    "@adonisjs/assembler": "^5.9.5",
    "@japa/preset-adonis": "^1.2.0",
    "@japa/runner": "^2.5.1",
    "@types/proxy-addr": "^2.0.0",
    "@types/source-map-support": "^0.5.6",
    "adonis-preset-ts": "^2.1.0",
    "eslint": "^8.44.0",
    "eslint-config-prettier": "^8.8.0",
    "eslint-plugin-adonis": "^2.1.1",
    "eslint-plugin-prettier": "^4.2.1",
    "pino-pretty": "^10.0.1",
    "prettier": "^3.0.0",
    "typescript": "~4.6",
    "youch": "^3.2.3",
    "youch-terminal": "^2.2.2"
  },
  "dependencies": {
    "@adonisjs/assembler": "^5.9.5",
    "@adonisjs/auth": "^5.1.1",
    "@adonisjs/core": "^5.8.0",
    "@adonisjs/lucid": "^18.4.0",
    "@adonisjs/repl": "^3.1.0",
    "luxon": "^3.3.0",
    "mysql2": "^3.5.0",
    "proxy-addr": "^2.0.7",
    "reflect-metadata": "^0.1.13",
    "source-map-support": "^0.5.21"
  }
}