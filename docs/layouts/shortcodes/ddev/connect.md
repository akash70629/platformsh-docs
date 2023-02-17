The best way to connect your local DDEV to your Platform.sh project is through the [Platform.sh DDEV add-on](https://github.com/drud/ddev-platformsh).
To add it, run the following command:

```bash
ddev get drud/ddev-platformsh
```

Answer the interactive prompts with your project ID and the name of the environment to pull data from.

With the add-on, you can now run `ddev platform <command>` from your computer without needing to install the Platform.sh CLI.