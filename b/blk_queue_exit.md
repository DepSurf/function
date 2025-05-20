# Function: <code>blk_queue_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b9c65)
Location: block/blk-core.c:670
Inline: True
Direct callers:
  - fs/block_dev.c:bdev_read_page
  - fs/block_dev.c:bdev_write_page
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff813b9eb0-ffffffff813b9eea: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fda45)
Location: block/blk-core.c:672
Inline: True
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - fs/dax.c:__dax_zero_page_range
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_do_io
  - fs/dax.c:dax_do_io
  - fs/dax.c:read_dax_sector
  - fs/dax.c:dax_map_atomic
  - block/blk-timeout.c:blk_timeout_work
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff813fdc70-ffffffff813fdca9: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81417385)
Location: block/blk-core.c:673
Inline: True
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:__dax_zero_page_range
  - fs/dax.c:read_dax_sector
  - fs/dax.c:dax_map_atomic
  - block/blk-timeout.c:blk_timeout_work
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff814175b0-ffffffff814175e9: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814250e8)
Location: block/blk-core.c:793
Inline: True
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-timeout.c:blk_timeout_work
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_get_request
```
**Symbols:**

```
ffffffff81425410-ffffffff81425449: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81450540)
Location: block/blk-core.c:867
Inline: True
Inline callers:
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:blk_get_request_flags
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_get_request
```
**Symbols:**

```
ffffffff814505b0-ffffffff814505ed: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81483820)
Location: block/blk-core.c:964
Inline: True
Inline callers:
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:blk_get_request
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_get_request
```
**Symbols:**

```
ffffffff814838a0-ffffffff814838dd: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149efdd)
Location: block/blk-core.c:445
Inline: True
Inline callers:
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff8149f060-ffffffff8149f09d: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd0cc)
Location: block/blk-core.c:443
Inline: True
Inline callers:
  - block/blk-core.c:direct_make_request
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff814cd140-ffffffff814cd17c: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e635c)
Location: block/blk-core.c:447
Inline: True
Inline callers:
  - block/blk-core.c:direct_make_request
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff814e63d0-ffffffff814e640c: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81544fa5)
Location: block/blk-core.c:476
Inline: True
Inline callers:
  - block/blk-core.c:direct_make_request
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff81545580-ffffffff815455bc: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815618c8)
Location: block/blk-core.c:494
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct_mq
  - block/blk-core.c:__submit_bio_noacct
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff81561be0-ffffffff81561c1d: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81569d02)
Location: block/blk-core.c:495
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff8156a340-ffffffff8156a37d: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cd53b)
Location: block/blk-core.c:502
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
Direct callers:
  - block/bdev.c:bdev_write_page
  - block/bdev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
```
**Symbols:**

```
ffffffff815ce5c0-ffffffff815ce5fd: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81679f3c)
Location: block/blk-core.c:396
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
Direct callers:
  - block/bdev.c:bdev_write_page
  - block/bdev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
```
**Symbols:**

```
ffffffff81678ed0-ffffffff81678f1f: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817363e1)
Location: block/blk-core.c:374
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
Direct callers:
  - block/bdev.c:bdev_write_page
  - block/bdev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
```
**Symbols:**

```
ffffffff81735380-ffffffff817353cf: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81772a4d)
Location: block/blk-core.c:371
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
Direct callers:
  - block/blk-mq.c:blk_rq_poll
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff81771900-ffffffff8177194f: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b4dea)
Location: block/blk-core.c:373
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
Direct callers:
  - block/blk-mq.c:blk_rq_poll
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff817b3c40-ffffffff817b3c8f: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e3958)
Location: block/blk-core.c:447
Inline: True
Inline callers:
  - block/blk-core.c:direct_make_request
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffff8000105e3a18-ffff8000105e3aa4: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0790c5c)
Location: block/blk-core.c:447
Inline: True
Inline callers:
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
c0790cf8-c0790d78: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000777408)
Location: block/blk-core.c:447
Inline: True
Inline callers:
  - block/blk-core.c:direct_make_request
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
c000000000777510-c0000000007775c4: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe0004253d8)
Location: block/blk-core.c:447
Inline: True
Inline callers:
  - block/blk-core.c:direct_make_request
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffe00042546c-ffffffe0004254d4: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814de93c)
Location: block/blk-core.c:447
Inline: True
Inline callers:
  - block/blk-core.c:direct_make_request
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff814de9b0-ffffffff814de9ec: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cf2dc)
Location: block/blk-core.c:447
Inline: True
Inline callers:
  - block/blk-core.c:direct_make_request
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff814cf350-ffffffff814cf38c: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814da9cc)
Location: block/blk-core.c:447
Inline: True
Inline callers:
  - block/blk-core.c:direct_make_request
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff814daa40-ffffffff814daa7c: blk_queue_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f36cc)
Location: block/blk-core.c:447
Inline: True
Inline callers:
  - block/blk-core.c:direct_make_request
Direct callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
**Symbols:**

```
ffffffff814f3760-ffffffff814f37b4: blk_queue_exit (STB_GLOBAL)
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
