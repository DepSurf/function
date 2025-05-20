# Function: <code>xen_drop_mm_ref</code>

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
In arch/x86/xen/mmu.c (ffffffff81020729)
Location: arch/x86/xen/mmu.c:1020
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
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
In arch/x86/xen/mmu.c (ffffffff81020717)
Location: arch/x86/xen/mmu.c:1021
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
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
In arch/x86/xen/mmu.c (ffffffff81020db9)
Location: arch/x86/xen/mmu.c:1021
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
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
In arch/x86/xen/mmu_pv.c (ffffffff81021ed9)
Location: arch/x86/xen/mmu_pv.c:998
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
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
In arch/x86/xen/mmu_pv.c (ffffffff810229d9)
Location: arch/x86/xen/mmu_pv.c:972
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
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
In arch/x86/xen/mmu_pv.c (ffffffff810232f9)
Location: arch/x86/xen/mmu_pv.c:1001
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
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
In arch/x86/xen/mmu_pv.c (ffffffff81022da0)
Location: arch/x86/xen/mmu_pv.c:1011
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
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
In arch/x86/xen/mmu_pv.c (ffffffff81025469)
Location: arch/x86/xen/mmu_pv.c:1011
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
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
In arch/x86/xen/mmu_pv.c (ffffffff81025a49)
Location: arch/x86/xen/mmu_pv.c:1011
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_drop_mm_ref(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025e00)
Location: arch/x86/xen/mmu_pv.c:1011
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
**Symbols:**

```
ffffffff81025e00-ffffffff81025f75: xen_drop_mm_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_drop_mm_ref(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81026640)
Location: arch/x86/xen/mmu_pv.c:916
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
**Symbols:**

```
ffffffff81026640-ffffffff810267b5: xen_drop_mm_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_drop_mm_ref(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810282c0)
Location: arch/x86/xen/mmu_pv.c:916
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
**Symbols:**

```
ffffffff810282c0-ffffffff81028435: xen_drop_mm_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_drop_mm_ref(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102c920)
Location: arch/x86/xen/mmu_pv.c:916
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
**Symbols:**

```
ffffffff8102c920-ffffffff8102cae3: xen_drop_mm_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_drop_mm_ref(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810316c0)
Location: arch/x86/xen/mmu_pv.c:922
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
**Symbols:**

```
ffffffff810316c0-ffffffff81031895: xen_drop_mm_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_drop_mm_ref(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81038ef0)
Location: arch/x86/xen/mmu_pv.c:922
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
**Symbols:**

```
ffffffff81038ef0-ffffffff810390fe: xen_drop_mm_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_drop_mm_ref(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81038e20)
Location: arch/x86/xen/mmu_pv.c:931
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
**Symbols:**

```
ffffffff81038e20-ffffffff81039034: xen_drop_mm_ref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_drop_mm_ref(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103f2d0)
Location: arch/x86/xen/mmu_pv.c:931
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
**Symbols:**

```
ffffffff8103f2d0-ffffffff8103f4e4: xen_drop_mm_ref (STB_LOCAL)
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
In arch/x86/xen/mmu_pv.c (ffffffff81025ba9)
Location: arch/x86/xen/mmu_pv.c:1011
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
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
In arch/x86/xen/mmu_pv.c (ffffffff81025a09)
Location: arch/x86/xen/mmu_pv.c:1011
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
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
In arch/x86/xen/mmu_pv.c (ffffffff810264f0)
Location: arch/x86/xen/mmu_pv.c:1011
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
