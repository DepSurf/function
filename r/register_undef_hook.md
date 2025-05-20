# Function: <code>register_undef_hook</code>

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
void register_undef_hook(struct undef_hook *hook);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/traps.c (ffff800010094e78)
Location: arch/arm64/kernel/traps.c:286
Inline: False
Direct callers:
  - arch/arm64/kernel/cpufeature.c:enable_mrs_emulation
  - arch/arm64/kernel/armv8_deprecated.c:update_insn_emulation_mode
```
**Symbols:**

```
ffff800010094e78-ffff800010094f44: register_undef_hook (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void register_undef_hook(struct undef_hook *hook);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/traps.c (c030f920)
Location: arch/arm/kernel/traps.c:401
Inline: False
Direct callers:
  - arch/arm/kernel/ptrace.c:ptrace_break_init
  - arch/arm/kernel/ptrace.c:ptrace_break_init
  - arch/arm/kernel/ptrace.c:ptrace_break_init
  - arch/arm/kernel/kgdb.c:kgdb_arch_init
  - arch/arm/kernel/kgdb.c:kgdb_arch_init
  - arch/arm/kernel/swp_emulate.c:swp_emulation_init
  - arch/arm/kernel/hw_breakpoint.c:arch_hw_breakpoint_init
  - arch/arm/probes/uprobes/core.c:arch_uprobes_init
  - arch/arm/probes/uprobes/core.c:arch_uprobes_init
  - arch/arm/probes/kprobes/core.c:arch_init_kprobes
```
**Symbols:**

```
c030f920-c030f978: register_undef_hook (STB_GLOBAL)
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
