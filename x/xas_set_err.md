# Function: <code>xas_set_err</code>

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
In mm/filemap.c (ffffffff811fe8d1)
Location: include/linux/xarray.h:1235
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff812215ac)
Location: include/linux/xarray.h:1235
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In fs/dax.c (ffffffff8130cded)
Location: include/linux/xarray.h:1235
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In lib/xarray.c (ffffffff81a19063)
Location: include/linux/xarray.h:1235
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:xas_alloc
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
In mm/filemap.c (ffffffff81215bd1)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff81230de3)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In fs/dax.c (ffffffff813354a0)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In lib/xarray.c (ffffffff81a88c86)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:xas_alloc
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
In mm/filemap.c (ffffffff812234d1)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff8123f006)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In fs/dax.c (ffffffff813490ad)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In lib/xarray.c (ffffffff81abff26)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:xas_alloc
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
In mm/filemap.c (ffffffff81250b63)
Location: include/linux/xarray.h:1399
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff8126c8c8)
Location: include/linux/xarray.h:1399
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In fs/dax.c (ffffffff8138e42d)
Location: include/linux/xarray.h:1399
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In lib/xarray.c (ffffffff815fc526)
Location: include/linux/xarray.h:1399
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:xas_alloc
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
In mm/filemap.c (ffffffff8125afce)
Location: include/linux/xarray.h:1401
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff8127730f)
Location: include/linux/xarray.h:1401
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In fs/dax.c (ffffffff8139fb7d)
Location: include/linux/xarray.h:1401
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In lib/xarray.c (ffffffff81621146)
Location: include/linux/xarray.h:1401
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:xas_split_alloc
  - lib/xarray.c:xas_alloc
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
In mm/filemap.c (ffffffff8125ec90)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff8127c377)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In fs/dax.c (ffffffff813a713f)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In lib/xarray.c (ffffffff81604b29)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:xas_split_alloc
  - lib/xarray.c:xas_alloc
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
In mm/filemap.c (ffffffff8129c0b6)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff812ba584)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In fs/dax.c (ffffffff813f7005)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In lib/xarray.c (ffffffff81673419)
Location: include/linux/xarray.h:1403
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:xas_split_alloc
  - lib/xarray.c:xas_alloc
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
In mm/filemap.c (ffffffff812f2596)
Location: include/linux/xarray.h:1406
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff81317a90)
Location: include/linux/xarray.h:1406
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/list_lru.c (ffffffff81335aef)
Location: include/linux/xarray.h:1406
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
```
```
In fs/dax.c (ffffffff81469449)
Location: include/linux/xarray.h:1406
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In lib/xarray.c (ffffffff8178da52)
Location: include/linux/xarray.h:1406
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:xas_split_alloc
  - lib/xarray.c:xas_alloc
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
In mm/filemap.c (ffffffff8135ab93)
Location: include/linux/xarray.h:1421
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff8138af75)
Location: include/linux/xarray.h:1421
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/list_lru.c (ffffffff813ac8af)
Location: include/linux/xarray.h:1421
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
```
```
In fs/dax.c (ffffffff814f9ed9)
Location: include/linux/xarray.h:1421
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In lib/xarray.c (ffffffff8204b0f2)
Location: include/linux/xarray.h:1421
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:xas_split_alloc
  - lib/xarray.c:xas_alloc
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
In mm/filemap.c (ffffffff8138c5b7)
Location: include/linux/xarray.h:1421
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff813bd5a8)
Location: include/linux/xarray.h:1421
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/list_lru.c (ffffffff813e0c4f)
Location: include/linux/xarray.h:1421
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
```
```
In fs/dax.c (ffffffff81531353)
Location: include/linux/xarray.h:1421
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In lib/xarray.c (ffffffff820c99f2)
Location: include/linux/xarray.h:1421
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:xas_split_alloc
  - lib/xarray.c:xas_alloc
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
In mm/filemap.c (ffffffff813b6157)
Location: include/linux/xarray.h:1439
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
```
```
In mm/shmem.c (ffffffff813e8691)
Location: include/linux/xarray.h:1439
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/list_lru.c (ffffffff8140b51f)
Location: include/linux/xarray.h:1439
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
  - mm/list_lru.c:memcg_list_lru_alloc
```
```
In fs/dax.c (ffffffff81566233)
Location: include/linux/xarray.h:1439
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In lib/xarray.c (ffffffff821a4372)
Location: include/linux/xarray.h:1439
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:xas_split_alloc
  - lib/xarray.c:xas_alloc
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
In mm/filemap.c (ffff8000102b0e50)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffff8000102d16ac)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In fs/dax.c (ffff800010409d3c)
Location: include/linux/xarray.h:1364
Inline: True
```
```
In lib/xarray.c (ffff800010d9b8c0)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:xas_alloc
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
In mm/filemap.c (c04dd858)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (c04f8a88)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In lib/xarray.c (c0e97fc8)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:xas_alloc
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
In mm/filemap.c (c000000000366300)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (c00000000038f100)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In fs/dax.c (c000000000515b40)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In lib/xarray.c (c000000000ee1ca4)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:xas_alloc
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
In mm/filemap.c (ffffffe0001d670c)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffe0001edb6e)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In fs/dax.c (ffffffe0002b393a)
Location: include/linux/xarray.h:1364
Inline: True
```
```
In lib/xarray.c (ffffffe0008c3a8c)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:xas_alloc
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
In mm/filemap.c (ffffffff8121bb21)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff81237656)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In fs/dax.c (ffffffff8134168d)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In lib/xarray.c (ffffffff81a5ed76)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:xas_alloc
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
In mm/filemap.c (ffffffff8120ed11)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff8122a4e6)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In fs/dax.c (ffffffff81332041)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In lib/xarray.c (ffffffff81a1be46)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:xas_alloc
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
In mm/filemap.c (ffffffff812198c1)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff812353f6)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In fs/dax.c (ffffffff8133f15d)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In lib/xarray.c (ffffffff81acb166)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:xas_alloc
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
In mm/filemap.c (ffffffff812289b1)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
```
In mm/shmem.c (ffffffff81245506)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In fs/dax.c (ffffffff81350beb)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In lib/xarray.c (ffffffff81ad77c6)
Location: include/linux/xarray.h:1364
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:xas_alloc
```
</details>
</li>
</ul>

## Differences
