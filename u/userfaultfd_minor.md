# Function: <code>userfaultfd_minor</code>

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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812dbc46)
Location: include/linux/userfaultfd_k.h:102
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
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
In mm/shmem.c (ffffffff812bd13f)
Location: include/linux/userfaultfd_k.h:107
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff812e2d19)
Location: include/linux/userfaultfd_k.h:107
Inline: True
Inline callers:
  - mm/memory.c:do_read_fault
```
```
In mm/hugetlb.c (ffffffff81322e4e)
Location: include/linux/userfaultfd_k.h:107
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
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
In mm/shmem.c (ffffffff81318de0)
Location: include/linux/userfaultfd_k.h:124
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/hugetlb.c (ffffffff813905eb)
Location: include/linux/userfaultfd_k.h:124
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
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
In mm/shmem.c (ffffffff8138ced2)
Location: include/linux/userfaultfd_k.h:124
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In mm/hugetlb.c (ffffffff81410bf5)
Location: include/linux/userfaultfd_k.h:124
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
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
In mm/shmem.c (ffffffff813bf829)
Location: include/linux/userfaultfd_k.h:137
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In mm/hugetlb.c (ffffffff8144403e)
Location: include/linux/userfaultfd_k.h:137
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
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
In mm/shmem.c (ffffffff813ea842)
Location: include/linux/userfaultfd_k.h:152
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In mm/hugetlb.c (ffffffff8147e10e)
Location: include/linux/userfaultfd_k.h:152
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
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
