[website]: https://bloom.host
[discord]: https://discord.gg/bloom
[release]: https://github.com/Bloom-host/Petal/releases

<img src="https://bloom.host/assets/images/Petal.png" alt="petal_logo" width="80" height="80">

# Petal Performance Minecraft JAR

Petal is a performance-oriented fork of Purpur intended to increase performance for entity-heavy servers by implementing multi-threaded and async improvements.

## Sponsored by Bloom Host

Development of this fork is sponsored by [Bloom Host][website], your home for the highest performance dedicated-core Minecraft hosting, VPS hosting, and bare metal dedicated servers. Bloom serves thousands of customers across the world with locations in Virginia, Dallas, Los Angeles, Miami, Germany, and soon to be Singapore! 

Join the [Bloom discord][discord] to connect with over 4,000 members and learn more about their services. Petal official support is limited to customers of Bloom Host.

For a limited time, you can enjoy 15% off your first invoice for any Minecraft/VPS hosting product with the coupon code `PETALPOWER`

## Features

Petal focuses on two specific improvements for entity-heavy servers:

- **Async Pathfinding** Entity pathfinding is performed completely asynchronously to completely offload processing from the main thread
- **Multi-threaded Entity Tracking** Entity tracking can take advantage of multiple threads to greatly reduce dependence on main thread processing


As Petal is forked from Purpur, it enjoys several performance features from previous projects including:

- **Sentry Integration** Easily track all errors coming from your server in excruciating detail (Pufferfish)
- **Better Entity Performance** Reduces the performance impact of entities by skipping useless work and making barely-noticeable changes to behavior (Pufferfish)
- **Partial Asynchronous Processing** Partially offloads some heavy work to other threads where possible without sacrificing stability (Pufferfish)
- **8x Faster Map Rendering** Reduces or eliminates lag spikes caused by plugins like ImageOnMap or ImageMaps (Pufferfish)
- **30% faster hoppers** over Paper (Airplane)
- **Reduced GC times & frequency** from removing useless allocations, which also improves CPU performance (Airplane)
- **Fast raytracing** which improves performance of any entity which utilizes line of sight, mainly Villagers (Airplane)
- **Built-in profiler** which has 0 performance hit and easy to read metrics for both server owners and developers (Airplane)

## Testimonials

> Petal has significantly improved entity performance on our 1.19 servers such as survival & skyblock. This has allowed us to increase per player mob spawn caps & increase frequency of mob spawning without having to worry about taking a performance hit.

-Foxcraft

## Download

The latest JAR can currently be found on the releases page [here][release].

## License

Petal is licensed under GPLv3.
