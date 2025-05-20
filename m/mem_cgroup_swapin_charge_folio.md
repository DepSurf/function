# Function: <code>mem_cgroup_swapin_charge_folio</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mem_cgroup_swapin_charge_folio(struct folio *folio, struct mm_struct *mm, gfp_t gfp, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8145a7d0)
Location: mm/memcontrol.c:6949
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
```
**Symbols:**

```
ffffffff8145a7d0-ffffffff8145a8f1: mem_cgroup_swapin_charge_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mem_cgroup_swapin_charge_folio(struct folio *folio, struct mm_struct *mm, gfp_t gfp, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81490430)
Location: mm/memcontrol.c:7017
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
```
**Symbols:**

```
ffffffff81490430-ffffffff81490551: mem_cgroup_swapin_charge_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mem_cgroup_swapin_charge_folio(struct folio *folio, struct mm_struct *mm, gfp_t gfp, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bfce0)
Location: mm/memcontrol.c:7344
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
```
**Symbols:**

```
ffffffff814bfce0-ffffffff814bfe39: mem_cgroup_swapin_charge_folio (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
