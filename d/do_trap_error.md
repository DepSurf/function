# Function: <code>do_trap_error</code>

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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void do_trap_error(struct pt_regs *regs, int signo, int code, long unsigned int addr, const char *str);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/traps.c (ffffffe0000b6da6)
Location: arch/riscv/kernel/traps.c:75
Inline: True
Direct callers:
  - arch/riscv/kernel/traps.c:do_trap_ecall_m
  - arch/riscv/kernel/traps.c:do_trap_ecall_s
  - arch/riscv/kernel/traps.c:do_trap_ecall_u
  - arch/riscv/kernel/traps.c:do_trap_store_fault
  - arch/riscv/kernel/traps.c:do_trap_store_misaligned
  - arch/riscv/kernel/traps.c:do_trap_load_fault
  - arch/riscv/kernel/traps.c:do_trap_load_misaligned
  - arch/riscv/kernel/traps.c:do_trap_insn_illegal
  - arch/riscv/kernel/traps.c:do_trap_insn_fault
  - arch/riscv/kernel/traps.c:do_trap_insn_misaligned
  - arch/riscv/kernel/traps.c:do_trap_unknown
```
**Symbols:**

```
ffffffe0000b6da6-ffffffe0000b6e12: do_trap_error (STB_LOCAL)
```
</details>
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
