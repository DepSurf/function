# Function: <code>bio_flagged</code>

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
In fs/buffer.c (0)
Location: include/linux/bio.h:298
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/bio.h:298
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/bio.h:298
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/bio.h:298
Inline: True
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
In fs/buffer.c (0)
Location: include/linux/bio.h:247
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/bio.h:247
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/bio.h:247
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/bio.h:247
Inline: True
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
In fs/buffer.c (0)
Location: include/linux/bio.h:244
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/bio.h:244
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/bio.h:244
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/bio.h:244
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/bio.h:244
Inline: True
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
In fs/buffer.c (0)
Location: include/linux/bio.h:260
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/bio.h:260
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/bio.h:260
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/bio.h:260
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/bio.h:260
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/bio.h:260
Inline: True
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
In fs/buffer.c (0)
Location: include/linux/bio.h:256
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/bio.h:256
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/bio.h:256
Inline: True
```
```
In block/blk-map.c (0)
Location: include/linux/bio.h:256
Inline: True
```
```
In block/blk-merge.c (0)
Location: include/linux/bio.h:256
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/bio.h:256
Inline: True
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
In kernel/power/swap.c (ffffffff810ed975)
Location: include/linux/bio.h:265
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff81246aa5)
Location: include/linux/bio.h:265
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/buffer.c (ffffffff812d8345)
Location: include/linux/bio.h:265
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:end_bio_bh_io_sync
```
```
In block/bio.c (ffffffff8147a849)
Location: include/linux/bio.h:265
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_uncopy_user
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_try_merge_page
  - block/bio.c:__bio_clone_fast
  - block/bio.c:bio_phys_segments
```
```
In block/blk-core.c (ffffffff814832a6)
Location: include/linux/bio.h:265
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-map.c (ffffffff8148993b)
Location: include/linux/bio.h:265
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:__blk_rq_unmap_user
```
```
In block/blk-merge.c (ffffffff8148b56a)
Location: include/linux/bio.h:265
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_recount_segments
```
```
In block/blk-throttle.c (ffffffff814ac5e9)
Location: include/linux/bio.h:265
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
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
In kernel/power/swap.c (ffffffff810f8fe5)
Location: include/linux/bio.h:219
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff8125aec5)
Location: include/linux/bio.h:219
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/buffer.c (ffffffff812ed815)
Location: include/linux/bio.h:219
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:end_bio_bh_io_sync
```
```
In block/bio.c (ffffffff81498b60)
Location: include/linux/bio.h:219
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_uncopy_user
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_try_merge_page
  - block/bio.c:__bio_clone_fast
  - block/bio.c:bio_phys_segments
```
```
In block/blk-core.c (ffffffff8149ea76)
Location: include/linux/bio.h:219
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-map.c (ffffffff814a3779)
Location: include/linux/bio.h:219
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:__blk_rq_unmap_user
```
```
In block/blk-merge.c (ffffffff814a53ba)
Location: include/linux/bio.h:219
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_recount_segments
```
```
In block/blk-throttle.c (ffffffff814c699a)
Location: include/linux/bio.h:219
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
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
In kernel/power/swap.c (ffffffff811016e5)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff81275ec5)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/buffer.c (ffffffff8130efa5)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - fs/buffer.c:guard_bio_eod
  - fs/buffer.c:end_bio_bh_io_sync
```
```
In block/bio.c (ffffffff814c6b3d)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_try_merge_page
  - block/bio.c:__bio_add_pc_page
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814cb7ee)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-map.c (ffffffff814d19ee)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:__blk_rq_unmap_user
```
```
In block/blk-throttle.c (ffffffff814f51d8)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
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
In kernel/power/swap.c (ffffffff8110db15)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff81285995)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/buffer.c (ffffffff8131fd72)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - fs/buffer.c:end_bio_bh_io_sync
```
```
In fs/verity/verify.c (ffffffff81351745)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In block/bio.c (ffffffff814df94d)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_try_merge_page
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814e61c8)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-map.c (ffffffff814eabae)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:__blk_rq_unmap_user
```
```
In block/blk-throttle.c (ffffffff8150e8a8)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
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
In kernel/power/swap.c (ffffffff81118b35)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff812b7d35)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/buffer.c (ffffffff8135a4a2)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - fs/buffer.c:end_bio_bh_io_sync
```
```
In fs/verity/verify.c (ffffffff813981f5)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff813ab2b8)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
```
```
In block/bio.c (ffffffff8153f3e2)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_try_merge_page
  - block/bio.c:bio_add_hw_page
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff815454b6)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blkcg_bio_issue_check
```
```
In block/blk-map.c (ffffffff8154a6be)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:__blk_rq_unmap_user
  - block/blk-map.c:__blk_rq_unmap_user
```
```
In block/blk-throttle.c (ffffffff8156fe67)
Location: include/linux/bio.h:240
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
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
In kernel/power/swap.c (ffffffff81114605)
Location: include/linux/bio.h:251
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff812c33e5)
Location: include/linux/bio.h:251
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/buffer.c (ffffffff81368502)
Location: include/linux/bio.h:251
Inline: True
Inline callers:
  - fs/buffer.c:end_bio_bh_io_sync
```
```
In fs/verity/verify.c (ffffffff813a9a75)
Location: include/linux/bio.h:251
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff813bc7e8)
Location: include/linux/bio.h:251
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
```
```
In block/bio.c (ffffffff8155bbe2)
Location: include/linux/bio.h:251
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_try_merge_page
  - block/bio.c:bio_add_hw_page
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff81561b16)
Location: include/linux/bio.h:251
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-map.c (ffffffff81566443)
Location: include/linux/bio.h:251
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
```
```
In block/blk-cgroup.c (ffffffff81586e84)
Location: include/linux/bio.h:251
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-throttle.c (ffffffff8158acb3)
Location: include/linux/bio.h:251
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
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
In kernel/power/swap.c (ffffffff81114dc5)
Location: include/linux/bio.h:254
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff812ca1f5)
Location: include/linux/bio.h:254
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/buffer.c (ffffffff8136e822)
Location: include/linux/bio.h:254
Inline: True
Inline callers:
  - fs/buffer.c:end_bio_bh_io_sync
```
```
In fs/verity/verify.c (ffffffff813b0fb5)
Location: include/linux/bio.h:254
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff813c2d0c)
Location: include/linux/bio.h:254
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
```
```
In block/bio.c (ffffffff81564272)
Location: include/linux/bio.h:254
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_try_merge_page
  - block/bio.c:bio_add_hw_page
  - block/bio.c:__bio_clone_fast
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff8156a276)
Location: include/linux/bio.h:254
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-cgroup.c (ffffffff8158dcc8)
Location: include/linux/bio.h:254
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-throttle.c (ffffffff8159179b)
Location: include/linux/bio.h:254
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
```
```
In block/blk-crypto-fallback.c (ffffffff815a6400)
Location: include/linux/bio.h:254
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
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
In kernel/power/swap.c (ffffffff81135445)
Location: include/linux/bio.h:253
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff8130f215)
Location: include/linux/bio.h:253
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/buffer.c (ffffffff813bd522)
Location: include/linux/bio.h:253
Inline: True
Inline callers:
  - fs/buffer.c:end_bio_bh_io_sync
```
```
In fs/verity/verify.c (ffffffff81400c95)
Location: include/linux/bio.h:253
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8141239c)
Location: include/linux/bio.h:253
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
```
```
In block/bio.c (ffffffff815c8562)
Location: include/linux/bio.h:253
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_try_merge_page
  - block/bio.c:__bio_clone_fast
  - block/bio.c:__bio_clone_fast
  - block/bio.c:bio_put
  - block/bio.c:bio_put
```
```
In block/blk-core.c (ffffffff815cda16)
Location: include/linux/bio.h:253
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-cgroup.c (ffffffff815f3757)
Location: include/linux/bio.h:253
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-throttle.c (ffffffff815f89d4)
Location: include/linux/bio.h:253
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
```
```
In block/blk-crypto-fallback.c (ffffffff8160ef20)
Location: include/linux/bio.h:253
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
```
In drivers/md/dm-zone.c (ffffffff81a061bd)
Location: include/linux/bio.h:253
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
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
In kernel/power/swap.c (ffffffff81157935)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff81379475)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/buffer.c (ffffffff81442bf1)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - fs/buffer.c:end_bio_bh_io_sync
```
```
In fs/direct-io.c (ffffffff81448d7d)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/verity/verify.c (ffffffff81474d15)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff814884c4)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/iomap/direct-io.c (ffffffff8148d985)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In block/fops.c (ffffffff8166fcc1)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/bio.c (ffffffff81673465)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_add_page
  - block/bio.c:bio_add_hw_page
  - block/bio.c:__bio_try_merge_page
  - block/bio.c:__bio_clone
  - block/bio.c:__bio_clone
  - block/bio.c:bio_put
```
```
In block/blk-core.c (ffffffff816793fc)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-map.c (ffffffff8167ebcd)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_map_user_iov
```
```
In block/blk-cgroup.c (ffffffff816a4d92)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-throttle.c (ffffffff816a5923)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_charge_bio
  - block/blk-throttle.c:throtl_charge_bio
  - block/blk-throttle.c:tg_may_dispatch
```
```
In block/blk-crypto-fallback.c (ffffffff816c37bb)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
```
In drivers/md/dm-zone.c (ffffffff81b6de2f)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
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
In kernel/power/swap.c (ffffffff81188825)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff813f6e95)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/buffer.c (ffffffff814d1c21)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - fs/buffer.c:end_bio_bh_io_sync
```
```
In fs/direct-io.c (ffffffff814d71aa)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/verity/verify.c (ffffffff815070f5)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8151c344)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/iomap/direct-io.c (ffffffff81521145)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In block/fops.c (ffffffff8172b191)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:__blkdev_direct_IO
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/bio.c (ffffffff8172eff5)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_dirty_fn
  - block/bio.c:__bio_add_page
  - block/bio.c:bio_add_hw_page
  - block/bio.c:__bio_try_merge_page
  - block/bio.c:__bio_clone
```
```
In block/blk-core.c (ffffffff817358d2)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct_nocheck
```
```
In block/blk-map.c (ffffffff8173bb54)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_map_user_iov
```
```
In block/blk-cgroup.c (ffffffff81763b61)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-throttle.c (ffffffff81769508)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:tg_may_dispatch
```
```
In block/blk-crypto-fallback.c (ffffffff81784c6b)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
```
In drivers/md/dm-zone.c (ffffffff81d0a35a)
Location: include/linux/bio.h:228
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
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
In kernel/power/swap.c (ffffffff811999e5)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff8142a025)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - mm/page_io.c:__end_swap_bio_read
  - mm/page_io.c:__end_swap_bio_write
```
```
In fs/buffer.c (ffffffff81508521)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - fs/buffer.c:end_bio_bh_io_sync
```
```
In fs/mpage.c (ffffffff8150e365)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_read_end_io
  - fs/mpage.c:mpage_read_end_io
```
```
In fs/direct-io.c (ffffffff815101c5)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/crypto/bio.c (ffffffff8153a5a5)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff8153e617)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff81554551)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/iomap/direct-io.c (ffffffff81559178)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/ext4/page-io.c (ffffffff815d9b65)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff815db015)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/fops.c (ffffffff817679d8)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/bio.c (ffffffff8176b229)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_release_pages
  - block/bio.c:bio_add_folio_nofail
  - block/bio.c:bio_add_page
  - block/bio.c:bio_add_hw_page
  - block/bio.c:__bio_clone
  - block/bio.c:bio_put
```
```
In block/blk-core.c (ffffffff81771def)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct_nocheck
```
```
In block/blk-map.c (ffffffff81778294)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/blk-cgroup.c (ffffffff817a2c0a)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-throttle.c (ffffffff817a86d0)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:tg_may_dispatch
```
```
In block/blk-crypto-fallback.c (ffffffff817c4f35)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
```
In drivers/md/dm-zone.c (ffffffff81d73497)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
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
In kernel/power/swap.c (ffffffff811a8a45)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff81463445)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - mm/page_io.c:__end_swap_bio_read
  - mm/page_io.c:__end_swap_bio_write
```
```
In fs/buffer.c (ffffffff8153d391)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - fs/buffer.c:end_bio_bh_io_sync
```
```
In fs/mpage.c (ffffffff81542e10)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - fs/mpage.c:bio_first_folio
```
```
In fs/direct-io.c (ffffffff81544675)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/crypto/bio.c (ffffffff8156f050)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - fs/crypto/bio.c:bio_first_folio
```
```
In fs/verity/verify.c (ffffffff81573c78)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8158a71e)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/iomap/direct-io.c (ffffffff8158f8c0)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/ext4/page-io.c (ffffffff816124f0)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81613aa4)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/fops.c (ffffffff817a9638)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - block/fops.c:blkdev_bio_end_io_async
  - block/fops.c:blkdev_bio_end_io
  - block/fops.c:__blkdev_direct_IO_simple
```
```
In block/bio.c (ffffffff817ad6b9)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:__bio_release_pages
  - block/bio.c:bio_add_folio_nofail
  - block/bio.c:bio_add_hw_page
  - block/bio.c:__bio_clone
  - block/bio.c:bio_put
  - block/bio.c:bio_first_folio
```
```
In block/blk-core.c (ffffffff817b412c)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct_nocheck
```
```
In block/blk-map.c (ffffffff817ba674)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_map_user_iov
```
```
In block/blk-cgroup.c (ffffffff817e674a)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-throttle.c (ffffffff817ec43d)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:tg_may_dispatch
```
```
In block/blk-crypto-fallback.c (ffffffff81809c25)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
```
In drivers/md/dm-zone.c (ffffffff81e2a570)
Location: include/linux/bio.h:230
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_endio
  - drivers/md/dm-zone.c:dm_zone_map_bio
  - drivers/md/dm-zone.c:dm_zone_map_bio
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
In mm/page_io.c (ffff80001032008c)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/buffer.c (ffff8000103d9af0)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - fs/buffer.c:end_bio_bh_io_sync
```
```
In fs/verity/verify.c (ffff800010413894)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In block/bio.c (ffff8000105dc4ac)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_try_merge_page
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffff8000105e37ac)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-map.c (ffff8000105e9540)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:__blk_rq_unmap_user
```
```
In block/blk-throttle.c (ffff800010612568)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
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
In kernel/power/swap.c (c03c0a28)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (c05388d4)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/buffer.c (c05b1534)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - fs/buffer.c:end_bio_bh_io_sync
```
```
In fs/verity/verify.c (c05dfb38)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In block/bio.c (c078991c)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_try_merge_page
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (c0790a88)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-map.c (c07959e4)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:__blk_rq_unmap_user
```
```
In block/blk-throttle.c (c07bd050)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
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
In mm/page_io.c (c0000000003f4f18)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/buffer.c (c0000000004dc7f0)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - fs/buffer.c:end_bio_bh_io_sync
```
```
In fs/verity/verify.c (c00000000052185c)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In block/bio.c (c00000000076d4f8)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_try_merge_page
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (c000000000777170)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-map.c (c00000000077e160)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:__blk_rq_unmap_user
```
```
In block/blk-throttle.c (c0000000007b0988)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
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
In mm/page_io.c (ffffffe000221798)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/buffer.c (ffffffe00029122e)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - fs/buffer.c:end_bio_bh_io_sync
```
```
In fs/verity/verify.c (ffffffe0002bb28a)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In block/bio.c (ffffffe00041f88c)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_try_merge_page
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffe000425216)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-map.c (ffffffe000429bc4)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:__blk_rq_unmap_user
```
```
In block/blk-throttle.c (ffffffe000449c2c)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
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
In mm/page_io.c (ffffffff8127dfe5)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/buffer.c (ffffffff81318352)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - fs/buffer.c:end_bio_bh_io_sync
```
```
In fs/verity/verify.c (ffffffff81349d25)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In block/bio.c (ffffffff814d7f2d)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_try_merge_page
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814de7a8)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-map.c (ffffffff814e318e)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:__blk_rq_unmap_user
```
```
In block/blk-throttle.c (ffffffff81506e88)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
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
In kernel/power/swap.c (ffffffff810f6fd5)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff8126fe15)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/buffer.c (ffffffff81308f42)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - fs/buffer.c:end_bio_bh_io_sync
```
```
In fs/verity/verify.c (ffffffff8133aa05)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In block/bio.c (ffffffff814c88dd)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_try_merge_page
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814cf148)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-map.c (ffffffff814d3b0e)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:__blk_rq_unmap_user
```
```
In block/blk-throttle.c (ffffffff814f7348)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
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
In kernel/power/swap.c (ffffffff81103fe5)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff8127bd85)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/buffer.c (ffffffff81315e22)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - fs/buffer.c:end_bio_bh_io_sync
```
```
In fs/verity/verify.c (ffffffff813477f5)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In block/bio.c (ffffffff814d3fbd)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_try_merge_page
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814da838)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-map.c (ffffffff814df21e)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:__blk_rq_unmap_user
```
```
In block/blk-throttle.c (ffffffff81502f18)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
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
In kernel/power/swap.c (ffffffff8110f3d5)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff8128b965)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/buffer.c (ffffffff81327b32)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - fs/buffer.c:end_bio_bh_io_sync
```
```
In fs/verity/verify.c (ffffffff8135aaf5)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In block/bio.c (ffffffff814ecb4d)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_endio
  - block/bio.c:bio_endio
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_dirty_fn
  - block/bio.c:bio_unmap_user
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_uncopy_user
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_try_merge_page
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814f3538)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-map.c (ffffffff814f808e)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:__blk_rq_unmap_user
```
```
In block/blk-throttle.c (ffffffff8151c3a8)
Location: include/linux/bio.h:232
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
```
</details>
</li>
</ul>

## Differences
