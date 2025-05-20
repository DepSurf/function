# Function: <code>follow_pmd_mask</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811ef590)
Location: mm/gup.c:211
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *follow_pmd_mask(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, unsigned int flags, unsigned int *page_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812065a0)
Location: mm/gup.c:211
Inline: False
```
**Symbols:**

```
ffffffff812065a0-ffffffff81206bb6: follow_pmd_mask (STB_LOCAL)
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
In mm/gup.c (ffffffff8122752f)
Location: mm/gup.c:211
Inline: True
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
In mm/gup.c (ffffffff8123acd2)
Location: mm/gup.c:209
Inline: True
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
In mm/gup.c (ffffffff8124bea0)
Location: mm/gup.c:323
Inline: True
```
**Symbols:**

```
ffffffff8124bea0-ffffffff8124c5b1: follow_pmd_mask.isra.0 (STB_LOCAL)
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
In mm/gup.c (ffffffff8125a390)
Location: mm/gup.c:318
Inline: True
```
**Symbols:**

```
ffffffff8125a390-ffffffff8125aae5: follow_pmd_mask.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/gup.c (ffffffff81288870)
Location: mm/gup.c:552
Inline: True
```
**Symbols:**

```
ffffffff81288870-ffffffff81288ec7: follow_pmd_mask.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/gup.c (ffffffff81292550)
Location: mm/gup.c:516
Inline: True
```
**Symbols:**

```
ffffffff81292550-ffffffff81292ba7: follow_pmd_mask.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/gup.c (ffffffff81297ff0)
Location: mm/gup.c:613
Inline: True
```
**Symbols:**

```
ffffffff81297ff0-ffffffff812985eb: follow_pmd_mask.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/gup.c (ffffffff812d8a30)
Location: mm/gup.c:636
Inline: True
```
**Symbols:**

```
ffffffff812d8a30-ffffffff812d9029: follow_pmd_mask.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/gup.c (ffffffff81338a40)
Location: mm/gup.c:647
Inline: True
```
**Symbols:**

```
ffffffff81338a40-ffffffff81338fb2: follow_pmd_mask.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/gup.c (ffffffff813b02e0)
Location: mm/gup.c:646
Inline: True
Direct callers:
  - mm/gup.c:follow_p4d_mask
```
**Symbols:**

```
ffffffff813b02e0-ffffffff813b08c5: follow_pmd_mask.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/gup.c (ffffffff813e48b0)
Location: mm/gup.c:691
Inline: True
Direct callers:
  - mm/gup.c:follow_p4d_mask
```
**Symbols:**

```
ffffffff813e48b0-ffffffff813e4cfc: follow_pmd_mask.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/gup.c (ffffffff8140f110)
Location: mm/gup.c:691
Inline: True
```
**Symbols:**

```
ffffffff8140f110-ffffffff8140f544: follow_pmd_mask.isra.0 (STB_LOCAL)
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
struct page *follow_pmd_mask(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, unsigned int flags, struct follow_page_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f1e70)
Location: mm/gup.c:318
Inline: False
Direct callers:
  - mm/gup.c:follow_page_mask
```
**Symbols:**

```
ffff8000102f1e70-ffff8000102f2364: follow_pmd_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (c05147c0)
Location: mm/gup.c:318
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *follow_pmd_mask(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, unsigned int flags, struct follow_page_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b7a10)
Location: mm/gup.c:318
Inline: False
Direct callers:
  - mm/gup.c:follow_page_mask
```
**Symbols:**

```
c0000000003b7a10-c0000000003b86b4: follow_pmd_mask (STB_LOCAL)
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
In mm/gup.c (ffffffe0002049e6)
Location: mm/gup.c:318
Inline: True
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
In mm/gup.c (ffffffff812529e0)
Location: mm/gup.c:318
Inline: True
```
**Symbols:**

```
ffffffff812529e0-ffffffff81253135: follow_pmd_mask.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *follow_pmd_mask(struct vm_area_struct *vma, long unsigned int address, pud_t *pudp, unsigned int flags, struct follow_page_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81245790)
Location: mm/gup.c:318
Inline: False
```
**Symbols:**

```
ffffffff81245790-ffffffff81245e5c: follow_pmd_mask (STB_LOCAL)
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
In mm/gup.c (ffffffff81250780)
Location: mm/gup.c:318
Inline: True
```
**Symbols:**

```
ffffffff81250780-ffffffff81250ed5: follow_pmd_mask.isra.0 (STB_LOCAL)
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
In mm/gup.c (ffffffff81260100)
Location: mm/gup.c:318
Inline: True
```
**Symbols:**

```
ffffffff81260100-ffffffff81260856: follow_pmd_mask.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
</ul>
