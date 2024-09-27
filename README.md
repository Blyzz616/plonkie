# plonkie
The 3rd Iteration of Discord / Project Zomboid integration

- [ ] Install / Setup
	- [ ] Input Server Name
	- [ ] Discord Webhook
	- [ ] Steam ID of admin

- [ ] Server Events
	- [ ] Startup init
	- [ ] Startup complete
	- [ ] Shutdown
		- [ ] Send in-game notifications
		- [ ] Allow for shutdown delay
		- [ ] Send discord messages
		- [ ] Session Uptime
		- [ ] Total Uptime
	- [ ] Server Version check
		- [ ] set interval during install
		- [ ] allow to change interval
		- [ ] init reboot
			- [ ] give warnings - time set during install

- [ ] Player Events
	- [ ] Join
	- [ ] Death
	- [ ] Quit
		- [ ] Shortly after death
		- [ ] Longer after death
	- [ ] Intercept plyer messages
		- [ ] List SteamID/Player name? permissions
		- [ ] Add new permissions
		- [ ] Remove permissions
		- [ ] get player count
		- [ ] get player list
		- [ ] trigger events
			- [ ] Server reboot - permission check
			- [ ] Server Shutdown - Permission Check
			- [ ] what other events can be triggered?

- [ ] Chopper Event
	- [ ] Arrive
	- [ ] Active
	- [ ] Search
	- [ ] Leave
