# Function: <code>__memcg_kmem_uncharge_page</code>

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
void __memcg_kmem_uncharge_page(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fce70)
Location: mm/memcontrol.c:2972
Inline: False
Direct callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - fs/pipe.c:anon_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff812fce70-ffffffff812fcf02: __memcg_kmem_uncharge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __memcg_kmem_uncharge_page(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81309120)
Location: mm/memcontrol.c:3148
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
  - fs/pipe.c:anon_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff81309120-ffffffff813091b3: __memcg_kmem_uncharge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __memcg_kmem_uncharge_page(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130f780)
Location: mm/memcontrol.c:2992
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
  - fs/pipe.c:anon_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff8130f780-ffffffff8130f7f2: __memcg_kmem_uncharge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __memcg_kmem_uncharge_page(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:3060
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
  - fs/pipe.c:anon_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff81cc2b6a-ffffffff81cc2b89: __memcg_kmem_uncharge_page.cold (STB_LOCAL)
ffffffff8135a670-ffffffff8135a6f5: __memcg_kmem_uncharge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __memcg_kmem_uncharge_page(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:3041
Inline: False
Direct callers:
  - kernel/fork.c:exit_task_stack_account
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
  - fs/pipe.c:anon_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff81e750e6-ffffffff81e75105: __memcg_kmem_uncharge_page.cold (STB_LOCAL)
ffffffff813d3c80-ffffffff813d3d56: __memcg_kmem_uncharge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __memcg_kmem_uncharge_page(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:3141
Inline: False
Direct callers:
  - kernel/fork.c:exit_task_stack_account
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:free_pcp_prepare
  - fs/pipe.c:anon_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff8206826e-ffffffff8206828d: __memcg_kmem_uncharge_page.cold (STB_LOCAL)
ffffffff81459620-ffffffff814596f6: __memcg_kmem_uncharge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __memcg_kmem_uncharge_page(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:3151
Inline: False
Direct callers:
  - kernel/fork.c:exit_task_stack_account
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - fs/pipe.c:anon_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff820e7b53-ffffffff820e7b72: __memcg_kmem_uncharge_page.cold (STB_LOCAL)
ffffffff8148f2b0-ffffffff8148f386: __memcg_kmem_uncharge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __memcg_kmem_uncharge_page(struct page *page, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:3343
Inline: False
Direct callers:
  - kernel/fork.c:exit_task_stack_account
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
  - fs/pipe.c:anon_pipe_buf_try_steal
```
**Symbols:**

```
ffffffff821c4882-ffffffff821c48a1: __memcg_kmem_uncharge_page.cold (STB_LOCAL)
ffffffff814beaf0-ffffffff814bebc3: __memcg_kmem_uncharge_page (STB_GLOBAL)
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
