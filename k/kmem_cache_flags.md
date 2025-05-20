# Function: <code>kmem_cache_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int kmem_cache_flags(long unsigned int object_size, long unsigned int flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811ed9d0)
Location: mm/slub.c:1212
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff811ed9d0-ffffffff811eda2b: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int kmem_cache_flags(long unsigned int object_size, long unsigned int flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120ce60)
Location: mm/slub.c:1257
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff8120ce60-ffffffff8120cebb: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int kmem_cache_flags(long unsigned int object_size, long unsigned int flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121eec0)
Location: mm/slub.c:1256
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff8121eec0-ffffffff8121ef1b: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int kmem_cache_flags(long unsigned int object_size, long unsigned int flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff8122b5dc)
Location: mm/slub.c:1258
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff81225260-ffffffff812252be: kmem_cache_flags.part.75 (STB_LOCAL)
ffffffff8122ab30-ffffffff8122ab55: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
slab_flags_t kmem_cache_flags(long unsigned int object_size, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff81246cdc)
Location: mm/slub.c:1293
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff812408e0-ffffffff8124093c: kmem_cache_flags.part.75 (STB_LOCAL)
ffffffff81246230-ffffffff81246253: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff81268075)
Location: mm/slub.c:1281
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff81263c70-ffffffff81263cc6: kmem_cache_flags.part.78 (STB_LOCAL)
ffffffff812696a0-ffffffff812696c2: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127daa0)
Location: mm/slub.c:1308
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff8127daa0-ffffffff8127db8d: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812998f0)
Location: mm/slub.c:1303
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff812998f0-ffffffff812999cc: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a97b0)
Location: mm/slub.c:1304
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff812a97b0-ffffffff812a988c: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812de7f0)
Location: mm/slub.c:1349
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff812de7f0-ffffffff812de8cc: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ea5b0)
Location: mm/slub.c:1410
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff812ea5b0-ffffffff812ea6de: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812f1d30)
Location: mm/slub.c:1421
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff812f1d30-ffffffff812f1e74: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8133ac80)
Location: mm/slub.c:1550
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff8133ac80-ffffffff8133adc4: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813ad520)
Location: mm/slub.c:1603
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff813ad520-ffffffff813ad68d: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142d0d0)
Location: mm/slub.c:1639
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff8142d0d0-ffffffff8142d23d: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff814626d0)
Location: mm/slub.c:1652
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff814626d0-ffffffff8146283d: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145f000)
Location: mm/slub.c:1776
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff8145f000-ffffffff8145f16d: kmem_cache_flags (STB_GLOBAL)
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
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034b280)
Location: mm/slub.c:1304
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffff80001034b280-ffff80001034b390: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054f2b0)
Location: mm/slub.c:1304
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
c054f2b0-c054f380: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c00000000042a7c0)
Location: mm/slub.c:1304
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
c00000000042a7c0-c00000000042a950: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023c91e)
Location: mm/slub.c:1304
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffe00023c91e-ffffffe00023c9e2: kmem_cache_flags (STB_GLOBAL)
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
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a1d90)
Location: mm/slub.c:1304
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff812a1d90-ffffffff812a1e6c: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81293870)
Location: mm/slub.c:1304
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff81293870-ffffffff8129394c: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129fba0)
Location: mm/slub.c:1304
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff8129fba0-ffffffff8129fc7c: kmem_cache_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
slab_flags_t kmem_cache_flags(unsigned int object_size, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812afce0)
Location: mm/slub.c:1304
Inline: False
Direct callers:
  - mm/slab_common.c:find_mergeable
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff812afce0-ffffffff812afdbc: kmem_cache_flags (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int flags</code> ➡️ <code>slab_flags_t flags</code>
</li>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>slab_flags_t</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int object_size</code> ➡️ <code>unsigned int object_size</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void (*ctor)(void *)</code>
</li>
</ul>
</details>
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
