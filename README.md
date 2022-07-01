# VSCode TypeScript Snippet

## Support Language
- TypeScript React
- TypeScript (TODO)

## Snippets
### TypeScript React
Trigger | Content
--- | ---
`irfc` | Create React Component with Interface
`trfc` | Create React Component with Type Alias
`rfctx` | Create React Context
`useState` | Create useState
`tuseState` | Create useState with Type
`useEffect` | Create useEffect
`tstate` | Create useReducer State Type and State
`taction` | Create useReducer Action Type
`reducer` | Create useReducer Reducer
`useReducer` | Create useReducer
`imr` | Import React
`exp` | Import and export default
`interface` | Create Interface
`interfaceGeneric` | Create Generic Interface
`type` | Create Type Alias
`typeObject` | Create Object Type Alias
`typeGeneric` | Create Generic Type Alias
`typeFunction` | Create Function Type Alias

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

