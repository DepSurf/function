# Function: <code>scsi_mq_put_budget</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b2260)
Location: drivers/scsi/scsi_lib.c:1965
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff816b2260-ffffffff816b2289: scsi_mq_put_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816ee500)
Location: drivers/scsi/scsi_lib.c:2001
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff816ee500-ffffffff816ee529: scsi_mq_put_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817120a0)
Location: drivers/scsi/scsi_lib.c:1660
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff817120a0-ffffffff817120c6: scsi_mq_put_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817508a9)
Location: drivers/scsi/scsi_lib.c:1611
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff8174d9a0-ffffffff8174d9ba: scsi_mq_put_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81774acc)
Location: drivers/scsi/scsi_lib.c:1623
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81771b10-ffffffff81771b2a: scsi_mq_put_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81837e10)
Location: drivers/scsi/scsi_lib.c:1611
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81834350-ffffffff8183436a: scsi_mq_put_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void scsi_mq_put_budget(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8184878b)
Location: drivers/scsi/scsi_lib.c:1607
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81844cd0-ffffffff81844ce3: scsi_mq_put_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void scsi_mq_put_budget(struct request_queue *q, int budget_token);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8182bac4)
Location: drivers/scsi/scsi_lib.c:1585
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff8182a3f0-ffffffff8182a444: scsi_mq_put_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_mq_put_budget(struct request_queue *q, int budget_token);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b7657)
Location: drivers/scsi/scsi_lib.c:1587
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff818b6000-ffffffff818b6085: scsi_mq_put_budget (STB_LOCAL)
ffffffff81d0c517-ffffffff81d0c571: scsi_mq_put_budget.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_mq_put_budget(struct request_queue *q, int budget_token);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a02d4d)
Location: drivers/scsi/scsi_lib.c:1645
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81a01540-ffffffff81a015cf: scsi_mq_put_budget (STB_LOCAL)
ffffffff81ed5477-ffffffff81ed54d1: scsi_mq_put_budget.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_mq_put_budget(struct request_queue *q, int budget_token);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b81787)
Location: drivers/scsi/scsi_lib.c:1645
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81b7fb70-ffffffff81b7fbff: scsi_mq_put_budget (STB_LOCAL)
ffffffff8209baa2-ffffffff8209bafc: scsi_mq_put_budget.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_mq_put_budget(struct request_queue *q, int budget_token);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd548d)
Location: drivers/scsi/scsi_lib.c:1650
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81bd3a90-ffffffff81bd3b22: scsi_mq_put_budget (STB_LOCAL)
ffffffff8211c939-ffffffff8211c993: scsi_mq_put_budget.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scsi_mq_put_budget(struct request_queue *q, int budget_token);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c2a0e5)
Location: drivers/scsi/scsi_lib.c:1647
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81c28720-ffffffff81c287ae: scsi_mq_put_budget (STB_LOCAL)
ffffffff821fa7e9-ffffffff821fa843: scsi_mq_put_budget.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff800010978b20)
Location: drivers/scsi/scsi_lib.c:1623
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffff800010977000-ffff80001097705c: scsi_mq_put_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a4cafc)
Location: drivers/scsi/scsi_lib.c:1623
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
c0a49820-c0a4985c: scsi_mq_put_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a332bc)
Location: drivers/scsi/scsi_lib.c:1623
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
c000000000a2eff0-c000000000a2f018: scsi_mq_put_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005e048c)
Location: drivers/scsi/scsi_lib.c:1623
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffe0005dd8a4-ffffffe0005dd8d2: scsi_mq_put_budget (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817291bc)
Location: drivers/scsi/scsi_lib.c:1623
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81726200-ffffffff8172621a: scsi_mq_put_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817025ec)
Location: drivers/scsi/scsi_lib.c:1623
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff816ff630-ffffffff816ff64a: scsi_mq_put_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81767f8c)
Location: drivers/scsi/scsi_lib.c:1623
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81764fd0-ffffffff81764fea: scsi_mq_put_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void scsi_mq_put_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817836c9)
Location: drivers/scsi/scsi_lib.c:1623
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81780650-ffffffff8178066a: scsi_mq_put_budget (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param removed. </b>
<code>struct blk_mq_hw_ctx *hctx</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int budget_token</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
