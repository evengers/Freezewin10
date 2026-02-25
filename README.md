# Freezewin10
Registry files to freeze a vm etc. 


Beyond the Registry — A Few More Things Worth Doing
Since you’re freezing the state anyway, these complement the registry tweaks nicely:
	∙	Services to disable (services.msc): Windows Update, Update Orchestrator Service, Windows Search (if you don’t need it), Connected User Experiences and Telemetry (DiagTrack), and Windows Error Reporting Service.
	∙	Task Scheduler: Under Task Scheduler Library → Microsoft → Windows, disable tasks under UpdateOrchestrator, WindowsUpdate, and Application Experience folders — these can wake services even when disabled.
	∙	Take a disk image after all tweaks are applied — tools like Macrium Reflect Free let you snapshot the clean state so you can restore it in minutes if something goes wrong later rather than redoing all of this.​​​​​​​​​​​​​​​​
