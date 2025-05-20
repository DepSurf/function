# Function: <code>dm_put_live_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a02ff)
Location: drivers/md/dm.c:745
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_live_table_for_ioctl
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_pr_register
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_prep_fn
  - drivers/md/dm.c:dm_prep_fn
  - drivers/md/dm.c:dm_request_fn
  - drivers/md/dm.c:dm_mq_queue_rq
  - drivers/md/dm.c:dm_mq_queue_rq
Direct callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
```
**Symbols:**

```
ffffffff816a3130-ffffffff816a3140: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8170356a)
Location: drivers/md/dm.c:579
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_blk_direct_access
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
  - drivers/md/dm-rq.c:dm_old_prep_fn
  - drivers/md/dm-rq.c:dm_old_prep_fn
```
**Symbols:**

```
ffffffff817039a0-ffffffff817039b0: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8173542a)
Location: drivers/md/dm.c:579
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_blk_direct_access
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
  - drivers/md/dm-rq.c:dm_old_request_fn
  - drivers/md/dm-rq.c:dm_old_prep_fn
  - drivers/md/dm-rq.c:dm_old_prep_fn
```
**Symbols:**

```
ffffffff81735860-ffffffff81735870: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174e66a)
Location: drivers/md/dm.c:577
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_flush
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff8174ec60-ffffffff8174ec70: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817c0695)
Location: drivers/md/dm.c:584
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff817c0ea0-ffffffff817c0eb7: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81806f9c)
Location: drivers/md/dm.c:676
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff818095c0-ffffffff818095d7: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81832fcc)
Location: drivers/md/dm.c:731
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff818356d0-ffffffff818356e7: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81876faf)
Location: drivers/md/dm.c:711
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81878530-ffffffff81878558: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a8d3f)
Location: drivers/md/dm.c:711
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff818aa370-ffffffff818aa398: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197875f)
Location: drivers/md/dm.c:724
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff8197a7e0-ffffffff8197a808: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197d5b9)
Location: drivers/md/dm.c:720
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff8197f020-ffffffff8197f048: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff819615b9)
Location: drivers/md/dm.c:725
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_keyslot_evict
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81962e70-ffffffff81962e98: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a08519)
Location: drivers/md/dm.c:605
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
Direct callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_blk_report_zones
  - drivers/md/dm-table.c:dm_keyslot_evict
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81a09ea0-ffffffff81a09ec8: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b70811)
Location: drivers/md/dm.c:690
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
Direct callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_blk_report_zones
  - drivers/md/dm-table.c:dm_keyslot_evict
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81b73330-ffffffff81b73365: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0d851)
Location: drivers/md/dm.c:684
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
Direct callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_blk_report_zones
  - drivers/md/dm-table.c:dm_keyslot_evict
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81d0fe70-ffffffff81d0fea5: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d767ab)
Location: drivers/md/dm.c:691
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
Direct callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_blk_report_zones
  - drivers/md/dm-table.c:dm_keyslot_evict
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81d792f0-ffffffff81d79325: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2d9db)
Location: drivers/md/dm.c:693
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
Direct callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_blk_report_zones
  - drivers/md/dm-table.c:dm_keyslot_evict
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81e30460-ffffffff81e30495: dm_put_live_table (STB_GLOBAL)
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
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afd138)
Location: drivers/md/dm.c:711
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffff800010b00250-ffff800010b002a4: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdecf8)
Location: drivers/md/dm.c:711
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
c0bdfca0-c0bdfd08: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bedcf0)
Location: drivers/md/dm.c:711
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
c000000000bef630-c000000000bef69c: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006ef064)
Location: drivers/md/dm.c:711
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffe0006f07d4-ffffffe0006f0812: dm_put_live_table (STB_GLOBAL)
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
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184ebbf)
Location: drivers/md/dm.c:711
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff818501f0-ffffffff81850218: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818161df)
Location: drivers/md/dm.c:711
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81817800-ffffffff81817828: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189e1ef)
Location: drivers/md/dm.c:711
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff8189f820-ffffffff8189f848: dm_put_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dm_put_live_table(struct mapped_device *md, int srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818ba8af)
Location: drivers/md/dm.c:711
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff818bba80-ffffffff818bbaa8: dm_put_live_table (STB_GLOBAL)
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
