# Function: <code>__mem_cgroup_try_charge_swap</code>

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
int __mem_cgroup_try_charge_swap(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:7250
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff81cc2bc7-ffffffff81cc2bdb: __mem_cgroup_try_charge_swap.cold (STB_LOCAL)
ffffffff8135bdb0-ffffffff8135bfb9: __mem_cgroup_try_charge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __mem_cgroup_try_charge_swap(struct folio *folio, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:7231
Inline: False
Direct callers:
  - mm/swap_slots.c:folio_alloc_swap
```
**Symbols:**

```
ffffffff81e7512e-ffffffff81e75143: __mem_cgroup_try_charge_swap.cold (STB_LOCAL)
ffffffff813d56e0-ffffffff813d590c: __mem_cgroup_try_charge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __mem_cgroup_try_charge_swap(struct folio *folio, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8145b190)
Location: mm/memcontrol.c:7420
Inline: False
Direct callers:
  - mm/swap_slots.c:folio_alloc_swap
```
**Symbols:**

```
ffffffff8145b190-ffffffff8145b35f: __mem_cgroup_try_charge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __mem_cgroup_try_charge_swap(struct folio *folio, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81490e00)
Location: mm/memcontrol.c:7489
Inline: False
Direct callers:
  - mm/swap_slots.c:folio_alloc_swap
```
**Symbols:**

```
ffffffff81490e00-ffffffff81490fcf: __mem_cgroup_try_charge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __mem_cgroup_try_charge_swap(struct folio *folio, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814c0770)
Location: mm/memcontrol.c:7866
Inline: False
Direct callers:
  - mm/swap_slots.c:folio_alloc_swap
```
**Symbols:**

```
ffffffff814c0770-ffffffff814c093c: __mem_cgroup_try_charge_swap (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
