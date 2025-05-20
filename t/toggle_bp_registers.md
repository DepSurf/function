# Function: <code>toggle_bp_registers</code>

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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void toggle_bp_registers(int reg, enum dbg_active_el el, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/hw_breakpoint.c (ffff8000100a56c8)
Location: arch/arm64/kernel/hw_breakpoint.c:580
Inline: False
Direct callers:
  - arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_thread_switch
  - arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_thread_switch
  - arch/arm64/kernel/hw_breakpoint.c:reinstall_suspended_bps
  - arch/arm64/kernel/hw_breakpoint.c:reinstall_suspended_bps
  - arch/arm64/kernel/hw_breakpoint.c:reinstall_suspended_bps
  - arch/arm64/kernel/hw_breakpoint.c:reinstall_suspended_bps
  - arch/arm64/kernel/hw_breakpoint.c:reinstall_suspended_bps
  - arch/arm64/kernel/hw_breakpoint.c:watchpoint_handler
  - arch/arm64/kernel/hw_breakpoint.c:watchpoint_handler
  - arch/arm64/kernel/hw_breakpoint.c:watchpoint_handler
  - arch/arm64/kernel/hw_breakpoint.c:breakpoint_handler
  - arch/arm64/kernel/hw_breakpoint.c:breakpoint_handler
```
**Symbols:**

```
ffff8000100a56c8-ffff8000100a57e8: toggle_bp_registers (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
