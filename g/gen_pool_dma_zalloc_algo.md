# Function: <code>gen_pool_dma_zalloc_algo</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_algo(struct gen_pool *pool, size_t size, dma_addr_t *dma, genpool_algo_t algo, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81516dc0)
Location: lib/genalloc.c:438
Inline: False
Direct callers:
  - lib/genalloc.c:gen_pool_dma_zalloc_align
  - lib/genalloc.c:gen_pool_dma_zalloc
```
**Symbols:**

```
ffffffff81516dc0-ffffffff81516ded: gen_pool_dma_zalloc_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_algo(struct gen_pool *pool, size_t size, dma_addr_t *dma, genpool_algo_t algo, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81537800)
Location: lib/genalloc.c:438
Inline: False
Direct callers:
  - lib/genalloc.c:gen_pool_dma_zalloc_align
  - lib/genalloc.c:gen_pool_dma_zalloc
```
**Symbols:**

```
ffffffff81537800-ffffffff8153782d: gen_pool_dma_zalloc_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *gen_pool_dma_zalloc_algo(struct gen_pool *pool, size_t size, dma_addr_t *dma, genpool_algo_t algo, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8159c233)
Location: lib/genalloc.c:438
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_dma_zalloc_align
  - lib/genalloc.c:gen_pool_dma_zalloc
```
**Symbols:**

```
ffffffff8159c0b0-ffffffff8159c0df: gen_pool_dma_zalloc_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *gen_pool_dma_zalloc_algo(struct gen_pool *pool, size_t size, dma_addr_t *dma, genpool_algo_t algo, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff815b7c83)
Location: lib/genalloc.c:439
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_dma_zalloc_align
  - lib/genalloc.c:gen_pool_dma_zalloc
```
**Symbols:**

```
ffffffff815b7b00-ffffffff815b7b2f: gen_pool_dma_zalloc_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *gen_pool_dma_zalloc_algo(struct gen_pool *pool, size_t size, dma_addr_t *dma, genpool_algo_t algo, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff815c2af3)
Location: lib/genalloc.c:440
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_dma_zalloc_align
  - lib/genalloc.c:gen_pool_dma_zalloc
```
**Symbols:**

```
ffffffff815c2970-ffffffff815c299f: gen_pool_dma_zalloc_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *gen_pool_dma_zalloc_algo(struct gen_pool *pool, size_t size, dma_addr_t *dma, genpool_algo_t algo, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8162aa63)
Location: lib/genalloc.c:440
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_dma_zalloc_align
  - lib/genalloc.c:gen_pool_dma_zalloc
```
**Symbols:**

```
ffffffff8162a8e0-ffffffff8162a90f: gen_pool_dma_zalloc_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *gen_pool_dma_zalloc_algo(struct gen_pool *pool, size_t size, dma_addr_t *dma, genpool_algo_t algo, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff816fbf42)
Location: lib/genalloc.c:440
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_dma_zalloc_align
  - lib/genalloc.c:gen_pool_dma_zalloc
```
**Symbols:**

```
ffffffff816fbdb0-ffffffff816fbded: gen_pool_dma_zalloc_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *gen_pool_dma_zalloc_algo(struct gen_pool *pool, size_t size, dma_addr_t *dma, genpool_algo_t algo, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff817eec42)
Location: lib/genalloc.c:440
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_dma_zalloc_align
  - lib/genalloc.c:gen_pool_dma_zalloc
```
**Symbols:**

```
ffffffff817eea90-ffffffff817eeacd: gen_pool_dma_zalloc_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_algo(struct gen_pool *pool, size_t size, dma_addr_t *dma, genpool_algo_t algo, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8182ee40)
Location: lib/genalloc.c:438
Inline: False
Direct callers:
  - lib/genalloc.c:gen_pool_dma_zalloc_align
  - lib/genalloc.c:gen_pool_dma_zalloc
```
**Symbols:**

```
ffffffff8182ee40-ffffffff8182ee7d: gen_pool_dma_zalloc_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_algo(struct gen_pool *pool, size_t size, dma_addr_t *dma, genpool_algo_t algo, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81880b10)
Location: lib/genalloc.c:440
Inline: False
Direct callers:
  - lib/genalloc.c:gen_pool_dma_zalloc_align
  - lib/genalloc.c:gen_pool_dma_zalloc
```
**Symbols:**

```
ffffffff81880b10-ffffffff81880b4d: gen_pool_dma_zalloc_algo (STB_GLOBAL)
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
void *gen_pool_dma_zalloc_algo(struct gen_pool *pool, size_t size, dma_addr_t *dma, genpool_algo_t algo, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffff8000106447c0)
Location: lib/genalloc.c:438
Inline: False
Direct callers:
  - lib/genalloc.c:gen_pool_dma_zalloc_align
  - lib/genalloc.c:gen_pool_dma_zalloc
```
**Symbols:**

```
ffff8000106447c0-ffff8000106447f8: gen_pool_dma_zalloc_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_algo(struct gen_pool *pool, size_t size, dma_addr_t *dma, genpool_algo_t algo, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (c07eb0ac)
Location: lib/genalloc.c:438
Inline: False
Direct callers:
  - lib/genalloc.c:gen_pool_dma_zalloc_align
  - lib/genalloc.c:gen_pool_dma_zalloc
```
**Symbols:**

```
c07eb0ac-c07eb0ec: gen_pool_dma_zalloc_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_algo(struct gen_pool *pool, size_t size, dma_addr_t *dma, genpool_algo_t algo, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (c0000000007f0020)
Location: lib/genalloc.c:438
Inline: False
Direct callers:
  - lib/genalloc.c:gen_pool_dma_zalloc_align
  - lib/genalloc.c:gen_pool_dma_zalloc
```
**Symbols:**

```
c0000000007f0020-c0000000007f0078: gen_pool_dma_zalloc_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_algo(struct gen_pool *pool, size_t size, dma_addr_t *dma, genpool_algo_t algo, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffe000470c20)
Location: lib/genalloc.c:438
Inline: False
Direct callers:
  - lib/genalloc.c:gen_pool_dma_zalloc_align
  - lib/genalloc.c:gen_pool_dma_zalloc
```
**Symbols:**

```
ffffffe000470c20-ffffffe000470c54: gen_pool_dma_zalloc_algo (STB_GLOBAL)
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
void *gen_pool_dma_zalloc_algo(struct gen_pool *pool, size_t size, dma_addr_t *dma, genpool_algo_t algo, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8152fde0)
Location: lib/genalloc.c:438
Inline: False
Direct callers:
  - lib/genalloc.c:gen_pool_dma_zalloc_align
  - lib/genalloc.c:gen_pool_dma_zalloc
```
**Symbols:**

```
ffffffff8152fde0-ffffffff8152fe0d: gen_pool_dma_zalloc_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_algo(struct gen_pool *pool, size_t size, dma_addr_t *dma, genpool_algo_t algo, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff815200c0)
Location: lib/genalloc.c:438
Inline: False
Direct callers:
  - lib/genalloc.c:gen_pool_dma_zalloc_align
  - lib/genalloc.c:gen_pool_dma_zalloc
```
**Symbols:**

```
ffffffff815200c0-ffffffff815200ed: gen_pool_dma_zalloc_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_algo(struct gen_pool *pool, size_t size, dma_addr_t *dma, genpool_algo_t algo, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8152bb20)
Location: lib/genalloc.c:438
Inline: False
Direct callers:
  - lib/genalloc.c:gen_pool_dma_zalloc_align
  - lib/genalloc.c:gen_pool_dma_zalloc
```
**Symbols:**

```
ffffffff8152bb20-ffffffff8152bb4d: gen_pool_dma_zalloc_algo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_algo(struct gen_pool *pool, size_t size, dma_addr_t *dma, genpool_algo_t algo, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81545920)
Location: lib/genalloc.c:438
Inline: False
Direct callers:
  - lib/genalloc.c:gen_pool_dma_zalloc_align
  - lib/genalloc.c:gen_pool_dma_zalloc
```
**Symbols:**

```
ffffffff81545920-ffffffff8154594d: gen_pool_dma_zalloc_algo (STB_GLOBAL)
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
