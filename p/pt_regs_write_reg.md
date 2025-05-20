# Function: <code>pt_regs_write_reg</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/traps.c (ffff8000100941b4)
Location: arch/arm64/include/asm/ptrace.h:287
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:compat_cntvct_read_handler
  - arch/arm64/kernel/traps.c:compat_cntvct_read_handler
  - arch/arm64/kernel/traps.c:compat_cntfrq_read_handler
  - arch/arm64/kernel/traps.c:cntfrq_read_handler
  - arch/arm64/kernel/traps.c:cntvct_read_handler
  - arch/arm64/kernel/traps.c:ctr_read_handler
```
```
In arch/arm64/kernel/cpufeature.c (ffff80001009b040)
Location: arch/arm64/include/asm/ptrace.h:287
Inline: True
Inline callers:
  - arch/arm64/kernel/cpufeature.c:do_emulate_mrs
```
```
In arch/arm64/kernel/probes/simulate-insn.c (ffff800010da8f88)
Location: arch/arm64/include/asm/ptrace.h:287
Inline: True
Inline callers:
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_ldrsw_literal
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_ldr_literal
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_ldr_literal
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_br_blr_ret
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_b_bl
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_adr_adrp
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
