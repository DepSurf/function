# Function: <code>__page_pool_alloc_pages_slow</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *__page_pool_alloc_pages_slow(struct page_pool *pool, gfp_t _gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff818bd6d0)
Location: net/core/page_pool.c:111
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
**Symbols:**

```
ffffffff818bd6d0-ffffffff818bd813: __page_pool_alloc_pages_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *__page_pool_alloc_pages_slow(struct page_pool *pool, gfp_t _gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff818e4ab0)
Location: net/core/page_pool.c:111
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
**Symbols:**

```
ffffffff818e4ab0-ffffffff818e4bd1: __page_pool_alloc_pages_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *__page_pool_alloc_pages_slow(struct page_pool *pool, gfp_t _gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff819342a0)
Location: net/core/page_pool.c:124
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
**Symbols:**

```
ffffffff819342a0-ffffffff8193442a: __page_pool_alloc_pages_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *__page_pool_alloc_pages_slow(struct page_pool *pool, gfp_t _gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81966ed0)
Location: net/core/page_pool.c:120
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
**Symbols:**

```
ffffffff81966ed0-ffffffff81967060: __page_pool_alloc_pages_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *__page_pool_alloc_pages_slow(struct page_pool *pool, gfp_t _gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3a5f0)
Location: net/core/page_pool.c:183
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
**Symbols:**

```
ffffffff81a3a5f0-ffffffff81a3a794: __page_pool_alloc_pages_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *__page_pool_alloc_pages_slow(struct page_pool *pool, gfp_t _gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3cb10)
Location: net/core/page_pool.c:185
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
**Symbols:**

```
ffffffff81a3cb10-ffffffff81a3cc6f: __page_pool_alloc_pages_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *__page_pool_alloc_pages_slow(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a24540)
Location: net/core/page_pool.c:232
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
**Symbols:**

```
ffffffff81a24540-ffffffff81a247e5: __page_pool_alloc_pages_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *__page_pool_alloc_pages_slow(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81ad8b80)
Location: net/core/page_pool.c:254
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_alloc_frag
```
**Symbols:**

```
ffffffff81ad8b80-ffffffff81ad8ed2: __page_pool_alloc_pages_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *__page_pool_alloc_pages_slow(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81c59b90)
Location: net/core/page_pool.c:372
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_alloc_frag
```
**Symbols:**

```
ffffffff81c59b90-ffffffff81c5a04f: __page_pool_alloc_pages_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *__page_pool_alloc_pages_slow(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e10370)
Location: net/core/page_pool.c:372
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_alloc_frag
```
**Symbols:**

```
ffffffff81e10370-ffffffff81e1071b: __page_pool_alloc_pages_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *__page_pool_alloc_pages_slow(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e83c10)
Location: net/core/page_pool.c:397
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_alloc_frag
```
**Symbols:**

```
ffffffff81e83c10-ffffffff81e83fdb: __page_pool_alloc_pages_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct page *__page_pool_alloc_pages_slow(struct page_pool *pool, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (0)
Location: net/core/page_pool.c:453
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_alloc_frag
```
**Symbols:**

```
ffffffff81f442e0-ffffffff81f446c0: __page_pool_alloc_pages_slow (STB_LOCAL)
ffffffff8220fd4f-ffffffff8220fd6a: __page_pool_alloc_pages_slow.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct page *__page_pool_alloc_pages_slow(struct page_pool *pool, gfp_t _gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffff800010c0cec8)
Location: net/core/page_pool.c:120
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
**Symbols:**

```
ffff800010c0cec8-ffff800010c0d094: __page_pool_alloc_pages_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *__page_pool_alloc_pages_slow(struct page_pool *pool, gfp_t _gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c0d24bd8)
Location: net/core/page_pool.c:120
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
**Symbols:**

```
c0d24bd8-c0d24da4: __page_pool_alloc_pages_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *__page_pool_alloc_pages_slow(struct page_pool *pool, gfp_t _gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c000000000cf7b70)
Location: net/core/page_pool.c:120
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
**Symbols:**

```
c000000000cf7b70-c000000000cf7ddc: __page_pool_alloc_pages_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *__page_pool_alloc_pages_slow(struct page_pool *pool, gfp_t _gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffe000789976)
Location: net/core/page_pool.c:120
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
**Symbols:**

```
ffffffe000789976-ffffffe000789ab4: __page_pool_alloc_pages_slow (STB_LOCAL)
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
struct page *__page_pool_alloc_pages_slow(struct page_pool *pool, gfp_t _gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81906ea0)
Location: net/core/page_pool.c:120
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
**Symbols:**

```
ffffffff81906ea0-ffffffff81907030: __page_pool_alloc_pages_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *__page_pool_alloc_pages_slow(struct page_pool *pool, gfp_t _gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff818c0cb0)
Location: net/core/page_pool.c:120
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
**Symbols:**

```
ffffffff818c0cb0-ffffffff818c0e40: __page_pool_alloc_pages_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *__page_pool_alloc_pages_slow(struct page_pool *pool, gfp_t _gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81957ed0)
Location: net/core/page_pool.c:120
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
**Symbols:**

```
ffffffff81957ed0-ffffffff81958060: __page_pool_alloc_pages_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *__page_pool_alloc_pages_slow(struct page_pool *pool, gfp_t _gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81979fc0)
Location: net/core/page_pool.c:120
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_alloc_pages
```
**Symbols:**

```
ffffffff81979fc0-ffffffff8197a162: __page_pool_alloc_pages_slow (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t _gfp</code>
</li>
</ul>
</details>
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
