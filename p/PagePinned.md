# Function: <code>PagePinned</code>

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
In arch/x86/xen/mmu.c (ffffffff8101e29a)
Location: include/linux/page-flags.h:219
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/mmu.c:xen_set_pud
  - arch/x86/xen/mmu.c:xen_set_pmd
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_mm_pin_all
  - arch/x86/xen/mmu.c:xen_mm_unpin_all
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101f039)
Location: include/linux/page-flags.h:270
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/mmu.c:xen_mm_unpin_all
  - arch/x86/xen/mmu.c:xen_mm_pin_all
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_set_pud
  - arch/x86/xen/mmu.c:xen_set_pmd
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
In arch/x86/xen/mmu.c (ffffffff8101f723)
Location: include/linux/page-flags.h:280
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_release_pud
  - arch/x86/xen/mmu.c:xen_alloc_pud
  - arch/x86/xen/mmu.c:xen_release_pmd
  - arch/x86/xen/mmu.c:xen_release_pte
  - arch/x86/xen/mmu.c:xen_alloc_pmd
  - arch/x86/xen/mmu.c:xen_alloc_pte
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/mmu.c:xen_mm_unpin_all
  - arch/x86/xen/mmu.c:xen_mm_pin_all
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_set_pud
  - arch/x86/xen/mmu.c:xen_set_pmd
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
In arch/x86/xen/mmu_pv.c (ffffffff81022a15)
Location: include/linux/page-flags.h:280
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
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
In arch/x86/xen/mmu_pv.c (ffffffff81023735)
Location: include/linux/page-flags.h:281
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024200)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024680)
Location: include/linux/page-flags.h:299
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81026480)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81026490)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810290f5)
Location: include/linux/page-flags.h:338
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810299fe)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102a97c)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102f74e)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
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
In arch/x86/xen/mmu_pv.c (ffffffff81034bee)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103c43e)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103c45f)
Location: include/linux/page-flags.h:483
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81042adf)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_release_ptpage
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810265f0)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81026450)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810271a0)
Location: include/linux/page-flags.h:330
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pud
  - arch/x86/xen/mmu_pv.c:xen_release_pmd
  - arch/x86/xen/mmu_pv.c:xen_release_pte
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_mm_unpin_all
  - arch/x86/xen/mmu_pv.c:xen_mm_pin_all
  - arch/x86/xen/mmu_pv.c:xen_page_pinned
```
</details>
</li>
</ul>

## Differences
