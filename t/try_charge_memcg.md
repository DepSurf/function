# Function: <code>try_charge_memcg</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
int try_charge_memcg(struct mem_cgroup *memcg, gfp_t gfp_mask, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81358330)
Location: mm/memcontrol.c:2579
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:obj_cgroup_charge_pages
```
**Symbols:**

```
ffffffff81358330-ffffffff81358a70: try_charge_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int try_charge_memcg(struct mem_cgroup *memcg, gfp_t gfp_mask, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d21f0)
Location: mm/memcontrol.c:2570
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:__memcg_kmem_charge_page
```
**Symbols:**

```
ffffffff813d21f0-ffffffff813d2927: try_charge_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int try_charge_memcg(struct mem_cgroup *memcg, gfp_t gfp_mask, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81457930)
Location: mm/memcontrol.c:2631
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:__memcg_kmem_charge_page
```
**Symbols:**

```
ffffffff81457930-ffffffff814580e2: try_charge_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int try_charge_memcg(struct mem_cgroup *memcg, gfp_t gfp_mask, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148d660)
Location: mm/memcontrol.c:2641
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:__memcg_kmem_charge_page
```
**Symbols:**

```
ffffffff8148d660-ffffffff8148de26: try_charge_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int try_charge_memcg(struct mem_cgroup *memcg, gfp_t gfp_mask, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bcfe0)
Location: mm/memcontrol.c:2728
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
  - mm/memcontrol.c:mem_cgroup_hugetlb_try_charge
  - mm/memcontrol.c:__mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:__memcg_kmem_charge_page
```
**Symbols:**

```
ffffffff814bcfe0-ffffffff814bd7a8: try_charge_memcg (STB_LOCAL)
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
