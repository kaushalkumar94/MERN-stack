# TypeScript vs JavaScript: Complete Comparison

## 🔍 Feature Comparison

| Feature                 | JavaScript (JS)                                   | TypeScript (TS)                                             |
|------------------------|----------------------------------------------------|--------------------------------------------------------------|
| **Type System**        | Dynamic (types are checked at runtime)             | Static (types are checked at compile time)                   |
| **Compilation**        | Interpreted directly by browsers                   | Compiled to JavaScript using the TypeScript compiler         |
| **Error Detection**    | Errors occur at runtime                            | Many errors caught at compile time                           |
| **Tooling & IDE Support** | Good, but limited for type-checking              | Excellent (auto-completion, refactoring, etc.)               |
| **Syntax**             | Loosely typed                                      | Superset of JS + static typing (`:string`, `:number`, etc.)  |
| **Learning Curve**     | Easier for beginners                               | Steeper if you're new to types, but manageable               |
| **Popular Use**        | Frontend, small-to-medium apps                     | Large-scale projects, team-based development                 |
| **Optional Typing**    | Not available                                      | Optional and gradual typing                                  |
| **Community & Ecosystem** | Very large                                      | Growing fast, backed by Microsoft                            |
| **File Extensions**    | `.js`, `.mjs`                                      | `.ts`, `.tsx` (for React)                                    |

---

## 🔧 TypeScript vs JavaScript Code Example

### 🔸 JavaScript:

```javascript
function greet(name) {
  return "Hello " + name;
}

console.log(greet(42)); // No error until runtime

---

## 🔹 TypeScript Example

```typescript
function greet(name: string): string {
  return "Hello " + name;
}

console.log(greet(42)); 
// ❌ Error: Argument of type 'number' is not assignable to parameter of type 'string'
###✅ Why Use TypeScript?
Helps prevent bugs early

Improves code readability and maintainability

Essential for large projects or working in teams

Makes refactoring safer

Strong support with Visual Studio Code (VS Code)