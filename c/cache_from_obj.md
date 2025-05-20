# Function: <code>cache_from_obj</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811ebea4)
Location: mm/slab.h:296
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free_bulk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120b3df)
Location: mm/slab.h:331
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:kmem_cache_free
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121d419)
Location: mm/slab.h:346
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:kmem_cache_free
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812289f4)
Location: mm/slab.h:354
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81242b94)
Location: mm/slab.h:354
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81267e35)
Location: mm/slab.h:356
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127ccf5)
Location: mm/slab.h:357
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:kmem_cache_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81299175)
Location: mm/slab.h:440
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a8ff5)
Location: mm/slab.h:504
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kmem_cache *cache_from_obj(struct kmem_cache *s, void *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812d8440)
Location: mm/slab.h:506
Inline: False
Direct callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff812d8440-ffffffff812d852e: cache_from_obj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e58eb)
Location: mm/slab.h:441
Inline: True
Inline callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ed0bb)
Location: mm/slab.h:444
Inline: True
Inline callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8133538b)
Location: mm/slab.h:440
Inline: True
Inline callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
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
In mm/slub.c (ffffffff813ac2ae)
Location: mm/slab.h:669
Inline: True
Inline callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct kmem_cache *cache_from_obj(struct kmem_cache *s, void *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slab.h:661
Inline: False
Direct callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff8142be90-ffffffff8142bfcd: cache_from_obj (STB_LOCAL)
ffffffff82067709-ffffffff8206771d: cache_from_obj.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct kmem_cache *cache_from_obj(struct kmem_cache *s, void *x);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slab.h:652
Inline: False
Direct callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
```
**Symbols:**

```
ffffffff81461410-ffffffff81461542: cache_from_obj (STB_LOCAL)
ffffffff820e6fea-ffffffff820e6ffe: cache_from_obj.cold (STB_LOCAL)
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
In mm/slub.c (ffffffff8145dced)
Location: mm/slub.c:4333
Inline: True
Inline callers:
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034ab20)
Location: mm/slab.h:504
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054e0e8)
Location: mm/slab.h:504
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (c000000000429ca8)
Location: mm/slab.h:504
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
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
In mm/slub.c (ffffffe00023c262)
Location: mm/slab.h:504
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a15d5)
Location: mm/slab.h:504
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812930b5)
Location: mm/slab.h:504
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129f3e5)
Location: mm/slab.h:504
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812af4f5)
Location: mm/slab.h:504
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
