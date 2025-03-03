# Remix Examples

Welcome to `@remix-run/examples`!

If you have an example you'd like to share, please submit a pull request!

**This is a community-driven repository.**. Here you'll find various examples of using Remix to accomplish certain tasks. Each example is a complete application including a build and even a button to preview a live instance of the app so you can play with it.

Also, remember to check out the `README` for each example before getting started.

You can also initialize a new project with any of these examples using the `--template` flag of the `create-remix` CLI. For example:

```
npx create-remix@latest --template https://github.com/remix-run/examples/tree/main/<example-dir>
```

Enjoy!

## Contributing

Thanks for your willingness to contribute an example to Remix. Examples are incredibly helpful to people like you who are trying to figure out how to use Remix to solve certain problems and integrate with other tools.

What makes a good example is focus. There's certainly room for examples that show off a whole app experience and we do have some examples like that. But the vast majority of useful examples are focused on a specific use-case. Otherwise it's hard for people to know what to look for in the code.

This means you should avoid adding stuff that isn't absolutely necessary for the example. Start with bare bones and add only what you need.

Most examples should:

- Not use a database
- Have no more than one or two routes (some may not even need any routes)
- Have only necessary deps
- Not use complex validation
- Be as practical as reasonable (balanced with the focus). Just, no `foo`/`bar` please.

To create an example, simply copy/paste the [`_template`](_template) directory into a new one with a sensible name, make the changes you need for your example, update the `README.md` and open a PR.
