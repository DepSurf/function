# Function: <code>__kmem_cache_release</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120d340)
Location: mm/slub.c:3347
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff8120d340-ffffffff8120d365: __kmem_cache_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121f3a0)
Location: mm/slub.c:3369
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff8121f3a0-ffffffff8121f3c5: __kmem_cache_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8122ab60)
Location: mm/slub.c:3366
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff8122ab60-ffffffff8122ab85: __kmem_cache_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81246260)
Location: mm/slub.c:3379
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff81246260-ffffffff81246285: __kmem_cache_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812696d0)
Location: mm/slub.c:3362
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff812696d0-ffffffff812696f5: __kmem_cache_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127dfa0)
Location: mm/slub.c:3412
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff8127dfa0-ffffffff8127dfc5: __kmem_cache_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81299de0)
Location: mm/slub.c:3423
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff81299de0-ffffffff81299e08: __kmem_cache_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a9ca0)
Location: mm/slub.c:3433
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff812a9ca0-ffffffff812a9cc8: __kmem_cache_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812deb10)
Location: mm/slub.c:3491
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff812deb10-ffffffff812deb6d: __kmem_cache_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812eb02f)
Location: mm/slub.c:3578
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
```
**Symbols:**

```
ffffffff812ea910-ffffffff812ea96f: __kmem_cache_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812f2aff)
Location: mm/slub.c:3611
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
```
**Symbols:**

```
ffffffff812f21b0-ffffffff812f220f: __kmem_cache_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8133add0)
Location: mm/slub.c:3948
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff8133add0-ffffffff8133ae2f: __kmem_cache_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813ad690)
Location: mm/slub.c:3998
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff813ad690-ffffffff813ad6f9: __kmem_cache_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142d8f0)
Location: mm/slub.c:4278
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff8142d8f0-ffffffff8142d959: __kmem_cache_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81462f30)
Location: mm/slub.c:4293
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff81462f30-ffffffff81462fd9: __kmem_cache_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145f180)
Location: mm/slub.c:4897
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff8145f180-ffffffff8145f229: __kmem_cache_release (STB_GLOBAL)
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
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034b818)
Location: mm/slub.c:3433
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffff80001034b818-ffff80001034b854: __kmem_cache_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054f71c)
Location: mm/slub.c:3433
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
c054f71c-c054f768: __kmem_cache_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c00000000042aec0)
Location: mm/slub.c:3433
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
c00000000042aec0-c00000000042af10: __kmem_cache_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023cd38)
Location: mm/slub.c:3433
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffe00023cd38-ffffffe00023cd86: __kmem_cache_release (STB_GLOBAL)
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
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a2280)
Location: mm/slub.c:3433
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff812a2280-ffffffff812a22a8: __kmem_cache_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81293d60)
Location: mm/slub.c:3433
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff81293d60-ffffffff81293d88: __kmem_cache_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a0090)
Location: mm/slub.c:3433
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff812a0090-ffffffff812a00b8: __kmem_cache_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __kmem_cache_release(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812b01d0)
Location: mm/slub.c:3433
Inline: False
Direct callers:
  - mm/slab_common.c:slab_kmem_cache_release
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff812b01d0-ffffffff812b01f8: __kmem_cache_release (STB_GLOBAL)
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
