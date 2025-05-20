# Function: <code>inode_to_wb</code>

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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:354
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:354
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:354
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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:355
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:355
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:355
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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:355
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:355
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:355
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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:330
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:330
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:330
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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:335
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:335
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:335
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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:336
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:336
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:336
Inline: True
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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:336
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:336
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:336
Inline: True
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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:337
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:337
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:337
Inline: True
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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:343
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:343
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:343
Inline: True
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
In mm/filemap.c (ffffffff8124f6e6)
Location: include/linux/backing-dev.h:339
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8125a08b)
Location: include/linux/backing-dev.h:339
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffff8134c46e)
Location: include/linux/backing-dev.h:339
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
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
In mm/filemap.c (ffffffff8125999d)
Location: include/linux/backing-dev.h:280
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812657ca)
Location: include/linux/backing-dev.h:280
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffff81359463)
Location: include/linux/backing-dev.h:280
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
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
In mm/filemap.c (ffffffff8125db2d)
Location: include/linux/backing-dev.h:280
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8126a2cc)
Location: include/linux/backing-dev.h:280
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffff8135ffe1)
Location: include/linux/backing-dev.h:280
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
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
In mm/filemap.c (ffffffff81299dbd)
Location: include/linux/backing-dev.h:280
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812a6f5f)
Location: include/linux/backing-dev.h:280
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:account_page_dirtied
```
```
In fs/fs-writeback.c (ffffffff813ae95a)
Location: include/linux/backing-dev.h:280
Inline: True
Inline callers:
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
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
In mm/filemap.c (ffffffff812f1d80)
Location: include/linux/backing-dev.h:258
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff812ff157)
Location: include/linux/backing-dev.h:258
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/huge_memory.c (ffffffff813ba8e9)
Location: include/linux/backing-dev.h:258
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In fs/fs-writeback.c (ffffffff8143304f)
Location: include/linux/backing-dev.h:258
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_prepare_wbs_switch
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
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
In mm/filemap.c (ffffffff81359932)
Location: include/linux/backing-dev.h:250
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff81369879)
Location: include/linux/backing-dev.h:250
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/huge_memory.c (ffffffff8143ce7e)
Location: include/linux/backing-dev.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In fs/fs-writeback.c (ffffffff814c103f)
Location: include/linux/backing-dev.h:250
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_prepare_wbs_switch
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
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
In mm/filemap.c (ffffffff8138b282)
Location: include/linux/backing-dev.h:250
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff8139ba16)
Location: include/linux/backing-dev.h:250
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/huge_memory.c (ffffffff814724cc)
Location: include/linux/backing-dev.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In fs/fs-writeback.c (ffffffff814f62ef)
Location: include/linux/backing-dev.h:250
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_prepare_wbs_switch
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
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
In mm/filemap.c (ffffffff813b4db2)
Location: include/linux/backing-dev.h:249
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff813c444c)
Location: include/linux/backing-dev.h:249
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_account_dirtied
```
```
In mm/huge_memory.c (ffffffff814a27ce)
Location: include/linux/backing-dev.h:249
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In fs/fs-writeback.c (ffffffff8152aa2f)
Location: include/linux/backing-dev.h:249
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_prepare_wbs_switch
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:343
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:343
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:343
Inline: True
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
In mm/filemap.c (c04da9d0)
Location: include/linux/backing-dev.h:343
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (c04e70a4)
Location: include/linux/backing-dev.h:343
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In fs/fs-writeback.c (c05a26a0)
Location: include/linux/backing-dev.h:343
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
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
In mm/filemap.c (c000000000362334)
Location: include/linux/backing-dev.h:343
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (c0000000003739f0)
Location: include/linux/backing-dev.h:343
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In fs/fs-writeback.c (c0000000004c64b4)
Location: include/linux/backing-dev.h:343
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
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
In mm/filemap.c (ffffffe0001d435c)
Location: include/linux/backing-dev.h:343
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffe0001de2a2)
Location: include/linux/backing-dev.h:343
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In fs/fs-writeback.c (ffffffe000286bb4)
Location: include/linux/backing-dev.h:343
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:343
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:343
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:343
Inline: True
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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:343
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:343
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:343
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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:343
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:343
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:343
Inline: True
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
In mm/filemap.c (0)
Location: include/linux/backing-dev.h:343
Inline: True
```
```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:343
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/backing-dev.h:343
Inline: True
```
</details>
</li>
</ul>

## Differences
