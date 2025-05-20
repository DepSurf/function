# Function: <code>force_sig_fault</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int force_sig_fault(int sig, int code, void *addr, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109fed0)
Location: kernel/signal.c:1486
Inline: False
```
**Symbols:**

```
ffffffff8109fed0-ffffffff8109ff4a: force_sig_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int force_sig_fault(int sig, int code, void *addr, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a8240)
Location: kernel/signal.c:1572
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/ptrace.c:user_single_step_report
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff810a8240-ffffffff810a82ae: force_sig_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int force_sig_fault(int sig, int code, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae7b0)
Location: kernel/signal.c:1674
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/ptrace.c:user_single_step_report
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff810ae7b0-ffffffff810ae829: force_sig_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int force_sig_fault(int sig, int code, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4dc0)
Location: kernel/signal.c:1679
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/ptrace.c:user_single_step_report
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff810b4dc0-ffffffff810b4e39: force_sig_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int force_sig_fault(int sig, int code, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bda50)
Location: kernel/signal.c:1675
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/ptrace.c:user_single_step_report
  - arch/x86/kernel/cpu/intel.c:handle_guest_split_lock
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff810bda50-ffffffff810bdab4: force_sig_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int force_sig_fault(int sig, int code, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8d60)
Location: kernel/signal.c:1676
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:write_ok_or_segv
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/ptrace.c:user_single_step_report
  - arch/x86/kernel/cpu/intel.c:handle_guest_split_lock
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff810b8d60-ffffffff810b8dc4: force_sig_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int force_sig_fault(int sig, int code, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ba350)
Location: kernel/signal.c:1678
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/ptrace.c:user_single_step_report
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - arch/x86/kernel/cpu/intel.c:handle_guest_split_lock
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
**Symbols:**

```
ffffffff810ba350-ffffffff810ba3b4: force_sig_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int force_sig_fault(int sig, int code, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ccbb0)
Location: kernel/signal.c:1721
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/ptrace.c:user_single_step_report
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - arch/x86/kernel/cpu/intel.c:handle_guest_split_lock
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
**Symbols:**

```
ffffffff810ccbb0-ffffffff810ccc16: force_sig_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int force_sig_fault(int sig, int code, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e3ef0)
Location: kernel/signal.c:1722
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/traps.c:handle_xfd_event
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/ptrace.c:user_single_step_report
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - arch/x86/kernel/cpu/intel.c:handle_guest_split_lock
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
**Symbols:**

```
ffffffff810e3ef0-ffffffff810e3f76: force_sig_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int force_sig_fault(int sig, int code, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81104550)
Location: kernel/signal.c:1723
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/traps.c:handle_xfd_event
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/ptrace.c:user_single_step_report
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - arch/x86/kernel/cpu/intel.c:handle_guest_split_lock
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
**Symbols:**

```
ffffffff81104550-ffffffff811045d6: force_sig_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int force_sig_fault(int sig, int code, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811107d0)
Location: kernel/signal.c:1729
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/traps.c:handle_xfd_event
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/ptrace.c:user_single_step_report
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - arch/x86/kernel/cpu/intel.c:handle_guest_split_lock
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
**Symbols:**

```
ffffffff811107d0-ffffffff81110856: force_sig_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int force_sig_fault(int sig, int code, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111a120)
Location: kernel/signal.c:1729
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - arch/x86/kernel/traps.c:handle_xfd_event
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/ptrace.c:user_single_step_report
  - arch/x86/kernel/cpu/intel.c:handle_bus_lock
  - arch/x86/kernel/cpu/intel.c:handle_guest_split_lock
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/kernel/sev.c:user_exc_vmm_communication
  - arch/x86/kernel/cet.c:do_user_cp_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
**Symbols:**

```
ffffffff8111a120-ffffffff8111a1a6: force_sig_fault (STB_GLOBAL)
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
int force_sig_fault(int sig, int code, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010110f50)
Location: kernel/signal.c:1679
Inline: False
Direct callers:
  - arch/arm64/kernel/traps.c:bad_el0_sync
```
**Symbols:**

```
ffff800010110f50-ffff800010110fd0: force_sig_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int force_sig_fault(int sig, int code, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0368748)
Location: kernel/signal.c:1679
Inline: False
Direct callers:
  - arch/arm/kernel/ptrace.c:break_trap
  - arch/arm/mm/alignment.c:do_alignment
```
**Symbols:**

```
c0368748-c03687dc: force_sig_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int force_sig_fault(int sig, int code, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000158830)
Location: kernel/signal.c:1679
Inline: False
Direct callers:
  - arch/powerpc/kernel/process.c:do_break
  - arch/powerpc/kernel/traps.c:_exception
  - arch/powerpc/kernel/traps.c:_exception
  - arch/powerpc/kernel/traps.c:user_single_step_report
  - arch/powerpc/mm/fault.c:__do_page_fault
```
**Symbols:**

```
c000000000158830-c0000000001588bc: force_sig_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int force_sig_fault(int sig, int code, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d09a0)
Location: kernel/signal.c:1679
Inline: False
Direct callers:
  - arch/riscv/kernel/traps.c:do_trap_break
  - arch/riscv/kernel/traps.c:do_trap
```
**Symbols:**

```
ffffffe0000d09a0-ffffffe0000d09dc: force_sig_fault (STB_GLOBAL)
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
int force_sig_fault(int sig, int code, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810af130)
Location: kernel/signal.c:1679
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/ptrace.c:user_single_step_report
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff810af130-ffffffff810af1a9: force_sig_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int force_sig_fault(int sig, int code, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109da80)
Location: kernel/signal.c:1679
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/ptrace.c:user_single_step_report
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff8109da80-ffffffff8109daf9: force_sig_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int force_sig_fault(int sig, int code, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae690)
Location: kernel/signal.c:1679
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/ptrace.c:user_single_step_report
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff810ae690-ffffffff810ae709: force_sig_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int force_sig_fault(int sig, int code, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6900)
Location: kernel/signal.c:1679
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/traps.c:do_trap
  - arch/x86/kernel/ptrace.c:user_single_step_report
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - arch/x86/mm/fault.c:mm_fault_error
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff810b6900-ffffffff810b6979: force_sig_fault (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *t</code>
</li>
</ul>
</details>
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
