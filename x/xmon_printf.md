# Function: <code>xmon_printf</code>

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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xmon_printf(const char *format, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/xmon/nonstdio.c (c000000000111de0)
Location: arch/powerpc/xmon/nonstdio.c:167
Inline: False
Direct callers:
  - arch/powerpc/sysdev/xive/common.c:xmon_xive_get_irq_config
  - arch/powerpc/sysdev/xive/common.c:xmon_xive_get_irq_config
  - arch/powerpc/sysdev/xive/common.c:xmon_xive_get_irq_config
  - arch/powerpc/sysdev/xive/common.c:xmon_xive_get_irq_config
  - arch/powerpc/sysdev/xive/common.c:xmon_xive_get_irq_config
  - arch/powerpc/sysdev/xive/common.c:xmon_xive_do_dump
  - arch/powerpc/sysdev/xive/common.c:xmon_xive_do_dump
  - arch/powerpc/sysdev/xive/common.c:xmon_xive_do_dump
  - arch/powerpc/sysdev/xive/common.c:xmon_xive_do_dump
  - arch/powerpc/sysdev/xive/common.c:xmon_xive_do_dump
  - arch/powerpc/sysdev/xive/common.c:xmon_xive_do_dump
  - arch/powerpc/xmon/xmon.c:dump_segments
  - arch/powerpc/xmon/xmon.c:dump_segments
  - arch/powerpc/xmon/xmon.c:dump_segments
  - arch/powerpc/xmon/xmon.c:dump_segments
  - arch/powerpc/xmon/xmon.c:xmon_print_symbol
  - arch/powerpc/xmon/xmon.c:xmon_print_symbol
  - arch/powerpc/xmon/xmon.c:xmon_print_symbol
  - arch/powerpc/xmon/xmon.c:xmon_print_symbol
  - arch/powerpc/xmon/xmon.c:symbol_lookup
  - arch/powerpc/xmon/xmon.c:symbol_lookup
  - arch/powerpc/xmon/xmon.c:symbol_lookup
  - arch/powerpc/xmon/xmon.c:symbol_lookup
  - arch/powerpc/xmon/xmon.c:scanhex
  - arch/powerpc/xmon/xmon.c:scanhex
  - arch/powerpc/xmon/xmon.c:scanhex
  - arch/powerpc/xmon/xmon.c:proccall
  - arch/powerpc/xmon/xmon.c:proccall
  - arch/powerpc/xmon/xmon.c:show_tasks
  - arch/powerpc/xmon/xmon.c:show_tasks
  - arch/powerpc/xmon/xmon.c:show_pte
  - arch/powerpc/xmon/xmon.c:show_pte
  - arch/powerpc/xmon/xmon.c:show_pte
  - arch/powerpc/xmon/xmon.c:show_pte
  - arch/powerpc/xmon/xmon.c:show_pte
  - arch/powerpc/xmon/xmon.c:show_pte
  - arch/powerpc/xmon/xmon.c:show_pte
  - arch/powerpc/xmon/xmon.c:show_pte
  - arch/powerpc/xmon/xmon.c:show_pte
  - arch/powerpc/xmon/xmon.c:format_pte
  - arch/powerpc/xmon/xmon.c:format_pte
  - arch/powerpc/xmon/xmon.c:format_pte
  - arch/powerpc/xmon/xmon.c:show_task
  - arch/powerpc/xmon/xmon.c:dump_opal_msglog
  - arch/powerpc/xmon/xmon.c:dump_opal_msglog
  - arch/powerpc/xmon/xmon.c:dump_opal_msglog
  - arch/powerpc/xmon/xmon.c:dump_opal_msglog
  - arch/powerpc/xmon/xmon.c:dump_log_buf
  - arch/powerpc/xmon/xmon.c:dump_log_buf
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump_one_xive
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:dump_one_paca
  - arch/powerpc/xmon/xmon.c:memex
  - arch/powerpc/xmon/xmon.c:memex
  - arch/powerpc/xmon/xmon.c:memex
  - arch/powerpc/xmon/xmon.c:memex
  - arch/powerpc/xmon/xmon.c:memex
  - arch/powerpc/xmon/xmon.c:mwrite
  - arch/powerpc/xmon/xmon.c:mwrite
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:super_regs
  - arch/powerpc/xmon/xmon.c:dump_one_spr
  - arch/powerpc/xmon/xmon.c:dump_one_spr
  - arch/powerpc/xmon/xmon.c:dump_one_spr
  - arch/powerpc/xmon/xmon.c:write_spr
  - arch/powerpc/xmon/xmon.c:write_spr
  - arch/powerpc/xmon/xmon.c:prregs
  - arch/powerpc/xmon/xmon.c:prregs
  - arch/powerpc/xmon/xmon.c:prregs
  - arch/powerpc/xmon/xmon.c:prregs
  - arch/powerpc/xmon/xmon.c:prregs
  - arch/powerpc/xmon/xmon.c:prregs
  - arch/powerpc/xmon/xmon.c:prregs
  - arch/powerpc/xmon/xmon.c:prregs
  - arch/powerpc/xmon/xmon.c:prregs
  - arch/powerpc/xmon/xmon.c:prregs
  - arch/powerpc/xmon/xmon.c:excprint
  - arch/powerpc/xmon/xmon.c:excprint
  - arch/powerpc/xmon/xmon.c:excprint
  - arch/powerpc/xmon/xmon.c:excprint
  - arch/powerpc/xmon/xmon.c:excprint
  - arch/powerpc/xmon/xmon.c:excprint
  - arch/powerpc/xmon/xmon.c:excprint
  - arch/powerpc/xmon/xmon.c:excprint
  - arch/powerpc/xmon/xmon.c:excprint
  - arch/powerpc/xmon/xmon.c:excprint
  - arch/powerpc/xmon/xmon.c:excprint
  - arch/powerpc/xmon/xmon.c:excprint
  - arch/powerpc/xmon/xmon.c:excprint
  - arch/powerpc/xmon/xmon.c:excprint
  - arch/powerpc/xmon/xmon.c:excprint
  - arch/powerpc/xmon/xmon.c:excprint
  - arch/powerpc/xmon/xmon.c:excprint
  - arch/powerpc/xmon/xmon.c:excprint
  - arch/powerpc/xmon/xmon.c:excprint
  - arch/powerpc/xmon/xmon.c:xmon_show_stack
  - arch/powerpc/xmon/xmon.c:xmon_show_stack
  - arch/powerpc/xmon/xmon.c:xmon_show_stack
  - arch/powerpc/xmon/xmon.c:xmon_show_stack
  - arch/powerpc/xmon/xmon.c:xmon_show_stack
  - arch/powerpc/xmon/xmon.c:xmon_show_stack
  - arch/powerpc/xmon/xmon.c:xmon_show_stack
  - arch/powerpc/xmon/xmon.c:bpt_cmds
  - arch/powerpc/xmon/xmon.c:bpt_cmds
  - arch/powerpc/xmon/xmon.c:bpt_cmds
  - arch/powerpc/xmon/xmon.c:bpt_cmds
  - arch/powerpc/xmon/xmon.c:bpt_cmds
  - arch/powerpc/xmon/xmon.c:bpt_cmds
  - arch/powerpc/xmon/xmon.c:bpt_cmds
  - arch/powerpc/xmon/xmon.c:bpt_cmds
  - arch/powerpc/xmon/xmon.c:bpt_cmds
  - arch/powerpc/xmon/xmon.c:bpt_cmds
  - arch/powerpc/xmon/xmon.c:bpt_cmds
  - arch/powerpc/xmon/xmon.c:bpt_cmds
  - arch/powerpc/xmon/xmon.c:bpt_cmds
  - arch/powerpc/xmon/xmon.c:bpt_cmds
  - arch/powerpc/xmon/xmon.c:check_bp_loc
  - arch/powerpc/xmon/xmon.c:check_bp_loc
  - arch/powerpc/xmon/xmon.c:check_bp_loc
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:cmds
  - arch/powerpc/xmon/xmon.c:show_uptime
  - arch/powerpc/xmon/xmon.c:remove_bpts
  - arch/powerpc/xmon/xmon.c:new_breakpoint
  - arch/powerpc/xmon/xmon.c:xmon_irq
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_core
  - arch/powerpc/xmon/xmon.c:xmon_is_locked_down
  - arch/powerpc/xmon/xmon.c:xmon_is_locked_down
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
  - arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc
```
**Symbols:**

```
c000000000111de0-c000000000111e88: xmon_printf (STB_GLOBAL)
```
</details>
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
