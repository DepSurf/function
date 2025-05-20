# Function: <code>mm_fault_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mm_fault_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, unsigned int fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106b240)
Location: arch/x86/mm/fault.c:886
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8106b240-ffffffff8106b39f: mm_fault_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mm_fault_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma, unsigned int fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106b020)
Location: arch/x86/mm/fault.c:977
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8106b020-ffffffff8106b1af: mm_fault_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mm_fault_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma, unsigned int fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106ec30)
Location: arch/x86/mm/fault.c:1008
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8106ec30-ffffffff8106edba: mm_fault_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mm_fault_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma, unsigned int fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106e3b0)
Location: arch/x86/mm/fault.c:1049
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8106e3b0-ffffffff8106e52c: mm_fault_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mm_fault_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 *pkey, unsigned int fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81073450)
Location: arch/x86/mm/fault.c:1029
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff81073450-ffffffff810735cc: mm_fault_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void mm_fault_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 *pkey, unsigned int fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1001
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff81075dd0-ffffffff81075f1e: mm_fault_error (STB_LOCAL)
ffffffff810765c9-ffffffff810765f7: mm_fault_error.cold.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void mm_fault_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1069
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8107bc40-ffffffff8107bd8f: mm_fault_error (STB_LOCAL)
ffffffff8107cbe7-ffffffff8107cc48: mm_fault_error.cold.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void mm_fault_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1033
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff8107f6b0-ffffffff8107f7fd: mm_fault_error (STB_LOCAL)
ffffffff81080476-ffffffff810804d1: mm_fault_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void mm_fault_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1055
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81080740-ffffffff8108088d: mm_fault_error (STB_LOCAL)
ffffffff81081520-ffffffff8108157b: mm_fault_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void mm_fault_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1021
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81087770-ffffffff8108786f: mm_fault_error (STB_LOCAL)
ffffffff8108848d-ffffffff810884f1: mm_fault_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void mm_fault_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:972
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81087e50-ffffffff81087fcd: mm_fault_error (STB_LOCAL)
ffffffff81bd9671-ffffffff81bd96cc: mm_fault_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/fault.c (c000000000086a10)
Location: arch/powerpc/mm/fault.c:170
Inline: True
Inline callers:
  - arch/powerpc/mm/fault.c:__do_page_fault
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void mm_fault_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1055
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff8107f740-ffffffff8107f88d: mm_fault_error (STB_LOCAL)
ffffffff81080520-ffffffff8108057b: mm_fault_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void mm_fault_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1055
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff8106e7b0-ffffffff8106e8fd: mm_fault_error (STB_LOCAL)
ffffffff8106f46c-ffffffff8106f4c7: mm_fault_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void mm_fault_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1055
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff8107f6f0-ffffffff8107f83d: mm_fault_error (STB_LOCAL)
ffffffff810804d0-ffffffff8108052b: mm_fault_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void mm_fault_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, vm_fault_t fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:1055
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff810817e0-ffffffff8108192d: mm_fault_error (STB_LOCAL)
ffffffff810825f0-ffffffff8108264b: mm_fault_error.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>regs, error_code, address, fault</code> ➡️ <code>regs, error_code, address, vma, fault</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 *pkey</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 *pkey</code>
</li>
<li>
<b>Param reordered. </b>
<code>regs, error_code, address, pkey, fault</code> ➡️ <code>regs, error_code, address, fault</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int fault</code> ➡️ <code>vm_fault_t fault</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
