# Function: <code>mmc_blk_part_switch_post</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int mmc_blk_part_switch_post(struct mmc_card *card, unsigned int part_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/block.c (ffff800010b3fdf0)
Location: drivers/mmc/core/block.c:853
Inline: True
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
```
**Symbols:**

```
ffff800010b3fdf0-ffff800010b3fe48: mmc_blk_part_switch_post (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mmc_blk_part_switch_post(struct mmc_card *card, unsigned int part_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/block.c (c0c1a6e8)
Location: drivers/mmc/core/block.c:853
Inline: True
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_reset
  - drivers/mmc/core/block.c:mmc_blk_reset
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
```
**Symbols:**

```
c0c1a6e8-c0c1a73c: mmc_blk_part_switch_post (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int mmc_blk_part_switch_post(struct mmc_card *card, unsigned int part_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/block.c (ffffffe000716d84)
Location: drivers/mmc/core/block.c:853
Inline: True
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_reset
  - drivers/mmc/core/block.c:mmc_blk_reset
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
```
**Symbols:**

```
ffffffe000716d84-ffffffe000716dd6: mmc_blk_part_switch_post (STB_LOCAL)
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
