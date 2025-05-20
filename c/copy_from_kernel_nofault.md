# Function: <code>copy_from_kernel_nofault</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int copy_from_kernel_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/maccess.c (ffffffff81257ec0)
Location: mm/maccess.c:25
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/kernel/traps.c:get_kernel_gp_address
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
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_verify_code
  - arch/x86/kernel/kprobes/core.c:__recover_probed_insn
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
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_support.c:kdb_task_state
  - kernel/trace/bpf_trace.c:bpf_seq_printf
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat
  - kernel/trace/bpf_trace.c:bpf_probe_read_kernel
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - fs/proc/kcore.c:read_kcore
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff81257ec0-ffffffff81257f69: copy_from_kernel_nofault.part.0 (STB_LOCAL)
ffffffff81258160-ffffffff812581b6: copy_from_kernel_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int copy_from_kernel_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/maccess.c (ffffffff81262830)
Location: mm/maccess.c:25
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/kernel/traps.c:get_kernel_gp_address
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
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/ftrace.c:addr_from_call
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_verify_code
  - arch/x86/kernel/kprobes/core.c:__recover_probed_insn
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/kernel/sev-es.c:vc_decode_insn
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
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_support.c:kdb_task_state
  - kernel/trace/bpf_trace.c:bpf_seq_printf
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat
  - kernel/trace/bpf_trace.c:bpf_probe_read_kernel
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/bpf/btf.c:btf_show_obj_safe
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - fs/proc/kcore.c:read_kcore
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff81262830-ffffffff812628d9: copy_from_kernel_nofault.part.0 (STB_LOCAL)
ffffffff81262990-ffffffff812629e6: copy_from_kernel_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int copy_from_kernel_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81267320)
Location: mm/maccess.c:25
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/kernel/traps.c:get_kernel_gp_address
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
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/ftrace.c:addr_from_call
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_verify_code
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/kernel/sev.c:vc_init_em_ctxt
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
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/trace/ftrace.c:print_ip_ins
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat
  - kernel/trace/bpf_trace.c:bpf_probe_read_kernel
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - fs/proc/kcore.c:read_kcore
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff81267320-ffffffff81267407: copy_from_kernel_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int copy_from_kernel_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff812a3d60)
Location: mm/maccess.c:25
Inline: True
Direct callers:
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/kernel/traps.c:get_kernel_gp_address
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
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/ftrace.c:addr_from_call
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_verify_code
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/kernel/sev.c:vc_init_em_ctxt
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
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/trace/ftrace.c:print_ip_ins
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat
  - kernel/trace/bpf_trace.c:bpf_probe_read_kernel
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - fs/d_path.c:simple_dname
  - fs/proc/kcore.c:read_kcore
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff812a3d60-ffffffff812a3e47: copy_from_kernel_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int copy_from_kernel_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff812fbdc0)
Location: mm/maccess.c:23
Inline: True
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/kernel/traps.c:get_kernel_gp_address
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
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/ftrace.c:addr_from_call
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_verify_code
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/kernel/sev.c:vc_decode_insn
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
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat
  - kernel/trace/bpf_trace.c:bpf_probe_read_kernel
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:check_core_relo
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/btf.c:btf_parse
  - fs/inode.c:dump_mapping
  - fs/inode.c:dump_mapping
  - fs/inode.c:dump_mapping
  - fs/inode.c:dump_mapping
  - fs/inode.c:dump_mapping
  - fs/d_path.c:prepend_copy
  - fs/proc/kcore.c:read_kcore
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff812fbdc0-ffffffff812fbeac: copy_from_kernel_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int copy_from_kernel_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81365fd0)
Location: mm/maccess.c:23
Inline: True
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/ftrace.c:addr_from_call
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_verify_code
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:__recover_probed_insn
  - arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/kernel/sev.c:vc_decode_insn
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
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat
  - kernel/trace/bpf_trace.c:bpf_probe_read_kernel
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:check_core_relo
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/btf.c:btf_parse
  - fs/inode.c:dump_mapping
  - fs/inode.c:dump_mapping
  - fs/inode.c:dump_mapping
  - fs/inode.c:dump_mapping
  - fs/inode.c:dump_mapping
  - fs/d_path.c:prepend_copy
  - fs/proc/kcore.c:read_kcore
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff81365fd0-ffffffff813660bc: copy_from_kernel_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int copy_from_kernel_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81398470)
Location: mm/maccess.c:24
Inline: True
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/ftrace.c:addr_from_call
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_verify_code
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:__recover_probed_insn
  - arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/kernel/sev.c:vc_init_em_ctxt
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
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/bpf_trace.c:bpf_d_path
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat
  - kernel/trace/bpf_trace.c:bpf_probe_read_kernel
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:check_core_relo
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/btf.c:btf_parse
  - fs/inode.c:dump_mapping
  - fs/inode.c:dump_mapping
  - fs/inode.c:dump_mapping
  - fs/inode.c:dump_mapping
  - fs/inode.c:dump_mapping
  - fs/d_path.c:prepend_copy
  - fs/proc/kcore.c:read_kcore_iter
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff81398470-ffffffff8139855c: copy_from_kernel_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int copy_from_kernel_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff813c2270)
Location: mm/maccess.c:24
Inline: True
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:probe_roms
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/probe_roms.c:find_oprom
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
  - arch/x86/kernel/ftrace.c:addr_from_call
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_verify_code
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:__recover_probed_insn
  - arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - arch/x86/kernel/sev.c:vc_init_em_ctxt
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
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/trace/trace.c:trace_check_vprintf
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/bpf_trace.c:bpf_d_path
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat
  - kernel/trace/bpf_trace.c:bpf_probe_read_kernel
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/trace/trace_fprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_delete_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
  - kernel/bpf/verifier.c:check_core_relo
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:__find_kfunc_desc_btf
  - kernel/bpf/helpers.c:bpf_bprintf_prepare
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/btf.c:btf_parse
  - fs/inode.c:dump_mapping
  - fs/inode.c:dump_mapping
  - fs/inode.c:dump_mapping
  - fs/inode.c:dump_mapping
  - fs/inode.c:dump_mapping
  - fs/d_path.c:prepend_copy
  - fs/proc/kcore.c:read_kcore_iter
  - drivers/char/mem.c:read_mem
```
**Symbols:**

```
ffffffff813c2270-ffffffff813c235c: copy_from_kernel_nofault (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
