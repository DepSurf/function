# Function: <code>generic_make_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
blk_qc_t generic_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b9b70)
Location: block/blk-core.c:2022
Inline: True
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:blk_queue_split
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:dm_wq_work
```
**Symbols:**

```
ffffffff813b9b70-ffffffff813b9d35: generic_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
blk_qc_t generic_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fd950)
Location: block/blk-core.c:1995
Inline: True
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:blk_queue_split
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff813fd950-ffffffff813fdb13: generic_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
blk_qc_t generic_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81417290)
Location: block/blk-core.c:1978
Inline: True
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:blk_queue_split
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff81417290-ffffffff81417453: generic_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
blk_qc_t generic_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81424fc0)
Location: block/blk-core.c:2138
Inline: True
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:blk_queue_split
  - block/bounce.c:blk_queue_bounce
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff81424fc0-ffffffff814252bf: generic_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
blk_qc_t generic_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81450090)
Location: block/blk-core.c:2259
Inline: True
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:blk_queue_split
  - block/bounce.c:blk_queue_bounce
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff81450090-ffffffff8145038c: generic_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
blk_qc_t generic_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81483270)
Location: block/blk-core.c:2377
Inline: False
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:blk_queue_split
  - block/bounce.c:blk_queue_bounce
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff81483270-ffffffff81483671: generic_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
blk_qc_t generic_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149ea40)
Location: block/blk-core.c:1007
Inline: False
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:blk_queue_split
  - block/bounce.c:blk_queue_bounce
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff8149ea40-ffffffff8149ee3b: generic_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
blk_qc_t generic_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814ccbe0)
Location: block/blk-core.c:994
Inline: True
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:__blk_queue_split
  - block/bounce.c:__blk_queue_bounce
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff814ccbe0-ffffffff814ccef4: generic_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
blk_qc_t generic_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e5e10)
Location: block/blk-core.c:1009
Inline: True
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:__blk_queue_split
  - block/bounce.c:__blk_queue_bounce
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff814e5e10-ffffffff814e6124: generic_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
blk_qc_t generic_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-core.c (ffffffff81545030)
Location: block/blk-core.c:1101
Inline: True
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:__blk_queue_split
  - block/bounce.c:__blk_queue_bounce
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-crypto-fallback.c:blk_crypto_split_bio_if_needed
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff81545030-ffffffff8154535f: generic_make_request.part.0 (STB_LOCAL)
ffffffff81545360-ffffffff815453d0: generic_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
blk_qc_t generic_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e33f8)
Location: block/blk-core.c:1009
Inline: True
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:__blk_queue_split
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffff8000105e33f8-ffff8000105e36e0: generic_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
blk_qc_t generic_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c07906f4)
Location: block/blk-core.c:1009
Inline: False
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:__blk_queue_split
  - block/bounce.c:__blk_queue_bounce
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
c07906f4-c07909dc: generic_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
blk_qc_t generic_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000776cb0)
Location: block/blk-core.c:1009
Inline: True
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:__blk_queue_split
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
c000000000776cb0-c000000000777094: generic_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
blk_qc_t generic_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000424f90)
Location: block/blk-core.c:1009
Inline: True
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:__blk_queue_split
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffe000424f90-ffffffe0004251be: generic_make_request (STB_GLOBAL)
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
blk_qc_t generic_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814de3f0)
Location: block/blk-core.c:1009
Inline: True
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:__blk_queue_split
  - block/bounce.c:__blk_queue_bounce
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/nvme/host/multipath.c:nvme_requeue_work
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff814de3f0-ffffffff814de704: generic_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
blk_qc_t generic_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814ced90)
Location: block/blk-core.c:1009
Inline: True
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:__blk_queue_split
  - block/bounce.c:__blk_queue_bounce
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/nvme/host/multipath.c:nvme_requeue_work
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff814ced90-ffffffff814cf0a4: generic_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
blk_qc_t generic_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814da480)
Location: block/blk-core.c:1009
Inline: True
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:__blk_queue_split
  - block/bounce.c:__blk_queue_bounce
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff814da480-ffffffff814da794: generic_make_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
blk_qc_t generic_make_request(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f3160)
Location: block/blk-core.c:1009
Inline: True
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:__blk_queue_split
  - block/bounce.c:__blk_queue_bounce
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff814f3160-ffffffff814f3492: generic_make_request (STB_GLOBAL)
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
