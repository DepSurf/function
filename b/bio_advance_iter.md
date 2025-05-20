# Function: <code>bio_advance_iter</code>

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
In block/bio.c (ffffffff813b089d)
Location: include/linux/bio.h:223
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
In block/blk-merge.c (ffffffff813bfcc3)
Location: include/linux/bio.h:223
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
In block/bounce.c (ffffffff813d4fcd)
Location: include/linux/bio.h:223
Inline: True
```
```
In block/bio-integrity.c (ffffffff813e76bc)
Location: include/linux/bio.h:223
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/block/brd.c (ffffffff8156d933)
Location: include/linux/bio.h:223
Inline: True
Inline callers:
  - drivers/block/brd.c:brd_make_request
```
```
In drivers/block/loop.c (ffffffff81570830)
Location: include/linux/bio.h:223
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
In drivers/block/xen-blkfront.c (ffffffff81578517)
Location: include/linux/bio.h:223
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_recover
  - drivers/block/xen-blkfront.c:blkif_recover
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
In block/bio.c (ffffffff813f4d6d)
Location: include/linux/bio.h:169
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
In block/blk-merge.c (ffffffff814050d8)
Location: include/linux/bio.h:169
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
In block/bounce.c (ffffffff8141ac8d)
Location: include/linux/bio.h:169
Inline: True
```
```
In block/bio-integrity.c (ffffffff8142d936)
Location: include/linux/bio.h:169
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/block/brd.c (ffffffff815c3177)
Location: include/linux/bio.h:169
Inline: True
Inline callers:
  - drivers/block/brd.c:brd_make_request
```
```
In drivers/block/loop.c (ffffffff815c6482)
Location: include/linux/bio.h:169
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/block/xen-blkfront.c (ffffffff815cdc7b)
Location: include/linux/bio.h:169
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
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
In block/bio.c (ffffffff8140e762)
Location: include/linux/bio.h:164
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
In block/blk-merge.c (ffffffff8141ef43)
Location: include/linux/bio.h:164
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
Location: include/linux/bio.h:164
Inline: True
```
```
In block/bio-integrity.c (ffffffff8144770b)
Location: include/linux/bio.h:164
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/block/loop.c (ffffffff815f4a16)
Location: include/linux/bio.h:164
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/block/xen-blkfront.c (ffffffff815fa7fb)
Location: include/linux/bio.h:164
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
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
In block/bio.c (ffffffff8141c26b)
Location: include/linux/bio.h:163
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
In block/blk-merge.c (ffffffff8142d44a)
Location: include/linux/bio.h:163
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
In block/bounce.c (ffffffff81442f09)
Location: include/linux/bio.h:163
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff81455b00)
Location: include/linux/bio.h:163
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/block/loop.c (ffffffff81608c8a)
Location: include/linux/bio.h:163
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
```
```
In drivers/md/dm.c (ffffffff8174c2c7)
Location: include/linux/bio.h:163
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_remap_zone_report
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
In block/bio.c (ffffffff81446e37)
Location: include/linux/bio.h:159
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
In block/blk-merge.c (ffffffff81458693)
Location: include/linux/bio.h:159
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
In block/bounce.c (ffffffff8146f990)
Location: include/linux/bio.h:159
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff81481763)
Location: include/linux/bio.h:159
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/block/loop.c (ffffffff81671544)
Location: include/linux/bio.h:159
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
In drivers/md/dm.c (ffffffff817be68c)
Location: include/linux/bio.h:159
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_remap_zone_report
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
In block/bio.c (ffffffff81479f66)
Location: include/linux/bio.h:168
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
In block/blk-merge.c (ffffffff8148b638)
Location: include/linux/bio.h:168
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
In block/bounce.c (ffffffff814a3b80)
Location: include/linux/bio.h:168
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
  - block/bounce.c:bounce_end_io
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff814b6227)
Location: include/linux/bio.h:168
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/block/loop.c (ffffffff816acfc3)
Location: include/linux/bio.h:168
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
In drivers/md/dm.c (ffffffff8180699b)
Location: include/linux/bio.h:168
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_remap_zone_report
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
In block/bio.c (ffffffff81497d7a)
Location: include/linux/bio.h:138
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-merge.c (ffffffff814a52b6)
Location: include/linux/bio.h:138
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
In block/bounce.c (ffffffff814be24e)
Location: include/linux/bio.h:138
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
In block/bio-integrity.c (ffffffff814c9b27)
Location: include/linux/bio.h:138
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/block/loop.c (ffffffff816cd26a)
Location: include/linux/bio.h:138
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
In block/bio.c (ffffffff814c58ac)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff814d165a)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff814d342a)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bounce.c (ffffffff814ec98e)
Location: include/linux/bio.h:141
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
In block/bio-integrity.c (ffffffff814f81f6)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/block/loop.c (ffffffff817093d1)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
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
In block/bio.c (ffffffff814deaac)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff814eaa0a)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff814ec75a)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bounce.c (ffffffff81505dde)
Location: include/linux/bio.h:141
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
In block/bio-integrity.c (ffffffff81515fd6)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/block/loop.c (ffffffff8172d73a)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
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
In block/bio.c (ffffffff8153e478)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff81549d44)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff8154c6e2)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/bounce.c (ffffffff81566aef)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:bounce_end_io
  - block/bounce.c:copy_to_high_bio_irq
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff8157696d)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-crypto.c (ffffffff8158186a)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-crypto.c:bio_crypt_check_alignment
```
```
In block/blk-crypto-fallback.c (ffffffff815825f1)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_split_bio_if_needed
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
```
In drivers/block/loop.c (ffffffff817e937f)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_read_simple
  - drivers/block/loop.c:lo_write_transfer
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
In block/bio.c (ffffffff8155a635)
Location: include/linux/bio.h:139
Inline: True
Inline callers:
  - block/bio.c:bio_advance
```
```
In block/blk-merge.c (ffffffff81566dda)
Location: include/linux/bio.h:139
Inline: True
Inline callers:
  - block/blk-merge.c:bio_get_last_bvec
```
```
In block/bounce.c (ffffffff815811b5)
Location: include/linux/bio.h:139
Inline: True
Inline callers:
  - block/bounce.c:bounce_end_io
  - block/bounce.c:copy_to_high_bio_irq
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
In block/bio.c (ffffffff81562e05)
Location: include/linux/bio.h:142
Inline: True
Inline callers:
  - block/bio.c:bio_advance
```
```
In block/blk-merge.c (ffffffff8156fb41)
Location: include/linux/bio.h:142
Inline: True
Inline callers:
  - block/blk-merge.c:bio_get_last_bvec
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
In block/bio.c (ffffffff815c6a75)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio.c:bio_advance
```
```
In block/blk-merge.c (ffffffff815d41e1)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-merge.c:bio_get_last_bvec
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
In block/bio.c (ffffffff81671975)
Location: include/linux/bio.h:96
Inline: True
Inline callers:
  - block/bio.c:__bio_advance
```
```
In block/blk-merge.c (ffffffff8167ffc2)
Location: include/linux/bio.h:96
Inline: True
Inline callers:
  - block/blk-merge.c:bio_get_last_bvec
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
In block/bio.c (ffffffff8172d205)
Location: include/linux/bio.h:96
Inline: True
Inline callers:
  - block/bio.c:__bio_advance
```
```
In block/blk-merge.c (ffffffff8173d372)
Location: include/linux/bio.h:96
Inline: True
Inline callers:
  - block/blk-merge.c:bio_get_last_bvec
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
In block/bio.c (ffffffff817695a5)
Location: include/linux/bio.h:98
Inline: True
Inline callers:
  - block/bio.c:__bio_advance
```
```
In block/blk-merge.c (ffffffff81779912)
Location: include/linux/bio.h:98
Inline: True
Inline callers:
  - block/blk-merge.c:bio_get_last_bvec
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
In block/bio.c (ffffffff817ab625)
Location: include/linux/bio.h:98
Inline: True
Inline callers:
  - block/bio.c:__bio_advance
```
```
In block/blk-merge.c (ffffffff817bbce2)
Location: include/linux/bio.h:98
Inline: True
Inline callers:
  - block/blk-merge.c:bio_get_last_bvec
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
In block/bio.c (ffff8000105dae2c)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-core.c (ffff8000105e0644)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-core.c:rq_flush_dcache_pages
```
```
In block/blk-map.c (ffff8000105e9368)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffff8000105eb178)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (ffff80001061d3cc)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/block/loop.c (ffff800010922db0)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
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
In block/bio.c (c0788944)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-core.c (c078e8e8)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-core.c:rq_flush_dcache_pages
```
```
In block/blk-map.c (c0795828)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (c07976c4)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bounce.c (c07b31dc)
Location: include/linux/bio.h:141
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
In block/bio-integrity.c (c07c4dbc)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/block/loop.c (c0a08b78)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
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
In block/bio.c (c00000000076be58)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-core.c (c00000000077494c)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-core.c:rq_flush_dcache_pages
```
```
In block/blk-map.c (c00000000077dea4)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (c000000000780360)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (c0000000007bbe60)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/block/loop.c (c0000000009c921c)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
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
In block/bio.c (ffffffe00041eb7c)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffe000429a1c)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffe00042b10c)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (ffffffe00045022e)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/block/loop.c (ffffffe0005a1f3e)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
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
In block/bio.c (ffffffff814d708c)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff814e2fea)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff814e4d3a)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bounce.c (ffffffff814fe3be)
Location: include/linux/bio.h:141
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
In block/bio-integrity.c (ffffffff8150e5b6)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/block/loop.c (ffffffff816f351a)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
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
In block/bio.c (ffffffff814c7a4c)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff814d396a)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff814d549f)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bounce.c (ffffffff814ee8ce)
Location: include/linux/bio.h:141
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
In block/bio-integrity.c (ffffffff814fe9e6)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/block/loop.c (ffffffff816cd61a)
Location: include/linux/bio.h:141
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
In drivers/nvdimm/pmem.c (ffffffff816ebb09)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:pmem_make_request
```
```
In drivers/nvdimm/btt.c (ffffffff816ed505)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - drivers/nvdimm/btt.c:btt_make_request
```
```
In drivers/nvdimm/blk.c (ffffffff816ef461)
Location: include/linux/bio.h:141
Inline: True
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
In block/bio.c (ffffffff814d311c)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff814df07a)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff814e0dca)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bounce.c (ffffffff814fa44e)
Location: include/linux/bio.h:141
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
In block/bio-integrity.c (ffffffff8150a646)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/block/loop.c (ffffffff81720bfa)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
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
In block/bio.c (ffffffff814ebb4d)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_advance
  - block/bio.c:bio_truncate
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff814f7eea)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff814f9c4a)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bounce.c (ffffffff815134ae)
Location: include/linux/bio.h:141
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
In block/bio-integrity.c (ffffffff81523cca)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/block/loop.c (ffffffff8173bfb2)
Location: include/linux/bio.h:141
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio
  - drivers/block/loop.c:lo_rw_aio
```
</details>
</li>
</ul>

## Differences
