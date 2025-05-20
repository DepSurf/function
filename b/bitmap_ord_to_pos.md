# Function: <code>bitmap_ord_to_pos</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int bitmap_ord_to_pos(const long unsigned int *buf, unsigned int ord, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff813f9b90)
Location: lib/bitmap.c:664
Inline: False
Direct callers:
  - mm/mempolicy.c:node_random
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_bitremap
```
**Symbols:**

```
ffffffff813f9b90-ffffffff813f9bde: bitmap_ord_to_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int bitmap_ord_to_pos(const long unsigned int *buf, unsigned int ord, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81440be0)
Location: lib/bitmap.c:666
Inline: False
Direct callers:
  - lib/nodemask.c:node_random
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
```
**Symbols:**

```
ffffffff81440be0-ffffffff81440c2e: bitmap_ord_to_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int bitmap_ord_to_pos(const long unsigned int *buf, unsigned int ord, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8145de00)
Location: lib/bitmap.c:708
Inline: False
Direct callers:
  - lib/nodemask.c:node_random
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
```
**Symbols:**

```
ffffffff8145de00-ffffffff8145de4e: bitmap_ord_to_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int bitmap_ord_to_pos(const long unsigned int *buf, unsigned int ord, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81463100)
Location: lib/bitmap.c:708
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff81463100-ffffffff8146314e: bitmap_ord_to_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int bitmap_ord_to_pos(const long unsigned int *buf, unsigned int ord, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8148f010)
Location: lib/bitmap.c:704
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff8148f010-ffffffff8148f05e: bitmap_ord_to_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int bitmap_ord_to_pos(const long unsigned int *buf, unsigned int ord, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814c3c50)
Location: lib/bitmap.c:701
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff814c3c50-ffffffff814c3c9e: bitmap_ord_to_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int bitmap_ord_to_pos(const long unsigned int *buf, unsigned int ord, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d8340)
Location: lib/bitmap.c:696
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff814d8340-ffffffff814d838e: bitmap_ord_to_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int bitmap_ord_to_pos(const long unsigned int *buf, unsigned int ord, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81504010)
Location: lib/bitmap.c:727
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff81504010-ffffffff81504064: bitmap_ord_to_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int bitmap_ord_to_pos(const long unsigned int *buf, unsigned int ord, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81522020)
Location: lib/bitmap.c:747
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff81522020-ffffffff81522074: bitmap_ord_to_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int bitmap_ord_to_pos(const long unsigned int *buf, unsigned int ord, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815854e6)
Location: lib/bitmap.c:822
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
Direct callers:
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff81585320-ffffffff81585374: bitmap_ord_to_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int bitmap_ord_to_pos(const long unsigned int *buf, unsigned int ord, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a25e6)
Location: lib/bitmap.c:822
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
Direct callers:
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff815a2420-ffffffff815a2474: bitmap_ord_to_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int bitmap_ord_to_pos(const long unsigned int *buf, unsigned int ord, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a9390)
Location: lib/bitmap.c:833
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff815a9390-ffffffff815a93ef: bitmap_ord_to_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int bitmap_ord_to_pos(const long unsigned int *buf, unsigned int ord, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816124f0)
Location: lib/bitmap.c:961
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff816124f0-ffffffff8161254f: bitmap_ord_to_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int bitmap_ord_to_pos(const long unsigned int *buf, unsigned int ord, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816de8e0)
Location: lib/bitmap.c:978
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff816de8e0-ffffffff816de94d: bitmap_ord_to_pos (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
unsigned int bitmap_ord_to_pos(const long unsigned int *buf, unsigned int ord, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062ba58)
Location: lib/bitmap.c:747
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffff80001062ba58-ffff80001062bac0: bitmap_ord_to_pos (STB_GLOBAL)
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
unsigned int bitmap_ord_to_pos(const long unsigned int *buf, unsigned int ord, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007ce080)
Location: lib/bitmap.c:747
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
  - lib/nodemask.c:node_random
```
**Symbols:**

```
c0000000007ce080-c0000000007ce130: bitmap_ord_to_pos (STB_GLOBAL)
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
unsigned int bitmap_ord_to_pos(const long unsigned int *buf, unsigned int ord, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8151a600)
Location: lib/bitmap.c:747
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff8151a600-ffffffff8151a654: bitmap_ord_to_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int bitmap_ord_to_pos(const long unsigned int *buf, unsigned int ord, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8150a8f0)
Location: lib/bitmap.c:747
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff8150a8f0-ffffffff8150a944: bitmap_ord_to_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int bitmap_ord_to_pos(const long unsigned int *buf, unsigned int ord, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81516690)
Location: lib/bitmap.c:747
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff81516690-ffffffff815166e4: bitmap_ord_to_pos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int bitmap_ord_to_pos(const long unsigned int *buf, unsigned int ord, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152fe20)
Location: lib/bitmap.c:747
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_bitremap
  - lib/bitmap.c:bitmap_remap
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff8152fe20-ffffffff8152fe74: bitmap_ord_to_pos (STB_GLOBAL)
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
