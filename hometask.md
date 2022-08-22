---
sidebar_position: 6
---

# 5. 📚 Home Task

1. Identify SOLID Principles

   Choose a large open source project written in TypeScript preferably (choose another OOP language if you want: Java, C#, Ruby). You may want to look at [Angular](https://github.com/angular) or [VS Code](https://github.com/microsoft/vscode) source code. A project may be considered large enough if it contains at least 30 classes.

   Try to identify **at least 1 (one)** example of each SOLID principle. Document them by filling in the table below. Note that you don't need to give code examples itself, just provide the link to file with line numbers range (or whatever you want to clearly recognize the example you describe, e.g. file hello.ts:15-36, class Foo), you can also write free text.

   | Principle                        | Examples |
   | -------------------------------- | -------- |
   | Single Responsibility Principle  |   [SSR render (Project React)](https://github.dev/facebook/react/blob/main/fixtures/ssr/server/render.js#L23)        |
   | Open / Closed Principle          | [SSR index (Project React)](https://github.dev/facebook/react/blob/main/fixtures/ssr/server/index.js#L6)         |
   | Liskov Substitution Principle    |     [Utils (Project VSCode)](https://github.dev/microsoft/vscode/blob/main/build/lib/eslint/utils.ts#L1)     |
   | Interface Seggregation Principle |    [Tak.ts (Project VSCode)](https://github.dev/microsoft/vscode/blob/main/build/lib/task.ts#L14) - line 14 to line 22      |
   | Dependency Inversion Principle   |      [(Project VSCode)](https://github.dev/microsoft/vscode/blob/main/build/lib/policies.ts#L148)   line 65-107  |

2. Violations of SOLID and Other Principles

   Try to find **at least 1 (one)** violations of each SOLID principle in the project you have chosen for Problem 1 and document it. Additionally, you can describe other (DRY/KISS/YAGNI/etc.) violations.

   You may provide short descriptions about how to refactor/improve such violations.

   Optionally, you can add small examples with results of such refactoring using pseudocode or real code.
