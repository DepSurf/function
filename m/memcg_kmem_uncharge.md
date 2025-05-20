# Function: <code>memcg_kmem_uncharge</code>

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
In mm/page_alloc.c (ffffffff811950a2)
Location: include/linux/memcontrol.h:804
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_kmem_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void memcg_kmem_uncharge(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81223890)
Location: mm/memcontrol.c:2366
Inline: False
Direct callers:
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/slub.c:__free_slab
  - fs/pipe.c:anon_pipe_buf_steal
```
**Symbols:**

```
ffffffff81223890-ffffffff8122394b: memcg_kmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void memcg_kmem_uncharge(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81235d80)
Location: mm/memcontrol.c:2339
Inline: False
Direct callers:
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/slub.c:__free_slab
  - fs/pipe.c:anon_pipe_buf_steal
```
**Symbols:**

```
ffffffff81235d80-ffffffff81235e3b: memcg_kmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void memcg_kmem_uncharge(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812417f0)
Location: mm/memcontrol.c:2348
Inline: False
Direct callers:
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/slub.c:__free_slab
  - fs/pipe.c:anon_pipe_buf_steal
```
**Symbols:**

```
ffffffff812417f0-ffffffff812418a4: memcg_kmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void memcg_kmem_uncharge(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81261540)
Location: mm/memcontrol.c:2375
Inline: False
Direct callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/slub.c:__free_slab
  - fs/pipe.c:anon_pipe_buf_steal
```
**Symbols:**

```
ffffffff81261540-ffffffff812615f9: memcg_kmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void memcg_kmem_uncharge(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81285540)
Location: mm/memcontrol.c:2362
Inline: False
Direct callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/slub.c:__free_slab
  - fs/pipe.c:anon_pipe_buf_steal
```
**Symbols:**

```
ffffffff81285540-ffffffff81285606: memcg_kmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void memcg_kmem_uncharge(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129a440)
Location: mm/memcontrol.c:2636
Inline: False
Direct callers:
  - kernel/fork.c:put_task_stack
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/slub.c:__free_slab
  - fs/pipe.c:anon_pipe_buf_steal
```
**Symbols:**

```
ffffffff8129a440-ffffffff8129a506: memcg_kmem_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81098bd8)
Location: include/linux/memcontrol.h:1323
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
```
In fs/pipe.c (ffffffff812d576c)
Location: include/linux/memcontrol.h:1323
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109f193)
Location: include/linux/memcontrol.h:1409
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
```
In fs/pipe.c (ffffffff812e72dc)
Location: include/linux/memcontrol.h:1409
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
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
In mm/slub.c (ffffffff812da3cd)
Location: include/linux/memcontrol.h:1396
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f1920)
Location: include/linux/memcontrol.h:1409
Inline: True
```
```
In fs/pipe.c (ffff80001038fb90)
Location: include/linux/memcontrol.h:1409
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
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
In fs/pipe.c (c05767e8)
Location: include/linux/memcontrol.h:1409
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
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
In fs/pipe.c (c000000000487870)
Location: include/linux/memcontrol.h:1409
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
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
In fs/pipe.c (ffffffe00025f7b2)
Location: include/linux/memcontrol.h:1409
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81098ab3)
Location: include/linux/memcontrol.h:1409
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
```
In fs/pipe.c (ffffffff812df8bc)
Location: include/linux/memcontrol.h:1409
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81087503)
Location: include/linux/memcontrol.h:1409
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
```
In fs/pipe.c (ffffffff812d04fc)
Location: include/linux/memcontrol.h:1409
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81098a63)
Location: include/linux/memcontrol.h:1409
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
```
In fs/pipe.c (ffffffff812dd6cc)
Location: include/linux/memcontrol.h:1409
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0681)
Location: include/linux/memcontrol.h:1409
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
```
In fs/pipe.c (ffffffff812ee64c)
Location: include/linux/memcontrol.h:1409
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_steal
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
