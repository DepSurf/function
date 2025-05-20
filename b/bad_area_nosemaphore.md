# Function: <code>bad_area_nosemaphore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106b180)
Location: arch/x86/mm/fault.c:819
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8106b180-ffffffff8106b195: bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106aec0)
Location: arch/x86/mm/fault.c:885
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
**Symbols:**

```
ffffffff8106aec0-ffffffff8106aed6: bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106ead0)
Location: arch/x86/mm/fault.c:916
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
**Symbols:**

```
ffffffff8106ead0-ffffffff8106eae6: bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106e250)
Location: arch/x86/mm/fault.c:957
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
**Symbols:**

```
ffffffff8106e250-ffffffff8106e266: bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 *pkey);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81073290)
Location: arch/x86/mm/fault.c:932
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
**Symbols:**

```
ffffffff81073290-ffffffff810732a6: bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address, u32 *pkey);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81075c10)
Location: arch/x86/mm/fault.c:904
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
**Symbols:**

```
ffffffff81075c10-ffffffff81075c26: bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107ba30)
Location: arch/x86/mm/fault.c:951
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
**Symbols:**

```
ffffffff8107ba30-ffffffff8107ba48: bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107f530)
Location: arch/x86/mm/fault.c:916
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
**Symbols:**

```
ffffffff8107f530-ffffffff8107f548: bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810805c0)
Location: arch/x86/mm/fault.c:938
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
**Symbols:**

```
ffffffff810805c0-ffffffff810805d8: bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810875f0)
Location: arch/x86/mm/fault.c:904
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_kern_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
**Symbols:**

```
ffffffff810875f0-ffffffff81087608: bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81087ce0)
Location: arch/x86/mm/fault.c:850
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
**Symbols:**

```
ffffffff81087ce0-ffffffff81087cf8: bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81088890)
Location: arch/x86/mm/fault.c:846
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81088890-ffffffff810888a8: bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81097cc0)
Location: arch/x86/mm/fault.c:852
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff81097cc0-ffffffff81097cd8: bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810aa8a0)
Location: arch/x86/mm/fault.c:852
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff810aa8a0-ffffffff810aa8c7: bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810c4490)
Location: arch/x86/mm/fault.c:883
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff810c4490-ffffffff810c44b7: bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810c7cd0)
Location: arch/x86/mm/fault.c:863
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff810c7cd0-ffffffff810c7cf7: bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810d01a0)
Location: arch/x86/mm/fault.c:854
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
**Symbols:**

```
ffffffff810d01a0-ffffffff810d01c7: bad_area_nosemaphore (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bad_area_nosemaphore(struct pt_regs *regs, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/fault.c (c000000000085ed0)
Location: arch/powerpc/mm/fault.c:98
Inline: False
Direct callers:
  - arch/powerpc/mm/fault.c:__do_page_fault
```
**Symbols:**

```
c000000000085ed0-c000000000085f38: bad_area_nosemaphore (STB_LOCAL)
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
void bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107f5c0)
Location: arch/x86/mm/fault.c:938
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
**Symbols:**

```
ffffffff8107f5c0-ffffffff8107f5d8: bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106e5a0)
Location: arch/x86/mm/fault.c:938
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
**Symbols:**

```
ffffffff8106e5a0-ffffffff8106e5b8: bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107f570)
Location: arch/x86/mm/fault.c:938
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
**Symbols:**

```
ffffffff8107f570-ffffffff8107f588: bad_area_nosemaphore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bad_area_nosemaphore(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81081660)
Location: arch/x86/mm/fault.c:938
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:mm_fault_error
```
**Symbols:**

```
ffffffff81081660-ffffffff81081678: bad_area_nosemaphore (STB_LOCAL)
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
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int error_code</code>
</li>
<li>
<b>Param reordered. </b>
<code>regs, error_code, address</code> ➡️ <code>regs, address</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
