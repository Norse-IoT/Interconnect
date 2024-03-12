# Interconnect
Interconnect is a Minecraft modpack focused on exploring the possibilities of Arduino/Raspberry Pi devices. Interconnect is the official modpack of the Norse IoT Club at NKU.

# Development
Norse IoT provides an automatically updating Prism Launcher instance, as well as a distribution on Modrinth.

Before working on the pack, you should already have the [packwiz tool](https://packwiz.infra.link/installation/) installed.
```
packwiz update --all # Update all mods to latest.
packwiz refresh      # Run after modifying any files.
git commit -a        # Now you can commit your changes..
git push             # ..and push them to the repository.
```

Before you push your changes, its recommended to test them locally.

- Set the Prism Launcher instance's "pre-launch command" to: `http://localhost:8080/pack.toml`
- Run `packwiz serve` to run a simple webserver that serves the files.
- Launch the instance and it will automatically refresh the modpack and update with your changes.

[For more help, see Packwiz's guide](https://packwiz.infra.link/tutorials/installing/packwiz-installer/).
