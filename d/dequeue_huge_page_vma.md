# Function: <code>dequeue_huge_page_vma</code>

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
In mm/hugetlb.c (ffffffff811dc986)
Location: mm/hugetlb.c:875
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
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
In mm/hugetlb.c (ffffffff811fabf4)
Location: mm/hugetlb.c:897
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
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
In mm/hugetlb.c (ffffffff8120b6f4)
Location: mm/hugetlb.c:897
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
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
In mm/hugetlb.c (ffffffff81216e0d)
Location: mm/hugetlb.c:935
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
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
In mm/hugetlb.c (ffffffff81231abd)
Location: mm/hugetlb.c:936
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
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
In mm/hugetlb.c (ffffffff81254a28)
Location: mm/hugetlb.c:928
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
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
In mm/hugetlb.c (ffffffff81268e08)
Location: mm/hugetlb.c:928
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
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
In mm/hugetlb.c (ffffffff81283efa)
Location: mm/hugetlb.c:938
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
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
In mm/hugetlb.c (ffffffff81293a9a)
Location: mm/hugetlb.c:939
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *dequeue_huge_page_vma(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, int avoid_reserve, long int chg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c4270)
Location: mm/hugetlb.c:1104
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff812c4270-ffffffff812c4448: dequeue_huge_page_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *dequeue_huge_page_vma(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, int avoid_reserve, long int chg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812cff80)
Location: mm/hugetlb.c:1129
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff812cff80-ffffffff812d0158: dequeue_huge_page_vma (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff812d9609)
Location: mm/hugetlb.c:1139
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
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
In mm/hugetlb.c (ffffffff813200b7)
Location: mm/hugetlb.c:1143
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *dequeue_huge_page_vma(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, int avoid_reserve, long int chg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81388c30)
Location: mm/hugetlb.c:1191
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff81388c30-ffffffff81388db9: dequeue_huge_page_vma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *dequeue_huge_page_vma(struct hstate *h, struct vm_area_struct *vma, long unsigned int address, int avoid_reserve, long int chg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81406d20)
Location: mm/hugetlb.c:1356
Inline: False
Direct callers:
  - mm/hugetlb.c:alloc_huge_page
```
**Symbols:**

```
ffffffff81406d20-ffffffff81406ea9: dequeue_huge_page_vma (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010331d60)
Location: mm/hugetlb.c:939
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
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
In mm/hugetlb.c (c00000000040ae34)
Location: mm/hugetlb.c:939
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
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
In mm/hugetlb.c (ffffffe00022eb68)
Location: mm/hugetlb.c:939
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
```
</details>
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
In mm/hugetlb.c (ffffffff8128c07a)
Location: mm/hugetlb.c:939
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
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
In mm/hugetlb.c (ffffffff8127deaa)
Location: mm/hugetlb.c:939
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
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
In mm/hugetlb.c (ffffffff81289e8a)
Location: mm/hugetlb.c:939
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
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
In mm/hugetlb.c (ffffffff81299c9a)
Location: mm/hugetlb.c:939
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
