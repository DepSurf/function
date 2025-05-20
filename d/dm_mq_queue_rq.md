# Function: <code>dm_mq_queue_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a3f00)
Location: drivers/md/dm.c:2648
Inline: False
```
**Symbols:**

```
ffffffff816a3f00-ffffffff816a40ff: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8170f890)
Location: drivers/md/dm-rq.c:858
Inline: False
```
**Symbols:**

```
ffffffff8170f890-ffffffff8170f9bf: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff817418a0)
Location: drivers/md/dm-rq.c:876
Inline: False
```
**Symbols:**

```
ffffffff817418a0-ffffffff817419b5: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8175b060)
Location: drivers/md/dm-rq.c:730
Inline: False
```
**Symbols:**

```
ffffffff8175b060-ffffffff8175b189: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff817cd2b0)
Location: drivers/md/dm-rq.c:727
Inline: False
```
**Symbols:**

```
ffffffff817cd2b0-ffffffff817cd3dc: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818160c0)
Location: drivers/md/dm-rq.c:741
Inline: False
```
**Symbols:**

```
ffffffff818160c0-ffffffff818161d8: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81841bb0)
Location: drivers/md/dm-rq.c:471
Inline: False
```
**Symbols:**

```
ffffffff81841bb0-ffffffff81841f72: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (0)
Location: drivers/md/dm-rq.c:490
Inline: False
```
**Symbols:**

```
ffffffff818849e0-ffffffff81884dd0: dm_mq_queue_rq (STB_LOCAL)
ffffffff8188520d-ffffffff8188521d: dm_mq_queue_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818b6b70)
Location: drivers/md/dm-rq.c:491
Inline: False
```
**Symbols:**

```
ffffffff818b6b70-ffffffff818b6d41: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81987430)
Location: drivers/md/dm-rq.c:484
Inline: False
```
**Symbols:**

```
ffffffff81987430-ffffffff81987632: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8198b3d0)
Location: drivers/md/dm-rq.c:485
Inline: False
```
**Symbols:**

```
ffffffff8198b3d0-ffffffff8198b5ca: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8196fac0)
Location: drivers/md/dm-rq.c:485
Inline: False
```
**Symbols:**

```
ffffffff8196fac0-ffffffff8196fcba: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81a18400)
Location: drivers/md/dm-rq.c:485
Inline: False
```
**Symbols:**

```
ffffffff81a18400-ffffffff81a185f8: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81b81110)
Location: drivers/md/dm-rq.c:473
Inline: False
```
**Symbols:**

```
ffffffff81b81110-ffffffff81b8133c: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81d1f440)
Location: drivers/md/dm-rq.c:474
Inline: False
```
**Symbols:**

```
ffffffff81d1f440-ffffffff81d1f66c: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81d88620)
Location: drivers/md/dm-rq.c:477
Inline: False
```
**Symbols:**

```
ffffffff81d88620-ffffffff81d8884c: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81e3fd30)
Location: drivers/md/dm-rq.c:477
Inline: False
```
**Symbols:**

```
ffffffff81e3fd30-ffffffff81e3ff5c: dm_mq_queue_rq (STB_LOCAL)
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
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffff800010b0ebc0)
Location: drivers/md/dm-rq.c:491
Inline: False
```
**Symbols:**

```
ffff800010b0ebc0-ffff800010b0ed50: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (c0becfa8)
Location: drivers/md/dm-rq.c:491
Inline: False
```
**Symbols:**

```
c0becfa8-c0bed13c: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (c000000000c01d80)
Location: drivers/md/dm-rq.c:491
Inline: False
```
**Symbols:**

```
c000000000c01d80-c000000000c01f9c: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffe0006fbe28)
Location: drivers/md/dm-rq.c:491
Inline: False
```
**Symbols:**

```
ffffffe0006fbe28-ffffffe0006fbf8c: dm_mq_queue_rq (STB_LOCAL)
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
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8185c9f0)
Location: drivers/md/dm-rq.c:491
Inline: False
```
**Symbols:**

```
ffffffff8185c9f0-ffffffff8185cbc1: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81823fc0)
Location: drivers/md/dm-rq.c:491
Inline: False
```
**Symbols:**

```
ffffffff81823fc0-ffffffff81824191: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818ac020)
Location: drivers/md/dm-rq.c:491
Inline: False
```
**Symbols:**

```
ffffffff818ac020-ffffffff818ac1f1: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
blk_status_t dm_mq_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818c8270)
Location: drivers/md/dm-rq.c:491
Inline: False
```
**Symbols:**

```
ffffffff818c8270-ffffffff818c8441: dm_mq_queue_rq (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>blk_status_t</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
