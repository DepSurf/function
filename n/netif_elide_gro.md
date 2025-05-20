# Function: <code>netif_elide_gro</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d136d)
Location: include/linux/netdevice.h:1915
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/gro_cells.c (ffffffff817f98e0)
Location: include/linux/netdevice.h:1915
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184b47d)
Location: include/linux/netdevice.h:1931
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/gro_cells.c (ffffffff81877200)
Location: include/linux/netdevice.h:1931
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8189583d)
Location: include/linux/netdevice.h:1999
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/gro_cells.c (ffffffff818c8930)
Location: include/linux/netdevice.h:1999
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b74be)
Location: include/linux/netdevice.h:2053
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/gro_cells.c (ffffffff818f3856)
Location: include/linux/netdevice.h:2053
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819032ed)
Location: include/linux/netdevice.h:2042
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/gro_cells.c (ffffffff819526fb)
Location: include/linux/netdevice.h:2042
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193609d)
Location: include/linux/netdevice.h:2072
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/gro_cells.c (ffffffff81988a4b)
Location: include/linux/netdevice.h:2072
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0adfb)
Location: include/linux/netdevice.h:2140
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/gro_cells.c (ffffffff81a6069c)
Location: include/linux/netdevice.h:2140
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0c04b)
Location: include/linux/netdevice.h:2188
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/gro_cells.c (ffffffff81a68f20)
Location: include/linux/netdevice.h:2188
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f2200)
Location: include/linux/netdevice.h:2252
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/gro_cells.c (ffffffff81a4c2e0)
Location: include/linux/netdevice.h:2252
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa40d0)
Location: include/linux/netdevice.h:2272
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/gro_cells.c (ffffffff81b04790)
Location: include/linux/netdevice.h:2272
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81c54105)
Location: include/linux/netdevice.h:2352
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/gro_cells.c (ffffffff81c8a01a)
Location: include/linux/netdevice.h:2352
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81e09833)
Location: include/linux/netdevice.h:2379
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/gro_cells.c (ffffffff81e44bfa)
Location: include/linux/netdevice.h:2379
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81e7c003)
Location: include/linux/netdevice.h:2431
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/gro_cells.c (ffffffff81e9f9fa)
Location: include/linux/netdevice.h:2431
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81f3c353)
Location: include/linux/netdevice.h:2490
Inline: True
Inline callers:
  - net/core/gro.c:dev_gro_receive
```
```
In net/core/gro_cells.c (ffffffff81f6226a)
Location: include/linux/netdevice.h:2490
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd46d4)
Location: include/linux/netdevice.h:2072
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/gro_cells.c (ffff800010c30be8)
Location: include/linux/netdevice.h:2072
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ceecb0)
Location: include/linux/netdevice.h:2072
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/gro_cells.c (c0d479e8)
Location: include/linux/netdevice.h:2072
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb37ac)
Location: include/linux/netdevice.h:2072
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/gro_cells.c (c000000000d29960)
Location: include/linux/netdevice.h:2072
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075e514)
Location: include/linux/netdevice.h:2072
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/gro_cells.c (ffffffe0007a6b02)
Location: include/linux/netdevice.h:2072
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d606d)
Location: include/linux/netdevice.h:2072
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/gro_cells.c (ffffffff819288bb)
Location: include/linux/netdevice.h:2072
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188fead)
Location: include/linux/netdevice.h:2072
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/gro_cells.c (ffffffff818e266b)
Location: include/linux/netdevice.h:2072
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192709d)
Location: include/linux/netdevice.h:2072
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/gro_cells.c (ffffffff81979a4b)
Location: include/linux/netdevice.h:2072
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8194870e)
Location: include/linux/netdevice.h:2072
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/gro_cells.c (ffffffff8199bf5e)
Location: include/linux/netdevice.h:2072
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
</ul>

## Differences
