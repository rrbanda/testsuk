registered_toolgroups = {tg.identifier for tg in client.toolgroups.list()}

print("Registered Toolgroups:")
for tg in registered_toolgroups:
    print(f" - {tg}")
