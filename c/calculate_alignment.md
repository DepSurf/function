# Function: <code>calculate_alignment</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int calculate_alignment(long unsigned int flags, long unsigned int align, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811b2f50)
Location: mm/slab_common.c:296
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:find_mergeable
  - mm/slab_common.c:create_boot_cache
```
**Symbols:**

```
ffffffff811b4710-ffffffff811b4756: calculate_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int calculate_alignment(long unsigned int flags, long unsigned int align, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81fb3b0b)
Location: mm/slab_common.c:301
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:find_mergeable
```
**Symbols:**

```
ffffffff811cd7c0-ffffffff811cd806: calculate_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int calculate_alignment(long unsigned int flags, long unsigned int align, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81ff04c8)
Location: mm/slab_common.c:301
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:find_mergeable
```
**Symbols:**

```
ffffffff811dd890-ffffffff811dd8d6: calculate_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int calculate_alignment(long unsigned int flags, long unsigned int align, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff820d28d1)
Location: mm/slab_common.c:335
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:find_mergeable
```
**Symbols:**

```
ffffffff811e7630-ffffffff811e7676: calculate_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int calculate_alignment(slab_flags_t flags, long unsigned int align, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff826db2f8)
Location: mm/slab_common.c:344
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create
  - mm/slab_common.c:find_mergeable
```
**Symbols:**

```
ffffffff811fd870-ffffffff811fd8b6: calculate_alignment (STB_GLOBAL)
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
In mm/slab_common.c (ffffffff827057c5)
Location: mm/slab_common.c:265
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:find_mergeable
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
In mm/slab_common.c (ffffffff828bcf0c)
Location: mm/slab_common.c:265
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:find_mergeable
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
In mm/slab_common.c (ffffffff828d4501)
Location: mm/slab_common.c:280
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:find_mergeable
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
In mm/slab_common.c (ffffffff828dc992)
Location: mm/slab_common.c:281
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:find_mergeable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff82cfa4bd)
Location: mm/slab_common.c:281
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:find_mergeable
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
In mm/slab_common.c (ffffffff82fe71f5)
Location: mm/slab_common.c:138
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:find_mergeable
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
In mm/slab_common.c (ffffffff831f192d)
Location: mm/slab_common.c:146
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:find_mergeable
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
In mm/slab_common.c (ffffffff832d729e)
Location: mm/slab_common.c:146
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:find_mergeable
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
In mm/slab_common.c (ffffffff8348beae)
Location: mm/slab_common.c:139
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:find_mergeable
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
In mm/slab_common.c (ffffffff83ebcf1b)
Location: mm/slab_common.c:111
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:find_mergeable
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
In mm/slab_common.c (ffffffff836e559b)
Location: mm/slab_common.c:113
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:find_mergeable
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
In mm/slab_common.c (ffffffff83917d8b)
Location: mm/slab_common.c:112
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:find_mergeable
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
In mm/slab_common.c (ffff8000114554b8)
Location: mm/slab_common.c:281
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:find_mergeable
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
In mm/slab_common.c (c1530488)
Location: mm/slab_common.c:281
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:find_mergeable
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
In mm/slab_common.c (c00000000137e10c)
Location: mm/slab_common.c:281
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:find_mergeable
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
In mm/slab_common.c (ffffffe000014576)
Location: mm/slab_common.c:281
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:find_mergeable
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
In mm/slab_common.c (ffffffff828c5846)
Location: mm/slab_common.c:281
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:find_mergeable
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
In mm/slab_common.c (ffffffff828bdf6b)
Location: mm/slab_common.c:281
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:find_mergeable
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
In mm/slab_common.c (ffffffff828d85c6)
Location: mm/slab_common.c:281
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:find_mergeable
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
In mm/slab_common.c (ffffffff828dd9e7)
Location: mm/slab_common.c:281
Inline: True
Inline callers:
  - mm/slab_common.c:create_boot_cache
  - mm/slab_common.c:kmem_cache_create_usercopy
  - mm/slab_common.c:find_mergeable
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
</ul>
