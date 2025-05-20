# Function: <code>page_pool_alloc_frag</code>

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
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *page_pool_alloc_frag(struct page_pool *pool, unsigned int *offset, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:560
Inline: False
```
**Symbols:**

```
ffffffff81d378c2-ffffffff81d378e0: page_pool_alloc_frag.cold (STB_LOCAL)
ffffffff81ad93d0-ffffffff81ad95dc: page_pool_alloc_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct page *page_pool_alloc_frag(struct page_pool *pool, unsigned int *offset, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:691
Inline: False
```
**Symbols:**

```
ffffffff81f0427b-ffffffff81f04299: page_pool_alloc_frag.cold (STB_LOCAL)
ffffffff81c5a660-ffffffff81c5a883: page_pool_alloc_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct page *page_pool_alloc_frag(struct page_pool *pool, unsigned int *offset, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:692
Inline: False
```
**Symbols:**

```
ffffffff820ac8b7-ffffffff820ac8d5: page_pool_alloc_frag.cold (STB_LOCAL)
ffffffff81e107c0-ffffffff81e109e3: page_pool_alloc_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct page *page_pool_alloc_frag(struct page_pool *pool, unsigned int *offset, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:718
Inline: False
```
**Symbols:**

```
ffffffff8212dfae-ffffffff8212dfcc: page_pool_alloc_frag.cold (STB_LOCAL)
ffffffff81e84090-ffffffff81e842e7: page_pool_alloc_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct page *page_pool_alloc_frag(struct page_pool *pool, unsigned int *offset, unsigned int size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:793
Inline: False
```
**Symbols:**

```
ffffffff8220fd6a-ffffffff8220fd88: page_pool_alloc_frag.cold (STB_LOCAL)
ffffffff81f44770-ffffffff81f4494f: page_pool_alloc_frag (STB_GLOBAL)
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
