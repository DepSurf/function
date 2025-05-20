# Function: <code>object_err</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void object_err(struct kmem_cache *s, struct page *page, u8 *object, char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e8431)
Location: mm/slub.c:655
Inline: True
Inline callers:
  - mm/slub.c:check_object
  - mm/slub.c:on_freelist
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff811ed990-ffffffff811ed9cb: object_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void object_err(struct kmem_cache *s, struct page *page, u8 *object, char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812093b0)
Location: mm/slub.c:670
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff8120ce20-ffffffff8120ce5b: object_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void object_err(struct kmem_cache *s, struct page *page, u8 *object, char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121b427)
Location: mm/slub.c:669
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff8121ee80-ffffffff8121eebb: object_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void object_err(struct kmem_cache *s, struct page *page, u8 *object, char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81226dd3)
Location: mm/slub.c:671
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff8122aaf0-ffffffff8122ab2b: object_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void object_err(struct kmem_cache *s, struct page *page, u8 *object, char *reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81241e0a)
Location: mm/slub.c:706
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff812461f0-ffffffff8124622b: object_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void object_err(struct kmem_cache *s, struct page *page, u8 *object, char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8126aecd)
Location: mm/slub.c:692
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff8126aecd-ffffffff8126af08: object_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void object_err(struct kmem_cache *s, struct page *page, u8 *object, char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127f75d)
Location: mm/slub.c:697
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff8127f75d-ffffffff8127f798: object_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void object_err(struct kmem_cache *s, struct page *page, u8 *object, char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129b60b)
Location: mm/slub.c:689
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff8129b60b-ffffffff8129b648: object_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void object_err(struct kmem_cache *s, struct page *page, u8 *object, char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ab4b8)
Location: mm/slub.c:689
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff812ab4b8-ffffffff812ab4f5: object_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void object_err(struct kmem_cache *s, struct page *page, u8 *object, char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812dfe9e)
Location: mm/slub.c:735
Inline: False
Direct callers:
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff812dfe9e-ffffffff812dfedb: object_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void object_err(struct kmem_cache *s, struct page *page, u8 *object, char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81be9614)
Location: mm/slub.c:730
Inline: False
Direct callers:
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff81be9614-ffffffff81be9651: object_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void object_err(struct kmem_cache *s, struct page *page, u8 *object, char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81bdb68d)
Location: mm/slub.c:742
Inline: False
Direct callers:
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff81bdb68d-ffffffff81bdb6ca: object_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void object_err(struct kmem_cache *s, struct page *page, u8 *object, char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81cc15dc)
Location: mm/slub.c:855
Inline: False
Direct callers:
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff81cc15dc-ffffffff81cc1628: object_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void object_err(struct kmem_cache *s, struct slab *slab, u8 *object, char *reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81e73a07)
Location: mm/slub.c:888
Inline: False
Direct callers:
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff81e73a07-ffffffff81e73a5d: object_err (STB_LOCAL)
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
In mm/slub.c (ffffffff8142b80e)
Location: mm/slub.c:955
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
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
In mm/slub.c (ffffffff81460d7e)
Location: mm/slub.c:976
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
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
In mm/slub.c (ffffffff81458d3e)
Location: mm/slub.c:1089
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
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
void object_err(struct kmem_cache *s, struct page *page, u8 *object, char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034d8cc)
Location: mm/slub.c:689
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
```
**Symbols:**

```
ffff80001034d8cc-ffff80001034d928: object_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void object_err(struct kmem_cache *s, struct page *page, u8 *object, char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c0550b30)
Location: mm/slub.c:689
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
```
**Symbols:**

```
c0550b30-c0550b74: object_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void object_err(struct kmem_cache *s, struct page *page, u8 *object, char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c00000000042d22c)
Location: mm/slub.c:689
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
```
**Symbols:**

```
c00000000042d22c-c00000000042d298: object_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void object_err(struct kmem_cache *s, struct page *page, u8 *object, char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023dee8)
Location: mm/slub.c:689
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffe00023dee8-ffffffe00023df3c: object_err (STB_GLOBAL)
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
void object_err(struct kmem_cache *s, struct page *page, u8 *object, char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a3a98)
Location: mm/slub.c:689
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff812a3a98-ffffffff812a3ad5: object_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void object_err(struct kmem_cache *s, struct page *page, u8 *object, char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81295568)
Location: mm/slub.c:689
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff81295568-ffffffff812955a5: object_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void object_err(struct kmem_cache *s, struct page *page, u8 *object, char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a18a8)
Location: mm/slub.c:689
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff812a18a8-ffffffff812a18e5: object_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void object_err(struct kmem_cache *s, struct page *page, u8 *object, char *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812b1a58)
Location: mm/slub.c:689
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
```
**Symbols:**

```
ffffffff812b1a58-ffffffff812b1a95: object_err (STB_GLOBAL)
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct slab *slab</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
