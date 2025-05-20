# Function: <code>__blk_bios_map_sg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff813bff30)
Location: block/blk-merge.c:378
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81403fb4)
Location: block/blk-merge.c:405
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8141e53f)
Location: block/blk-merge.c:416
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8142be14)
Location: block/blk-merge.c:406
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81456ea1)
Location: block/blk-merge.c:407
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8148a933)
Location: block/blk-merge.c:416
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814a4505)
Location: block/blk-merge.c:458
Inline: True
Inline callers:
  - block/blk-merge.c:blk_rq_map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __blk_bios_map_sg(struct request_queue *q, struct bio *bio, struct scatterlist *sglist, struct scatterlist **sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d1e70)
Location: block/blk-merge.c:409
Inline: False
Direct callers:
  - block/blk-merge.c:blk_rq_map_sg
```
**Symbols:**

```
ffffffff814d1e70-ffffffff814d2315: __blk_bios_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __blk_bios_map_sg(struct request_queue *q, struct bio *bio, struct scatterlist *sglist, struct scatterlist **sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814eb1e0)
Location: block/blk-merge.c:462
Inline: False
Direct callers:
  - block/blk-merge.c:blk_rq_map_sg
```
**Symbols:**

```
ffffffff814eb1e0-ffffffff814eb69c: __blk_bios_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __blk_bios_map_sg(struct request_queue *q, struct bio *bio, struct scatterlist *sglist, struct scatterlist **sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8154b110)
Location: block/blk-merge.c:472
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
**Symbols:**

```
ffffffff8154b110-ffffffff8154b4e9: __blk_bios_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __blk_bios_map_sg(struct request_queue *q, struct bio *bio, struct scatterlist *sglist, struct scatterlist **sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81567240)
Location: block/blk-merge.c:488
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
**Symbols:**

```
ffffffff81567240-ffffffff8156759e: __blk_bios_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __blk_bios_map_sg(struct request_queue *q, struct bio *bio, struct scatterlist *sglist, struct scatterlist **sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8156f580)
Location: block/blk-merge.c:487
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
**Symbols:**

```
ffffffff8156f580-ffffffff8156f98c: __blk_bios_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __blk_bios_map_sg(struct request_queue *q, struct bio *bio, struct scatterlist *sglist, struct scatterlist **sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815d3c30)
Location: block/blk-merge.c:489
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
**Symbols:**

```
ffffffff815d3c30-ffffffff815d402e: __blk_bios_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __blk_bios_map_sg(struct request_queue *q, struct bio *bio, struct scatterlist *sglist, struct scatterlist **sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8167fa60)
Location: block/blk-merge.c:489
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
**Symbols:**

```
ffffffff8167fa60-ffffffff8167fe88: __blk_bios_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __blk_bios_map_sg(struct request_queue *q, struct bio *bio, struct scatterlist *sglist, struct scatterlist **sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8173ce00)
Location: block/blk-merge.c:526
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
**Symbols:**

```
ffffffff8173ce00-ffffffff8173d21d: __blk_bios_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __blk_bios_map_sg(struct request_queue *q, struct bio *bio, struct scatterlist *sglist, struct scatterlist **sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81779380)
Location: block/blk-merge.c:527
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
**Symbols:**

```
ffffffff81779380-ffffffff817797ba: __blk_bios_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __blk_bios_map_sg(struct request_queue *q, struct bio *bio, struct scatterlist *sglist, struct scatterlist **sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817bb750)
Location: block/blk-merge.c:523
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_rq_map_sg
```
**Symbols:**

```
ffffffff817bb750-ffffffff817bbb8a: __blk_bios_map_sg (STB_LOCAL)
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
int __blk_bios_map_sg(struct request_queue *q, struct bio *bio, struct scatterlist *sglist, struct scatterlist **sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffff8000105e9ce0)
Location: block/blk-merge.c:462
Inline: False
Direct callers:
  - block/blk-merge.c:blk_rq_map_sg
```
**Symbols:**

```
ffff8000105e9ce0-ffff8000105ea0e0: __blk_bios_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __blk_bios_map_sg(struct request_queue *q, struct bio *bio, struct scatterlist *sglist, struct scatterlist **sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c07961f8)
Location: block/blk-merge.c:462
Inline: False
Direct callers:
  - block/blk-merge.c:blk_rq_map_sg
```
**Symbols:**

```
c07961f8-c0796694: __blk_bios_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __blk_bios_map_sg(struct request_queue *q, struct bio *bio, struct scatterlist *sglist, struct scatterlist **sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c00000000077eb00)
Location: block/blk-merge.c:462
Inline: False
Direct callers:
  - block/blk-merge.c:blk_rq_map_sg
```
**Symbols:**

```
c00000000077eb00-c00000000077efe0: __blk_bios_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __blk_bios_map_sg(struct request_queue *q, struct bio *bio, struct scatterlist *sglist, struct scatterlist **sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffe00042a176)
Location: block/blk-merge.c:462
Inline: False
Direct callers:
  - block/blk-merge.c:blk_rq_map_sg
```
**Symbols:**

```
ffffffe00042a176-ffffffe00042a53a: __blk_bios_map_sg (STB_LOCAL)
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
int __blk_bios_map_sg(struct request_queue *q, struct bio *bio, struct scatterlist *sglist, struct scatterlist **sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e37c0)
Location: block/blk-merge.c:462
Inline: False
Direct callers:
  - block/blk-merge.c:blk_rq_map_sg
```
**Symbols:**

```
ffffffff814e37c0-ffffffff814e3c7c: __blk_bios_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __blk_bios_map_sg(struct request_queue *q, struct bio *bio, struct scatterlist *sglist, struct scatterlist **sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d4140)
Location: block/blk-merge.c:462
Inline: False
Direct callers:
  - block/blk-merge.c:blk_rq_map_sg
```
**Symbols:**

```
ffffffff814d4140-ffffffff814d4557: __blk_bios_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __blk_bios_map_sg(struct request_queue *q, struct bio *bio, struct scatterlist *sglist, struct scatterlist **sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814df850)
Location: block/blk-merge.c:462
Inline: False
Direct callers:
  - block/blk-merge.c:blk_rq_map_sg
```
**Symbols:**

```
ffffffff814df850-ffffffff814dfd0c: __blk_bios_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __blk_bios_map_sg(struct request_queue *q, struct bio *bio, struct scatterlist *sglist, struct scatterlist **sg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814f86b0)
Location: block/blk-merge.c:462
Inline: False
Direct callers:
  - block/blk-merge.c:blk_rq_map_sg
```
**Symbols:**

```
ffffffff814f86b0-ffffffff814f8b6c: __blk_bios_map_sg (STB_LOCAL)
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
