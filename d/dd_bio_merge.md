# Function: <code>dd_bio_merge</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool dd_bio_merge(struct blk_mq_hw_ctx *hctx, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff814c83d0)
Location: block/mq-deadline.c:471
Inline: False
```
**Symbols:**

```
ffffffff814c83d0-ffffffff814c8464: dd_bio_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool dd_bio_merge(struct blk_mq_hw_ctx *hctx, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff814f6cd0)
Location: block/mq-deadline.c:472
Inline: False
```
**Symbols:**

```
ffffffff814f6cd0-ffffffff814f6d6f: dd_bio_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool dd_bio_merge(struct blk_mq_hw_ctx *hctx, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81514d70)
Location: block/mq-deadline.c:462
Inline: False
```
**Symbols:**

```
ffffffff81514d70-ffffffff81514e0f: dd_bio_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool dd_bio_merge(struct blk_mq_hw_ctx *hctx, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81575b80)
Location: block/mq-deadline.c:462
Inline: False
```
**Symbols:**

```
ffffffff81575b80-ffffffff81575c1f: dd_bio_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool dd_bio_merge(struct blk_mq_hw_ctx *hctx, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81592980)
Location: block/mq-deadline.c:464
Inline: False
```
**Symbols:**

```
ffffffff81592980-ffffffff81592a1f: dd_bio_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool dd_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff815997a0)
Location: block/mq-deadline.c:464
Inline: False
```
**Symbols:**

```
ffffffff815997a0-ffffffff81599839: dd_bio_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool dd_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81602100)
Location: block/mq-deadline.c:639
Inline: False
```
**Symbols:**

```
ffffffff81602100-ffffffff8160219c: dd_bio_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool dd_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff816b3e00)
Location: block/mq-deadline.c:692
Inline: False
```
**Symbols:**

```
ffffffff816b3e00-ffffffff816b3ea4: dd_bio_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool dd_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81773550)
Location: block/mq-deadline.c:750
Inline: False
```
**Symbols:**

```
ffffffff81773550-ffffffff817735f4: dd_bio_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool dd_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff817b23f0)
Location: block/mq-deadline.c:775
Inline: False
```
**Symbols:**

```
ffffffff817b23f0-ffffffff817b2494: dd_bio_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool dd_bio_merge(struct request_queue *q, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff817f6200)
Location: block/mq-deadline.c:775
Inline: False
```
**Symbols:**

```
ffffffff817f6200-ffffffff817f62a4: dd_bio_merge (STB_LOCAL)
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
bool dd_bio_merge(struct blk_mq_hw_ctx *hctx, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffff8000106197f8)
Location: block/mq-deadline.c:462
Inline: False
```
**Symbols:**

```
ffff8000106197f8-ffff8000106198e4: dd_bio_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool dd_bio_merge(struct blk_mq_hw_ctx *hctx, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (c07c3e68)
Location: block/mq-deadline.c:462
Inline: False
```
**Symbols:**

```
c07c3e68-c07c3f20: dd_bio_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool dd_bio_merge(struct blk_mq_hw_ctx *hctx, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (c0000000007b8b00)
Location: block/mq-deadline.c:462
Inline: False
```
**Symbols:**

```
c0000000007b8b00-c0000000007b8c04: dd_bio_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool dd_bio_merge(struct blk_mq_hw_ctx *hctx, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffe00044f7d0)
Location: block/mq-deadline.c:462
Inline: False
```
**Symbols:**

```
ffffffe00044f7d0-ffffffe00044f880: dd_bio_merge (STB_LOCAL)
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
bool dd_bio_merge(struct blk_mq_hw_ctx *hctx, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff8150d350)
Location: block/mq-deadline.c:462
Inline: False
```
**Symbols:**

```
ffffffff8150d350-ffffffff8150d3ef: dd_bio_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool dd_bio_merge(struct blk_mq_hw_ctx *hctx, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff814fd780)
Location: block/mq-deadline.c:462
Inline: False
```
**Symbols:**

```
ffffffff814fd780-ffffffff814fd81f: dd_bio_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool dd_bio_merge(struct blk_mq_hw_ctx *hctx, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff815093e0)
Location: block/mq-deadline.c:462
Inline: False
```
**Symbols:**

```
ffffffff815093e0-ffffffff8150947f: dd_bio_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool dd_bio_merge(struct blk_mq_hw_ctx *hctx, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff815224e0)
Location: block/mq-deadline.c:462
Inline: False
```
**Symbols:**

```
ffffffff815224e0-ffffffff8152257d: dd_bio_merge (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int nr_segs</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
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
