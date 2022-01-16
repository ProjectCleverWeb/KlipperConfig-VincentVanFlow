# Summers Klipper Suite
A collection of macros and configurations for Klipper (3D printer firmware)

---

### WARNING:
This repo is currently only configured for my exact Ender-3 v2 with its set of hardware.

HOWEVER, it should be pretty easy to modify it to work for any other printer that klipper supports by just clearing the auto-generated portion of `./printer.cfg` and then splitting your existing `printer.cfg` into the respective `./config/*.cfg` files.

Alternatively, you can just copy the `./macro` directory into your `klipper_config` directory and add `[include macro/*.cfg]` to your existing `printer.cfg`

## Usage & Contributing

You are welcome to use this as-is and request any features as well as report any bugs as Github issues.

Eventually there will be formal Alpha & Beta versions with proper installation instructions, easier install, versioning, etc., but for now this will have to do if you want to use it immediately.
