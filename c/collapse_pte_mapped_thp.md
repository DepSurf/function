# Function: <code>collapse_pte_mapped_thp</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void collapse_pte_mapped_thp(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812bdd70)
Location: mm/khugepaged.c:1290
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff812bdd70-ffffffff812be0f3: collapse_pte_mapped_thp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void collapse_pte_mapped_thp(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812f3570)
Location: mm/khugepaged.c:1408
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff812f3570-ffffffff812f3987: collapse_pte_mapped_thp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void collapse_pte_mapped_thp(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812fed50)
Location: mm/khugepaged.c:1439
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff812fed50-ffffffff812ff184: collapse_pte_mapped_thp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void collapse_pte_mapped_thp(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813059c0)
Location: mm/khugepaged.c:1429
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff813059c0-ffffffff81305e02: collapse_pte_mapped_thp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void collapse_pte_mapped_thp(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8134f830)
Location: mm/khugepaged.c:1433
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff8134f830-ffffffff8134fc6c: collapse_pte_mapped_thp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void collapse_pte_mapped_thp(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813c7ad0)
Location: mm/khugepaged.c:1426
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff813c7ad0-ffffffff813c7e87: collapse_pte_mapped_thp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int collapse_pte_mapped_thp(struct mm_struct *mm, long unsigned int addr, bool install_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8144bab0)
Location: mm/khugepaged.c:1438
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/khugepaged.c:madvise_collapse
```
**Symbols:**

```
ffffffff8144bab0-ffffffff8144c060: collapse_pte_mapped_thp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int collapse_pte_mapped_thp(struct mm_struct *mm, long unsigned int addr, bool install_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81481350)
Location: mm/khugepaged.c:1561
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/khugepaged.c:madvise_collapse
```
**Symbols:**

```
ffffffff81481350-ffffffff81481873: collapse_pte_mapped_thp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int collapse_pte_mapped_thp(struct mm_struct *mm, long unsigned int addr, bool install_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff814b03a0)
Location: mm/khugepaged.c:1476
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/khugepaged.c:madvise_collapse
```
**Symbols:**

```
ffffffff814b03a0-ffffffff814b0c84: collapse_pte_mapped_thp (STB_GLOBAL)
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
void collapse_pte_mapped_thp(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffff80001035f3d8)
Location: mm/khugepaged.c:1290
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffff80001035f3d8-ffff80001035f750: collapse_pte_mapped_thp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: include/linux/khugepaged.h:84
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void collapse_pte_mapped_thp(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (c00000000044a010)
Location: mm/khugepaged.c:1290
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
c00000000044a010-c00000000044a678: collapse_pte_mapped_thp (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void collapse_pte_mapped_thp(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b6350)
Location: mm/khugepaged.c:1290
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff812b6350-ffffffff812b66d3: collapse_pte_mapped_thp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void collapse_pte_mapped_thp(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812a7540)
Location: mm/khugepaged.c:1290
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff812a7540-ffffffff812a78a8: collapse_pte_mapped_thp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void collapse_pte_mapped_thp(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b4160)
Location: mm/khugepaged.c:1290
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
**Symbols:**

```
ffffffff812b4160-ffffffff812b44e3: collapse_pte_mapped_thp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void collapse_pte_mapped_thp(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812c4630)
Location: mm/khugepaged.c:1290
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/khugepaged.c:khugepaged
```
**Symbols:**

```
ffffffff812c4630-ffffffff812c49ae: collapse_pte_mapped_thp (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool install_pmd</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
