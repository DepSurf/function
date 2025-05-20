# Function: <code>blk_rq_append_bio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_rq_append_bio(struct request_queue *q, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff813bf700)
Location: block/blk-map.c:30
Inline: False
Direct callers:
  - block/blk-core.c:blk_make_request
  - block/blk-map.c:blk_rq_map_kern
```
**Symbols:**

```
ffffffff813bf700-ffffffff813bf74f: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81403380)
Location: block/blk-map.c:16
Inline: True
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff81403380-ffffffff814033d9: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8141d0b0)
Location: block/blk-map.c:16
Inline: True
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff8141d0b0-ffffffff8141d127: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8142b090)
Location: block/blk-map.c:17
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff8142b090-ffffffff8142b104: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81456320)
Location: block/blk-map.c:18
Inline: True
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff81456320-ffffffff814563c3: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81489770)
Location: block/blk-map.c:18
Inline: True
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff81489770-ffffffff81489804: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814a35b0)
Location: block/blk-map.c:18
Inline: True
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff814a35b0-ffffffff814a3644: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814d15e0)
Location: block/blk-map.c:18
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff814d15e0-ffffffff814d1794: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814ea990)
Location: block/blk-map.c:18
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff814ea990-ffffffff814eab44: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81549cc0)
Location: block/blk-map.c:527
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff81549cc0-ffffffff81549e69: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81565760)
Location: block/blk-map.c:524
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff81565760-ffffffff815658bd: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8156ddc0)
Location: block/blk-map.c:482
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff8156ddc0-ffffffff8156ded5: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff815d23b0)
Location: block/blk-map.c:482
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff815d23b0-ffffffff815d24c5: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8167e0c0)
Location: block/blk-map.c:490
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff8167e0c0-ffffffff8167e1c4: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8173ad50)
Location: block/blk-map.c:531
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff8173ad50-ffffffff8173ae54: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff817773f0)
Location: block/blk-map.c:530
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff817773f0-ffffffff817774fa: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff817b9610)
Location: block/blk-map.c:537
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
```
**Symbols:**

```
ffffffff817b9610-ffffffff817b971a: blk_rq_append_bio (STB_GLOBAL)
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
int blk_rq_append_bio(struct request *rq, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffff8000105e92f0)
Location: block/blk-map.c:18
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffff8000105e92f0-ffff8000105e94bc: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (c079578c)
Location: block/blk-map.c:18
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
c079578c-c0795988: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (c00000000077de00)
Location: block/blk-map.c:18
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
c00000000077de00-c00000000077e0a8: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffe0004299de)
Location: block/blk-map.c:18
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffe0004299de-ffffffe000429b5a: blk_rq_append_bio (STB_GLOBAL)
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
int blk_rq_append_bio(struct request *rq, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814e2f70)
Location: block/blk-map.c:18
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
  - drivers/nvme/host/lightnvm.c:nvme_nvm_submit_io
```
**Symbols:**

```
ffffffff814e2f70-ffffffff814e3124: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814d38f0)
Location: block/blk-map.c:18
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff814d38f0-ffffffff814d3aa4: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814df000)
Location: block/blk-map.c:18
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff814df000-ffffffff814df1b4: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_rq_append_bio(struct request *rq, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814f7e70)
Location: block/blk-map.c:18
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_kern
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff814f7e70-ffffffff814f8024: blk_rq_append_bio (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param reordered. </b>
<code>q, rq, bio</code> ➡️ <code>rq, bio</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bio *bio</code> ➡️ <code>struct bio **bio</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bio **bio</code> ➡️ <code>struct bio *bio</code>
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
