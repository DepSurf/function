# Function: <code>force_sig_info_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void force_sig_info_fault(int si_signo, int si_code, long unsigned int address, struct task_struct *tsk, int fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106a120)
Location: arch/x86/mm/fault.c:171
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:mm_fault_error
```
**Symbols:**

```
ffffffff8106a120-ffffffff8106a1aa: force_sig_info_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void force_sig_info_fault(int si_signo, int si_code, long unsigned int address, struct task_struct *tsk, struct vm_area_struct *vma, int fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106a060)
Location: arch/x86/mm/fault.c:225
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff8106a060-ffffffff8106a15d: force_sig_info_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void force_sig_info_fault(int si_signo, int si_code, long unsigned int address, struct task_struct *tsk, struct vm_area_struct *vma, int fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106dc00)
Location: arch/x86/mm/fault.c:225
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff8106dc00-ffffffff8106dcfd: force_sig_info_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void force_sig_info_fault(int si_signo, int si_code, long unsigned int address, struct task_struct *tsk, struct vm_area_struct *vma, int fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106d130)
Location: arch/x86/mm/fault.c:226
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff8106d130-ffffffff8106d225: force_sig_info_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void force_sig_info_fault(int si_signo, int si_code, long unsigned int address, struct task_struct *tsk, u32 *pkey, int fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81071e90)
Location: arch/x86/mm/fault.c:206
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff81071e90-ffffffff81071f81: force_sig_info_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void force_sig_info_fault(int si_signo, int si_code, long unsigned int address, struct task_struct *tsk, u32 *pkey, int fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81074c90)
Location: arch/x86/mm/fault.c:206
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff81074c90-ffffffff81074d95: force_sig_info_fault (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
<code>si_signo, si_code, address, tsk, fault</code> ➡️ <code>si_signo, si_code, address, tsk, vma, fault</code>
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
</ul>
