# 🕵️‍♂️ Simple TypeScript Playground

`yarn` or `npm i` to install a few dependencies

`yarn start` or `npm start` to start debuging

## 🤖 Mechs

This simple app utilizes a combination of `tsc` in watch mode, `nodemon` to watch the compiled typescript, and `concurrently` to run the two processes in tandem.

`yarn start:ts` - will run the standalone TypeScript compiler in watch mode

`yarn start:js` - will run any complied js in the build folder. (you must first run `yarn start:ts`)

### 👩‍🚀 Happy hacking 🚀
