# Function: <code>dm_get_live_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a02d0)
Location: drivers/md/dm.c:738
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_live_table_for_ioctl
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_prep_fn
  - drivers/md/dm.c:dm_request_fn
  - drivers/md/dm.c:dm_mq_queue_rq
Direct callers:
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-ioctl.c:dm_get_inactive_table
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:dev_rename
```
**Symbols:**

```
ffffffff816a3100-ffffffff816a3127: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817034f0)
Location: drivers/md/dm.c:572
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_blk_direct_access
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_get_inactive_table
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
  - drivers/md/dm-rq.c:dm_old_prep_fn
```
**Symbols:**

```
ffffffff81703970-ffffffff81703997: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817353b0)
Location: drivers/md/dm.c:572
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_blk_direct_access
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_get_inactive_table
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
  - drivers/md/dm-rq.c:dm_old_prep_fn
```
**Symbols:**

```
ffffffff81735830-ffffffff81735857: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174e5ec)
Location: drivers/md/dm.c:570
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_get_inactive_table
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff8174ec30-ffffffff8174ec57: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817c05f6)
Location: drivers/md/dm.c:577
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_get_inactive_table
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff817c0e70-ffffffff817c0e9b: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81808b7d)
Location: drivers/md/dm.c:669
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_get_inactive_table
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff81809590-ffffffff818095bb: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81834c4d)
Location: drivers/md/dm.c:724
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_get_inactive_table
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff818356a0-ffffffff818356cb: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818774bd)
Location: drivers/md/dm.c:704
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_get_inactive_table
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81878500-ffffffff8187852b: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a924d)
Location: drivers/md/dm.c:704
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_get_inactive_table
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff818aa340-ffffffff818aa36b: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197987d)
Location: drivers/md/dm.c:717
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff8197a7b0-ffffffff8197a7db: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197e67e)
Location: drivers/md/dm.c:713
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff8197eff0-ffffffff8197f01b: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff819624ce)
Location: drivers/md/dm.c:718
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_keyslot_evict
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81962e40-ffffffff81962e6b: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a09685)
Location: drivers/md/dm.c:598
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
Direct callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_blk_report_zones
  - drivers/md/dm-table.c:dm_keyslot_evict
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81a09e70-ffffffff81a09e9b: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b71708)
Location: drivers/md/dm.c:682
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
Direct callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_blk_report_zones
  - drivers/md/dm-table.c:dm_keyslot_evict
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81b732f0-ffffffff81b73323: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0e558)
Location: drivers/md/dm.c:676
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
Direct callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_blk_report_zones
  - drivers/md/dm-table.c:dm_keyslot_evict
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81d0fe20-ffffffff81d0fe53: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d77b58)
Location: drivers/md/dm.c:683
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
Direct callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_blk_report_zones
  - drivers/md/dm-table.c:dm_keyslot_evict
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81d792a0-ffffffff81d792d3: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2ed88)
Location: drivers/md/dm.c:685
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_prepare_ioctl
Direct callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_blk_report_zones
  - drivers/md/dm-table.c:dm_keyslot_evict
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_hash_rename
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81e30410-ffffffff81e30443: dm_get_live_table (STB_GLOBAL)
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
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010aff680)
Location: drivers/md/dm.c:704
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_get_inactive_table
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffff800010b00218-ffff800010b00250: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdf638)
Location: drivers/md/dm.c:704
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_get_live_or_inactive_table
  - drivers/md/dm-ioctl.c:dm_get_inactive_table
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
c0bdfc70-c0bdfca0: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bee498)
Location: drivers/md/dm.c:704
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_get_inactive_table
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
c000000000bef5d0-c000000000bef628: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006ef612)
Location: drivers/md/dm.c:704
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_get_inactive_table
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffe0006f079c-ffffffe0006f07d4: dm_get_live_table (STB_GLOBAL)
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
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184f0cd)
Location: drivers/md/dm.c:704
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_get_inactive_table
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff818501c0-ffffffff818501eb: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818166ed)
Location: drivers/md/dm.c:704
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_get_inactive_table
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff818177d0-ffffffff818177fb: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189e6fd)
Location: drivers/md/dm.c:704
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_get_inactive_table
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff8189f7f0-ffffffff8189f81b: dm_get_live_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dm_table *dm_get_live_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818bb02d)
Location: drivers/md/dm.c:704
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_dax_supported
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_prepare_ioctl
  - drivers/md/dm.c:dm_blk_report_zones
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:dev_rename
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_get_inactive_table
  - drivers/md/dm-ioctl.c:__hash_remove
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff818bba50-ffffffff818bba7b: dm_get_live_table (STB_GLOBAL)
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
