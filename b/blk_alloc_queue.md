# Function: <code>blk_alloc_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b5ac0)
Location: block/blk-core.c:643
Inline: False
Direct callers:
  - drivers/block/brd.c:brd_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff813b5ac0-ffffffff813b5ad5: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fa930)
Location: block/blk-core.c:645
Inline: False
Direct callers:
  - drivers/block/brd.c:brd_alloc
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff813fa930-ffffffff813fa945: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814142b0)
Location: block/blk-core.c:646
Inline: False
Direct callers:
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff814142b0-ffffffff814142c5: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81421d80)
Location: block/blk-core.c:757
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff81421d80-ffffffff81421d95: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144c8b0)
Location: block/blk-core.c:807
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff8144c8b0-ffffffff8144c8c5: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147fbc0)
Location: block/blk-core.c:907
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff8147fbc0-ffffffff8147fbd7: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149cf10)
Location: block/blk-core.c:387
Inline: False
Direct callers:
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff8149cf10-ffffffff8149cf25: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cb0a0)
Location: block/blk-core.c:385
Inline: False
Direct callers:
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff814cb0a0-ffffffff814cb0b5: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e4290)
Location: block/blk-core.c:389
Inline: False
Direct callers:
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff814e4290-ffffffff814e42a5: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(make_request_fn *make_request, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81545890)
Location: block/blk-core.c:586
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81545890-ffffffff815458cd: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155f080)
Location: block/blk-core.c:518
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_sq_queue
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff8155f080-ffffffff8155f334: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815678f0)
Location: block/blk-core.c:519
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_sq_queue
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff815678f0-ffffffff81567ba1: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815ce600)
Location: block/blk-core.c:526
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_disk
  - block/blk-mq.c:blk_mq_init_queue
  - block/genhd.c:__blk_alloc_disk
```
**Symbols:**

```
ffffffff815ce600-ffffffff815ce873: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(int node_id, bool alloc_srcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81678f20)
Location: block/blk-core.c:420
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_disk
  - block/blk-mq.c:blk_mq_init_queue
  - block/genhd.c:__blk_alloc_disk
```
**Symbols:**

```
ffffffff81678f20-ffffffff81679231: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817353e0)
Location: block/blk-core.c:398
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_disk
  - block/blk-mq.c:blk_mq_init_queue
  - block/genhd.c:__blk_alloc_disk
```
**Symbols:**

```
ffffffff817353e0-ffffffff817355da: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81771960)
Location: block/blk-core.c:395
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_disk
  - block/blk-mq.c:blk_mq_init_queue
  - block/genhd.c:__blk_alloc_disk
```
**Symbols:**

```
ffffffff81771960-ffffffff81771b7a: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b3ca0)
Location: block/blk-core.c:397
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_disk
  - block/blk-mq.c:blk_mq_init_queue
  - block/genhd.c:__blk_alloc_disk
```
**Symbols:**

```
ffffffff817b3ca0-ffffffff817b3ebb: blk_alloc_queue (STB_GLOBAL)
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
struct request_queue *blk_alloc_queue(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e0470)
Location: block/blk-core.c:389
Inline: False
Direct callers:
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffff8000105e0470-ffff8000105e04a0: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078e6e8)
Location: block/blk-core.c:389
Inline: False
Direct callers:
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
c078e6e8-c078e708: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0000000007746e0)
Location: block/blk-core.c:389
Inline: False
Direct callers:
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
c0000000007746e0-c0000000007746f8: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000423990)
Location: block/blk-core.c:389
Inline: False
Direct callers:
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffe000423990-ffffffe0004239bc: blk_alloc_queue (STB_GLOBAL)
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
struct request_queue *blk_alloc_queue(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dc870)
Location: block/blk-core.c:389
Inline: False
Direct callers:
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff814dc870-ffffffff814dc885: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd220)
Location: block/blk-core.c:389
Inline: False
Direct callers:
  - drivers/nvdimm/blk.c:nd_blk_probe
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff814cd220-ffffffff814cd235: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d8900)
Location: block/blk-core.c:389
Inline: False
Direct callers:
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff814d8900-ffffffff814d8915: blk_alloc_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct request_queue *blk_alloc_queue(gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f1510)
Location: block/blk-core.c:389
Inline: False
Direct callers:
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff814f1510-ffffffff814f1525: blk_alloc_queue (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>make_request_fn *make_request</code>
</li>
<li>
<b>Param added. </b>
<code>int node_id</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>make_request_fn *make_request</code>
</li>
<li>
<b>Param reordered. </b>
<code>make_request, node_id</code> ➡️ <code>node_id</code>
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
<code>bool alloc_srcu</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool alloc_srcu</code>
</li>
</ul>
</details>
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
