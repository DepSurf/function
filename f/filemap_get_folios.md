# Function: <code>filemap_get_folios</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
unsigned int filemap_get_folios(struct address_space *mapping, long unsigned int *start, long unsigned int end, struct folio_batch *fbatch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2163
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unlock_mapping
  - fs/buffer.c:clean_bdev_aliases
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff82062072-ffffffff82062098: filemap_get_folios.cold (STB_LOCAL)
ffffffff8135b810-ffffffff8135ba24: filemap_get_folios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
unsigned int filemap_get_folios(struct address_space *mapping, long unsigned int *start, long unsigned int end, struct folio_batch *fbatch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2134
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unlock_mapping
  - fs/buffer.c:clean_bdev_aliases
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff820e187a-ffffffff820e18a0: filemap_get_folios.cold (STB_LOCAL)
ffffffff8138d670-ffffffff8138d88e: filemap_get_folios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int filemap_get_folios(struct address_space *mapping, long unsigned int *start, long unsigned int end, struct folio_batch *fbatch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b74e0)
Location: mm/filemap.c:2113
Inline: False
Direct callers:
  - mm/shmem.c:shmem_unlock_mapping
  - fs/buffer.c:clean_bdev_aliases
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
**Symbols:**

```
ffffffff813b74e0-ffffffff813b7507: filemap_get_folios (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
