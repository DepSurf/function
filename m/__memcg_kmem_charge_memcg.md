# Function: <code>__memcg_kmem_charge_memcg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __memcg_kmem_charge_memcg(struct page *page, gfp_t gfp, int order, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811ff9f0)
Location: mm/memcontrol.c:2403
Inline: False
Direct callers:
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/memcontrol.c:__memcg_kmem_charge
```
**Symbols:**

```
ffffffff811ff9f0-ffffffff811ffaae: __memcg_kmem_charge_memcg (STB_GLOBAL)
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
int __memcg_kmem_charge_memcg(struct page *page, gfp_t gfp, int order, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b54e0)
Location: mm/memcontrol.c:2811
Inline: False
Direct callers:
  - mm/slub.c:alloc_slab_page
  - mm/memcontrol.c:__memcg_kmem_charge
```
**Symbols:**

```
ffffffff812b54e0-ffffffff812b5585: __memcg_kmem_charge_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __memcg_kmem_charge_memcg(struct page *page, gfp_t gfp, int order, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c7180)
Location: mm/memcontrol.c:3010
Inline: False
Direct callers:
  - mm/slub.c:alloc_slab_page
  - mm/memcontrol.c:__memcg_kmem_charge
```
**Symbols:**

```
ffffffff812c7180-ffffffff812c723f: __memcg_kmem_charge_memcg (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int __memcg_kmem_charge_memcg(struct page *page, gfp_t gfp, int order, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010369f68)
Location: mm/memcontrol.c:3010
Inline: False
Direct callers:
  - mm/slub.c:alloc_slab_page
  - mm/memcontrol.c:__memcg_kmem_charge
```
**Symbols:**

```
ffff800010369f68-ffff80001036a064: __memcg_kmem_charge_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __memcg_kmem_charge_memcg(struct page *page, gfp_t gfp, int order, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055b370)
Location: mm/memcontrol.c:3010
Inline: False
Direct callers:
  - mm/slub.c:alloc_slab_page
  - mm/memcontrol.c:__memcg_kmem_charge
```
**Symbols:**

```
c055b370-c055b45c: __memcg_kmem_charge_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __memcg_kmem_charge_memcg(struct page *page, gfp_t gfp, int order, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000458ca0)
Location: mm/memcontrol.c:3010
Inline: False
Direct callers:
  - mm/slub.c:alloc_slab_page
  - mm/memcontrol.c:__memcg_kmem_charge
```
**Symbols:**

```
c000000000458ca0-c000000000458dcc: __memcg_kmem_charge_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __memcg_kmem_charge_memcg(struct page *page, gfp_t gfp, int order, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe0002477fc)
Location: mm/memcontrol.c:3010
Inline: False
Direct callers:
  - mm/slub.c:alloc_slab_page
  - mm/memcontrol.c:__memcg_kmem_charge
```
**Symbols:**

```
ffffffe0002477fc-ffffffe0002478ac: __memcg_kmem_charge_memcg (STB_GLOBAL)
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
int __memcg_kmem_charge_memcg(struct page *page, gfp_t gfp, int order, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bf760)
Location: mm/memcontrol.c:3010
Inline: False
Direct callers:
  - mm/slub.c:alloc_slab_page
  - mm/memcontrol.c:__memcg_kmem_charge
```
**Symbols:**

```
ffffffff812bf760-ffffffff812bf81f: __memcg_kmem_charge_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __memcg_kmem_charge_memcg(struct page *page, gfp_t gfp, int order, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b0840)
Location: mm/memcontrol.c:3010
Inline: False
Direct callers:
  - mm/slub.c:alloc_slab_page
  - mm/memcontrol.c:__memcg_kmem_charge
```
**Symbols:**

```
ffffffff812b0840-ffffffff812b08ff: __memcg_kmem_charge_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __memcg_kmem_charge_memcg(struct page *page, gfp_t gfp, int order, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bd570)
Location: mm/memcontrol.c:3010
Inline: False
Direct callers:
  - mm/slub.c:alloc_slab_page
  - mm/memcontrol.c:__memcg_kmem_charge
```
**Symbols:**

```
ffffffff812bd570-ffffffff812bd62f: __memcg_kmem_charge_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __memcg_kmem_charge_memcg(struct page *page, gfp_t gfp, int order, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cde50)
Location: mm/memcontrol.c:3010
Inline: False
Direct callers:
  - mm/slub.c:alloc_slab_page
  - mm/memcontrol.c:__memcg_kmem_charge
```
**Symbols:**

```
ffffffff812cde50-ffffffff812cdf0f: __memcg_kmem_charge_memcg (STB_GLOBAL)
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
