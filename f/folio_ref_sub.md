# Function: <code>folio_ref_sub</code>

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
In mm/filemap.c (ffffffff81e6b4b6)
Location: include/linux/page_ref.h:137
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/shmem.c (ffffffff81317ba9)
Location: include/linux/page_ref.h:137
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
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
In mm/filemap.c (ffffffff81359a58)
Location: include/linux/page_ref.h:137
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/shmem.c (ffffffff8138af48)
Location: include/linux/page_ref.h:137
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff813f8dfe)
Location: include/linux/page_ref.h:137
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
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
In mm/filemap.c (ffffffff8138b3a5)
Location: include/linux/page_ref.h:137
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/shmem.c (ffffffff813bd576)
Location: include/linux/page_ref.h:137
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8142bbce)
Location: include/linux/page_ref.h:137
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
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
In mm/filemap.c (ffffffff813b4ecc)
Location: include/linux/page_ref.h:137
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/shmem.c (ffffffff813e87e8)
Location: include/linux/page_ref.h:137
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/swap_state.c (ffffffff8146532b)
Location: include/linux/page_ref.h:137
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/khugepaged.c (ffffffff814b087d)
Location: include/linux/page_ref.h:137
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
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
