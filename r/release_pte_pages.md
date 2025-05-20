# Function: <code>release_pte_pages</code>

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
In mm/huge_memory.c (ffffffff811f538a)
Location: mm/huge_memory.c:2188
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
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
In mm/khugepaged.c (ffffffff8121a2f2)
Location: mm/khugepaged.c:488
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In mm/khugepaged.c (ffffffff8122e537)
Location: mm/khugepaged.c:490
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/khugepaged.c (ffffffff81238716)
Location: mm/khugepaged.c:491
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In mm/khugepaged.c (ffffffff81258dce)
Location: mm/khugepaged.c:492
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8127c1c2)
Location: mm/khugepaged.c:492
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81290858)
Location: mm/khugepaged.c:511
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812a9fab)
Location: mm/khugepaged.c:511
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812bb51b)
Location: mm/khugepaged.c:523
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void release_pte_pages(pte_t *pte, pte_t *_pte, struct list_head *compound_pagelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812f0330)
Location: mm/khugepaged.c:553
Inline: False
Direct callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff812f0330-ffffffff812f0473: release_pte_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void release_pte_pages(pte_t *pte, pte_t *_pte, struct list_head *compound_pagelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812fbaf0)
Location: mm/khugepaged.c:568
Inline: False
Direct callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff812fbaf0-ffffffff812fbc33: release_pte_pages (STB_LOCAL)
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
In mm/khugepaged.c (ffffffff8130341f)
Location: mm/khugepaged.c:566
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
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
In mm/khugepaged.c (ffffffff8134d189)
Location: mm/khugepaged.c:570
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813c49e3)
Location: mm/khugepaged.c:561
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
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
In mm/khugepaged.c (ffffffff814482d8)
Location: mm/khugepaged.c:502
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void release_pte_pages(pte_t *pte, pte_t *_pte, struct list_head *compound_pagelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8147cc30)
Location: mm/khugepaged.c:508
Inline: False
Direct callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff8147cc30-ffffffff8147cd78: release_pte_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void release_pte_pages(pte_t *pte, pte_t *_pte, struct list_head *compound_pagelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff814ac2d0)
Location: mm/khugepaged.c:498
Inline: False
Direct callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff814ac2d0-ffffffff814ac40f: release_pte_pages (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffff80001035c8ec)
Location: mm/khugepaged.c:523
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (c000000000446a28)
Location: mm/khugepaged.c:523
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b3afb)
Location: mm/khugepaged.c:523
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812a4b35)
Location: mm/khugepaged.c:523
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b190b)
Location: mm/khugepaged.c:523
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812c1cab)
Location: mm/khugepaged.c:523
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
