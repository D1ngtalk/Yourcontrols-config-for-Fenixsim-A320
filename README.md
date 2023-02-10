# Yourcontrols Config For Fenixsim A320
A share cockpit config for Microsoft Flight Simulator's Fenixsim A320, based on Yourcontrols.


## How to use
Please be sure you have to install the Yourcontrols. If you don't, you can find it [here](https://github.com/Sequal32/yourcontrols).

Open your Yourcontrols directory, download the YAML file and put it into /{yourcontrols directory}/definitions/aircraft

And you can choose Fenixsim A320 in Yourcontrols! Enjoy it!
## Known issues
If you turn the FCU's knobs too fast, it will be out of sync.

Throttle will be out of sync when you and your copilot use different external throttle device.

Trim in air will spasm, if you transfer control, the aircraft may raise/lower the pitch sharply because of Auto trim value out of sync. manual pitch trim don't have this problem.

Client's flight control surface(Aileron, Elevator, etc.) may move up and down when altitude above FL150.#Fixed in lastest release
## FAQs
### Can we use Simbrief and CPDLC?
Yes, but you need use same Hoppie ID and Simbrief ID with your copilot.
### How to take control easily?
Press your AP disconnect button, you will take control.
### How to report issues?
If you have and another issues, you can report it. I will try to fix it.
### Still out of sync?
Some out of sync is due to NETWORK ISSUES, please check your connection with your copilot BEFORE report it as a bug.
The recommended update rate is 60. If every thing still out of sync, try 120.
## Solutions to some out of sync(thanks Hurfifx)
FENIX RELATED :
If one of you ONLY have CLR in the txt field MCDU, hit mdcu menu and select any option (ATSU...), it will throw an error and you will be able to CLR and you will now both have a cleared txt field.
If one of you Have more ACARS message than the other, go to the tablet in fenix app, mass and balance hit resend loadshet as many times you need to have the same amount of acars messages.
If one of you ONLY have a different heading, do a direct to a waypoint then pull heading again.
If one of you ONLY have A/THR engaged, both users pull THR to IDLE then TO CLB and press A/THR on the FCU.
If one of you have different fuel (probably because you are not using the same server on microsft and then you have weather discrepency) go to mcdu menu config then fuel and the host fuel will be applied to the slave.

GSX RELATED :
When you use GSX doors can close ealier and block the boarding of your friend so crosscheck this every 5 minutes during gsx load operations. To reduce the chances of this happening use the simbrief option of GSX and make sure to start every service at the same time with your friend. I recommend using a chrono inside the plane for coordination. I recommend not using pushback tug that lift the aircraft but the smaller one that only connect to the noosewheel (you can tune that in gsx airport config).
