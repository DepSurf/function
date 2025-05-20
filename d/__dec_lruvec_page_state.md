# Function: <code>__dec_lruvec_page_state</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81238a5d)
Location: include/linux/memcontrol.h:1164
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812503fb)
Location: include/linux/memcontrol.h:1177
Inline: True
Inline callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/shmem.c (ffffffff8126d48e)
Location: include/linux/memcontrol.h:1177
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_delete_from_page_cache
  - mm/shmem.c:shmem_delete_from_page_cache
```
```
In mm/rmap.c (ffffffff812a501e)
Location: include/linux/memcontrol.h:1177
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
```
```
In mm/huge_memory.c (ffffffff812ea46e)
Location: include/linux/memcontrol.h:1177
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/filemap.c (ffffffff8125a00f)
Location: include/linux/vmstat.h:527
Inline: True
Inline callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff81277c34)
Location: include/linux/vmstat.h:527
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_delete_from_page_cache
  - mm/shmem.c:shmem_delete_from_page_cache
```
```
In mm/rmap.c (ffffffff812b055a)
Location: include/linux/vmstat.h:527
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
```
```
In mm/huge_memory.c (ffffffff812f9485)
Location: include/linux/vmstat.h:527
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/filemap.c (ffffffff8125e5bd)
Location: include/linux/vmstat.h:527
Inline: True
Inline callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/shmem.c (ffffffff8127c994)
Location: include/linux/vmstat.h:527
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
```
```
In mm/rmap.c (ffffffff812b5b6a)
Location: include/linux/vmstat.h:527
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
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
In mm/filemap.c (ffffffff8129aecc)
Location: include/linux/vmstat.h:540
Inline: True
Inline callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/shmem.c (ffffffff812baaf4)
Location: include/linux/vmstat.h:540
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
```
```
In mm/rmap.c (ffffffff812f77ea)
Location: include/linux/vmstat.h:540
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
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
In mm/filemap.c (ffffffff812f0d88)
Location: include/linux/vmstat.h:606
Inline: True
Inline callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/shmem.c (ffffffff813181d0)
Location: include/linux/vmstat.h:606
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
```
```
In mm/rmap.c (ffffffff8135d447)
Location: include/linux/vmstat.h:606
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
```
</details>
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
