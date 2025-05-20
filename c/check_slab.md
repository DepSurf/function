# Function: <code>check_slab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int check_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e8c90)
Location: mm/slub.c:865
Inline: False
Direct callers:
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff811e8c90-ffffffff811e8d37: check_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int check_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81207a50)
Location: mm/slub.c:889
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81207a50-ffffffff81207b01: check_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int check_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81219a80)
Location: mm/slub.c:888
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81219a80-ffffffff81219b32: check_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int check_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81225540)
Location: mm/slub.c:890
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81225540-ffffffff812255f8: check_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int check_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81240bc0)
Location: mm/slub.c:925
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81240bc0-ffffffff81240c78: check_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int check_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:913
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81263d90-ffffffff81263e09: check_slab (STB_LOCAL)
ffffffff8126ac1a-ffffffff8126ac5f: check_slab.cold.90 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int check_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:918
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812784d0-ffffffff8127854c: check_slab (STB_LOCAL)
ffffffff8127f4aa-ffffffff8127f4ef: check_slab.cold.92 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int check_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:910
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81293c30-ffffffff81293cb3: check_slab (STB_LOCAL)
ffffffff8129b581-ffffffff8129b5c5: check_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int check_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:910
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812a3990-ffffffff812a3a13: check_slab (STB_LOCAL)
ffffffff812ab441-ffffffff812ab485: check_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int check_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:955
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812d80f0-ffffffff812d8175: check_slab (STB_LOCAL)
ffffffff812dfd00-ffffffff812dfd44: check_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int check_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:950
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812e3a60-ffffffff812e3ae5: check_slab (STB_LOCAL)
ffffffff81be9238-ffffffff81be927c: check_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int check_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:962
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812eb2e0-ffffffff812eb365: check_slab (STB_LOCAL)
ffffffff81bdb3c6-ffffffff81bdb40a: check_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1088
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81333660-ffffffff8133370d: check_slab (STB_LOCAL)
ffffffff81cc0f41-ffffffff81cc0fb0: check_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_slab(struct kmem_cache *s, struct slab *slab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1134
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff813a61d0-ffffffff813a62a6: check_slab (STB_LOCAL)
ffffffff81e73767-ffffffff81e737c4: check_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int check_slab(struct kmem_cache *s, struct slab *slab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1229
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81425f10-ffffffff81426000: check_slab (STB_LOCAL)
ffffffff820673ea-ffffffff82067409: check_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int check_slab(struct kmem_cache *s, struct slab *slab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1250
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff8145b0c0-ffffffff8145b1a4: check_slab (STB_LOCAL)
ffffffff820e6caf-ffffffff820e6cca: check_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int check_slab(struct kmem_cache *s, struct slab *slab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1374
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff814563b0-ffffffff814564a3: check_slab (STB_LOCAL)
ffffffff821c1e10-ffffffff821c1e2c: check_slab.cold (STB_LOCAL)
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
int check_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010343ea8)
Location: mm/slub.c:910
Inline: False
Direct callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffff800010343ea8-ffff800010343fa4: check_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int check_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054932c)
Location: mm/slub.c:910
Inline: False
Direct callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
c054932c-c0549420: check_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int check_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c0000000004217c0)
Location: mm/slub.c:910
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
c0000000004217c0-c0000000004218d8: check_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int check_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe000237664)
Location: mm/slub.c:910
Inline: False
Direct callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffe000237664-ffffffe000237740: check_slab (STB_LOCAL)
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
int check_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:910
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff8129bf70-ffffffff8129bff3: check_slab (STB_LOCAL)
ffffffff812a3a21-ffffffff812a3a65: check_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int check_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:910
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff8128db30-ffffffff8128dbb3: check_slab (STB_LOCAL)
ffffffff812954f1-ffffffff81295535: check_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int check_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:910
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81299d80-ffffffff81299e03: check_slab (STB_LOCAL)
ffffffff812a1831-ffffffff812a1875: check_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int check_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:910
Inline: False
Direct callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812a9bc0-ffffffff812a9c43: check_slab (STB_LOCAL)
ffffffff812b19e1-ffffffff812b1a25: check_slab.cold (STB_LOCAL)
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
