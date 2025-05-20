# Function: <code>clear_user_highpage</code>

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
In mm/memory.c (ffffffff811c209b)
Location: include/linux/highmem.h:133
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/huge_memory.c (ffffffff811f5478)
Location: include/linux/highmem.h:133
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
```
```
In fs/dax.c (ffffffff8125df18)
Location: include/linux/highmem.h:133
Inline: True
Inline callers:
  - fs/dax.c:__dax_fault
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
In mm/memory.c (ffffffff811ddbdb)
Location: include/linux/highmem.h:133
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/khugepaged.c (ffffffff8121a3fe)
Location: include/linux/highmem.h:133
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81287ce8)
Location: include/linux/highmem.h:133
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
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
In mm/memory.c (ffffffff811eda02)
Location: include/linux/highmem.h:133
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/khugepaged.c (ffffffff8122d46d)
Location: include/linux/highmem.h:133
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (ffffffff8129c384)
Location: include/linux/highmem.h:133
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
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
In mm/memory.c (ffffffff811f89ab)
Location: include/linux/highmem.h:133
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/khugepaged.c (ffffffff812384f5)
Location: include/linux/highmem.h:133
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812ab4a5)
Location: include/linux/highmem.h:133
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
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
In mm/memory.c (ffffffff81210c5c)
Location: include/linux/highmem.h:134
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/khugepaged.c (ffffffff81259b08)
Location: include/linux/highmem.h:134
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (ffffffff812cedeb)
Location: include/linux/highmem.h:134
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
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
In mm/memory.c (ffffffff8123169b)
Location: include/linux/highmem.h:134
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff8127c47d)
Location: include/linux/highmem.h:134
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812f960b)
Location: include/linux/highmem.h:134
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
In mm/memory.c (ffffffff81244e6b)
Location: include/linux/highmem.h:158
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff81290b1f)
Location: include/linux/highmem.h:158
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8130d7ac)
Location: include/linux/highmem.h:158
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
In mm/memory.c (ffffffff81256e31)
Location: include/linux/highmem.h:158
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff812a9e5a)
Location: include/linux/highmem.h:158
Inline: True
```
```
In fs/dax.c (ffffffff813359cd)
Location: include/linux/highmem.h:158
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
In mm/memory.c (ffffffff812653c1)
Location: include/linux/highmem.h:158
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff812bb3ca)
Location: include/linux/highmem.h:158
Inline: True
```
```
In fs/dax.c (ffffffff813495cd)
Location: include/linux/highmem.h:158
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
In mm/memory.c (ffffffff8129579e)
Location: include/linux/highmem.h:227
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff812f0630)
Location: include/linux/highmem.h:227
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_copy
```
```
In fs/dax.c (ffffffff8138e89f)
Location: include/linux/highmem.h:227
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff812a068e)
Location: include/linux/highmem.h:147
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff812fbdba)
Location: include/linux/highmem.h:147
Inline: True
```
```
In fs/dax.c (ffffffff8139fffd)
Location: include/linux/highmem.h:147
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff812a5fcf)
Location: include/linux/highmem.h:147
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff81302d03)
Location: include/linux/highmem.h:147
Inline: True
```
```
In fs/dax.c (ffffffff813a7593)
Location: include/linux/highmem.h:147
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff812e7450)
Location: include/linux/highmem.h:144
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff8134c7c3)
Location: include/linux/highmem.h:144
Inline: True
```
```
In fs/dax.c (ffffffff813f4cf5)
Location: include/linux/highmem.h:144
Inline: True
Inline callers:
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
In mm/shmem.c (ffffffff8131cafa)
Location: include/linux/highmem.h:203
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81348629)
Location: include/linux/highmem.h:203
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/khugepaged.c (ffffffff813c4002)
Location: include/linux/highmem.h:203
Inline: True
```
```
In fs/dax.c (ffffffff81467888)
Location: include/linux/highmem.h:203
Inline: True
Inline callers:
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
In mm/shmem.c (ffffffff813906ab)
Location: include/linux/highmem.h:203
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff813c0b39)
Location: include/linux/highmem.h:203
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/khugepaged.c (ffffffff814477a7)
Location: include/linux/highmem.h:203
Inline: True
```
```
In fs/dax.c (ffffffff814f7f48)
Location: include/linux/highmem.h:203
Inline: True
Inline callers:
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
In mm/shmem.c (ffffffff813c3031)
Location: include/linux/highmem.h:202
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff813f58aa)
Location: include/linux/highmem.h:202
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/khugepaged.c (ffffffff8147d18d)
Location: include/linux/highmem.h:202
Inline: True
```
```
In fs/dax.c (ffffffff8152f148)
Location: include/linux/highmem.h:202
Inline: True
Inline callers:
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
In mm/shmem.c (ffffffff813edb4a)
Location: include/linux/highmem.h:202
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8141f58a)
Location: include/linux/highmem.h:202
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_huge_page
```
```
In mm/khugepaged.c (ffffffff814ac95c)
Location: include/linux/highmem.h:202
Inline: True
```
```
In fs/dax.c (ffffffff81564028)
Location: include/linux/highmem.h:202
Inline: True
Inline callers:
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
In mm/memory.c (ffff8000102fbe44)
Location: include/linux/highmem.h:158
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/khugepaged.c (ffff80001035e7cc)
Location: include/linux/highmem.h:158
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffff80001040a194)
Location: include/linux/highmem.h:158
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
In mm/memory.c (c0000000003c7458)
Location: include/linux/highmem.h:158
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/khugepaged.c (c00000000044610c)
Location: include/linux/highmem.h:158
Inline: True
```
```
In fs/dax.c (c000000000516190)
Location: include/linux/highmem.h:158
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
In mm/memory.c (ffffffe00020b3ee)
Location: include/linux/highmem.h:158
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In fs/dax.c (ffffffe0002b3ada)
Location: include/linux/highmem.h:158
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
In mm/memory.c (ffffffff8125da11)
Location: include/linux/highmem.h:158
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff812b39aa)
Location: include/linux/highmem.h:158
Inline: True
```
```
In fs/dax.c (ffffffff81341bad)
Location: include/linux/highmem.h:158
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
In mm/memory.c (ffffffff8124fe61)
Location: include/linux/highmem.h:158
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff812a693c)
Location: include/linux/highmem.h:158
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813324a1)
Location: include/linux/highmem.h:158
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
In mm/memory.c (ffffffff8125b7b1)
Location: include/linux/highmem.h:158
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff812b17ba)
Location: include/linux/highmem.h:158
Inline: True
```
```
In fs/dax.c (ffffffff8133f67d)
Location: include/linux/highmem.h:158
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
In mm/memory.c (ffffffff8126b165)
Location: include/linux/highmem.h:158
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:clear_subpage
```
```
In mm/khugepaged.c (ffffffff812c1b22)
Location: include/linux/highmem.h:158
Inline: True
```
```
In fs/dax.c (ffffffff81353044)
Location: include/linux/highmem.h:158
Inline: True
```
</details>
</li>
</ul>

## Differences
