# Function: <code>arm64_skip_faulting_instruction</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void arm64_skip_faulting_instruction(struct pt_regs *regs, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm64/kernel/traps.c (ffff800010093f18)
Location: arch/arm64/kernel/traps.c:271
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:wfi_handler
  - arch/arm64/kernel/traps.c:cntfrq_read_handler
  - arch/arm64/kernel/traps.c:cntvct_read_handler
  - arch/arm64/kernel/traps.c:ctr_read_handler
  - arch/arm64/kernel/traps.c:user_cache_maint_handler
Direct callers:
  - arch/arm64/kernel/traps.c:wfi_handler
  - arch/arm64/kernel/traps.c:cntfrq_read_handler
  - arch/arm64/kernel/traps.c:cntvct_read_handler
  - arch/arm64/kernel/traps.c:ctr_read_handler
  - arch/arm64/kernel/traps.c:user_cache_maint_handler
  - arch/arm64/kernel/cpufeature.c:do_emulate_mrs
  - arch/arm64/kernel/cpufeature.c:ssbs_emulation_handler
  - arch/arm64/kernel/armv8_deprecated.c:t16_setend_handler
  - arch/arm64/kernel/armv8_deprecated.c:a32_setend_handler
  - arch/arm64/kernel/armv8_deprecated.c:cp15barrier_handler
  - arch/arm64/kernel/armv8_deprecated.c:swp_handler
```
**Symbols:**

```
ffff800010093ee0-ffff800010093f00: arm64_skip_faulting_instruction.part.0 (STB_LOCAL)
ffff800010094e28-ffff800010094e74: arm64_skip_faulting_instruction (STB_GLOBAL)
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
