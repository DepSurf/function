# Function: <code>__blk_queue_split</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __blk_queue_split(struct request_queue *q, struct bio **bio, unsigned int *nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d25a0)
Location: block/blk-merge.c:253
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814d25a0-ffffffff814d2a86: __blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __blk_queue_split(struct request_queue *q, struct bio **bio, unsigned int *nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814eb920)
Location: block/blk-merge.c:293
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814eb920-ffffffff814ebd9c: __blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __blk_queue_split(struct request_queue *q, struct bio **bio, unsigned int *nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8154be50)
Location: block/blk-merge.c:297
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff8154be50-ffffffff8154c053: __blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __blk_queue_split(struct bio **bio, unsigned int *nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815681d0)
Location: block/blk-merge.c:306
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff815681d0-ffffffff815683af: __blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __blk_queue_split(struct bio **bio, unsigned int *nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8156ff90)
Location: block/blk-merge.c:305
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff8156ff90-ffffffff81570175: __blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __blk_queue_split(struct bio **bio, unsigned int *nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815d4630)
Location: block/blk-merge.c:305
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff815d4630-ffffffff815d481e: __blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __blk_queue_split(struct request_queue *q, struct bio **bio, unsigned int *nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81680440)
Location: block/blk-merge.c:325
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff81680440-ffffffff81680631: __blk_queue_split (STB_GLOBAL)
```
</details>
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
void __blk_queue_split(struct request_queue *q, struct bio **bio, unsigned int *nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffff8000105ea340)
Location: block/blk-merge.c:293
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffff8000105ea340-ffff8000105ea7e0: __blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __blk_queue_split(struct request_queue *q, struct bio **bio, unsigned int *nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c0796934)
Location: block/blk-merge.c:293
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
c0796934-c0796dc0: __blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __blk_queue_split(struct request_queue *q, struct bio **bio, unsigned int *nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c00000000077f300)
Location: block/blk-merge.c:293
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
c00000000077f300-c00000000077f984: __blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __blk_queue_split(struct request_queue *q, struct bio **bio, unsigned int *nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffe00042a70e)
Location: block/blk-merge.c:293
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffe00042a70e-ffffffe00042ab22: __blk_queue_split (STB_GLOBAL)
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
void __blk_queue_split(struct request_queue *q, struct bio **bio, unsigned int *nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e3f00)
Location: block/blk-merge.c:293
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814e3f00-ffffffff814e437c: __blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __blk_queue_split(struct request_queue *q, struct bio **bio, unsigned int *nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d47e0)
Location: block/blk-merge.c:293
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814d47e0-ffffffff814d4c5c: __blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __blk_queue_split(struct request_queue *q, struct bio **bio, unsigned int *nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814dff90)
Location: block/blk-merge.c:293
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814dff90-ffffffff814e040c: __blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __blk_queue_split(struct request_queue *q, struct bio **bio, unsigned int *nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814f8df0)
Location: block/blk-merge.c:293
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814f8df0-ffffffff814f9283: __blk_queue_split (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Param removed. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param reordered. </b>
<code>q, bio, nr_segs</code> ➡️ <code>bio, nr_segs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param reordered. </b>
<code>bio, nr_segs</code> ➡️ <code>q, bio, nr_segs</code>
</li>
</ul>
</details>
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
