# Function: <code>mmc_blk_rw_rq_prep</code>

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
void mmc_blk_rw_rq_prep(struct mmc_queue_req *mqrq, struct mmc_card *card, int disable_multi, struct mmc_queue *mq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/block.c (ffff800010b3f310)
Location: drivers/mmc/core/block.c:1544
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
```
**Symbols:**

```
ffff800010b3f310-ffff800010b3f498: mmc_blk_rw_rq_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mmc_blk_rw_rq_prep(struct mmc_queue_req *mqrq, struct mmc_card *card, int disable_multi, struct mmc_queue *mq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/block.c (c0c19a00)
Location: drivers/mmc/core/block.c:1544
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
```
**Symbols:**

```
c0c19a00-c0c19b8c: mmc_blk_rw_rq_prep (STB_LOCAL)
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
void mmc_blk_rw_rq_prep(struct mmc_queue_req *mqrq, struct mmc_card *card, int disable_multi, struct mmc_queue *mq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/block.c (ffffffe00071614c)
Location: drivers/mmc/core/block.c:1544
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
```
**Symbols:**

```
ffffffe00071614c-ffffffe00071628e: mmc_blk_rw_rq_prep (STB_LOCAL)
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
