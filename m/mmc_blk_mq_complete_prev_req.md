# Function: <code>mmc_blk_mq_complete_prev_req</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/block.c (ffff800010b41614)
Location: drivers/mmc/core/block.c:2006
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_rw_wait
  - drivers/mmc/core/block.c:mmc_blk_mq_complete_work
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_rw_wait
  - drivers/mmc/core/block.c:mmc_blk_mq_complete_work
```
**Symbols:**

```
ffff800010b41398-ffff800010b415c4: mmc_blk_mq_complete_prev_req.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/block.c (c0c1c3b8)
Location: drivers/mmc/core/block.c:2006
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_rw_wait
  - drivers/mmc/core/block.c:mmc_blk_mq_complete_work
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_rw_wait
  - drivers/mmc/core/block.c:mmc_blk_mq_complete_work
```
**Symbols:**

```
c0c1c0f8-c0c1c350: mmc_blk_mq_complete_prev_req.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/block.c (ffffffe0007184fa)
Location: drivers/mmc/core/block.c:2006
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_rw_wait
  - drivers/mmc/core/block.c:mmc_blk_mq_complete_work
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_rw_wait
  - drivers/mmc/core/block.c:mmc_blk_mq_complete_work
```
**Symbols:**

```
ffffffe0007182f8-ffffffe0007184ac: mmc_blk_mq_complete_prev_req.part.0 (STB_LOCAL)
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
