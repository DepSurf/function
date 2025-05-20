# Function: <code>__pagevec_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119e140)
Location: mm/swap.c:984
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/mlock.c:__munlock_pagevec
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff8119e140-ffffffff8119e178: __pagevec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b3a00)
Location: mm/swap.c:810
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/mlock.c:__munlock_pagevec
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff811b3a00-ffffffff811b3a38: __pagevec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811c4090)
Location: mm/swap.c:810
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/mlock.c:__munlock_pagevec
  - fs/buffer.c:clean_bdev_aliases
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff811c4090-ffffffff811c40c8: __pagevec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811cc480)
Location: mm/swap.c:823
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/filemap.c:filemap_range_has_page
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/mlock.c:__munlock_pagevec
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:clean_bdev_aliases
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff811cc480-ffffffff811cc4b8: __pagevec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811e1470)
Location: mm/swap.c:834
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/mlock.c:__munlock_pagevec
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:page_cache_seek_hole_data
  - fs/buffer.c:clean_bdev_aliases
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff811e1470-ffffffff811e14a8: __pagevec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81202bd0)
Location: mm/swap.c:806
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/mlock.c:__munlock_pagevec
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff81202bd0-ffffffff81202c07: __pagevec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81215550)
Location: mm/swap.c:808
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/mlock.c:__munlock_pagevec
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/iomap.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff81215550-ffffffff81215587: __pagevec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81224f70)
Location: mm/swap.c:814
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/mlock.c:__munlock_pagevec
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff81224f70-ffffffff81224fa7: __pagevec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81232d40)
Location: mm/swap.c:856
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/mlock.c:__munlock_pagevec
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff81232d40-ffffffff81232d77: __pagevec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81260270)
Location: mm/swap.c:925
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/mlock.c:__munlock_pagevec
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff81260270-ffffffff812602c5: __pagevec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126acb0)
Location: mm/swap.c:948
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff8126acb0-ffffffff8126ad05: __pagevec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126fe90)
Location: mm/swap.c:986
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - fs/buffer.c:clean_bdev_aliases
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff8126fe90-ffffffff8126fee5: __pagevec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:977
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - fs/buffer.c:clean_bdev_aliases
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff81cba5a3-ffffffff81cba5b8: __pagevec_release.cold (STB_LOCAL)
ffffffff812ad270-ffffffff812ad2d4: __pagevec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:994
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - fs/buffer.c:clean_bdev_aliases
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff81e6bde6-ffffffff81e6bdfb: __pagevec_release.cold (STB_LOCAL)
ffffffff81307300-ffffffff8130736e: __pagevec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:1090
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - fs/buffer.c:clean_bdev_aliases
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff82062722-ffffffff82062737: __pagevec_release.cold (STB_LOCAL)
ffffffff81370d20-ffffffff81370d8e: __pagevec_release (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c30b8)
Location: mm/swap.c:856
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/mlock.c:__munlock_pagevec
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffff8000102c30b8-ffff8000102c311c: __pagevec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c04ede44)
Location: mm/swap.c:856
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/mlock.c:__munlock_pagevec
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
c04ede44-c04edea0: __pagevec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c00000000037cf40)
Location: mm/swap.c:856
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/mlock.c:__munlock_pagevec
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
c00000000037cf40-c00000000037cfd8: __pagevec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffe0001e4034)
Location: mm/swap.c:856
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/mlock.c:__munlock_pagevec
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffe0001e4034-ffffffe0001e4082: __pagevec_release (STB_GLOBAL)
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
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8122b390)
Location: mm/swap.c:856
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/mlock.c:__munlock_pagevec
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff8122b390-ffffffff8122b3c7: __pagevec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121e480)
Location: mm/swap.c:856
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/mlock.c:__munlock_pagevec
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff8121e480-ffffffff8121e4b7: __pagevec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81229130)
Location: mm/swap.c:856
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/mlock.c:__munlock_pagevec
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff81229130-ffffffff81229167: __pagevec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __pagevec_release(struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812387a0)
Location: mm/swap.c:856
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawait_range
  - mm/page-writeback.c:write_cache_pages
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unlock_mapping
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - fs/buffer.c:clean_bdev_aliases
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/iomap/seek.c:page_cache_seek_hole_data
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff812387a0-ffffffff812387d0: __pagevec_release (STB_GLOBAL)
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
