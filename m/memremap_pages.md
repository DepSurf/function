# Function: <code>memremap_pages</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *memremap_pages(struct dev_pagemap *pgmap, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812d4650)
Location: mm/memremap.c:157
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff812d4650-ffffffff812d4bbc: memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *memremap_pages(struct dev_pagemap *pgmap, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8130a100)
Location: mm/memremap.c:183
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff8130a100-ffffffff8130a706: memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *memremap_pages(struct dev_pagemap *pgmap, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff81316510)
Location: mm/memremap.c:314
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff81316510-ffffffff813167f9: memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *memremap_pages(struct dev_pagemap *pgmap, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8131c760)
Location: mm/memremap.c:320
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff8131c760-ffffffff8131ca49: memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *memremap_pages(struct dev_pagemap *pgmap, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memremap.c (0)
Location: mm/memremap.c:317
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff81cc3706-ffffffff81cc371a: memremap_pages.cold (STB_LOCAL)
ffffffff81369aa0-ffffffff81369d95: memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *memremap_pages(struct dev_pagemap *pgmap, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memremap.c (0)
Location: mm/memremap.c:286
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff81e75e11-ffffffff81e75e25: memremap_pages.cold (STB_LOCAL)
ffffffff813e7860-ffffffff813e7a97: memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *memremap_pages(struct dev_pagemap *pgmap, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memremap.c (0)
Location: mm/memremap.c:291
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff82068663-ffffffff82068677: memremap_pages.cold (STB_LOCAL)
ffffffff8146f4f0-ffffffff8146f788: memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *memremap_pages(struct dev_pagemap *pgmap, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memremap.c (0)
Location: mm/memremap.c:291
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff820e7f38-ffffffff820e7f4c: memremap_pages.cold (STB_LOCAL)
ffffffff814a3ce0-ffffffff814a3f70: memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *memremap_pages(struct dev_pagemap *pgmap, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memremap.c (0)
Location: mm/memremap.c:292
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff821c4c77-ffffffff821c4c8b: memremap_pages.cold (STB_LOCAL)
ffffffff814d4b80-ffffffff814d4e1a: memremap_pages (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *memremap_pages(struct dev_pagemap *pgmap, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (c00000000046de70)
Location: mm/memremap.c:157
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
c00000000046de70-c00000000046e504: memremap_pages (STB_GLOBAL)
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
void *memremap_pages(struct dev_pagemap *pgmap, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812ccc30)
Location: mm/memremap.c:157
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff812ccc30-ffffffff812cd19c: memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *memremap_pages(struct dev_pagemap *pgmap, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812bdaa0)
Location: mm/memremap.c:157
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff812bdaa0-ffffffff812be00c: memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *memremap_pages(struct dev_pagemap *pgmap, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812caa40)
Location: mm/memremap.c:157
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff812caa40-ffffffff812cafac: memremap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *memremap_pages(struct dev_pagemap *pgmap, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812db760)
Location: mm/memremap.c:157
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff812db760-ffffffff812dbd01: memremap_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
