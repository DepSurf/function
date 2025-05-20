# Function: <code>probe_kernel_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/ftrace.c:ftrace_write
  - arch/x86/kernel/livepatch.c:klp_write_module_reloc
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/debug/gdbstub.c:write_mem_msg
```
**Symbols:**

```
ffffffff81191590-ffffffff8119161b: probe_kernel_write (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_write
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:write_mem_msg
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
**Symbols:**

```
ffffffff811a5d80-ffffffff811a5e36: probe_kernel_write (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_write
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:write_mem_msg
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
**Symbols:**

```
ffffffff811b6100-ffffffff811b61b6: probe_kernel_write (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_write
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:write_mem_msg
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
**Symbols:**

```
ffffffff811be050-ffffffff811be0d2: probe_kernel_write (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_write
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:write_mem_msg
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
**Symbols:**

```
ffffffff811d2d10-ffffffff811d2d96: probe_kernel_write (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_write
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:write_mem_msg
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
**Symbols:**

```
ffffffff811f4090-ffffffff811f4116: probe_kernel_write (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_write
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:write_mem_msg
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
**Symbols:**

```
ffffffff81206420-ffffffff812064a6: probe_kernel_write (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_write
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:write_mem_msg
  - kernel/debug/gdbstub.c:kgdb_hex2mem
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
**Symbols:**

```
ffffffff8121d710-ffffffff8121d796: probe_kernel_write (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_write
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:write_mem_msg
  - kernel/debug/gdbstub.c:kgdb_hex2mem
```
**Symbols:**

```
ffffffff8122b0f0-ffffffff8122b176: probe_kernel_write (STB_WEAK)
```
</details>
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

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/arm64/kernel/insn.c:__aarch64_insn_write
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:write_mem_msg
  - kernel/debug/gdbstub.c:kgdb_hex2mem
```
**Symbols:**

```
ffff8000102b95c8-ffff8000102b979c: probe_kernel_write (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/arm/kernel/ftrace.c:ftrace_modify_code
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:write_mem_msg
  - kernel/debug/gdbstub.c:kgdb_hex2mem
```
**Symbols:**

```
c04e5d40-c04e5e04: probe_kernel_write (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:write_mem_msg
  - kernel/debug/gdbstub.c:kgdb_hex2mem
```
**Symbols:**

```
c000000000371a40-c000000000371b88: probe_kernel_write (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/riscv/kernel/ftrace.c:__ftrace_modify_call
```
**Symbols:**

```
ffffffe0001dd064-ffffffe0001dd0da: probe_kernel_write (STB_WEAK)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_write
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:write_mem_msg
  - kernel/debug/gdbstub.c:kgdb_hex2mem
```
**Symbols:**

```
ffffffff81223740-ffffffff812237c6: probe_kernel_write (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_write
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:write_mem_msg
  - kernel/debug/gdbstub.c:kgdb_hex2mem
```
**Symbols:**

```
ffffffff812168f0-ffffffff81216976: probe_kernel_write (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_write
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:write_mem_msg
  - kernel/debug/gdbstub.c:kgdb_hex2mem
```
**Symbols:**

```
ffffffff812214e0-ffffffff81221566: probe_kernel_write (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:ftrace_write
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:write_mem_msg
  - kernel/debug/gdbstub.c:kgdb_hex2mem
```
**Symbols:**

```
ffffffff812306a0-ffffffff81230726: probe_kernel_write (STB_WEAK)
```
</details>
</li>
</ul>

## Differences
