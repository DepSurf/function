# Function: <code>mem_cgroup_try_charge_swap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mem_cgroup_try_charge_swap(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81224560)
Location: mm/memcontrol.c:5905
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff81224560-ffffffff81224624: mem_cgroup_try_charge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mem_cgroup_try_charge_swap(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81236b30)
Location: mm/memcontrol.c:5905
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff81236b30-ffffffff81236bf4: mem_cgroup_try_charge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mem_cgroup_try_charge_swap(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812425c0)
Location: mm/memcontrol.c:5967
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff812425c0-ffffffff812426bc: mem_cgroup_try_charge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mem_cgroup_try_charge_swap(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81262400)
Location: mm/memcontrol.c:6073
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff81262400-ffffffff812624fc: mem_cgroup_try_charge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mem_cgroup_try_charge_swap(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812864c0)
Location: mm/memcontrol.c:6141
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff812864c0-ffffffff81286668: mem_cgroup_try_charge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mem_cgroup_try_charge_swap(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129b420)
Location: mm/memcontrol.c:6472
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff8129b420-ffffffff8129b5d8: mem_cgroup_try_charge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mem_cgroup_try_charge_swap(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b6660)
Location: mm/memcontrol.c:6764
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff812b6660-ffffffff812b6813: mem_cgroup_try_charge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mem_cgroup_try_charge_swap(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c8530)
Location: mm/memcontrol.c:7094
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff812c8530-ffffffff812c86e3: mem_cgroup_try_charge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mem_cgroup_try_charge_swap(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fddd0)
Location: mm/memcontrol.c:6951
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff812fddd0-ffffffff812fdfc0: mem_cgroup_try_charge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mem_cgroup_try_charge_swap(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130a260)
Location: mm/memcontrol.c:7202
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff8130a260-ffffffff8130a44a: mem_cgroup_try_charge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mem_cgroup_try_charge_swap(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81310ae0)
Location: mm/memcontrol.c:7071
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff81310ae0-ffffffff81310ce7: mem_cgroup_try_charge_swap (STB_GLOBAL)
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
In mm/swap_slots.c (ffffffff813186c7)
Location: include/linux/swap.h:740
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
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
In mm/swap_slots.c (ffffffff81383d75)
Location: include/linux/swap.h:654
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
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
In mm/swap_slots.c (ffffffff8140172e)
Location: include/linux/swap.h:664
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
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
In mm/swap_slots.c (ffffffff8143460e)
Location: include/linux/swap.h:655
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
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
In mm/swap_slots.c (ffffffff8146da08)
Location: include/linux/swap.h:646
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
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
int mem_cgroup_try_charge_swap(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036b440)
Location: mm/memcontrol.c:7094
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffff80001036b440-ffff80001036b5b4: mem_cgroup_try_charge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mem_cgroup_try_charge_swap(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055cb30)
Location: mm/memcontrol.c:7094
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
c055cb30-c055ccec: mem_cgroup_try_charge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mem_cgroup_try_charge_swap(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000045ae00)
Location: mm/memcontrol.c:7094
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
c00000000045ae00-c00000000045b090: mem_cgroup_try_charge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mem_cgroup_try_charge_swap(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000248b50)
Location: mm/memcontrol.c:7094
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffe000248b50-ffffffe000248c98: mem_cgroup_try_charge_swap (STB_GLOBAL)
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
int mem_cgroup_try_charge_swap(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c0b10)
Location: mm/memcontrol.c:7094
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff812c0b10-ffffffff812c0cc3: mem_cgroup_try_charge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mem_cgroup_try_charge_swap(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b1ba0)
Location: mm/memcontrol.c:7094
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff812b1ba0-ffffffff812b1d3b: mem_cgroup_try_charge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mem_cgroup_try_charge_swap(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812be920)
Location: mm/memcontrol.c:7094
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff812be920-ffffffff812bead3: mem_cgroup_try_charge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mem_cgroup_try_charge_swap(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cf390)
Location: mm/memcontrol.c:7094
Inline: False
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff812cf390-ffffffff812cf543: mem_cgroup_try_charge_swap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
