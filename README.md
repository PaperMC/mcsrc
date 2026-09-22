# [https://mcsrc.dev/](https://mcsrc.dev/)

Note: This project is not affiliated with Mojang or Microsoft in any way. It does NOT redistribute any Minecraft code or compiled bytecode. The minecraft jar is downloaded directly from Mojang's servers to your browser.

## How to build locally

First you must build the java project using Gradle.

- `cd java`
- `./gradlew build`

Then you can run the web app:

- `nvm use` (or ensure you have the correct Node version, see `.nvmrc`)
- `npm install`
- `npm run dev`

## Credits

Libraries and tools used:

- Decompiler: [Vineflower](https://github.com/Vineflower/vineflower)
- Wasm compilation of Vineflower: [@run-slicer/vf](https://www.npmjs.com/package/@run-slicer/vf)

`./src/ui/intellij-icons/` includes icons from [IntelliJ Platform](https://intellij-icons.jetbrains.design), Licensed Apache 2.0.

[![CI powered by namespace badge](https://papermc.io/assets/misc/namespace-oss-badge.svg?project=mcsrc)](https://namespace.so/github-actions/?utm_source=oss&utm_campaign=papermc)
