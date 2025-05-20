# Function: <code>build_detached_freelist</code>

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
In mm/slub.c (ffffffff811ec117)
Location: mm/slub.c:2836
Inline: True
Inline callers:
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
In mm/slub.c (ffffffff8120b370)
Location: mm/slub.c:2984
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free_bulk
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
In mm/slub.c (ffffffff8121d3b0)
Location: mm/slub.c:3006
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_free_bulk
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
In mm/slub.c (ffffffff81228c30)
Location: mm/slub.c:3003
Inline: True
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
In mm/slub.c (ffffffff812428a0)
Location: mm/slub.c:3016
Inline: True
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
In mm/slub.c (ffffffff812684b9)
Location: mm/slub.c:2997
Inline: True
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
In mm/slub.c (ffffffff8127cf59)
Location: mm/slub.c:3047
Inline: True
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
In mm/slub.c (ffffffff812994a1)
Location: mm/slub.c:3058
Inline: True
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
In mm/slub.c (ffffffff812a9319)
Location: mm/slub.c:3056
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int build_detached_freelist(struct kmem_cache *s, size_t size, void **p, struct detached_freelist *df);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812d8530)
Location: mm/slub.c:3114
Inline: False
```
**Symbols:**

```
ffffffff812d8530-ffffffff812d8782: build_detached_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int build_detached_freelist(struct kmem_cache *s, size_t size, void **p, struct detached_freelist *df);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e5850)
Location: mm/slub.c:3185
Inline: False
```
**Symbols:**

```
ffffffff812e5850-ffffffff812e5b59: build_detached_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int build_detached_freelist(struct kmem_cache *s, size_t size, void **p, struct detached_freelist *df);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ed020)
Location: mm/slub.c:3210
Inline: False
```
**Symbols:**

```
ffffffff812ed020-ffffffff812ed2ff: build_detached_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int build_detached_freelist(struct kmem_cache *s, size_t size, void **p, struct detached_freelist *df);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3544
Inline: False
```
**Symbols:**

```
ffffffff813352f0-ffffffff81335672: build_detached_freelist (STB_LOCAL)
ffffffff81cc1587-ffffffff81cc15dc: build_detached_freelist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int build_detached_freelist(struct kmem_cache *s, size_t size, void **p, struct detached_freelist *df);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3591
Inline: False
```
**Symbols:**

```
ffffffff813ac1f0-ffffffff813ac67e: build_detached_freelist (STB_LOCAL)
ffffffff81e73f84-ffffffff81e73ffc: build_detached_freelist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int build_detached_freelist(struct kmem_cache *s, size_t size, void **p, struct detached_freelist *df);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142c3a0)
Location: mm/slub.c:3834
Inline: False
```
**Symbols:**

```
ffffffff8142c3a0-ffffffff8142c62d: build_detached_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int build_detached_freelist(struct kmem_cache *s, size_t size, void **p, struct detached_freelist *df);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81461950)
Location: mm/slub.c:3848
Inline: False
```
**Symbols:**

```
ffffffff81461950-ffffffff81461be1: build_detached_freelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int build_detached_freelist(struct kmem_cache *s, size_t size, void **p, struct detached_freelist *df);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:4434
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alloc_bulk
```
**Symbols:**

```
ffffffff8145dc80-ffffffff8145e020: build_detached_freelist (STB_LOCAL)
ffffffff821c20ad-ffffffff821c20c2: build_detached_freelist.cold (STB_LOCAL)
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
In mm/slub.c (ffff80001034ae58)
Location: mm/slub.c:3056
Inline: True
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
In mm/slub.c (c054e478)
Location: mm/slub.c:3056
Inline: True
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
In mm/slub.c (c00000000042a250)
Location: mm/slub.c:3056
Inline: True
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
In mm/slub.c (ffffffe00023c51c)
Location: mm/slub.c:3056
Inline: True
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
In mm/slub.c (ffffffff812a18f9)
Location: mm/slub.c:3056
Inline: True
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
In mm/slub.c (ffffffff812933d9)
Location: mm/slub.c:3056
Inline: True
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
In mm/slub.c (ffffffff8129f709)
Location: mm/slub.c:3056
Inline: True
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
In mm/slub.c (ffffffff812af839)
Location: mm/slub.c:3056
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
