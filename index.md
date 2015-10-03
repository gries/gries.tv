---
layout: page
title: About me
description: "All about me"
---
## Hi, this is me

>"The function of good software is to make the complex appear to be simple.”
>
>(Grady Booch)

I'm a young aspiring software-engineer who's passion is writing high quality code. I love takeling highly complex tasks and breaking them down into small pieces of reusable code.

My other passions include IT-Security, playing and extending Minecraft and making music.

## What I do

Have a look at my [CV](cv) to find out about all of my projects.
For the lazy ones here's some examples:

### PHP-Minecraft
I've written some libraries to interact with a running minecraft server using the RCON protocol.

* [minecraft-commander](https://github.com/gries/minecraft-commander)
* [mcontrol](https://github.com/gries/mcontrol)
* [rcon](https://github.com/gries/rcon)

#### Exmaples
Some examples of what can be achieved with these libraries.

<iframe src="https://player.vimeo.com/video/78989366" width="500" height="270" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe> <p><a href="https://vimeo.com/78989366">drawing with minecraft and imagick</a> from <a href="https://vimeo.com/user22534748">gries grieson</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

<iframe src="https://player.vimeo.com/video/80205456" width="500" height="270" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe> <p><a href="https://vimeo.com/80205456">Minecraft + phps MControl - Scan + Rebuild Biomes</a> from <a href="https://vimeo.com/user22534748">gries grieson</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

<iframe src="https://player.vimeo.com/video/83455915" width="500" height="270" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe> <p><a href="https://vimeo.com/83455915">minecraft live browser drawing demo</a> from <a href="https://vimeo.com/user22534748">gries grieson</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

### [POKEMATH](https://github.com/gries/pokemath)
A library to do basic calculation base-pokemon. Basically a Pokemon number-system.
The whole thing is based on my [number-system](https://github.com/gries/number-system) library.

    <?php

    use gries\Pokemath\Numbers\Ivysaur;
    use gries\Pokemath\Numbers\Jigglypuff;

    // big calculation
    $jiggly = new Jigglypuff();
    $wiggly = new Wigglytuff();

    echo $jiggly->multiply($wiggly)->value()."\n"; // -> ivysaur-chespin

    // expression parsing
    $calculator = new \gries\Pokemath\PokeCalculator();

    $expression = '(ivysaur + ivysaur) * ivysaur#ivysaur';
    $result = $calculator->calculate('(ivysaur + ivysaur) * ivysaur#ivysaur');

    echo $result->value(). '('.$result->asDecimalString().")\n";      
    // -> (1 + 1) * 701 = venusaur#venusaur(1402)

**WHY?**
> "ENTON!" - Enton
