# Function: <code>memunmap_pages</code>

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
void memunmap_pages(struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812d4450)
Location: mm/memremap.c:103
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff812d4450-ffffffff812d4637: memunmap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memunmap_pages(struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8130a710)
Location: mm/memremap.c:127
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff8130a710-ffffffff8130a971: memunmap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memunmap_pages(struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff81316330)
Location: mm/memremap.c:168
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81316330-ffffffff81316500: memunmap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void memunmap_pages(struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8131c400)
Location: mm/memremap.c:168
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff8131c400-ffffffff8131c74f: memunmap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void memunmap_pages(struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memremap.c (0)
Location: mm/memremap.c:165
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81cc36f1-ffffffff81cc3706: memunmap_pages.cold (STB_LOCAL)
ffffffff81369700-ffffffff81369a8f: memunmap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void memunmap_pages(struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memremap.c (0)
Location: mm/memremap.c:136
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81e75dce-ffffffff81e75de3: memunmap_pages.cold (STB_LOCAL)
ffffffff813e7140-ffffffff813e7421: memunmap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void memunmap_pages(struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memremap.c (0)
Location: mm/memremap.c:136
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff82068620-ffffffff82068635: memunmap_pages.cold (STB_LOCAL)
ffffffff8146eda0-ffffffff8146f08c: memunmap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void memunmap_pages(struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memremap.c (0)
Location: mm/memremap.c:136
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff820e7ef6-ffffffff820e7f0a: memunmap_pages.cold (STB_LOCAL)
ffffffff814a3560-ffffffff814a3863: memunmap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void memunmap_pages(struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memremap.c (0)
Location: mm/memremap.c:137
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff821c4c35-ffffffff821c4c49: memunmap_pages.cold (STB_LOCAL)
ffffffff814d4400-ffffffff814d4703: memunmap_pages (STB_GLOBAL)
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
void memunmap_pages(struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (c00000000046dbb0)
Location: mm/memremap.c:103
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
c00000000046dbb0-c00000000046de44: memunmap_pages (STB_GLOBAL)
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
void memunmap_pages(struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812cca30)
Location: mm/memremap.c:103
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff812cca30-ffffffff812ccc17: memunmap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void memunmap_pages(struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812bd8a0)
Location: mm/memremap.c:103
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff812bd8a0-ffffffff812bda87: memunmap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void memunmap_pages(struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812ca840)
Location: mm/memremap.c:103
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff812ca840-ffffffff812caa27: memunmap_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void memunmap_pages(struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812db570)
Location: mm/memremap.c:103
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
```
**Symbols:**

```
ffffffff812db570-ffffffff812db748: memunmap_pages (STB_GLOBAL)
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
