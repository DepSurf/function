# Function: <code>__kmem_cache_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811ee640)
Location: mm/slub.c:3966
Inline: False
Direct callers:
  - mm/slab_common.c:create_cache
  - mm/slab_common.c:create_boot_cache
```
**Symbols:**

```
ffffffff811ee640-ffffffff811eea38: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120dc50)
Location: mm/slub.c:4193
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffffffff8120dc50-ffffffff8120dda5: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121fc90)
Location: mm/slub.c:4199
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffffffff8121fc90-ffffffff8121fde5: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8122b5c0)
Location: mm/slub.c:4241
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffffffff8122b5c0-ffffffff8122bb56: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81246cc0)
Location: mm/slub.c:4257
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffffffff81246cc0-ffffffff81247261: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8126a050)
Location: mm/slub.c:4259
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffffffff8126a050-ffffffff8126a19c: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127e910)
Location: mm/slub.c:4311
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffffffff8127e910-ffffffff8127ea5c: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:4302
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffffffff8129bb19-ffffffff8129bb2c: __kmem_cache_create.cold (STB_LOCAL)
ffffffff8129a6f0-ffffffff8129a83e: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812aa5b0)
Location: mm/slub.c:4320
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffffffff812aa5b0-ffffffff812aa6fc: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812df2d0)
Location: mm/slub.c:4397
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffffffff812df2d0-ffffffff812df413: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812eaff0)
Location: mm/slub.c:4447
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff812eaff0-ffffffff812eb089: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812f2ac0)
Location: mm/slub.c:4528
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff812f2ac0-ffffffff812f2b59: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8133b800)
Location: mm/slub.c:4879
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff8133b800-ffffffff8133b85c: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813adf00)
Location: mm/slub.c:4911
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff813adf00-ffffffff813adf64: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142e2c0)
Location: mm/slub.c:5086
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff8142e2c0-ffffffff8142e324: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81463a00)
Location: mm/slub.c:5101
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff81463a00-ffffffff81463a64: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145fc50)
Location: mm/slub.c:5712
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
```
**Symbols:**

```
ffffffff8145fc50-ffffffff8145fcb4: __kmem_cache_create (STB_GLOBAL)
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
int __kmem_cache_create(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034c420)
Location: mm/slub.c:4320
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffff80001034c420-ffff80001034c5a4: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054ffd8)
Location: mm/slub.c:4320
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
c054ffd8-c0550154: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c00000000042be70)
Location: mm/slub.c:4320
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
c00000000042be70-c00000000042c090: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023d580)
Location: mm/slub.c:4320
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffffffe00023d580-ffffffe00023d694: __kmem_cache_create (STB_GLOBAL)
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
int __kmem_cache_create(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a2b90)
Location: mm/slub.c:4320
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffffffff812a2b90-ffffffff812a2cdc: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81294660)
Location: mm/slub.c:4320
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffffffff81294660-ffffffff812947ac: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a09a0)
Location: mm/slub.c:4320
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffffffff812a09a0-ffffffff812a0aec: __kmem_cache_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __kmem_cache_create(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812b0ae0)
Location: mm/slub.c:4320
Inline: False
Direct callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:create_cache
```
**Symbols:**

```
ffffffff812b0ae0-ffffffff812b0c2c: __kmem_cache_create (STB_GLOBAL)
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
