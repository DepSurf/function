# Function: <code>__mpol_equal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e2430)
Location: mm/mempolicy.c:2115
Inline: True
Direct callers:
  - mm/mmap.c:reusable_anon_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
```
**Symbols:**

```
ffffffff811e2430-ffffffff811e24a0: __mpol_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81200e20)
Location: mm/mempolicy.c:2132
Inline: True
Direct callers:
  - mm/mmap.c:reusable_anon_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
```
**Symbols:**

```
ffffffff81200e20-ffffffff81200e8c: __mpol_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81212830)
Location: mm/mempolicy.c:2126
Inline: True
Direct callers:
  - mm/mmap.c:reusable_anon_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
```
**Symbols:**

```
ffffffff81212830-ffffffff812128cf: __mpol_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121db40)
Location: mm/mempolicy.c:2028
Inline: True
Direct callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
```
**Symbols:**

```
ffffffff8121db40-ffffffff8121dbf8: __mpol_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81238d90)
Location: mm/mempolicy.c:2090
Inline: True
Direct callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:SYSC_mbind
```
**Symbols:**

```
ffffffff81238d90-ffffffff81238e48: __mpol_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8125c2b0)
Location: mm/mempolicy.c:2147
Inline: True
Direct callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff8125c2b0-ffffffff8125c369: __mpol_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81270b80)
Location: mm/mempolicy.c:2186
Inline: True
Direct callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81270b80-ffffffff81270c50: __mpol_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128c190)
Location: mm/mempolicy.c:2207
Inline: True
Direct callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff8128c190-ffffffff8128c26f: __mpol_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129bd60)
Location: mm/mempolicy.c:2246
Inline: True
Direct callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff8129bd60-ffffffff8129be3f: __mpol_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cfa50)
Location: mm/mempolicy.c:2346
Inline: True
Direct callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
```
**Symbols:**

```
ffffffff812cfa50-ffffffff812cfb2f: __mpol_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812db520)
Location: mm/mempolicy.c:2321
Inline: True
Direct callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
```
**Symbols:**

```
ffffffff812db520-ffffffff812db5ff: __mpol_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e2ca0)
Location: mm/mempolicy.c:2326
Inline: True
Direct callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
```
**Symbols:**

```
ffffffff812e2ca0-ffffffff812e2d80: __mpol_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8132a020)
Location: mm/mempolicy.c:2244
Inline: True
Direct callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:mbind_range
  - mm/mempolicy.c:mbind_range
```
**Symbols:**

```
ffffffff8132a020-ffffffff8132a0e0: __mpol_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff813996f0)
Location: mm/mempolicy.c:2418
Inline: False
Direct callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:mbind_range
```
**Symbols:**

```
ffffffff813996f0-ffffffff813997d4: __mpol_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81419570)
Location: mm/mempolicy.c:2433
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:mbind_range
```
**Symbols:**

```
ffffffff81419570-ffffffff81419654: __mpol_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8144cb70)
Location: mm/mempolicy.c:2444
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:mbind_range
```
**Symbols:**

```
ffffffff8144cb70-ffffffff8144cc54: __mpol_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81486470)
Location: mm/mempolicy.c:2346
Inline: False
Direct callers:
  - mm/mmap.c:find_mergeable_anon_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:mbind_range
```
**Symbols:**

```
ffffffff81486470-ffffffff81486554: __mpol_equal (STB_GLOBAL)
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
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff80001033ad48)
Location: mm/mempolicy.c:2246
Inline: True
Direct callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffff80001033ad48-ffff80001033ae24: __mpol_equal (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000415810)
Location: mm/mempolicy.c:2246
Inline: True
Direct callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
```
**Symbols:**

```
c000000000415810-c00000000041595c: __mpol_equal (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81294340)
Location: mm/mempolicy.c:2246
Inline: True
Direct callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81294340-ffffffff8129441f: __mpol_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81285f50)
Location: mm/mempolicy.c:2246
Inline: True
Direct callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81285f50-ffffffff8128602f: __mpol_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81292150)
Location: mm/mempolicy.c:2246
Inline: True
Direct callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81292150-ffffffff8129222f: __mpol_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool __mpol_equal(struct mempolicy *a, struct mempolicy *b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812a1f50)
Location: mm/mempolicy.c:2246
Inline: True
Direct callers:
  - mm/mmap.c:anon_vma_compatible
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff812a1f50-ffffffff812a202f: __mpol_equal (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
