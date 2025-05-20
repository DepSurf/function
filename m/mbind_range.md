# Function: <code>mbind_range</code>

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
In mm/mempolicy.c (ffffffff811e269b)
Location: mm/mempolicy.c:692
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
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
In mm/mempolicy.c (ffffffff812010c2)
Location: mm/mempolicy.c:724
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
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
In mm/mempolicy.c (ffffffff81212bd5)
Location: mm/mempolicy.c:726
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_mbind
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
In mm/mempolicy.c (ffffffff8121df77)
Location: mm/mempolicy.c:660
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_mbind
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
In mm/mempolicy.c (ffffffff812391c7)
Location: mm/mempolicy.c:702
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_mbind
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
In mm/mempolicy.c (ffffffff8125c6f1)
Location: mm/mempolicy.c:677
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
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
In mm/mempolicy.c (ffffffff81270fd1)
Location: mm/mempolicy.c:703
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
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
In mm/mempolicy.c (ffffffff8128c4ec)
Location: mm/mempolicy.c:730
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
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
In mm/mempolicy.c (ffffffff8129c0ea)
Location: mm/mempolicy.c:731
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mbind_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, struct mempolicy *new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cfb30)
Location: mm/mempolicy.c:802
Inline: False
Direct callers:
  - mm/mempolicy.c:do_mbind
```
**Symbols:**

```
ffffffff812cfb30-ffffffff812cfcc7: mbind_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mbind_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, struct mempolicy *new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812db600)
Location: mm/mempolicy.c:802
Inline: False
Direct callers:
  - mm/mempolicy.c:do_mbind
```
**Symbols:**

```
ffffffff812db600-ffffffff812db797: mbind_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mbind_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, struct mempolicy *new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e2d80)
Location: mm/mempolicy.c:802
Inline: False
Direct callers:
  - mm/mempolicy.c:do_mbind
```
**Symbols:**

```
ffffffff812e2d80-ffffffff812e301d: mbind_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mbind_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, struct mempolicy *new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8132a0e0)
Location: mm/mempolicy.c:783
Inline: False
Direct callers:
  - mm/mempolicy.c:do_mbind
```
**Symbols:**

```
ffffffff8132a0e0-ffffffff8132a37d: mbind_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mbind_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, struct mempolicy *new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff813997e0)
Location: mm/mempolicy.c:787
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
```
**Symbols:**

```
ffffffff813997e0-ffffffff81399a78: mbind_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mbind_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, struct mempolicy *new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81419670)
Location: mm/mempolicy.c:788
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
```
**Symbols:**

```
ffffffff81419670-ffffffff81419987: mbind_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mbind_range(struct vma_iterator *vmi, struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, struct mempolicy *new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8144cc70)
Location: mm/mempolicy.c:811
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
```
**Symbols:**

```
ffffffff8144cc70-ffffffff8144cdf0: mbind_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mbind_range(struct vma_iterator *vmi, struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, struct mempolicy *new_pol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81486570)
Location: mm/mempolicy.c:785
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:do_mbind
```
**Symbols:**

```
ffffffff81486570-ffffffff814866d2: mbind_range (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff80001033b0e4)
Location: mm/mempolicy.c:731
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000415b18)
Location: mm/mempolicy.c:731
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812946ca)
Location: mm/mempolicy.c:731
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812862da)
Location: mm/mempolicy.c:731
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812924da)
Location: mm/mempolicy.c:731
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
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
In mm/mempolicy.c (ffffffff812a233b)
Location: mm/mempolicy.c:731
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vma_iterator *vmi</code>
</li>
<li>
<b>Param added. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param added. </b>
<code>struct vm_area_struct **prev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct *mm</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, start, end, new_pol</code> ➡️ <code>vmi, vma, prev, start, end, new_pol</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
