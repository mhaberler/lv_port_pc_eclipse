# build and run the LVGL ThorVG demo on MacOS

```
brew install sdl2
git clone https://github.com/mhaberler/lv_port_pc_eclipse.git  --branch mah
git submodule update --init
mkdir build
cd build
cmake -DLV_USE_DRAW_SDL=ON ..
make -j
cd ..
bin/main vector_graphic

```

the demo code is in lvgl/demos/vector_graphic/*
