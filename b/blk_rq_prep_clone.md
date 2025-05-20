# Function: <code>blk_rq_prep_clone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b5b40)
Location: block/blk-core.c:3084
Inline: False
Direct callers:
  - drivers/md/dm.c:map_request
```
**Symbols:**

```
ffffffff813b5b40-ffffffff813b5c8e: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fa9b0)
Location: block/blk-core.c:3056
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_old_prep_fn
```
**Symbols:**

```
ffffffff813fa9b0-ffffffff813fab21: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81414330)
Location: block/blk-core.c:3050
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_old_prep_fn
```
**Symbols:**

```
ffffffff81414330-ffffffff8141446c: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81421ec0)
Location: block/blk-core.c:3146
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81421ec0-ffffffff81421fed: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144cd30)
Location: block/blk-core.c:3370
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff8144cd30-ffffffff8144ce60: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147ff70)
Location: block/blk-core.c:3521
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff8147ff70-ffffffff814800c8: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149d000)
Location: block/blk-core.c:1627
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff8149d000-ffffffff8149d150: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cb190)
Location: block/blk-core.c:1578
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff814cb190-ffffffff814cb2e8: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e4380)
Location: block/blk-core.c:1619
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff814e4380-ffffffff814e44d8: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815431a0)
Location: block/blk-core.c:1705
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff815431a0-ffffffff81543309: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155f9f0)
Location: block/blk-core.c:1597
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff8155f9f0-ffffffff8155fb57: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815686e0)
Location: block/blk-core.c:1589
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff815686e0-ffffffff81568847: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cccc0)
Location: block/blk-core.c:1575
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff815cccc0-ffffffff815cce27: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff816845d0)
Location: block/blk-mq.c:2953
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff816845d0-ffffffff8168476a: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81741f80)
Location: block/blk-mq.c:3113
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81741f80-ffffffff8174211a: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177d950)
Location: block/blk-mq.c:3125
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff8177d950-ffffffff8177daf5: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817bfce0)
Location: block/blk-mq.c:3141
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff817bfce0-ffffffff817bfe82: blk_rq_prep_clone (STB_GLOBAL)
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
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e0758)
Location: block/blk-core.c:1619
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffff8000105e0758-ffff8000105e08a0: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078e9fc)
Location: block/blk-core.c:1619
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
c078e9fc-c078eb50: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000774b10)
Location: block/blk-core.c:1619
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
c000000000774b10-c000000000774d20: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000423ac4)
Location: block/blk-core.c:1619
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffe000423ac4-ffffffe000423be2: blk_rq_prep_clone (STB_GLOBAL)
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
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dc960)
Location: block/blk-core.c:1619
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff814dc960-ffffffff814dcab8: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd310)
Location: block/blk-core.c:1619
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff814cd310-ffffffff814cd468: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d89f0)
Location: block/blk-core.c:1619
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff814d89f0-ffffffff814d8b48: blk_rq_prep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_rq_prep_clone(struct request *rq, struct request *rq_src, struct bio_set *bs, gfp_t gfp_mask, int (*bio_ctr)(struct bio *, struct bio *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f1600)
Location: block/blk-core.c:1619
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff814f1600-ffffffff814f1758: blk_rq_prep_clone (STB_GLOBAL)
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
