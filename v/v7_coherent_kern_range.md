# Function: <code>v7_coherent_kern_range</code>

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
  - arch/arm/kernel/setup.c:setup_processor
  - arch/arm/kernel/setup.c:setup_processor
  - arch/arm/kernel/signal.c:get_signal_page
  - arch/arm/kernel/signal.c:setup_return
  - arch/arm/kernel/traps.c:early_trap_init
  - arch/arm/kernel/fiq.c:set_fiq_handler
  - arch/arm/kernel/fiq.c:set_fiq_handler
  - arch/arm/kernel/ftrace.c:ftrace_modify_code
  - arch/arm/kernel/machine_kexec.c:machine_kexec
  - arch/arm/kernel/patch.c:__patch_text_real
  - arch/arm/mm/flush.c:copy_to_user_page
  - arch/arm/mm/flush.c:flush_uprobe_xol_access
  - arch/arm/mm/flush.c:flush_icache_alias
  - arch/arm/probes/kprobes/core.c:arch_prepare_kprobe
  - arch/arm/probes/kprobes/opt-arm.c:arch_prepare_optimized_kprobe
  - arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile
  - arch/arm/mach-imx/pm-imx6.c:imx6q_suspend_init
  - arch/arm/plat-omap/sram.c:omap_sram_push
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:hib_end_io
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/debug/debug_core.c:kgdb_flush_swbreak_addr
  - kernel/debug/gdbstub.c:write_mem_msg
  - fs/exec.c:read_code
  - fs/binfmt_flat.c:load_flat_file
  - drivers/misc/sram-exec.c:sram_exec_copy
```
**Symbols:**

```
c0321f78-c0321fec: v7_coherent_kern_range (STB_GLOBAL)
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
