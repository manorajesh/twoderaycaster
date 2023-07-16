# twodee raycaster
A very basic 2D raycaster built with Rust

![Demo picture](https://github.com/manorajesh/rusty-graphics/blob/perlin_map_gen/images/demo1.png)
![Demo picture](https://github.com/manorajesh/rusty-graphics/blob/perlin_map_gen/images/demo2.png)

## Installation
```
git clone https://github.com/manorajesh/rusty-graphics.git && cd rusty-graphics
cargo run
```

## Usage
Use the arrow keys to traverse the extremely entertaining room and watch the shadows

#### Important Code
The [`draw`](https://github.com/manorajesh/rusty-graphics/blob/cdf31fba1238801ae4804fe2ce98fec9d935985d/src/raycaster.rs#L147-L207) function is responsible for casting the rays and rendering them accordingly.
