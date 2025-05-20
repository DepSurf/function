# Function: <code>find_get_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *find_get_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118cf70)
Location: mm/filemap.c:1030
Inline: False
Direct callers:
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:pagecache_get_page
  - mm/mincore.c:mincore_page
  - mm/madvise.c:SyS_madvise
  - mm/memcontrol.c:get_mctgt_type
```
**Symbols:**

```
ffffffff8118cf70-ffffffff8118d004: find_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *find_get_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a0bc0)
Location: mm/filemap.c:1073
Inline: False
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/mincore.c:mincore_page
  - mm/madvise.c:SyS_madvise
  - mm/memcontrol.c:get_mctgt_type
```
**Symbols:**

```
ffffffff811a0bc0-ffffffff811a0cc0: find_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *find_get_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b07c0)
Location: mm/filemap.c:1175
Inline: False
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/mincore.c:mincore_page
  - mm/madvise.c:SyS_madvise
  - mm/memcontrol.c:get_mctgt_type
```
**Symbols:**

```
ffffffff811b07c0-ffffffff811b08c0: find_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *find_get_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b7ad0)
Location: mm/filemap.c:1301
Inline: False
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/mincore.c:mincore_page
  - mm/madvise.c:madvise_willneed
  - mm/memcontrol.c:get_mctgt_type
```
**Symbols:**

```
ffffffff811b7ad0-ffffffff811b7b96: find_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *find_get_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cc0c0)
Location: mm/filemap.c:1423
Inline: False
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/mincore.c:mincore_page
  - mm/madvise.c:madvise_willneed
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff811cc0c0-ffffffff811cc1c2: find_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *find_get_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ed190)
Location: mm/filemap.c:1423
Inline: False
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/mincore.c:mincore_page
  - mm/madvise.c:madvise_willneed
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff811ed190-ffffffff811ed280: find_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *find_get_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fe5f0)
Location: mm/filemap.c:1468
Inline: False
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/mincore.c:mincore_page
  - mm/madvise.c:madvise_willneed
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff811fe5f0-ffffffff811fe744: find_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *find_get_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81215900)
Location: mm/filemap.c:1516
Inline: False
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/mincore.c:mincore_page
  - mm/madvise.c:madvise_willneed
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81215900-ffffffff81215a3b: find_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *find_get_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812231d0)
Location: mm/filemap.c:1525
Inline: False
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/mincore.c:mincore_page
  - mm/madvise.c:__do_sys_madvise
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812231d0-ffffffff81223338: find_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *find_get_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81251ad0)
Location: mm/filemap.c:1500
Inline: False
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/mincore.c:mincore_page
  - mm/madvise.c:madvise_willneed
  - mm/memcontrol.c:get_mctgt_type
```
**Symbols:**

```
ffffffff81251ad0-ffffffff81251c29: find_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *find_get_entry(struct address_space *mapping, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125d220)
Location: mm/filemap.c:1691
Inline: False
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:get_shadow_from_swap_cache
```
**Symbols:**

```
ffffffff8125d220-ffffffff8125d380: find_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81262b26)
Location: mm/filemap.c:1916
Inline: True
Inline callers:
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129f174)
Location: mm/filemap.c:1971
Inline: True
Inline callers:
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2023
Inline: True
Inline callers:
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
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
In mm/filemap.c (0)
Location: mm/filemap.c:1997
Inline: True
Inline callers:
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:1968
Inline: True
Inline callers:
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:filemap_get_folios
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
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
In mm/filemap.c (0)
Location: mm/filemap.c:1954
Inline: True
Inline callers:
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_get_folios_tag
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:find_get_entries
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
struct page *find_get_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b0a68)
Location: mm/filemap.c:1525
Inline: False
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/mincore.c:mincore_page
  - mm/madvise.c:__arm64_sys_madvise
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffff8000102b0a68-ffff8000102b0bfc: find_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *find_get_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04dd3f8)
Location: mm/filemap.c:1525
Inline: False
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/mincore.c:mincore_page
  - mm/madvise.c:__se_sys_madvise
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:smaps_pte_entry
```
**Symbols:**

```
c04dd3f8-c04dd55c: find_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *find_get_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000365e50)
Location: mm/filemap.c:1525
Inline: False
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/mincore.c:mincore_page
  - mm/madvise.c:__se_sys_madvise
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
c000000000365e50-c000000000366070: find_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *find_get_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d6460)
Location: mm/filemap.c:1525
Inline: False
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/mincore.c:mincore_page
  - mm/madvise.c:__se_sys_madvise
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffe0001d6460-ffffffe0001d658a: find_get_entry (STB_GLOBAL)
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
struct page *find_get_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121b820)
Location: mm/filemap.c:1525
Inline: False
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/mincore.c:mincore_page
  - mm/madvise.c:__do_sys_madvise
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8121b820-ffffffff8121b988: find_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *find_get_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120ea10)
Location: mm/filemap.c:1525
Inline: False
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/mincore.c:mincore_page
  - mm/madvise.c:__do_sys_madvise
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8120ea10-ffffffff8120eb78: find_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *find_get_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812195c0)
Location: mm/filemap.c:1525
Inline: False
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/mincore.c:mincore_page
  - mm/madvise.c:__do_sys_madvise
  - mm/memcontrol.c:get_mctgt_type
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812195c0-ffffffff81219728: find_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *find_get_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812286b0)
Location: mm/filemap.c:1525
Inline: False
Direct callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/mincore.c:mincore_page
  - mm/madvise.c:__do_sys_madvise
  - mm/memcontrol.c:get_mctgt_type
```
**Symbols:**

```
ffffffff812286b0-ffffffff81228822: find_get_entry (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int index</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int offset</code>
</li>
</ul>
</details>
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
