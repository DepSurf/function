# Function: <code>mmc_card_hs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: include/linux/mmc/host.h:477
Inline: True
```
```
In drivers/mmc/core/mmc.c (ffffffff816c393c)
Location: include/linux/mmc/host.h:477
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (ffffffff816c7845)
Location: include/linux/mmc/host.h:477
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff816c91bd)
Location: include/linux/mmc/host.h:477
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff8172467c)
Location: include/linux/mmc/host.h:498
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff81726a7a)
Location: include/linux/mmc/host.h:498
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (ffffffff8172a93d)
Location: include/linux/mmc/host.h:498
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff8172c17f)
Location: include/linux/mmc/host.h:498
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff817575fc)
Location: include/linux/mmc/host.h:495
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff81759713)
Location: include/linux/mmc/host.h:495
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (ffffffff8175d849)
Location: include/linux/mmc/host.h:495
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff8175f334)
Location: include/linux/mmc/host.h:495
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81775498)
Location: include/linux/mmc/host.h:482
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff8177866b)
Location: include/linux/mmc/host.h:482
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (ffffffff8177c10c)
Location: include/linux/mmc/host.h:482
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff8177dd2c)
Location: include/linux/mmc/host.h:482
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/bus.c (ffffffff817eb778)
Location: include/linux/mmc/host.h:537
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff817eea68)
Location: include/linux/mmc/host.h:537
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (ffffffff817f29ee)
Location: include/linux/mmc/host.h:537
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff817f42b4)
Location: include/linux/mmc/host.h:537
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/bus.c (ffffffff81834982)
Location: include/linux/mmc/host.h:542
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff8183785e)
Location: include/linux/mmc/host.h:542
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (ffffffff8183bb0b)
Location: include/linux/mmc/host.h:542
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff8183d7ce)
Location: include/linux/mmc/host.h:542
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/bus.c (ffffffff81860912)
Location: include/linux/mmc/host.h:549
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff818637e9)
Location: include/linux/mmc/host.h:549
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (ffffffff81867a9b)
Location: include/linux/mmc/host.h:549
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff81869773)
Location: include/linux/mmc/host.h:549
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/bus.c (ffffffff818a473f)
Location: include/linux/mmc/host.h:544
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff818a7b8b)
Location: include/linux/mmc/host.h:544
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (ffffffff818ab95f)
Location: include/linux/mmc/host.h:544
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff818ad5c1)
Location: include/linux/mmc/host.h:544
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/bus.c (ffffffff818d6bc8)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff818d9ff2)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (ffffffff818dddaf)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff818dfa24)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/bus.c (ffffffff819a9528)
Location: include/linux/mmc/host.h:564
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff819acc30)
Location: include/linux/mmc/host.h:564
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (ffffffff819b0b25)
Location: include/linux/mmc/host.h:564
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff819b2dc1)
Location: include/linux/mmc/host.h:564
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/bus.c (ffffffff81c2a43d)
Location: include/linux/mmc/host.h:575
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff819af852)
Location: include/linux/mmc/host.h:575
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (ffffffff819b3095)
Location: include/linux/mmc/host.h:575
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff819b5311)
Location: include/linux/mmc/host.h:575
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/bus.c (ffffffff81c1c7fb)
Location: include/linux/mmc/host.h:593
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff81993fc8)
Location: include/linux/mmc/host.h:593
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (ffffffff81997875)
Location: include/linux/mmc/host.h:593
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff819997ee)
Location: include/linux/mmc/host.h:593
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/bus.c (ffffffff81d2d45d)
Location: include/linux/mmc/host.h:594
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff81a3fc28)
Location: include/linux/mmc/host.h:594
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (ffffffff81a43f58)
Location: include/linux/mmc/host.h:594
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff81a45f81)
Location: include/linux/mmc/host.h:594
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/bus.c (ffffffff81ef98ba)
Location: include/linux/mmc/host.h:597
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff81bace84)
Location: include/linux/mmc/host.h:597
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (ffffffff81bb19da)
Location: include/linux/mmc/host.h:597
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff81bb3ca1)
Location: include/linux/mmc/host.h:597
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/bus.c (ffffffff81d4b875)
Location: include/linux/mmc/host.h:617
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff81d50369)
Location: include/linux/mmc/host.h:617
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (ffffffff81d55a34)
Location: include/linux/mmc/host.h:617
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff81d58275)
Location: include/linux/mmc/host.h:617
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/bus.c (ffffffff81db614c)
Location: include/linux/mmc/host.h:621
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff81dbad2e)
Location: include/linux/mmc/host.h:621
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (ffffffff81dc03a4)
Location: include/linux/mmc/host.h:621
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff81dc2c16)
Location: include/linux/mmc/host.h:621
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/bus.c (ffffffff81e6e5e3)
Location: include/linux/mmc/host.h:628
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff81e734f5)
Location: include/linux/mmc/host.h:628
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (ffffffff81e78d35)
Location: include/linux/mmc/host.h:628
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff81e7b4d6)
Location: include/linux/mmc/host.h:628
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/bus.c (ffff800010b30ae4)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffff800010b34400)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (ffff800010b38124)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffff800010b39bd8)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/bus.c (c0c0b82c)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (c0c0ef2c)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (c0c129fc)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (c0c145fc)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/bus.c (c000000000c2a5ac)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (c000000000c2ee34)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (c000000000c33c28)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (c000000000c3628c)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/bus.c (ffffffe0007095b0)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffe00070cbce)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (ffffffe00070ff82)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffe00071182c)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/bus.c (ffffffff8187a588)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff8187d9b2)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (ffffffff8188176f)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff818833e4)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff818cba28)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff818cee52)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (ffffffff818d2c0f)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff818d4884)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/bus.c (ffffffff818e8548)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff818eb972)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
```
```
In drivers/mmc/core/sd.c (ffffffff818ef72f)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff818f13a4)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
</ul>

## Differences
