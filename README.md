# issue-15190-mre

https://github.com/sveltejs/kit/issues/15190

see `src/routes/+layout.svelte` and `src/routes/+page.svelte`, they have `export const ssr=false`. it should warn, it doesn't.