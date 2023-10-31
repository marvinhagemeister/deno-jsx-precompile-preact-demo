# Deno JSX precompile preact demo

This shows the new precompile JSX transform working with Preact. It uses vendored versions of these open PRs:

- https://github.com/preactjs/preact/pull/4177
- https://github.com/preactjs/preact-render-to-string/pull/322

## How to run this demo

1. Clone https://github.com/denoland/deno
2. Checkout this PR https://github.com/denoland/deno/pull/20962
3. cd into the cloned folder and run `cargo build`
4. Run `cargo run -- run <path-to-demo-repo>/main.tsx`
