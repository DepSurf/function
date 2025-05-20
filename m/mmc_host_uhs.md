# Function: <code>mmc_host_uhs</code>

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
In drivers/mmc/core/sd.c (0)
Location: include/linux/mmc/host.h:464
Inline: True
```
```
In drivers/mmc/core/sdio.c (0)
Location: include/linux/mmc/host.h:464
Inline: True
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
In drivers/mmc/core/sd.c (0)
Location: include/linux/mmc/host.h:485
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff8172c358)
Location: include/linux/mmc/host.h:485
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
In drivers/mmc/core/sd.c (0)
Location: include/linux/mmc/host.h:487
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff8175f50d)
Location: include/linux/mmc/host.h:487
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
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/host.h:43
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff8177da52)
Location: drivers/mmc/core/host.h:43
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
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/host.h:49
Inline: True
```
```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/host.h:49
Inline: True
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
In drivers/mmc/core/sd.c (ffffffff8183ba1c)
Location: drivers/mmc/core/host.h:54
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff8183d02e)
Location: drivers/mmc/core/host.h:54
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/sd.c (ffffffff818679ac)
Location: drivers/mmc/core/host.h:54
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
```
In drivers/mmc/core/sdio.c (ffffffff81868fbe)
Location: drivers/mmc/core/host.h:54
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/sd.c (ffffffff818ab85e)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
```
In drivers/mmc/core/sdio.c (ffffffff818ace2c)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/sd.c (ffffffff818ddcae)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
```
In drivers/mmc/core/sdio.c (ffffffff818df27c)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/sd.c (ffffffff819b0a90)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
```
In drivers/mmc/core/sdio.c (ffffffff819b2922)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:sdio_read_cccr
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
In drivers/mmc/core/sd.c (ffffffff819b3000)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
```
In drivers/mmc/core/sdio.c (ffffffff819b4e72)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:sdio_read_cccr
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
In drivers/mmc/core/sd.c (ffffffff819977e0)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
```
In drivers/mmc/core/sdio.c (ffffffff81999352)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:sdio_read_cccr
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
In drivers/mmc/core/sd.c (ffffffff81a43e90)
Location: drivers/mmc/core/host.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
```
In drivers/mmc/core/sdio.c (ffffffff81a45ac3)
Location: drivers/mmc/core/host.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:sdio_read_cccr
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
In drivers/mmc/core/sd.c (ffffffff81bb190e)
Location: drivers/mmc/core/host.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
```
In drivers/mmc/core/sdio.c (ffffffff81bb3832)
Location: drivers/mmc/core/host.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:sdio_read_cccr
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
In drivers/mmc/core/sd.c (ffffffff81d55a0d)
Location: drivers/mmc/core/host.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
```
In drivers/mmc/core/sdio.c (ffffffff81d57de2)
Location: drivers/mmc/core/host.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:sdio_read_cccr
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
In drivers/mmc/core/sd.c (ffffffff81dc037d)
Location: drivers/mmc/core/host.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
```
In drivers/mmc/core/sdio.c (ffffffff81dc2782)
Location: drivers/mmc/core/host.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:sdio_read_cccr
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
In drivers/mmc/core/sd.c (ffffffff81e78c87)
Location: drivers/mmc/core/host.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
```
In drivers/mmc/core/sdio.c (ffffffff81e7b042)
Location: drivers/mmc/core/host.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/sdio.c:sdio_read_cccr
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
In drivers/mmc/core/sd.c (ffff800010b38024)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
```
In drivers/mmc/core/sdio.c (ffff800010b394c8)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/sd.c (c0c12938)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
```
In drivers/mmc/core/sdio.c (c0c13df8)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/sd.c (c000000000c33b5c)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
```
In drivers/mmc/core/sdio.c (c000000000c358f4)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/sd.c (ffffffe00070feee)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
```
In drivers/mmc/core/sdio.c (ffffffe000711192)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/sd.c (ffffffff8188166e)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
```
In drivers/mmc/core/sdio.c (ffffffff81882c3c)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/sd.c (ffffffff818d2b0e)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
```
In drivers/mmc/core/sdio.c (ffffffff818d40dc)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
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
In drivers/mmc/core/sd.c (ffffffff818ef62e)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
```
In drivers/mmc/core/sdio.c (ffffffff818f0bfc)
Location: drivers/mmc/core/host.h:51
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
</ul>

## Differences
