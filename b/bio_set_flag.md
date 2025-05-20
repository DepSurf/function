# Function: <code>bio_set_flag</code>

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
In block/bio.c (ffffffff813b07f3)
Location: include/linux/bio.h:303
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
```
```
In block/blk-core.c (ffffffff813ba25b)
Location: include/linux/bio.h:303
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-map.c (ffffffff813bf547)
Location: include/linux/bio.h:303
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In block/blk-merge.c (ffffffff813c04b8)
Location: include/linux/bio.h:303
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-merge.c:blk_recount_segments
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
In block/bio.c (ffffffff813f4363)
Location: include/linux/bio.h:252
Inline: True
```
```
In block/blk-core.c (ffffffff813fe01b)
Location: include/linux/bio.h:252
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-map.c (ffffffff81403490)
Location: include/linux/bio.h:252
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In block/blk-merge.c (ffffffff81404b6d)
Location: include/linux/bio.h:252
Inline: True
Inline callers:
  - block/blk-merge.c:blk_recount_segments
  - block/blk-merge.c:blk_queue_split
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
In block/bio.c (ffffffff8140dd53)
Location: include/linux/bio.h:249
Inline: True
```
```
In block/blk-core.c (ffffffff81417960)
Location: include/linux/bio.h:249
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
```
```
In block/blk-map.c (ffffffff8141d1ee)
Location: include/linux/bio.h:249
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In block/blk-merge.c (ffffffff8141e2dd)
Location: include/linux/bio.h:249
Inline: True
Inline callers:
  - block/blk-merge.c:blk_recount_segments
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-throttle.c (ffffffff8143cc33)
Location: include/linux/bio.h:249
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
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
In block/bio.c (ffffffff8141dcba)
Location: include/linux/bio.h:265
Inline: True
Inline callers:
  - block/bio.c:bio_split
```
```
In block/blk-core.c (ffffffff814257b6)
Location: include/linux/bio.h:265
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-map.c (ffffffff8142b219)
Location: include/linux/bio.h:265
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In block/blk-merge.c (ffffffff8142bb16)
Location: include/linux/bio.h:265
Inline: True
Inline callers:
  - block/blk-merge.c:blk_recount_segments
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-throttle.c (ffffffff81448416)
Location: include/linux/bio.h:265
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_charge_bio
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
In block/bio.c (ffffffff8144774a)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:__bio_clone_fast
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff81450943)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-merge.c (ffffffff81456d26)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - block/blk-merge.c:blk_recount_segments
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-throttle.c (ffffffff81477f84)
Location: include/linux/bio.h:261
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
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
In block/bio.c (ffffffff8147a84f)
Location: include/linux/bio.h:270
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:__bio_clone_fast
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff81483cfb)
Location: include/linux/bio.h:270
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-merge.c (ffffffff8148a194)
Location: include/linux/bio.h:270
Inline: True
Inline callers:
  - block/blk-merge.c:blk_recount_segments
  - block/blk-merge.c:blk_queue_split
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-throttle.c (ffffffff814ac610)
Location: include/linux/bio.h:270
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
In block/bio.c (ffffffff81498b67)
Location: include/linux/bio.h:224
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:__bio_clone_fast
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff8149f2bb)
Location: include/linux/bio.h:224
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-merge.c (ffffffff814a4a91)
Location: include/linux/bio.h:224
Inline: True
Inline callers:
  - block/blk-merge.c:blk_recount_segments
  - block/blk-merge.c:blk_queue_split
  - block/blk-merge.c:blk_queue_split
```
```
In block/blk-mq.c (ffffffff814aaa64)
Location: include/linux/bio.h:224
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/blk-throttle.c (ffffffff814c69c4)
Location: include/linux/bio.h:224
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
In block/bio.c (ffffffff814c6b44)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_clone_fast
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814cd37c)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-merge.c (ffffffff814d282b)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-mq.c (ffffffff814d84fc)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/blk-throttle.c (ffffffff814f520e)
Location: include/linux/bio.h:237
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
In block/bio.c (ffffffff814df954)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_clone_fast
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814e66bc)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-merge.c (ffffffff814ebbb4)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-mq.c (ffffffff814f18ac)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/blk-throttle.c (ffffffff8150e8e2)
Location: include/linux/bio.h:237
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
In block/bio.c (ffffffff8153f3ea)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_clone_fast
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff8154397d)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blkcg_bio_issue_check
```
```
In block/blk-map.c (ffffffff8154a937)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
  - block/blk-map.c:bio_copy_user_iov
```
```
In block/blk-mq.c (ffffffff81550fbc)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/blk-throttle.c (ffffffff8156febd)
Location: include/linux/bio.h:245
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
In block/bio.c (ffffffff8155bbea)
Location: include/linux/bio.h:256
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_clone_fast
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff8156085c)
Location: include/linux/bio.h:256
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:__submit_bio_noacct_mq
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-mq.c (ffffffff8156ee6a)
Location: include/linux/bio.h:256
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/blk-cgroup.c (ffffffff81586e8d)
Location: include/linux/bio.h:256
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-throttle.c (ffffffff8158acf8)
Location: include/linux/bio.h:256
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
```
```
In drivers/md/dm.c (ffffffff8197e3cc)
Location: include/linux/bio.h:256
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
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
In block/bio.c (ffffffff8156427a)
Location: include/linux/bio.h:259
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_clone_fast
  - block/bio.c:__bio_clone_fast
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff81568ec2)
Location: include/linux/bio.h:259
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-mq.c (ffffffff81576a43)
Location: include/linux/bio.h:259
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/blk-cgroup.c (ffffffff8158dcd3)
Location: include/linux/bio.h:259
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-throttle.c (ffffffff815917e2)
Location: include/linux/bio.h:259
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
```
```
In block/blk-crypto-fallback.c (ffffffff815a655e)
Location: include/linux/bio.h:259
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
```
In drivers/md/dm.c (ffffffff8196217f)
Location: include/linux/bio.h:259
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
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
In block/bio.c (ffffffff815c856a)
Location: include/linux/bio.h:258
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_clone_fast
  - block/bio.c:__bio_clone_fast
  - block/bio.c:__bio_clone_fast
  - block/bio.c:bio_chain
```
```
In block/blk-core.c (ffffffff815cd169)
Location: include/linux/bio.h:258
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-mq.c (ffffffff815db6f3)
Location: include/linux/bio.h:258
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/blk-cgroup.c (ffffffff815f375f)
Location: include/linux/bio.h:258
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-throttle.c (ffffffff815f8a26)
Location: include/linux/bio.h:258
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
```
```
In block/blk-crypto-fallback.c (ffffffff8160f077)
Location: include/linux/bio.h:258
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
```
In drivers/md/dm-zone.c (ffffffff81a05f62)
Location: include/linux/bio.h:258
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/md/dm.c (ffffffff81a0b2bf)
Location: include/linux/bio.h:258
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
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
In block/bio.c (ffffffff8167346b)
Location: include/linux/bio.h:233
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_iov_bvec_set
  - block/bio.c:bio_iov_bvec_set
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_clone
  - block/bio.c:__bio_clone
  - block/bio.c:__bio_clone
  - block/bio.c:blk_next_bio
```
```
In block/blk-core.c (ffffffff816796e8)
Location: include/linux/bio.h:233
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:__bio_queue_enter
```
```
In block/blk-merge.c (ffffffff8168038c)
Location: include/linux/bio.h:233
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
```
```
In block/blk-mq.c (ffffffff81689846)
Location: include/linux/bio.h:233
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_update_request
```
```
In block/blk-cgroup.c (ffffffff816a4d9a)
Location: include/linux/bio.h:233
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-throttle.c (ffffffff816aab7e)
Location: include/linux/bio.h:233
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
```
```
In block/blk-crypto-fallback.c (ffffffff816c38b4)
Location: include/linux/bio.h:233
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
```
In drivers/md/md.c (ffffffff81b5c027)
Location: include/linux/bio.h:233
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm-zone.c (ffffffff81b6dc92)
Location: include/linux/bio.h:233
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/md/dm.c (ffffffff81b72e46)
Location: include/linux/bio.h:233
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
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
In block/bio.c (ffffffff8172effb)
Location: include/linux/bio.h:233
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_iov_bvec_set
  - block/bio.c:bio_iov_bvec_set
  - block/bio.c:__bio_clone
  - block/bio.c:__bio_clone
  - block/bio.c:blk_next_bio
```
```
In block/blk-core.c (ffffffff81735c5e)
Location: include/linux/bio.h:233
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct_nocheck
  - block/blk-core.c:__bio_queue_enter
```
```
In block/blk-merge.c (ffffffff8173d714)
Location: include/linux/bio.h:233
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
```
```
In block/blk-mq.c (ffffffff81747dcf)
Location: include/linux/bio.h:233
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_update_request
```
```
In block/blk-cgroup.c (ffffffff81763bba)
Location: include/linux/bio.h:233
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-throttle.c (ffffffff81769577)
Location: include/linux/bio.h:233
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
```
In block/blk-crypto-fallback.c (ffffffff81784d71)
Location: include/linux/bio.h:233
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
```
In drivers/md/md.c (ffffffff81cf6017)
Location: include/linux/bio.h:233
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm-zone.c (ffffffff81d0a17d)
Location: include/linux/bio.h:233
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/md/dm.c (ffffffff81d0fc06)
Location: include/linux/bio.h:233
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_split_and_process_bio
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
In fs/direct-io.c (ffffffff81510a5b)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - fs/direct-io.c:dio_send_cur_page
  - fs/direct-io.c:dio_send_cur_page
```
```
In block/bio.c (ffffffff8176b22f)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_bvec_set
  - block/bio.c:__bio_clone
  - block/bio.c:__bio_clone
  - block/bio.c:blk_next_bio
```
```
In block/blk-core.c (ffffffff81772281)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct_nocheck
  - block/blk-core.c:__bio_queue_enter
```
```
In block/blk-map.c (ffffffff817787f1)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
```
```
In block/blk-merge.c (ffffffff81779c94)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
```
```
In block/blk-mq.c (ffffffff817843d0)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_update_request
```
```
In block/blk-cgroup.c (ffffffff817a2c14)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-throttle.c (ffffffff817a8731)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
```
In block/blk-crypto-fallback.c (ffffffff817c5039)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
```
In drivers/md/md.c (ffffffff81d5fd7c)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm-zone.c (ffffffff81d732b6)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/md/dm.c (ffffffff81d79083)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_split_and_process_bio
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
In fs/direct-io.c (ffffffff81544efb)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - fs/direct-io.c:dio_send_cur_page
  - fs/direct-io.c:dio_send_cur_page
```
```
In block/bio.c (ffffffff817ad6bf)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_bvec_set
  - block/bio.c:__bio_clone
  - block/bio.c:__bio_clone
  - block/bio.c:blk_next_bio
```
```
In block/blk-core.c (ffffffff817b4587)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct_nocheck
  - block/blk-core.c:__bio_queue_enter
```
```
In block/blk-map.c (ffffffff817ba8d6)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
```
```
In block/blk-merge.c (ffffffff817bc067)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_discard_merge
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
```
```
In block/blk-mq.c (ffffffff817c66d3)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_update_request
```
```
In block/blk-cgroup.c (ffffffff817e6754)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_bio_start
```
```
In block/blk-throttle.c (ffffffff817ec49e)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
```
In block/blk-crypto-fallback.c (ffffffff81809d29)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
```
In drivers/md/md.c (ffffffff81e17358)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/dm-zone.c (ffffffff81e2a3f9)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio
```
```
In drivers/md/dm.c (ffffffff81e301f6)
Location: include/linux/bio.h:235
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_split_and_process_bio
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
In block/bio.c (ffff8000105dc4b4)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_clone_fast
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffff8000105e3e94)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-merge.c (ffff8000105ea55c)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-mq.c (ffff8000105f0f68)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/blk-throttle.c (ffff800010612594)
Location: include/linux/bio.h:237
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
In block/bio.c (c0789924)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_clone_fast
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (c0790f10)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-merge.c (c07969d8)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-mq.c (c079cfe0)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/blk-throttle.c (c07bd084)
Location: include/linux/bio.h:237
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
In block/bio.c (c00000000076d504)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_clone_fast
  - block/bio.c:__bio_clone_fast
  - block/bio.c:bio_chain
```
```
In block/blk-core.c (c000000000777a30)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-merge.c (c00000000077f6c4)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-mq.c (c000000000787c44)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/blk-throttle.c (c0000000007b09c8)
Location: include/linux/bio.h:237
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
In block/bio.c (ffffffe00041f896)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_clone_fast
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffe000425736)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-merge.c (ffffffe00042a8f2)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-mq.c (ffffffe00042fc18)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/blk-throttle.c (ffffffe000449c52)
Location: include/linux/bio.h:237
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
In block/bio.c (ffffffff814d7f34)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_clone_fast
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814dec9c)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-merge.c (ffffffff814e4194)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-mq.c (ffffffff814e9e8c)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/blk-throttle.c (ffffffff81506ec2)
Location: include/linux/bio.h:237
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
In block/bio.c (ffffffff814c88e4)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_clone_fast
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814cf63c)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-merge.c (ffffffff814d4a74)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-mq.c (ffffffff814da3ec)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/blk-throttle.c (ffffffff814f7382)
Location: include/linux/bio.h:237
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
In block/bio.c (ffffffff814d3fc4)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_clone_fast
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814dad2c)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-merge.c (ffffffff814e0224)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-mq.c (ffffffff814e5f1c)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/blk-throttle.c (ffffffff81502f52)
Location: include/linux/bio.h:237
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
In block/bio.c (ffffffff814ecb54)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/bio.c:bio_split
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_copy_user_iov
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:__bio_add_page
  - block/bio.c:__bio_clone_fast
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814f3ab7)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:generic_make_request_checks
```
```
In block/blk-merge.c (ffffffff814f9084)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-mq.c (ffffffff814fee8c)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/blk-throttle.c (ffffffff8151c3e4)
Location: include/linux/bio.h:237
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_charge_bio
```
</details>
</li>
</ul>

## Differences
