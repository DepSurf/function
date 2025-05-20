# Function: <code>__page_file_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811d2f40)
Location: mm/swapfile.c:2755
Inline: False
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_readpage
```
**Symbols:**

```
ffffffff811d2f40-ffffffff811d2f59: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811f0dd0)
Location: mm/swapfile.c:2740
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff811f0dd0-ffffffff811f0de9: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81201740)
Location: mm/swapfile.c:2752
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff81201740-ffffffff81201759: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120c6f0)
Location: mm/swapfile.c:3232
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff8120c6f0-ffffffff8120c709: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81226320)
Location: mm/swapfile.c:3485
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff81226320-ffffffff81226339: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81248930)
Location: mm/swapfile.c:3509
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff81248930-ffffffff81248949: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125cf10)
Location: mm/swapfile.c:3487
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff8125cf10-ffffffff8125cf29: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812780c0)
Location: mm/swapfile.c:3491
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff812780c0-ffffffff812780d9: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81287bb0)
Location: mm/swapfile.c:3499
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff81287bb0-ffffffff81287bc9: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812b9f70)
Location: mm/swapfile.c:3553
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff812b9f70-ffffffff812b9f89: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c78ce)
Location: mm/swapfile.c:3573
Inline: True
Inline callers:
  - mm/swapfile.c:swap_page_sector
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff812c59e0-ffffffff812c59f9: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812ce23e)
Location: mm/swapfile.c:3544
Inline: True
Inline callers:
  - mm/swapfile.c:swap_page_sector
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff812cc690-ffffffff812cc6a9: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813136c0)
Location: mm/swapfile.c:3545
Inline: True
Inline callers:
  - mm/swapfile.c:swap_page_sector
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__set_page_dirty
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff813119d0-ffffffff813119e9: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137ed10)
Location: mm/swapfile.c:3400
Inline: True
Inline callers:
  - mm/swapfile.c:swap_page_sector
Direct callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_mark_dirty
  - mm/truncate.c:truncate_inode_pages_range
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:sio_write_complete
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
**Symbols:**

```
ffffffff8137cb60-ffffffff8137cb7f: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fd7f0)
Location: mm/swapfile.c:3402
Inline: True
Inline callers:
  - mm/swapfile.c:swap_page_sector
Direct callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_mark_dirty
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:sio_write_complete
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
**Symbols:**

```
ffffffff813fa390-ffffffff813fa3af: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81430ab0)
Location: mm/swapfile.c:3390
Inline: True
Inline callers:
  - mm/swapfile.c:swap_page_sector
Direct callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_mark_dirty
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:sio_write_complete
  - mm/hugetlb.c:hugetlb_basepage_index
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
**Symbols:**

```
ffffffff8142d2c0-ffffffff8142d2df: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81468ce0)
Location: mm/swapfile.c:3395
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_mark_dirty
  - mm/page_io.c:swap_read_folio_fs
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:sio_write_complete
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
```
**Symbols:**

```
ffffffff81468ce0-ffffffff81468d44: __page_file_index (STB_GLOBAL)
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
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010322968)
Location: mm/swapfile.c:3499
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffff800010322968-ffff800010322994: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053aeac)
Location: mm/swapfile.c:3499
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
c053aeac-c053aecc: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003f8390)
Location: mm/swapfile.c:3499
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
c0000000003f8390-c0000000003f83a4: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe00022372a)
Location: mm/swapfile.c:3499
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffe00022372a-ffffffe000223750: __page_file_index (STB_GLOBAL)
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
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81280190)
Location: mm/swapfile.c:3499
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff81280190-ffffffff812801a9: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81272000)
Location: mm/swapfile.c:3499
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff81272000-ffffffff81272019: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127dfa0)
Location: mm/swapfile.c:3499
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff8127dfa0-ffffffff8127dfb9: __page_file_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int __page_file_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128db50)
Location: mm/swapfile.c:3499
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/huge_memory.c:split_huge_page_to_list
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff8128db50-ffffffff8128db69: __page_file_index (STB_GLOBAL)
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
