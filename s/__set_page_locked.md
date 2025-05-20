# Function: <code>__set_page_locked</code>

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
In mm/filemap.c (ffffffff8118df4a)
Location: include/linux/pagemap.h:436
Inline: True
Inline callers:
  - mm/filemap.c:add_to_page_cache_lru
```
```
In mm/shmem.c (ffffffff811a8e03)
Location: include/linux/pagemap.h:436
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/swap_state.c (ffffffff811d2b58)
Location: include/linux/pagemap.h:436
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff811dd114)
Location: include/linux/pagemap.h:436
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_add_to_page_cache
```
```
In mm/ksm.c (ffffffff811e6de2)
Location: include/linux/pagemap.h:436
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff811f32c5)
Location: include/linux/pagemap.h:436
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
</details>
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
In <code>6.2</code>: Absent ⚠️
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
