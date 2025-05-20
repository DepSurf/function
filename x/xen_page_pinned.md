# Function: <code>xen_page_pinned</code>

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
In arch/x86/xen/mmu.c (ffffffff8101fea9)
Location: arch/x86/xen/mmu.c:190
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_set_pud
  - arch/x86/xen/mmu.c:xen_set_pmd
  - arch/x86/xen/mmu.c:xen_exit_mmap
  - arch/x86/xen/mmu.c:xen_set_pgd
  - arch/x86/xen/mmu.c:xen_set_pgd
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
In arch/x86/xen/mmu.c (ffffffff81020814)
Location: arch/x86/xen/mmu.c:191
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
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
In arch/x86/xen/mmu.c (ffffffff81020ed7)
Location: arch/x86/xen/mmu.c:191
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
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
In arch/x86/xen/mmu_pv.c (ffffffff81021fcc)
Location: arch/x86/xen/mmu_pv.c:158
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
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
In arch/x86/xen/mmu_pv.c (ffffffff81022ab1)
Location: arch/x86/xen/mmu_pv.c:158
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool xen_page_pinned(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81021410)
Location: arch/x86/xen/mmu_pv.c:164
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81021410-ffffffff81021464: xen_page_pinned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool xen_page_pinned(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81020c80)
Location: arch/x86/xen/mmu_pv.c:173
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81020c80-ffffffff81020cd4: xen_page_pinned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool xen_page_pinned(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81022c60)
Location: arch/x86/xen/mmu_pv.c:173
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81022c60-ffffffff81022cb4: xen_page_pinned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool xen_page_pinned(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810235a0)
Location: arch/x86/xen/mmu_pv.c:173
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff810235a0-ffffffff810235f4: xen_page_pinned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool xen_page_pinned(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025c40)
Location: arch/x86/xen/mmu_pv.c:173
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81025c40-ffffffff81025c94: xen_page_pinned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool xen_page_pinned(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81026360)
Location: arch/x86/xen/mmu_pv.c:162
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81026360-ffffffff810263b4: xen_page_pinned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool xen_page_pinned(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028260)
Location: arch/x86/xen/mmu_pv.c:162
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81028260-ffffffff810282b4: xen_page_pinned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool xen_page_pinned(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102c8c0)
Location: arch/x86/xen/mmu_pv.c:162
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff8102c8c0-ffffffff8102c911: xen_page_pinned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool xen_page_pinned(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81031380)
Location: arch/x86/xen/mmu_pv.c:164
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81031380-ffffffff810313dd: xen_page_pinned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool xen_page_pinned(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81038b20)
Location: arch/x86/xen/mmu_pv.c:164
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81038b20-ffffffff81038b7d: xen_page_pinned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool xen_page_pinned(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81038a60)
Location: arch/x86/xen/mmu_pv.c:180
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81038a60-ffffffff81038abd: xen_page_pinned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool xen_page_pinned(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103ee20)
Location: arch/x86/xen/mmu_pv.c:180
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff8103ee20-ffffffff8103ee7d: xen_page_pinned (STB_LOCAL)
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
bool xen_page_pinned(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023700)
Location: arch/x86/xen/mmu_pv.c:173
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81023700-ffffffff81023754: xen_page_pinned (STB_LOCAL)
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
bool xen_page_pinned(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023560)
Location: arch/x86/xen/mmu_pv.c:173
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81023560-ffffffff810235b4: xen_page_pinned (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool xen_page_pinned(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023a10)
Location: arch/x86/xen/mmu_pv.c:173
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_alloc_pud
  - arch/x86/xen/mmu_pv.c:xen_alloc_pmd
  - arch/x86/xen/mmu_pv.c:xen_alloc_pte
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81023a10-ffffffff81023a64: xen_page_pinned (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
