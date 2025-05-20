# Function: <code>swiotlb_set_max_segment</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_set_max_segment(unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814796ed)
Location: lib/swiotlb.c:139
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff814794f0-ffffffff81479511: swiotlb_set_max_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_set_max_segment(unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81482a61)
Location: lib/swiotlb.c:139
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81482860-ffffffff81482887: swiotlb_set_max_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_set_max_segment(unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814beaa1)
Location: lib/swiotlb.c:140
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_late_init_with_tbl
  - lib/swiotlb.c:swiotlb_init_with_tbl
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff814be860-ffffffff814be887: swiotlb_set_max_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_set_max_segment(unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8110e85c)
Location: kernel/dma/swiotlb.c:141
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff8110d780-ffffffff8110d7a6: swiotlb_set_max_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_set_max_segment(unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81119de1)
Location: kernel/dma/swiotlb.c:135
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81119380-ffffffff811193a3: swiotlb_set_max_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_set_max_segment(unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811247e1)
Location: kernel/dma/swiotlb.c:146
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81123de0-ffffffff81123e03: swiotlb_set_max_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_set_max_segment(unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81130763)
Location: kernel/dma/swiotlb.c:146
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff8112fd70-ffffffff8112fd93: swiotlb_set_max_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_set_max_segment(unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8113f573)
Location: kernel/dma/swiotlb.c:147
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff8113eb60-ffffffff8113eb83: swiotlb_set_max_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_set_max_segment(unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81be36a4)
Location: kernel/dma/swiotlb.c:147
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff8113a1d0-ffffffff8113a1f3: swiotlb_set_max_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_set_max_segment(unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8113b892)
Location: kernel/dma/swiotlb.c:101
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init_early
```
**Symbols:**

```
ffffffff8113b720-ffffffff8113b743: swiotlb_set_max_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_set_max_segment(unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8115e965)
Location: kernel/dma/swiotlb.c:108
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init_early
```
**Symbols:**

```
ffffffff8115e860-ffffffff8115e883: swiotlb_set_max_segment (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_set_max_segment(unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffff8000101966b0)
Location: kernel/dma/swiotlb.c:146
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffff800010196538-ffff800010196578: swiotlb_set_max_segment (STB_GLOBAL)
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
void swiotlb_set_max_segment(unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (c0000000001f6938)
Location: kernel/dma/swiotlb.c:146
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
```
**Symbols:**

```
c0000000001f6770-c0000000001f67a0: swiotlb_set_max_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_set_max_segment(unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffe000128034)
Location: kernel/dma/swiotlb.c:146
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
```
**Symbols:**

```
ffffffe000127ee0-ffffffe000127f1a: swiotlb_set_max_segment (STB_GLOBAL)
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
void swiotlb_set_max_segment(unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81128f13)
Location: kernel/dma/swiotlb.c:146
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81128520-ffffffff81128543: swiotlb_set_max_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_set_max_segment(unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8111b7a3)
Location: kernel/dma/swiotlb.c:146
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
```
**Symbols:**

```
ffffffff8111adb0-ffffffff8111add3: swiotlb_set_max_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_set_max_segment(unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81126c33)
Location: kernel/dma/swiotlb.c:146
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81126240-ffffffff81126263: swiotlb_set_max_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_set_max_segment(unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81133283)
Location: kernel/dma/swiotlb.c:146
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_tbl
  - kernel/dma/swiotlb.c:swiotlb_init_with_tbl
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81132880-ffffffff811328a3: swiotlb_set_max_segment (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
