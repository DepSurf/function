# Function: <code>on_freelist</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int on_freelist(struct kmem_cache *s, struct page *page, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e8580)
Location: mm/slub.c:896
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff811e8580-ffffffff811e87d8: on_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int on_freelist(struct kmem_cache *s, struct page *page, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81207f20)
Location: mm/slub.c:920
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff81207f20-ffffffff81208164: on_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int on_freelist(struct kmem_cache *s, struct page *page, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81219f80)
Location: mm/slub.c:919
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff81219f80-ffffffff8121a1c1: on_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int on_freelist(struct kmem_cache *s, struct page *page, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81225610)
Location: mm/slub.c:921
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff81225610-ffffffff81225863: on_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int on_freelist(struct kmem_cache *s, struct page *page, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81240c90)
Location: mm/slub.c:956
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff81240c90-ffffffff81240ef9: on_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int on_freelist(struct kmem_cache *s, struct page *page, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:944
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff81267520-ffffffff81267683: on_freelist (STB_LOCAL)
ffffffff8126af81-ffffffff8126b088: on_freelist.cold.95 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int on_freelist(struct kmem_cache *s, struct page *page, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:949
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff8127c1f0-ffffffff8127c356: on_freelist (STB_LOCAL)
ffffffff8127f811-ffffffff8127f918: on_freelist.cold.97 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int on_freelist(struct kmem_cache *s, struct page *page, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:941
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff81297df0-ffffffff81297f38: on_freelist (STB_LOCAL)
ffffffff8129b714-ffffffff8129b82a: on_freelist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int on_freelist(struct kmem_cache *s, struct page *page, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:941
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff812a7c50-ffffffff812a7d98: on_freelist (STB_LOCAL)
ffffffff812ab5a0-ffffffff812ab6b6: on_freelist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int on_freelist(struct kmem_cache *s, struct page *page, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:986
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff812dd160-ffffffff812dd2b2: on_freelist (STB_LOCAL)
ffffffff812e0023-ffffffff812e0125: on_freelist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int on_freelist(struct kmem_cache *s, struct page *page, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:981
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff812e5f30-ffffffff812e6082: on_freelist (STB_LOCAL)
ffffffff81be96ee-ffffffff81be97f0: on_freelist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int on_freelist(struct kmem_cache *s, struct page *page, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:993
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff812ed6d0-ffffffff812ed820: on_freelist (STB_LOCAL)
ffffffff81bdb767-ffffffff81bdb869: on_freelist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int on_freelist(struct kmem_cache *s, struct page *page, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1117
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff81335a30-ffffffff81335b8a: on_freelist (STB_LOCAL)
ffffffff81cc16d5-ffffffff81cc17f8: on_freelist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int on_freelist(struct kmem_cache *s, struct slab *slab, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1163
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff813a6cb0-ffffffff813a6e61: on_freelist (STB_LOCAL)
ffffffff81e73a5d-ffffffff81e73b7c: on_freelist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int on_freelist(struct kmem_cache *s, struct slab *slab, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1258
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff81428440-ffffffff814286de: on_freelist (STB_LOCAL)
ffffffff8206768d-ffffffff820676ac: on_freelist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int on_freelist(struct kmem_cache *s, struct slab *slab, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1279
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff8145d800-ffffffff8145da9e: on_freelist (STB_LOCAL)
ffffffff820e6f6e-ffffffff820e6f8d: on_freelist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int on_freelist(struct kmem_cache *s, struct slab *slab, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1403
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff81457f00-ffffffff814581a0: on_freelist (STB_LOCAL)
ffffffff821c1fa4-ffffffff821c1fc0: on_freelist.cold (STB_LOCAL)
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
int on_freelist(struct kmem_cache *s, struct page *page, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff8000103490f8)
Location: mm/slub.c:941
Inline: False
Direct callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffff8000103490f8-ffff800010349364: on_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int on_freelist(struct kmem_cache *s, struct page *page, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054d2bc)
Location: mm/slub.c:941
Inline: False
Direct callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
c054d2bc-c054d514: on_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int on_freelist(struct kmem_cache *s, struct page *page, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c000000000427d30)
Location: mm/slub.c:941
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
c000000000427d30-c00000000042800c: on_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int on_freelist(struct kmem_cache *s, struct page *page, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023aee4)
Location: mm/slub.c:941
Inline: False
Direct callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffe00023aee4-ffffffe00023b104: on_freelist (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int on_freelist(struct kmem_cache *s, struct page *page, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:941
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff812a0230-ffffffff812a0378: on_freelist (STB_LOCAL)
ffffffff812a3b80-ffffffff812a3c96: on_freelist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int on_freelist(struct kmem_cache *s, struct page *page, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:941
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff81291d40-ffffffff81291e88: on_freelist (STB_LOCAL)
ffffffff81295650-ffffffff81295766: on_freelist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int on_freelist(struct kmem_cache *s, struct page *page, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:941
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff8129e040-ffffffff8129e188: on_freelist (STB_LOCAL)
ffffffff812a1990-ffffffff812a1aa6: on_freelist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int on_freelist(struct kmem_cache *s, struct page *page, void *search);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:941
Inline: False
Direct callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff812ae0b0-ffffffff812ae1f8: on_freelist (STB_LOCAL)
ffffffff812b1b40-ffffffff812b1c56: on_freelist.cold (STB_LOCAL)
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
