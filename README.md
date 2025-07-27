# DS2832
This repository contains my customizations for [Devantech DS2832](https://www.robot-electronics.co.uk/products/relay-modules/ethernet-relay/ds2832.html) module. This is a very versatile hardware board containing relais, digital inputs/outputs, an RS485 connection and many other goodies. On top, it's highly programmable using the [Devantech dScript language](https://www.robot-electronics.co.uk/products/dscript.html). 

During my usage of the board, I bumped into several small issues (e.g. Modbus command timeouts) which I decided to fix in the original dScript firmware, and post here. The great thing about the Devantech boards is that the entire default firmware is available, so small tweaking is a matter of going through the (very understandable) code and off you go!

> Disclaimer: the majority of this repository is building further on the
> original DS2832 firmware, which was created and is maintained by
> [Devantech](https://github.com/devantech). Unfortunately, they do not
> (yet) have a Github repo for the entire dScript set where changes in
> the form of a pull request could be injected. I therefore downloaded
> the publicly available firmware and copied it here with my
> adjustments. 
