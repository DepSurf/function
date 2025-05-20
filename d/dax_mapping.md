# Function: <code>dax_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a1eac)
Location: include/linux/dax.h:63
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:page_cache_tree_insert
```
```
In mm/readahead.c (ffffffff811b167a)
Location: include/linux/dax.h:63
Inline: True
Inline callers:
  - mm/readahead.c:SyS_readahead
```
```
In mm/truncate.c (ffffffff811b40aa)
Location: include/linux/dax.h:63
Inline: True
```
```
In mm/vmscan.c (ffffffff811b7448)
Location: include/linux/dax.h:63
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In fs/block_dev.c (ffffffff8127048c)
Location: include/linux/dax.h:63
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_writepages
```
```
In fs/ext4/inode.c (ffffffff812c94ce)
Location: include/linux/dax.h:63
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
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
In mm/filemap.c (ffffffff811af22b)
Location: include/linux/dax.h:95
Inline: True
Inline callers:
  - mm/filemap.c:page_cache_tree_insert
```
```
In mm/readahead.c (ffffffff811c1cba)
Location: include/linux/dax.h:95
Inline: True
Inline callers:
  - mm/readahead.c:SyS_readahead
```
```
In mm/truncate.c (ffffffff811c49f3)
Location: include/linux/dax.h:95
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff811c7a9e)
Location: include/linux/dax.h:95
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/workingset.c (ffffffff811e4198)
Location: include/linux/dax.h:95
Inline: True
```
```
In fs/block_dev.c (ffffffff81283c5c)
Location: include/linux/dax.h:95
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_writepages
```
```
In fs/ext4/inode.c (ffffffff812df11f)
Location: include/linux/dax.h:95
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
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
In mm/filemap.c (ffffffff811ba075)
Location: include/linux/dax.h:113
Inline: True
Inline callers:
  - mm/filemap.c:file_write_and_wait_range
```
```
In mm/readahead.c (ffffffff811c9f63)
Location: include/linux/dax.h:113
Inline: True
Inline callers:
  - mm/readahead.c:SyS_readahead
```
```
In mm/truncate.c (ffffffff811cce3d)
Location: include/linux/dax.h:113
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff811d01b0)
Location: include/linux/dax.h:113
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/workingset.c (ffffffff811ee3a8)
Location: include/linux/dax.h:113
Inline: True
```
```
In fs/block_dev.c (ffffffff8129135c)
Location: include/linux/dax.h:113
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_writepages
```
```
In fs/ext4/inode.c (ffffffff8130331a)
Location: include/linux/dax.h:113
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
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
In mm/filemap.c (ffffffff811c9a0c)
Location: include/linux/dax.h:119
Inline: True
Inline callers:
  - mm/filemap.c:mapping_needs_writeback
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:page_cache_tree_insert
```
```
In mm/readahead.c (ffffffff811dee33)
Location: include/linux/dax.h:119
Inline: True
Inline callers:
  - mm/readahead.c:SyS_readahead
```
```
In mm/truncate.c (ffffffff811e2040)
Location: include/linux/dax.h:119
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff811e5660)
Location: include/linux/dax.h:119
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/workingset.c (ffffffff812048e1)
Location: include/linux/dax.h:119
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/block_dev.c (ffffffff812b40ac)
Location: include/linux/dax.h:119
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_writepages
```
```
In fs/ext4/inode.c (ffffffff81327d0a)
Location: include/linux/dax.h:119
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
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
In mm/filemap.c (ffffffff811eab69)
Location: include/linux/dax.h:172
Inline: True
Inline callers:
  - mm/filemap.c:mapping_needs_writeback
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
  - mm/filemap.c:page_cache_tree_insert
```
```
In mm/readahead.c (ffffffff81200586)
Location: include/linux/dax.h:172
Inline: True
Inline callers:
  - mm/readahead.c:ksys_readahead
```
```
In mm/truncate.c (ffffffff812037aa)
Location: include/linux/dax.h:172
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff81206c92)
Location: include/linux/dax.h:172
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/workingset.c (ffffffff81225713)
Location: include/linux/dax.h:172
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/dax.c (ffffffff812f9e1b)
Location: include/linux/dax.h:172
Inline: True
Inline callers:
  - fs/dax.c:dax_lock_mapping_entry
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
In mm/filemap.c (ffffffff811fe88b)
Location: include/linux/dax.h:174
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:mapping_needs_writeback
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff8121607a)
Location: include/linux/dax.h:174
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff81219817)
Location: include/linux/dax.h:174
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In fs/dax.c (ffffffff8130e6b3)
Location: include/linux/dax.h:174
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
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
In mm/filemap.c (ffffffff81215b8b)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:mapping_needs_writeback
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff81225a7a)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff812292f6)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In fs/dax.c (ffffffff81334de3)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
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
In mm/filemap.c (ffffffff8122348b)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff812338ca)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff812371c3)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In fs/dax.c (ffffffff813489c3)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
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
In mm/filemap.c (ffffffff81250b1d)
Location: include/linux/dax.h:236
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:page_cache_delete
```
```
In mm/truncate.c (ffffffff81260feb)
Location: include/linux/dax.h:236
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff81264050)
Location: include/linux/dax.h:236
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In fs/dax.c (ffffffff8138dcf3)
Location: include/linux/dax.h:236
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
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
In mm/filemap.c (ffffffff8125ae37)
Location: include/linux/dax.h:241
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:page_cache_delete
```
```
In mm/truncate.c (ffffffff8126b3e9)
Location: include/linux/dax.h:241
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff8126eace)
Location: include/linux/dax.h:241
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In fs/dax.c (ffffffff8139efc5)
Location: include/linux/dax.h:241
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_lock_page
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
In mm/filemap.c (ffffffff8125eb06)
Location: include/linux/dax.h:241
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff81270598)
Location: include/linux/dax.h:241
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff81273bfb)
Location: include/linux/dax.h:241
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In fs/dax.c (ffffffff813a6785)
Location: include/linux/dax.h:241
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_lock_page
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
In mm/filemap.c (ffffffff8129bf26)
Location: include/linux/dax.h:214
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff812ae224)
Location: include/linux/dax.h:214
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff812b2ca8)
Location: include/linux/dax.h:214
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In fs/dax.c (ffffffff813f6227)
Location: include/linux/dax.h:214
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_lock_page
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
In mm/filemap.c (ffffffff812f2363)
Location: include/linux/dax.h:217
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/truncate.c (ffffffff813076d4)
Location: include/linux/dax.h:217
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pagevec
```
```
In mm/vmscan.c (ffffffff8130ce52)
Location: include/linux/dax.h:217
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In fs/dax.c (ffffffff81468580)
Location: include/linux/dax.h:217
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_lock_page
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
In mm/filemap.c (ffffffff8135a973)
Location: include/linux/dax.h:259
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/truncate.c (ffffffff81371842)
Location: include/linux/dax.h:259
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pagevec
```
```
In mm/vmscan.c (ffffffff813762c7)
Location: include/linux/dax.h:259
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In fs/dax.c (ffffffff814f9010)
Location: include/linux/dax.h:259
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_page
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
In mm/filemap.c (ffffffff8138c3a3)
Location: include/linux/dax.h:259
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/truncate.c (ffffffff813a394f)
Location: include/linux/dax.h:259
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_try_invalidate
```
```
In mm/vmscan.c (ffffffff813a62ee)
Location: include/linux/dax.h:259
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In fs/dax.c (ffffffff815305e0)
Location: include/linux/dax.h:259
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_page
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
In mm/filemap.c (ffffffff813b5f1c)
Location: include/linux/dax.h:259
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/truncate.c (ffffffff813cd5ff)
Location: include/linux/dax.h:259
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:mapping_try_invalidate
```
```
In mm/vmscan.c (ffffffff813cfe5b)
Location: include/linux/dax.h:259
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In fs/dax.c (ffffffff815654c0)
Location: include/linux/dax.h:259
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_folio
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
In mm/filemap.c (ffff8000102b0db0)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffff8000102c3e84)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffff8000102c822c)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In fs/dax.c (ffff800010408dc8)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
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
In mm/filemap.c (0)
Location: include/linux/dax.h:237
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/dax.h:237
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/dax.h:237
Inline: True
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
In mm/filemap.c (c000000000366288)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (c00000000037e20c)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (c00000000038351c)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In fs/dax.c (c000000000515110)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
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
In mm/filemap.c (ffffffe0001d66b4)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffe0001e49ba)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffe0001e769a)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In fs/dax.c (ffffffe0002b31ca)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
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
In mm/filemap.c (ffffffff8121badb)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff8122bf1a)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff8122f813)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In fs/dax.c (ffffffff81340fa3)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
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
In mm/filemap.c (ffffffff8120eccb)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff8121effa)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff812228d3)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In fs/dax.c (ffffffff81331983)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
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
In mm/filemap.c (ffffffff8121987b)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff81229cba)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff8122d5b3)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In fs/dax.c (ffffffff8133ea73)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
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
In mm/filemap.c (ffffffff8122896b)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:file_write_and_wait_range
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff812390b5)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/vmscan.c (ffffffff8123c9b3)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In fs/dax.c (ffffffff81351943)
Location: include/linux/dax.h:237
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
```
</details>
</li>
</ul>

## Differences
