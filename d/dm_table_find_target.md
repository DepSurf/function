# Function: <code>dm_table_find_target</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff816a68b0)
Location: drivers/md/dm-table.c:1178
Inline: False
Direct callers:
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dm_request_fn
  - drivers/md/dm.c:dm_mq_queue_rq
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff816a68b0-ffffffff816a6925: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81706b30)
Location: drivers/md/dm-table.c:1280
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:dm_blk_direct_access
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff81706b30-ffffffff81706ba5: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81738a00)
Location: drivers/md/dm-table.c:1281
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:dm_blk_direct_access
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff81738a00-ffffffff81738a75: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81751f60)
Location: drivers/md/dm-table.c:1332
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff81751f60-ffffffff81751fdc: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817c4140)
Location: drivers/md/dm-table.c:1334
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_changing_extent_only
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff817c4140-ffffffff817c41bc: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8180cc30)
Location: drivers/md/dm-table.c:1372
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff8180cc30-ffffffff8180ccac: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81838b60)
Location: drivers/md/dm-table.c:1352
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81838b60-ffffffff81838bdc: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8187b6f0)
Location: drivers/md/dm-table.c:1365
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff8187b6f0-ffffffff8187b79b: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818ad4e0)
Location: drivers/md/dm-table.c:1363
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff818ad4e0-ffffffff818ad578: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8197d7b0)
Location: drivers/md/dm-table.c:1339
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff8197d7b0-ffffffff8197d84d: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81981d30)
Location: drivers/md/dm-table.c:1278
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81981d30-ffffffff81981dcd: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff819660f0)
Location: drivers/md/dm-table.c:1474
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff819660f0-ffffffff8196618d: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81a0e2e0)
Location: drivers/md/dm-table.c:1469
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_copy_to_iter
  - drivers/md/dm.c:dm_dax_copy_from_iter
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81a0e2e0-ffffffff81a0e39e: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81b76a30)
Location: drivers/md/dm-table.c:1461
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81b76a30-ffffffff81b76b00: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d13dd0)
Location: drivers/md/dm-table.c:1470
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81d13dd0-ffffffff81d13ea0: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d7cf00)
Location: drivers/md/dm-table.c:1454
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81d7cf00-ffffffff81d7cfd0: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81e343e0)
Location: drivers/md/dm-table.c:1476
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_dax_recovery_write
  - drivers/md/dm.c:dm_dax_zero_page_range
  - drivers/md/dm.c:dm_dax_direct_access
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81e343e0-ffffffff81e344b0: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffff800010b04080)
Location: drivers/md/dm-table.c:1363
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffff800010b04080-ffff800010b04164: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c0be30b0)
Location: drivers/md/dm-table.c:1363
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
c0be30b0-c0be3174: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c000000000bf3930)
Location: drivers/md/dm-table.c:1363
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
c000000000bf3930-c000000000bf3a00: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffe0006f33fa)
Location: drivers/md/dm-table.c:1363
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffe0006f33fa-ffffffe0006f34b2: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81853360)
Location: drivers/md/dm-table.c:1363
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81853360-ffffffff818533f8: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8181a970)
Location: drivers/md/dm-table.c:1363
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff8181a970-ffffffff8181aa08: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818a2990)
Location: drivers/md/dm-table.c:1363
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff818a2990-ffffffff818a2a28: dm_table_find_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dm_target *dm_table_find_target(struct dm_table *t, sector_t sector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818bebd0)
Location: drivers/md/dm-table.c:1363
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:dm_dax_get_live_target
  - drivers/md/dm.c:dm_blk_report_zones
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff818bebd0-ffffffff818bec68: dm_table_find_target (STB_GLOBAL)
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
