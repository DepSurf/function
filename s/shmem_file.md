# Function: <code>shmem_file</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8121bd0c)
Location: include/linux/shmem_fs.h:94
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/khugepaged.c (ffffffff8122d4bb)
Location: include/linux/shmem_fs.h:91
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
In mm/khugepaged.c (ffffffff81239c37)
Location: include/linux/shmem_fs.h:101
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/khugepaged.c (ffffffff8125842b)
Location: include/linux/shmem_fs.h:104
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/khugepaged.c (ffffffff8127cd98)
Location: include/linux/shmem_fs.h:104
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memfd.c (ffffffff81293c55)
Location: include/linux/shmem_fs.h:104
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
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
In mm/khugepaged.c (ffffffff812918fd)
Location: include/linux/shmem_fs.h:104
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memfd.c (ffffffff812a8915)
Location: include/linux/shmem_fs.h:104
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
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
In mm/khugepaged.c (ffffffff812ac818)
Location: include/linux/shmem_fs.h:106
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memfd.c (ffffffff812c5075)
Location: include/linux/shmem_fs.h:106
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
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
In mm/khugepaged.c (ffffffff812be24c)
Location: include/linux/shmem_fs.h:107
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812d6a05)
Location: include/linux/shmem_fs.h:107
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
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
In mm/khugepaged.c (ffffffff812f3af9)
Location: include/linux/shmem_fs.h:109
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff8130ba95)
Location: include/linux/shmem_fs.h:109
Inline: True
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
In mm/shmem.c (ffffffff8127cf0c)
Location: include/linux/shmem_fs.h:113
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_mmap
```
```
In mm/huge_memory.c (ffffffff812f5cb1)
Location: include/linux/shmem_fs.h:113
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812ff2a3)
Location: include/linux/shmem_fs.h:113
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff81317b60)
Location: include/linux/shmem_fs.h:113
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
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
In mm/shmem.c (ffffffff812821dd)
Location: include/linux/shmem_fs.h:113
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
```
```
In mm/huge_memory.c (ffffffff812fc119)
Location: include/linux/shmem_fs.h:113
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81305f20)
Location: include/linux/shmem_fs.h:113
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff8131dd50)
Location: include/linux/shmem_fs.h:113
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
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
In mm/shmem.c (ffffffff812bf87d)
Location: include/linux/shmem_fs.h:118
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
```
```
In mm/huge_memory.c (ffffffff81345f71)
Location: include/linux/shmem_fs.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134fd80)
Location: include/linux/shmem_fs.h:118
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff8136b0f0)
Location: include/linux/shmem_fs.h:118
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
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
In mm/khugepaged.c (ffffffff813c7f99)
Location: include/linux/shmem_fs.h:118
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff813e909a)
Location: include/linux/shmem_fs.h:118
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
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
In mm/huge_memory.c (ffffffff8143e197)
Location: include/linux/shmem_fs.h:126
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_vma_check
```
```
In mm/khugepaged.c (ffffffff8144938b)
Location: include/linux/shmem_fs.h:126
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff81471016)
Location: include/linux/shmem_fs.h:126
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
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
In mm/huge_memory.c (ffffffff814739ec)
Location: include/linux/shmem_fs.h:137
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_vma_check
```
```
In mm/khugepaged.c (ffffffff8147f4d1)
Location: include/linux/shmem_fs.h:137
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff814a5ff5)
Location: include/linux/shmem_fs.h:137
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
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
In mm/huge_memory.c (ffffffff814a2ea8)
Location: include/linux/shmem_fs.h:157
Inline: True
Inline callers:
  - mm/huge_memory.c:__thp_vma_allowable_orders
```
```
In mm/khugepaged.c (ffffffff814ad501)
Location: include/linux/shmem_fs.h:157
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff814d6f16)
Location: include/linux/shmem_fs.h:157
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
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
In mm/khugepaged.c (ffff80001035fb70)
Location: include/linux/shmem_fs.h:107
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffff80001037bb70)
Location: include/linux/shmem_fs.h:107
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
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
In mm/memfd.c (c05670f8)
Location: include/linux/shmem_fs.h:107
Inline: True
Inline callers:
  - mm/memfd.c:__se_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
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
In mm/khugepaged.c (c00000000044a86c)
Location: include/linux/shmem_fs.h:107
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (c000000000470c80)
Location: include/linux/shmem_fs.h:107
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
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
In mm/memfd.c (ffffffe00025233c)
Location: include/linux/shmem_fs.h:107
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
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
In mm/khugepaged.c (ffffffff812b682c)
Location: include/linux/shmem_fs.h:107
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812cefe5)
Location: include/linux/shmem_fs.h:107
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
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
In mm/khugepaged.c (ffffffff812a79fc)
Location: include/linux/shmem_fs.h:107
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812bfc75)
Location: include/linux/shmem_fs.h:107
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
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
In mm/khugepaged.c (ffffffff812b463c)
Location: include/linux/shmem_fs.h:107
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812ccdf5)
Location: include/linux/shmem_fs.h:107
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
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
In mm/khugepaged.c (ffffffff812c4f8f)
Location: include/linux/shmem_fs.h:107
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
```
```
In mm/memfd.c (ffffffff812ddb95)
Location: include/linux/shmem_fs.h:107
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
</details>
</li>
</ul>

## Differences
