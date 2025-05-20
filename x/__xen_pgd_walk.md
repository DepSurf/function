# Function: <code>__xen_pgd_walk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __xen_pgd_walk(struct mm_struct *mm, pgd_t *pgd, int (*func)(struct mm_struct *, struct page *, enum pt_level), long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101e4b0)
Location: arch/x86/xen/mmu.c:610
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
**Symbols:**

```
ffffffff8101e4b0-ffffffff8101e772: __xen_pgd_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __xen_pgd_walk(struct mm_struct *mm, pgd_t *pgd, int (*func)(struct mm_struct *, struct page *, enum pt_level), long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101d8b0)
Location: arch/x86/xen/mmu.c:611
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
```
**Symbols:**

```
ffffffff8101d8b0-ffffffff8101db92: __xen_pgd_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __xen_pgd_walk(struct mm_struct *mm, pgd_t *pgd, int (*func)(struct mm_struct *, struct page *, enum pt_level), long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101dfc0)
Location: arch/x86/xen/mmu.c:611
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
```
**Symbols:**

```
ffffffff8101dfc0-ffffffff8101e28d: __xen_pgd_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __xen_pgd_walk(struct mm_struct *mm, pgd_t *pgd, int (*func)(struct mm_struct *, struct page *, enum pt_level), long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81020180)
Location: arch/x86/xen/mmu_pv.c:636
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
```
**Symbols:**

```
ffffffff81020180-ffffffff81020463: __xen_pgd_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __xen_pgd_walk(struct mm_struct *mm, pgd_t *pgd, int (*func)(struct mm_struct *, struct page *, enum pt_level), long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81020e00)
Location: arch/x86/xen/mmu_pv.c:612
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
```
**Symbols:**

```
ffffffff81020e00-ffffffff8102113c: __xen_pgd_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __xen_pgd_walk(struct mm_struct *mm, pgd_t *pgd, int (*func)(struct mm_struct *, struct page *, enum pt_level), long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810219a0)
Location: arch/x86/xen/mmu_pv.c:636
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
```
**Symbols:**

```
ffffffff810219a0-ffffffff81021cb8: __xen_pgd_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __xen_pgd_walk(struct mm_struct *mm, pgd_t *pgd, int (*func)(struct mm_struct *, struct page *, enum pt_level), long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81021160)
Location: arch/x86/xen/mmu_pv.c:645
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
```
**Symbols:**

```
ffffffff81021160-ffffffff8102145a: __xen_pgd_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __xen_pgd_walk(struct mm_struct *mm, pgd_t *pgd, int (*func)(struct mm_struct *, struct page *, enum pt_level), long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81022cc0)
Location: arch/x86/xen/mmu_pv.c:645
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
```
**Symbols:**

```
ffffffff81022cc0-ffffffff81022fc3: __xen_pgd_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __xen_pgd_walk(struct mm_struct *mm, pgd_t *pgd, int (*func)(struct mm_struct *, struct page *, enum pt_level), long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023600)
Location: arch/x86/xen/mmu_pv.c:645
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
```
**Symbols:**

```
ffffffff81023600-ffffffff81023903: __xen_pgd_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __xen_pgd_walk(struct mm_struct *mm, pgd_t *pgd, int (*func)(struct mm_struct *, struct page *, enum pt_level), long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81026390)
Location: arch/x86/xen/mmu_pv.c:645
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
```
**Symbols:**

```
ffffffff81026390-ffffffff81026583: __xen_pgd_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __xen_pgd_walk(struct mm_struct *mm, pgd_t *pgd, void (*func)(struct mm_struct *, struct page *, enum pt_level), long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81026aa0)
Location: arch/x86/xen/mmu_pv.c:597
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
```
**Symbols:**

```
ffffffff81026aa0-ffffffff81026c71: __xen_pgd_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __xen_pgd_walk(struct mm_struct *mm, pgd_t *pgd, void (*func)(struct mm_struct *, struct page *, enum pt_level), long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028de0)
Location: arch/x86/xen/mmu_pv.c:597
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
```
**Symbols:**

```
ffffffff81028de0-ffffffff81028f9b: __xen_pgd_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __xen_pgd_walk(struct mm_struct *mm, pgd_t *pgd, void (*func)(struct mm_struct *, struct page *, enum pt_level), long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:597
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
```
**Symbols:**

```
ffffffff8102d520-ffffffff8102d6f0: __xen_pgd_walk (STB_LOCAL)
ffffffff81c978aa-ffffffff81c979af: __xen_pgd_walk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __xen_pgd_walk(struct mm_struct *mm, pgd_t *pgd, void (*func)(struct mm_struct *, struct page *, enum pt_level), long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:601
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
```
**Symbols:**

```
ffffffff81032380-ffffffff8103256c: __xen_pgd_walk (STB_LOCAL)
ffffffff81e46bd9-ffffffff81e46d5d: __xen_pgd_walk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __xen_pgd_walk(struct mm_struct *mm, pgd_t *pgd, void (*func)(struct mm_struct *, struct page *, enum pt_level), long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:601
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
```
**Symbols:**

```
ffffffff81039c90-ffffffff81039e7b: __xen_pgd_walk (STB_LOCAL)
ffffffff82051b8a-ffffffff82051d12: __xen_pgd_walk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __xen_pgd_walk(struct mm_struct *mm, pgd_t *pgd, void (*func)(struct mm_struct *, struct page *, enum pt_level), long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:617
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
```
**Symbols:**

```
ffffffff810397a0-ffffffff8103997f: __xen_pgd_walk (STB_LOCAL)
ffffffff820d0039-ffffffff820d016d: __xen_pgd_walk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __xen_pgd_walk(struct mm_struct *mm, pgd_t *pgd, void (*func)(struct mm_struct *, struct page *, enum pt_level), long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:617
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
```
**Symbols:**

```
ffffffff8103fc50-ffffffff8103fe2f: __xen_pgd_walk (STB_LOCAL)
ffffffff821aa9a6-ffffffff821aaada: __xen_pgd_walk.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int __xen_pgd_walk(struct mm_struct *mm, pgd_t *pgd, int (*func)(struct mm_struct *, struct page *, enum pt_level), long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023760)
Location: arch/x86/xen/mmu_pv.c:645
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
```
**Symbols:**

```
ffffffff81023760-ffffffff81023a63: __xen_pgd_walk (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __xen_pgd_walk(struct mm_struct *mm, pgd_t *pgd, int (*func)(struct mm_struct *, struct page *, enum pt_level), long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810235c0)
Location: arch/x86/xen/mmu_pv.c:645
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
```
**Symbols:**

```
ffffffff810235c0-ffffffff810238c3: __xen_pgd_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __xen_pgd_walk(struct mm_struct *mm, pgd_t *pgd, int (*func)(struct mm_struct *, struct page *, enum pt_level), long unsigned int limit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023a70)
Location: arch/x86/xen/mmu_pv.c:645
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:xen_after_bootmem
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
```
**Symbols:**

```
ffffffff81023a70-ffffffff81023d73: __xen_pgd_walk (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
