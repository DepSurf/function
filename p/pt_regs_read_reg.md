# Function: <code>pt_regs_read_reg</code>

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
In arch/arm64/kernel/traps.c (ffff800010095214)
Location: arch/arm64/include/asm/ptrace.h:278
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:user_cache_maint_handler
```
```
In arch/arm64/kernel/probes/simulate-insn.c (ffff800010da8e7c)
Location: arch/arm64/include/asm/ptrace.h:278
Inline: True
Inline callers:
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_tbz_tbnz
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_tbz_tbnz
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_cbz_cbnz
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_cbz_cbnz
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_cbz_cbnz
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_cbz_cbnz
  - arch/arm64/kernel/probes/simulate-insn.c:simulate_br_blr_ret
```
```
In kernel/trace/trace_kprobe.c (ffff80001024f1f8)
Location: arch/arm64/include/asm/ptrace.h:278
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
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
