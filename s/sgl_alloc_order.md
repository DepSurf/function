# Function: <code>sgl_alloc_order</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct scatterlist *sgl_alloc_order(long long unsigned int length, unsigned int order, bool chainable, gfp_t gfp, unsigned int *nent_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814c4a40)
Location: lib/scatterlist.c:478
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc
```
**Symbols:**

```
ffffffff814c4a40-ffffffff814c4b9f: sgl_alloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct scatterlist *sgl_alloc_order(long long unsigned int length, unsigned int order, bool chainable, gfp_t gfp, unsigned int *nent_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814d9130)
Location: lib/scatterlist.c:478
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc
```
**Symbols:**

```
ffffffff814d9130-ffffffff814d928f: sgl_alloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct scatterlist *sgl_alloc_order(long long unsigned int length, unsigned int order, bool chainable, gfp_t gfp, unsigned int *nent_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81504fd0)
Location: lib/scatterlist.c:486
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc
```
**Symbols:**

```
ffffffff81504fd0-ffffffff81505132: sgl_alloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct scatterlist *sgl_alloc_order(long long unsigned int length, unsigned int order, bool chainable, gfp_t gfp, unsigned int *nent_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815229e0)
Location: lib/scatterlist.c:486
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc
```
**Symbols:**

```
ffffffff815229e0-ffffffff81522b42: sgl_alloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct scatterlist *sgl_alloc_order(long long unsigned int length, unsigned int order, bool chainable, gfp_t gfp, unsigned int *nent_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81586530)
Location: lib/scatterlist.c:486
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc
```
**Symbols:**

```
ffffffff81586530-ffffffff815866dc: sgl_alloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct scatterlist *sgl_alloc_order(long long unsigned int length, unsigned int order, bool chainable, gfp_t gfp, unsigned int *nent_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a3820)
Location: lib/scatterlist.c:567
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc
```
**Symbols:**

```
ffffffff815a3820-ffffffff815a39c4: sgl_alloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct scatterlist *sgl_alloc_order(long long unsigned int length, unsigned int order, bool chainable, gfp_t gfp, unsigned int *nent_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815aa740)
Location: lib/scatterlist.c:567
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc
```
**Symbols:**

```
ffffffff815aa740-ffffffff815aa8e6: sgl_alloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct scatterlist *sgl_alloc_order(long long unsigned int length, unsigned int order, bool chainable, gfp_t gfp, unsigned int *nent_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/scatterlist.c (0)
Location: lib/scatterlist.c:598
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc
```
**Symbols:**

```
ffffffff81cda7b0-ffffffff81cda824: sgl_alloc_order.cold (STB_LOCAL)
ffffffff816139d0-ffffffff81613b9e: sgl_alloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct scatterlist *sgl_alloc_order(long long unsigned int length, unsigned int order, bool chainable, gfp_t gfp, unsigned int *nent_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/scatterlist.c (0)
Location: lib/scatterlist.c:598
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc
```
**Symbols:**

```
ffffffff81e92df4-ffffffff81e92e65: sgl_alloc_order.cold (STB_LOCAL)
ffffffff816e0250-ffffffff816e0427: sgl_alloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct scatterlist *sgl_alloc_order(long long unsigned int length, unsigned int order, bool chainable, gfp_t gfp, unsigned int *nent_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/scatterlist.c (0)
Location: lib/scatterlist.c:608
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc
```
**Symbols:**

```
ffffffff82077fd7-ffffffff82078048: sgl_alloc_order.cold (STB_LOCAL)
ffffffff817d0550-ffffffff817d0727: sgl_alloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct scatterlist *sgl_alloc_order(long long unsigned int length, unsigned int order, bool chainable, gfp_t gfp, unsigned int *nent_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/scatterlist.c (0)
Location: lib/scatterlist.c:610
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc
```
**Symbols:**

```
ffffffff820f8372-ffffffff820f8405: sgl_alloc_order.cold (STB_LOCAL)
ffffffff8180f1a0-ffffffff8180f37a: sgl_alloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct scatterlist *sgl_alloc_order(long long unsigned int length, unsigned int order, bool chainable, gfp_t gfp, unsigned int *nent_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/scatterlist.c (0)
Location: lib/scatterlist.c:611
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc
```
**Symbols:**

```
ffffffff821d6141-ffffffff821d61d4: sgl_alloc_order.cold (STB_LOCAL)
ffffffff81854e20-ffffffff81854ffa: sgl_alloc_order (STB_GLOBAL)
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
struct scatterlist *sgl_alloc_order(long long unsigned int length, unsigned int order, bool chainable, gfp_t gfp, unsigned int *nent_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffff80001062cd18)
Location: lib/scatterlist.c:486
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc
```
**Symbols:**

```
ffff80001062cd18-ffff80001062ce98: sgl_alloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct scatterlist *sgl_alloc_order(long long unsigned int length, unsigned int order, bool chainable, gfp_t gfp, unsigned int *nent_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c07d3560)
Location: lib/scatterlist.c:486
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc
```
**Symbols:**

```
c07d3560-c07d3734: sgl_alloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct scatterlist *sgl_alloc_order(long long unsigned int length, unsigned int order, bool chainable, gfp_t gfp, unsigned int *nent_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c0000000007cfa70)
Location: lib/scatterlist.c:486
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc
```
**Symbols:**

```
c0000000007cfa70-c0000000007cfce8: sgl_alloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct scatterlist *sgl_alloc_order(long long unsigned int length, unsigned int order, bool chainable, gfp_t gfp, unsigned int *nent_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffe00045cb8c)
Location: lib/scatterlist.c:486
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc
```
**Symbols:**

```
ffffffe00045cb8c-ffffffe00045ccc0: sgl_alloc_order (STB_GLOBAL)
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
struct scatterlist *sgl_alloc_order(long long unsigned int length, unsigned int order, bool chainable, gfp_t gfp, unsigned int *nent_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8151afc0)
Location: lib/scatterlist.c:486
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc
```
**Symbols:**

```
ffffffff8151afc0-ffffffff8151b122: sgl_alloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct scatterlist *sgl_alloc_order(long long unsigned int length, unsigned int order, bool chainable, gfp_t gfp, unsigned int *nent_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8150b2b0)
Location: lib/scatterlist.c:486
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc
```
**Symbols:**

```
ffffffff8150b2b0-ffffffff8150b412: sgl_alloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct scatterlist *sgl_alloc_order(long long unsigned int length, unsigned int order, bool chainable, gfp_t gfp, unsigned int *nent_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81517050)
Location: lib/scatterlist.c:486
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc
```
**Symbols:**

```
ffffffff81517050-ffffffff815171b2: sgl_alloc_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct scatterlist *sgl_alloc_order(long long unsigned int length, unsigned int order, bool chainable, gfp_t gfp, unsigned int *nent_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815307e0)
Location: lib/scatterlist.c:486
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc
```
**Symbols:**

```
ffffffff815307e0-ffffffff81530942: sgl_alloc_order (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
