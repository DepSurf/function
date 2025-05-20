# Function: <code>blk_queue_enter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, bool nowait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b99b0)
Location: block/blk-core.c:649
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_read_page
  - fs/block_dev.c:bdev_write_page
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff813b99b0-ffffffff813b9b64: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, bool nowait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fd7a0)
Location: block/blk-core.c:651
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - fs/dax.c:dax_map_atomic
  - block/blk-timeout.c:blk_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff813fd7a0-ffffffff813fd949: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, bool nowait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81417100)
Location: block/blk-core.c:652
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - fs/dax.c:dax_map_atomic
  - block/blk-timeout.c:blk_timeout_work
```
**Symbols:**

```
ffffffff81417100-ffffffff81417287: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, bool nowait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81424e30)
Location: block/blk-core.c:763
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-timeout.c:blk_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff81424e30-ffffffff81424fb2: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144fcb0)
Location: block/blk-core.c:818
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_get_request_flags
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff8144fcb0-ffffffff8144fec1: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81482ed0)
Location: block/blk-core.c:918
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:blk_get_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff81482ed0-ffffffff814830a3: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149e830)
Location: block/blk-core.c:398
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff8149e830-ffffffff8149ea38: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cc9d0)
Location: block/blk-core.c:396
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-core.c:direct_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff814cc9d0-ffffffff814ccbda: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e5c10)
Location: block/blk-core.c:400
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-core.c:direct_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff814e5c10-ffffffff814e5e0e: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81544d00)
Location: block/blk-core.c:412
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-core.c:direct_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff81544d00-ffffffff81544ef6: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81561280)
Location: block/blk-core.c:430
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-core.c:__submit_bio_noacct_mq
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff81561280-ffffffff815614b2: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815699d0)
Location: block/blk-core.c:431
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff815699d0-ffffffff81569c02: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815ce450)
Location: block/blk-core.c:440
Inline: False
Direct callers:
  - block/bdev.c:bdev_write_page
  - block/bdev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-cgroup.c:blkg_conf_prep
```
**Symbols:**

```
ffffffff815ce450-ffffffff815ce5bb: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81678680)
Location: block/blk-core.c:335
Inline: False
Direct callers:
  - block/bdev.c:bdev_write_page
  - block/bdev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-cgroup.c:blkg_conf_prep
```
**Symbols:**

```
ffffffff81678680-ffffffff816788a4: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81734ae0)
Location: block/blk-core.c:313
Inline: False
Direct callers:
  - block/bdev.c:bdev_write_page
  - block/bdev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-cgroup.c:blkg_conf_prep
```
**Symbols:**

```
ffffffff81734ae0-ffffffff81734cfe: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81771030)
Location: block/blk-core.c:310
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff81771030-ffffffff8177125f: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b3380)
Location: block/blk-core.c:312
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff817b3380-ffffffff817b35a0: blk_queue_enter (STB_GLOBAL)
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
int blk_queue_enter(struct request_queue *q, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e31a0)
Location: block/blk-core.c:400
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-core.c:direct_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffff8000105e31a0-ffff8000105e33f4: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c079048c)
Location: block/blk-core.c:400
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
c079048c-c07906f4: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0000000007769c0)
Location: block/blk-core.c:400
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-core.c:direct_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
c0000000007769c0-c000000000776cb0: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000424de4)
Location: block/blk-core.c:400
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-core.c:direct_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffe000424de4-ffffffe000424f90: blk_queue_enter (STB_GLOBAL)
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
int blk_queue_enter(struct request_queue *q, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814de1f0)
Location: block/blk-core.c:400
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-core.c:direct_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff814de1f0-ffffffff814de3ee: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814ceb90)
Location: block/blk-core.c:400
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-core.c:direct_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff814ceb90-ffffffff814ced8e: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814da280)
Location: block/blk-core.c:400
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-core.c:direct_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff814da280-ffffffff814da47e: blk_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_queue_enter(struct request_queue *q, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f2f10)
Location: block/blk-core.c:400
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-core.c:direct_make_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff814f2f10-ffffffff814f315e: blk_queue_enter (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_mq_req_flags_t flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool nowait</code>
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
