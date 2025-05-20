# Function: <code>__inc_lruvec_page_state</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c79ac)
Location: include/linux/memcontrol.h:973
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811dc7ec)
Location: include/linux/memcontrol.h:981
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811fc7dc)
Location: include/linux/memcontrol.h:1074
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
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
In mm/page-writeback.c (ffffffff8120f32c)
Location: include/linux/memcontrol.h:1158
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/workingset.c (ffffffff81238ba2)
Location: include/linux/memcontrol.h:1158
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812213a9)
Location: include/linux/memcontrol.h:1159
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8122ee39)
Location: include/linux/memcontrol.h:1211
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
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
In mm/filemap.c (ffffffff81250c45)
Location: include/linux/memcontrol.h:1171
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8125bf19)
Location: include/linux/memcontrol.h:1171
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/shmem.c (ffffffff8126d433)
Location: include/linux/memcontrol.h:1171
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/rmap.c (ffffffff812a4d34)
Location: include/linux/memcontrol.h:1171
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
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
In mm/filemap.c (ffffffff8125b03c)
Location: include/linux/vmstat.h:521
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81266349)
Location: include/linux/vmstat.h:521
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/shmem.c (ffffffff81277c22)
Location: include/linux/vmstat.h:521
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/rmap.c (ffffffff812b03a3)
Location: include/linux/vmstat.h:521
Inline: True
Inline callers:
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
```
In mm/khugepaged.c (ffffffff812fdc37)
Location: include/linux/vmstat.h:521
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
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
In mm/filemap.c (ffffffff8125ecdc)
Location: include/linux/vmstat.h:521
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8126ae49)
Location: include/linux/vmstat.h:521
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/shmem.c (ffffffff8127c982)
Location: include/linux/vmstat.h:521
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
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
In mm/filemap.c (ffffffff8129c105)
Location: include/linux/vmstat.h:534
Inline: True
Inline callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812a4ae9)
Location: include/linux/vmstat.h:534
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
```
In mm/shmem.c (ffffffff812baae2)
Location: include/linux/vmstat.h:534
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
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
In mm/filemap.c (ffffffff812f0d71)
Location: include/linux/vmstat.h:600
Inline: True
Inline callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/shmem.c (ffffffff813181be)
Location: include/linux/vmstat.h:600
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffff8000102be0a8)
Location: include/linux/memcontrol.h:1211
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
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
In mm/page-writeback.c (c04ea364)
Location: include/linux/memcontrol.h:1211
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c000000000376efc)
Location: include/linux/memcontrol.h:1211
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
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
In mm/page-writeback.c (ffffffe0001e0b1a)
Location: include/linux/memcontrol.h:1211
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81227489)
Location: include/linux/memcontrol.h:1211
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8121a5f9)
Location: include/linux/memcontrol.h:1211
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81225229)
Location: include/linux/memcontrol.h:1211
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81234509)
Location: include/linux/memcontrol.h:1211
Inline: True
Inline callers:
  - mm/page-writeback.c:account_page_dirtied
```
</details>
</li>
</ul>

## Differences
