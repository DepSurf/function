# Function: <code>vmf_error</code>

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
In mm/shmem.c (ffffffff8121190b)
Location: include/linux/mm.h:2560
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
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
In mm/filemap.c (ffffffff81201f9d)
Location: include/linux/mm.h:2613
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff81225eb8)
Location: include/linux/mm.h:2613
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/hugetlb.c (ffffffff8126af80)
Location: include/linux/mm.h:2613
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
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
In mm/filemap.c (0)
Location: include/linux/mm.h:2611
Inline: True
```
```
In mm/shmem.c (ffffffff81234123)
Location: include/linux/mm.h:2611
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/hugetlb.c (ffffffff81285f85)
Location: include/linux/mm.h:2611
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In fs/dax.c (ffffffff81335740)
Location: include/linux/mm.h:2611
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
In mm/filemap.c (0)
Location: include/linux/mm.h:2585
Inline: True
```
```
In mm/shmem.c (ffffffff81242323)
Location: include/linux/mm.h:2585
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/hugetlb.c (ffffffff81295b65)
Location: include/linux/mm.h:2585
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In fs/dax.c (ffffffff81349340)
Location: include/linux/mm.h:2585
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
In mm/shmem.c (ffffffff81271053)
Location: include/linux/mm.h:2799
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/hugetlb.c (ffffffff812c919b)
Location: include/linux/mm.h:2799
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In fs/dax.c (ffffffff8138e6d4)
Location: include/linux/mm.h:2799
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
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
In mm/shmem.c (ffffffff8127a535)
Location: include/linux/mm.h:2810
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/hugetlb.c (ffffffff812d4dc8)
Location: include/linux/mm.h:2810
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In fs/dax.c (ffffffff8139fe2d)
Location: include/linux/mm.h:2810
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
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
In mm/shmem.c (ffffffff8127f675)
Location: include/linux/mm.h:2808
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/hugetlb.c (ffffffff812dbbde)
Location: include/linux/mm.h:2808
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In fs/dax.c (ffffffff813a73f0)
Location: include/linux/mm.h:2808
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
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
In mm/shmem.c (ffffffff812bd954)
Location: include/linux/mm.h:2866
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/hugetlb.c (ffffffff81322de6)
Location: include/linux/mm.h:2866
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/secretmem.c (ffffffff813667c4)
Location: include/linux/mm.h:2866
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In fs/dax.c (ffffffff813f72b4)
Location: include/linux/mm.h:2866
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_cow_page
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
In mm/shmem.c (ffffffff813196b3)
Location: include/linux/mm.h:2941
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/hugetlb.c (ffffffff8139057c)
Location: include/linux/mm.h:2941
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
```
```
In mm/secretmem.c (ffffffff813e3b03)
Location: include/linux/mm.h:2941
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In fs/dax.c (ffffffff8146a008)
Location: include/linux/mm.h:2941
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_cow_page
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
In mm/shmem.c (ffffffff8138d699)
Location: include/linux/mm.h:3092
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/hugetlb.c (ffffffff814111db)
Location: include/linux/mm.h:3092
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
```
```
In mm/secretmem.c (ffffffff8146b4e0)
Location: include/linux/mm.h:3092
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In fs/dax.c (ffffffff814faaa5)
Location: include/linux/mm.h:3092
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_cow_page
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
In mm/shmem.c (ffffffff813c0041)
Location: include/linux/mm.h:3397
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/hugetlb.c (ffffffff81444638)
Location: include/linux/mm.h:3397
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
```
```
In mm/secretmem.c (ffffffff814a02c3)
Location: include/linux/mm.h:3397
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In fs/dax.c (ffffffff81531ef0)
Location: include/linux/mm.h:3397
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_cow_page
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
In mm/shmem.c (ffffffff813eae01)
Location: include/linux/mm.h:3585
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/hugetlb.c (ffffffff8147e70d)
Location: include/linux/mm.h:3585
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
```
```
In mm/secretmem.c (ffffffff814cf932)
Location: include/linux/mm.h:3585
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
  - mm/secretmem.c:secretmem_fault
```
```
In fs/dax.c (ffffffff81566de0)
Location: include/linux/mm.h:3585
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_cow_page
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
In mm/filemap.c (0)
Location: include/linux/mm.h:2585
Inline: True
```
```
In mm/shmem.c (ffff8000102d66f4)
Location: include/linux/mm.h:2585
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/hugetlb.c (ffff80001033482c)
Location: include/linux/mm.h:2585
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In fs/dax.c (ffff800010409ef8)
Location: include/linux/mm.h:2585
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (0)
Location: include/linux/mm.h:2585
Inline: True
```
```
In mm/shmem.c (c04fc964)
Location: include/linux/mm.h:2585
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
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
In mm/filemap.c (0)
Location: include/linux/mm.h:2585
Inline: True
```
```
In mm/shmem.c (c000000000393e40)
Location: include/linux/mm.h:2585
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/hugetlb.c (c00000000040dba0)
Location: include/linux/mm.h:2585
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In fs/dax.c (c000000000515e70)
Location: include/linux/mm.h:2585
Inline: True
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
In mm/filemap.c (0)
Location: include/linux/mm.h:2585
Inline: True
```
```
In mm/shmem.c (ffffffe0001f051a)
Location: include/linux/mm.h:2585
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/hugetlb.c (ffffffe0002306ee)
Location: include/linux/mm.h:2585
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In fs/dax.c (ffffffe0002b3aca)
Location: include/linux/mm.h:2585
Inline: True
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
In mm/filemap.c (0)
Location: include/linux/mm.h:2585
Inline: True
```
```
In mm/shmem.c (ffffffff8123a973)
Location: include/linux/mm.h:2585
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/hugetlb.c (ffffffff8128e145)
Location: include/linux/mm.h:2585
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In fs/dax.c (ffffffff81341920)
Location: include/linux/mm.h:2585
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
In mm/filemap.c (0)
Location: include/linux/mm.h:2585
Inline: True
```
```
In mm/shmem.c (ffffffff8122d973)
Location: include/linux/mm.h:2585
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/hugetlb.c (ffffffff8127feb5)
Location: include/linux/mm.h:2585
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In fs/dax.c (ffffffff8133229c)
Location: include/linux/mm.h:2585
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
In mm/filemap.c (0)
Location: include/linux/mm.h:2585
Inline: True
```
```
In mm/shmem.c (ffffffff81238713)
Location: include/linux/mm.h:2585
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/hugetlb.c (ffffffff8128bf55)
Location: include/linux/mm.h:2585
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In fs/dax.c (ffffffff8133f3f0)
Location: include/linux/mm.h:2585
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
In mm/filemap.c (0)
Location: include/linux/mm.h:2585
Inline: True
```
```
In mm/shmem.c (ffffffff81247d53)
Location: include/linux/mm.h:2585
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/hugetlb.c (ffffffff8129bd41)
Location: include/linux/mm.h:2585
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In fs/dax.c (ffffffff81352d70)
Location: include/linux/mm.h:2585
Inline: True
```
</details>
</li>
</ul>

## Differences
