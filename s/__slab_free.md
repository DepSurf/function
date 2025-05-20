# Function: <code>__slab_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct page *page, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811eb8b0)
Location: mm/slub.c:2634
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free_bulk
```
**Symbols:**

```
ffffffff811eb8b0-ffffffff811ebb69: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct page *page, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120aac0)
Location: mm/slub.c:2763
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff8120aac0-ffffffff8120ada0: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct page *page, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121cb10)
Location: mm/slub.c:2785
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff8121cb10-ffffffff8121cdf0: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct page *page, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81228710)
Location: mm/slub.c:2782
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff81228710-ffffffff812289d6: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct page *page, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812425b0)
Location: mm/slub.c:2795
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff812425b0-ffffffff81242866: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct page *page, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81267af0)
Location: mm/slub.c:2778
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff81267af0-ffffffff81267e30: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct page *page, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127c9b0)
Location: mm/slub.c:2828
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff8127c9b0-ffffffff8127ccf0: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct page *page, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81298570)
Location: mm/slub.c:2840
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff81298570-ffffffff81298893: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct page *page, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a83d0)
Location: mm/slub.c:2836
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff812a83d0-ffffffff812a86f3: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct page *page, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812dd760)
Location: mm/slub.c:2894
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff812dd760-ffffffff812dda78: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct page *page, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e6550)
Location: mm/slub.c:2962
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff812e6550-ffffffff812e688a: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct page *page, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812edce0)
Location: mm/slub.c:2984
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff812edce0-ffffffff812ee046: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct page *page, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813360c0)
Location: mm/slub.c:3283
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff813360c0-ffffffff81336426: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct slab *slab, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813a7980)
Location: mm/slub.c:3327
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff813a7980-ffffffff813a7c90: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct slab *slab, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142bba0)
Location: mm/slub.c:3574
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
```
**Symbols:**

```
ffffffff8142bba0-ffffffff8142be77: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct slab *slab, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81461120)
Location: mm/slub.c:3592
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:__kmem_cache_free
```
**Symbols:**

```
ffffffff81461120-ffffffff814613fb: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct slab *slab, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff814590f0)
Location: mm/slub.c:4098
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff814590f0-ffffffff814593a6: __slab_free (STB_LOCAL)
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
void __slab_free(struct kmem_cache *s, struct page *page, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010349c88)
Location: mm/slub.c:2836
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffff800010349c88-ffff80001034a0b8: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct page *page, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054dd10)
Location: mm/slub.c:2836
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
c054dd10-c054e0d0: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct page *page, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c000000000428ae0)
Location: mm/slub.c:2836
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
c000000000428ae0-c000000000428fa0: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct page *page, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023b7ac)
Location: mm/slub.c:2836
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffe00023b7ac-ffffffe00023ba38: __slab_free (STB_LOCAL)
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
void __slab_free(struct kmem_cache *s, struct page *page, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a09b0)
Location: mm/slub.c:2836
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff812a09b0-ffffffff812a0cd3: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct page *page, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812924c0)
Location: mm/slub.c:2836
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff812924c0-ffffffff812927ba: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct page *page, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129e7c0)
Location: mm/slub.c:2836
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff8129e7c0-ffffffff8129eae3: __slab_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __slab_free(struct kmem_cache *s, struct page *page, void *head, void *tail, int cnt, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ae850)
Location: mm/slub.c:2836
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff812ae850-ffffffff812aebc6: __slab_free (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
<code>struct slab *slab</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
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
