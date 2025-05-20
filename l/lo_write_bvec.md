# Function: <code>lo_write_bvec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int lo_write_bvec(struct file *file, struct bio_vec *bvec, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8156f270)
Location: drivers/block/loop.c:261
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff8156f270-ffffffff8156f37e: lo_write_bvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int lo_write_bvec(struct file *file, struct bio_vec *bvec, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815c4b70)
Location: drivers/block/loop.c:261
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff815c4b70-ffffffff815c4c80: lo_write_bvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int lo_write_bvec(struct file *file, struct bio_vec *bvec, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815f32b0)
Location: drivers/block/loop.c:261
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff815f32b0-ffffffff815f33c0: lo_write_bvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int lo_write_bvec(struct file *file, struct bio_vec *bvec, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816075a0)
Location: drivers/block/loop.c:261
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff816075a0-ffffffff816076b2: lo_write_bvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int lo_write_bvec(struct file *file, struct bio_vec *bvec, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8166fa70)
Location: drivers/block/loop.c:264
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff8166fa70-ffffffff8166fb82: lo_write_bvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int lo_write_bvec(struct file *file, struct bio_vec *bvec, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:266
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff816ab600-ffffffff816ab701: lo_write_bvec (STB_LOCAL)
ffffffff816ad79a-ffffffff816ad7b2: lo_write_bvec.cold.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int lo_write_bvec(struct file *file, struct bio_vec *bvec, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:267
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff816cbd70-ffffffff816cbe71: lo_write_bvec (STB_LOCAL)
ffffffff816ce647-ffffffff816ce65f: lo_write_bvec.cold.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int lo_write_bvec(struct file *file, struct bio_vec *bvec, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:267
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff81707370-ffffffff81707471: lo_write_bvec (STB_LOCAL)
ffffffff81709d8a-ffffffff81709da1: lo_write_bvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int lo_write_bvec(struct file *file, struct bio_vec *bvec, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:267
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff8172b5c0-ffffffff8172b6c1: lo_write_bvec (STB_LOCAL)
ffffffff8172e087-ffffffff8172e09e: lo_write_bvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int lo_write_bvec(struct file *file, struct bio_vec *bvec, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:279
Inline: False
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:lo_write_transfer
```
**Symbols:**

```
ffffffff817e7ee0-ffffffff817e7fe1: lo_write_bvec (STB_LOCAL)
ffffffff817eac57-ffffffff817eac6e: lo_write_bvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int lo_write_bvec(struct file *file, struct bio_vec *bvec, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:276
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_write_transfer
```
**Symbols:**

```
ffffffff817fce00-ffffffff817fcf4e: lo_write_bvec (STB_LOCAL)
ffffffff81c0fa42-ffffffff81c0fa59: lo_write_bvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int lo_write_bvec(struct file *file, struct bio_vec *bvec, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:318
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_write_transfer
```
**Symbols:**

```
ffffffff817e1890-ffffffff817e19de: lo_write_bvec (STB_LOCAL)
ffffffff81c01bac-ffffffff81c01bc3: lo_write_bvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int lo_write_bvec(struct file *file, struct bio_vec *bvec, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:308
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_write_transfer
```
**Symbols:**

```
ffffffff8186d030-ffffffff8186d17e: lo_write_bvec (STB_LOCAL)
ffffffff81d057a9-ffffffff81d057c0: lo_write_bvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff819b6d1c)
Location: drivers/block/loop.c:241
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b2bf78)
Location: drivers/block/loop.c:241
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b7c247)
Location: drivers/block/loop.c:241
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81bd0227)
Location: drivers/block/loop.c:239
Inline: True
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
int lo_write_bvec(struct file *file, struct bio_vec *bvec, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffff800010921758)
Location: drivers/block/loop.c:267
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffff800010921758-ffff800010921894: lo_write_bvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int lo_write_bvec(struct file *file, struct bio_vec *bvec, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0a06fa8)
Location: drivers/block/loop.c:267
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
c0a06fa8-c0a070e8: lo_write_bvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int lo_write_bvec(struct file *file, struct bio_vec *bvec, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0000000009c66c0)
Location: drivers/block/loop.c:267
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
c0000000009c66c0-c0000000009c6874: lo_write_bvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int lo_write_bvec(struct file *file, struct bio_vec *bvec, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffe0005a0528)
Location: drivers/block/loop.c:267
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffe0005a0528-ffffffe0005a061c: lo_write_bvec (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int lo_write_bvec(struct file *file, struct bio_vec *bvec, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:267
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff816f13a0-ffffffff816f14a1: lo_write_bvec (STB_LOCAL)
ffffffff816f3e67-ffffffff816f3e7e: lo_write_bvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int lo_write_bvec(struct file *file, struct bio_vec *bvec, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:267
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff816cb4a0-ffffffff816cb5a1: lo_write_bvec (STB_LOCAL)
ffffffff816cdf67-ffffffff816cdf7e: lo_write_bvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int lo_write_bvec(struct file *file, struct bio_vec *bvec, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:267
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff8171ea80-ffffffff8171eb81: lo_write_bvec (STB_LOCAL)
ffffffff81721547-ffffffff8172155e: lo_write_bvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int lo_write_bvec(struct file *file, struct bio_vec *bvec, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:267
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff81739eb0-ffffffff81739fb1: lo_write_bvec (STB_LOCAL)
ffffffff8173c914-ffffffff8173c92b: lo_write_bvec.cold (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
