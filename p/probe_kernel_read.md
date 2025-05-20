# Function: <code>probe_kernel_read</code>

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
  - arch/x86/kernel/dumpstack_64.c:show_regs
  - arch/x86/kernel/dumpstack_64.c:show_regs
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:romsignature
  - arch/x86/kernel/probe_roms.c:romchecksum
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/ftrace.c:add_break
  - arch/x86/kernel/ftrace.c:addr_from_call
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/kthread.c:probe_kthread_data
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/trace/trace_kprobe.c:fetch_symbol_u8
  - kernel/trace/trace_kprobe.c:fetch_symbol_u16
  - kernel/trace/trace_kprobe.c:fetch_symbol_u32
  - kernel/trace/trace_kprobe.c:fetch_symbol_u64
```
**Symbols:**

```
ffffffff81191500-ffffffff81191590: probe_kernel_read (STB_WEAK)
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
  - arch/x86/xen/enlighten.c:set_aliased_prot
  - arch/x86/kernel/dumpstack_64.c:show_regs
  - arch/x86/kernel/dumpstack_64.c:show_regs
  - arch/x86/kernel/dumpstack_64.c:show_stack_log_lvl
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:romchecksum
  - arch/x86/kernel/probe_roms.c:romsignature
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/ftrace.c:addr_from_call
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:add_break
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - kernel/exit.c:task_rcu_dereference
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/kthread.c:probe_kthread_data
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/trace/trace_kprobe.c:fetch_symbol_u64
  - kernel/trace/trace_kprobe.c:fetch_symbol_u32
  - kernel/trace/trace_kprobe.c:fetch_symbol_u16
  - kernel/trace/trace_kprobe.c:fetch_symbol_u8
```
**Symbols:**

```
ffffffff811a5cc0-ffffffff811a5d75: probe_kernel_read (STB_WEAK)
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
  - arch/x86/xen/enlighten.c:set_aliased_prot
  - arch/x86/kernel/dumpstack_64.c:show_regs
  - arch/x86/kernel/dumpstack_64.c:show_regs
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:romchecksum
  - arch/x86/kernel/probe_roms.c:romsignature
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/ftrace.c:addr_from_call
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:add_break
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - kernel/exit.c:task_rcu_dereference
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/kthread.c:kthread_probe_data
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/trace/trace_kprobe.c:fetch_symbol_u64
  - kernel/trace/trace_kprobe.c:fetch_symbol_u32
  - kernel/trace/trace_kprobe.c:fetch_symbol_u16
  - kernel/trace/trace_kprobe.c:fetch_symbol_u8
```
**Symbols:**

```
ffffffff811b6040-ffffffff811b60f5: probe_kernel_read (STB_WEAK)
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
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/kernel/traps.c:is_valid_bugaddr
  - arch/x86/kernel/dumpstack_64.c:show_regs
  - arch/x86/kernel/dumpstack_64.c:show_regs
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:romchecksum
  - arch/x86/kernel/probe_roms.c:romsignature
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/ftrace.c:addr_from_call
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:add_break
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
  - arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - kernel/exit.c:task_rcu_dereference
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/kthread.c:kthread_probe_data
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/trace/trace_kprobe.c:fetch_symbol_u64
  - kernel/trace/trace_kprobe.c:fetch_symbol_u32
  - kernel/trace/trace_kprobe.c:fetch_symbol_u16
  - kernel/trace/trace_kprobe.c:fetch_symbol_u8
```
**Symbols:**

```
ffffffff811bdfc0-ffffffff811be041: probe_kernel_read (STB_WEAK)
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
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/kernel/traps.c:is_valid_bugaddr
  - arch/x86/kernel/dumpstack_64.c:show_regs
  - arch/x86/kernel/dumpstack_64.c:show_regs
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:romchecksum
  - arch/x86/kernel/probe_roms.c:romsignature
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/ftrace.c:addr_from_call
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:add_break
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
  - arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - kernel/exit.c:task_rcu_dereference
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/kthread.c:kthread_probe_data
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/trace/trace_kprobe.c:fetch_symbol_u64
  - kernel/trace/trace_kprobe.c:fetch_symbol_u32
  - kernel/trace/trace_kprobe.c:fetch_symbol_u16
  - kernel/trace/trace_kprobe.c:fetch_symbol_u8
  - fs/proc/kcore.c:read_kcore
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff811d2c80-ffffffff811d2d05: probe_kernel_read (STB_WEAK)
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
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/kernel/traps.c:is_valid_bugaddr
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:romchecksum
  - arch/x86/kernel/probe_roms.c:romsignature
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/ftrace.c:addr_from_call
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:add_break
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
  - arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - kernel/exit.c:task_rcu_dereference
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/kthread.c:kthread_probe_data
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/trace/trace_kprobe.c:fetch_symbol_u64
  - kernel/trace/trace_kprobe.c:fetch_symbol_u32
  - kernel/trace/trace_kprobe.c:fetch_symbol_u16
  - kernel/trace/trace_kprobe.c:fetch_symbol_u8
  - fs/proc/kcore.c:read_kcore
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff811f4000-ffffffff811f4085: probe_kernel_read (STB_WEAK)
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
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/kernel/traps.c:is_valid_bugaddr
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:romchecksum
  - arch/x86/kernel/probe_roms.c:romsignature
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/ftrace.c:addr_from_call
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:add_break
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
  - arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/mm/fault.c:show_ldttss
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - kernel/exit.c:task_rcu_dereference
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/kthread.c:kthread_probe_data
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - fs/proc/kcore.c:read_kcore
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff81206390-ffffffff81206415: probe_kernel_read (STB_WEAK)
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
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/kernel/traps.c:is_valid_bugaddr
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:romchecksum
  - arch/x86/kernel/probe_roms.c:romsignature
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/ftrace.c:addr_from_call
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:add_break
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
  - arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/mm/fault.c:show_ldttss
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - kernel/exit.c:task_rcu_dereference
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/kthread.c:kthread_probe_data
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - fs/proc/kcore.c:read_kcore
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff8121d7a0-ffffffff8121d825: probe_kernel_read (STB_WEAK)
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
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/kernel/traps.c:is_valid_bugaddr
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:romchecksum
  - arch/x86/kernel/probe_roms.c:romsignature
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/ftrace.c:addr_from_call
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:add_break
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
  - arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/mm/fault.c:show_ldttss
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/kthread.c:kthread_probe_data
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - fs/proc/kcore.c:read_kcore
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff8122b240-ffffffff8122b2c5: probe_kernel_read (STB_WEAK)
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
  - arch/arm64/kernel/traps.c:call_undef_hook
  - arch/arm64/kernel/insn.c:aarch64_insn_read
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/kthread.c:kthread_probe_data
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - fs/proc/kcore.c:read_kcore
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffff8000102b93e8-ffff8000102b95c4: probe_kernel_read (STB_WEAK)
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
  - arch/arm/kernel/traps.c:is_valid_bugaddr
  - arch/arm/kernel/ftrace.c:ftrace_modify_code
  - arch/arm/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/arm/mm/alignment.c:do_alignment
  - arch/arm/mm/alignment.c:alignment_get_thumb
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/kthread.c:kthread_probe_data
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
c04e5e04-c04e5ec8: probe_kernel_read (STB_WEAK)
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
  - arch/powerpc/kernel/process.c:show_regs
  - arch/powerpc/kernel/process.c:show_user_instructions
  - arch/powerpc/kernel/module_64.c:module_trampoline_target
  - arch/powerpc/kernel/module_64.c:module_trampoline_target
  - arch/powerpc/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_modify_call
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_make_call
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_make_call
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_make_nop
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_make_nop
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_make_nop
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_make_nop
  - arch/powerpc/kernel/trace/ftrace.c:ftrace_modify_code
  - arch/powerpc/perf/core-book3s.c:record_and_restart
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/kthread.c:kthread_probe_data
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - fs/proc/kcore.c:read_kcore
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
c000000000371b90-c000000000371ce8: probe_kernel_read (STB_WEAK)
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
  - arch/riscv/kernel/traps.c:is_valid_bugaddr
  - arch/riscv/kernel/traps.c:do_trap_break
  - arch/riscv/kernel/ftrace.c:ftrace_check_current_call
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/kthread.c:kthread_probe_data
  - fs/proc/kcore.c:read_kcore
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffe0001dcf58-ffffffe0001dcfd8: probe_kernel_read (STB_WEAK)
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
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/kernel/traps.c:is_valid_bugaddr
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:romchecksum
  - arch/x86/kernel/probe_roms.c:romsignature
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/ftrace.c:addr_from_call
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:add_break
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
  - arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/mm/fault.c:show_ldttss
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/kthread.c:kthread_probe_data
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - fs/proc/kcore.c:read_kcore
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff81223890-ffffffff81223915: probe_kernel_read (STB_WEAK)
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
  - arch/x86/kernel/traps.c:is_valid_bugaddr
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:romchecksum
  - arch/x86/kernel/probe_roms.c:romsignature
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/ftrace.c:addr_from_call
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:add_break
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
  - arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/mm/fault.c:show_ldttss
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/kthread.c:kthread_probe_data
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - fs/proc/kcore.c:read_kcore
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff81216a40-ffffffff81216ac5: probe_kernel_read (STB_WEAK)
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
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/kernel/traps.c:is_valid_bugaddr
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:romchecksum
  - arch/x86/kernel/probe_roms.c:romsignature
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/ftrace.c:addr_from_call
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:add_break
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
  - arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/mm/fault.c:show_ldttss
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/kthread.c:kthread_probe_data
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - fs/proc/kcore.c:read_kcore
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff81221630-ffffffff812216b5: probe_kernel_read (STB_WEAK)
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
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/kernel/traps.c:is_valid_bugaddr
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:romchecksum
  - arch/x86/kernel/probe_roms.c:romsignature
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/ftrace.c:addr_from_call
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:add_break
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
  - arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/mm/fault.c:show_ldttss
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/workqueue.c:print_worker_info
  - kernel/kthread.c:kthread_probe_data
  - kernel/debug/gdbstub.c:kgdb_mem2hex
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - fs/proc/kcore.c:read_kcore
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff812307f0-ffffffff81230875: probe_kernel_read (STB_WEAK)
```
</details>
</li>
</ul>

## Differences
