# Function: <code>sparse_init_one_section</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81f8c9ee)
Location: mm/sparse.c:232
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_add_one_section
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81899555)
Location: mm/sparse.c:234
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:sparse_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff818cdc0d)
Location: mm/sparse.c:234
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:sparse_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff819050b0)
Location: mm/sparse.c:274
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:sparse_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8198f09d)
Location: mm/sparse.c:280
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:sparse_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sparse_init_one_section(struct mem_section *ms, long unsigned int pnum, struct page *mem_map, long unsigned int *pageblock_bitmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff819eb799)
Location: mm/sparse.c:260
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:sparse_init
```
**Symbols:**

```
ffffffff819eb799-ffffffff819eb7d4: sparse_init_one_section (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/sparse.c (ffffffff81a26a3e)
Location: mm/sparse.c:282
Inline: True
Direct callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81a26a3e-ffffffff81a26a64: sparse_init_one_section.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/sparse.c (ffffffff81a971f3)
Location: mm/sparse.c:331
Inline: True
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81a971f3-ffffffff81a9721b: sparse_init_one_section.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/sparse.c (ffffffff81aceaaa)
Location: mm/sparse.c:333
Inline: True
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81aceaaa-ffffffff81acead2: sparse_init_one_section.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sparse_init_one_section(struct mem_section *ms, long unsigned int pnum, struct page *mem_map, struct mem_section_usage *usage, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81bc7427)
Location: mm/sparse.c:328
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81bc7427-ffffffff81bc7450: sparse_init_one_section (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sparse_init_one_section(struct mem_section *ms, long unsigned int pnum, struct page *mem_map, struct mem_section_usage *usage, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81c40196)
Location: mm/sparse.c:327
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81c40196-ffffffff81c401bf: sparse_init_one_section (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sparse_init_one_section(struct mem_section *ms, long unsigned int pnum, struct page *mem_map, struct mem_section_usage *usage, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81c32258)
Location: mm/sparse.c:327
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81c32258-ffffffff81c32288: sparse_init_one_section (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sparse_init_one_section(struct mem_section *ms, long unsigned int pnum, struct page *mem_map, struct mem_section_usage *usage, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81d50c58)
Location: mm/sparse.c:301
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81d50c58-ffffffff81d50c88: sparse_init_one_section (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sparse_init_one_section(struct mem_section *ms, long unsigned int pnum, struct page *mem_map, struct mem_section_usage *usage, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81f20e74)
Location: mm/sparse.c:301
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81f20e74-ffffffff81f20eb8: sparse_init_one_section (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff820cad1f)
Location: mm/sparse.c:301
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8214efaf)
Location: mm/sparse.c:301
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff82231e32)
Location: mm/sparse.c:300
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/sparse.c (ffff800010da05fc)
Location: mm/sparse.c:333
Inline: True
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffff800010da05fc-ffff800010da0630: sparse_init_one_section.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/sparse.c (c000000000eed2dc)
Location: mm/sparse.c:333
Inline: True
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
c000000000eed2dc-c000000000eed30c: sparse_init_one_section.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffe0000183a4)
Location: mm/sparse.c:333
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init_nid
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/sparse.c (ffffffff81a6d91a)
Location: mm/sparse.c:333
Inline: True
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81a6d91a-ffffffff81a6d942: sparse_init_one_section.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/sparse.c (ffffffff81a29e61)
Location: mm/sparse.c:333
Inline: True
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81a29e61-ffffffff81a29e89: sparse_init_one_section.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/sparse.c (ffffffff81ad9d2a)
Location: mm/sparse.c:333
Inline: True
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81ad9d2a-ffffffff81ad9d52: sparse_init_one_section.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/sparse.c (ffffffff81ae61e0)
Location: mm/sparse.c:333
Inline: True
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81ae61e0-ffffffff81ae6208: sparse_init_one_section.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
