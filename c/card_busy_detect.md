# Function: <code>card_busy_detect</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int card_busy_detect(struct mmc_card *card, unsigned int timeout_ms, u32 *resp_errs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/block.c (ffff800010b3ecb8)
Location: drivers/mmc/core/block.c:449
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_fix_state
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
```
**Symbols:**

```
ffff800010b3ecb8-ffff800010b3edcc: card_busy_detect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int card_busy_detect(struct mmc_card *card, unsigned int timeout_ms, u32 *resp_errs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/block.c (c0c19218)
Location: drivers/mmc/core/block.c:449
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_fix_state
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
```
**Symbols:**

```
c0c19218-c0c1931c: card_busy_detect (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int card_busy_detect(struct mmc_card *card, unsigned int timeout_ms, u32 *resp_errs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/block.c (ffffffe000715bc8)
Location: drivers/mmc/core/block.c:449
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_fix_state
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
```
**Symbols:**

```
ffffffe000715bc8-ffffffe000715ca0: card_busy_detect (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
