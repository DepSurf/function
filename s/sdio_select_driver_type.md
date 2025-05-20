# Function: <code>sdio_select_driver_type</code>

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
In drivers/mmc/core/sdio.c (ffffffff816c94dc)
Location: drivers/mmc/core/sdio.c:403
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
In drivers/mmc/core/sdio.c (ffffffff8172c49e)
Location: drivers/mmc/core/sdio.c:401
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
In drivers/mmc/core/sdio.c (ffffffff8175f653)
Location: drivers/mmc/core/sdio.c:402
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
In drivers/mmc/core/sdio.c (ffffffff8177de51)
Location: drivers/mmc/core/sdio.c:405
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
In drivers/mmc/core/sdio.c (ffffffff817f43d9)
Location: drivers/mmc/core/sdio.c:405
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
In drivers/mmc/core/sdio.c (ffffffff8183d8b1)
Location: drivers/mmc/core/sdio.c:405
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
In drivers/mmc/core/sdio.c (ffffffff81869856)
Location: drivers/mmc/core/sdio.c:405
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
In drivers/mmc/core/sdio.c (ffffffff818ad6e3)
Location: drivers/mmc/core/sdio.c:401
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
In drivers/mmc/core/sdio.c (ffffffff818dfb46)
Location: drivers/mmc/core/sdio.c:401
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
void sdio_select_driver_type(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff819b21c0)
Location: drivers/mmc/core/sdio.c:419
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff819b21c0-ffffffff819b22af: sdio_select_driver_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sdio_select_driver_type(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff819b4700)
Location: drivers/mmc/core/sdio.c:465
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff819b4700-ffffffff819b47ef: sdio_select_driver_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff8199988b)
Location: drivers/mmc/core/sdio.c:465
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81a4601e)
Location: drivers/mmc/core/sdio.c:465
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81bb3dac)
Location: drivers/mmc/core/sdio.c:466
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81d5838f)
Location: drivers/mmc/core/sdio.c:480
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81dc2d28)
Location: drivers/mmc/core/sdio.c:480
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81e7b5e8)
Location: drivers/mmc/core/sdio.c:480
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffff800010b39cf0)
Location: drivers/mmc/core/sdio.c:401
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
In drivers/mmc/core/sdio.c (c0c14740)
Location: drivers/mmc/core/sdio.c:401
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
In drivers/mmc/core/sdio.c (c000000000c363c8)
Location: drivers/mmc/core/sdio.c:401
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
In drivers/mmc/core/sdio.c (ffffffe000711934)
Location: drivers/mmc/core/sdio.c:401
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
In drivers/mmc/core/sdio.c (ffffffff81883506)
Location: drivers/mmc/core/sdio.c:401
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
In drivers/mmc/core/sdio.c (ffffffff818d49a6)
Location: drivers/mmc/core/sdio.c:401
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
In drivers/mmc/core/sdio.c (ffffffff818f14c6)
Location: drivers/mmc/core/sdio.c:401
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
</ul>
