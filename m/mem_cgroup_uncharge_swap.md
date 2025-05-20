# Function: <code>mem_cgroup_uncharge_swap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mem_cgroup_uncharge_swap(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812004a0)
Location: mm/memcontrol.c:5674
Inline: False
Direct callers:
  - mm/swapfile.c:swap_entry_free
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff812004a0-ffffffff81200526: mem_cgroup_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mem_cgroup_uncharge_swap(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81224630)
Location: mm/memcontrol.c:5941
Inline: False
Direct callers:
  - mm/swapfile.c:swap_entry_free
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff81224630-ffffffff812246d2: mem_cgroup_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mem_cgroup_uncharge_swap(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81236c00)
Location: mm/memcontrol.c:5941
Inline: False
Direct callers:
  - mm/swapfile.c:swap_entry_free
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff81236c00-ffffffff81236ca3: mem_cgroup_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812426c0)
Location: mm/memcontrol.c:6006
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff812426c0-ffffffff8124274b: mem_cgroup_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81262500)
Location: mm/memcontrol.c:6112
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff81262500-ffffffff8126258b: mem_cgroup_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81286670)
Location: mm/memcontrol.c:6187
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff81286670-ffffffff81286746: mem_cgroup_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129b5e0)
Location: mm/memcontrol.c:6518
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff8129b5e0-ffffffff8129b6b6: mem_cgroup_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b6820)
Location: mm/memcontrol.c:6810
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff812b6820-ffffffff812b68c9: mem_cgroup_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c86f0)
Location: mm/memcontrol.c:7140
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff812c86f0-ffffffff812c8799: mem_cgroup_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fdfc0)
Location: mm/memcontrol.c:6997
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/memcontrol.c:mem_cgroup_charge
```
**Symbols:**

```
ffffffff812fdfc0-ffffffff812fe06c: mem_cgroup_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130a450)
Location: mm/memcontrol.c:7251
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/memcontrol.c:mem_cgroup_charge
```
**Symbols:**

```
ffffffff8130a450-ffffffff8130a501: mem_cgroup_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81310cf0)
Location: mm/memcontrol.c:7120
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
```
**Symbols:**

```
ffffffff81310cf0-ffffffff81310da5: mem_cgroup_uncharge_swap (STB_GLOBAL)
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
In mm/swapfile.c (ffffffff81313f08)
Location: include/linux/swap.h:748
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
```
```
In mm/memcontrol.c (ffffffff8135c0a0)
Location: include/linux/swap.h:748
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
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
In mm/swapfile.c (ffffffff8137f5d3)
Location: include/linux/swap.h:663
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
```
```
In mm/memcontrol.c (ffffffff813d59e3)
Location: include/linux/swap.h:663
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
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
In mm/swapfile.c (ffffffff813fe113)
Location: include/linux/swap.h:673
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_folio
```
```
In mm/memcontrol.c (ffffffff8145b42b)
Location: include/linux/swap.h:673
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
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
In mm/swapfile.c (ffffffff814310f3)
Location: include/linux/swap.h:664
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_folio
```
```
In mm/memcontrol.c (ffffffff8149109b)
Location: include/linux/swap.h:664
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
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
In mm/swapfile.c (ffffffff8146a513)
Location: include/linux/swap.h:655
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_folio
```
```
In mm/memcontrol.c (ffffffff814c0a0b)
Location: include/linux/swap.h:655
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap
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
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036b5b8)
Location: mm/memcontrol.c:7140
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffff80001036b5b8-ffff80001036b69c: mem_cgroup_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055ccec)
Location: mm/memcontrol.c:7140
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
c055ccec-c055cd94: mem_cgroup_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000045b090)
Location: mm/memcontrol.c:7140
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
c00000000045b090-c00000000045b1a4: mem_cgroup_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000248c98)
Location: mm/memcontrol.c:7140
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffe000248c98-ffffffe000248d60: mem_cgroup_uncharge_swap (STB_GLOBAL)
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
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c0cd0)
Location: mm/memcontrol.c:7140
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff812c0cd0-ffffffff812c0d79: mem_cgroup_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b1d40)
Location: mm/memcontrol.c:7140
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff812b1d40-ffffffff812b1dd3: mem_cgroup_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812beae0)
Location: mm/memcontrol.c:7140
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff812beae0-ffffffff812beb89: mem_cgroup_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mem_cgroup_uncharge_swap(swp_entry_t entry, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cf550)
Location: mm/memcontrol.c:7140
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
  - mm/swapfile.c:put_swap_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
**Symbols:**

```
ffffffff812cf550-ffffffff812cf607: mem_cgroup_uncharge_swap (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int nr_pages</code>
</li>
</ul>
</details>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
