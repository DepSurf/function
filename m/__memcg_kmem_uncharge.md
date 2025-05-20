# Function: <code>__memcg_kmem_uncharge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __memcg_kmem_uncharge(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811ffb40)
Location: mm/memcontrol.c:2438
Inline: False
Direct callers:
  - mm/page_alloc.c:__free_kmem_pages
```
**Symbols:**

```
ffffffff811ffb40-ffffffff811ffbe3: __memcg_kmem_uncharge (STB_GLOBAL)
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
void __memcg_kmem_uncharge(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b5750)
Location: mm/memcontrol.c:2878
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - fs/pipe.c:anon_pipe_buf_steal
```
**Symbols:**

```
ffffffff812b5750-ffffffff812b57e2: __memcg_kmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __memcg_kmem_uncharge(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c7400)
Location: mm/memcontrol.c:3087
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - fs/pipe.c:anon_pipe_buf_steal
```
**Symbols:**

```
ffffffff812c7400-ffffffff812c7492: __memcg_kmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __memcg_kmem_uncharge(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fcc90)
Location: mm/memcontrol.c:2929
Inline: False
Direct callers:
  - mm/slub.c:__free_slab
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
```
**Symbols:**

```
ffffffff812fcc90-ffffffff812fccf1: __memcg_kmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __memcg_kmem_uncharge(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130442d)
Location: mm/memcontrol.c:3109
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_uncharge_page
  - mm/memcontrol.c:obj_cgroup_release
```
**Symbols:**

```
ffffffff81308ef0-ffffffff81308f29: __memcg_kmem_uncharge (STB_GLOBAL)
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
void __memcg_kmem_uncharge(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036a208)
Location: mm/memcontrol.c:3087
Inline: False
Direct callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - fs/pipe.c:anon_pipe_buf_steal
```
**Symbols:**

```
ffff80001036a208-ffff80001036a2a4: __memcg_kmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __memcg_kmem_uncharge(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055b6e8)
Location: mm/memcontrol.c:3087
Inline: False
Direct callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - fs/pipe.c:anon_pipe_buf_steal
```
**Symbols:**

```
c055b6e8-c055b7b4: __memcg_kmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __memcg_kmem_uncharge(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000459110)
Location: mm/memcontrol.c:3087
Inline: False
Direct callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - fs/pipe.c:anon_pipe_buf_steal
```
**Symbols:**

```
c000000000459110-c00000000045924c: __memcg_kmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __memcg_kmem_uncharge(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000247ac2)
Location: mm/memcontrol.c:3087
Inline: False
Direct callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - fs/pipe.c:anon_pipe_buf_steal
```
**Symbols:**

```
ffffffe000247ac2-ffffffe000247b92: __memcg_kmem_uncharge (STB_GLOBAL)
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
void __memcg_kmem_uncharge(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bf9e0)
Location: mm/memcontrol.c:3087
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - fs/pipe.c:anon_pipe_buf_steal
```
**Symbols:**

```
ffffffff812bf9e0-ffffffff812bfa72: __memcg_kmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __memcg_kmem_uncharge(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b0ac0)
Location: mm/memcontrol.c:3087
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - fs/pipe.c:anon_pipe_buf_steal
```
**Symbols:**

```
ffffffff812b0ac0-ffffffff812b0b52: __memcg_kmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __memcg_kmem_uncharge(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bd7f0)
Location: mm/memcontrol.c:3087
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - fs/pipe.c:anon_pipe_buf_steal
```
**Symbols:**

```
ffffffff812bd7f0-ffffffff812bd882: __memcg_kmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __memcg_kmem_uncharge(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ce120)
Location: mm/memcontrol.c:3087
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - fs/pipe.c:anon_pipe_buf_steal
```
**Symbols:**

```
ffffffff812ce120-ffffffff812ce1c2: __memcg_kmem_uncharge (STB_GLOBAL)
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
