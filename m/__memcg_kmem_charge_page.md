# Function: <code>__memcg_kmem_charge_page</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __memcg_kmem_charge_page(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fcd00)
Location: mm/memcontrol.c:2947
Inline: False
Direct callers:
  - kernel/fork.c:memcg_charge_kernel_stack
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff812fcd00-ffffffff812fce6d: __memcg_kmem_charge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __memcg_kmem_charge_page(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81308f30)
Location: mm/memcontrol.c:3125
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff81308f30-ffffffff8130911d: __memcg_kmem_charge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __memcg_kmem_charge_page(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130f540)
Location: mm/memcontrol.c:2969
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
  - mm/page_alloc.c:__alloc_pages
```
**Symbols:**

```
ffffffff8130f540-ffffffff8130f773: __memcg_kmem_charge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __memcg_kmem_charge_page(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:3037
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
  - mm/page_alloc.c:__alloc_pages
```
**Symbols:**

```
ffffffff81cc2b51-ffffffff81cc2b6a: __memcg_kmem_charge_page.cold (STB_LOCAL)
ffffffff8135a430-ffffffff8135a66d: __memcg_kmem_charge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __memcg_kmem_charge_page(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:3018
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages
```
**Symbols:**

```
ffffffff81e750cd-ffffffff81e750e6: __memcg_kmem_charge_page.cold (STB_LOCAL)
ffffffff813d39d0-ffffffff813d3c7a: __memcg_kmem_charge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __memcg_kmem_charge_page(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:3118
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages
```
**Symbols:**

```
ffffffff82068255-ffffffff8206826e: __memcg_kmem_charge_page.cold (STB_LOCAL)
ffffffff81459360-ffffffff8145960a: __memcg_kmem_charge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __memcg_kmem_charge_page(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:3128
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages
```
**Symbols:**

```
ffffffff820e7b3a-ffffffff820e7b53: __memcg_kmem_charge_page.cold (STB_LOCAL)
ffffffff8148eff0-ffffffff8148f29a: __memcg_kmem_charge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __memcg_kmem_charge_page(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:3320
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages
```
**Symbols:**

```
ffffffff821c4863-ffffffff821c4882: __memcg_kmem_charge_page.cold (STB_LOCAL)
ffffffff814be8e0-ffffffff814beade: __memcg_kmem_charge_page (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
