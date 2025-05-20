# Function: <code>sdio_set_bus_speed_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff816c952c)
Location: drivers/mmc/core/sdio.c:440
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff8172c4ee)
Location: drivers/mmc/core/sdio.c:438
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff8175f6a3)
Location: drivers/mmc/core/sdio.c:439
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff8177de9c)
Location: drivers/mmc/core/sdio.c:442
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff817f441a)
Location: drivers/mmc/core/sdio.c:442
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff8183d8ef)
Location: drivers/mmc/core/sdio.c:442
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81869894)
Location: drivers/mmc/core/sdio.c:442
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff818ad721)
Location: drivers/mmc/core/sdio.c:438
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff818dfb84)
Location: drivers/mmc/core/sdio.c:438
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sdio_set_bus_speed_mode(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff819b1ed0)
Location: drivers/mmc/core/sdio.c:456
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff819b1ed0-ffffffff819b20f1: sdio_set_bus_speed_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sdio_set_bus_speed_mode(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff819b42a0)
Location: drivers/mmc/core/sdio.c:502
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff819b42a0-ffffffff819b44c3: sdio_set_bus_speed_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sdio_set_bus_speed_mode(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81998940)
Location: drivers/mmc/core/sdio.c:502
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81998940-ffffffff81998b55: sdio_set_bus_speed_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sdio_set_bus_speed_mode(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81a45060)
Location: drivers/mmc/core/sdio.c:502
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81a45060-ffffffff81a45275: sdio_set_bus_speed_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sdio_set_bus_speed_mode(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81bb2d70)
Location: drivers/mmc/core/sdio.c:503
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81bb2d70-ffffffff81bb2f81: sdio_set_bus_speed_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sdio_set_bus_speed_mode(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81d57190)
Location: drivers/mmc/core/sdio.c:517
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81d57190-ffffffff81d573a1: sdio_set_bus_speed_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sdio_set_bus_speed_mode(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81dc1b10)
Location: drivers/mmc/core/sdio.c:517
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81dc1b10-ffffffff81dc1d21: sdio_set_bus_speed_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sdio_set_bus_speed_mode(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81e7a3d0)
Location: drivers/mmc/core/sdio.c:517
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81e7a3d0-ffffffff81e7a5e1: sdio_set_bus_speed_mode (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffff800010b39d1c)
Location: drivers/mmc/core/sdio.c:438
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (c0c14774)
Location: drivers/mmc/core/sdio.c:438
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (c000000000c36400)
Location: drivers/mmc/core/sdio.c:438
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffe000711960)
Location: drivers/mmc/core/sdio.c:438
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81883544)
Location: drivers/mmc/core/sdio.c:438
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
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff818d49e4)
Location: drivers/mmc/core/sdio.c:438
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff818f1504)
Location: drivers/mmc/core/sdio.c:438
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
