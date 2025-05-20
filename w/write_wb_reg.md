# Function: <code>write_wb_reg</code>

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
void write_wb_reg(int reg, int n, u64 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/hw_breakpoint.c (ffff8000100a5400)
Location: arch/arm64/kernel/hw_breakpoint.c:122
Inline: False
Direct callers:
  - arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_reset
  - arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_reset
  - arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_reset
  - arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_reset
  - arch/arm64/kernel/hw_breakpoint.c:toggle_bp_registers
  - arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_control
  - arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_control
  - arch/arm64/kernel/hw_breakpoint.c:hw_breakpoint_control
```
**Symbols:**

```
ffff8000100a5400-ffff8000100a566c: write_wb_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void write_wb_reg(int n, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/hw_breakpoint.c (c031601c)
Location: arch/arm/kernel/hw_breakpoint.c:111
Inline: False
Direct callers:
  - arch/arm/kernel/hw_breakpoint.c:arch_hw_breakpoint_init
  - arch/arm/kernel/hw_breakpoint.c:arch_hw_breakpoint_init
  - arch/arm/kernel/hw_breakpoint.c:reset_ctrl_regs
  - arch/arm/kernel/hw_breakpoint.c:reset_ctrl_regs
  - arch/arm/kernel/hw_breakpoint.c:reset_ctrl_regs
  - arch/arm/kernel/hw_breakpoint.c:reset_ctrl_regs
  - arch/arm/kernel/hw_breakpoint.c:arch_uninstall_hw_breakpoint
  - arch/arm/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
  - arch/arm/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
```
**Symbols:**

```
c031601c-c0316358: write_wb_reg (STB_LOCAL)
```
</details>
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
