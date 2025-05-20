# Function: <code>page_pool_use_xdp_mem</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void page_pool_use_xdp_mem(struct page_pool *pool, void (*disconnect)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81967aa0)
Location: net/core/page_pool.c:406
Inline: False
```
**Symbols:**

```
ffffffff81967aa0-ffffffff81967abc: page_pool_use_xdp_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void page_pool_use_xdp_mem(struct page_pool *pool, void (*disconnect)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3b290)
Location: net/core/page_pool.c:502
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
```
**Symbols:**

```
ffffffff81a3b290-ffffffff81a3b2f9: page_pool_use_xdp_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void page_pool_use_xdp_mem(struct page_pool *pool, void (*disconnect)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3d9d0)
Location: net/core/page_pool.c:552
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
```
**Symbols:**

```
ffffffff81a3d9d0-ffffffff81a3da39: page_pool_use_xdp_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void page_pool_use_xdp_mem(struct page_pool *pool, void (*disconnect)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a24aa0)
Location: net/core/page_pool.c:585
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_reg_mem_model
```
**Symbols:**

```
ffffffff81a24aa0-ffffffff81a24b09: page_pool_use_xdp_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void page_pool_use_xdp_mem(struct page_pool *pool, void (*disconnect)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81ad95e0)
Location: net/core/page_pool.c:694
Inline: False
```
**Symbols:**

```
ffffffff81ad95e0-ffffffff81ad9649: page_pool_use_xdp_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void page_pool_use_xdp_mem(struct page_pool *pool, void (*disconnect)(void *), struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81c5a890)
Location: net/core/page_pool.c:831
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_reg_mem_model
```
**Symbols:**

```
ffffffff81c5a890-ffffffff81c5a903: page_pool_use_xdp_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void page_pool_use_xdp_mem(struct page_pool *pool, void (*disconnect)(void *), struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e10a00)
Location: net/core/page_pool.c:832
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_reg_mem_model
```
**Symbols:**

```
ffffffff81e10a00-ffffffff81e10a73: page_pool_use_xdp_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void page_pool_use_xdp_mem(struct page_pool *pool, void (*disconnect)(void *), struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e84300)
Location: net/core/page_pool.c:858
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_reg_mem_model
```
**Symbols:**

```
ffffffff81e84300-ffffffff81e84373: page_pool_use_xdp_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void page_pool_use_xdp_mem(struct page_pool *pool, void (*disconnect)(void *), struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81f44ec0)
Location: net/core/page_pool.c:929
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_reg_mem_model
```
**Symbols:**

```
ffffffff81f44ec0-ffffffff81f44f33: page_pool_use_xdp_mem (STB_GLOBAL)
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
void page_pool_use_xdp_mem(struct page_pool *pool, void (*disconnect)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffff800010c0d590)
Location: net/core/page_pool.c:406
Inline: False
```
**Symbols:**

```
ffff800010c0d590-ffff800010c0d5c4: page_pool_use_xdp_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void page_pool_use_xdp_mem(struct page_pool *pool, void (*disconnect)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c0d25760)
Location: net/core/page_pool.c:406
Inline: False
```
**Symbols:**

```
c0d25760-c0d25790: page_pool_use_xdp_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void page_pool_use_xdp_mem(struct page_pool *pool, void (*disconnect)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c000000000cf8d60)
Location: net/core/page_pool.c:406
Inline: False
```
**Symbols:**

```
c000000000cf8d60-c000000000cf8d84: page_pool_use_xdp_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void page_pool_use_xdp_mem(struct page_pool *pool, void (*disconnect)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffe00078a35c)
Location: net/core/page_pool.c:406
Inline: False
```
**Symbols:**

```
ffffffe00078a35c-ffffffe00078a390: page_pool_use_xdp_mem (STB_GLOBAL)
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
void page_pool_use_xdp_mem(struct page_pool *pool, void (*disconnect)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81907a70)
Location: net/core/page_pool.c:406
Inline: False
```
**Symbols:**

```
ffffffff81907a70-ffffffff81907a8c: page_pool_use_xdp_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void page_pool_use_xdp_mem(struct page_pool *pool, void (*disconnect)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff818c1880)
Location: net/core/page_pool.c:406
Inline: False
```
**Symbols:**

```
ffffffff818c1880-ffffffff818c189c: page_pool_use_xdp_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void page_pool_use_xdp_mem(struct page_pool *pool, void (*disconnect)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81958aa0)
Location: net/core/page_pool.c:406
Inline: False
```
**Symbols:**

```
ffffffff81958aa0-ffffffff81958abc: page_pool_use_xdp_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void page_pool_use_xdp_mem(struct page_pool *pool, void (*disconnect)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff8197abe0)
Location: net/core/page_pool.c:406
Inline: False
```
**Symbols:**

```
ffffffff8197abe0-ffffffff8197abfc: page_pool_use_xdp_mem (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xdp_mem_info *mem</code>
</li>
</ul>
</details>
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
