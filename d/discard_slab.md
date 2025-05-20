# Function: <code>discard_slab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e9210)
Location: mm/slub.c:1567
Inline: False
Direct callers:
  - mm/slub.c:deactivate_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff811e9210-ffffffff811e925c: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81208cf0)
Location: mm/slub.c:1702
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:deactivate_slab
```
**Symbols:**

```
ffffffff81208cf0-ffffffff81208d3c: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121ad70)
Location: mm/slub.c:1705
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:deactivate_slab
```
**Symbols:**

```
ffffffff8121ad70-ffffffff8121adbc: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812267b0)
Location: mm/slub.c:1708
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff812267b0-ffffffff812267fc: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812417f0)
Location: mm/slub.c:1721
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff812417f0-ffffffff8124183c: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81265450)
Location: mm/slub.c:1704
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff81265450-ffffffff8126549c: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127a180)
Location: mm/slub.c:1763
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff8127a180-ffffffff8127a1cd: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81295af0)
Location: mm/slub.c:1770
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff81295af0-ffffffff81295b3c: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a58d0)
Location: mm/slub.c:1749
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff812a58d0-ffffffff812a591c: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812da590)
Location: mm/slub.c:1799
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:free_partial
  - mm/slub.c:__slab_free
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
```
**Symbols:**

```
ffffffff812da590-ffffffff812da5dc: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e6e50)
Location: mm/slub.c:1864
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:free_partial
  - mm/slub.c:__slab_free
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
```
**Symbols:**

```
ffffffff812e6e50-ffffffff812e6e9c: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ee640)
Location: mm/slub.c:1892
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
```
**Symbols:**

```
ffffffff812ee640-ffffffff812ee68c: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81336880)
Location: mm/slub.c:2013
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:deactivate_slab
```
**Symbols:**

```
ffffffff81336880-ffffffff813368cc: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct slab *slab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813a81d0)
Location: mm/slub.c:2071
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_partial
  - mm/slub.c:__slab_free
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:deactivate_slab
```
**Symbols:**

```
ffffffff813a81d0-ffffffff813a8234: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct slab *slab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81428be0)
Location: mm/slub.c:2095
Inline: False
Direct callers:
  - mm/slub.c:free_partial
  - mm/slub.c:__slab_free
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:deactivate_slab
```
**Symbols:**

```
ffffffff81428be0-ffffffff81428c20: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct slab *slab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145df50)
Location: mm/slub.c:2105
Inline: False
Direct callers:
  - mm/slub.c:free_partial
  - mm/slub.c:__slab_free
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:deactivate_slab
```
**Symbols:**

```
ffffffff8145df50-ffffffff8145df90: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct slab *slab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81459920)
Location: mm/slub.c:2450
Inline: False
Direct callers:
  - mm/slub.c:free_partial
  - mm/slub.c:__slab_free
  - mm/slub.c:__put_partials
  - mm/slub.c:deactivate_slab
```
**Symbols:**

```
ffffffff81459920-ffffffff81459960: discard_slab (STB_LOCAL)
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
void discard_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010346748)
Location: mm/slub.c:1749
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffff800010346748-ffff800010346808: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054b308)
Location: mm/slub.c:1749
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
```
**Symbols:**

```
c054b308-c054b38c: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c000000000424790)
Location: mm/slub.c:1749
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
```
**Symbols:**

```
c000000000424790-c000000000424820: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023d39e)
Location: mm/slub.c:1749
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
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
void discard_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129deb0)
Location: mm/slub.c:1749
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff8129deb0-ffffffff8129defc: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8128fa30)
Location: mm/slub.c:1749
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff8128fa30-ffffffff8128fa7c: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129bcc0)
Location: mm/slub.c:1749
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff8129bcc0-ffffffff8129bd0c: discard_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void discard_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812abbd0)
Location: mm/slub.c:1749
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff812abbd0-ffffffff812abc1c: discard_slab (STB_LOCAL)
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
