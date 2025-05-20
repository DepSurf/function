# Function: <code>mapping_shrinkable</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f53e7)
Location: include/linux/pagemap.h:161
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_remove_folio
```
```
In mm/truncate.c (ffffffff813077c6)
Location: include/linux/pagemap.h:161
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:clear_shadow_entry
```
```
In mm/vmscan.c (ffffffff8130cd35)
Location: include/linux/pagemap.h:161
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/workingset.c (ffffffff81335cde)
Location: include/linux/pagemap.h:161
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/inode.c (ffffffff81417a25)
Location: include/linux/pagemap.h:161
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_add_lru
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
In mm/filemap.c (ffffffff8135f257)
Location: include/linux/pagemap.h:161
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_remove_folio
```
```
In mm/truncate.c (ffffffff81371936)
Location: include/linux/pagemap.h:161
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:clear_shadow_entry
```
```
In mm/vmscan.c (ffffffff813761ea)
Location: include/linux/pagemap.h:161
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/workingset.c (ffffffff813acade)
Location: include/linux/pagemap.h:161
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/inode.c (ffffffff814a31c5)
Location: include/linux/pagemap.h:161
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_add_lru
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
In mm/filemap.c (ffffffff81390376)
Location: include/linux/pagemap.h:165
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_remove_folio
```
```
In mm/truncate.c (ffffffff813a3a43)
Location: include/linux/pagemap.h:165
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:clear_shadow_entry
```
```
In mm/vmscan.c (ffffffff813a6217)
Location: include/linux/pagemap.h:165
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/workingset.c (ffffffff813e0e8c)
Location: include/linux/pagemap.h:165
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/inode.c (ffffffff814d8315)
Location: include/linux/pagemap.h:165
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_add_lru
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
In mm/filemap.c (ffffffff813b9db6)
Location: include/linux/pagemap.h:165
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_remove_folio
```
```
In mm/truncate.c (ffffffff813cd565)
Location: include/linux/pagemap.h:165
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:clear_shadow_entry
```
```
In mm/vmscan.c (ffffffff813cfd84)
Location: include/linux/pagemap.h:165
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/workingset.c (ffffffff8140b75c)
Location: include/linux/pagemap.h:165
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In fs/inode.c (ffffffff8150aaf5)
Location: include/linux/pagemap.h:165
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
  - fs/inode.c:inode_add_lru
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
