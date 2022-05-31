[![hacs_badge](https://img.shields.io/badge/HACS-Default-41BDF5.svg)](https://github.com/hacs/integration)

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/V7V51QQOL)

[Octopus.Energy 🐙](https://share.octopus.energy/wise-boar-813) referral code. You get £50 credit for joining and I get £50 credit.

# homsassistant-IamMeter-modbus
IamMeter Modbus custom_component for Home Assistant
Support Modbus TCP

Firmware version >= 75.82

You can have multiple instances of this Integration, just change the default Prefix from IamMeter to something else. Ie IamMeter Main or IamMeter Garage

Supports:

- WEM3080
- WEM3080T

# Installation

<B>Preferred Option</B>

~~You can add this custom_component directly through HACS, if you have HACS installed on your Home Assistant instance.~~

<B>Alternatively</B>

Download the zip / tar.gz from the release page.
- Extract the contents of solax_modbus into to your home-assistant config/custom_components folder.

If you manually clone the repository you may end up mid code update!

~~Copy the folder and contents of solax_modbus into to your home-assistant config/custom_components folder.~~


<B>Post Installation</B>

After reboot of Home-Assistant, this integration can be configured through the integration setup UI

Any manual updates / HACS updates require a restart of Home Assistant to take effect.
- Any major changes might require deleting the Integration from the Integration page and adding again. If you name the Integration exactly the same including the Area if set, you should retain the same entity naming bar any name changes in the release. (Refer to the release notes for any naming change)