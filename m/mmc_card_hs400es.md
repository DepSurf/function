# Function: <code>mmc_card_hs400es</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: include/linux/mmc/host.h:525
Inline: True
```
```
In drivers/mmc/core/debugfs.c (ffffffff817303e3)
Location: include/linux/mmc/host.h:525
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (0)
Location: include/linux/mmc/host.h:522
Inline: True
```
```
In drivers/mmc/core/bus.c (0)
Location: include/linux/mmc/host.h:522
Inline: True
```
```
In drivers/mmc/core/mmc.c (0)
Location: include/linux/mmc/host.h:522
Inline: True
```
```
In drivers/mmc/core/debugfs.c (ffffffff817633e0)
Location: include/linux/mmc/host.h:522
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/host.h:66
Inline: True
```
```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/host.h:66
Inline: True
```
```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/host.h:66
Inline: True
```
```
In drivers/mmc/core/debugfs.c (ffffffff81781a47)
Location: drivers/mmc/core/host.h:66
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/host.h:72
Inline: True
```
```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/host.h:72
Inline: True
```
```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/host.h:72
Inline: True
```
```
In drivers/mmc/core/debugfs.c (ffffffff817f801c)
Location: drivers/mmc/core/host.h:72
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (ffffffff81831ed9)
Location: drivers/mmc/core/host.h:78
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
```
```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/host.h:78
Inline: True
```
```
In drivers/mmc/core/mmc.c (ffffffff81837551)
Location: drivers/mmc/core/host.h:78
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/debugfs.c (ffffffff818415ed)
Location: drivers/mmc/core/host.h:78
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (ffffffff8185deb9)
Location: drivers/mmc/core/host.h:78
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
```
```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/host.h:78
Inline: True
```
```
In drivers/mmc/core/mmc.c (ffffffff81863521)
Location: drivers/mmc/core/host.h:78
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/debugfs.c (ffffffff8186d440)
Location: drivers/mmc/core/host.h:78
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (ffffffff818a1b2c)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
```
```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/host.h:75
Inline: True
```
```
In drivers/mmc/core/mmc.c (ffffffff818a769a)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/debugfs.c (ffffffff818b167f)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (ffffffff818d3e2c)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
```
```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/host.h:75
Inline: True
```
```
In drivers/mmc/core/mmc.c (ffffffff818d9afa)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/debugfs.c (ffffffff818e3b1f)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (ffffffff819a5fbe)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
```
```
In drivers/mmc/core/bus.c (ffffffff819a950c)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff819ac8ca)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/debugfs.c (ffffffff819b6c2b)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (ffffffff819a8d6e)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
```
```
In drivers/mmc/core/bus.c (ffffffff81c2a421)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff819af49a)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/debugfs.c (ffffffff819b912b)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (ffffffff8198da3c)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
```
```
In drivers/mmc/core/bus.c (ffffffff81c1c7df)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff81993c6e)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/debugfs.c (ffffffff8199d85c)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (ffffffff81a390ca)
Location: drivers/mmc/core/host.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
```
```
In drivers/mmc/core/bus.c (ffffffff81d2d3b2)
Location: drivers/mmc/core/host.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff81a3f88f)
Location: drivers/mmc/core/host.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/debugfs.c (ffffffff81a4a2de)
Location: drivers/mmc/core/host.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (ffffffff81ba618a)
Location: drivers/mmc/core/host.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
```
```
In drivers/mmc/core/bus.c (ffffffff81ef96e8)
Location: drivers/mmc/core/host.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff81bacb38)
Location: drivers/mmc/core/host.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/debugfs.c (ffffffff81bb8760)
Location: drivers/mmc/core/host.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (ffffffff81d4864a)
Location: drivers/mmc/core/host.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
```
```
In drivers/mmc/core/bus.c (ffffffff81d4b96e)
Location: drivers/mmc/core/host.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff81d4ffa3)
Location: drivers/mmc/core/host.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/debugfs.c (ffffffff81d5d860)
Location: drivers/mmc/core/host.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (ffffffff81db2f4a)
Location: drivers/mmc/core/host.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
```
```
In drivers/mmc/core/bus.c (ffffffff81db621e)
Location: drivers/mmc/core/host.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff81dba903)
Location: drivers/mmc/core/host.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/debugfs.c (ffffffff81dc8446)
Location: drivers/mmc/core/host.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (ffffffff81e6b31a)
Location: drivers/mmc/core/host.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
```
```
In drivers/mmc/core/bus.c (ffffffff81e6e6b5)
Location: drivers/mmc/core/host.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/mmc.c (ffffffff81e7302c)
Location: drivers/mmc/core/host.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/debugfs.c (ffffffff81e80f16)
Location: drivers/mmc/core/host.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (ffff800010b2d47c)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
```
```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/host.h:75
Inline: True
```
```
In drivers/mmc/core/mmc.c (ffff800010b33f9c)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/debugfs.c (ffff800010b3e9ec)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (c0c087c0)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
```
```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/host.h:75
Inline: True
```
```
In drivers/mmc/core/mmc.c (c0c0ea44)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/debugfs.c (c0c18e8c)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (c000000000c26588)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
```
```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/host.h:75
Inline: True
```
```
In drivers/mmc/core/mmc.c (c000000000c2e74c)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/debugfs.c (c000000000c3c670)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (ffffffe0007073d6)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
```
```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/host.h:75
Inline: True
```
```
In drivers/mmc/core/mmc.c (ffffffe00070c5d4)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/debugfs.c (ffffffe00071586a)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (ffffffff818777ec)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
```
```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/host.h:75
Inline: True
```
```
In drivers/mmc/core/mmc.c (ffffffff8187d4ba)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/debugfs.c (ffffffff818874df)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (ffffffff818c8c8c)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
```
```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/host.h:75
Inline: True
```
```
In drivers/mmc/core/mmc.c (ffffffff818ce95a)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/debugfs.c (ffffffff818d897f)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
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
In drivers/mmc/core/core.c (ffffffff818e57ac)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_set_blocklen
```
```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/host.h:75
Inline: True
```
```
In drivers/mmc/core/mmc.c (ffffffff818eb47a)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/debugfs.c (ffffffff818f549f)
Location: drivers/mmc/core/host.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_ios_show
```
</details>
</li>
</ul>

## Differences
