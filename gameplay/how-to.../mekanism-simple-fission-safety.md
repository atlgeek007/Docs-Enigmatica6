---
cover: ../../.gitbook/assets/Enigmatica_6_1900x400.png
coverY: 0
---

# Simple Mekanism Fission Safety

## The Process

So you're doing Mekanism fission, but you don't want to irradiate your base and make it a danger to yourself and others?  ExplodeyWolf from the E6 discord has you covered!

![Start with your reactor](https://i.imgur.com/1RQ9wtw.png)

Start with your reactor.

![Add five logic ports](https://i.imgur.com/IC2D5mX.png)

Add 5 logic ports, the left one set to Activate reactor, and the 4 right ones set to High Temperature, Excess Waste, Damage Critical, and Insufficient Fuel. You can have a minimum of two, 3 is recommended, and a max of 5.

![Redstone blocks](https://i.imgur.com/VrjnT7J.png)

Add some building blocks for the redstone, like so.

![Redstone line](https://i.imgur.com/dkEjAkD.png)

Place redstone like so, and a powered latch facing the left logic adapter. Note that my redstone is lit up because I have no fissil fuel in the reactor.

![Toggle Latch](https://i.imgur.com/YuZU57s.png)

Activate the reactor with the lever on the powered latch. Alternatively you can activate it by giving it a pulse to the back of the latch. Only turn the reactor on these ways, or your safety breaker will not function.

![Finish the Reactor](https://i.imgur.com/UCk5SnL.png)

Finish configuring your reactor for fuel/coolant/exhaust/etc.

![Entangled blocks!](https://i.imgur.com/yNxndBU.png)

A little tip: If you entangle an input next to an output port on a multiblock, you will get infinite transfer rate(unless it's the thermal evaporation plant). This is helpful if you don't want to have multiblocks right next to each other. You could do this with an entangled block on a turbine vent entangled to an input port of the fission reactor.

![Working Examples](https://i.imgur.com/H408Nxs.png)

If I set this to a high amount...

![Power: On!](https://i.imgur.com/BuGAzMQ.png)

And turn it on...

![No explosion!](https://i.imgur.com/FhlDdT2.png)

My reactor would have exploded! But the safety breaker turned the reactor off. This setup should be able to handle very large heating rates.

- Written by ExplodeyWolf on the E6 discord, submitted to GitBook by atlgeek007/vanamar