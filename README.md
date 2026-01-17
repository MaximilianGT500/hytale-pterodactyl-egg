![Picture](https://pics.re/raw/WmWM9S.png)

**Hytale Dedicated Server (Pterodactyl Egg)**

This Pterodactyl egg lets you run the official Hytale Dedicated Server in a clean, container-based environment with simple panel control. It’s made for anyone who wants an easy, repeatable setup—whether you’re running a small private world with friends or building a larger community server.

Once installed, you can manage everything from the Pterodactyl panel: start and stop the server, restart it after changes, view logs in real time, and use the live console to run commands. The egg also supports common configuration through panel variables, while still allowing you to edit the standard Hytale configuration files whenever you need more control.

**Main features**

* **Automatic setup:** Installs the required Hytale server files on first launch so you don’t need to manually upload or assemble a server package.
* **Panel control:** Full start/stop/restart support with clear logging and a predictable boot process.
* **Live console access:** Run server commands, view output, and troubleshoot issues directly in the panel.
* **Real-time logs:** Monitor server activity, startup progress, and errors without needing SSH access.
* **Easy configuration:** Adjust key settings via environment variables and config files, depending on your preference.
* **Containerized environment:** Keeps the server runtime clean and consistent, reducing conflicts and making deployments easier to replicate.
* **Flexible runtime options:** Supports additional startup parameters (for example Java arguments) to tailor behavior to your system.
* **Authentication support:** Depending on your setup, you may need to complete the login flow before players can join. If required, run `/auth login device` in the server console and follow the on-screen instructions.

**How it works (high level)**

1. Create a server in Pterodactyl using this egg.
2. Start the server: it will download/prepare the Hytale Dedicated Server files automatically (first run).
3. Adjust settings through variables and/or the generated config files.
4. Use the console and logs for daily administration and maintenance.

If you want a straightforward way to host Hytale with a modern panel, clear logs, and an interactive console, this egg provides a solid foundation for running your dedicated server reliably and comfortably.
