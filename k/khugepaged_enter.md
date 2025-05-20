# Function: <code>khugepaged_enter</code>

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
In mm/huge_memory.c (ffffffff811f79fd)
Location: include/linux/khugepaged.h:39
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811c45f8)
Location: include/linux/khugepaged.h:44
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
```
```
In mm/huge_memory.c (ffffffff812142ba)
Location: include/linux/khugepaged.h:44
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8121cac9)
Location: include/linux/khugepaged.h:44
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d46e8)
Location: include/linux/khugepaged.h:44
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
```
```
In mm/huge_memory.c (ffffffff81226805)
Location: include/linux/khugepaged.h:44
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8122f0c9)
Location: include/linux/khugepaged.h:44
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
In mm/shmem.c (ffffffff811dd3d2)
Location: include/linux/khugepaged.h:45
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
```
```
In mm/huge_memory.c (ffffffff81232688)
Location: include/linux/khugepaged.h:45
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8123a909)
Location: include/linux/khugepaged.h:45
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
In mm/shmem.c (ffffffff811f2e58)
Location: include/linux/khugepaged.h:46
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
```
```
In mm/huge_memory.c (ffffffff8124fd4c)
Location: include/linux/khugepaged.h:46
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8125a199)
Location: include/linux/khugepaged.h:46
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
In mm/shmem.c (ffffffff81214063)
Location: include/linux/khugepaged.h:46
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
```
```
In mm/huge_memory.c (ffffffff812742bc)
Location: include/linux/khugepaged.h:46
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8127def7)
Location: include/linux/khugepaged.h:46
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
In mm/shmem.c (ffffffff812211c1)
Location: include/linux/khugepaged.h:46
Inline: True
```
```
In mm/huge_memory.c (ffffffff812892e9)
Location: include/linux/khugepaged.h:46
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812925d5)
Location: include/linux/khugepaged.h:46
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
In mm/shmem.c (ffffffff812309b8)
Location: include/linux/khugepaged.h:46
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a3e95)
Location: include/linux/khugepaged.h:46
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812acfb5)
Location: include/linux/khugepaged.h:46
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
In mm/shmem.c (ffffffff8123ebec)
Location: include/linux/khugepaged.h:54
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b5395)
Location: include/linux/khugepaged.h:54
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812bdbb5)
Location: include/linux/khugepaged.h:54
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
In mm/shmem.c (ffffffff81271e9f)
Location: include/linux/khugepaged.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_mmap
```
```
In mm/huge_memory.c (ffffffff812ea82b)
Location: include/linux/khugepaged.h:54
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812f33b5)
Location: include/linux/khugepaged.h:54
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
In mm/shmem.c (ffffffff8127ceeb)
Location: include/linux/khugepaged.h:56
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_mmap
  - mm/shmem.c:shmem_mmap
```
```
In mm/huge_memory.c (ffffffff812f5c86)
Location: include/linux/khugepaged.h:56
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812feb11)
Location: include/linux/khugepaged.h:56
Inline: True
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
In mm/shmem.c (ffffffff812821c2)
Location: include/linux/khugepaged.h:56
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
```
```
In mm/huge_memory.c (ffffffff812fc0f9)
Location: include/linux/khugepaged.h:56
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81305781)
Location: include/linux/khugepaged.h:56
Inline: True
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
In mm/shmem.c (ffffffff812bf862)
Location: include/linux/khugepaged.h:56
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
```
```
In mm/huge_memory.c (ffffffff81345f50)
Location: include/linux/khugepaged.h:56
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134f5f1)
Location: include/linux/khugepaged.h:56
Inline: True
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
In mm/huge_memory.c (ffffffff813bc17d)
Location: include/linux/khugepaged.h:55
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d0544)
Location: include/linux/khugepaged.h:54
Inline: True
```
```
In mm/huge_memory.c (ffff8000103568b8)
Location: include/linux/khugepaged.h:54
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035f130)
Location: include/linux/khugepaged.h:54
Inline: True
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
In mm/shmem.c (c000000000390494)
Location: include/linux/khugepaged.h:54
Inline: True
Inline callers:
  - mm/shmem.c:shmem_zero_setup
```
```
In mm/huge_memory.c (c00000000043dc44)
Location: include/linux/khugepaged.h:54
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (c000000000449ca4)
Location: include/linux/khugepaged.h:54
Inline: True
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In mm/shmem.c (ffffffff8123723c)
Location: include/linux/khugepaged.h:54
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ad975)
Location: include/linux/khugepaged.h:54
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b6195)
Location: include/linux/khugepaged.h:54
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
In mm/shmem.c (ffffffff8122a29c)
Location: include/linux/khugepaged.h:54
Inline: True
```
```
In mm/huge_memory.c (ffffffff8129eff5)
Location: include/linux/khugepaged.h:54
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812a7385)
Location: include/linux/khugepaged.h:54
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
In mm/shmem.c (ffffffff81234fdc)
Location: include/linux/khugepaged.h:54
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ab785)
Location: include/linux/khugepaged.h:54
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b3fa5)
Location: include/linux/khugepaged.h:54
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
In mm/shmem.c (ffffffff81245046)
Location: include/linux/khugepaged.h:54
Inline: True
```
```
In mm/huge_memory.c (ffffffff812bbaf5)
Location: include/linux/khugepaged.h:54
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812c4445)
Location: include/linux/khugepaged.h:54
Inline: True
```
</details>
</li>
</ul>

## Differences
