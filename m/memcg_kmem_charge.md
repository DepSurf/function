# Function: <code>memcg_kmem_charge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81195021)
Location: include/linux/memcontrol.h:791
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_kmem_pages
  - mm/page_alloc.c:alloc_kmem_pages_node
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int memcg_kmem_charge(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812237c0)
Location: mm/memcontrol.c:2344
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff812237c0-ffffffff8122388e: memcg_kmem_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int memcg_kmem_charge(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81235cb0)
Location: mm/memcontrol.c:2317
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff81235cb0-ffffffff81235d7e: memcg_kmem_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int memcg_kmem_charge(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81241720)
Location: mm/memcontrol.c:2326
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff81241720-ffffffff812417ee: memcg_kmem_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int memcg_kmem_charge(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81261460)
Location: mm/memcontrol.c:2353
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff81261460-ffffffff81261533: memcg_kmem_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int memcg_kmem_charge(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81285470)
Location: mm/memcontrol.c:2340
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff81285470-ffffffff8128553f: memcg_kmem_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int memcg_kmem_charge(struct page *page, gfp_t gfp, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129a2f0)
Location: mm/memcontrol.c:2614
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff8129a2f0-ffffffff8129a43d: memcg_kmem_charge (STB_GLOBAL)
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
In kernel/fork.c (ffffffff810983a6)
Location: include/linux/memcontrol.h:1316
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff8109e97c)
Location: include/linux/memcontrol.h:1402
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812d9727)
Location: include/linux/memcontrol.h:1388
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
</details>
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
In kernel/fork.c (ffff8000100f30a8)
Location: include/linux/memcontrol.h:1402
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109829c)
Location: include/linux/memcontrol.h:1402
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff81086cf6)
Location: include/linux/memcontrol.h:1402
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff8109824c)
Location: include/linux/memcontrol.h:1402
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff8109fe43)
Location: include/linux/memcontrol.h:1402
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
