## My first blog post

```Elixir
  @impl true
  def init(%__MODULE__{} = state) do
    Process.flag(:trap_exit, true)

    {:ok, state, {:continue, :setup}}
  end

```
