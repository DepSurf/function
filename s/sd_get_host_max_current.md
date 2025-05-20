# Function: <code>sd_get_host_max_current</code>

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
In drivers/mmc/core/sd.c (ffffffff816c6d5e)
Location: drivers/mmc/core/sd.c:495
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sd.c:mmc_sd_init_card
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
In drivers/mmc/core/sd.c (ffffffff8172a7ed)
Location: drivers/mmc/core/sd.c:494
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
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
In drivers/mmc/core/sd.c (ffffffff8175d9bd)
Location: drivers/mmc/core/sd.c:494
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
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
In drivers/mmc/core/sd.c (ffffffff8177c091)
Location: drivers/mmc/core/sd.c:489
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
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
In drivers/mmc/core/sd.c (ffffffff817f205e)
Location: drivers/mmc/core/sd.c:489
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
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
In drivers/mmc/core/sd.c (ffffffff8183acd6)
Location: drivers/mmc/core/sd.c:487
Inline: True
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
In drivers/mmc/core/sd.c (ffffffff81866c46)
Location: drivers/mmc/core/sd.c:487
Inline: True
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
In drivers/mmc/core/sd.c (ffffffff818ab0e7)
Location: drivers/mmc/core/sd.c:507
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
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
In drivers/mmc/core/sd.c (ffffffff818dd537)
Location: drivers/mmc/core/sd.c:507
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff819b0627)
Location: drivers/mmc/core/sd.c:507
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff819b2b97)
Location: drivers/mmc/core/sd.c:507
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
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
In drivers/mmc/core/sd.c (ffffffff81997387)
Location: drivers/mmc/core/sd.c:513
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u32 sd_get_host_max_current(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:523
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff81a42830-ffffffff81a428c0: sd_get_host_max_current (STB_LOCAL)
ffffffff81d2e068-ffffffff81d2e087: sd_get_host_max_current.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u32 sd_get_host_max_current(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:532
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff81bb00d0-ffffffff81bb0190: sd_get_host_max_current (STB_LOCAL)
ffffffff81efa4a0-ffffffff81efa4bf: sd_get_host_max_current.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u32 sd_get_host_max_current(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:532
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff81d53db0-ffffffff81d53e70: sd_get_host_max_current (STB_LOCAL)
ffffffff820a9a5e-ffffffff820a9a7d: sd_get_host_max_current.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u32 sd_get_host_max_current(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:532
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff81dbe770-ffffffff81dbe7fd: sd_get_host_max_current (STB_LOCAL)
ffffffff8212ae40-ffffffff8212ae65: sd_get_host_max_current.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u32 sd_get_host_max_current(struct mmc_host *host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:532
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
**Symbols:**

```
ffffffff81e765a0-ffffffff81e7662d: sd_get_host_max_current (STB_LOCAL)
ffffffff8220cbfd-ffffffff8220cc22: sd_get_host_max_current.cold (STB_LOCAL)
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
In drivers/mmc/core/sd.c (ffff800010b37828)
Location: drivers/mmc/core/sd.c:507
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
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
In drivers/mmc/core/sd.c (c0c12184)
Location: drivers/mmc/core/sd.c:507
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
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
In drivers/mmc/core/sd.c (c000000000c330ac)
Location: drivers/mmc/core/sd.c:507
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
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
In drivers/mmc/core/sd.c (ffffffe00070f732)
Location: drivers/mmc/core/sd.c:507
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
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
In drivers/mmc/core/sd.c (ffffffff81880ef7)
Location: drivers/mmc/core/sd.c:507
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
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
In drivers/mmc/core/sd.c (ffffffff818d2397)
Location: drivers/mmc/core/sd.c:507
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
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
In drivers/mmc/core/sd.c (ffffffff818eeeb7)
Location: drivers/mmc/core/sd.c:507
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
