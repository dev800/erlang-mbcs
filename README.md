```elixir

# Elixir

in mix.exs

  defp deps do
    [
      {:mbcs, "~> 1.1.1"}
    ]
  end

iex(1)> :mbcs.encode(to_charlist("中文"), :gb2312)
<<214, 208, 206, 196>>

```
