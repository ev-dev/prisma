- 3 ways to use query or mutation
  - delegate via `info`
  - fetch all scalar fields on type level
  - provide additional query
- exists
  - https://github.com/graphcool/graphql-boilerplate/blob/ce6fe737839caec07ba76cd537c2a115caca71bb/src/resolvers/Mutation/post.ts#L14
  - returns `Promise<boolean>`: https://github.com/graphcool/graphcool-binding/blob/master/src/index.ts#L29-L34
- raw delegate
- request
- soon: codegen
- fragmentReplacement / resolver fragments: query fields where it's unsure whether they're in the current selection set but needed as arguments

- instantiate Graphcool Binding per request (batching)