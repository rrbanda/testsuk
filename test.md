```registered_toolgroups = {tg.identifier for tg in client.toolgroups.list()}

print("Registered Toolgroups:")
for tg in registered_toolgroups:
    print(f" - {tg}")

```
```
tools = client.tools.list(toolgroup_id="mcp::custom_tool")
tool_names = [t.identifier for t in tools]

print(tool_names)
```
