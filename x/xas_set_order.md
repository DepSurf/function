# Function: <code>xas_set_order</code>

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
In mm/filemap.c (ffffffff8120063d)
Location: include/linux/xarray.h:1388
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In lib/xarray.c (ffffffff81a1916a)
Location: include/linux/xarray.h:1388
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (ffffffff8121830c)
Location: include/linux/xarray.h:1517
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In lib/xarray.c (ffffffff81a88e84)
Location: include/linux/xarray.h:1517
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (ffffffff81225b9c)
Location: include/linux/xarray.h:1517
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In lib/xarray.c (ffffffff81ac0124)
Location: include/linux/xarray.h:1517
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (ffffffff8124e6c3)
Location: include/linux/xarray.h:1552
Inline: True
Inline callers:
  - mm/filemap.c:page_cache_delete
```
```
In lib/xarray.c (ffffffff815fbe64)
Location: include/linux/xarray.h:1552
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (ffffffff81258971)
Location: include/linux/xarray.h:1587
Inline: True
Inline callers:
  - mm/filemap.c:page_cache_delete
```
```
In lib/xarray.c (ffffffff81620a04)
Location: include/linux/xarray.h:1587
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (ffffffff81261340)
Location: include/linux/xarray.h:1589
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In lib/xarray.c (ffffffff816041e4)
Location: include/linux/xarray.h:1589
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (ffffffff8129dfa6)
Location: include/linux/xarray.h:1589
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In lib/xarray.c (ffffffff81672a57)
Location: include/linux/xarray.h:1589
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (ffffffff812f2523)
Location: include/linux/xarray.h:1611
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/khugepaged.c (ffffffff813c57c6)
Location: include/linux/xarray.h:1611
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In lib/xarray.c (ffffffff8178d331)
Location: include/linux/xarray.h:1611
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (ffffffff8135ab24)
Location: include/linux/xarray.h:1626
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/khugepaged.c (ffffffff8144a132)
Location: include/linux/xarray.h:1626
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In lib/xarray.c (ffffffff8204a97e)
Location: include/linux/xarray.h:1626
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (ffffffff8138c548)
Location: include/linux/xarray.h:1626
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/khugepaged.c (ffffffff8148038b)
Location: include/linux/xarray.h:1626
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In lib/xarray.c (ffffffff820c927e)
Location: include/linux/xarray.h:1626
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (ffffffff813b5fdb)
Location: include/linux/xarray.h:1644
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_remove_folio
```
```
In mm/khugepaged.c (ffffffff814ae481)
Location: include/linux/xarray.h:1644
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In lib/xarray.c (ffffffff821a3bfe)
Location: include/linux/xarray.h:1644
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (ffff8000102b2b74)
Location: include/linux/xarray.h:1517
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In lib/xarray.c (ffff800010d9ae08)
Location: include/linux/xarray.h:1517
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04dfdfc)
Location: include/linux/xarray.h:1517
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
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
In mm/filemap.c (c0000000003695fc)
Location: include/linux/xarray.h:1517
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In lib/xarray.c (c000000000ee1fe0)
Location: include/linux/xarray.h:1517
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d8486)
Location: include/linux/xarray.h:1517
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
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
In mm/filemap.c (ffffffff8121e1ec)
Location: include/linux/xarray.h:1517
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In lib/xarray.c (ffffffff81a5ef74)
Location: include/linux/xarray.h:1517
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (ffffffff812113ac)
Location: include/linux/xarray.h:1517
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In lib/xarray.c (ffffffff81a1c044)
Location: include/linux/xarray.h:1517
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (ffffffff8121bf8c)
Location: include/linux/xarray.h:1517
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In lib/xarray.c (ffffffff81acb364)
Location: include/linux/xarray.h:1517
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
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
In mm/filemap.c (ffffffff8122aff5)
Location: include/linux/xarray.h:1517
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In lib/xarray.c (ffffffff81ad79c4)
Location: include/linux/xarray.h:1517
Inline: True
Inline callers:
  - lib/xarray.c:xa_store_range
```
</details>
</li>
</ul>

## Differences
