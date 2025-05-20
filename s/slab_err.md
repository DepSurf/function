# Function: <code>slab_err</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct page *page, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e7510)
Location: mm/slub.c:662
Inline: False
Direct callers:
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff811e7510-ffffffff811e75e4: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct page *page, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812065e0)
Location: mm/slub.c:677
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
```
**Symbols:**

```
ffffffff812065e0-ffffffff812066b4: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct page *page, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81218600)
Location: mm/slub.c:676
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
```
**Symbols:**

```
ffffffff81218600-ffffffff812186d4: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct page *page, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81224250)
Location: mm/slub.c:678
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
```
**Symbols:**

```
ffffffff81224250-ffffffff8122431f: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct page *page, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8123f8b0)
Location: mm/slub.c:713
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
```
**Symbols:**

```
ffffffff8123f8b0-ffffffff8123f97f: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct page *page, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8126a8e2)
Location: mm/slub.c:699
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
```
**Symbols:**

```
ffffffff8126a8e2-ffffffff8126a9b6: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct page *page, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127f172)
Location: mm/slub.c:704
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
```
**Symbols:**

```
ffffffff8127f172-ffffffff8127f246: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct page *page, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129b012)
Location: mm/slub.c:696
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
```
**Symbols:**

```
ffffffff8129b012-ffffffff8129b0ee: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct page *page, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812aaed2)
Location: mm/slub.c:696
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
```
**Symbols:**

```
ffffffff812aaed2-ffffffff812aafae: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct page *page, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812df777)
Location: mm/slub.c:742
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
```
**Symbols:**

```
ffffffff812df777-ffffffff812df831: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct page *page, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81be8f26)
Location: mm/slub.c:737
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
```
**Symbols:**

```
ffffffff81be8f26-ffffffff81be8fe0: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct page *page, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81bdb07d)
Location: mm/slub.c:749
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
```
**Symbols:**

```
ffffffff81bdb07d-ffffffff81bdb137: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct page *page, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81cc0bc2)
Location: mm/slub.c:866
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
```
**Symbols:**

```
ffffffff81cc0bc2-ffffffff81cc0c8b: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct slab *slab, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81e7310c)
Location: mm/slub.c:913
Inline: False
Direct callers:
  - mm/slub.c:free_partial
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:slab_pad_check
```
**Symbols:**

```
ffffffff81e7310c-ffffffff81e73203: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct slab *slab, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81425080)
Location: mm/slub.c:980
Inline: False
Direct callers:
  - mm/slub.c:free_partial
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:slab_pad_check
```
**Symbols:**

```
ffffffff81425080-ffffffff814251af: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct slab *slab, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145a430)
Location: mm/slub.c:1001
Inline: False
Direct callers:
  - mm/slub.c:free_partial
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:slab_pad_check
```
**Symbols:**

```
ffffffff8145a430-ffffffff8145a55f: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct slab *slab, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81455500)
Location: mm/slub.c:1114
Inline: False
Direct callers:
  - mm/slub.c:free_partial
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:slab_pad_check
```
**Symbols:**

```
ffffffff81455500-ffffffff8145562f: slab_err (STB_LOCAL)
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
void slab_err(struct kmem_cache *s, struct page *page, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034d480)
Location: mm/slub.c:696
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
```
**Symbols:**

```
ffff80001034d480-ffff80001034d55c: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct page *page, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c055071c)
Location: mm/slub.c:696
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
```
**Symbols:**

```
c055071c-c05507d0: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct page *page, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c00000000042cd14)
Location: mm/slub.c:696
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
```
**Symbols:**

```
c00000000042cd14-c00000000042cdec: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct page *page, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023db70)
Location: mm/slub.c:696
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
```
**Symbols:**

```
ffffffe00023db70-ffffffe00023dc02: slab_err (STB_LOCAL)
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
void slab_err(struct kmem_cache *s, struct page *page, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a34b2)
Location: mm/slub.c:696
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
```
**Symbols:**

```
ffffffff812a34b2-ffffffff812a358e: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct page *page, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81294f82)
Location: mm/slub.c:696
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
```
**Symbols:**

```
ffffffff81294f82-ffffffff8129505e: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct page *page, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a12c2)
Location: mm/slub.c:696
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
```
**Symbols:**

```
ffffffff812a12c2-ffffffff812a139e: slab_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void slab_err(struct kmem_cache *s, struct page *page, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812b1472)
Location: mm/slub.c:696
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:on_freelist
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
  - mm/slub.c:check_slab
```
**Symbols:**

```
ffffffff812b1472-ffffffff812b154e: slab_err (STB_LOCAL)
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
