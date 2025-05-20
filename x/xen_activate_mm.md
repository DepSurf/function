# Function: <code>xen_activate_mm</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_activate_mm(struct mm_struct *prev, struct mm_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (0)
Location: arch/x86/xen/mmu.c:987
Inline: False
```
**Symbols:**

```
ffffffff81021a00-ffffffff81021a10: xen_activate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_activate_mm(struct mm_struct *prev, struct mm_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (0)
Location: arch/x86/xen/mmu.c:987
Inline: False
```
**Symbols:**

```
ffffffff81022160-ffffffff81022170: xen_activate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_activate_mm(struct mm_struct *prev, struct mm_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024120)
Location: arch/x86/xen/mmu_pv.c:964
Inline: False
```
**Symbols:**

```
ffffffff81024120-ffffffff81024157: xen_activate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_activate_mm(struct mm_struct *prev, struct mm_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024cb0)
Location: arch/x86/xen/mmu_pv.c:938
Inline: False
```
**Symbols:**

```
ffffffff81024cb0-ffffffff81024ce7: xen_activate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_activate_mm(struct mm_struct *prev, struct mm_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025bf0)
Location: arch/x86/xen/mmu_pv.c:967
Inline: False
```
**Symbols:**

```
ffffffff81025bf0-ffffffff81025c27: xen_activate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_activate_mm(struct mm_struct *prev, struct mm_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810257a0)
Location: arch/x86/xen/mmu_pv.c:977
Inline: False
```
**Symbols:**

```
ffffffff810257a0-ffffffff810257d7: xen_activate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_activate_mm(struct mm_struct *prev, struct mm_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810274e0)
Location: arch/x86/xen/mmu_pv.c:977
Inline: False
```
**Symbols:**

```
ffffffff810274e0-ffffffff81027519: xen_activate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_activate_mm(struct mm_struct *prev, struct mm_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81027ac0)
Location: arch/x86/xen/mmu_pv.c:977
Inline: False
```
**Symbols:**

```
ffffffff81027ac0-ffffffff81027af9: xen_activate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xen_activate_mm(struct mm_struct *prev, struct mm_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810296c0)
Location: arch/x86/xen/mmu_pv.c:977
Inline: True
```
**Symbols:**

```
ffffffff810296c0-ffffffff810296f9: xen_activate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xen_activate_mm(struct mm_struct *prev, struct mm_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81028be0)
Location: arch/x86/xen/mmu_pv.c:882
Inline: True
```
**Symbols:**

```
ffffffff81028be0-ffffffff81028c19: xen_activate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xen_activate_mm(struct mm_struct *prev, struct mm_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102a8e0)
Location: arch/x86/xen/mmu_pv.c:882
Inline: True
```
**Symbols:**

```
ffffffff8102a8e0-ffffffff8102a919: xen_activate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xen_activate_mm(struct mm_struct *prev, struct mm_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102ef10)
Location: arch/x86/xen/mmu_pv.c:882
Inline: True
```
**Symbols:**

```
ffffffff8102ef10-ffffffff8102ef49: xen_activate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void xen_activate_mm(struct mm_struct *prev, struct mm_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810341e0)
Location: arch/x86/xen/mmu_pv.c:888
Inline: True
```
**Symbols:**

```
ffffffff810341e0-ffffffff8103421c: xen_activate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void xen_activate_mm(struct mm_struct *prev, struct mm_struct *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103bc90)
Location: arch/x86/xen/mmu_pv.c:888
Inline: True
```
**Symbols:**

```
ffffffff8103bc90-ffffffff8103bccc: xen_activate_mm (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
void xen_activate_mm(struct mm_struct *prev, struct mm_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81027c20)
Location: arch/x86/xen/mmu_pv.c:977
Inline: False
```
**Symbols:**

```
ffffffff81027c20-ffffffff81027c59: xen_activate_mm (STB_LOCAL)
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
void xen_activate_mm(struct mm_struct *prev, struct mm_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81027a80)
Location: arch/x86/xen/mmu_pv.c:977
Inline: False
```
**Symbols:**

```
ffffffff81027a80-ffffffff81027ab9: xen_activate_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_activate_mm(struct mm_struct *prev, struct mm_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810286c0)
Location: arch/x86/xen/mmu_pv.c:977
Inline: False
```
**Symbols:**

```
ffffffff810286c0-ffffffff810286f7: xen_activate_mm (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
