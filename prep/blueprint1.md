# 2-hour lesson blueprint

---

## 0. Preparation (before class)

- **Environment**: Node.js & npm installed, VS Code with the “TypeScript” extension.
- **Starter files**: A minimal `tsconfig.json` and a basic project folder.

---

## 1. Introduction & Setup (≈15 min)

| Goal                | Key Points                                                                    | Demo / Activity                                        |
| ------------------- | ----------------------------------------------------------------------------- | ------------------------------------------------------ |
| Motivate TypeScript | Why add types to JavaScript (maintainability, tooling, catching errors early) | Show a short “JS bug” and how a TS type would catch it |
| Tooling             | Install `typescript` and run `tsc --init`                                     | Guide students to create `hello.ts` and compile to JS  |

---

## 2. Core Language Features (≈35 min)

| Topic                  | Highlights                                                | Quick Exercise                                                |
| ---------------------- | --------------------------------------------------------- | ------------------------------------------------------------- |
| Basic Types            | `string`, `number`, `boolean`, `any`, `unknown`           | Type a few simple variables                                   |
| Functions & Parameters | Typed parameters, return types, optional & default params | Add a function with wrong argument type, watch compiler error |
| Objects & Interfaces   | Interfaces, type aliases, readonly, optional properties   | Create a `User` interface                                     |
| Arrays & Tuples        | `string[]`, `[number, string]`                            | Build a typed list of users                                   |
| Union & Literal Types  | `type Status = "open" \| "closed"`                        | Validate a status field                                       |

---

## 3. Organising Code (≈30 min)

| Topic         | Key Takeaways                                          | Hands-on                      |
| ------------- | ------------------------------------------------------ | ----------------------------- |
| Modules       | `export` / `import`, compiling with ES modules         | Split code into two files     |
| Classes & OOP | `class`, `constructor`, `public/private`, `implements` | Model a `Car` class           |
| Generics      | `Array<T>`, generic functions                          | Write a generic `identity<T>` |

---

## 4. Tooling & Workflow (≈20 min)

| Focus                               | Demo / Tips                                               |
| ----------------------------------- | --------------------------------------------------------- |
| Compiler Options                    | Strict mode, target, `tsconfig.json` essentials           |
| Type Declarations & DefinitelyTyped | Using npm packages with types                             |
| Build + Run                         | `tsc --watch` and running via `ts-node`                   |
| Next Steps                          | Resources: official docs, TypeScript Handbook, playground |

---

## 5. Wrap-Up (≈10 min)

- Quick quiz or code review.
- Encourage experimenting in the [TypeScript Playground](https://www.typescriptlang.org/play).
- Share a small homework idea: convert a tiny JavaScript snippet to TypeScript.

---

### Tips for a Tight 2 Hours

- Keep slides minimal; live-code wherever possible.
- Prepare sample code so you can copy/paste instead of typing everything.
- Encourage learners to fix small compiler errors themselves—it reinforces the type system quickly.

This blueprint gives students a working grasp of TypeScript’s essentials and the confidence to start using it in real projects—all within a focused 2-hour session.
