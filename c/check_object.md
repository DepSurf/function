# Function: <code>check_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int check_object(struct kmem_cache *s, struct page *page, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e8340)
Location: mm/slub.c:813
Inline: False
Direct callers:
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:validate_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff811e8340-ffffffff811e8574: check_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int check_object(struct kmem_cache *s, struct page *page, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81208850)
Location: mm/slub.c:833
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81208850-ffffffff81208acf: check_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int check_object(struct kmem_cache *s, struct page *page, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121a8c0)
Location: mm/slub.c:832
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff8121a8c0-ffffffff8121ab3c: check_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int check_object(struct kmem_cache *s, struct page *page, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812262f0)
Location: mm/slub.c:834
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812262f0-ffffffff8122656f: check_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int check_object(struct kmem_cache *s, struct page *page, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81241320)
Location: mm/slub.c:869
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81241320-ffffffff812415c0: check_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int check_object(struct kmem_cache *s, struct page *page, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:857
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81264ee0-ffffffff8126516a: check_object (STB_LOCAL)
ffffffff8126af08-ffffffff8126af28: check_object.cold.93 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int check_object(struct kmem_cache *s, struct page *page, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:862
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81279c10-ffffffff81279e9a: check_object (STB_LOCAL)
ffffffff8127f798-ffffffff8127f7b8: check_object.cold.95 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int check_object(struct kmem_cache *s, struct page *page, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:854
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812955a0-ffffffff81295801: check_object (STB_LOCAL)
ffffffff8129b648-ffffffff8129b682: check_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int check_object(struct kmem_cache *s, struct page *page, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:854
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812a5380-ffffffff812a55e1: check_object (STB_LOCAL)
ffffffff812ab4f5-ffffffff812ab52e: check_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int check_object(struct kmem_cache *s, struct page *page, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:899
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812da010-ffffffff812da29f: check_object (STB_LOCAL)
ffffffff812dfedb-ffffffff812dff04: check_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int check_object(struct kmem_cache *s, struct page *page, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:894
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812e5b60-ffffffff812e5def: check_object (STB_LOCAL)
ffffffff81be9651-ffffffff81be967a: check_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int check_object(struct kmem_cache *s, struct page *page, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:906
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812ed300-ffffffff812ed58f: check_object (STB_LOCAL)
ffffffff81bdb6ca-ffffffff81bdb6f3: check_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_object(struct kmem_cache *s, struct page *page, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1032
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff81335680-ffffffff813358ee: check_object (STB_LOCAL)
ffffffff81cc1628-ffffffff81cc1661: check_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_object(struct kmem_cache *s, struct slab *slab, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1078
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff813a6f20-ffffffff813a71b2: check_object (STB_LOCAL)
ffffffff81e73c13-ffffffff81e73c4c: check_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_object(struct kmem_cache *s, struct slab *slab, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff814286f0)
Location: mm/slub.c:1161
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_slab
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff814286f0-ffffffff81428a98: check_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_object(struct kmem_cache *s, struct slab *slab, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145dab0)
Location: mm/slub.c:1182
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_slab
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff8145dab0-ffffffff8145de15: check_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int check_object(struct kmem_cache *s, struct slab *slab, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff814581b0)
Location: mm/slub.c:1295
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_slab
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff814581b0-ffffffff8145851e: check_object (STB_LOCAL)
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
int check_object(struct kmem_cache *s, struct page *page, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010346190)
Location: mm/slub.c:854
Inline: False
Direct callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffff800010346190-ffff800010346444: check_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int check_object(struct kmem_cache *s, struct page *page, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054adcc)
Location: mm/slub.c:854
Inline: False
Direct callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
c054adcc-c054b068: check_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int check_object(struct kmem_cache *s, struct page *page, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c000000000423fd0)
Location: mm/slub.c:854
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
c000000000423fd0-c000000000424354: check_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int check_object(struct kmem_cache *s, struct page *page, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe0002390e2)
Location: mm/slub.c:854
Inline: False
Direct callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffe0002390e2-ffffffe00023931c: check_object (STB_LOCAL)
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
int check_object(struct kmem_cache *s, struct page *page, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:854
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff8129d960-ffffffff8129dbc1: check_object (STB_LOCAL)
ffffffff812a3ad5-ffffffff812a3b0e: check_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int check_object(struct kmem_cache *s, struct page *page, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:854
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff8128f4f0-ffffffff8128f751: check_object (STB_LOCAL)
ffffffff812955a5-ffffffff812955de: check_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int check_object(struct kmem_cache *s, struct page *page, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:854
Inline: False
Direct callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:validate_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff8129b770-ffffffff8129b9d1: check_object (STB_LOCAL)
ffffffff812a18e5-ffffffff812a191e: check_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int check_object(struct kmem_cache *s, struct page *page, void *object, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:854
Inline: False
Direct callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__free_slab
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff812ab650-ffffffff812ab8b1: check_object (STB_LOCAL)
ffffffff812b1a95-ffffffff812b1ace: check_object.cold (STB_LOCAL)
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
