# Function: <code>pagevec_add</code>

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
In mm/swap.c (ffffffff8119dc98)
Location: include/linux/pagevec.h:60
Inline: True
Inline callers:
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:deactivate_file_page
```
```
In mm/mlock.c (ffffffff811c2e45)
Location: include/linux/pagevec.h:60
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
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
In mm/swap.c (ffffffff811b3b66)
Location: include/linux/pagevec.h:60
Inline: True
Inline callers:
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/mlock.c (ffffffff811df2c3)
Location: include/linux/pagevec.h:60
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffff811c41f6)
Location: include/linux/pagevec.h:60
Inline: True
Inline callers:
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/mlock.c (ffffffff811ef0d7)
Location: include/linux/pagevec.h:60
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffff811cc5e8)
Location: include/linux/pagevec.h:60
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/mlock.c (ffffffff811fa00d)
Location: include/linux/pagevec.h:60
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffff811e1615)
Location: include/linux/pagevec.h:77
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff811e2712)
Location: include/linux/pagevec.h:77
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/mlock.c (ffffffff812124a6)
Location: include/linux/pagevec.h:77
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffff81202d5a)
Location: include/linux/pagevec.h:77
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff81203d40)
Location: include/linux/pagevec.h:77
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/mlock.c (ffffffff812332bb)
Location: include/linux/pagevec.h:77
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffff812156ea)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff81216700)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/mlock.c (ffffffff81246a8c)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffff812250e9)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff812260d1)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/mlock.c (ffffffff81258c8d)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffff81232f69)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff81233f31)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/mlock.c (ffffffff8126715d)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffff81260509)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff81261501)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/mlock.c (ffffffff81297263)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__putback_lru_fast_prepare
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
In mm/swap.c (ffffffff8126a639)
Location: include/linux/pagevec.h:76
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff8126b901)
Location: include/linux/pagevec.h:76
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/mlock.c (ffffffff812a2215)
Location: include/linux/pagevec.h:76
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__putback_lru_fast_prepare
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
In mm/filemap.c (ffffffff8126224a)
Location: include/linux/pagevec.h:72
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_lock_entries
```
```
In mm/swap.c (ffffffff8126f76f)
Location: include/linux/pagevec.h:72
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_cache_add
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/mlock.c (ffffffff812a7aa5)
Location: include/linux/pagevec.h:72
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
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
In mm/filemap.c (ffffffff8129e8af)
Location: include/linux/pagevec.h:72
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_lock_entries
```
```
In mm/swap.c (ffffffff812ac8bf)
Location: include/linux/pagevec.h:72
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_cache_add
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/mlock.c (ffffffff812e90c5)
Location: include/linux/pagevec.h:72
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffff81306c06)
Location: include/linux/pagevec.h:73
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_rotate_reclaimable
```
```
In mm/mlock.c (ffffffff8134c465)
Location: include/linux/pagevec.h:73
Inline: True
Inline callers:
  - mm/mlock.c:munlock_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff813c4ff5)
Location: include/linux/pagevec.h:62
Inline: True
Inline callers:
  - mm/mlock.c:munlock_page
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c3000)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffff8000102c4674)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/mlock.c (ffff8000102fe280)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (c04ee140)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (c04eef14)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/mlock.c (c051d39c)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (c00000000037d2e4)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (c00000000037eb68)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/mlock.c (c0000000003c9b84)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffe0001e42c2)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffe0001e4ef0)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/mlock.c (ffffffe00020c830)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffff8122b5b9)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff8122c581)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/mlock.c (ffffffff8125f7ad)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffff8121e6a9)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff8121f661)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/mlock.c (ffffffff81251bcd)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffff81229359)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff8122a321)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/mlock.c (ffffffff8125d54d)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
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
In mm/swap.c (ffffffff81238708)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/truncate.c (ffffffff81239711)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/mlock.c (ffffffff8126cf31)
Location: include/linux/pagevec.h:79
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_pagevec
```
</details>
</li>
</ul>

## Differences
