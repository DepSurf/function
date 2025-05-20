# Function: <code>vma_init</code>

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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108b613)
Location: include/linux/mm.h:455
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_alloc
```
```
In mm/shmem.c (ffffffff8120d197)
Location: include/linux/mm.h:455
Inline: True
Inline callers:
  - mm/shmem.c:shmem_pseudo_vma_init
```
```
In mm/mempolicy.c (ffffffff8125d202)
Location: include/linux/mm.h:455
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In fs/hugetlbfs/inode.c (ffffffff813a64e8)
Location: include/linux/mm.h:455
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff81093506)
Location: include/linux/mm.h:482
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_alloc
```
```
In mm/shmem.c (ffffffff81220ee5)
Location: include/linux/mm.h:482
Inline: True
Inline callers:
  - mm/shmem.c:shmem_pseudo_vma_init
```
```
In mm/mempolicy.c (ffffffff81271aae)
Location: include/linux/mm.h:482
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In fs/hugetlbfs/inode.c (ffffffff813bf2c3)
Location: include/linux/mm.h:482
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff81097616)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_alloc
```
```
In mm/shmem.c (ffffffff81230685)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - mm/shmem.c:shmem_pseudo_vma_init
```
```
In mm/mempolicy.c (ffffffff8128d0ca)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In fs/hugetlbfs/inode.c (ffffffff813e9b9f)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff8109dcd6)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_alloc
```
```
In mm/shmem.c (ffffffff8123e8a5)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - mm/shmem.c:shmem_pseudo_vma_init
```
```
In mm/mempolicy.c (ffffffff8129ccfa)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In fs/hugetlbfs/inode.c (ffffffff81403c3f)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff810a52e6)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_alloc
```
```
In mm/shmem.c (ffffffff8126c095)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/mempolicy.c (ffffffff812d088a)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In fs/hugetlbfs/inode.c (ffffffff81451aa0)
Location: include/linux/mm.h:602
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff810a0a06)
Location: include/linux/mm.h:635
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_alloc
```
```
In mm/shmem.c (ffffffff81276ae5)
Location: include/linux/mm.h:635
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/mempolicy.c (ffffffff812dc3aa)
Location: include/linux/mm.h:635
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In fs/hugetlbfs/inode.c (ffffffff8146dfc0)
Location: include/linux/mm.h:635
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff810a1796)
Location: include/linux/mm.h:658
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_alloc
```
```
In mm/shmem.c (ffffffff8127bd1b)
Location: include/linux/mm.h:658
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/mempolicy.c (ffffffff812e3c3a)
Location: include/linux/mm.h:658
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In fs/hugetlbfs/inode.c (ffffffff81473409)
Location: include/linux/mm.h:658
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/fork.c (ffffffff810b2bc6)
Location: include/linux/mm.h:659
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_alloc
```
```
In mm/shmem.c (ffffffff812b9e8b)
Location: include/linux/mm.h:659
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
```
```
In mm/mempolicy.c (ffffffff8132af22)
Location: include/linux/mm.h:659
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In fs/hugetlbfs/inode.c (ffffffff814ca003)
Location: include/linux/mm.h:659
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/fork.c (ffffffff810c8dc6)
Location: include/linux/mm.h:611
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_alloc
```
```
In mm/shmem.c (ffffffff81315d95)
Location: include/linux/mm.h:611
Inline: True
Inline callers:
  - mm/shmem.c:shmem_pseudo_vma_init
```
```
In mm/mempolicy.c (ffffffff8139a991)
Location: include/linux/mm.h:611
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In fs/hugetlbfs/inode.c (ffffffff81555cf9)
Location: include/linux/mm.h:611
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/fork.c (ffffffff810e6286)
Location: include/linux/mm.h:621
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_alloc
```
```
In mm/shmem.c (ffffffff8138aa19)
Location: include/linux/mm.h:621
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_folio
```
```
In mm/mempolicy.c (ffffffff8141a9d1)
Location: include/linux/mm.h:621
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In fs/hugetlbfs/inode.c (ffffffff815f73f7)
Location: include/linux/mm.h:621
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/fork.c (ffffffff810f1b0c)
Location: include/linux/mm.h:763
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_alloc
```
```
In mm/shmem.c (ffffffff813bc0a5)
Location: include/linux/mm.h:763
Inline: True
Inline callers:
  - mm/shmem.c:shmem_pseudo_vma_init
```
```
In mm/mempolicy.c (ffffffff8144df42)
Location: include/linux/mm.h:763
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In fs/hugetlbfs/inode.c (ffffffff8162f4c6)
Location: include/linux/mm.h:763
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/fork.c (ffffffff810fae9c)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_alloc
```
```
In fs/hugetlbfs/inode.c (ffffffff816689d6)
Location: include/linux/mm.h:802
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/fork.c (ffff8000100f28d4)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_alloc
```
```
In mm/shmem.c (ffff8000102d0674)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - mm/shmem.c:shmem_pseudo_vma_init
```
```
In mm/mempolicy.c (ffff80001033bd64)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In fs/hugetlbfs/inode.c (ffff8000104e23f8)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In arch/arm/kernel/process.c (c15039e4)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - arch/arm/kernel/process.c:gate_vma_init
```
```
In kernel/fork.c (c03511d0)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_alloc
```
```
In mm/shmem.c (c04fa8e8)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_swapin
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
In kernel/fork.c (c000000000138494)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_alloc
```
```
In mm/shmem.c (c00000000038e118)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - mm/shmem.c:shmem_pseudo_vma_init
```
```
In mm/mempolicy.c (c000000000416c14)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In fs/hugetlbfs/inode.c (c00000000061f478)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffe0000bf52e)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_alloc
```
```
In mm/shmem.c (ffffffe0001ecc28)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin
```
```
In fs/hugetlbfs/inode.c (ffffffe000355f14)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff810975f6)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_alloc
```
```
In mm/shmem.c (ffffffff81236ef5)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - mm/shmem.c:shmem_pseudo_vma_init
```
```
In mm/mempolicy.c (ffffffff812952da)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In fs/hugetlbfs/inode.c (ffffffff813fc21f)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff81086076)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_alloc
```
```
In mm/shmem.c (ffffffff81229f55)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - mm/shmem.c:shmem_pseudo_vma_init
```
```
In mm/mempolicy.c (ffffffff81286eea)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In fs/hugetlbfs/inode.c (ffffffff813ecc9f)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff810975a6)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_alloc
```
```
In mm/shmem.c (ffffffff81234c95)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - mm/shmem.c:shmem_pseudo_vma_init
```
```
In mm/mempolicy.c (ffffffff812930ea)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In fs/hugetlbfs/inode.c (ffffffff813f959f)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
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
In kernel/fork.c (ffffffff8109f1a6)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - kernel/fork.c:vm_area_alloc
```
```
In mm/shmem.c (ffffffff81245095)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - mm/shmem.c:shmem_pseudo_vma_init
```
```
In mm/mempolicy.c (ffffffff812a2f69)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In fs/hugetlbfs/inode.c (ffffffff8140f1ff)
Location: include/linux/mm.h:529
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
```
</details>
</li>
</ul>

## Differences
