# Function: <code>bitmap_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *bitmap_alloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d7fa0)
Location: lib/bitmap.c:1123
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_zalloc
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff814d8320-ffffffff814d8339: bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *bitmap_alloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81503b10)
Location: lib/bitmap.c:1151
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_zalloc
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - drivers/input/evdev.c:evdev_handle_get_val
```
**Symbols:**

```
ffffffff81503ff0-ffffffff81504009: bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *bitmap_alloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81521ab0)
Location: lib/bitmap.c:1171
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_zalloc
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - drivers/input/evdev.c:evdev_handle_get_val
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81521f90-ffffffff81521fa9: bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *bitmap_alloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81584d50)
Location: lib/bitmap.c:1246
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_zalloc
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
  - drivers/input/evdev.c:evdev_handle_get_val
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81584f00-ffffffff81584f19: bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *bitmap_alloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a1e50)
Location: lib/bitmap.c:1246
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_zalloc
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
  - drivers/input/evdev.c:evdev_handle_get_val
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff815a2000-ffffffff815a2019: bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *bitmap_alloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a8c70)
Location: lib/bitmap.c:1257
Inline: True
Inline callers:
  - lib/bitmap.c:devm_bitmap_alloc
  - lib/bitmap.c:bitmap_zalloc
Direct callers:
  - kernel/sched/topology.c:sched_init_numa
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
  - drivers/input/evdev.c:evdev_handle_get_val
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff815a8f10-ffffffff815a8f29: bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *bitmap_alloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81611f10)
Location: lib/bitmap.c:1388
Inline: True
Inline callers:
  - lib/bitmap.c:devm_bitmap_alloc
  - lib/bitmap.c:bitmap_zalloc
Direct callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:validate_slab_cache
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
  - drivers/input/evdev.c:evdev_handle_get_val
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81612020-ffffffff81612039: bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *bitmap_alloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816de230)
Location: lib/bitmap.c:1405
Inline: True
Inline callers:
  - lib/bitmap.c:devm_bitmap_alloc
  - lib/bitmap.c:bitmap_zalloc
Direct callers:
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/watch_queue.c:watch_queue_set_size
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:validate_slab_cache
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
  - drivers/input/evdev.c:evdev_handle_get_val
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff816de3b0-ffffffff816de3d1: bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *bitmap_alloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff817ce3d0)
Location: lib/bitmap.c:1386
Inline: True
Inline callers:
  - lib/bitmap.c:devm_bitmap_alloc
  - lib/bitmap.c:bitmap_zalloc
Direct callers:
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/watch_queue.c:watch_queue_set_size
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:validate_slab_cache
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
  - drivers/input/evdev.c:evdev_handle_get_val
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff817ce690-ffffffff817ce6b1: bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *bitmap_alloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8180c880)
Location: lib/bitmap.c:1386
Inline: True
Inline callers:
  - lib/bitmap.c:devm_bitmap_alloc
  - lib/bitmap.c:bitmap_zalloc
Direct callers:
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/watch_queue.c:watch_queue_set_size
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:validate_slab_cache
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
  - drivers/input/evdev.c:evdev_handle_get_val
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff8180cb40-ffffffff8180cb61: bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *bitmap_alloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81852990)
Location: lib/bitmap.c:710
Inline: True
Inline callers:
  - lib/bitmap.c:devm_bitmap_alloc
  - lib/bitmap.c:bitmap_zalloc
Direct callers:
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/watch_queue.c:watch_queue_set_size
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:validate_slab_cache
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
  - drivers/input/evdev.c:evdev_handle_get_val
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_chardev.c:ptp_open
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81852c50-ffffffff81852c71: bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *bitmap_alloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062b200)
Location: lib/bitmap.c:1171
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_zalloc
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - drivers/input/evdev.c:evdev_handle_get_val
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffff80001062b600-ffff80001062b624: bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *bitmap_alloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c07d2520)
Location: lib/bitmap.c:1171
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_zalloc
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
c07d2850-c07d2870: bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *bitmap_alloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007cd844)
Location: lib/bitmap.c:1171
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_zalloc
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
  - drivers/input/evdev.c:evdev_handle_get_val
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
c0000000007cdf90-c0000000007cdfc8: bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *bitmap_alloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffe00045bf96)
Location: lib/bitmap.c:1171
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_zalloc
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - drivers/gpio/gpiolib.c:gpiochip_allocate_mask
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffe00045c04e-ffffffe00045c072: bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *bitmap_alloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8151a090)
Location: lib/bitmap.c:1171
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_zalloc
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - drivers/input/evdev.c:evdev_handle_get_val
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff8151a570-ffffffff8151a589: bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *bitmap_alloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8150a380)
Location: lib/bitmap.c:1171
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_zalloc
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - drivers/input/evdev.c:evdev_handle_get_val
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff8150a860-ffffffff8150a879: bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *bitmap_alloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81516120)
Location: lib/bitmap.c:1171
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_zalloc
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - drivers/input/evdev.c:evdev_handle_get_val
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81516600-ffffffff81516619: bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *bitmap_alloc(unsigned int nbits, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152f8b0)
Location: lib/bitmap.c:1171
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_zalloc
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:list_locations
  - drivers/input/evdev.c:evdev_handle_get_val
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff8152fd90-ffffffff8152fda9: bitmap_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
