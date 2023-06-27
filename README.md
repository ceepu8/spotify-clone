## SUPABASE

## STRIPE

## MODAL PROVIDER

- Provider: ModalProvider.tsx
- Hook: useModal.ts
- Component: Modal.tsx

```jsx
import { forwardRef } from "react";

interface InputProps extends React.InputHTMLAttributes<HTMLInputElement> {}

const Input = forwardRef<HTMLInputElement, InputProps>(({}, ref) => {
  return <div>Input</div>;
});

Input.displayName = "Input";

export default Input;

```
