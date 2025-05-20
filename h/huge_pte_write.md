# Function: <code>huge_pte_write</code>

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
In mm/hugetlb.c (0)
Location: include/asm-generic/hugetlb.h:9
Inline: True
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
In mm/hugetlb.c (0)
Location: include/asm-generic/hugetlb.h:9
Inline: True
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
In mm/hugetlb.c (0)
Location: include/asm-generic/hugetlb.h:9
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (0)
Location: include/asm-generic/hugetlb.h:9
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:9
Inline: True
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
In mm/hugetlb.c (ffffffff81234b9d)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:10
Inline: True
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
In mm/hugetlb.c (ffffffff812580a8)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:10
Inline: True
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
In mm/hugetlb.c (ffffffff8126c787)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:10
Inline: True
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
In mm/hugetlb.c (ffffffff81287b11)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:10
Inline: True
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
In mm/hugetlb.c (ffffffff81297720)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:10
Inline: True
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
In mm/hugetlb.c (ffffffff812cac8f)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/userfaultfd.c (ffffffff813745a7)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In mm/hugetlb.c (ffffffff812d68af)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/userfaultfd.c (ffffffff813824f7)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In mm/hugetlb.c (ffffffff812dda62)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/userfaultfd.c (ffffffff8138957d)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In mm/hugetlb.c (ffffffff81324c36)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/userfaultfd.c (ffffffff813d6877)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In mm/hugetlb.c (ffffffff813934f2)
Location: include/asm-generic/hugetlb.h:13
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/userfaultfd.c (ffffffff8145da12)
Location: include/asm-generic/hugetlb.h:13
Inline: True
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
In mm/hugetlb.c (ffffffff81411c77)
Location: include/asm-generic/hugetlb.h:13
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/userfaultfd.c (ffffffff814ed443)
Location: include/asm-generic/hugetlb.h:13
Inline: True
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
In mm/hugetlb.c (ffffffff8144519c)
Location: include/asm-generic/hugetlb.h:13
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/userfaultfd.c (ffffffff815241d3)
Location: include/asm-generic/hugetlb.h:13
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8147b5e7)
Location: include/asm-generic/hugetlb.h:13
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/userfaultfd.c (ffffffff81558824)
Location: include/asm-generic/hugetlb.h:13
Inline: True
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
In mm/hugetlb.c (ffff800010335514)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/userfaultfd.c (ffff8000103f9600)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c00000000040f588)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/userfaultfd.c (c00000000050167c)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In mm/hugetlb.c (ffffffe000231d2a)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/userfaultfd.c (ffffffe0002a8808)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In mm/hugetlb.c (ffffffff8128fd00)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:10
Inline: True
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
In mm/hugetlb.c (ffffffff812819c5)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:10
Inline: True
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
In mm/hugetlb.c (ffffffff8128db10)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:10
Inline: True
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
In mm/hugetlb.c (ffffffff8129d8c7)
Location: include/asm-generic/hugetlb.h:10
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/hugetlb.h:10
Inline: True
```
</details>
</li>
</ul>

## Differences
