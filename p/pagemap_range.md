# Function: <code>pagemap_range</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pagemap_range(struct dev_pagemap *pgmap, struct mhp_params *params, int range_id, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff81315dd0)
Location: mm/memremap.c:200
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff81315dd0-ffffffff813161c8: pagemap_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pagemap_range(struct dev_pagemap *pgmap, struct mhp_params *params, int range_id, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8131bfd0)
Location: mm/memremap.c:200
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff8131bfd0-ffffffff8131c3fb: pagemap_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pagemap_range(struct dev_pagemap *pgmap, struct mhp_params *params, int range_id, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memremap.c (0)
Location: mm/memremap.c:197
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff813692b0-ffffffff813696f8: pagemap_range (STB_LOCAL)
ffffffff81cc36c3-ffffffff81cc36f1: pagemap_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pagemap_range(struct dev_pagemap *pgmap, struct mhp_params *params, int range_id, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memremap.c (0)
Location: mm/memremap.c:166
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff813e7450-ffffffff813e785a: pagemap_range (STB_LOCAL)
ffffffff81e75de3-ffffffff81e75e11: pagemap_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pagemap_range(struct dev_pagemap *pgmap, struct mhp_params *params, int range_id, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memremap.c (0)
Location: mm/memremap.c:169
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff8146f0d0-ffffffff8146f4de: pagemap_range (STB_LOCAL)
ffffffff82068635-ffffffff82068663: pagemap_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pagemap_range(struct dev_pagemap *pgmap, struct mhp_params *params, int range_id, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memremap.c (0)
Location: mm/memremap.c:169
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff814a38b0-ffffffff814a3cc1: pagemap_range (STB_LOCAL)
ffffffff820e7f0a-ffffffff820e7f38: pagemap_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pagemap_range(struct dev_pagemap *pgmap, struct mhp_params *params, int range_id, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memremap.c (0)
Location: mm/memremap.c:170
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
```
**Symbols:**

```
ffffffff814d4750-ffffffff814d4b61: pagemap_range (STB_LOCAL)
ffffffff821c4c49-ffffffff821c4c77: pagemap_range.cold (STB_LOCAL)
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
