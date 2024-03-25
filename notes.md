### `tsc` or `tsc -b` (build)

- The `-b` flag also enables incremental compilation, which means that TypeScript will only recompile files that have changed or files that depend on files that have changed, making the compilation process faster for large projects
<hr>

### `"prestart": "pnpm build",`

- The prestart script is a special script in npm that gets automatically run before the start script when you run npm start.
- This is a feature of npm and yarn, but pnpm does not support these automatic pre and post scripts.
- In pnpm, if you want to run a command before start, you would have to explicitly call it.
<hr>

[For More](https://www.totaltypescript.com/typescript-and-node)
