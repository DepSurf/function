# Function: <code>bitmap_onto</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff813f9690)
Location: lib/bitmap.c:868
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffffffff813f9690-ffffffff813f9722: bitmap_onto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814406c0)
Location: lib/bitmap.c:870
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffffffff814406c0-ffffffff8144074e: bitmap_onto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8145d7c0)
Location: lib/bitmap.c:912
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffffffff8145d7c0-ffffffff8145d84e: bitmap_onto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81462e30)
Location: lib/bitmap.c:918
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffffffff81462e30-ffffffff81462ec1: bitmap_onto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8148ed40)
Location: lib/bitmap.c:914
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffffffff8148ed40-ffffffff8148edd1: bitmap_onto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814c3620)
Location: lib/bitmap.c:911
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffffffff814c3620-ffffffff814c36b0: bitmap_onto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d8080)
Location: lib/bitmap.c:906
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffffffff814d8080-ffffffff814d8110: bitmap_onto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815041c0)
Location: lib/bitmap.c:935
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffffffff815041c0-ffffffff8150424c: bitmap_onto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815221d0)
Location: lib/bitmap.c:955
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffffffff815221d0-ffffffff8152225c: bitmap_onto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81585530)
Location: lib/bitmap.c:1030
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffffffff81585530-ffffffff815855bc: bitmap_onto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a2630)
Location: lib/bitmap.c:1030
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffffffff815a2630-ffffffff815a26bc: bitmap_onto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a9540)
Location: lib/bitmap.c:1041
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffffffff815a9540-ffffffff815a95d4: bitmap_onto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816126c0)
Location: lib/bitmap.c:1172
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffffffff816126c0-ffffffff81612754: bitmap_onto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816deb10)
Location: lib/bitmap.c:1189
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffffffff816deb10-ffffffff816debc5: bitmap_onto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff817cec20)
Location: lib/bitmap.c:1170
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffffffff817cec20-ffffffff817cecad: bitmap_onto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8180d0d0)
Location: lib/bitmap.c:1170
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffffffff8180d0d0-ffffffff8180d15d: bitmap_onto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81852d80)
Location: lib/bitmap.c:657
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffffffff81852d80-ffffffff81852e0d: bitmap_onto (STB_GLOBAL)
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
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062bcb8)
Location: lib/bitmap.c:955
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffff80001062bcb8-ffff80001062bdbc: bitmap_onto (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007ce3f0)
Location: lib/bitmap.c:955
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
c0000000007ce3f0-c0000000007ce528: bitmap_onto (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8151a7b0)
Location: lib/bitmap.c:955
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffffffff8151a7b0-ffffffff8151a83c: bitmap_onto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8150aaa0)
Location: lib/bitmap.c:955
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffffffff8150aaa0-ffffffff8150ab2c: bitmap_onto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81516840)
Location: lib/bitmap.c:955
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffffffff81516840-ffffffff815168cc: bitmap_onto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bitmap_onto(long unsigned int *dst, const long unsigned int *orig, const long unsigned int *relmap, unsigned int bits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152ffd0)
Location: lib/bitmap.c:955
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_relative_nodemask
```
**Symbols:**

```
ffffffff8152ffd0-ffffffff8153005c: bitmap_onto (STB_GLOBAL)
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
