# Function: <code>__memcg_kmem_charge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __memcg_kmem_charge(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811ffab0)
Location: mm/memcontrol.c:2427
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_kmem_pages
  - mm/page_alloc.c:alloc_kmem_pages_node
```
**Symbols:**

```
ffffffff811ffab0-ffffffff811ffb3c: __memcg_kmem_charge (STB_GLOBAL)
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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __memcg_kmem_charge(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b5590)
Location: mm/memcontrol.c:2838
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff812b5590-ffffffff812b56da: __memcg_kmem_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __memcg_kmem_charge(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c7240)
Location: mm/memcontrol.c:3047
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff812c7240-ffffffff812c738a: __memcg_kmem_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __memcg_kmem_charge(struct mem_cgroup *memcg, gfp_t gfp, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fcbd0)
Location: mm/memcontrol.c:2896
Inline: True
Direct callers:
  - mm/slub.c:alloc_slab_page
  - mm/memcontrol.c:__memcg_kmem_charge_page
```
**Symbols:**

```
ffffffff812fcbd0-ffffffff812fcc81: __memcg_kmem_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __memcg_kmem_charge(struct mem_cgroup *memcg, gfp_t gfp, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81308e00)
Location: mm/memcontrol.c:3076
Inline: True
Direct callers:
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:__memcg_kmem_charge_page
```
**Symbols:**

```
ffffffff81308e00-ffffffff81308ee4: __memcg_kmem_charge (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __memcg_kmem_charge(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036a068)
Location: mm/memcontrol.c:3047
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffff80001036a068-ffff80001036a198: __memcg_kmem_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __memcg_kmem_charge(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055b45c)
Location: mm/memcontrol.c:3047
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
c055b45c-c055b670: __memcg_kmem_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __memcg_kmem_charge(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000458dd0)
Location: mm/memcontrol.c:3047
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
c000000000458dd0-c000000000459054: __memcg_kmem_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __memcg_kmem_charge(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe0002478ac)
Location: mm/memcontrol.c:3047
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffe0002478ac-ffffffe000247a26: __memcg_kmem_charge (STB_GLOBAL)
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
int __memcg_kmem_charge(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bf820)
Location: mm/memcontrol.c:3047
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff812bf820-ffffffff812bf96a: __memcg_kmem_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __memcg_kmem_charge(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b0900)
Location: mm/memcontrol.c:3047
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff812b0900-ffffffff812b0a4a: __memcg_kmem_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __memcg_kmem_charge(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bd630)
Location: mm/memcontrol.c:3047
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff812bd630-ffffffff812bd77a: __memcg_kmem_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __memcg_kmem_charge(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cdf10)
Location: mm/memcontrol.c:3047
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff812cdf10-ffffffff812ce0a3: __memcg_kmem_charge (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mem_cgroup *memcg</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int nr_pages</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
<li>
<b>Param removed. </b>
<code>int order</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
