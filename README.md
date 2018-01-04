## mvt-bench-fixtures

This repository is deprecated and should not be used. Use the `real world` fixtures inside https://github.com/mapbox/mvt-fixtures instead. See https://github.com/mapbox/mvt-fixtures/blob/master/REAL-WORLD.md for the fixtures available and https://github.com/mapbox/vtquery/tree/96d389b5e1f0708192785802ba8d170410de80ea/bench for sample usage.

Sample vector tiles at z14. 210 of 'em. Designed to be used to benchmark decoders.

Contains `mapbox.mapbox-terrain-v2` and `mapbox.mapbox-streets-v7`.

Can be loaded like:

```c++
        for (std::size_t x=4680;x<=4693;++x) {
            for (std::size_t y=6260;y<=6274;++y) {
                std::string path = "fixtures/14-" + std::to_string(x) + "-" + std::to_string(y) + ".mvt";
                // open `path`....
            }
        }
```
