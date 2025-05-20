# Function: <code>__set_breakpoint</code>

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
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __set_breakpoint(struct arch_hw_breakpoint *brk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/process.c (c0000000000213f0)
Location: arch/powerpc/kernel/process.c:783
Inline: True
Direct callers:
  - arch/powerpc/kernel/process.c:do_break
  - arch/powerpc/kernel/signal.c:do_notify_resume
  - arch/powerpc/kernel/hw_breakpoint.c:single_step_dabr_instruction
  - arch/powerpc/kernel/hw_breakpoint.c:hw_breakpoint_handler
  - arch/powerpc/kernel/hw_breakpoint.c:hw_breakpoint_handler
  - arch/powerpc/kernel/hw_breakpoint.c:thread_change_pc
  - arch/powerpc/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/powerpc/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/powerpc/kernel/machine_kexec_64.c:kexec_prepare_cpus_wait
  - arch/powerpc/kernel/machine_kexec_64.c:kexec_smp_down
  - arch/powerpc/xmon/xmon.c:clear_all_bpt
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
```
**Symbols:**

```
c0000000000213f0-c0000000000214d0: __set_breakpoint (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
