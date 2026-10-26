A TypeScript example with Chinese and HTML characters:

```ts
const greeting: string = "你好<&>";

/* Multi-line comment:
   中文文字 and <HTML> stay intact. */
function greet(name: string): string {
  return `${greeting}, ${name}!`;
}

console.log(greet("Maka")); // Keep the original code.
```

The same response is shown in both transcript surfaces.
