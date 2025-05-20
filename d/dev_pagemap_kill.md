# Function: <code>dev_pagemap_kill</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void dev_pagemap_kill(struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812c2390)
Location: mm/memremap.c:78
Inline: True
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages_release
```
**Symbols:**

```
ffffffff812c2390-ffffffff812c23c2: dev_pagemap_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dev_pagemap_kill(struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812d42c0)
Location: mm/memremap.c:79
Inline: True
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812d42c0-ffffffff812d42f2: dev_pagemap_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8130a204)
Location: mm/memremap.c:103
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff81316335)
Location: mm/memremap.c:115
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8131c405)
Location: mm/memremap.c:115
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff81369705)
Location: mm/memremap.c:115
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void dev_pagemap_kill(struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (c00000000046d860)
Location: mm/memremap.c:79
Inline: True
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
c00000000046d860-c00000000046d8e0: dev_pagemap_kill (STB_LOCAL)
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
void dev_pagemap_kill(struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812cc8a0)
Location: mm/memremap.c:79
Inline: True
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812cc8a0-ffffffff812cc8d2: dev_pagemap_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void dev_pagemap_kill(struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812bd710)
Location: mm/memremap.c:79
Inline: True
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812bd710-ffffffff812bd742: dev_pagemap_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void dev_pagemap_kill(struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812ca6b0)
Location: mm/memremap.c:79
Inline: True
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812ca6b0-ffffffff812ca6e2: dev_pagemap_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dev_pagemap_kill(struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff812db3b0)
Location: mm/memremap.c:79
Inline: True
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff812db3b0-ffffffff812db3e2: dev_pagemap_kill (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
