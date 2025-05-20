# Function: <code>bio_integrity</code>

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
In block/bio.c (ffffffff813b0888)
Location: include/linux/bio.h:376
Inline: True
Inline callers:
  - block/bio.c:bio_advance
  - block/bio.c:__bio_free
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_split
```
```
In block/blk-merge.c (ffffffff813c0d3f)
Location: include/linux/bio.h:376
Inline: True
Inline callers:
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
```
```
In block/bio-integrity.c (ffffffff813e6f52)
Location: include/linux/bio.h:376
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_enabled
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_prep
```
```
In block/blk-integrity.c (ffffffff813e8294)
Location: include/linux/bio.h:376
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
```
```
In drivers/scsi/sd.c (ffffffff815bbe4e)
Location: include/linux/bio.h:376
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff815bf82e)
Location: include/linux/bio.h:376
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_prepare
  - drivers/scsi/sd_dif.c:sd_dif_complete
```
```
In drivers/md/dm.c (ffffffff816a29d1)
Location: include/linux/bio.h:376
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
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
In block/bio.c (ffffffff813f6bdb)
Location: include/linux/bio.h:325
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_fast
  - block/bio.c:__bio_free
```
```
In block/blk-merge.c (ffffffff81405241)
Location: include/linux/bio.h:325
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bio-integrity.c (ffffffff8142d5ee)
Location: include/linux/bio.h:325
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_enabled
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffffffff8142e8fb)
Location: include/linux/bio.h:325
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
```
```
In drivers/scsi/sd.c (ffffffff816146c8)
Location: include/linux/bio.h:325
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff81618242)
Location: include/linux/bio.h:325
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/md/dm.c (ffffffff817032e3)
Location: include/linux/bio.h:325
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
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
In block/bio.c (ffffffff8141024b)
Location: include/linux/bio.h:322
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_fast
  - block/bio.c:__bio_free
```
```
In block/blk-merge.c (ffffffff8141f15c)
Location: include/linux/bio.h:322
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bio-integrity.c (ffffffff814473ce)
Location: include/linux/bio.h:322
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_enabled
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffffffff8144867b)
Location: include/linux/bio.h:322
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
```
```
In drivers/scsi/sd.c (ffffffff81644080)
Location: include/linux/bio.h:322
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff81647de2)
Location: include/linux/bio.h:322
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/md/dm.c (ffffffff817351b0)
Location: include/linux/bio.h:322
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
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
In block/bio.c (ffffffff8141dc8d)
Location: include/linux/bio.h:336
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_fast
```
```
In block/blk-merge.c (ffffffff8142cf9c)
Location: include/linux/bio.h:336
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bio-integrity.c (ffffffff814557bc)
Location: include/linux/bio.h:336
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_clone
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffffffff81456b54)
Location: include/linux/bio.h:336
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
```
```
In drivers/scsi/sd.c (ffffffff81659f3f)
Location: include/linux/bio.h:336
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff8165c91e)
Location: include/linux/bio.h:336
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/md/dm.c (ffffffff8174d3e6)
Location: include/linux/bio.h:336
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
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
In block/bio.c (ffffffff8144771d)
Location: include/linux/bio.h:332
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_fast
```
```
In block/blk-merge.c (ffffffff814581ac)
Location: include/linux/bio.h:332
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bio-integrity.c (ffffffff8148143c)
Location: include/linux/bio.h:332
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_clone
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffffffff814827a4)
Location: include/linux/bio.h:332
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
```
```
In drivers/scsi/sd.c (ffffffff816c318a)
Location: include/linux/bio.h:332
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff816c5f6d)
Location: include/linux/bio.h:332
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/md/dm.c (ffffffff817bf5c6)
Location: include/linux/bio.h:332
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
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
In block/bio.c (ffffffff8147a820)
Location: include/linux/bio.h:364
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_fast
```
```
In block/blk-merge.c (ffffffff8148b442)
Location: include/linux/bio.h:364
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bio-integrity.c (ffffffff814b6045)
Location: include/linux/bio.h:364
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_clone
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffffffff814b73a4)
Location: include/linux/bio.h:364
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
```
```
In drivers/scsi/sd.c (ffffffff816ff42e)
Location: include/linux/bio.h:364
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/scsi/sd_dif.c (ffffffff817024f5)
Location: include/linux/bio.h:364
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_complete
  - drivers/scsi/sd_dif.c:sd_dif_prepare
```
```
In drivers/md/dm.c (ffffffff81808735)
Location: include/linux/bio.h:364
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
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
In block/bio.c (ffffffff81498b40)
Location: include/linux/bio.h:320
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_fast
```
```
In block/blk-merge.c (ffffffff814a5122)
Location: include/linux/bio.h:320
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bounce.c (ffffffff814be3f1)
Location: include/linux/bio.h:320
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff814c98f5)
Location: include/linux/bio.h:320
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_clone
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffffffff814cab84)
Location: include/linux/bio.h:320
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
```
```
In block/t10-pi.c (ffffffff814cb02f)
Location: include/linux/bio.h:320
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_complete
  - block/t10-pi.c:t10_pi_prepare
```
```
In drivers/scsi/sd.c (ffffffff817221e8)
Location: include/linux/bio.h:320
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/md/dm.c (ffffffff818345e5)
Location: include/linux/bio.h:320
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
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
In block/bio.c (ffffffff814c6b19)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_fast
```
```
In block/blk-merge.c (ffffffff814d3201)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bounce.c (ffffffff814ecb7a)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff814f84a5)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_clone
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffffffff814f9463)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
```
```
In block/t10-pi.c (ffffffff814f9959)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_complete
  - block/t10-pi.c:t10_pi_prepare
```
```
In drivers/scsi/sd.c (ffffffff8175e4b8)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/md/dm.c (ffffffff818763b5)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
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
In block/bio.c (ffffffff814df929)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_fast
```
```
In block/blk-merge.c (ffffffff814ec531)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bounce.c (ffffffff81505fca)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff81516225)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_clone
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffffffff81517323)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
```
```
In block/t10-pi.c (ffffffff815176e4)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/scsi/sd.c (ffffffff81782494)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/md/dm.c (ffffffff818a81b4)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
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
In block/bio.c (ffffffff8153f3bf)
Location: include/linux/bio.h:335
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_uninit
```
```
In block/blk-merge.c (ffffffff8154c504)
Location: include/linux/bio.h:335
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bounce.c (ffffffff815667f3)
Location: include/linux/bio.h:335
Inline: True
```
```
In block/bio-integrity.c (ffffffff81576715)
Location: include/linux/bio.h:335
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_clone
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffffffff81577a93)
Location: include/linux/bio.h:335
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
```
```
In block/t10-pi.c (ffffffff81577ea4)
Location: include/linux/bio.h:335
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/scsi/sd.c (ffffffff81843be2)
Location: include/linux/bio.h:335
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
```
```
In drivers/md/dm.c (ffffffff819770d5)
Location: include/linux/bio.h:335
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_bio
  - drivers/md/dm.c:clone_bio
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
In block/bio.c (ffffffff8155bbbf)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_uninit
```
```
In block/blk-merge.c (ffffffff81567dbe)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
```
```
In block/bounce.c (ffffffff815816fb)
Location: include/linux/bio.h:346
Inline: True
```
```
In block/bio-integrity.c (ffffffff81593635)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_clone
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffffffff81594643)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_rq
  - block/blk-integrity.c:blk_integrity_merge_rq
```
```
In block/t10-pi.c (ffffffff81594b25)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/scsi/sd.c (ffffffff81853f12)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
```
```
In drivers/md/dm.c (ffffffff8197bcc5)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_bio
  - drivers/md/dm.c:clone_bio
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
In block/bio.c (ffffffff8156424f)
Location: include/linux/bio.h:347
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_uninit
```
```
In block/blk-merge.c (ffffffff81570c65)
Location: include/linux/bio.h:347
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_front_merge
```
```
In block/bio-integrity.c (ffffffff8159a415)
Location: include/linux/bio.h:347
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_clone
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffffffff8159b423)
Location: include/linux/bio.h:347
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_rq
  - block/blk-integrity.c:blk_integrity_merge_rq
```
```
In block/t10-pi.c (ffffffff8159b8f5)
Location: include/linux/bio.h:347
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/scsi/sd.c (ffffffff8183794b)
Location: include/linux/bio.h:347
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
```
```
In drivers/md/dm.c (ffffffff819611e3)
Location: include/linux/bio.h:347
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
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
In block/bio.c (ffffffff815c6b81)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_uninit
```
```
In block/blk-merge.c (ffffffff815d5315)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_front_merge
```
```
In block/bio-integrity.c (ffffffff81602575)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_clone
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffffffff81603683)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_rq
  - block/blk-integrity.c:blk_integrity_merge_rq
```
```
In block/t10-pi.c (ffffffff8160388c)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/scsi/sd.c (ffffffff818c2d45)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
```
```
In drivers/md/dm.c (ffffffff81a0ae03)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
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
In block/bio.c (ffffffff81671aa3)
Location: include/linux/bio.h:344
Inline: True
Inline callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:__bio_advance
  - block/bio.c:__bio_clone
  - block/bio.c:bio_uninit
```
```
In block/blk-merge.c (ffffffff816810ff)
Location: include/linux/bio.h:344
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bio-integrity.c (ffffffff816b57f5)
Location: include/linux/bio.h:344
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_clone
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffffffff816b63e3)
Location: include/linux/bio.h:344
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_rq
  - block/blk-integrity.c:blk_integrity_merge_rq
```
```
In block/t10-pi.c (ffffffff816b6aab)
Location: include/linux/bio.h:344
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/scsi/sd.c (ffffffff81a0f735)
Location: include/linux/bio.h:344
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
```
```
In drivers/md/dm.c (ffffffff81b70385)
Location: include/linux/bio.h:344
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_tio
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
In block/bio.c (ffffffff8172d343)
Location: include/linux/bio.h:344
Inline: True
Inline callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:__bio_advance
  - block/bio.c:__bio_clone
  - block/bio.c:bio_uninit
```
```
In block/blk-merge.c (ffffffff8173e68a)
Location: include/linux/bio.h:344
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bio-integrity.c (ffffffff81775405)
Location: include/linux/bio.h:344
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_clone
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffffffff81776223)
Location: include/linux/bio.h:344
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_rq
  - block/blk-integrity.c:blk_integrity_merge_rq
```
```
In block/t10-pi.c (ffffffff81776a6b)
Location: include/linux/bio.h:344
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/scsi/sd.c (ffffffff81b8f915)
Location: include/linux/bio.h:344
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
```
```
In drivers/md/dm.c (ffffffff81d0cc95)
Location: include/linux/bio.h:344
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_tio
```
```
In drivers/md/dm-io-rewind.c (ffffffff81d1fd35)
Location: include/linux/bio.h:344
Inline: True
Inline callers:
  - drivers/md/dm-io-rewind.c:dm_io_rewind
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
In block/bio.c (ffffffff817696f3)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:__bio_advance
  - block/bio.c:__bio_clone
  - block/bio.c:bio_uninit
```
```
In block/blk-merge.c (ffffffff8177abea)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bio-integrity.c (ffffffff817b5105)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_clone
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffffffff817b5ed3)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_rq
  - block/blk-integrity.c:blk_integrity_merge_rq
```
```
In block/t10-pi.c (ffffffff817b6642)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/scsi/sd.c (ffffffff81be5de4)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
```
```
In drivers/md/dm.c (ffffffff81d75a64)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_tio
```
```
In drivers/md/dm-io-rewind.c (ffffffff81d88f26)
Location: include/linux/bio.h:346
Inline: True
Inline callers:
  - drivers/md/dm-io-rewind.c:dm_io_rewind
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
In block/bio.c (ffffffff817ab773)
Location: include/linux/bio.h:356
Inline: True
Inline callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:__bio_advance
  - block/bio.c:__bio_clone
  - block/bio.c:bio_uninit
```
```
In block/blk-merge.c (ffffffff817bcfca)
Location: include/linux/bio.h:356
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bio-integrity.c (ffffffff817f9b15)
Location: include/linux/bio.h:356
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_clone
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_map_user
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffffffff817fa8e3)
Location: include/linux/bio.h:356
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_rq
  - block/blk-integrity.c:blk_integrity_merge_rq
```
```
In block/t10-pi.c (ffffffff817fb052)
Location: include/linux/bio.h:356
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/scsi/sd.c (ffffffff81c3b234)
Location: include/linux/bio.h:356
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
  - drivers/scsi/sd.c:sd_setup_protect_cmnd
```
```
In drivers/md/dm.c (ffffffff81e2cb64)
Location: include/linux/bio.h:356
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_tio
```
```
In drivers/md/dm-io-rewind.c (ffffffff81e40666)
Location: include/linux/bio.h:356
Inline: True
Inline callers:
  - drivers/md/dm-io-rewind.c:dm_io_rewind
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
In block/bio.c (ffff8000105dc490)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_fast
```
```
In block/blk-merge.c (ffff8000105eafa0)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bio-integrity.c (ffff80001061d164)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_clone
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffff80001061e7c4)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
```
```
In block/t10-pi.c (ffff80001061ebc8)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/scsi/sd.c (ffff8000109891b4)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/md/dm.c (ffff800010afef14)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
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
In block/bio.c (c07898f8)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_fast
```
```
In block/blk-merge.c (c0797508)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bounce.c (c07b32e4)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (c07c5040)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_clone
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (c07c6214)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
```
```
In block/t10-pi.c (c07c65ac)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/scsi/sd.c (c0a5b178)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/md/dm.c (c0bddd7c)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
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
In block/bio.c (c00000000076d4d0)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_fast
```
```
In block/blk-merge.c (c0000000007804bc)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bio-integrity.c (c0000000007bc1e0)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_clone
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (c0000000007bd9c8)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
```
```
In block/t10-pi.c (c0000000007be130)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/scsi/sd.c (c000000000a48fd4)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/md/dm.c (c000000000becd70)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
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
In block/bio.c (ffffffe00041f862)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_fast
```
```
In block/blk-merge.c (ffffffe00042b20a)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bio-integrity.c (ffffffe00044fd58)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffffffe00045131a)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
```
```
In block/t10-pi.c (ffffffe000451bc2)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/scsi/sd.c (ffffffe0005ed24a)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/md/dm.c (ffffffe0006ee664)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
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
In block/bio.c (ffffffff814d7f09)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_fast
```
```
In block/blk-merge.c (ffffffff814e4b11)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bounce.c (ffffffff814fe5aa)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff8150e805)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_clone
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffffffff8150f903)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
```
```
In block/t10-pi.c (ffffffff8150fcc4)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/scsi/sd.c (ffffffff81736b84)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/md/dm.c (ffffffff8184e034)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
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
In block/bio.c (ffffffff814c88b9)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_fast
```
```
In block/blk-merge.c (ffffffff814d52d0)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bounce.c (ffffffff814eeaba)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff814fec35)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_clone
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffffffff814ffc23)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
```
```
In block/t10-pi.c (ffffffff814fffe4)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/nvdimm/btt.c (ffffffff816ed425)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - drivers/nvdimm/btt.c:btt_make_request
```
```
In drivers/nvdimm/blk.c (ffffffff816ef086)
Location: include/linux/bio.h:327
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81718824)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/md/dm.c (ffffffff81815654)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
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
In block/bio.c (ffffffff814d3f99)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_fast
```
```
In block/blk-merge.c (ffffffff814e0ba1)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bounce.c (ffffffff814fa63a)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff8150a895)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_clone
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffffffff8150b993)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
```
```
In block/t10-pi.c (ffffffff8150bd54)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/scsi/sd.c (ffffffff81777314)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/md/dm.c (ffffffff8189d664)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
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
In block/bio.c (ffffffff814ecb29)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_fast
```
```
In block/blk-merge.c (ffffffff814f9a21)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bounce.c (ffffffff815137c5)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/bio-integrity.c (ffffffff81523f35)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_clone
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_add_page
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-integrity.c (ffffffff81525033)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
  - block/blk-integrity.c:blk_integrity_merge_bio
```
```
In block/t10-pi.c (ffffffff815253f4)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In drivers/scsi/sd.c (ffffffff81791134)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
```
In drivers/md/dm.c (ffffffff818b99c4)
Location: include/linux/bio.h:327
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
```
</details>
</li>
</ul>

## Differences
