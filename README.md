# ask-template

A template for creating an Ask! contract project.

## Usage

- Build the template contract

```bash
yarn build flipper.ts
```

- Build the template contract and print transform information

```bash
yarn debug flipper.ts
```

## Project Structure

The main `Ask!` project structure is as follows:

```log
ask-template
├── asconfig.json               (assemblyscript config)
├── askconfig.json              (ask-lang config)
├── build                       (build targets, configurable, see asconfig.json and askconfig.json)
│   ├── false
│   ├── flipper.optimized.wasm  (Ask! contract wasm binary)
│   ├── flipper.optimized.wat   (Ask! contract wasm text)
│   └── metadata.json           (Ask! contract metadata)
├── flipper.ts                  (Ask! contract code)
├── index.d.ts                  (typescript definition file, used for syntax and code hinting)
├── LICENSE
├── node_modules
├── package.json                (npm package config)
├── README.md
├── tsconfig.json               (typescript config)
└── yarn.lock
```

## License

[MIT](./LICENSE)
