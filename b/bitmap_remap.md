# Function: <code>bitmap_remap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff813f9be0)
Location: lib/bitmap.c:708
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffffffff813f9be0-ffffffff813f9cb8: bitmap_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81440c30)
Location: lib/bitmap.c:710
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffffffff81440c30-ffffffff81440d08: bitmap_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8145de50)
Location: lib/bitmap.c:752
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffffffff8145de50-ffffffff8145df28: bitmap_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81463150)
Location: lib/bitmap.c:752
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffffffff81463150-ffffffff81463224: bitmap_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8148f060)
Location: lib/bitmap.c:748
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffffffff8148f060-ffffffff8148f134: bitmap_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814c3ca0)
Location: lib/bitmap.c:745
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffffffff814c3ca0-ffffffff814c3d73: bitmap_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d8390)
Location: lib/bitmap.c:740
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffffffff814d8390-ffffffff814d8463: bitmap_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81504070)
Location: lib/bitmap.c:771
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffffffff81504070-ffffffff81504146: bitmap_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81522080)
Location: lib/bitmap.c:791
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffffffff81522080-ffffffff81522156: bitmap_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81585380)
Location: lib/bitmap.c:866
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffffffff81585380-ffffffff8158547a: bitmap_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a2480)
Location: lib/bitmap.c:866
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffffffff815a2480-ffffffff815a257a: bitmap_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a93f0)
Location: lib/bitmap.c:877
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffffffff815a93f0-ffffffff815a94cd: bitmap_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/bitmap.c (ffffffff81612550)
Location: lib/bitmap.c:1005
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffffffff81612550-ffffffff81612624: bitmap_remap.part.0 (STB_LOCAL)
ffffffff81612630-ffffffff81612641: bitmap_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/bitmap.c (ffffffff816de950)
Location: lib/bitmap.c:1022
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffffffff816de950-ffffffff816dea44: bitmap_remap.part.0 (STB_LOCAL)
ffffffff816dea50-ffffffff816dea7f: bitmap_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/bitmap.c (ffffffff817ce530)
Location: lib/bitmap.c:1003
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffffffff817ce530-ffffffff817ce5fa: bitmap_remap.part.0 (STB_LOCAL)
ffffffff817ce610-ffffffff817ce63f: bitmap_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/bitmap.c (ffffffff8180c9e0)
Location: lib/bitmap.c:1003
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffffffff8180c9e0-ffffffff8180caaa: bitmap_remap.part.0 (STB_LOCAL)
ffffffff8180cac0-ffffffff8180caef: bitmap_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/bitmap.c (ffffffff81852a40)
Location: lib/bitmap.c:490
Inline: True
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffffffff81852a40-ffffffff81852b0a: bitmap_remap.part.0 (STB_LOCAL)
ffffffff81852b20-ffffffff81852b4f: bitmap_remap (STB_GLOBAL)
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
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062bac0)
Location: lib/bitmap.c:791
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffff80001062bac0-ffff80001062bc18: bitmap_remap (STB_GLOBAL)
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
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007ce130)
Location: lib/bitmap.c:791
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
c0000000007ce130-c0000000007ce308: bitmap_remap (STB_GLOBAL)
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
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8151a660)
Location: lib/bitmap.c:791
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffffffff8151a660-ffffffff8151a736: bitmap_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8150a950)
Location: lib/bitmap.c:791
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffffffff8150a950-ffffffff8150aa26: bitmap_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815166f0)
Location: lib/bitmap.c:791
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffffffff815166f0-ffffffff815167c6: bitmap_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bitmap_remap(long unsigned int *dst, const long unsigned int *src, const long unsigned int *old, const long unsigned int *new, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152fe80)
Location: lib/bitmap.c:791
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
```
**Symbols:**

```
ffffffff8152fe80-ffffffff8152ff56: bitmap_remap (STB_GLOBAL)
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
