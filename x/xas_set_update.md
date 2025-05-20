# Function: <code>xas_set_update</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fea52)
Location: include/linux/xarray.h:1410
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff81216253)
Location: include/linux/xarray.h:1410
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/workingset.c (ffffffff81238b71)
Location: include/linux/xarray.h:1410
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
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
In mm/filemap.c (ffffffff81215d52)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff81225bef)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/workingset.c (ffffffff81249ce9)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
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
In mm/filemap.c (ffffffff81223652)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff81233a3f)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/workingset.c (ffffffff81258139)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
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
In mm/filemap.c (ffffffff81250d56)
Location: include/linux/xarray.h:1574
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:page_cache_delete
```
```
In mm/truncate.c (ffffffff812611ce)
Location: include/linux/xarray.h:1574
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/workingset.c (ffffffff81286958)
Location: include/linux/xarray.h:1574
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
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
In mm/filemap.c (ffffffff8125afc1)
Location: include/linux/xarray.h:1609
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:page_cache_delete
```
```
In mm/truncate.c (ffffffff8126b5cc)
Location: include/linux/xarray.h:1609
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
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
In mm/filemap.c (ffffffff8125ec83)
Location: include/linux/xarray.h:1611
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff81270715)
Location: include/linux/xarray.h:1611
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
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
In mm/filemap.c (ffffffff8129c0a9)
Location: include/linux/xarray.h:1611
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff812ae39d)
Location: include/linux/xarray.h:1611
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:__invalidate_mapping_pages
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
In mm/filemap.c (ffffffff812f24d7)
Location: include/linux/xarray.h:1633
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/truncate.c (ffffffff81307491)
Location: include/linux/xarray.h:1633
Inline: True
Inline callers:
  - mm/truncate.c:clear_shadow_entry
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
In mm/filemap.c (ffffffff8135aadd)
Location: include/linux/xarray.h:1648
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/truncate.c (ffffffff813715a1)
Location: include/linux/xarray.h:1648
Inline: True
Inline callers:
  - mm/truncate.c:clear_shadow_entry
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
In mm/filemap.c (ffffffff8138c502)
Location: include/linux/xarray.h:1649
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/truncate.c (ffffffff813a36b1)
Location: include/linux/xarray.h:1649
Inline: True
Inline callers:
  - mm/truncate.c:clear_shadow_entry
```
```
In mm/swap_state.c (ffffffff8142bcac)
Location: include/linux/xarray.h:1649
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
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
In mm/filemap.c (ffffffff813b5f31)
Location: include/linux/xarray.h:1667
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/truncate.c (ffffffff813cd251)
Location: include/linux/xarray.h:1667
Inline: True
Inline callers:
  - mm/truncate.c:clear_shadow_entry
```
```
In mm/swap_state.c (ffffffff8146540c)
Location: include/linux/xarray.h:1667
Inline: True
Inline callers:
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
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
In mm/filemap.c (ffff8000102b0f1c)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffff8000102c3f54)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/workingset.c (ffff8000102f00b4)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
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
In mm/filemap.c (c04dd70c)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (c04ee4a4)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/truncate.c:clear_shadow_entry
```
```
In mm/workingset.c (c05134e4)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
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
In mm/filemap.c (c000000000366584)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (c00000000037e480)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/workingset.c (c0000000003b4718)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
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
In mm/filemap.c (ffffffe0001d685a)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffe0001e4abc)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/workingset.c (ffffffe000203ad0)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
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
In mm/filemap.c (ffffffff8121bca2)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff8122c08f)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/workingset.c (ffffffff81250789)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
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
In mm/filemap.c (ffffffff8120ee8c)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff8121f16f)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/workingset.c (ffffffff81243719)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
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
In mm/filemap.c (ffffffff81219a42)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff81229e2f)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/workingset.c (ffffffff8124e529)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
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
In mm/filemap.c (ffffffff81228b32)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff81239225)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
```
```
In mm/workingset.c (ffffffff8125ddf6)
Location: include/linux/xarray.h:1539
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
</details>
</li>
</ul>

## Differences
