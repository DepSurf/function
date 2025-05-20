# Function: <code>uffd_disable_huge_pmd_share</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812dc8c3)
Location: include/linux/userfaultfd_k.h:87
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In fs/userfaultfd.c (ffffffff81387344)
Location: include/linux/userfaultfd_k.h:87
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
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
In mm/hugetlb.c (ffffffff81323a8e)
Location: include/linux/userfaultfd_k.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In fs/userfaultfd.c (ffffffff813d45ea)
Location: include/linux/userfaultfd_k.h:92
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
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
In mm/hugetlb.c (ffffffff8139167c)
Location: include/linux/userfaultfd_k.h:97
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In fs/userfaultfd.c (ffffffff8145f0e8)
Location: include/linux/userfaultfd_k.h:97
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
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
In mm/hugetlb.c (ffffffff8140d795)
Location: include/linux/userfaultfd_k.h:97
Inline: True
Inline callers:
  - mm/hugetlb.c:want_pmd_share
```
```
In fs/userfaultfd.c (ffffffff814ef17a)
Location: include/linux/userfaultfd_k.h:97
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
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
In mm/hugetlb.c (ffffffff81440b45)
Location: include/linux/userfaultfd_k.h:110
Inline: True
Inline callers:
  - mm/hugetlb.c:want_pmd_share
```
```
In fs/userfaultfd.c (ffffffff81525e20)
Location: include/linux/userfaultfd_k.h:110
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
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
In mm/hugetlb.c (ffffffff8147ac75)
Location: include/linux/userfaultfd_k.h:125
Inline: True
Inline callers:
  - mm/hugetlb.c:want_pmd_share
```
```
In fs/userfaultfd.c (ffffffff8155a25b)
Location: include/linux/userfaultfd_k.h:125
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_register
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
