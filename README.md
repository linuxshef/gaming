# gaming

--------------------------------------

Универсальные параметры 

```bash
LD_PRELOAD="" SDL_VIDEODRIVER=wayland PROTON_FORCE_LARGE_ADDRESS_AWARE=1 DXVK_ASYNC=1 PROTON_NO_ESYNC=1 PROTON_NO_FSYNC=1 mangohud gamemoderun %command%
```
---------------------------------------

---------------------------------------

Параметры с оптимизацией шейдеров для видеокарты AMD - функция ( GPL )

```bash
LD_PRELOAD="" SDL_VIDEODRIVER=wayland RADV_PERFTEST=gpl PROTON_FORCE_LARGE_ADDRESS_AWARE=1 DXVK_ASYNC=1 PROTON_NO_ESYNC=1 PROTON_NO_FSYNC=1 mangohud gamemoderun %command%
```
---------------------------------------

---------------------------------------

Параметры с оптимизацией шейдеров для видеокарты AMD - функция ( ACO )

```bash
LD_PRELOAD="" SDL_VIDEODRIVER=wayland RADV_PERFTEST=aco PROTON_FORCE_LARGE_ADDRESS_AWARE=1 DXVK_ASYNC=1 PROTON_NO_ESYNC=1 PROTON_NO_FSYNC=1 mangohud gamemoderun %command%
```
---------------------------------------

---------------------------------------
RTX для видеокарты AMD ( Polaris, а также Volcanic Islands и Arctic Islands )

```bash
LD_PRELOAD="" SDL_VIDEODRIVER=wayland RADV_PERFTEST=emulate_rt PROTON_FORCE_LARGE_ADDRESS_AWARE=1 DXVK_ASYNC=1 PROTON_NO_ESYNC=1 PROTON_NO_FSYNC=1 mangohud gamemoderun %command%
```
---------------------------------------
