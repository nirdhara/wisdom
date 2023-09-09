
# Technology Stack

Our technology stack is chosen based on the expertise of our initial community members. We aim to avoid redundancy in our stack, only diversifying when it significantly benefits us. We manage our code using a monorepo approach, which means all our packages are in a single repository with clear relationships.

## Programming Language:
- [**Typescript**](https://www.typescriptlang.org/): We use Typescript, a strongly typed language that extends JavaScript, for both frontend and backend development, preserving a single language for our entire stack.

## Backend:
- [**Nest**](https://nestjs.com/): Our backend is built using Nest, a Node.js framework known for its scalability and efficiency, and we switched the underlying framework to Fastify to get speed benefits.

- [**LangChain**](https://www.langchain.com/): We leverage LangChain to use its components and abstractions tailored for building LLM applications.

## Frontend:
- [**Next.js**](https://nextjs.org/): For our frontend, we rely on Next.js, a React framework designed for building full-stack web applications, benefiting from an excellent out-of-the-box application architecture.

- [**React Flow**](https://reactflow.dev/): We use React Flow, a highly customizable React component, to create node-based editors and interactive diagrams. This library, well-maintained and integrating seamlessly with our Next.js/React-based frontend, serves our needs effectively.

## Development Tools:
- [**Nx**](https://nx.dev/): Nx simplifies monorepo management, significantly speeding up various operations related to codebase management - [Repo](https://github.com/nrwl/nx).

- [**Lerna**](https://lerna.js.org/): Lerna helps us manage versions and changelogs effectively, especially when dealing with multiple JS/TS packages within the same repository - [Repo](https://github.com/lerna/lerna).

- [**Eslint**](https://eslint.org/): Eslint statically analyzes our code, quickly identifying potential issues and ensuring code quality - [Repo](https://github.com/eslint/eslint).

- [**Prettier**](https://prettier.io/): Prettier helps maintain consistent coding conventions by easily formatting our codebase - [Repo](https://github.com/prettier/prettier).

- [**Lint-Staged**](https://github.com/okonet/lint-staged): We use lint-staged to efficiently lint only staged git files - [Repo](https://github.com/okonet/lint-staged).

- [**Husky**](https://typicode.github.io/husky/): Husky simplifies the use of Git hooks - [Repo](https://github.com/typicode/husky).

- [**Commitizen**](https://commitizen-tools.github.io/commitizen/): Commitizen provides an easy-to-use prompt for filling out required commit fields during commits, promoting a consistent commit message convention - [Repo](https://github.com/commitizen/cz-cli).

- [**Commitlint**](https://commitlint.js.org/): Commitlint helps our team adhere to a commit convention, ensuring clarity and consistency in our commit history - [Repo](https://github.com/conventional-changelog/commitlint).