# Function: <code>sg_kmalloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff813fa120)
Location: lib/scatterlist.c:164
Inline: False
```
**Symbols:**

```
ffffffff813fa120-ffffffff813fa146: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81441170)
Location: lib/scatterlist.c:164
Inline: False
```
**Symbols:**

```
ffffffff81441170-ffffffff81441196: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8145e310)
Location: lib/scatterlist.c:164
Inline: False
```
**Symbols:**

```
ffffffff8145e310-ffffffff8145e336: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81463580)
Location: lib/scatterlist.c:164
Inline: False
```
**Symbols:**

```
ffffffff81463580-ffffffff814635a6: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8148f490)
Location: lib/scatterlist.c:164
Inline: False
```
**Symbols:**

```
ffffffff8148f490-ffffffff8148f4b6: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814c4bc0)
Location: lib/scatterlist.c:151
Inline: True
```
**Symbols:**

```
ffffffff814c4bc0-ffffffff814c4be6: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814d92b0)
Location: lib/scatterlist.c:151
Inline: True
```
**Symbols:**

```
ffffffff814d92b0-ffffffff814d92d6: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81505160)
Location: lib/scatterlist.c:149
Inline: True
```
**Symbols:**

```
ffffffff81505160-ffffffff81505188: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81523180)
Location: lib/scatterlist.c:149
Inline: True
```
**Symbols:**

```
ffffffff81523180-ffffffff815231a8: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815862a0)
Location: lib/scatterlist.c:149
Inline: True
```
**Symbols:**

```
ffffffff815862a0-ffffffff815862c8: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a35a4)
Location: lib/scatterlist.c:149
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table_from_pages
  - lib/scatterlist.c:__sg_alloc_table_from_pages
```
**Symbols:**

```
ffffffff815a3380-ffffffff815a33a8: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815aa160)
Location: lib/scatterlist.c:149
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table_from_pages
  - lib/scatterlist.c:__sg_alloc_table_from_pages
```
**Symbols:**

```
ffffffff815a9f40-ffffffff815a9f68: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816131f2)
Location: lib/scatterlist.c:149
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
```
**Symbols:**

```
ffffffff816136b0-ffffffff816136d8: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816df7e7)
Location: lib/scatterlist.c:149
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
```
**Symbols:**

```
ffffffff816dfd20-ffffffff816dfd56: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff817cfd5a)
Location: lib/scatterlist.c:149
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
```
**Symbols:**

```
ffffffff817cfb10-ffffffff817cfb46: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8180ebd4)
Location: lib/scatterlist.c:151
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
```
**Symbols:**

```
ffffffff8180e990-ffffffff8180e9c6: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81854857)
Location: lib/scatterlist.c:151
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
```
**Symbols:**

```
ffffffff81854610-ffffffff81854646: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffff80001062cec0)
Location: lib/scatterlist.c:149
Inline: True
```
**Symbols:**

```
ffff80001062cec0-ffff80001062cef8: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c07d3a64)
Location: lib/scatterlist.c:149
Inline: True
```
**Symbols:**

```
c07d3a64-c07d3ab0: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c0000000007cfd10)
Location: lib/scatterlist.c:149
Inline: True
```
**Symbols:**

```
c0000000007cfd10-c0000000007cfd70: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffe00045ce78)
Location: lib/scatterlist.c:149
Inline: True
```
**Symbols:**

```
ffffffe00045ce78-ffffffe00045ceba: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8151b760)
Location: lib/scatterlist.c:149
Inline: True
```
**Symbols:**

```
ffffffff8151b760-ffffffff8151b788: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8150ba50)
Location: lib/scatterlist.c:149
Inline: True
```
**Symbols:**

```
ffffffff8150ba50-ffffffff8150ba78: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815177f0)
Location: lib/scatterlist.c:149
Inline: True
```
**Symbols:**

```
ffffffff815177f0-ffffffff81517818: sg_kmalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct scatterlist *sg_kmalloc(unsigned int nents, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81530f90)
Location: lib/scatterlist.c:149
Inline: True
```
**Symbols:**

```
ffffffff81530f90-ffffffff81530fb8: sg_kmalloc (STB_LOCAL)
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
