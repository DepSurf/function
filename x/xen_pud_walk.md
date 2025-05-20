# Function: <code>xen_pud_walk</code>

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
Location: arch/x86/xen/mmu_pv.c:577
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
Location: arch/x86/xen/mmu_pv.c:557
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
In arch/x86/xen/mmu_pv.c (ffffffff81021ab1)
Location: arch/x86/xen/mmu_pv.c:581
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
In arch/x86/xen/mmu_pv.c (ffffffff81021253)
Location: arch/x86/xen/mmu_pv.c:590
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
In arch/x86/xen/mmu_pv.c (ffffffff81022dbd)
Location: arch/x86/xen/mmu_pv.c:590
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
In arch/x86/xen/mmu_pv.c (ffffffff810236fd)
Location: arch/x86/xen/mmu_pv.c:590
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
int xen_pud_walk(struct mm_struct *mm, pud_t *pud, int (*func)(struct mm_struct *, struct page *, enum pt_level), bool last, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025f80)
Location: arch/x86/xen/mmu_pv.c:590
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
**Symbols:**

```
ffffffff81025f80-ffffffff810260b0: xen_pud_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_pud_walk(struct mm_struct *mm, pud_t *pud, void (*func)(struct mm_struct *, struct page *, enum pt_level), bool last, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81026510)
Location: arch/x86/xen/mmu_pv.c:547
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
**Symbols:**

```
ffffffff81026510-ffffffff81026635: xen_pud_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_pud_walk(struct mm_struct *mm, pud_t *pud, void (*func)(struct mm_struct *, struct page *, enum pt_level), bool last, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028c20)
Location: arch/x86/xen/mmu_pv.c:547
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
**Symbols:**

```
ffffffff81028c20-ffffffff81028dd3: xen_pud_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_pud_walk(struct mm_struct *mm, pud_t *pud, void (*func)(struct mm_struct *, struct page *, enum pt_level), bool last, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102d360)
Location: arch/x86/xen/mmu_pv.c:547
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
**Symbols:**

```
ffffffff8102d360-ffffffff8102d513: xen_pud_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_pud_walk(struct mm_struct *mm, pud_t *pud, void (*func)(struct mm_struct *, struct page *, enum pt_level), bool last, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810321b0)
Location: arch/x86/xen/mmu_pv.c:551
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
**Symbols:**

```
ffffffff810321b0-ffffffff81032374: xen_pud_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_pud_walk(struct mm_struct *mm, pud_t *pud, void (*func)(struct mm_struct *, struct page *, enum pt_level), bool last, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81039ab0)
Location: arch/x86/xen/mmu_pv.c:551
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
**Symbols:**

```
ffffffff81039ab0-ffffffff81039c79: xen_pud_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_pud_walk(struct mm_struct *mm, pud_t *pud, void (*func)(struct mm_struct *, struct page *, enum pt_level), bool last, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810395c0)
Location: arch/x86/xen/mmu_pv.c:567
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
**Symbols:**

```
ffffffff810395c0-ffffffff81039786: xen_pud_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_pud_walk(struct mm_struct *mm, pud_t *pud, void (*func)(struct mm_struct *, struct page *, enum pt_level), bool last, long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103fa70)
Location: arch/x86/xen/mmu_pv.c:567
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
**Symbols:**

```
ffffffff8103fa70-ffffffff8103fc36: xen_pud_walk (STB_LOCAL)
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
In arch/x86/xen/mmu_pv.c (ffffffff8102385d)
Location: arch/x86/xen/mmu_pv.c:590
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
In arch/x86/xen/mmu_pv.c (ffffffff810236bd)
Location: arch/x86/xen/mmu_pv.c:590
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
In arch/x86/xen/mmu_pv.c (ffffffff81023b6d)
Location: arch/x86/xen/mmu_pv.c:590
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
