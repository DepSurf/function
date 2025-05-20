# Function: <code>bvec_iter_advance</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b08ba)
Location: include/linux/bio.h:196
Inline: True
Inline callers:
  - block/bio.c:bio_advance
  - block/bio.c:zero_fill_bio
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_bioset
```
```
In block/blk-merge.c (ffffffff813bfd04)
Location: include/linux/bio.h:196
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_recalc_rq_segments
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_queue_split
  - block/blk-merge.c:blk_recount_segments
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
```
```
In block/bounce.c (ffffffff813d5016)
Location: include/linux/bio.h:196
Inline: True
```
```
In block/bio-integrity.c (ffffffff813e72bd)
Location: include/linux/bio.h:196
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffff813e7d1f)
Location: include/linux/bio.h:196
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In drivers/block/brd.c (ffffffff8156d961)
Location: include/linux/bio.h:196
Inline: True
Inline callers:
  - drivers/block/brd.c:brd_make_request
```
```
In drivers/block/loop.c (ffffffff81570bcd)
Location: include/linux/bio.h:196
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff81578657)
Location: include/linux/bio.h:196
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_recover
  - drivers/block/xen-blkfront.c:blkif_recover
```
```
In drivers/scsi/sd_dif.c (ffffffff815bf908)
Location: include/linux/bio.h:196
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_prepare
  - drivers/scsi/sd_dif.c:sd_dif_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f4db9)
Location: include/linux/bvec.h:69
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_bioset
  - block/bio.c:zero_fill_bio
```
```
In block/blk-merge.c (ffffffff8140520f)
Location: include/linux/bvec.h:69
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_recount_segments
  - block/blk-merge.c:__blk_recalc_rq_segments
  - block/blk-merge.c:blk_queue_split
```
```
In block/bounce.c (ffffffff8141acda)
Location: include/linux/bvec.h:69
Inline: True
```
```
In block/bio-integrity.c (ffffffff8142d53d)
Location: include/linux/bvec.h:69
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffff8142dfb2)
Location: include/linux/bvec.h:69
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In lib/iov_iter.c (ffffffff81442da6)
Location: include/linux/bvec.h:69
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_from_iter_nocache
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:copy_to_iter
```
```
In drivers/block/brd.c (ffffffff815c3193)
Location: include/linux/bvec.h:69
Inline: True
Inline callers:
  - drivers/block/brd.c:brd_make_request
```
```
In drivers/block/loop.c (ffffffff815c6662)
Location: include/linux/bvec.h:69
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/block/xen-blkfront.c (ffffffff815cdddd)
Location: include/linux/bvec.h:69
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
```
```
In drivers/scsi/sd_dif.c (ffffffff81618343)
Location: include/linux/bvec.h:69
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140e782)
Location: include/linux/bvec.h:69
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_bioset
  - block/bio.c:zero_fill_bio
```
```
In block/blk-merge.c (ffffffff8141f12f)
Location: include/linux/bvec.h:69
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_recount_segments
  - block/blk-merge.c:__blk_recalc_rq_segments
  - block/blk-merge.c:blk_queue_split
```
```
In block/bounce.c (ffffffff814361b0)
Location: include/linux/bvec.h:69
Inline: True
```
```
In block/bio-integrity.c (ffffffff8144731d)
Location: include/linux/bvec.h:69
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffff81447d6a)
Location: include/linux/bvec.h:69
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In lib/iov_iter.c (ffffffff8146094d)
Location: include/linux/bvec.h:69
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:copy_from_iter_full_nocache
  - lib/iov_iter.c:copy_from_iter_nocache
  - lib/iov_iter.c:copy_from_iter_full
  - lib/iov_iter.c:copy_from_iter
  - lib/iov_iter.c:copy_to_iter
```
```
In drivers/block/loop.c (ffffffff815f4a38)
Location: include/linux/bvec.h:69
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/block/xen-blkfront.c (ffffffff815fa81e)
Location: include/linux/bvec.h:69
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
```
```
In drivers/scsi/sd_dif.c (ffffffff81647edd)
Location: include/linux/bvec.h:69
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/md/dm-io.c (ffffffff8173d027)
Location: include/linux/bvec.h:69
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141c2d9)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_bioset
  - block/bio.c:zero_fill_bio
```
```
In block/blk-merge.c (ffffffff8142db6a)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_recount_segments
  - block/blk-merge.c:__blk_recalc_rq_segments
  - block/blk-merge.c:blk_queue_split
```
```
In block/bounce.c (ffffffff81442f88)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff814558ac)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffff814566a8)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In lib/iov_iter.c (ffffffff81465aff)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/block/loop.c (ffffffff816091a2)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/scsi/sd_dif.c (ffffffff8165c9d6)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/md/dm.c (ffffffff8174c325)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_remap_zone_report
```
```
In drivers/md/dm-io.c (ffffffff81756cde)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81446ea9)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_copy_data
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_bioset
  - block/bio.c:zero_fill_bio
```
```
In block/blk-merge.c (ffffffff81458d62)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_recount_segments
  - block/blk-merge.c:__blk_recalc_rq_segments
  - block/blk-merge.c:blk_queue_split
```
```
In block/bounce.c (ffffffff8146fa07)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff81481525)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffff814822f6)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In lib/iov_iter.c (ffffffff814918fd)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/block/loop.c (ffffffff81671a6b)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/scsi/sd_dif.c (ffffffff816c603c)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/md/dm.c (ffffffff817be6ee)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_remap_zone_report
```
```
In drivers/md/dm-io.c (ffffffff817c8eee)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81479fe5)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_bioset
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-merge.c (ffffffff8148b759)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_recount_segments
  - block/blk-merge.c:__blk_recalc_rq_segments
  - block/blk-merge.c:blk_queue_split
```
```
In block/bounce.c (ffffffff814a3d0f)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
  - block/bounce.c:bounce_end_io
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff814b6735)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffff814b6ee1)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In lib/iov_iter.c (ffffffff814c68c6)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/block/loop.c (ffffffff816ad4f4)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/scsi/sd_dif.c (ffffffff817025c6)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/md/dm.c (ffffffff818069f7)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_remap_zone_report
```
```
In drivers/md/dm-io.c (ffffffff81811c6e)
Location: include/linux/bvec.h:72
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81497df1)
Location: include/linux/bvec.h:70
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-merge.c (ffffffff814a5428)
Location: include/linux/bvec.h:70
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_rq_map_sg
  - block/blk-merge.c:blk_recount_segments
  - block/blk-merge.c:__blk_recalc_rq_segments
  - block/blk-merge.c:blk_queue_split
```
```
In block/bounce.c (ffffffff814be270)
Location: include/linux/bvec.h:70
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
  - block/bounce.c:blk_queue_bounce
  - block/bounce.c:blk_queue_bounce
  - block/bounce.c:bounce_end_io
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff814c9fe4)
Location: include/linux/bvec.h:70
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffff814ca6a9)
Location: include/linux/bvec.h:70
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In block/t10-pi.c (ffffffff814cb0ed)
Location: include/linux/bvec.h:70
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_complete
  - block/t10-pi.c:t10_pi_complete
  - block/t10-pi.c:t10_pi_prepare
  - block/t10-pi.c:t10_pi_prepare
```
```
In lib/iov_iter.c (ffffffff814db060)
Location: include/linux/bvec.h:70
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/block/loop.c (ffffffff816cd7e5)
Location: include/linux/bvec.h:70
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/md/dm-io.c (ffffffff8183dc09)
Location: include/linux/bvec.h:70
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c5a41)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff814d166f)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff814d20e8)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bounce.c (ffffffff814ec9be)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:bounce_end_io
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff814f88a4)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffff814f8f78)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In block/t10-pi.c (ffffffff814f9a41)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_complete
  - block/t10-pi.c:t10_pi_complete
  - block/t10-pi.c:t10_pi_prepare
  - block/t10-pi.c:t10_pi_prepare
```
```
In lib/iov_iter.c (ffffffff8150697c)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/block/loop.c (ffffffff817093f2)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/md/dm-io.c (ffffffff818808de)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814dec41)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff814eaa1f)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff814eb47b)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bounce.c (ffffffff81505e0e)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:bounce_end_io
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff81516734)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffff81516e34)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In block/t10-pi.c (ffffffff815177cc)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/iov_iter.c (ffffffff81524a8c)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/block/loop.c (ffffffff8172d75b)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/md/dm-io.c (ffffffff818b279e)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153e600)
Location: include/linux/bvec.h:96
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff81549d49)
Location: include/linux/bvec.h:96
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff8154c83e)
Location: include/linux/bvec.h:96
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/bounce.c (ffffffff81566b10)
Location: include/linux/bvec.h:96
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:bounce_end_io
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff81576ec9)
Location: include/linux/bvec.h:96
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffff815776de)
Location: include/linux/bvec.h:96
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In block/t10-pi.c (ffffffff81577fa1)
Location: include/linux/bvec.h:96
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-crypto.c (ffffffff81581887)
Location: include/linux/bvec.h:96
Inline: True
Inline callers:
  - block/blk-crypto.c:bio_crypt_check_alignment
```
```
In block/blk-crypto-fallback.c (ffffffff8158262d)
Location: include/linux/bvec.h:96
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_split_bio_if_needed
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
```
In lib/iov_iter.c (ffffffff815892a0)
Location: include/linux/bvec.h:96
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/block/loop.c (ffffffff817e93ac)
Location: include/linux/bvec.h:96
Inline: True
Inline callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_read_simple
  - drivers/block/loop.c:lo_write_transfer
```
```
In drivers/md/dm-io.c (ffffffff81983838)
Location: include/linux/bvec.h:96
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155a670)
Location: include/linux/bvec.h:100
Inline: True
Inline callers:
  - block/bio.c:bio_advance
```
```
In block/blk-merge.c (ffffffff81566e19)
Location: include/linux/bvec.h:100
Inline: True
Inline callers:
  - block/blk-merge.c:bio_get_last_bvec
```
```
In block/bounce.c (ffffffff8158121b)
Location: include/linux/bvec.h:100
Inline: True
Inline callers:
  - block/bounce.c:bounce_end_io
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff81593bd6)
Location: include/linux/bvec.h:100
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
```
```
In drivers/md/dm-io.c (ffffffff81987958)
Location: include/linux/bvec.h:100
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81562e40)
Location: include/linux/bvec.h:100
Inline: True
Inline callers:
  - block/bio.c:bio_advance
```
```
In block/blk-merge.c (ffffffff8156fb7e)
Location: include/linux/bvec.h:100
Inline: True
Inline callers:
  - block/blk-merge.c:bio_get_last_bvec
```
```
In block/bio-integrity.c (ffffffff8159a9bd)
Location: include/linux/bvec.h:100
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
```
```
In lib/iov_iter.c (ffffffff815b1af2)
Location: include/linux/bvec.h:100
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
```
```
In drivers/md/dm-io.c (ffffffff8196c028)
Location: include/linux/bvec.h:100
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c6ab0)
Location: include/linux/bvec.h:101
Inline: True
Inline callers:
  - block/bio.c:bio_advance
```
```
In block/blk-merge.c (ffffffff815d421e)
Location: include/linux/bvec.h:101
Inline: True
Inline callers:
  - block/blk-merge.c:bio_get_last_bvec
```
```
In block/bio-integrity.c (ffffffff81602bbb)
Location: include/linux/bvec.h:101
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
```
```
In lib/iov_iter.c (ffffffff81615887)
Location: include/linux/bvec.h:101
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
```
```
In drivers/md/dm-io.c (ffffffff81a144ea)
Location: include/linux/bvec.h:101
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff816719b6)
Location: include/linux/bvec.h:101
Inline: True
Inline callers:
  - block/bio.c:__bio_advance
```
```
In block/blk-merge.c (ffffffff8167ffd1)
Location: include/linux/bvec.h:101
Inline: True
Inline callers:
  - block/blk-merge.c:bio_get_last_bvec
```
```
In block/bio-integrity.c (ffffffff816b574b)
Location: include/linux/bvec.h:101
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
```
```
In lib/iov_iter.c (ffffffff816e2478)
Location: include/linux/bvec.h:101
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
```
```
In drivers/md/dm-io.c (ffffffff81b7cd5a)
Location: include/linux/bvec.h:101
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172d246)
Location: include/linux/bvec.h:101
Inline: True
Inline callers:
  - block/bio.c:__bio_advance
```
```
In block/blk-merge.c (ffffffff8173d3bf)
Location: include/linux/bvec.h:101
Inline: True
Inline callers:
  - block/blk-merge.c:bio_get_last_bvec
```
```
In block/bio-integrity.c (ffffffff8177534b)
Location: include/linux/bvec.h:101
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
```
```
In drivers/md/dm-io.c (ffffffff81d1ac4a)
Location: include/linux/bvec.h:101
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817695e9)
Location: include/linux/bvec.h:140
Inline: True
Inline callers:
  - block/bio.c:__bio_advance
```
```
In block/blk-merge.c (ffffffff81779961)
Location: include/linux/bvec.h:140
Inline: True
Inline callers:
  - block/blk-merge.c:bio_get_last_bvec
```
```
In block/bio-integrity.c (ffffffff817b5050)
Location: include/linux/bvec.h:140
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
```
```
In drivers/md/dm-io.c (ffffffff81d83dba)
Location: include/linux/bvec.h:140
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817ab669)
Location: include/linux/bvec.h:140
Inline: True
Inline callers:
  - block/bio.c:__bio_advance
```
```
In block/blk-merge.c (ffffffff817bbd31)
Location: include/linux/bvec.h:140
Inline: True
Inline callers:
  - block/blk-merge.c:bio_get_last_bvec
```
```
In block/bio-integrity.c (ffffffff817f9a60)
Location: include/linux/bvec.h:140
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
```
```
In drivers/md/dm-io.c (ffffffff81e3b4ca)
Location: include/linux/bvec.h:140
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dae5c)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-core.c (ffff8000105e067c)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-core.c:rq_flush_dcache_pages
```
```
In block/blk-map.c (ffff8000105e9384)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffff8000105e9f24)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (ffff80001061d9f4)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffff80001061e28c)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In block/t10-pi.c (ffff80001061ecac)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/iov_iter.c (ffff80001062f0c8)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/block/loop.c (ffff8000109230b0)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/md/dm-io.c (ffff800010b09ec4)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (c078897c)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-core.c (c078e914)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-core.c:rq_flush_dcache_pages
```
```
In block/blk-map.c (c0795838)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (c0796540)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bounce.c (c07b31ec)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:bounce_end_io
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (c07c5588)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (c07c5dc4)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In block/t10-pi.c (c07c66b4)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/iov_iter.c (c07d5a20)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/block/loop.c (c0a08b98)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/md/dm-io.c (c0be83a0)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076be8c)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-core.c (c000000000774978)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-core.c:rq_flush_dcache_pages
```
```
In block/blk-map.c (c00000000077deac)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (c00000000077ec88)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (c0000000007bc9c8)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (c0000000007bd43c)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In block/t10-pi.c (c0000000007be274)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/iov_iter.c (c0000000007d2ae0)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/block/loop.c (c0000000009c923c)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/md/dm-io.c (c000000000bfb71c)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041eba4)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffe000429a52)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffe00042b11c)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (ffffffe00045076a)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffe000450f5e)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In block/t10-pi.c (ffffffe000451cd6)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/iov_iter.c (ffffffe00045e438)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/block/loop.c (ffffffe0005a1fc6)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/md/dm-io.c (ffffffe0006f7f06)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d7221)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff814e2fff)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff814e3a5b)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bounce.c (ffffffff814fe3ee)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:bounce_end_io
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff8150ed14)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffff8150f414)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In block/t10-pi.c (ffffffff8150fdac)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/iov_iter.c (ffffffff8151d06c)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/block/loop.c (ffffffff816f353b)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/md/dm-io.c (ffffffff8185861e)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c7be1)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff814d397f)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff814d43ac)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bounce.c (ffffffff814ee8fe)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:bounce_end_io
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff814ff144)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffff814ff821)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In block/t10-pi.c (ffffffff815000cc)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/iov_iter.c (ffffffff8150d35c)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/block/loop.c (ffffffff816cd63b)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/nvdimm/pmem.c (ffffffff816ebb3a)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:pmem_make_request
```
```
In drivers/nvdimm/btt.c (ffffffff816ed5d1)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/nvdimm/btt.c:btt_make_request
  - drivers/nvdimm/btt.c:btt_make_request
  - drivers/nvdimm/btt.c:btt_rw_integrity
  - drivers/nvdimm/btt.c:btt_rw_integrity
```
```
In drivers/nvdimm/blk.c (ffffffff816ef3d1)
Location: include/linux/bvec.h:87
Inline: True
```
```
In drivers/md/dm-io.c (ffffffff8181fc2e)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d32b1)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff814df08f)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff814dfaeb)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bounce.c (ffffffff814fa47e)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:bounce_end_io
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff8150ada4)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffff8150b4a4)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In block/t10-pi.c (ffffffff8150be3c)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/iov_iter.c (ffffffff815190fc)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/block/loop.c (ffffffff81720c1b)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/md/dm-io.c (ffffffff818a7c4e)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ebd73)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff814f7eff)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff814f894b)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bounce.c (ffffffff815134de)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:bounce_end_io
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff81524444)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffff81524b44)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In block/t10-pi.c (ffffffff815254f0)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In lib/iov_iter.c (ffffffff815328d0)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter_mcsafe
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/block/loop.c (ffffffff8173bfd1)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/md/dm-io.c (ffffffff818c3e8e)
Location: include/linux/bvec.h:87
Inline: True
Inline callers:
  - drivers/md/dm-io.c:bio_next_page
```
</details>
</li>
</ul>

## Differences
