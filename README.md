# Next.js useEffect setInterval Bug

This repository demonstrates a common bug encountered when using the `React.useEffect` hook with `setInterval` in Next.js applications. The counter in `MyComponent` does not update predictably because the `setInterval` callback doesn't trigger a re-render in the way we expect it to.