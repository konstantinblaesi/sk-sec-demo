### Global shared state security issue

### Demo

- Call http://localhost:5173/?user=John to create the global server side shared state to simulate logging in as John
- Now call http://localhost:5173/ as many times as you like and see John flash briefly on the UI

### Further resources

- https://github.com/sveltejs/kit/discussions/4339
- https://kit.svelte.dev/docs/state-management
- https://www.youtube.com/watch?v=EyDV5XLfagg
