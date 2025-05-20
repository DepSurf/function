# Function: <code>mmc_issue_type</code>

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
enum mmc_issue_type mmc_issue_type(struct mmc_queue *mq, struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/queue.c (ffff800010b43c80)
Location: drivers/mmc/core/queue.c:61
Inline: True
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_post_req
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
  - drivers/mmc/core/queue.c:mmc_mq_queue_rq
  - drivers/mmc/core/queue.c:mmc_mq_timed_out
```
**Symbols:**

```
ffff800010b43c80-ffff800010b43d2c: mmc_issue_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
enum mmc_issue_type mmc_issue_type(struct mmc_queue *mq, struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/queue.c (c0c1d920)
Location: drivers/mmc/core/queue.c:61
Inline: True
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_post_req
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
  - drivers/mmc/core/queue.c:mmc_mq_queue_rq
  - drivers/mmc/core/queue.c:mmc_mq_timed_out
```
**Symbols:**

```
c0c1d920-c0c1da14: mmc_issue_type (STB_GLOBAL)
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
enum mmc_issue_type mmc_issue_type(struct mmc_queue *mq, struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/queue.c (ffffffe000719738)
Location: drivers/mmc/core/queue.c:61
Inline: True
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_post_req
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
  - drivers/mmc/core/queue.c:mmc_mq_queue_rq
  - drivers/mmc/core/queue.c:mmc_mq_timed_out
```
**Symbols:**

```
ffffffe000719738-ffffffe0007197c4: mmc_issue_type (STB_GLOBAL)
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
