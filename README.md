# VSCode TypeScript Snippet

## Support Language
- TypeScript React
- TypeScript

## Snippets
### TypeScript React
Trigger | Content
--- | ---
`irfc→` | Create React Component with Interface
`irafc→` | Create Arrow Function React Component with Interface
`trfc→` | Create React Component with Type Alias
`trafc→` | Create Arrow Function React Component with Type Alias
`rfctx→` | Create React Context
`useState→` | Create useState
`tuseState→` | Create useState with Type
`useEffect→` | Create useEffect
`tstate→` | Create useReducer State Type and State
`taction→` | Create useReducer Action Type
`reducer→` | Create useReducer Reducer
`useReducer→` | Create useReducer
`imr→` | Import React
`exp→` | Import and export default
`dfas→` | Default As
`interface→` | Create Interface
`interfaceGeneric→` | Create Generic Interface
`type→` | Create Type Alias
`typeObject→` | Create Object Type Alias
`typeGeneric→` | Create Generic Type Alias
`typeFunction→` | Create Function Type Alias
`mappedType→` | Create Mapped Type
`asconst→` | Attach as const in object value
`MapType→` | Define Map Type
`newMap→` | Create Map Instance
`SetType→` | Define Set Type
`newSet→` | Create Set Instance
`Partial→` | Make all properties in Type optional.
`Required→` | Make all properties in Type required.
`Readonly→` | Make all properties in Type readonly.
`Record→` | Construct a type with a set of properties Keys of type Value.
`Pick→` | From Type, pick a set of properties whose keys are in the union Keys
`Exclude→` | Exclude from Type those types that are assignable to Union
`Omit→` | Construct a type with the properties of Type except for those in type Keys.
`Extract→` | Extract from Type those types that are assignable to Union
`NonNullable→` | Exclude null and undefined from Type
`Parameters→` | Obtain the parameters of a function type in a tuple
`ReturnType→` | Obtain the return type of a function type
`Uppercase→` | Convert string literal type to uppercase
`Lowercase→` | Convert string literal type to lowercase
`Capitalize→` | Convert first character of string literal type to uppercase
`Uncapitalize→` | Convert first character of string literal type to lowercase

## Exmaple

- `irfc→`: Create React Component with Interface

```tsx
// Button.tsx

interface ButtonProps {

}

export default function Button({ }: ButtonProps) {
  return <div>Button</div>
}
```

- `trfc→`: Create React Component with Type Alias


```tsx
// Button.tsx

type ButtonProps = {

}

export default function Button({  }: ButtonProps) {
  return <div>Button</div>
}
```

