# Function: <code>find_mergeable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kmem_cache *find_mergeable(size_t size, size_t align, long unsigned int flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811b45f0)
Location: mm/slab_common.c:248
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffff811b45f0-ffffffff811b470a: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kmem_cache *find_mergeable(size_t size, size_t align, long unsigned int flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811cd6a0)
Location: mm/slab_common.c:253
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffff811cd6a0-ffffffff811cd7b7: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kmem_cache *find_mergeable(size_t size, size_t align, long unsigned int flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811dd770)
Location: mm/slab_common.c:253
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffff811dd770-ffffffff811dd887: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kmem_cache *find_mergeable(size_t size, size_t align, long unsigned int flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811e7510)
Location: mm/slab_common.c:284
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffff811e7510-ffffffff811e762a: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kmem_cache *find_mergeable(size_t size, size_t align, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811fd750)
Location: mm/slab_common.c:293
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffff811fd750-ffffffff811fd869: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kmem_cache *find_mergeable(unsigned int size, unsigned int align, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8121eae0)
Location: mm/slab_common.c:316
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffff8121eae0-ffffffff8121ebdd: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kmem_cache *find_mergeable(unsigned int size, unsigned int align, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81231ac0)
Location: mm/slab_common.c:316
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffff81231ac0-ffffffff81231bbd: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kmem_cache *find_mergeable(unsigned int size, unsigned int align, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81241f00)
Location: mm/slab_common.c:331
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffff81241f00-ffffffff81241ff2: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kmem_cache *find_mergeable(unsigned int size, unsigned int align, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81250390)
Location: mm/slab_common.c:332
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffff81250390-ffffffff81250482: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kmem_cache *find_mergeable(unsigned int size, unsigned int align, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8127e9d0)
Location: mm/slab_common.c:332
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffff8127e9d0-ffffffff8127eaeb: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kmem_cache *find_mergeable(unsigned int size, unsigned int align, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81288a70)
Location: mm/slab_common.c:186
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffff81288a70-ffffffff81288b74: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kmem_cache *find_mergeable(unsigned int size, unsigned int align, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8128e120)
Location: mm/slab_common.c:194
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffff8128e120-ffffffff8128e223: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct kmem_cache *find_mergeable(unsigned int size, unsigned int align, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:194
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffff81cbb405-ffffffff81cbb443: find_mergeable.cold (STB_LOCAL)
ffffffff812cdf80-ffffffff812ce0d1: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct kmem_cache *find_mergeable(unsigned int size, unsigned int align, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:186
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffff81e6cfbc-ffffffff81e6cfd9: find_mergeable.cold (STB_LOCAL)
ffffffff8132c070-ffffffff8132c190: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct kmem_cache *find_mergeable(unsigned int size, unsigned int align, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:160
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffff82063227-ffffffff82063244: find_mergeable.cold (STB_LOCAL)
ffffffff813a1b60-ffffffff813a1c80: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct kmem_cache *find_mergeable(unsigned int size, unsigned int align, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:162
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffff820e2ae3-ffffffff820e2b1d: find_mergeable.cold (STB_LOCAL)
ffffffff813d4f00-ffffffff813d5063: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct kmem_cache *find_mergeable(unsigned int size, unsigned int align, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:161
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffff821bf476-ffffffff821bf4b0: find_mergeable.cold (STB_LOCAL)
ffffffff813ff330-ffffffff813ff493: find_mergeable (STB_GLOBAL)
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
struct kmem_cache *find_mergeable(unsigned int size, unsigned int align, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e7370)
Location: mm/slab_common.c:332
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffff8000102e7370-ffff8000102e74c4: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kmem_cache *find_mergeable(unsigned int size, unsigned int align, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c050b4f4)
Location: mm/slab_common.c:332
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
c050b4f4-c050b620: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kmem_cache *find_mergeable(unsigned int size, unsigned int align, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0000000003a8f70)
Location: mm/slab_common.c:332
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
c0000000003a8f70-c0000000003a915c: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kmem_cache *find_mergeable(unsigned int size, unsigned int align, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0001fcf7c)
Location: mm/slab_common.c:332
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffe0001fcf7c-ffffffe0001fd0a0: find_mergeable (STB_GLOBAL)
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
struct kmem_cache *find_mergeable(unsigned int size, unsigned int align, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812489e0)
Location: mm/slab_common.c:332
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffff812489e0-ffffffff81248ad2: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kmem_cache *find_mergeable(unsigned int size, unsigned int align, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8123b990)
Location: mm/slab_common.c:332
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffff8123b990-ffffffff8123ba82: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kmem_cache *find_mergeable(unsigned int size, unsigned int align, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81246780)
Location: mm/slab_common.c:332
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffff81246780-ffffffff81246872: find_mergeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kmem_cache *find_mergeable(unsigned int size, unsigned int align, slab_flags_t flags, const char *name, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81255f90)
Location: mm/slab_common.c:332
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_alias
```
**Symbols:**

```
ffffffff81255f90-ffffffff81256082: find_mergeable (STB_GLOBAL)
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
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>size_t size</code> ➡️ <code>unsigned int size</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t align</code> ➡️ <code>unsigned int align</code>
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
