# Function: <code>memcg_kmem_charge_memcg</code>

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
int memcg_kmem_charge_memcg(struct page *page, gfp_t gfp, int order, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81223720)
Location: mm/memcontrol.c:2314
Inline: False
Direct callers:
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/memcontrol.c:memcg_kmem_charge
```
**Symbols:**

```
ffffffff81223720-ffffffff812237b8: memcg_kmem_charge_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int memcg_kmem_charge_memcg(struct page *page, gfp_t gfp, int order, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81235c10)
Location: mm/memcontrol.c:2287
Inline: False
Direct callers:
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/memcontrol.c:memcg_kmem_charge
```
**Symbols:**

```
ffffffff81235c10-ffffffff81235ca8: memcg_kmem_charge_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int memcg_kmem_charge_memcg(struct page *page, gfp_t gfp, int order, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81241670)
Location: mm/memcontrol.c:2296
Inline: False
Direct callers:
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/memcontrol.c:memcg_kmem_charge
```
**Symbols:**

```
ffffffff81241670-ffffffff81241711: memcg_kmem_charge_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int memcg_kmem_charge_memcg(struct page *page, gfp_t gfp, int order, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812613b0)
Location: mm/memcontrol.c:2323
Inline: False
Direct callers:
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/memcontrol.c:memcg_kmem_charge
```
**Symbols:**

```
ffffffff812613b0-ffffffff81261451: memcg_kmem_charge_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int memcg_kmem_charge_memcg(struct page *page, gfp_t gfp, int order, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812853c0)
Location: mm/memcontrol.c:2310
Inline: False
Direct callers:
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/memcontrol.c:memcg_kmem_charge
```
**Symbols:**

```
ffffffff812853c0-ffffffff81285461: memcg_kmem_charge_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int memcg_kmem_charge_memcg(struct page *page, gfp_t gfp, int order, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129a240)
Location: mm/memcontrol.c:2584
Inline: False
Direct callers:
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/memcontrol.c:memcg_kmem_charge
```
**Symbols:**

```
ffffffff8129a240-ffffffff8129a2e1: memcg_kmem_charge_memcg (STB_GLOBAL)
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
In mm/slub.c (ffffffff81293e6e)
Location: include/linux/memcontrol.h:1329
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
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
In mm/slub.c (ffffffff812a3bde)
Location: include/linux/memcontrol.h:1415
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
</details>
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
In mm/slub.c (ffff80001034588c)
Location: include/linux/memcontrol.h:1415
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
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
In mm/slub.c (c0549654)
Location: include/linux/memcontrol.h:1415
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
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
In mm/slub.c (c000000000421de4)
Location: include/linux/memcontrol.h:1415
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
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
In mm/slub.c (ffffffe0002380a2)
Location: include/linux/memcontrol.h:1415
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
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
In mm/slub.c (ffffffff8129c1be)
Location: include/linux/memcontrol.h:1415
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
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
In mm/slub.c (ffffffff8128dd7e)
Location: include/linux/memcontrol.h:1415
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
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
In mm/slub.c (ffffffff81299fce)
Location: include/linux/memcontrol.h:1415
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
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
In mm/slub.c (ffffffff812a9e0f)
Location: include/linux/memcontrol.h:1415
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
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
</ul>
