# Function: <code>vm_fault_to_errno</code>

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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811eec60)
Location: include/linux/mm.h:2352
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff8121a235)
Location: include/linux/mm.h:2352
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81205141)
Location: include/linux/mm.h:2461
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff81235306)
Location: include/linux/mm.h:2461
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81226084)
Location: include/linux/mm.h:2596
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff812582aa)
Location: include/linux/mm.h:2596
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812397f4)
Location: include/linux/mm.h:2641
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff8126c96b)
Location: include/linux/mm.h:2641
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124a890)
Location: include/linux/mm.h:2667
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff81287d60)
Location: include/linux/mm.h:2667
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81258d60)
Location: include/linux/mm.h:2642
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff81297964)
Location: include/linux/mm.h:2642
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81287846)
Location: include/linux/mm.h:2887
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff812cafcd)
Location: include/linux/mm.h:2887
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812916a7)
Location: include/linux/mm.h:2898
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff812d6bea)
Location: include/linux/mm.h:2898
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81296bc4)
Location: include/linux/mm.h:2895
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff812ddde4)
Location: include/linux/mm.h:2895
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d75b3)
Location: include/linux/mm.h:2953
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff81325030)
Location: include/linux/mm.h:2953
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81337255)
Location: include/linux/mm.h:3026
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff81393909)
Location: include/linux/mm.h:3026
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813aec1d)
Location: include/linux/mm.h:3177
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff81411ffb)
Location: include/linux/mm.h:3177
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e2cd6)
Location: include/linux/mm.h:3409
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff8144553b)
Location: include/linux/mm.h:3409
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
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
In mm/gup.c (ffffffff8140d516)
Location: include/linux/mm.h:3615
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f0c14)
Location: include/linux/mm.h:2642
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffff800010335754)
Location: include/linux/mm.h:2642
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
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
In mm/gup.c (c0514078)
Location: include/linux/mm.h:2642
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b5780)
Location: include/linux/mm.h:2642
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (c00000000040f9c0)
Location: include/linux/mm.h:2642
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffe00020433c)
Location: include/linux/mm.h:2642
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffe000231dbe)
Location: include/linux/mm.h:2642
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812513b0)
Location: include/linux/mm.h:2642
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff8128ff44)
Location: include/linux/mm.h:2642
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812442a0)
Location: include/linux/mm.h:2642
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff81281bfa)
Location: include/linux/mm.h:2642
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124f150)
Location: include/linux/mm.h:2642
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff8128dd54)
Location: include/linux/mm.h:2642
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125eac0)
Location: include/linux/mm.h:2642
Inline: True
Inline callers:
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:__get_user_pages
```
```
In mm/hugetlb.c (ffffffff8129db07)
Location: include/linux/mm.h:2642
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
</details>
</li>
</ul>

## Differences
