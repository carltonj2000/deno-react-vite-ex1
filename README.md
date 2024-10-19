# Deno React Vite Example 1

Failed to compile as a single executable because you need to include the
`public` and `dist` directories which is not possible as of 10/18/24.
If it is possible I could not find out how.

At present I can build, serve and run the executable.

## Code History

The code in this repository is based on the following.

- https://docs.deno.com/runtime/tutorials/how_to_with_npm/react/
- https://github.com/denoland/tutorial-with-react

## Creation History

```bash
deno run -A npm:create-vite@latest
cd deno-react-vite-ex1
deno install
deno task run
deno add jsr:@oak/oak jsr:@tajpouria/cors
deno add npm:react-router-dom
```
