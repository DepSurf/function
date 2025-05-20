# Function: <code>xen_pmd_walk</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81020195)
Location: arch/x86/xen/mmu_pv.c:563
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
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
In arch/x86/xen/mmu_pv.c (ffffffff81020e19)
Location: arch/x86/xen/mmu_pv.c:543
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:567
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:576
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:576
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:576
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xen_pmd_walk(struct mm_struct *mm, pmd_t *pmd, int (*func)(struct mm_struct *, struct page *, enum pt_level), bool last, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025ca0)
Location: arch/x86/xen/mmu_pv.c:576
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
**Symbols:**

```
ffffffff81025ca0-ffffffff81025d67: xen_pmd_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_pmd_walk(struct mm_struct *mm, pmd_t *pmd, void (*func)(struct mm_struct *, struct page *, enum pt_level), bool last, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810263c0)
Location: arch/x86/xen/mmu_pv.c:533
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
**Symbols:**

```
ffffffff810263c0-ffffffff8102647a: xen_pmd_walk (STB_LOCAL)
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:533
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:533
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:537
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:537
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:553
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:553
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:576
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:576
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:576
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*func)(struct mm_struct *, struct page *, enum pt_level)</code> ➡️ <code>void (*func)(struct mm_struct *, struct page *, enum pt_level)</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
</ul>
