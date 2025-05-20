# Function: <code>swiotlb_late_init_with_tbl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int swiotlb_late_init_with_tbl(char *tlb, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81412de0)
Location: lib/swiotlb.c:286
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81412de0-ffffffff81412fc2: swiotlb_late_init_with_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int swiotlb_late_init_with_tbl(char *tlb, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff8145aaf0)
Location: lib/swiotlb.c:286
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff8145aaf0-ffffffff8145acd8: swiotlb_late_init_with_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int swiotlb_late_init_with_tbl(char *tlb, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814795a0)
Location: lib/swiotlb.c:312
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff814795a0-ffffffff814797c4: swiotlb_late_init_with_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int swiotlb_late_init_with_tbl(char *tlb, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81482910)
Location: lib/swiotlb.c:312
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81482910-ffffffff81482b38: swiotlb_late_init_with_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int swiotlb_late_init_with_tbl(char *tlb, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814be920)
Location: lib/swiotlb.c:347
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff814be920-ffffffff814beb78: swiotlb_late_init_with_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int swiotlb_late_init_with_tbl(char *tlb, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:332
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff8110e83c-ffffffff8110e88a: swiotlb_late_init_with_tbl.cold.18 (STB_LOCAL)
ffffffff8110d7d0-ffffffff8110d9ed: swiotlb_late_init_with_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int swiotlb_late_init_with_tbl(char *tlb, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:305
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81119dc1-ffffffff81119e0f: swiotlb_late_init_with_tbl.cold.10 (STB_LOCAL)
ffffffff811193d0-ffffffff81119567: swiotlb_late_init_with_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int swiotlb_late_init_with_tbl(char *tlb, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:329
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff811247c1-ffffffff8112480f: swiotlb_late_init_with_tbl.cold (STB_LOCAL)
ffffffff81123e30-ffffffff81123fca: swiotlb_late_init_with_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int swiotlb_late_init_with_tbl(char *tlb, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:329
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81130741-ffffffff8113078f: swiotlb_late_init_with_tbl.cold (STB_LOCAL)
ffffffff8112fdc0-ffffffff8112ff5a: swiotlb_late_init_with_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int swiotlb_late_init_with_tbl(char *tlb, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:330
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff8113f551-ffffffff8113f59f: swiotlb_late_init_with_tbl.cold (STB_LOCAL)
ffffffff8113ebb0-ffffffff8113ed34: swiotlb_late_init_with_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int swiotlb_late_init_with_tbl(char *tlb, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:347
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81be367b-ffffffff81be36d0: swiotlb_late_init_with_tbl.cold (STB_LOCAL)
ffffffff8113a220-ffffffff8113a3bb: swiotlb_late_init_with_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int swiotlb_late_init_with_tbl(char *tlb, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:283
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81bd552c-ffffffff81bd554f: swiotlb_late_init_with_tbl.cold (STB_LOCAL)
ffffffff8113b770-ffffffff8113b8d6: swiotlb_late_init_with_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int swiotlb_late_init_with_tbl(char *tlb, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8115e8b0)
Location: kernel/dma/swiotlb.c:304
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff8115e8b0-ffffffff8115e9b5: swiotlb_late_init_with_tbl (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int swiotlb_late_init_with_tbl(char *tlb, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffff8000101965a8)
Location: kernel/dma/swiotlb.c:329
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffff8000101965a8-ffff800010196724: swiotlb_late_init_with_tbl (STB_GLOBAL)
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
int swiotlb_late_init_with_tbl(char *tlb, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (c0000000001f67d0)
Location: kernel/dma/swiotlb.c:329
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
```
**Symbols:**

```
c0000000001f67d0-c0000000001f69d8: swiotlb_late_init_with_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int swiotlb_late_init_with_tbl(char *tlb, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffe000127f44)
Location: kernel/dma/swiotlb.c:329
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
```
**Symbols:**

```
ffffffe000127f44-ffffffe0001280b6: swiotlb_late_init_with_tbl (STB_GLOBAL)
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
int swiotlb_late_init_with_tbl(char *tlb, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:329
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81128ef1-ffffffff81128f3f: swiotlb_late_init_with_tbl.cold (STB_LOCAL)
ffffffff81128570-ffffffff8112870a: swiotlb_late_init_with_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int swiotlb_late_init_with_tbl(char *tlb, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:329
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
```
**Symbols:**

```
ffffffff8111b781-ffffffff8111b7cf: swiotlb_late_init_with_tbl.cold (STB_LOCAL)
ffffffff8111ae00-ffffffff8111af9a: swiotlb_late_init_with_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int swiotlb_late_init_with_tbl(char *tlb, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:329
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81126c11-ffffffff81126c5f: swiotlb_late_init_with_tbl.cold (STB_LOCAL)
ffffffff81126290-ffffffff8112642a: swiotlb_late_init_with_tbl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int swiotlb_late_init_with_tbl(char *tlb, long unsigned int nslabs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:329
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_late_init_with_default_size
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81133261-ffffffff811332af: swiotlb_late_init_with_tbl.cold (STB_LOCAL)
ffffffff811328d0-ffffffff81132a6a: swiotlb_late_init_with_tbl (STB_GLOBAL)
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
