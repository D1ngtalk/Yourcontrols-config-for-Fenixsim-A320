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

Client's flight control surface(Aileron, Elevator, etc.) may move up and down when altitude above FL150.
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
