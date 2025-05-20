# Function: <code>sgl_free_n_order</code>

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
void sgl_free_n_order(struct scatterlist *sgl, int nents, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814c4050)
Location: lib/scatterlist.c:552
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc_order
```
**Symbols:**

```
ffffffff814c4050-ffffffff814c40c7: sgl_free_n_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sgl_free_n_order(struct scatterlist *sgl, int nents, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814d8750)
Location: lib/scatterlist.c:552
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc_order
```
**Symbols:**

```
ffffffff814d8750-ffffffff814d87c7: sgl_free_n_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sgl_free_n_order(struct scatterlist *sgl, int nents, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815046b0)
Location: lib/scatterlist.c:560
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc_order
```
**Symbols:**

```
ffffffff815046b0-ffffffff81504728: sgl_free_n_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sgl_free_n_order(struct scatterlist *sgl, int nents, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81522640)
Location: lib/scatterlist.c:560
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc_order
```
**Symbols:**

```
ffffffff81522640-ffffffff815226b8: sgl_free_n_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void sgl_free_n_order(struct scatterlist *sgl, int nents, int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81585970)
Location: lib/scatterlist.c:560
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
```
**Symbols:**

```
ffffffff81585970-ffffffff815859e8: sgl_free_n_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sgl_free_n_order(struct scatterlist *sgl, int nents, int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a3200)
Location: lib/scatterlist.c:641
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
```
**Symbols:**

```
ffffffff815a2a50-ffffffff815a2ac8: sgl_free_n_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sgl_free_n_order(struct scatterlist *sgl, int nents, int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815aa5c0)
Location: lib/scatterlist.c:641
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
```
**Symbols:**

```
ffffffff815a9980-ffffffff815a99f8: sgl_free_n_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void sgl_free_n_order(struct scatterlist *sgl, int nents, int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81613850)
Location: lib/scatterlist.c:672
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
```
**Symbols:**

```
ffffffff81612bc0-ffffffff81612c38: sgl_free_n_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void sgl_free_n_order(struct scatterlist *sgl, int nents, int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816e0110)
Location: lib/scatterlist.c:672
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
```
**Symbols:**

```
ffffffff816df300-ffffffff816df38f: sgl_free_n_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void sgl_free_n_order(struct scatterlist *sgl, int nents, int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff817d0350)
Location: lib/scatterlist.c:682
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
```
**Symbols:**

```
ffffffff817cf510-ffffffff817cf59f: sgl_free_n_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void sgl_free_n_order(struct scatterlist *sgl, int nents, int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8180efa0)
Location: lib/scatterlist.c:684
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
```
**Symbols:**

```
ffffffff8180d9c0-ffffffff8180da4f: sgl_free_n_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void sgl_free_n_order(struct scatterlist *sgl, int nents, int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81854c20)
Location: lib/scatterlist.c:685
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
```
**Symbols:**

```
ffffffff81853670-ffffffff818536ff: sgl_free_n_order (STB_GLOBAL)
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
void sgl_free_n_order(struct scatterlist *sgl, int nents, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffff80001062c2c8)
Location: lib/scatterlist.c:560
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc_order
```
**Symbols:**

```
ffff80001062c2c8-ffff80001062c360: sgl_free_n_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sgl_free_n_order(struct scatterlist *sgl, int nents, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c07d2c90)
Location: lib/scatterlist.c:560
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc_order
```
**Symbols:**

```
c07d2c90-c07d2d18: sgl_free_n_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sgl_free_n_order(struct scatterlist *sgl, int nents, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c0000000007ceca0)
Location: lib/scatterlist.c:560
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc_order
```
**Symbols:**

```
c0000000007ceca0-c0000000007ced84: sgl_free_n_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sgl_free_n_order(struct scatterlist *sgl, int nents, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffe00045c520)
Location: lib/scatterlist.c:560
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc_order
```
**Symbols:**

```
ffffffe00045c520-ffffffe00045c592: sgl_free_n_order (STB_GLOBAL)
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
void sgl_free_n_order(struct scatterlist *sgl, int nents, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8151ac20)
Location: lib/scatterlist.c:560
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc_order
```
**Symbols:**

```
ffffffff8151ac20-ffffffff8151ac98: sgl_free_n_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sgl_free_n_order(struct scatterlist *sgl, int nents, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8150af10)
Location: lib/scatterlist.c:560
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc_order
```
**Symbols:**

```
ffffffff8150af10-ffffffff8150af88: sgl_free_n_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sgl_free_n_order(struct scatterlist *sgl, int nents, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81516cb0)
Location: lib/scatterlist.c:560
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc_order
```
**Symbols:**

```
ffffffff81516cb0-ffffffff81516d28: sgl_free_n_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sgl_free_n_order(struct scatterlist *sgl, int nents, int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81530440)
Location: lib/scatterlist.c:560
Inline: False
Direct callers:
  - lib/scatterlist.c:sgl_alloc_order
```
**Symbols:**

```
ffffffff81530440-ffffffff815304b8: sgl_free_n_order (STB_GLOBAL)
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
