# Function: <code>bio_data_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810d75b3)
Location: include/linux/fs.h:2507
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In block/bio.c (ffffffff813f606c)
Location: include/linux/fs.h:2507
Inline: True
Inline callers:
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_uncopy_user
```
```
In block/blk-core.c (ffffffff813ff692)
Location: include/linux/fs.h:2507
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bio
```
```
In block/blk-merge.c (0)
Location: include/linux/fs.h:2507
Inline: True
```
```
In block/blk-mq.c (ffffffff81408d9f)
Location: include/linux/fs.h:2507
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_request
```
```
In block/bounce.c (0)
Location: include/linux/fs.h:2507
Inline: True
```
```
In block/blk-throttle.c (ffffffff814218d0)
Location: include/linux/fs.h:2507
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
```
```
In block/deadline-iosched.c (ffffffff814227c2)
Location: include/linux/fs.h:2507
Inline: True
```
```
In block/cfq-iosched.c (ffffffff81423ec8)
Location: include/linux/fs.h:2507
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_allow_bio_merge
  - block/cfq-iosched.c:cfq_allow_bio_merge
  - block/cfq-iosched.c:cfq_merge
```
```
In block/bio-integrity.c (ffffffff8142dc47)
Location: include/linux/fs.h:2507
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_prep
```
```
In drivers/nvdimm/core.c (ffffffff815eba03)
Location: include/linux/fs.h:2507
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_iostat_end
  - drivers/nvdimm/core.c:__nd_iostat_start
```
```
In drivers/md/md.c (ffffffff816f0fc2)
Location: include/linux/fs.h:2507
Inline: True
Inline callers:
  - drivers/md/md.c:md_make_request
```
```
In drivers/md/dm.c (ffffffff817035c1)
Location: include/linux/fs.h:2507
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-io.c (ffffffff8170b21a)
Location: include/linux/fs.h:2507
Inline: True
Inline callers:
  - drivers/md/dm-io.c:endio
```
</details>
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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
