# Function: <code>bio_op</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff8118883c)
Location: include/linux/blk_types.h:470
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In fs/mpage.c (ffffffff814d965d)
Location: include/linux/blk_types.h:470
Inline: True
Inline callers:
  - fs/mpage.c:mpage_end_io
```
```
In block/bio.c (ffffffff8172ef7f)
Location: include/linux/blk_types.h:470
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:__bio_advance
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_iov_bvec_set
  - block/bio.c:bio_add_zone_append_page
  - block/bio.c:guard_bio_eod
  - block/bio.c:guard_bio_eod
  - block/bio.c:zero_fill_bio
```
```
In block/blk-core.c (ffffffff81736149)
Location: include/linux/blk_types.h:470
Inline: True
Inline callers:
  - block/blk-core.c:bio_end_io_acct_remapped
  - block/blk-core.c:bio_start_io_acct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-map.c (ffffffff8173bafc)
Location: include/linux/blk_types.h:470
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff8173ef05)
Location: include/linux/blk_types.h:470
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_plug_merge
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:bio_split_to_limits
  - block/blk-merge.c:__bio_split_to_limits
  - block/blk-merge.c:bio_split_rw
  - block/blk-merge.c:bio_will_gap
  - block/blk-merge.c:bio_get_last_bvec
```
```
In block/blk-mq.c (ffffffff81747bf4)
Location: include/linux/blk_types.h:470
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_dump_rq_flags
```
```
In block/blk-throttle.c (ffffffff81769466)
Location: include/linux/blk_types.h:470
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_add_bio_tg
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
```
```
In block/blk-iocost.c (ffffffff8176aa02)
Location: include/linux/blk_types.h:470
Inline: True
Inline callers:
  - block/blk-iocost.c:calc_vtime_cost_builtin
```
```
In block/mq-deadline.c (ffffffff817734b2)
Location: include/linux/blk_types.h:470
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_request_merge
```
```
In block/bio-integrity.c (ffffffff8177523f)
Location: include/linux/blk_types.h:470
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-wbt.c (ffffffff8177a40e)
Location: include/linux/blk_types.h:470
Inline: True
```
```
In block/blk-crypto.c (ffffffff81782cbc)
Location: include/linux/blk_types.h:470
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In block/blk-crypto-fallback.c (ffffffff81785403)
Location: include/linux/blk_types.h:470
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
```
In drivers/block/loop.c (ffffffff81b2c5e4)
Location: include/linux/blk_types.h:470
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_read_simple
```
```
In drivers/md/md.c (ffffffff81cf4e01)
Location: include/linux/blk_types.h:470
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_submit_bio
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm-zone.c (ffffffff81d0a303)
Location: include/linux/blk_types.h:470
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_is_zone_write
```
```
In drivers/md/dm.c (ffffffff81d0f69d)
Location: include/linux/blk_types.h:470
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_accept_partial_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dm_io_acct
  - drivers/md/dm.c:dm_io_acct
```
```
In drivers/md/dm-stripe.c (ffffffff81d16361)
Location: include/linux/blk_types.h:470
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff81d1a388)
Location: include/linux/blk_types.h:470
Inline: True
Inline callers:
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-io-rewind.c (ffffffff81d1fe18)
Location: include/linux/blk_types.h:470
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
In kernel/power/swap.c (ffffffff811999fc)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In block/bio.c (ffffffff8176b1af)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:__bio_advance
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_iov_bvec_set
  - block/bio.c:bio_add_zone_append_page
  - block/bio.c:guard_bio_eod
  - block/bio.c:guard_bio_eod
  - block/bio.c:zero_fill_bio
```
```
In block/blk-core.c (ffffffff817726e8)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - block/blk-core.c:bio_end_io_acct_remapped
  - block/blk-core.c:bio_start_io_acct
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-map.c (ffffffff8177823c)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff8177b475)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_plug_merge
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:bio_split_to_limits
  - block/blk-merge.c:__bio_split_to_limits
  - block/blk-merge.c:bio_split_rw
  - block/blk-merge.c:bio_will_gap
  - block/blk-merge.c:bio_get_last_bvec
```
```
In block/blk-mq.c (ffffffff817842a4)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_dump_rq_flags
```
```
In block/blk-throttle.c (ffffffff817a8623)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_add_bio_tg
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
```
```
In block/blk-iocost.c (ffffffff817a9b09)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - block/blk-iocost.c:calc_vtime_cost_builtin
```
```
In block/mq-deadline.c (ffffffff817b2352)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_request_merge
```
```
In block/bio-integrity.c (ffffffff817b4f4c)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-wbt.c (ffffffff817ba20b)
Location: include/linux/blk_types.h:475
Inline: True
```
```
In block/blk-crypto.c (ffffffff817c2ef0)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In block/blk-crypto-fallback.c (ffffffff817c5763)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
```
In drivers/block/loop.c (ffffffff81b7c847)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_read_simple
```
```
In drivers/md/md.c (ffffffff81d5cc11)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_submit_bio
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm-zone.c (ffffffff81d73443)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_is_zone_write
```
```
In drivers/md/dm.c (ffffffff81d78a8d)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_accept_partial_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dm_io_acct
  - drivers/md/dm.c:dm_io_acct
```
```
In drivers/md/dm-stripe.c (ffffffff81d7f481)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff81d834e8)
Location: include/linux/blk_types.h:475
Inline: True
Inline callers:
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-io-rewind.c (ffffffff81d89003)
Location: include/linux/blk_types.h:475
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
In kernel/power/swap.c (ffffffff811a8a5c)
Location: include/linux/blk_types.h:474
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In block/bio.c (ffffffff817ad63f)
Location: include/linux/blk_types.h:474
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:__bio_advance
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_iov_bvec_set
  - block/bio.c:bio_add_zone_append_page
  - block/bio.c:guard_bio_eod
  - block/bio.c:guard_bio_eod
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-core.c (ffffffff817b4a88)
Location: include/linux/blk_types.h:474
Inline: True
Inline callers:
  - block/blk-core.c:bio_end_io_acct_remapped
  - block/blk-core.c:bio_start_io_acct
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-map.c (ffffffff817ba61c)
Location: include/linux/blk_types.h:474
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff817bd865)
Location: include/linux/blk_types.h:474
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_plug_merge
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:bio_split_to_limits
  - block/blk-merge.c:__bio_split_to_limits
  - block/blk-merge.c:bio_split_rw
  - block/blk-merge.c:bio_will_gap
  - block/blk-merge.c:bio_get_last_bvec
```
```
In block/blk-mq.c (ffffffff817c65b2)
Location: include/linux/blk_types.h:474
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_dump_rq_flags
```
```
In block/blk-throttle.c (ffffffff817ec393)
Location: include/linux/blk_types.h:474
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_add_bio_tg
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
```
```
In block/blk-iocost.c (ffffffff817ed8c9)
Location: include/linux/blk_types.h:474
Inline: True
Inline callers:
  - block/blk-iocost.c:calc_vtime_cost_builtin
```
```
In block/mq-deadline.c (ffffffff817f6162)
Location: include/linux/blk_types.h:474
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_request_merge
```
```
In block/bio-integrity.c (ffffffff817f995c)
Location: include/linux/blk_types.h:474
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In block/blk-wbt.c (ffffffff817fe97b)
Location: include/linux/blk_types.h:474
Inline: True
```
```
In block/blk-crypto.c (ffffffff81807b80)
Location: include/linux/blk_types.h:474
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In block/blk-crypto-fallback.c (ffffffff8180a453)
Location: include/linux/blk_types.h:474
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
```
In drivers/block/loop.c (ffffffff81bd0777)
Location: include/linux/blk_types.h:474
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_read_simple
```
```
In drivers/md/md.c (ffffffff81e15cb1)
Location: include/linux/blk_types.h:474
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_submit_bio
  - drivers/md/md.c:md_handle_request
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm-zone.c (ffffffff81e2a53d)
Location: include/linux/blk_types.h:474
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_is_zone_write
```
```
In drivers/md/dm.c (ffffffff81e2fcc9)
Location: include/linux/blk_types.h:474
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_accept_partial_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dm_io_acct
  - drivers/md/dm.c:dm_io_acct
```
```
In drivers/md/dm-stripe.c (ffffffff81e36aa1)
Location: include/linux/blk_types.h:474
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff81e3aba8)
Location: include/linux/blk_types.h:474
Inline: True
Inline callers:
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-io-rewind.c (ffffffff81e40743)
Location: include/linux/blk_types.h:474
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
