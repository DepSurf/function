# Function: <code>scsi_mq_get_budget</code>

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
bool scsi_mq_get_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b33f0)
Location: drivers/scsi/scsi_lib.c:1974
Inline: False
```
**Symbols:**

```
ffffffff816b33f0-ffffffff816b3504: scsi_mq_get_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool scsi_mq_get_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816f0b40)
Location: drivers/scsi/scsi_lib.c:2010
Inline: False
```
**Symbols:**

```
ffffffff816f0b40-ffffffff816f0c3f: scsi_mq_get_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool scsi_mq_get_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81713d60)
Location: drivers/scsi/scsi_lib.c:1669
Inline: False
```
**Symbols:**

```
ffffffff81713d60-ffffffff81713e36: scsi_mq_get_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool scsi_mq_get_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8174f470)
Location: drivers/scsi/scsi_lib.c:1619
Inline: False
```
**Symbols:**

```
ffffffff8174f470-ffffffff8174f53c: scsi_mq_get_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool scsi_mq_get_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81773650)
Location: drivers/scsi/scsi_lib.c:1631
Inline: False
```
**Symbols:**

```
ffffffff81773650-ffffffff8177371c: scsi_mq_get_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool scsi_mq_get_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81835970)
Location: drivers/scsi/scsi_lib.c:1619
Inline: False
```
**Symbols:**

```
ffffffff81835970-ffffffff818359f1: scsi_mq_get_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool scsi_mq_get_budget(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818464a0)
Location: drivers/scsi/scsi_lib.c:1614
Inline: False
```
**Symbols:**

```
ffffffff818464a0-ffffffff81846558: scsi_mq_get_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scsi_mq_get_budget(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81829840)
Location: drivers/scsi/scsi_lib.c:1592
Inline: False
```
**Symbols:**

```
ffffffff81829840-ffffffff81829953: scsi_mq_get_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int scsi_mq_get_budget(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:1594
Inline: False
```
**Symbols:**

```
ffffffff818b5160-ffffffff818b5298: scsi_mq_get_budget (STB_LOCAL)
ffffffff81d0c4a7-ffffffff81d0c502: scsi_mq_get_budget.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int scsi_mq_get_budget(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:1652
Inline: False
```
**Symbols:**

```
ffffffff81a00270-ffffffff81a003b1: scsi_mq_get_budget (STB_LOCAL)
ffffffff81ed541b-ffffffff81ed5477: scsi_mq_get_budget.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int scsi_mq_get_budget(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:1659
Inline: False
```
**Symbols:**

```
ffffffff81b7e870-ffffffff81b7e9b1: scsi_mq_get_budget (STB_LOCAL)
ffffffff8209ba23-ffffffff8209ba7f: scsi_mq_get_budget.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int scsi_mq_get_budget(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:1664
Inline: False
```
**Symbols:**

```
ffffffff81bd26a0-ffffffff81bd27e4: scsi_mq_get_budget (STB_LOCAL)
ffffffff8211c8ba-ffffffff8211c916: scsi_mq_get_budget.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int scsi_mq_get_budget(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:1661
Inline: False
```
**Symbols:**

```
ffffffff81c27330-ffffffff81c27460: scsi_mq_get_budget (STB_LOCAL)
ffffffff821fa76a-ffffffff821fa7c6: scsi_mq_get_budget.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool scsi_mq_get_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff800010977250)
Location: drivers/scsi/scsi_lib.c:1631
Inline: False
```
**Symbols:**

```
ffff800010977250-ffff800010977398: scsi_mq_get_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool scsi_mq_get_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a4b538)
Location: drivers/scsi/scsi_lib.c:1631
Inline: False
```
**Symbols:**

```
c0a4b538-c0a4b658: scsi_mq_get_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool scsi_mq_get_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a31550)
Location: drivers/scsi/scsi_lib.c:1631
Inline: False
```
**Symbols:**

```
c000000000a31550-c000000000a316e4: scsi_mq_get_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool scsi_mq_get_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005df124)
Location: drivers/scsi/scsi_lib.c:1631
Inline: False
```
**Symbols:**

```
ffffffe0005df124-ffffffe0005df202: scsi_mq_get_budget (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool scsi_mq_get_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81727d40)
Location: drivers/scsi/scsi_lib.c:1631
Inline: False
```
**Symbols:**

```
ffffffff81727d40-ffffffff81727e0c: scsi_mq_get_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool scsi_mq_get_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81701170)
Location: drivers/scsi/scsi_lib.c:1631
Inline: False
```
**Symbols:**

```
ffffffff81701170-ffffffff8170123c: scsi_mq_get_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool scsi_mq_get_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81766b10)
Location: drivers/scsi/scsi_lib.c:1631
Inline: False
```
**Symbols:**

```
ffffffff81766b10-ffffffff81766bdc: scsi_mq_get_budget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool scsi_mq_get_budget(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81782220)
Location: drivers/scsi/scsi_lib.c:1631
Inline: False
```
**Symbols:**

```
ffffffff81782220-ffffffff817822ec: scsi_mq_get_budget (STB_LOCAL)
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
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
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
