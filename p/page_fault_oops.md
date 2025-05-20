# Function: <code>page_fault_oops</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void page_fault_oops(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:631
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
**Symbols:**

```
ffffffff81088510-ffffffff8108860e: page_fault_oops (STB_LOCAL)
ffffffff81bcb56c-ffffffff81bcb57d: page_fault_oops.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void page_fault_oops(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:632
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
**Symbols:**

```
ffffffff810978b0-ffffffff81097a18: page_fault_oops (STB_LOCAL)
ffffffff81ca0c3e-ffffffff81ca0c4f: page_fault_oops.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void page_fault_oops(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:632
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
**Symbols:**

```
ffffffff810aa3e0-ffffffff810aa585: page_fault_oops (STB_LOCAL)
ffffffff81e501cc-ffffffff81e501dd: page_fault_oops.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void page_fault_oops(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810c3eb0)
Location: arch/x86/mm/fault.c:653
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
**Symbols:**

```
ffffffff810c3eb0-ffffffff810c405b: page_fault_oops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void page_fault_oops(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810c76f0)
Location: arch/x86/mm/fault.c:633
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
**Symbols:**

```
ffffffff810c76f0-ffffffff810c789b: page_fault_oops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void page_fault_oops(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810cfbc0)
Location: arch/x86/mm/fault.c:633
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
**Symbols:**

```
ffffffff810cfbc0-ffffffff810cfd6b: page_fault_oops (STB_LOCAL)
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
