# Function: <code>print_trailer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct page *page, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e8040)
Location: mm/slub.c:619
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:check_object
  - mm/slub.c:on_freelist
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff811e8040-ffffffff811e8228: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct page *page, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812072c0)
Location: mm/slub.c:630
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff812072c0-ffffffff8120750d: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct page *page, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812192f0)
Location: mm/slub.c:627
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff812192f0-ffffffff81219536: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct page *page, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81224ef0)
Location: mm/slub.c:629
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff81224ef0-ffffffff8122510e: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct page *page, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81240560)
Location: mm/slub.c:664
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff81240560-ffffffff81240781: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct page *page, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8126ac5f)
Location: mm/slub.c:650
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff8126ac5f-ffffffff8126ae3f: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct page *page, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127f4ef)
Location: mm/slub.c:655
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff8127f4ef-ffffffff8127f6cf: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct page *page, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129b2cb)
Location: mm/slub.c:647
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff8129b2cb-ffffffff8129b4ab: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct page *page, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ab18b)
Location: mm/slub.c:647
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff812ab18b-ffffffff812ab36b: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct page *page, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812df9e8)
Location: mm/slub.c:696
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff812df9e8-ffffffff812dfb40: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct page *page, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81be9334)
Location: mm/slub.c:691
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff81be9334-ffffffff81be948c: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct page *page, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81bdb4ae)
Location: mm/slub.c:703
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff81bdb4ae-ffffffff81bdb603: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct page *page, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81cc1393)
Location: mm/slub.c:816
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff81cc1393-ffffffff81cc14e8: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct slab *slab, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81e738a7)
Location: mm/slub.c:849
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff81e738a7-ffffffff81e73a07: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct slab *slab, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81428090)
Location: mm/slub.c:913
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff81428090-ffffffff814282c9: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct slab *slab, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145d450)
Location: mm/slub.c:934
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff8145d450-ffffffff8145d685: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct slab *slab, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81457b50)
Location: mm/slub.c:1047
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:check_bytes_and_report
```
**Symbols:**

```
ffffffff81457b50-ffffffff81457d85: print_trailer (STB_LOCAL)
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
void print_trailer(struct kmem_cache *s, struct page *page, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034d6e4)
Location: mm/slub.c:647
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:object_err
```
**Symbols:**

```
ffff80001034d6e4-ffff80001034d8cc: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct page *page, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c055092c)
Location: mm/slub.c:647
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:object_err
```
**Symbols:**

```
c055092c-c0550b30: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct page *page, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c00000000042cfc8)
Location: mm/slub.c:647
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:object_err
```
**Symbols:**

```
c00000000042cfc8-c00000000042d22c: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct page *page, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023dd0e)
Location: mm/slub.c:647
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffe00023dd0e-ffffffe00023dee8: print_trailer (STB_LOCAL)
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
void print_trailer(struct kmem_cache *s, struct page *page, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a376b)
Location: mm/slub.c:647
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff812a376b-ffffffff812a394b: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct page *page, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129523b)
Location: mm/slub.c:647
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff8129523b-ffffffff8129541b: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct page *page, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a157b)
Location: mm/slub.c:647
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff812a157b-ffffffff812a175b: print_trailer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void print_trailer(struct kmem_cache *s, struct page *page, u8 *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812b172b)
Location: mm/slub.c:647
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff812b172b-ffffffff812b190b: print_trailer (STB_LOCAL)
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
