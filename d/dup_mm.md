# Function: <code>dup_mm</code>

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
In kernel/fork.c (ffffffff8107f878)
Location: kernel/fork.c:918
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
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
In kernel/fork.c (ffffffff81080ccc)
Location: kernel/fork.c:974
Inline: True
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
In kernel/fork.c (ffffffff810856cd)
Location: kernel/fork.c:1128
Inline: True
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
In kernel/fork.c (ffffffff81082d31)
Location: kernel/fork.c:1175
Inline: True
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
In kernel/fork.c (ffffffff81088e0b)
Location: kernel/fork.c:1187
Inline: True
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
In kernel/fork.c (ffffffff8108b786)
Location: kernel/fork.c:1256
Inline: True
Inline callers:
  - kernel/fork.c:copy_mm
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
In kernel/fork.c (ffffffff81095217)
Location: kernel/fork.c:1312
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mm_struct *dup_mm(struct task_struct *tsk, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097b90)
Location: kernel/fork.c:1337
Inline: False
Direct callers:
  - kernel/fork.c:copy_init_mm
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81097b90-ffffffff81097ca1: dup_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mm_struct *dup_mm(struct task_struct *tsk, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109e250)
Location: kernel/fork.c:1348
Inline: False
Direct callers:
  - kernel/fork.c:copy_init_mm
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8109e250-ffffffff8109e361: dup_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mm_struct *dup_mm(struct task_struct *tsk, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a5840)
Location: kernel/fork.c:1362
Inline: False
Direct callers:
  - kernel/fork.c:copy_init_mm
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810a5840-ffffffff810a5951: dup_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mm_struct *dup_mm(struct task_struct *tsk, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a1030)
Location: kernel/fork.c:1359
Inline: False
Direct callers:
  - kernel/fork.c:copy_init_mm
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810a1030-ffffffff810a1141: dup_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mm_struct *dup_mm(struct task_struct *tsk, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a1db0)
Location: kernel/fork.c:1365
Inline: False
Direct callers:
  - kernel/fork.c:copy_init_mm
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810a1db0-ffffffff810a1ebc: dup_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mm_struct *dup_mm(struct task_struct *tsk, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b3980)
Location: kernel/fork.c:1444
Inline: False
Direct callers:
  - kernel/fork.c:copy_init_mm
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810b3980-ffffffff810b3a8c: dup_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mm_struct *dup_mm(struct task_struct *tsk, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c9bd0)
Location: kernel/fork.c:1515
Inline: False
Direct callers:
  - kernel/fork.c:copy_init_mm
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810c9bd0-ffffffff810c9ce7: dup_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff810e71d0)
Location: kernel/fork.c:1538
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810e71d0-ffffffff810e72e2: dup_mm.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff810f2ce0)
Location: kernel/fork.c:1679
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810f2ce0-ffffffff810f2df5: dup_mm.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff810fb840)
Location: kernel/fork.c:1675
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810fb840-ffffffff810fb955: dup_mm.constprop.0 (STB_LOCAL)
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
struct mm_struct *dup_mm(struct task_struct *tsk, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f2df8)
Location: kernel/fork.c:1348
Inline: False
Direct callers:
  - kernel/fork.c:copy_init_mm
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffff8000100f2df8-ffff8000100f2f00: dup_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mm_struct *dup_mm(struct task_struct *tsk, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c03516a0)
Location: kernel/fork.c:1348
Inline: False
Direct callers:
  - kernel/fork.c:copy_init_mm
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c03516a0-c035178c: dup_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mm_struct *dup_mm(struct task_struct *tsk, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c000000000138ae0)
Location: kernel/fork.c:1348
Inline: False
Direct callers:
  - kernel/fork.c:copy_init_mm
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c000000000138ae0-c000000000138c54: dup_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mm_struct *dup_mm(struct task_struct *tsk, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000bf928)
Location: kernel/fork.c:1348
Inline: False
Direct callers:
  - kernel/fork.c:copy_init_mm
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffe0000bf928-ffffffe0000bfaf8: dup_mm (STB_LOCAL)
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
struct mm_struct *dup_mm(struct task_struct *tsk, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097b70)
Location: kernel/fork.c:1348
Inline: False
Direct callers:
  - kernel/fork.c:copy_init_mm
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81097b70-ffffffff81097c81: dup_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mm_struct *dup_mm(struct task_struct *tsk, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810865e0)
Location: kernel/fork.c:1348
Inline: False
Direct callers:
  - kernel/fork.c:copy_init_mm
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810865e0-ffffffff810866f1: dup_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mm_struct *dup_mm(struct task_struct *tsk, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097b20)
Location: kernel/fork.c:1348
Inline: False
Direct callers:
  - kernel/fork.c:copy_init_mm
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81097b20-ffffffff81097c31: dup_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mm_struct *dup_mm(struct task_struct *tsk, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109f720)
Location: kernel/fork.c:1348
Inline: False
Direct callers:
  - kernel/fork.c:copy_init_mm
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8109f720-ffffffff8109f831: dup_mm (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
