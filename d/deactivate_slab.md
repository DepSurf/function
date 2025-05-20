# Function: <code>deactivate_slab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void deactivate_slab(struct kmem_cache *s, struct page *page, void *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e9ee0)
Location: mm/slub.c:1860
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:flush_cpu_slab
  - mm/slub.c:slab_cpuup_callback
```
**Symbols:**

```
ffffffff811e9ee0-ffffffff811ea2bc: deactivate_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void deactivate_slab(struct kmem_cache *s, struct page *page, void *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81209530)
Location: mm/slub.c:1989
Inline: False
Direct callers:
  - mm/slub.c:slab_cpuup_callback
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:flush_cpu_slab
```
**Symbols:**

```
ffffffff81209530-ffffffff812098f3: deactivate_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void deactivate_slab(struct kmem_cache *s, struct page *page, void *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121b5a0)
Location: mm/slub.c:1992
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
```
**Symbols:**

```
ffffffff8121b5a0-ffffffff8121b963: deactivate_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff81226fe0)
Location: mm/slub.c:1995
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
```
**Symbols:**

```
ffffffff81226fe0-ffffffff81227392: deactivate_slab.isra.70 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812435b0)
Location: mm/slub.c:2008
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
```
**Symbols:**

```
ffffffff812435b0-ffffffff812439a0: deactivate_slab.isra.70 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812654a0)
Location: mm/slub.c:1991
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
```
**Symbols:**

```
ffffffff812654a0-ffffffff81265957: deactivate_slab.isra.72 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff8127a1d0)
Location: mm/slub.c:2050
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
```
**Symbols:**

```
ffffffff8127a1d0-ffffffff8127a693: deactivate_slab.isra.75 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff81295b40)
Location: mm/slub.c:2057
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
```
**Symbols:**

```
ffffffff81295b40-ffffffff81295fe3: deactivate_slab.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812a5920)
Location: mm/slub.c:2036
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
```
**Symbols:**

```
ffffffff812a5920-ffffffff812a5dc3: deactivate_slab.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void deactivate_slab(struct kmem_cache *s, struct page *page, void *freelist, struct kmem_cache_cpu *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2086
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
```
**Symbols:**

```
ffffffff812da5e0-ffffffff812daad3: deactivate_slab (STB_LOCAL)
ffffffff812dff04-ffffffff812dff49: deactivate_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void deactivate_slab(struct kmem_cache *s, struct page *page, void *freelist, struct kmem_cache_cpu *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2151
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
```
**Symbols:**

```
ffffffff812e6ea0-ffffffff812e73b7: deactivate_slab (STB_LOCAL)
ffffffff81be9926-ffffffff81be996b: deactivate_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void deactivate_slab(struct kmem_cache *s, struct page *page, void *freelist, struct kmem_cache_cpu *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2179
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
```
**Symbols:**

```
ffffffff812ee690-ffffffff812eeac8: deactivate_slab (STB_LOCAL)
ffffffff81bdb99f-ffffffff81bdb9d5: deactivate_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void deactivate_slab(struct kmem_cache *s, struct page *page, void *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2313
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
```
**Symbols:**

```
ffffffff813368d0-ffffffff81336d80: deactivate_slab (STB_LOCAL)
ffffffff81cc19d9-ffffffff81cc1a0f: deactivate_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void deactivate_slab(struct kmem_cache *s, struct slab *slab, void *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2373
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_slab
```
**Symbols:**

```
ffffffff813a8240-ffffffff813a85d9: deactivate_slab (STB_LOCAL)
ffffffff81e73e95-ffffffff81e73ecf: deactivate_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void deactivate_slab(struct kmem_cache *s, struct slab *slab, void *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81428c30)
Location: mm/slub.c:2474
Inline: False
Direct callers:
  - mm/slub.c:bootstrap
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_slab
```
**Symbols:**

```
ffffffff81428c30-ffffffff81428f71: deactivate_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void deactivate_slab(struct kmem_cache *s, struct slab *slab, void *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145dfa0)
Location: mm/slub.c:2484
Inline: False
Direct callers:
  - mm/slub.c:bootstrap
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_slab
```
**Symbols:**

```
ffffffff8145dfa0-ffffffff8145e2ba: deactivate_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void deactivate_slab(struct kmem_cache *s, struct slab *slab, void *freelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81459970)
Location: mm/slub.c:2805
Inline: False
Direct callers:
  - mm/slub.c:bootstrap
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_slab
```
**Symbols:**

```
ffffffff81459970-ffffffff81459c39: deactivate_slab (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffff800010346808)
Location: mm/slub.c:2036
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
```
**Symbols:**

```
ffff800010346808-ffff800010346d60: deactivate_slab.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void deactivate_slab(struct kmem_cache *s, struct page *page, void *freelist, struct kmem_cache_cpu *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054b38c)
Location: mm/slub.c:2036
Inline: False
Direct callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
```
**Symbols:**

```
c054b38c-c054b8c4: deactivate_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (c000000000424820)
Location: mm/slub.c:2036
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
```
**Symbols:**

```
c000000000424820-c000000000424dc4: deactivate_slab.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffe000239618)
Location: mm/slub.c:2036
Inline: True
Direct callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
```
**Symbols:**

```
ffffffe000239618-ffffffe0002399a4: deactivate_slab.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff8129df00)
Location: mm/slub.c:2036
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
```
**Symbols:**

```
ffffffff8129df00-ffffffff8129e3a3: deactivate_slab.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff8128fa80)
Location: mm/slub.c:2036
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
```
**Symbols:**

```
ffffffff8128fa80-ffffffff8128ff23: deactivate_slab.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff8129bd10)
Location: mm/slub.c:2036
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
```
**Symbols:**

```
ffffffff8129bd10-ffffffff8129c1b3: deactivate_slab.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812abc20)
Location: mm/slub.c:2036
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
```
**Symbols:**

```
ffffffff812abc20-ffffffff812ac15f: deactivate_slab.isra.0 (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct kmem_cache_cpu *c</code>
</li>
</ul>
</details>
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
</ul>
