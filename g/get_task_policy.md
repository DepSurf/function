# Function: <code>get_task_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff811e03e0)
Location: mm/mempolicy.c:126
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff811e03e0-ffffffff811e0416: get_task_policy.part.26 (STB_LOCAL)
ffffffff811e0d30-ffffffff811e0d4d: get_task_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff811feb8b)
Location: mm/mempolicy.c:125
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff811fe6c0-ffffffff811fe6f6: get_task_policy.part.31 (STB_LOCAL)
ffffffff811ff700-ffffffff811ff71d: get_task_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff812103cd)
Location: mm/mempolicy.c:125
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff8120f400-ffffffff8120f43c: get_task_policy.part.31 (STB_LOCAL)
ffffffff81210b50-ffffffff81210b6d: get_task_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8121aedc)
Location: mm/mempolicy.c:128
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff8121ad40-ffffffff8121ad7c: get_task_policy.part.28 (STB_LOCAL)
ffffffff8121c4e0-ffffffff8121c4fe: get_task_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff812360fc)
Location: mm/mempolicy.c:130
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff81235f60-ffffffff81235f9c: get_task_policy.part.30 (STB_LOCAL)
ffffffff81237690-ffffffff812376ae: get_task_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8125909e)
Location: mm/mempolicy.c:130
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
  - fs/proc/task_mmu.c:m_start
```
**Symbols:**

```
ffffffff81258f70-ffffffff81258fac: get_task_policy.part.33 (STB_LOCAL)
ffffffff8125ab10-ffffffff8125ab2d: get_task_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8126d49e)
Location: mm/mempolicy.c:130
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
```
**Symbols:**

```
ffffffff8126d360-ffffffff8126d39c: get_task_policy.part.35 (STB_LOCAL)
ffffffff8126f2d0-ffffffff8126f2ed: get_task_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff812888ff)
Location: mm/mempolicy.c:130
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
```
**Symbols:**

```
ffffffff81288720-ffffffff8128875e: get_task_policy.part.0 (STB_LOCAL)
ffffffff8128a8c0-ffffffff8128a8dd: get_task_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8129846f)
Location: mm/mempolicy.c:130
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
```
**Symbols:**

```
ffffffff81298290-ffffffff812982ce: get_task_policy.part.0 (STB_LOCAL)
ffffffff8129a430-ffffffff8129a44d: get_task_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d04fe)
Location: mm/mempolicy.c:156
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
**Symbols:**

```
ffffffff812ce550-ffffffff812ce59a: get_task_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812dc01e)
Location: mm/mempolicy.c:156
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - mm/hugetlb.c:allowed_mems_nr
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
**Symbols:**

```
ffffffff812d94e0-ffffffff812d952a: get_task_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e389b)
Location: mm/mempolicy.c:156
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
**Symbols:**

```
ffffffff812e0d60-ffffffff812e0daa: get_task_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8132aae1)
Location: mm/mempolicy.c:158
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
**Symbols:**

```
ffffffff81327f30-ffffffff81327fa3: get_task_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8139a48a)
Location: mm/mempolicy.c:161
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
**Symbols:**

```
ffffffff81397160-ffffffff813971f7: get_task_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8141a4aa)
Location: mm/mempolicy.c:161
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
**Symbols:**

```
ffffffff81416c20-ffffffff81416cb7: get_task_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8144da38)
Location: mm/mempolicy.c:161
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
**Symbols:**

```
ffffffff8144a160-ffffffff8144a1f7: get_task_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8148603a)
Location: mm/mempolicy.c:166
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:folio_alloc
  - mm/mempolicy.c:folio_alloc
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_mbind
Direct callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_alloc_and_add_folio
  - mm/shmem.c:shmem_alloc_folio
  - mm/zswap.c:zswap_writeback_entry
  - fs/proc/task_mmu.c:hold_task_mempolicy
```
**Symbols:**

```
ffffffff81483bf0-ffffffff81483c87: get_task_policy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffff800010338448)
Location: mm/mempolicy.c:130
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
```
**Symbols:**

```
ffff800010337e38-ffff800010337eac: get_task_policy.part.0 (STB_LOCAL)
ffff800010338e10-ffff800010338e40: get_task_policy (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (c000000000411994)
Location: mm/mempolicy.c:130
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
```
**Symbols:**

```
c000000000411650-c0000000004116a4: get_task_policy.part.0 (STB_LOCAL)
c0000000004136d0-c0000000004136f0: get_task_policy (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff81290a4f)
Location: mm/mempolicy.c:130
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
```
**Symbols:**

```
ffffffff81290870-ffffffff812908ae: get_task_policy.part.0 (STB_LOCAL)
ffffffff81292a10-ffffffff81292a2d: get_task_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff812826cf)
Location: mm/mempolicy.c:130
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
```
**Symbols:**

```
ffffffff812824f0-ffffffff8128252e: get_task_policy.part.0 (STB_LOCAL)
ffffffff81284620-ffffffff8128463d: get_task_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8128e85f)
Location: mm/mempolicy.c:130
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
```
**Symbols:**

```
ffffffff8128e680-ffffffff8128e6be: get_task_policy.part.0 (STB_LOCAL)
ffffffff81290820-ffffffff8129083d: get_task_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct mempolicy *get_task_policy(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8129e75f)
Location: mm/mempolicy.c:130
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
Direct callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:vma_policy_mof
```
**Symbols:**

```
ffffffff8129e580-ffffffff8129e5be: get_task_policy.part.0 (STB_LOCAL)
ffffffff812a0650-ffffffff812a066d: get_task_policy (STB_GLOBAL)
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
