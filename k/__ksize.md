# Function: <code>__ksize</code>

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
In mm/slub.c (ffffffff811e8a55)
Location: mm/slub.c:3588
Inline: True
Inline callers:
  - mm/slub.c:ksize
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
In mm/slub.c (ffffffff81206745)
Location: mm/slub.c:3811
Inline: True
Inline callers:
  - mm/slub.c:ksize
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
In mm/slub.c (ffffffff81218775)
Location: mm/slub.c:3833
Inline: True
Inline callers:
  - mm/slub.c:ksize
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
In mm/slub.c (ffffffff81223fe6)
Location: mm/slub.c:3838
Inline: True
Inline callers:
  - mm/slub.c:ksize
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
In mm/slub.c (ffffffff8123f625)
Location: mm/slub.c:3854
Inline: True
Inline callers:
  - mm/slub.c:ksize
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
In mm/slub.c (ffffffff81262ca5)
Location: mm/slub.c:3863
Inline: True
Inline callers:
  - mm/slub.c:ksize
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
In mm/slub.c (ffffffff81277525)
Location: mm/slub.c:3915
Inline: True
Inline callers:
  - mm/slub.c:ksize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
size_t __ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3922
Inline: False
Direct callers:
  - mm/slab_common.c:ksize
```
**Symbols:**

```
ffffffff8129b5c5-ffffffff8129b5d8: __ksize.cold (STB_LOCAL)
ffffffff81293d20-ffffffff81293de8: __ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t __ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a3a80)
Location: mm/slub.c:3936
Inline: False
Direct callers:
  - mm/slab_common.c:ksize
```
**Symbols:**

```
ffffffff812a3a80-ffffffff812a3b5c: __ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t __ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812d8360)
Location: mm/slub.c:4013
Inline: False
Direct callers:
  - mm/slab_common.c:kzfree
  - mm/slab_common.c:krealloc
```
**Symbols:**

```
ffffffff812d8360-ffffffff812d843c: __ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t __ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e3dc0)
Location: mm/slub.c:4100
Inline: False
Direct callers:
  - mm/mempool.c:mempool_exit
  - mm/slab_common.c:kfree_sensitive
  - mm/slab_common.c:krealloc
```
**Symbols:**

```
ffffffff812e3dc0-ffffffff812e3e9c: __ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t __ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812eb7f0)
Location: mm/slub.c:4173
Inline: False
Direct callers:
  - mm/mempool.c:mempool_exit
  - mm/slab_common.c:kfree_sensitive
  - mm/slab_common.c:krealloc
```
**Symbols:**

```
ffffffff812eb7f0-ffffffff812eb8cc: __ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
size_t __ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:4519
Inline: False
Direct callers:
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/mempool.c:mempool_exit
  - mm/slab_common.c:kfree_sensitive
  - mm/slab_common.c:krealloc
```
**Symbols:**

```
ffffffff81cc10e1-ffffffff81cc10fa: __ksize.cold (STB_LOCAL)
ffffffff813341c0-ffffffff813342b6: __ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t __ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:4551
Inline: False
Direct callers:
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/mempool.c:mempool_exit
  - mm/slab_common.c:kfree_sensitive
  - mm/slab_common.c:krealloc
```
**Symbols:**

```
ffffffff81e737f7-ffffffff81e73810: __ksize.cold (STB_LOCAL)
ffffffff813a6ab0-ffffffff813a6bee: __ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t __ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:1036
Inline: False
Direct callers:
  - mm/slab_common.c:kfree_sensitive
  - mm/slab_common.c:krealloc
```
**Symbols:**

```
ffffffff8206347e-ffffffff820634b7: __ksize.cold (STB_LOCAL)
ffffffff813a2390-ffffffff813a2538: __ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t __ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:1050
Inline: False
Direct callers:
  - mm/slab_common.c:kfree_sensitive
  - mm/slab_common.c:krealloc
```
**Symbols:**

```
ffffffff820e2bab-ffffffff820e2bc4: __ksize.cold (STB_LOCAL)
ffffffff813d5880-ffffffff813d59fe: __ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t __ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:951
Inline: False
Direct callers:
  - mm/slab_common.c:kfree_sensitive
  - mm/slab_common.c:krealloc
```
**Symbols:**

```
ffffffff821bf4b0-ffffffff821bf4ec: __ksize.cold (STB_LOCAL)
ffffffff813ff530-ffffffff813ff6ce: __ksize (STB_GLOBAL)
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
size_t __ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010342fc8)
Location: mm/slub.c:3936
Inline: False
Direct callers:
  - mm/slab_common.c:ksize
```
**Symbols:**

```
ffff800010342fc8-ffff8000103430bc: __ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t __ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054874c)
Location: mm/slub.c:3936
Inline: False
Direct callers:
  - mm/slab_common.c:ksize
```
**Symbols:**

```
c054874c-c0548824: __ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t __ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c0000000004205c0)
Location: mm/slub.c:3936
Inline: False
Direct callers:
  - mm/slab_common.c:ksize
```
**Symbols:**

```
c0000000004205c0-c0000000004206d4: __ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t __ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe000236bbe)
Location: mm/slub.c:3936
Inline: False
Direct callers:
  - mm/slab_common.c:ksize
```
**Symbols:**

```
ffffffe000236bbe-ffffffe000236c8e: __ksize (STB_GLOBAL)
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
size_t __ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129c060)
Location: mm/slub.c:3936
Inline: False
Direct callers:
  - mm/slab_common.c:ksize
```
**Symbols:**

```
ffffffff8129c060-ffffffff8129c13c: __ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t __ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8128dc20)
Location: mm/slub.c:3936
Inline: False
Direct callers:
  - mm/slab_common.c:ksize
```
**Symbols:**

```
ffffffff8128dc20-ffffffff8128dcfc: __ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t __ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81299e70)
Location: mm/slub.c:3936
Inline: False
Direct callers:
  - mm/slab_common.c:ksize
```
**Symbols:**

```
ffffffff81299e70-ffffffff81299f4c: __ksize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t __ksize(const void *object);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a9cb0)
Location: mm/slub.c:3936
Inline: False
Direct callers:
  - mm/slab_common.c:ksize
```
**Symbols:**

```
ffffffff812a9cb0-ffffffff812a9d8c: __ksize (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
