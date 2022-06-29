# VSCode TypeScript Snippet

## Support Language
- TypeScript React
- TypeScript (TODO)

## Snippets

Trigger | Content
--- | ---
`irfc` | Create React Component with Interface
`trfc` | Create React Component with Type Alias
`rfctx` | Create React Context
`useState` | Create useState
`tuseState` | Create useState with Type
`useEffect` | Create useEffect

## Exmaple

- `irfc`: Create React Component with Interface

```tsx
// Button.tsx

interface ButtonProps {

}

export default function Button({ }: ButtonProps) {
  return <div>Button</div>
}
```

- `trfc`: Create React Component with Type Alias


```tsx
// Button.tsx

type ButtonProps = {

}

export default function Button({  }: ButtonProps) {
  return <div>Button</div>
}
```

