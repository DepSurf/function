# Function: <code>pte_to_hmm_pfn_flags</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812935fa)
Location: mm/hmm.c:477
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/hmm.c (ffffffff812a7b6e)
Location: mm/hmm.c:495
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/hmm.c (ffffffff812c3cf1)
Location: mm/hmm.c:513
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hmm.c (ffffffff812d5a53)
Location: mm/hmm.c:445
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hmm.c (ffffffff8130b6b0)
Location: mm/hmm.c:213
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hmm.c (ffffffff81317578)
Location: mm/hmm.c:221
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hmm.c (ffffffff8131d278)
Location: mm/hmm.c:221
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hmm.c (ffffffff8136a613)
Location: mm/hmm.c:223
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hmm.c (ffffffff813e81d6)
Location: mm/hmm.c:215
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hmm.c (ffffffff814700e7)
Location: mm/hmm.c:215
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hmm.c (ffffffff814a48bd)
Location: mm/hmm.c:215
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_handle_pte
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
In mm/hmm.c (ffffffff814d58ed)
Location: mm/hmm.c:215
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_handle_pte
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
In mm/hmm.c (ffff80001037b2bc)
Location: mm/hmm.c:445
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/hmm.c (c0566680)
Location: mm/hmm.c:445
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hmm.c (c00000000046fb28)
Location: mm/hmm.c:445
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hmm.c (ffffffe0002521f2)
Location: mm/hmm.c:445
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
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
In mm/hmm.c (ffffffff812ce033)
Location: mm/hmm.c:445
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hmm.c (ffffffff812bee99)
Location: mm/hmm.c:445
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hmm.c (ffffffff812cbe43)
Location: mm/hmm.c:445
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
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
In mm/hmm.c (ffffffff812dcba1)
Location: mm/hmm.c:445
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
</details>
</li>
</ul>

## Differences
