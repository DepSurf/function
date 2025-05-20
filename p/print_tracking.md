# Function: <code>print_tracking</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff811e7fe0)
Location: mm/slub.c:575
Inline: True
Inline callers:
  - mm/slub.c:print_trailer
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_create
Direct callers:
  - mm/slub.c:print_trailer
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff811e7fe0-ffffffff811e803e: print_tracking.part.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff8120d674)
Location: mm/slub.c:586
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:print_trailer
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff81207260-ffffffff812072c0: print_tracking.part.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff8121f6d0)
Location: mm/slub.c:583
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:print_trailer
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff81219290-ffffffff812192f0: print_tracking.part.46 (STB_LOCAL)
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
In mm/slub.c (ffffffff8122aef1)
Location: mm/slub.c:585
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:print_trailer
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff81224e90-ffffffff81224ef0: print_tracking.part.46 (STB_LOCAL)
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
In mm/slub.c (ffffffff812465f1)
Location: mm/slub.c:620
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:print_trailer
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff81240500-ffffffff81240560: print_tracking.part.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void print_tracking(struct kmem_cache *s, void *object);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8126aaf6)
Location: mm/slub.c:605
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff8126aaf6-ffffffff8126ab6d: print_tracking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void print_tracking(struct kmem_cache *s, void *object);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127f386)
Location: mm/slub.c:610
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff8127f386-ffffffff8127f3fd: print_tracking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void print_tracking(struct kmem_cache *s, void *object);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129b16b)
Location: mm/slub.c:602
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff8129b16b-ffffffff8129b1e2: print_tracking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void print_tracking(struct kmem_cache *s, void *object);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ab02b)
Location: mm/slub.c:602
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff812ab02b-ffffffff812ab0a2: print_tracking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void print_tracking(struct kmem_cache *s, void *object);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812df981)
Location: mm/slub.c:637
Inline: False
Direct callers:
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff812df981-ffffffff812df9e8: print_tracking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void print_tracking(struct kmem_cache *s, void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:632
Inline: False
Direct callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff81be92b0-ffffffff81be9334: print_tracking.cold (STB_LOCAL)
ffffffff812e5740-ffffffff812e57b0: print_tracking (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void print_tracking(struct kmem_cache *s, void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:643
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff81bdb42a-ffffffff81bdb4ae: print_tracking.cold (STB_LOCAL)
ffffffff812ecf10-ffffffff812ecf80: print_tracking (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void print_tracking(struct kmem_cache *s, void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:754
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff81cc130f-ffffffff81cc1393: print_tracking.cold (STB_LOCAL)
ffffffff813351e0-ffffffff81335250: print_tracking (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void print_tracking(struct kmem_cache *s, void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:800
Inline: False
Direct callers:
  - mm/slub.c:free_partial
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff81e73810-ffffffff81e738a7: print_tracking.cold (STB_LOCAL)
ffffffff813a6c30-ffffffff813a6cb0: print_tracking (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void print_tracking(struct kmem_cache *s, void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81428000)
Location: mm/slub.c:815
Inline: False
Direct callers:
  - mm/slub.c:free_partial
  - mm/slub.c:print_trailer
  - mm/slub.c:cache_from_obj
```
**Symbols:**

```
ffffffff81428000-ffffffff81428073: print_tracking (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void print_tracking(struct kmem_cache *s, void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145d3c0)
Location: mm/slub.c:836
Inline: False
Direct callers:
  - mm/slub.c:free_partial
  - mm/slub.c:print_trailer
  - mm/slub.c:cache_from_obj
```
**Symbols:**

```
ffffffff8145d3c0-ffffffff8145d433: print_tracking (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void print_tracking(struct kmem_cache *s, void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81457ac0)
Location: mm/slub.c:949
Inline: False
Direct callers:
  - mm/slub.c:free_partial
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff81457ac0-ffffffff81457b33: print_tracking (STB_GLOBAL)
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
void print_tracking(struct kmem_cache *s, void *object);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034d5dc)
Location: mm/slub.c:602
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffff80001034d5dc-ffff80001034d680: print_tracking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void print_tracking(struct kmem_cache *s, void *object);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c0550858)
Location: mm/slub.c:602
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:print_trailer
```
**Symbols:**

```
c0550858-c05508dc: print_tracking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void print_tracking(struct kmem_cache *s, void *object);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c00000000042ce94)
Location: mm/slub.c:602
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:print_trailer
```
**Symbols:**

```
c00000000042ce94-c00000000042cf50: print_tracking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void print_tracking(struct kmem_cache *s, void *object);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023dc78)
Location: mm/slub.c:602
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffe00023dc78-ffffffe00023dd0e: print_tracking (STB_LOCAL)
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
void print_tracking(struct kmem_cache *s, void *object);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a360b)
Location: mm/slub.c:602
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff812a360b-ffffffff812a3682: print_tracking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void print_tracking(struct kmem_cache *s, void *object);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812950db)
Location: mm/slub.c:602
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff812950db-ffffffff81295152: print_tracking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void print_tracking(struct kmem_cache *s, void *object);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a141b)
Location: mm/slub.c:602
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff812a141b-ffffffff812a1492: print_tracking (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void print_tracking(struct kmem_cache *s, void *object);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812b15cb)
Location: mm/slub.c:602
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff812b15cb-ffffffff812b1642: print_tracking (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
