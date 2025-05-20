# Function: <code>mpol_shared_policy_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e2bd0)
Location: mm/mempolicy.c:2207
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_swapin
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff811e2bd0-ffffffff811e2c36: mpol_shared_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812015b0)
Location: mm/mempolicy.c:2228
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff812015b0-ffffffff81201612: mpol_shared_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812130a0)
Location: mm/mempolicy.c:2222
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff812130a0-ffffffff81213102: mpol_shared_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121e3d0)
Location: mm/mempolicy.c:2124
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8121e3d0-ffffffff8121e430: mpol_shared_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81239620)
Location: mm/mempolicy.c:2186
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff81239620-ffffffff81239680: mpol_shared_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8125cbc0)
Location: mm/mempolicy.c:2246
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_pseudo_vma_init
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8125cbc0-ffffffff8125cc20: mpol_shared_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812714a0)
Location: mm/mempolicy.c:2285
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_pseudo_vma_init
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff812714a0-ffffffff812714fc: mpol_shared_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128cab0)
Location: mm/mempolicy.c:2306
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_pseudo_vma_init
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8128cab0-ffffffff8128cb0c: mpol_shared_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129c6e0)
Location: mm/mempolicy.c:2345
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_pseudo_vma_init
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8129c6e0-ffffffff8129c73c: mpol_shared_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d0330)
Location: mm/mempolicy.c:2444
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff812d0330-ffffffff812d038c: mpol_shared_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812dbe50)
Location: mm/mempolicy.c:2419
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff812dbe50-ffffffff812dbeac: mpol_shared_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e36c0)
Location: mm/mempolicy.c:2424
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff812e36c0-ffffffff812e371c: mpol_shared_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8132a8e0)
Location: mm/mempolicy.c:2341
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_swapin
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8132a8e0-ffffffff8132a93c: mpol_shared_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8139a270)
Location: mm/mempolicy.c:2517
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_pseudo_vma_init
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8139a270-ffffffff8139a2e4: mpol_shared_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8141a280)
Location: mm/mempolicy.c:2532
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_alloc_folio
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8141a280-ffffffff8141a2f4: mpol_shared_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8144d820)
Location: mm/mempolicy.c:2543
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_pseudo_vma_init
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff8144d820-ffffffff8144d894: mpol_shared_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81487450)
Location: mm/mempolicy.c:2442
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_alloc_and_add_folio
  - mm/shmem.c:shmem_alloc_folio
```
**Symbols:**

```
ffffffff81487450-ffffffff814874c4: mpol_shared_policy_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff80001033b5d8)
Location: mm/mempolicy.c:2345
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_pseudo_vma_init
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffff80001033b5d8-ffff80001033b6c0: mpol_shared_policy_lookup (STB_GLOBAL)
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
In mm/shmem.c (0)
Location: include/linux/mempolicy.h:241
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000416330)
Location: mm/mempolicy.c:2345
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_pseudo_vma_init
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
c000000000416330-c00000000041641c: mpol_shared_policy_lookup (STB_GLOBAL)
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
In mm/shmem.c (0)
Location: include/linux/mempolicy.h:241
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81294cc0)
Location: mm/mempolicy.c:2345
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_pseudo_vma_init
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff81294cc0-ffffffff81294d1c: mpol_shared_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812868d0)
Location: mm/mempolicy.c:2345
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_pseudo_vma_init
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff812868d0-ffffffff8128692c: mpol_shared_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81292ad0)
Location: mm/mempolicy.c:2345
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_pseudo_vma_init
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff81292ad0-ffffffff81292b2c: mpol_shared_policy_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mempolicy *mpol_shared_policy_lookup(struct shared_policy *sp, long unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812a28a0)
Location: mm/mempolicy.c:2345
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_policy
  - mm/shmem.c:shmem_pseudo_vma_init
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff812a28a0-ffffffff812a2913: mpol_shared_policy_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
