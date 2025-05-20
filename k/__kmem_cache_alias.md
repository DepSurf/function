# Function: <code>__kmem_cache_alias</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, size_t size, size_t align, long unsigned int flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811ee590)
Location: mm/slub.c:3935
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create
```
**Symbols:**

```
ffffffff811ee590-ffffffff811ee63c: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, size_t size, size_t align, long unsigned int flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120dba0)
Location: mm/slub.c:4162
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create
```
**Symbols:**

```
ffffffff8120dba0-ffffffff8120dc4c: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, size_t size, size_t align, long unsigned int flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121fbe0)
Location: mm/slub.c:4168
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create
```
**Symbols:**

```
ffffffff8121fbe0-ffffffff8121fc8c: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, size_t size, size_t align, long unsigned int flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8122b500)
Location: mm/slub.c:4210
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create
```
**Symbols:**

```
ffffffff8122b500-ffffffff8122b5bc: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, size_t size, size_t align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81246c00)
Location: mm/slub.c:4226
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create
```
**Symbols:**

```
ffffffff81246c00-ffffffff81246cbb: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81269f90)
Location: mm/slub.c:4229
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff81269f90-ffffffff8126a050: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127e850)
Location: mm/slub.c:4281
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff8127e850-ffffffff8127e910: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129a630)
Location: mm/slub.c:4272
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff8129a630-ffffffff8129a6f0: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812aa4f0)
Location: mm/slub.c:4290
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff812aa4f0-ffffffff812aa5b0: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812df210)
Location: mm/slub.c:4367
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff812df210-ffffffff812df2d0: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812eaf70)
Location: mm/slub.c:4422
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff812eaf70-ffffffff812eafee: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812f2a40)
Location: mm/slub.c:4503
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff812f2a40-ffffffff812f2abb: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8133b780)
Location: mm/slub.c:4854
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff8133b780-ffffffff8133b7fb: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813ade60)
Location: mm/slub.c:4886
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff813ade60-ffffffff813adef9: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142e210)
Location: mm/slub.c:5063
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff8142e210-ffffffff8142e2a5: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81463950)
Location: mm/slub.c:5078
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff81463950-ffffffff814639e5: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145fba0)
Location: mm/slub.c:5689
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff8145fba0-ffffffff8145fc35: __kmem_cache_alias (STB_GLOBAL)
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
struct kmem_cache *__kmem_cache_alias(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034c310)
Location: mm/slub.c:4290
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffff80001034c310-ffff80001034c420: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054fef4)
Location: mm/slub.c:4290
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
c054fef4-c054ffd8: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c00000000042bcf0)
Location: mm/slub.c:4290
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
c00000000042bcf0-c00000000042be70: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023d4a4)
Location: mm/slub.c:4290
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffe00023d4a4-ffffffe00023d580: __kmem_cache_alias (STB_GLOBAL)
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
struct kmem_cache *__kmem_cache_alias(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a2ad0)
Location: mm/slub.c:4290
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff812a2ad0-ffffffff812a2b90: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812945a0)
Location: mm/slub.c:4290
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff812945a0-ffffffff81294660: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a08e0)
Location: mm/slub.c:4290
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff812a08e0-ffffffff812a09a0: __kmem_cache_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kmem_cache *__kmem_cache_alias(const char *name, unsigned int size, unsigned int align, slab_flags_t flags, void (*ctor)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812b0a20)
Location: mm/slub.c:4290
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff812b0a20-ffffffff812b0ae0: __kmem_cache_alias (STB_GLOBAL)
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
