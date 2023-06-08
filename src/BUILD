python_sources()
resources(name="resources", sources=["resources/*"])
pex_binary(
  name="app",
  entry_point="main.py",
  dependencies=[":resources"],
)