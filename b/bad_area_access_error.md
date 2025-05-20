# Function: <code>bad_area_access_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bad_area_access_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106b1f0)
Location: arch/x86/mm/fault.c:847
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8106b1f0-ffffffff8106b23a: bad_area_access_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bad_area_access_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106af30)
Location: arch/x86/mm/fault.c:930
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8106af30-ffffffff8106b018: bad_area_access_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bad_area_access_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106eb40)
Location: arch/x86/mm/fault.c:961
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8106eb40-ffffffff8106ec28: bad_area_access_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bad_area_access_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106e2c0)
Location: arch/x86/mm/fault.c:1002
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8106e2c0-ffffffff8106e3aa: bad_area_access_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bad_area_access_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81073350)
Location: arch/x86/mm/fault.c:982
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff81073350-ffffffff810733f8: bad_area_access_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bad_area_access_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81075cd0)
Location: arch/x86/mm/fault.c:954
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff81075cd0-ffffffff81075d78: bad_area_access_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bad_area_access_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107bb30)
Location: arch/x86/mm/fault.c:995
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8107bb30-ffffffff8107bc38: bad_area_access_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bad_area_access_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107f5a0)
Location: arch/x86/mm/fault.c:960
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff8107f5a0-ffffffff8107f6a4: bad_area_access_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bad_area_access_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81080630)
Location: arch/x86/mm/fault.c:982
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81080630-ffffffff81080734: bad_area_access_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bad_area_access_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81087660)
Location: arch/x86/mm/fault.c:948
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81087660-ffffffff81087764: bad_area_access_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bad_area_access_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81087da0)
Location: arch/x86/mm/fault.c:894
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81087da0-ffffffff81087e4c: bad_area_access_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bad_area_access_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81088950)
Location: arch/x86/mm/fault.c:890
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81088950-ffffffff810889f6: bad_area_access_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bad_area_access_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81097d80)
Location: arch/x86/mm/fault.c:896
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81097d80-ffffffff81097e21: bad_area_access_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bad_area_access_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810aa990)
Location: arch/x86/mm/fault.c:896
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff810aa990-ffffffff810aaa60: bad_area_access_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bad_area_access_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810c4660)
Location: arch/x86/mm/fault.c:927
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff810c4660-ffffffff810c4730: bad_area_access_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bad_area_access_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810c7e60)
Location: arch/x86/mm/fault.c:901
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff810c7e60-ffffffff810c7f30: bad_area_access_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bad_area_access_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810d0330)
Location: arch/x86/mm/fault.c:892
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff810d0330-ffffffff810d0400: bad_area_access_error (STB_LOCAL)
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
void bad_area_access_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107f630)
Location: arch/x86/mm/fault.c:982
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff8107f630-ffffffff8107f734: bad_area_access_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bad_area_access_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106e6a0)
Location: arch/x86/mm/fault.c:982
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff8106e6a0-ffffffff8106e7a4: bad_area_access_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bad_area_access_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107f5e0)
Location: arch/x86/mm/fault.c:982
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff8107f5e0-ffffffff8107f6e4: bad_area_access_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bad_area_access_error(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810816d0)
Location: arch/x86/mm/fault.c:982
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff810816d0-ffffffff810817d4: bad_area_access_error (STB_LOCAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
