# Function: <code>set_track</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_track(struct kmem_cache *s, void *object, enum track_item alloc, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e75f0)
Location: mm/slub.c:513
Inline: False
Direct callers:
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff811e75f0-ffffffff811e772e: set_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void set_track(struct kmem_cache *s, void *object, enum track_item alloc, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81206820)
Location: mm/slub.c:524
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81206820-ffffffff8120695e: set_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void set_track(struct kmem_cache *s, void *object, enum track_item alloc, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812188d0)
Location: mm/slub.c:521
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812188d0-ffffffff81218a0e: set_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void set_track(struct kmem_cache *s, void *object, enum track_item alloc, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812244a0)
Location: mm/slub.c:523
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812244a0-ffffffff812245cd: set_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void set_track(struct kmem_cache *s, void *object, enum track_item alloc, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8123fb00)
Location: mm/slub.c:558
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff8123fb00-ffffffff8123fc2d: set_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_track(struct kmem_cache *s, void *object, enum track_item alloc, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81263170)
Location: mm/slub.c:543
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81263170-ffffffff8126329b: set_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_track(struct kmem_cache *s, void *object, enum track_item alloc, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81277a00)
Location: mm/slub.c:548
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81277a00-ffffffff81277b2b: set_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_track(struct kmem_cache *s, void *object, enum track_item alloc, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812931a0)
Location: mm/slub.c:549
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812931a0-ffffffff81293262: set_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_track(struct kmem_cache *s, void *object, enum track_item alloc, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a2f20)
Location: mm/slub.c:549
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812a2f20-ffffffff812a2fe2: set_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812d9f51)
Location: mm/slub.c:584
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812d7eb0-ffffffff812d7f6c: set_track.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812e5283)
Location: mm/slub.c:578
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812e38b0-ffffffff812e396c: set_track.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812ece53)
Location: mm/slub.c:589
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812eb060-ffffffff812eb11c: set_track.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff81335063)
Location: mm/slub.c:700
Inline: True
Inline callers:
  - mm/slub.c:early_kmem_cache_node_alloc
  - mm/slub.c:early_kmem_cache_node_alloc
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81333280-ffffffff81333356: set_track.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813a72c0)
Location: mm/slub.c:763
Inline: True
Inline callers:
  - mm/slub.c:alloc_debug_processing
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142a47d)
Location: mm/slub.c:778
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145f88a)
Location: mm/slub.c:799
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145aa74)
Location: mm/slub.c:912
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
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
void set_track(struct kmem_cache *s, void *object, enum track_item alloc, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff8000103432a0)
Location: mm/slub.c:549
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffff8000103432a0-ffff8000103433ac: set_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void set_track(struct kmem_cache *s, void *object, enum track_item alloc, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c0548894)
Location: mm/slub.c:549
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
c0548894-c0548940: set_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void set_track(struct kmem_cache *s, void *object, enum track_item alloc, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c0000000004208f0)
Location: mm/slub.c:549
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
c0000000004208f0-c0000000004209f4: set_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void set_track(struct kmem_cache *s, void *object, enum track_item alloc, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe000236d1c)
Location: mm/slub.c:549
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffe000236d1c-ffffffe000236dda: set_track (STB_LOCAL)
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
void set_track(struct kmem_cache *s, void *object, enum track_item alloc, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129b500)
Location: mm/slub.c:549
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff8129b500-ffffffff8129b5c2: set_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_track(struct kmem_cache *s, void *object, enum track_item alloc, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8128d0c0)
Location: mm/slub.c:549
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff8128d0c0-ffffffff8128d182: set_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_track(struct kmem_cache *s, void *object, enum track_item alloc, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81299310)
Location: mm/slub.c:549
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81299310-ffffffff812993d2: set_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_track(struct kmem_cache *s, void *object, enum track_item alloc, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a9130)
Location: mm/slub.c:549
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812a9130-ffffffff812a91f2: set_track (STB_LOCAL)
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
