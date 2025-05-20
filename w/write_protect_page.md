# Function: <code>write_protect_page</code>

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
In mm/ksm.c (ffffffff811e53e9)
Location: mm/ksm.c:856
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
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
In mm/ksm.c (ffffffff81203f45)
Location: mm/ksm.c:844
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
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
In mm/ksm.c (ffffffff81215f2b)
Location: mm/ksm.c:855
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
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
In mm/ksm.c (ffffffff812215fd)
Location: mm/ksm.c:1012
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
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
In mm/ksm.c (ffffffff8123c90d)
Location: mm/ksm.c:1012
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
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
In mm/ksm.c (ffffffff81260212)
Location: mm/ksm.c:1035
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
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
In mm/ksm.c (ffffffff8127494a)
Location: mm/ksm.c:1036
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
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
In mm/ksm.c (ffffffff8128edd0)
Location: mm/ksm.c:1050
Inline: True
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8128edd0-ffffffff8128f0d3: write_protect_page.isra.0 (STB_LOCAL)
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
In mm/ksm.c (ffffffff8129eb40)
Location: mm/ksm.c:1032
Inline: True
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8129eb40-ffffffff8129ee59: write_protect_page.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int write_protect_page(struct vm_area_struct *vma, struct page *page, pte_t *orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812d36a0)
Location: mm/ksm.c:1032
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff812d36a0-ffffffff812d39de: write_protect_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int write_protect_page(struct vm_area_struct *vma, struct page *page, pte_t *orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812df0c0)
Location: mm/ksm.c:1033
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff812df0c0-ffffffff812df3de: write_protect_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int write_protect_page(struct vm_area_struct *vma, struct page *page, pte_t *orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e68a0)
Location: mm/ksm.c:1031
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff812e68a0-ffffffff812e6bb2: write_protect_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int write_protect_page(struct vm_area_struct *vma, struct page *page, pte_t *orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/ksm.c (0)
Location: mm/ksm.c:1027
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8132e7c0-ffffffff8132eae7: write_protect_page (STB_LOCAL)
ffffffff81cc08fb-ffffffff81cc0921: write_protect_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int write_protect_page(struct vm_area_struct *vma, struct page *page, pte_t *orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/ksm.c (0)
Location: mm/ksm.c:1040
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff813a0470-ffffffff813a09e9: write_protect_page (STB_LOCAL)
ffffffff81e72d9b-ffffffff81e72daf: write_protect_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int write_protect_page(struct vm_area_struct *vma, struct page *page, pte_t *orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/ksm.c (0)
Location: mm/ksm.c:1044
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8141fc80-ffffffff8142024d: write_protect_page (STB_LOCAL)
ffffffff820672f5-ffffffff82067309: write_protect_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int write_protect_page(struct vm_area_struct *vma, struct page *page, pte_t *orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/ksm.c (0)
Location: mm/ksm.c:1088
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff814548a0-ffffffff81454e5d: write_protect_page (STB_LOCAL)
ffffffff820e6bb7-ffffffff820e6bcb: write_protect_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int write_protect_page(struct vm_area_struct *vma, struct page *page, pte_t *orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/ksm.c (0)
Location: mm/ksm.c:1278
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8148fae0-ffffffff8149011a: write_protect_page (STB_LOCAL)
ffffffff821c3cea-ffffffff821c3d0a: write_protect_page.cold (STB_LOCAL)
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
In mm/ksm.c (ffff80001033e300)
Location: mm/ksm.c:1032
Inline: True
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffff80001033e300-ffff80001033e65c: write_protect_page.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int write_protect_page(struct vm_area_struct *vma, struct page *page, pte_t *orig_pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c05448ac)
Location: mm/ksm.c:1032
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
c05448ac-c0544c38: write_protect_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/ksm.c (c000000000419d90)
Location: mm/ksm.c:1032
Inline: True
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
c000000000419d90-c00000000041a1e0: write_protect_page.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/ksm.c (ffffffe00023456e)
Location: mm/ksm.c:1032
Inline: True
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffe00023456e-ffffffe00023480a: write_protect_page.isra.0 (STB_LOCAL)
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
In mm/ksm.c (ffffffff81297120)
Location: mm/ksm.c:1032
Inline: True
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81297120-ffffffff81297439: write_protect_page.isra.0 (STB_LOCAL)
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
In mm/ksm.c (ffffffff81288d30)
Location: mm/ksm.c:1032
Inline: True
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81288d30-ffffffff81289023: write_protect_page.isra.0 (STB_LOCAL)
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
In mm/ksm.c (ffffffff81294f30)
Location: mm/ksm.c:1032
Inline: True
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81294f30-ffffffff81295249: write_protect_page.isra.0 (STB_LOCAL)
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
In mm/ksm.c (ffffffff812a4da0)
Location: mm/ksm.c:1032
Inline: True
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff812a4da0-ffffffff812a50a1: write_protect_page.isra.0 (STB_LOCAL)
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
</ul>
