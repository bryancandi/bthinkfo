# bthinkfo

### bthinkfo:
CPU core frequency, core temperature and fan speed monitoring script for ThinkPad Laptops.

---

#### Script `bthinkfo` defaults to a 2 second refresh interval and temperatures in Celsius unless specified with launch options.

Examples:<br>
`bthinkfo` : Run script with default values.<br>
`bthinkfo -f` : Run script and display temperatures in Fahrenheit and a default refresh of 2 seconds.<br>
`bthinkfo -f -t 10` : Run script and display temperatures in Fahrenheit and refresh every 10 seconds.<br>
`bthinkfo -a` : Ask user to input desired refresh interval and temperature unit on launch.<br>

<pre>
Options:
  -h, --help    Display this help message
  -a, --ask     Display time and unit prompts
  -c            Show temperatures in degrees Celsius
  -f            Show temperatures in degrees Fahrenheit
  -t, --time    Specify refresh interval in seconds
  -v, --version Display script version
</pre>

---

### Installation

Normal install will install scripts to `/usr/bin` and requires root.<br>
Local install will install scripts to `~/bin`.<br>

Run `make install` to install `bthinkfo`.<br>
Run `make uninstall` to uninstall `bthinkfo`.<br>

Run `make install-local` to install `bthinkfo` locally for current user.<br>
Run `make uninstall-local` to uninstall `bthinkfo` locally for current user.<br>

### Debian/Ubuntu

The .deb binary packages can be used on Debian and Ubuntu based distros.

These packages will also install a launcher with an icon for each script (not automatic in Makefile installations).

Change the file name to install the desired script and version number.

Run `sudo dpkg -i bcbthinkfo_0.0.3-1_all.deb` to install.<br>
Run `sudo dpkg -r bbthinkfo` to uninstall.<br>

---
### Screenshots

![Alt text](/screenshots/bthinkfo.png?raw=true "bthinkfo")
