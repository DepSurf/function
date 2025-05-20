# Function: <code>ppc_breakpoint_available</code>

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
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ppc_breakpoint_available();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/powerpc/kernel/process.c (c000000000021574)
Location: arch/powerpc/kernel/process.c:799
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:do_break
Direct callers:
  - arch/powerpc/kernel/ptrace.c:arch_ptrace
  - arch/powerpc/kernel/process.c:do_break
  - arch/powerpc/kernel/hw_breakpoint.c:hw_breakpoint_handler
  - arch/powerpc/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
  - arch/powerpc/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/powerpc/kernel/machine_kexec_64.c:kexec_prepare_cpus_wait
  - arch/powerpc/kernel/machine_kexec_64.c:kexec_smp_down
  - arch/powerpc/xmon/xmon.c:clear_all_bpt
  - arch/powerpc/xmon/xmon.c:bpt_cmds
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
```
**Symbols:**

```
c000000000020520-c000000000020548: ppc_breakpoint_available.part.0 (STB_LOCAL)
c000000000020550-c000000000020578: ppc_breakpoint_available (STB_GLOBAL)
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
