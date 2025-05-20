# Function: <code>alloc_zspage</code>

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
In mm/zsmalloc.c (ffffffff81205ada)
Location: mm/zsmalloc.c:957
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff8122af16)
Location: mm/zsmalloc.c:1112
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff8123d47b)
Location: mm/zsmalloc.c:1112
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff81248e09)
Location: mm/zsmalloc.c:1102
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff81269039)
Location: mm/zsmalloc.c:1106
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff8128e008)
Location: mm/zsmalloc.c:1089
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812a3938)
Location: mm/zsmalloc.c:1076
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812bed45)
Location: mm/zsmalloc.c:1066
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812d0ca5)
Location: mm/zsmalloc.c:1063
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct zspage *alloc_zspage(struct zs_pool *pool, struct size_class *class, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813058b0)
Location: mm/zsmalloc.c:1063
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff813058b0-ffffffff813059f1: alloc_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct zspage *alloc_zspage(struct zs_pool *pool, struct size_class *class, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81311610)
Location: mm/zsmalloc.c:1056
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff81311610-ffffffff81311751: alloc_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct zspage *alloc_zspage(struct zs_pool *pool, struct size_class *class, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81317700)
Location: mm/zsmalloc.c:1056
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff81317700-ffffffff8131790f: alloc_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct zspage *alloc_zspage(struct zs_pool *pool, struct size_class *class, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81363d60)
Location: mm/zsmalloc.c:1056
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff81363d60-ffffffff81363fdb: alloc_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct zspage *alloc_zspage(struct zs_pool *pool, struct size_class *class, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813e0ae0)
Location: mm/zsmalloc.c:1053
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff813e0ae0-ffffffff813e0da2: alloc_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct zspage *alloc_zspage(struct zs_pool *pool, struct size_class *class, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81467770)
Location: mm/zsmalloc.c:1160
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff81467770-ffffffff81467a52: alloc_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct zspage *alloc_zspage(struct zs_pool *pool, struct size_class *class, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8149cf40)
Location: mm/zsmalloc.c:985
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff8149cf40-ffffffff8149d207: alloc_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct zspage *alloc_zspage(struct zs_pool *pool, struct size_class *class, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814cc700)
Location: mm/zsmalloc.c:980
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff814cc700-ffffffff814cc9c7: alloc_zspage (STB_LOCAL)
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
In mm/zsmalloc.c (ffff80001037604c)
Location: mm/zsmalloc.c:1063
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (c0560b14)
Location: mm/zsmalloc.c:1063
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (c000000000466018)
Location: mm/zsmalloc.c:1063
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffe00024e836)
Location: mm/zsmalloc.c:1063
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812c9285)
Location: mm/zsmalloc.c:1063
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812ba2c5)
Location: mm/zsmalloc.c:1063
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812c7095)
Location: mm/zsmalloc.c:1063
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812d6943)
Location: mm/zsmalloc.c:1063
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
