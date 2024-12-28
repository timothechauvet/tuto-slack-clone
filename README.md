## What I did

Tutorial from [Code With Antonio](https://www.youtube.com/watch?v=lXITA5MZIiI)

```sh
# Install bun
brew install oven-sh/bun/bun
# Init Next.Js -> Yes everywhere, except "import alias"
bunx create-next-app@latest tuto-slack-clone
bun next telemetry disable
# Install shadcn
bunx shadcn@latest init
# Test
bun run dev
# Import components
bunx shadcn@latest add button card input separator
bun add react-icons
```