# Function: <code>alloc_debug_processing</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int alloc_debug_processing(struct kmem_cache *s, struct page *page, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e8d40)
Location: mm/slub.c:1032
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff811e8d40-ffffffff811e8ebd: alloc_debug_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int alloc_debug_processing(struct kmem_cache *s, struct page *page, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81208d60)
Location: mm/slub.c:1074
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81208d60-ffffffff81208f08: alloc_debug_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int alloc_debug_processing(struct kmem_cache *s, struct page *page, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121ade0)
Location: mm/slub.c:1073
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8121ade0-ffffffff8121af82: alloc_debug_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int alloc_debug_processing(struct kmem_cache *s, struct page *page, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81226820)
Location: mm/slub.c:1075
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81226820-ffffffff812269c2: alloc_debug_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int alloc_debug_processing(struct kmem_cache *s, struct page *page, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81241860)
Location: mm/slub.c:1110
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81241860-ffffffff812419ff: alloc_debug_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int alloc_debug_processing(struct kmem_cache *s, struct page *page, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1098
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81265f80-ffffffff812660b1: alloc_debug_processing (STB_LOCAL)
ffffffff8126af28-ffffffff8126af81: alloc_debug_processing.cold.94 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int alloc_debug_processing(struct kmem_cache *s, struct page *page, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1113
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8127acc0-ffffffff8127adf1: alloc_debug_processing (STB_LOCAL)
ffffffff8127f7b8-ffffffff8127f811: alloc_debug_processing.cold.96 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int alloc_debug_processing(struct kmem_cache *s, struct page *page, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1104
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81296610-ffffffff8129673e: alloc_debug_processing (STB_LOCAL)
ffffffff8129b6a2-ffffffff8129b714: alloc_debug_processing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int alloc_debug_processing(struct kmem_cache *s, struct page *page, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1105
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812a63e0-ffffffff812a650e: alloc_debug_processing (STB_LOCAL)
ffffffff812ab52e-ffffffff812ab5a0: alloc_debug_processing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int alloc_debug_processing(struct kmem_cache *s, struct page *page, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1150
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812db370-ffffffff812db4ad: alloc_debug_processing (STB_LOCAL)
ffffffff812dffaf-ffffffff812e0023: alloc_debug_processing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int alloc_debug_processing(struct kmem_cache *s, struct page *page, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1145
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812e5df0-ffffffff812e5f2d: alloc_debug_processing (STB_LOCAL)
ffffffff81be967a-ffffffff81be96ee: alloc_debug_processing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int alloc_debug_processing(struct kmem_cache *s, struct page *page, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1157
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812ed590-ffffffff812ed6cd: alloc_debug_processing (STB_LOCAL)
ffffffff81bdb6f3-ffffffff81bdb767: alloc_debug_processing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int alloc_debug_processing(struct kmem_cache *s, struct page *page, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1281
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff813358f0-ffffffff81335a2d: alloc_debug_processing (STB_LOCAL)
ffffffff81cc1661-ffffffff81cc16d5: alloc_debug_processing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int alloc_debug_processing(struct kmem_cache *s, struct slab *slab, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1326
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff813a71c0-ffffffff813a7332: alloc_debug_processing (STB_LOCAL)
ffffffff81e73c4c-ffffffff81e73cbb: alloc_debug_processing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool alloc_debug_processing(struct kmem_cache *s, struct slab *slab, void *object, int orig_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81429750)
Location: mm/slub.c:1421
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81429750-ffffffff8142990b: alloc_debug_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool alloc_debug_processing(struct kmem_cache *s, struct slab *slab, void *object, int orig_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145eb30)
Location: mm/slub.c:1434
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8145eb30-ffffffff8145eceb: alloc_debug_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool alloc_debug_processing(struct kmem_cache *s, struct slab *slab, void *object, int orig_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81458530)
Location: mm/slub.c:1558
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81458530-ffffffff814586eb: alloc_debug_processing (STB_LOCAL)
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
int alloc_debug_processing(struct kmem_cache *s, struct page *page, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff8000103475d8)
Location: mm/slub.c:1105
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffff8000103475d8-ffff80001034777c: alloc_debug_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int alloc_debug_processing(struct kmem_cache *s, struct page *page, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054bdc8)
Location: mm/slub.c:1105
Inline: False
```
**Symbols:**

```
c054bdc8-c054bf60: alloc_debug_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int alloc_debug_processing(struct kmem_cache *s, struct page *page, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c000000000425790)
Location: mm/slub.c:1105
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
c000000000425790-c000000000425998: alloc_debug_processing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int alloc_debug_processing(struct kmem_cache *s, struct page *page, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe000239e3c)
Location: mm/slub.c:1105
Inline: False
```
**Symbols:**

```
ffffffe000239e3c-ffffffe000239fb2: alloc_debug_processing (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int alloc_debug_processing(struct kmem_cache *s, struct page *page, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1105
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8129e9c0-ffffffff8129eaee: alloc_debug_processing (STB_LOCAL)
ffffffff812a3b0e-ffffffff812a3b80: alloc_debug_processing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int alloc_debug_processing(struct kmem_cache *s, struct page *page, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1105
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81290500-ffffffff8129062e: alloc_debug_processing (STB_LOCAL)
ffffffff812955de-ffffffff81295650: alloc_debug_processing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int alloc_debug_processing(struct kmem_cache *s, struct page *page, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1105
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff8129c7d0-ffffffff8129c8fe: alloc_debug_processing (STB_LOCAL)
ffffffff812a191e-ffffffff812a1990: alloc_debug_processing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int alloc_debug_processing(struct kmem_cache *s, struct page *page, void *object, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1105
Inline: False
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff812ac800-ffffffff812ac92e: alloc_debug_processing (STB_LOCAL)
ffffffff812b1ace-ffffffff812b1b40: alloc_debug_processing.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int orig_size</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
