# PerksSpecial
Custom PCB for the JLI2555 Capsule 
After long delays in my redesign of Matthew Perks’ excellent USB 3.0 microphone, I’m releasing this very simple design that will work with many TO92 and TO71 JFETs.

It’s primarily designed with the LSK170(a-c) or the LSK389 but should also work with any low-voltage JFETs designed for condenser microphone applications such as the 2K208 - which is lpower cost than it's higher-performance (lower noise) brethren. It's worth noting that even the cheapest FETs have respectably low noise for the application but it's better to check the datasheet so you don't buy something optimised for a different application. Whatever you choose, it MUST be an N-type.

ALL three (technically four) devices are wired in parallel as can be seen in the schematic, but you should only fit one appropriate to the device you have. I recommend that LSK170 which is low noise, in current production and not especially expensive.

The name tag should break right off if you want to- the silkscreen doesn't have the part numbers as there are a fair number in different packages that will also work (to some degree). 
