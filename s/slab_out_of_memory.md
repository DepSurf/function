# Function: <code>slab_out_of_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e7730)
Location: mm/slub.c:2220
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff811e7730-ffffffff811e7838: slab_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81206960)
Location: mm/slub.c:2349
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81206960-ffffffff81206a7d: slab_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81218a10)
Location: mm/slub.c:2371
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81218a10-ffffffff81218b2d: slab_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812245d0)
Location: mm/slub.c:2375
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812245d0-ffffffff812246df: slab_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8123fc30)
Location: mm/slub.c:2388
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8123fc30-ffffffff8123fd3f: slab_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2369
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812632a0-ffffffff812632f8: slab_out_of_memory (STB_LOCAL)
ffffffff8126a9cb-ffffffff8126aa87: slab_out_of_memory.cold.88 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2419
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81277b30-ffffffff81277b88: slab_out_of_memory (STB_LOCAL)
ffffffff8127f25b-ffffffff8127f317: slab_out_of_memory.cold.90 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2426
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812939a0-ffffffff812939f3: slab_out_of_memory (STB_LOCAL)
ffffffff8129b1e2-ffffffff8129b28b: slab_out_of_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2405
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812a3720-ffffffff812a3773: slab_out_of_memory (STB_LOCAL)
ffffffff812ab0a2-ffffffff812ab14b: slab_out_of_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2463
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812d7690-ffffffff812d76e3: slab_out_of_memory (STB_LOCAL)
ffffffff812df870-ffffffff812df919: slab_out_of_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2528
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812e3160-ffffffff812e31b3: slab_out_of_memory (STB_LOCAL)
ffffffff81be901f-ffffffff81be90d1: slab_out_of_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2545
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812ea900-ffffffff812ea953: slab_out_of_memory (STB_LOCAL)
ffffffff81bdb1a4-ffffffff81bdb256: slab_out_of_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2768
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81332840-ffffffff81332893: slab_out_of_memory (STB_LOCAL)
ffffffff81cc0d0d-ffffffff81cc0dbf: slab_out_of_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2810
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff813a3dd0-ffffffff813a3e4a: slab_out_of_memory (STB_LOCAL)
ffffffff81e7326f-ffffffff81e73328: slab_out_of_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff814261b0)
Location: mm/slub.c:2965
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff814261b0-ffffffff81426329: slab_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145b360)
Location: mm/slub.c:2975
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8145b360-ffffffff8145b4fe: slab_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81456540)
Location: mm/slub.c:3249
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81456540-ffffffff814566de: slab_out_of_memory (STB_LOCAL)
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
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010345028)
Location: mm/slub.c:2405
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffff800010345028-ffff800010345144: slab_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c0549084)
Location: mm/slub.c:2405
Inline: False
```
**Symbols:**

```
c0549084-c0549174: slab_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c000000000421a00)
Location: mm/slub.c:2405
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
c000000000421a00-c000000000421b8c: slab_out_of_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe0002378fe)
Location: mm/slub.c:2405
Inline: False
```
**Symbols:**

```
ffffffe0002378fe-ffffffe0002379e2: slab_out_of_memory (STB_LOCAL)
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
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2405
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8129bd00-ffffffff8129bd53: slab_out_of_memory (STB_LOCAL)
ffffffff812a3682-ffffffff812a372b: slab_out_of_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2405
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8128d8c0-ffffffff8128d913: slab_out_of_memory (STB_LOCAL)
ffffffff81295152-ffffffff812951fb: slab_out_of_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2405
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81299b10-ffffffff81299b63: slab_out_of_memory (STB_LOCAL)
ffffffff812a1492-ffffffff812a153b: slab_out_of_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void slab_out_of_memory(struct kmem_cache *s, gfp_t gfpflags, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:2405
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812a9930-ffffffff812a9983: slab_out_of_memory (STB_LOCAL)
ffffffff812b1642-ffffffff812b16eb: slab_out_of_memory.cold (STB_LOCAL)
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
