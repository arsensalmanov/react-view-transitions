A simple way to use View Transition API in React

![react-view-transitions demo](https://raw.githubusercontent.com/arsensalmanov/react-view-transitions/main/demo.gif)

# Installation

Install with npm

```bash
npm i react-view-transitions
```

Install with yarn

```bash
yarn add react-view-transitions
```

# Usage

```tsx
import { useViewTransition } from "react-view-transitions";

function MyComponent() {
  const [color, setColor] = useState("red");
  const viewColor = useViewTransition(color);

  return (
    <>
      <p style={{ color }}>With React state</p>
      <p style={{ color: viewColor }}>With View Transition state</p>
    </>
  );
}
```
