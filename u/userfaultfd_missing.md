# Function: <code>userfaultfd_missing</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/linux/userfaultfd_k.h:46
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/userfaultfd_k.h:46
Inline: True
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
In mm/memory.c (0)
Location: include/linux/userfaultfd_k.h:45
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/userfaultfd_k.h:45
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
In mm/memory.c (0)
Location: include/linux/userfaultfd_k.h:45
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/userfaultfd_k.h:45
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
In mm/shmem.c (0)
Location: include/linux/userfaultfd_k.h:45
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/userfaultfd_k.h:45
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/userfaultfd_k.h:45
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/userfaultfd_k.h:45
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/userfaultfd_k.h:45
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
In mm/shmem.c (0)
Location: include/linux/userfaultfd_k.h:46
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/userfaultfd_k.h:46
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/userfaultfd_k.h:46
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/userfaultfd_k.h:46
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/userfaultfd_k.h:46
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/linux/userfaultfd_k.h:46
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
In mm/shmem.c (ffffffff81210c0b)
Location: include/linux/userfaultfd_k.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff8122e580)
Location: include/linux/userfaultfd_k.h:48
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
```
```
In mm/hugetlb.c (ffffffff8125674b)
Location: include/linux/userfaultfd_k.h:48
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/migrate.c (ffffffff8126f14a)
Location: include/linux/userfaultfd_k.h:48
Inline: True
```
```
In mm/huge_memory.c (ffffffff812746b4)
Location: include/linux/userfaultfd_k.h:48
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In fs/userfaultfd.c (ffffffff812f0886)
Location: include/linux/userfaultfd_k.h:48
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
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
In mm/shmem.c (ffffffff81222c41)
Location: include/linux/userfaultfd_k.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff812423de)
Location: include/linux/userfaultfd_k.h:48
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/hugetlb.c (ffffffff8126ac9a)
Location: include/linux/userfaultfd_k.h:48
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/migrate.c (ffffffff812837fa)
Location: include/linux/userfaultfd_k.h:48
Inline: True
```
```
In mm/huge_memory.c (ffffffff812896e8)
Location: include/linux/userfaultfd_k.h:48
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In fs/userfaultfd.c (ffffffff813057ea)
Location: include/linux/userfaultfd_k.h:48
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
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
In mm/shmem.c (ffffffff81233827)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff8124fda6)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/hugetlb.c (ffffffff81285e17)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/huge_memory.c (ffffffff812a4004)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In fs/userfaultfd.c (ffffffff81326047)
Location: include/linux/userfaultfd_k.h:50
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
In mm/shmem.c (ffffffff81241a27)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff8125e349)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/hugetlb.c (ffffffff812959f7)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/migrate.c (ffffffff812af2ad)
Location: include/linux/userfaultfd_k.h:50
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b5755)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In fs/userfaultfd.c (ffffffff81338dc9)
Location: include/linux/userfaultfd_k.h:50
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
In mm/shmem.c (ffffffff8126eb28)
Location: include/linux/userfaultfd_k.h:55
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff8128e4e4)
Location: include/linux/userfaultfd_k.h:55
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/hugetlb.c (ffffffff812c902e)
Location: include/linux/userfaultfd_k.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/migrate.c (ffffffff812e534c)
Location: include/linux/userfaultfd_k.h:55
Inline: True
```
```
In mm/huge_memory.c (ffffffff812eaa16)
Location: include/linux/userfaultfd_k.h:55
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/userfaultfd.c (ffffffff813731de)
Location: include/linux/userfaultfd_k.h:55
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
In mm/shmem.c (ffffffff81279cb3)
Location: include/linux/userfaultfd_k.h:55
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff8129914a)
Location: include/linux/userfaultfd_k.h:55
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/hugetlb.c (ffffffff812d4c5e)
Location: include/linux/userfaultfd_k.h:55
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/migrate.c (ffffffff812f0714)
Location: include/linux/userfaultfd_k.h:55
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f5ea5)
Location: include/linux/userfaultfd_k.h:55
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/userfaultfd.c (ffffffff81381091)
Location: include/linux/userfaultfd_k.h:55
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
In mm/shmem.c (ffffffff8127edea)
Location: include/linux/userfaultfd_k.h:92
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff8129e404)
Location: include/linux/userfaultfd_k.h:92
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/hugetlb.c (ffffffff812dbab1)
Location: include/linux/userfaultfd_k.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/migrate.c (ffffffff812f6add)
Location: include/linux/userfaultfd_k.h:92
Inline: True
```
```
In mm/huge_memory.c (ffffffff812fc288)
Location: include/linux/userfaultfd_k.h:92
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/userfaultfd.c (ffffffff813881ac)
Location: include/linux/userfaultfd_k.h:92
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
In mm/shmem.c (ffffffff812bd24f)
Location: include/linux/userfaultfd_k.h:97
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff812df647)
Location: include/linux/userfaultfd_k.h:97
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/hugetlb.c (ffffffff81322ca4)
Location: include/linux/userfaultfd_k.h:97
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/migrate.c (ffffffff81341139)
Location: include/linux/userfaultfd_k.h:97
Inline: True
```
```
In mm/huge_memory.c (ffffffff813460e7)
Location: include/linux/userfaultfd_k.h:97
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/userfaultfd.c (ffffffff813d54d5)
Location: include/linux/userfaultfd_k.h:97
Inline: True
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
In mm/shmem.c (ffffffff813191ed)
Location: include/linux/userfaultfd_k.h:114
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff8133fbc5)
Location: include/linux/userfaultfd_k.h:114
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/hugetlb.c (ffffffff8139040b)
Location: include/linux/userfaultfd_k.h:114
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/migrate_device.c (ffffffff813b7f4e)
Location: include/linux/userfaultfd_k.h:114
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bc2b5)
Location: include/linux/userfaultfd_k.h:114
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/userfaultfd.c (ffffffff8145eba7)
Location: include/linux/userfaultfd_k.h:114
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
In mm/shmem.c (ffffffff8138d200)
Location: include/linux/userfaultfd_k.h:114
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In mm/memory.c (ffffffff813b7ba7)
Location: include/linux/userfaultfd_k.h:114
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/hugetlb.c (ffffffff81410dc0)
Location: include/linux/userfaultfd_k.h:114
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/migrate_device.c (ffffffff81439c32)
Location: include/linux/userfaultfd_k.h:114
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143e85c)
Location: include/linux/userfaultfd_k.h:114
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/userfaultfd.c (ffffffff814ee758)
Location: include/linux/userfaultfd_k.h:114
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
In mm/shmem.c (ffffffff813bfabd)
Location: include/linux/userfaultfd_k.h:127
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In mm/memory.c (ffffffff813ec846)
Location: include/linux/userfaultfd_k.h:127
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/hugetlb.c (ffffffff814443e6)
Location: include/linux/userfaultfd_k.h:127
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/migrate_device.c (ffffffff8146e8ce)
Location: include/linux/userfaultfd_k.h:127
Inline: True
```
```
In mm/huge_memory.c (ffffffff8147403f)
Location: include/linux/userfaultfd_k.h:127
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81480757)
Location: include/linux/userfaultfd_k.h:127
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/userfaultfd.c (ffffffff815256db)
Location: include/linux/userfaultfd_k.h:127
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
In mm/shmem.c (ffffffff813eab0e)
Location: include/linux/userfaultfd_k.h:142
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
```
```
In mm/memory.c (ffffffff8141fc98)
Location: include/linux/userfaultfd_k.h:142
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/hugetlb.c (ffffffff8147e47d)
Location: include/linux/userfaultfd_k.h:142
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/migrate_device.c (ffffffff8149d337)
Location: include/linux/userfaultfd_k.h:142
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/huge_memory.c (ffffffff814a3535)
Location: include/linux/userfaultfd_k.h:142
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814ae764)
Location: include/linux/userfaultfd_k.h:142
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/userfaultfd.c (ffffffff81559b73)
Location: include/linux/userfaultfd_k.h:142
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unregister
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
In mm/shmem.c (ffff8000102d3ebc)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffff8000102f5d38)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/hugetlb.c (ffff8000103346d0)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/huge_memory.c (ffff800010356a64)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/userfaultfd.c (ffff8000103f8028)
Location: include/linux/userfaultfd_k.h:50
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
In mm/shmem.c (c04fc070)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (c0517dac)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In fs/userfaultfd.c (c05cc0d4)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unregister
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
In mm/shmem.c (c00000000039315c)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (c0000000003bd3c8)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/hugetlb.c (c00000000040d944)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/migrate.c (c000000000432a94)
Location: include/linux/userfaultfd_k.h:50
Inline: True
```
```
In mm/huge_memory.c (c00000000043e0a0)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In fs/userfaultfd.c (c0000000004ff914)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unregister
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
In mm/shmem.c (ffffffe0001efdcc)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffe000207030)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/hugetlb.c (ffffffe00023066e)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In fs/userfaultfd.c (ffffffe0002a758a)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unregister
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
In mm/shmem.c (ffffffff8123a077)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff81256999)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/hugetlb.c (ffffffff8128dfd7)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/migrate.c (ffffffff812a788d)
Location: include/linux/userfaultfd_k.h:50
Inline: True
```
```
In mm/huge_memory.c (ffffffff812add35)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In fs/userfaultfd.c (ffffffff813313a9)
Location: include/linux/userfaultfd_k.h:50
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
In mm/shmem.c (ffffffff8122d087)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff81249349)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/hugetlb.c (ffffffff8127fd58)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/migrate.c (ffffffff81299299)
Location: include/linux/userfaultfd_k.h:50
Inline: True
```
```
In mm/huge_memory.c (ffffffff8129f38c)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In fs/userfaultfd.c (ffffffff81321999)
Location: include/linux/userfaultfd_k.h:50
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
In mm/shmem.c (ffffffff81237e17)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff81254739)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/hugetlb.c (ffffffff8128bde7)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/migrate.c (ffffffff812a569d)
Location: include/linux/userfaultfd_k.h:50
Inline: True
```
```
In mm/huge_memory.c (ffffffff812abb45)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In fs/userfaultfd.c (ffffffff8132ee79)
Location: include/linux/userfaultfd_k.h:50
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
In mm/shmem.c (ffffffff81247457)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff812641cc)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
```
```
In mm/hugetlb.c (ffffffff8129bbd7)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/migrate.c (ffffffff812b4dca)
Location: include/linux/userfaultfd_k.h:50
Inline: True
```
```
In mm/huge_memory.c (ffffffff812bbeb2)
Location: include/linux/userfaultfd_k.h:50
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In fs/userfaultfd.c (ffffffff81341c01)
Location: include/linux/userfaultfd_k.h:50
Inline: True
```
</details>
</li>
</ul>

## Differences
