# Backend

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup`
  * Start Phoenix endpoint with `mix phx.server` or inside IEx with `iex -S mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

  * Official website: https://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Source: https://github.com/phoenixframework/phoenix


# Important Packages

## <code>Credo</code>

Credo is a static code analysis tool for the Elixir language with a focus on teaching and code consistency.
<code>Credo</code> can show you refactoring opportunities in your code, complex code fragments, warn you about common mistakes, show inconsistencies in your naming scheme and - if needed - help you enforce a desired coding style
To learn more about <code>credo</code> checkout documentation [here](https://hexdocs.pm/credo/overview.html)

## <code>ExCoveralls</code>

An Elixir library that reports test coverage statistics, with the option to post to [coveralls.io](https://coveralls.io/) service. It uses Erlang's [cover](http://www.erlang.org/doc/man/cover.html) to generate coverage information, and posts the test coverage results to coveralls.io through the JSON API.

## <code>mix test.watch</code>

Automatically run your Elixir project's tests each time you save a file. Because Test-driven development (TDD) is awesome.
Check its usage [here](https://hexdocs.pm/mix_test_watch/readme.html)
