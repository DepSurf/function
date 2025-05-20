# Function: <code>page_index</code>

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
In mm/page-writeback.c (ffffffff8119aa11)
Location: include/linux/mm.h:958
Inline: True
Inline callers:
  - mm/page-writeback.c:__set_page_dirty_nobuffers
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/hugetlb.c (ffffffff811dc60f)
Location: include/linux/mm.h:958
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/migrate.c (ffffffff811f1694)
Location: include/linux/mm.h:958
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
```
```
In fs/buffer.c (ffffffff8124288e)
Location: include/linux/mm.h:958
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
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
In mm/page-writeback.c (ffffffff811add83)
Location: include/linux/mm.h:1055
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/hugetlb.c (ffffffff811fa86f)
Location: include/linux/mm.h:1055
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/migrate.c (ffffffff81211a67)
Location: include/linux/mm.h:1055
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81217a84)
Location: include/linux/mm.h:1055
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/buffer.c (ffffffff8126abb2)
Location: include/linux/mm.h:1055
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
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
In mm/page-writeback.c (ffffffff811be3a7)
Location: include/linux/mm.h:1046
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/page_io.c (ffffffff81200971)
Location: include/linux/mm.h:1046
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/hugetlb.c (ffffffff8120b29f)
Location: include/linux/mm.h:1046
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/migrate.c (ffffffff81223c1b)
Location: include/linux/mm.h:1046
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8122a034)
Location: include/linux/mm.h:1046
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/buffer.c (ffffffff8127dcd7)
Location: include/linux/mm.h:1046
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
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
In mm/page-writeback.c (ffffffff811c7796)
Location: include/linux/mm.h:1088
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/page_io.c (ffffffff8120b5ca)
Location: include/linux/mm.h:1088
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/hugetlb.c (ffffffff812167fd)
Location: include/linux/mm.h:1088
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/migrate.c (ffffffff8122f557)
Location: include/linux/mm.h:1088
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81235b83)
Location: include/linux/mm.h:1088
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/buffer.c (ffffffff8128b8b7)
Location: include/linux/mm.h:1088
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
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
In mm/page-writeback.c (ffffffff811dc5d7)
Location: include/linux/mm.h:1139
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/page_io.c (ffffffff81224aac)
Location: include/linux/mm.h:1139
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/hugetlb.c (ffffffff812314ad)
Location: include/linux/mm.h:1139
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/migrate.c (ffffffff8124d077)
Location: include/linux/mm.h:1139
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8125492e)
Location: include/linux/mm.h:1139
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/buffer.c (ffffffff812ae467)
Location: include/linux/mm.h:1139
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
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
In mm/page-writeback.c (ffffffff811fe90b)
Location: include/linux/mm.h:1218
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/page_io.c (ffffffff812470df)
Location: include/linux/mm.h:1218
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/hugetlb.c (ffffffff812543ad)
Location: include/linux/mm.h:1218
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/migrate.c (ffffffff81270b72)
Location: include/linux/mm.h:1218
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81278711)
Location: include/linux/mm.h:1218
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/buffer.c (ffffffff812d6137)
Location: include/linux/mm.h:1218
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
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
In mm/page-writeback.c (ffffffff8120ef23)
Location: include/linux/mm.h:1286
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/page_io.c (ffffffff8125b537)
Location: include/linux/mm.h:1286
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/hugetlb.c (ffffffff8126878d)
Location: include/linux/mm.h:1286
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/migrate.c (ffffffff81285111)
Location: include/linux/mm.h:1286
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8128cd95)
Location: include/linux/mm.h:1286
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/buffer.c (ffffffff812eb507)
Location: include/linux/mm.h:1286
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
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
In mm/page-writeback.c (ffffffff8121eab6)
Location: include/linux/mm.h:1354
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/page_io.c (ffffffff812766a1)
Location: include/linux/mm.h:1354
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/hugetlb.c (ffffffff8128386f)
Location: include/linux/mm.h:1354
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/migrate.c (ffffffff8129f771)
Location: include/linux/mm.h:1354
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a7a83)
Location: include/linux/mm.h:1354
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/buffer.c (ffffffff8130cc07)
Location: include/linux/mm.h:1354
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
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
In mm/page-writeback.c (ffffffff8122c556)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/page_io.c (ffffffff81286191)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/hugetlb.c (ffffffff8129340f)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/migrate.c (ffffffff812b0b11)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b8f64)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/buffer.c (ffffffff8131fbd7)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int page_index(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81259e66)
Location: include/linux/mm.h:1542
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/page_io.c (ffffffff812b83a2)
Location: include/linux/mm.h:1542
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
Direct callers:
  - mm/page_io.c:__swap_writepage
```
```
In mm/hugetlb.c (ffffffff812c692d)
Location: include/linux/mm.h:1542
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/migrate.c (ffffffff812e6c51)
Location: include/linux/mm.h:1542
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812edb5d)
Location: include/linux/mm.h:1542
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/buffer.c (ffffffff81359f10)
Location: include/linux/mm.h:1542
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff812b7b20-ffffffff812b7b61: page_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int page_index(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81265618)
Location: include/linux/mm.h:1583
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/page_io.c (ffffffff812c3a6f)
Location: include/linux/mm.h:1583
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
Direct callers:
  - mm/page_io.c:__swap_writepage
```
```
In mm/hugetlb.c (ffffffff812d246d)
Location: include/linux/mm.h:1583
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/migrate.c (ffffffff812f1fa1)
Location: include/linux/mm.h:1583
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812f920a)
Location: include/linux/mm.h:1583
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/buffer.c (ffffffff81368040)
Location: include/linux/mm.h:1583
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff812c31e0-ffffffff812c3221: page_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int page_index(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8126a116)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/page_io.c (ffffffff812ca839)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
Direct callers:
  - mm/page_io.c:__swap_writepage
```
```
In mm/hugetlb.c (ffffffff812d8f1d)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
```
```
In mm/migrate.c (ffffffff812f82f1)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812ff80c)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/buffer.c (ffffffff8136eb00)
Location: include/linux/mm.h:1653
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff812ca040-ffffffff812ca081: page_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int page_index(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812a6da9)
Location: include/linux/mm.h:1664
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__set_page_dirty
```
```
In mm/page_io.c (ffffffff8130f839)
Location: include/linux/mm.h:1664
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
Direct callers:
  - mm/page_io.c:__swap_writepage
```
```
In mm/hugetlb.c (ffffffff8131f91f)
Location: include/linux/mm.h:1664
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
```
```
In mm/migrate.c (ffffffff81342961)
Location: include/linux/mm.h:1664
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81349423)
Location: include/linux/mm.h:1664
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8130f060-ffffffff8130f0a1: page_index (STB_LOCAL)
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
In mm/page_io.c (ffffffff8137a0a4)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:sio_write_complete
```
```
In mm/hugetlb.c (ffffffff8138c39a)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
```
```
In mm/migrate.c (ffffffff813b4e7f)
Location: include/linux/mm.h:1776
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
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
In mm/page_io.c (ffffffff813f7b94)
Location: include/linux/mm.h:1909
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:sio_write_complete
```
```
In mm/hugetlb.c (ffffffff8140ae6c)
Location: include/linux/mm.h:1909
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
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
In mm/page_io.c (ffffffff8142ad54)
Location: include/linux/mm.h:2180
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:sio_write_complete
```
```
In mm/hugetlb.c (ffffffff8143e516)
Location: include/linux/mm.h:2180
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff814644f8)
Location: include/linux/mm.h:2234
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio_fs
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:sio_write_complete
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
In mm/page-writeback.c (ffff8000102bbfcc)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/page_io.c (ffff8000103207d0)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/hugetlb.c (ffff800010331438)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/migrate.c (ffff800010350f50)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffff800010359658)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/buffer.c (ffff8000103d824c)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
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
In mm/page-writeback.c (c04e6ec0)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/page_io.c (c05391ac)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/migrate.c (c05525c8)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In fs/buffer.c (c05b131c)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
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
In mm/page-writeback.c (c000000000373758)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/page_io.c (c0000000003f5a50)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/hugetlb.c (c00000000040a194)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/migrate.c (c00000000043712c)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (c000000000442ba0)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/buffer.c (c0000000004dbfa4)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
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
In mm/page-writeback.c (ffffffe0001de102)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/page_io.c (ffffffe000221e36)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/hugetlb.c (ffffffe00022e538)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/migrate.c (ffffffe00023f89e)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In fs/buffer.c (ffffffe000291096)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
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
In mm/page-writeback.c (ffffffff81224ba6)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/page_io.c (ffffffff8127e7e1)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/hugetlb.c (ffffffff8128b9ef)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/migrate.c (ffffffff812a90f1)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b1544)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/buffer.c (ffffffff813181b7)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
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
In mm/page-writeback.c (ffffffff81217d56)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/page_io.c (ffffffff81270611)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/hugetlb.c (ffffffff8127d81f)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/migrate.c (ffffffff8129aa61)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a2914)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/buffer.c (ffffffff81308da7)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
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
In mm/page-writeback.c (ffffffff81222946)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/page_io.c (ffffffff8127c581)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/hugetlb.c (ffffffff812897ff)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/migrate.c (ffffffff812a6f01)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812af354)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/buffer.c (ffffffff81315c87)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
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
In mm/page-writeback.c (ffffffff81231b26)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/page_io.c (ffffffff8128c151)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/hugetlb.c (ffffffff812995df)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/migrate.c (ffffffff812b7231)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812bf6a4)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/buffer.c (ffffffff81327887)
Location: include/linux/mm.h:1368
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
