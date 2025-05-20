# Function: <code>__kmem_cache_free_bulk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811b43c0)
Location: mm/slab_common.c:107
Inline: True
Inline callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
Direct callers:
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
ffffffff811b43c0-ffffffff811b4400: __kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811cd470)
Location: mm/slab_common.c:108
Inline: False
Direct callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
ffffffff811cd470-ffffffff811cd4c8: __kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811dd540)
Location: mm/slab_common.c:108
Inline: False
Direct callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
ffffffff811dd540-ffffffff811dd598: __kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811e6e90)
Location: mm/slab_common.c:112
Inline: False
Direct callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
ffffffff811e6e90-ffffffff811e6ee2: __kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811fd0d0)
Location: mm/slab_common.c:113
Inline: False
Direct callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
ffffffff811fd0d0-ffffffff811fd122: __kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8121e3e0)
Location: mm/slab_common.c:103
Inline: False
Direct callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
ffffffff8121e3e0-ffffffff8121e430: __kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812313c0)
Location: mm/slab_common.c:103
Inline: False
Direct callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
ffffffff812313c0-ffffffff81231410: __kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812417a0)
Location: mm/slab_common.c:104
Inline: False
Direct callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
ffffffff812417a0-ffffffff812417f0: __kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8124fc40)
Location: mm/slab_common.c:104
Inline: False
Direct callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
ffffffff8124fc40-ffffffff8124fc90: __kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8127e2f4)
Location: mm/slab_common.c:104
Inline: True
Inline callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
Direct callers:
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
ffffffff8127e240-ffffffff8127e297: __kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812889f4)
Location: mm/slab_common.c:107
Inline: True
Inline callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
Direct callers:
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
ffffffff81288940-ffffffff81288997: __kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8128e0a4)
Location: mm/slab_common.c:115
Inline: True
Inline callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
Direct callers:
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
ffffffff8128dff0-ffffffff8128e047: __kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812cdee4)
Location: mm/slab_common.c:115
Inline: True
Inline callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
Direct callers:
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
ffffffff812cde30-ffffffff812cde87: __kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8132bfbc)
Location: mm/slab_common.c:108
Inline: True
Inline callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
Direct callers:
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
ffffffff8132bee0-ffffffff8132bf4b: __kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145e5fe)
Location: mm/slub.c:4496
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_alloc_bulk
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
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e6b38)
Location: mm/slab_common.c:104
Inline: False
Direct callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
ffff8000102e6b38-ffff8000102e6ba8: __kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c050ad94)
Location: mm/slab_common.c:104
Inline: False
Direct callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
c050ad94-c050adf0: __kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0000000003a84f0)
Location: mm/slab_common.c:104
Inline: False
Direct callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
c0000000003a84f0-c0000000003a8594: __kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0001fc8dc)
Location: mm/slab_common.c:104
Inline: False
Direct callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
ffffffe0001fc8dc-ffffffe0001fc93e: __kmem_cache_free_bulk (STB_GLOBAL)
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
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81248290)
Location: mm/slab_common.c:104
Inline: False
Direct callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
ffffffff81248290-ffffffff812482e0: __kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8123b240)
Location: mm/slab_common.c:104
Inline: False
Direct callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
ffffffff8123b240-ffffffff8123b290: __kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81246030)
Location: mm/slab_common.c:104
Inline: False
Direct callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
ffffffff81246030-ffffffff81246080: __kmem_cache_free_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __kmem_cache_free_bulk(struct kmem_cache *s, size_t nr, void **p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81255820)
Location: mm/slab_common.c:104
Inline: False
Direct callers:
  - mm/slab_common.c:__kmem_cache_alloc_bulk
  - mm/slub.c:kmem_cache_alloc_bulk
```
**Symbols:**

```
ffffffff81255820-ffffffff81255870: __kmem_cache_free_bulk (STB_GLOBAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
