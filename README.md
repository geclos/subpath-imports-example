# Subpath imports example

This repo demonstrates how node's subpath imports do not work with next build. 

- `packages/ui` has a subpath imports declared
- go to `apps/web` and `pnpm build`
- ☝️ it fails
