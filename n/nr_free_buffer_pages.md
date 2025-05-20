# Function: <code>nr_free_buffer_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81191b20)
Location: mm/page_alloc.c:3564
Inline: True
Inline callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
Direct callers:
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffff81191b20-ffffffff81191b35: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81897b4e)
Location: mm/page_alloc.c:3983
Inline: True
Inline callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
Direct callers:
  - mm/khugepaged.c:start_stop_khugepaged
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffff811a6650-ffffffff811a6665: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff818cc1ea)
Location: mm/page_alloc.c:4139
Inline: True
Inline callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
Direct callers:
  - mm/khugepaged.c:start_stop_khugepaged
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffff811b69c0-ffffffff811b69d5: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81903762)
Location: mm/page_alloc.c:4427
Inline: True
Inline callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
Direct callers:
  - mm/khugepaged.c:start_stop_khugepaged
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffff811be870-ffffffff811be885: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8198d777)
Location: mm/page_alloc.c:4546
Inline: True
Inline callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
Direct callers:
  - mm/khugepaged.c:start_stop_khugepaged
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffff811d35e0-ffffffff811d35f5: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff819ea036)
Location: mm/page_alloc.c:4678
Inline: True
Inline callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
Direct callers:
  - mm/khugepaged.c:start_stop_khugepaged
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffff811f4880-ffffffff811f4895: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a252b9)
Location: mm/page_alloc.c:4849
Inline: True
Inline callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
Direct callers:
  - mm/khugepaged.c:start_stop_khugepaged
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffff81206cc0-ffffffff81206cd5: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a95708)
Location: mm/page_alloc.c:5033
Inline: True
Inline callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
Direct callers:
  - mm/khugepaged.c:start_stop_khugepaged
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffff8126cd00-ffffffff8126cd15: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81accfeb)
Location: mm/page_alloc.c:5051
Inline: True
Inline callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
Direct callers:
  - mm/khugepaged.c:start_stop_khugepaged
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffff8127bb10-ffffffff8127bb25: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81bc59d0)
Location: mm/page_alloc.c:5154
Inline: True
Inline callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
Direct callers:
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffff812add10-ffffffff812add25: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c3e980)
Location: mm/page_alloc.c:5333
Inline: True
Inline callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
Direct callers:
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffff812b97f0-ffffffff812b9805: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c30ab0)
Location: mm/page_alloc.c:5536
Inline: True
Inline callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
Direct callers:
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffff812bebc0-ffffffff812bebd5: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81d4f3cc)
Location: mm/page_alloc.c:5717
Inline: True
Inline callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
Direct callers:
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffff81301450-ffffffff81301465: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81371955)
Location: mm/page_alloc.c:5772
Inline: True
Inline callers:
  - mm/page_alloc.c:calculate_min_free_kbytes
Direct callers:
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffff81368c80-ffffffff81368c9b: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813ef0b5)
Location: mm/page_alloc.c:5915
Inline: True
Inline callers:
  - mm/page_alloc.c:calculate_min_free_kbytes
Direct callers:
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - fs/buffer.c:buffer_init
  - lib/stackdepot.c:stack_depot_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffff813e4bf0-ffffffff813e4c0b: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81422f55)
Location: mm/page_alloc.c:4843
Inline: True
Inline callers:
  - mm/page_alloc.c:calculate_min_free_kbytes
Direct callers:
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - fs/buffer.c:buffer_init
  - lib/stackdepot.c:stack_depot_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffff814196d0-ffffffff814196eb: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144fe85)
Location: mm/page_alloc.c:4932
Inline: True
Inline callers:
  - mm/page_alloc.c:calculate_min_free_kbytes
Direct callers:
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - mm/khugepaged.c:set_recommended_min_free_kbytes
  - fs/buffer.c:buffer_init
  - lib/stackdepot.c:stack_depot_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffff81446410-ffffffff8144642b: nr_free_buffer_pages (STB_GLOBAL)
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
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010d9ffb4)
Location: mm/page_alloc.c:5051
Inline: True
Inline callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
Direct callers:
  - mm/khugepaged.c:start_stop_khugepaged
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffff800010313cc0-ffff800010313ce0: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c15bdec4)
Location: mm/page_alloc.c:5051
Inline: True
Inline callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
Direct callers:
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
c052dd9c-c052ddbc: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c000000000eecbb0)
Location: mm/page_alloc.c:5051
Inline: True
Inline callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
Direct callers:
  - mm/khugepaged.c:start_stop_khugepaged
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
c0000000003e4560-c0000000003e4578: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe000047360)
Location: mm/page_alloc.c:5051
Inline: True
Inline callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
Direct callers:
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffe00021a47c-ffffffe00021a4a0: nr_free_buffer_pages (STB_GLOBAL)
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
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a6be5b)
Location: mm/page_alloc.c:5051
Inline: True
Inline callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
Direct callers:
  - mm/khugepaged.c:start_stop_khugepaged
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffff81274160-ffffffff81274175: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a283a2)
Location: mm/page_alloc.c:5051
Inline: True
Inline callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
Direct callers:
  - mm/khugepaged.c:start_stop_khugepaged
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffff812660d0-ffffffff812660e5: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ad826b)
Location: mm/page_alloc.c:5051
Inline: True
Inline callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
Direct callers:
  - mm/khugepaged.c:start_stop_khugepaged
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffff81271f00-ffffffff81271f15: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int nr_free_buffer_pages();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ae4726)
Location: mm/page_alloc.c:5051
Inline: True
Inline callers:
  - mm/page_alloc.c:init_per_zone_wmark_min
Direct callers:
  - mm/khugepaged.c:start_stop_khugepaged
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/buffer.c:buffer_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/tcp.c:tcp_init
  - net/ipv4/udp.c:udp_init
```
**Symbols:**

```
ffffffff81281960-ffffffff81281975: nr_free_buffer_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
