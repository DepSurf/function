# Function: <code>create_kmalloc_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kmem_cache *create_kmalloc_cache(const char *name, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81f8a0cc)
Location: mm/slab_common.c:784
Inline: False
Direct callers:
  - mm/slab_common.c:new_kmalloc_cache
  - mm/slab_common.c:create_kmalloc_caches
```
**Symbols:**

```
ffffffff81f8a0cc-ffffffff81f8a14e: create_kmalloc_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kmem_cache *create_kmalloc_cache(const char *name, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81fb3bb8)
Location: mm/slab_common.c:792
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff81fb3bb8-ffffffff81fb3c3a: create_kmalloc_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kmem_cache *create_kmalloc_cache(const char *name, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81ff0575)
Location: mm/slab_common.c:821
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff81ff0575-ffffffff81ff05f7: create_kmalloc_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kmem_cache *create_kmalloc_cache(const char *name, size_t size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff820d2982)
Location: mm/slab_common.c:892
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff820d2982-ffffffff820d2a11: create_kmalloc_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kmem_cache *create_kmalloc_cache(const char *name, size_t size, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff826db3a8)
Location: mm/slab_common.c:901
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff826db3a8-ffffffff826db437: create_kmalloc_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kmem_cache *create_kmalloc_cache(const char *name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff82705865)
Location: mm/slab_common.c:960
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff82705865-ffffffff8270590c: create_kmalloc_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kmem_cache *create_kmalloc_cache(const char *name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff828bcfac)
Location: mm/slab_common.c:987
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff828bcfac-ffffffff828bd053: create_kmalloc_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kmem_cache *create_kmalloc_cache(const char *name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff828d4594)
Location: mm/slab_common.c:1014
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff828d4594-ffffffff828d463e: create_kmalloc_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kmem_cache *create_kmalloc_cache(const char *name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff828dca23)
Location: mm/slab_common.c:1074
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff828dca23-ffffffff828dcacd: create_kmalloc_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kmem_cache *create_kmalloc_cache(const char *name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff82cfa54e)
Location: mm/slab_common.c:1074
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff82cfa54e-ffffffff82cfa5f8: create_kmalloc_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kmem_cache *create_kmalloc_cache(const char *name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff82fe7254)
Location: mm/slab_common.c:572
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff82fe7254-ffffffff82fe72f4: create_kmalloc_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kmem_cache *create_kmalloc_cache(const char *name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff831f198c)
Location: mm/slab_common.c:657
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff831f198c-ffffffff831f1a2c: create_kmalloc_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kmem_cache *create_kmalloc_cache(const char *name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff832d72fd)
Location: mm/slab_common.c:671
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff832d72fd-ffffffff832d739d: create_kmalloc_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kmem_cache *create_kmalloc_cache(const char *name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8348bf21)
Location: mm/slab_common.c:671
Inline: False
Direct callers:
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff8348bf21-ffffffff8348bfcd: create_kmalloc_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kmem_cache *create_kmalloc_cache(const char *name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff83ebcfb0)
Location: mm/slab_common.c:662
Inline: False
Direct callers:
  - mm/slab_common.c:new_kmalloc_cache
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff83ebcfb0-ffffffff83ebd066: create_kmalloc_cache (STB_GLOBAL)
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
In mm/slab_common.c (ffffffff836e5724)
Location: mm/slab_common.c:661
Inline: True
Inline callers:
  - mm/slab_common.c:new_kmalloc_cache
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
In mm/slab_common.c (ffffffff83917f19)
Location: mm/slab_common.c:637
Inline: True
Inline callers:
  - mm/slab_common.c:new_kmalloc_cache
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
struct kmem_cache *create_kmalloc_cache(const char *name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff80001145554c)
Location: mm/slab_common.c:1074
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
```
**Symbols:**

```
ffff80001145554c-ffff800011455608: create_kmalloc_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kmem_cache *create_kmalloc_cache(const char *name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c153050c)
Location: mm/slab_common.c:1074
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
```
**Symbols:**

```
c153050c-c15305c0: create_kmalloc_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kmem_cache *create_kmalloc_cache(const char *name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c00000000137e1bc)
Location: mm/slab_common.c:1074
Inline: False
Direct callers:
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
c00000000137e1bc-c00000000137e2a8: create_kmalloc_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kmem_cache *create_kmalloc_cache(const char *name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0000145f6)
Location: mm/slab_common.c:1074
Inline: False
Direct callers:
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffe0000145f6-ffffffe0000146a0: create_kmalloc_cache (STB_GLOBAL)
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
struct kmem_cache *create_kmalloc_cache(const char *name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff828c58d7)
Location: mm/slab_common.c:1074
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff828c58d7-ffffffff828c5981: create_kmalloc_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kmem_cache *create_kmalloc_cache(const char *name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff828bdffc)
Location: mm/slab_common.c:1074
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff828bdffc-ffffffff828be0a6: create_kmalloc_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kmem_cache *create_kmalloc_cache(const char *name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff828d8657)
Location: mm/slab_common.c:1074
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff828d8657-ffffffff828d8701: create_kmalloc_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kmem_cache *create_kmalloc_cache(const char *name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff828dda78)
Location: mm/slab_common.c:1074
Inline: False
Direct callers:
  - mm/slab_common.c:create_kmalloc_caches
  - mm/slab_common.c:new_kmalloc_cache
```
**Symbols:**

```
ffffffff828dda78-ffffffff828ddb22: create_kmalloc_cache (STB_GLOBAL)
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
<b>Param added. </b>
<code>unsigned int useroffset</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int usersize</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t size</code> ➡️ <code>unsigned int size</code>
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
