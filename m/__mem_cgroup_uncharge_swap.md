# Function: <code>__mem_cgroup_uncharge_swap</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:7296
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
```
**Symbols:**

```
ffffffff81cc2bdb-ffffffff81cc2bef: __mem_cgroup_uncharge_swap.cold (STB_LOCAL)
ffffffff8135bfc0-ffffffff8135c079: __mem_cgroup_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:7277
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
```
**Symbols:**

```
ffffffff81e75143-ffffffff81e75158: __mem_cgroup_uncharge_swap.cold (STB_LOCAL)
ffffffff813d5910-ffffffff813d59af: __mem_cgroup_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8145b370)
Location: mm/memcontrol.c:7466
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_folio
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
```
**Symbols:**

```
ffffffff8145b370-ffffffff8145b400: __mem_cgroup_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81490fe0)
Location: mm/memcontrol.c:7535
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_folio
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
```
**Symbols:**

```
ffffffff81490fe0-ffffffff81491070: __mem_cgroup_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814c0950)
Location: mm/memcontrol.c:7912
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_folio
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
```
**Symbols:**

```
ffffffff814c0950-ffffffff814c09d3: __mem_cgroup_uncharge_swap (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
