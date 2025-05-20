# Function: <code>blk_queue_split</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_queue_split(struct request_queue *q, struct bio **bio, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff813c0460)
Location: block/blk-merge.c:167
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - drivers/md/md.c:md_make_request
```
**Symbols:**

```
ffffffff813c0460-ffffffff813c09f6: blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_queue_split(struct request_queue *q, struct bio **bio, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814044d0)
Location: block/blk-merge.c:191
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - drivers/md/md.c:md_make_request
```
**Symbols:**

```
ffffffff814044d0-ffffffff81404b05: blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_queue_split(struct request_queue *q, struct bio **bio, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8141dc20)
Location: block/blk-merge.c:191
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - drivers/md/md.c:md_make_request
```
**Symbols:**

```
ffffffff8141dc20-ffffffff8141e279: blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_split(struct request_queue *q, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8142c170)
Location: block/blk-merge.c:183
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
  - drivers/md/md.c:md_make_request
```
**Symbols:**

```
ffffffff8142c170-ffffffff8142c737: blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_split(struct request_queue *q, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81457380)
Location: block/blk-merge.c:184
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
  - drivers/md/md.c:md_make_request
```
**Symbols:**

```
ffffffff81457380-ffffffff8145794a: blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_queue_split(struct request_queue *q, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8148a2b0)
Location: block/blk-merge.c:183
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
  - drivers/md/md.c:md_make_request
```
**Symbols:**

```
ffffffff8148a2b0-ffffffff8148a8cf: blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_queue_split(struct request_queue *q, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814a3e90)
Location: block/blk-merge.c:245
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814a3e90-ffffffff814a4498: blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_queue_split(struct request_queue *q, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d2a90)
Location: block/blk-merge.c:297
Inline: False
Direct callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
ffffffff814d2a90-ffffffff814d2acb: blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_queue_split(struct request_queue *q, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814ebda0)
Location: block/blk-merge.c:348
Inline: False
Direct callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
ffffffff814ebda0-ffffffff814ebddb: blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_queue_split(struct request_queue *q, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8154c060)
Location: block/blk-merge.c:357
Inline: False
Direct callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
ffffffff8154c060-ffffffff8154c09b: blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_queue_split(struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815683b0)
Location: block/blk-merge.c:365
Inline: False
Direct callers:
  - drivers/md/md.c:md_submit_bio
  - drivers/md/dm.c:dm_submit_bio
```
**Symbols:**

```
ffffffff815683b0-ffffffff815683eb: blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_queue_split(struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81570180)
Location: block/blk-merge.c:364
Inline: False
Direct callers:
  - drivers/md/md.c:md_submit_bio
  - drivers/md/dm.c:dm_submit_bio
```
**Symbols:**

```
ffffffff81570180-ffffffff815701bb: blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_queue_split(struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815d4820)
Location: block/blk-merge.c:366
Inline: False
Direct callers:
  - drivers/md/md.c:md_submit_bio
  - drivers/md/dm.c:dm_submit_bio
```
**Symbols:**

```
ffffffff815d4820-ffffffff815d485b: blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_queue_split(struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81680640)
Location: block/blk-merge.c:366
Inline: False
Direct callers:
  - drivers/md/md.c:md_submit_bio
  - drivers/md/md.c:md_submit_bio
  - drivers/md/dm.c:dm_split_and_process_bio
```
**Symbols:**

```
ffffffff81680640-ffffffff816806d0: blk_queue_split (STB_GLOBAL)
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
void blk_queue_split(struct request_queue *q, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffff8000105ea7e0)
Location: block/blk-merge.c:348
Inline: False
Direct callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
ffff8000105ea7e0-ffff8000105ea844: blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_queue_split(struct request_queue *q, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c0796dc0)
Location: block/blk-merge.c:348
Inline: False
Direct callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
c0796dc0-c0796e18: blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_queue_split(struct request_queue *q, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c00000000077f990)
Location: block/blk-merge.c:348
Inline: False
Direct callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
c00000000077f990-c00000000077f9ec: blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_queue_split(struct request_queue *q, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffe00042ab22)
Location: block/blk-merge.c:348
Inline: False
Direct callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
ffffffe00042ab22-ffffffe00042ab58: blk_queue_split (STB_GLOBAL)
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
void blk_queue_split(struct request_queue *q, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e4380)
Location: block/blk-merge.c:348
Inline: False
Direct callers:
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
ffffffff814e4380-ffffffff814e43bb: blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_queue_split(struct request_queue *q, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d4c60)
Location: block/blk-merge.c:348
Inline: False
Direct callers:
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
ffffffff814d4c60-ffffffff814d4c9b: blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_queue_split(struct request_queue *q, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e0410)
Location: block/blk-merge.c:348
Inline: False
Direct callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
ffffffff814e0410-ffffffff814e044b: blk_queue_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_queue_split(struct request_queue *q, struct bio **bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814f9290)
Location: block/blk-merge.c:348
Inline: False
Direct callers:
  - drivers/md/md.c:md_make_request
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
ffffffff814f9290-ffffffff814f92cb: blk_queue_split (STB_GLOBAL)
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
<b>Param removed. </b>
<code>struct bio_set *bs</code>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param reordered. </b>
<code>q, bio</code> ➡️ <code>bio</code>
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
