# Function: <code>__page_pool_alloc_page_order</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a24728)
Location: net/core/page_pool.c:208
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In net/core/page_pool.c (ffffffff81ad8da0)
Location: net/core/page_pool.c:228
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In net/core/page_pool.c (ffffffff81c59de1)
Location: net/core/page_pool.c:345
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *__page_pool_alloc_page_order(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e10150)
Location: net/core/page_pool.c:345
Inline: False
Direct callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff81e10150-ffffffff81e10359: __page_pool_alloc_page_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *__page_pool_alloc_page_order(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e839f0)
Location: net/core/page_pool.c:370
Inline: False
Direct callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff81e839f0-ffffffff81e83bfd: __page_pool_alloc_page_order (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct page *__page_pool_alloc_page_order(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:426
Inline: False
Direct callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff81f43e10-ffffffff81f4403b: __page_pool_alloc_page_order (STB_LOCAL)
ffffffff8220fd3a-ffffffff8220fd4f: __page_pool_alloc_page_order.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
