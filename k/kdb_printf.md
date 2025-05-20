# Function: <code>kdb_printf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff811328a0)
Location: kernel/debug/kdb/kdb_io.c:863
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig_info
  - kernel/signal.c:kdb_send_sig_info
  - kernel/signal.c:kdb_send_sig_info
  - kernel/signal.c:kdb_send_sig_info
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_task_state_string
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
```
**Symbols:**

```
ffffffff811328a0-ffffffff81132914: kdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8113aca0)
Location: kernel/debug/kdb/kdb_io.c:863
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig_info
  - kernel/signal.c:kdb_send_sig_info
  - kernel/signal.c:kdb_send_sig_info
  - kernel/signal.c:kdb_send_sig_info
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_task_state_string
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
```
**Symbols:**

```
ffffffff8113aca0-ffffffff8113ad14: kdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81144a50)
Location: kernel/debug/kdb/kdb_io.c:852
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig_info
  - kernel/signal.c:kdb_send_sig_info
  - kernel/signal.c:kdb_send_sig_info
  - kernel/signal.c:kdb_send_sig_info
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_task_state_string
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
```
**Symbols:**

```
ffffffff81144a50-ffffffff81144ac4: kdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81146690)
Location: kernel/debug/kdb/kdb_io.c:852
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig_info
  - kernel/signal.c:kdb_send_sig_info
  - kernel/signal.c:kdb_send_sig_info
  - kernel/signal.c:kdb_send_sig_info
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_task_state_string
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
```
**Symbols:**

```
ffffffff81146690-ffffffff81146703: kdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81152fc0)
Location: kernel/debug/kdb/kdb_io.c:852
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig_info
  - kernel/signal.c:kdb_send_sig_info
  - kernel/signal.c:kdb_send_sig_info
  - kernel/signal.c:kdb_send_sig_info
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_task_state_string
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
```
**Symbols:**

```
ffffffff81152fc0-ffffffff81153033: kdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81161b10)
Location: kernel/debug/kdb/kdb_io.c:852
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_task_state_string
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
```
**Symbols:**

```
ffffffff81161b10-ffffffff81161b84: kdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8116e940)
Location: kernel/debug/kdb/kdb_io.c:855
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_task_state_string
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
```
**Symbols:**

```
ffffffff8116e940-ffffffff8116e9b4: kdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8117b740)
Location: kernel/debug/kdb/kdb_io.c:855
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_task_state_string
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
```
**Symbols:**

```
ffffffff8117b740-ffffffff8117b7b4: kdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff811875d0)
Location: kernel/debug/kdb/kdb_io.c:855
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/debug/debug_core.c:kgdb_panic
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_task_state_string
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
```
**Symbols:**

```
ffffffff811875d0-ffffffff81187644: kdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8119bc90)
Location: kernel/debug/kdb/kdb_io.c:855
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/debug/debug_core.c:kgdb_panic
  - kernel/debug/debug_core.c:kdb_dump_stack_on_cpu
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kgdb_transition_check
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_task_state_string
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
```
**Symbols:**

```
ffffffff8119bc90-ffffffff8119bd04: kdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81198db0)
Location: kernel/debug/kdb/kdb_io.c:859
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/debug/debug_core.c:kgdb_panic
  - kernel/debug/debug_core.c:kdb_dump_stack_on_cpu
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kgdb_transition_check
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_task_state_string
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
```
**Symbols:**

```
ffffffff81198db0-ffffffff81198e24: kdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81199c00)
Location: kernel/debug/kdb/kdb_io.c:859
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/debug/debug_core.c:kgdb_panic
  - kernel/debug/debug_core.c:kdb_dump_stack_on_cpu
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:kdb_task_state_string
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
```
**Symbols:**

```
ffffffff81199c00-ffffffff81199c74: kdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff811c3a70)
Location: kernel/debug/kdb/kdb_io.c:859
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/debug/debug_core.c:kgdb_panic
  - kernel/debug/debug_core.c:kdb_dump_stack_on_cpu
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
```
**Symbols:**

```
ffffffff811c3a70-ffffffff811c3ae4: kdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff811f72a0)
Location: kernel/debug/kdb/kdb_io.c:858
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/debug/debug_core.c:kgdb_panic
  - kernel/debug/debug_core.c:kdb_dump_stack_on_cpu
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
```
**Symbols:**

```
ffffffff811f72a0-ffffffff811f732e: kdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8123e5f0)
Location: kernel/debug/kdb/kdb_io.c:872
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/debug/debug_core.c:kgdb_panic
  - kernel/debug/debug_core.c:kdb_dump_stack_on_cpu
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
```
**Symbols:**

```
ffffffff8123e5f0-ffffffff8123e67e: kdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81255650)
Location: kernel/debug/kdb/kdb_io.c:886
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/debug/debug_core.c:kgdb_panic
  - kernel/debug/debug_core.c:kdb_dump_stack_on_cpu
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kgdb_transition_check
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
```
**Symbols:**

```
ffffffff81255650-ffffffff812556de: kdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8126f4d0)
Location: kernel/debug/kdb/kdb_io.c:888
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/module/kdb.c:kdb_lsmod
  - kernel/debug/debug_core.c:kgdb_panic
  - kernel/debug/debug_core.c:kdb_dump_stack_on_cpu
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kgdb_transition_check
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_cpu_status
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_rd
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:parse_grep
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bt.c:kdb_bt1
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_one_knock
```
**Symbols:**

```
ffffffff8126f4d0-ffffffff8126f55e: kdb_printf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffff8000101fd6c0)
Location: kernel/debug/kdb/kdb_io.c:855
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/debug/debug_core.c:kgdb_panic
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_print_state
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_task_state_string
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
```
**Symbols:**

```
ffff8000101fd6c0-ffff8000101fd750: kdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (c043d7d0)
Location: kernel/debug/kdb/kdb_io.c:855
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/debug/debug_core.c:kgdb_panic
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_print_state
  - kernel/debug/kdb/kdb_main.c:kdb_reboot
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_task_state_string
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
```
**Symbols:**

```
c043d7d0-c043d838: kdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (c000000000276080)
Location: kernel/debug/kdb/kdb_io.c:855
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/debug/debug_core.c:kgdb_panic
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_print_state
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_task_state_string
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
```
**Symbols:**

```
c000000000276080-c0000000002760dc: kdb_printf (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8117fbf0)
Location: kernel/debug/kdb/kdb_io.c:855
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/debug/debug_core.c:kgdb_panic
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_task_state_string
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
```
**Symbols:**

```
ffffffff8117fbf0-ffffffff8117fc64: kdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81172d30)
Location: kernel/debug/kdb/kdb_io.c:855
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/debug/debug_core.c:kgdb_panic
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_task_state_string
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
```
**Symbols:**

```
ffffffff81172d30-ffffffff81172da4: kdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8117d9c0)
Location: kernel/debug/kdb/kdb_io.c:855
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/debug/debug_core.c:kgdb_panic
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_task_state_string
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
```
**Symbols:**

```
ffffffff8117d9c0-ffffffff8117da34: kdb_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kdb_printf(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8118b2e0)
Location: kernel/debug/kdb/kdb_io.c:855
Inline: False
Direct callers:
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/signal.c:kdb_send_sig
  - kernel/debug/debug_core.c:kgdb_panic
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_io.c:kdb_read
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_init
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_register_flags
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_grep_help
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_summary
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_help
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_env
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_lsmod
  - kernel/debug/kdb/kdb_main.c:kdb_rm
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_go
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_md_line
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_parse
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_exec_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/debug/kdb/kdb_main.c:kdb_set
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:debug_kusage
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_print_nameval
  - kernel/debug/kdb/kdb_support.c:kdb_task_state_string
  - kernel/debug/kdb/kdb_support.c:kdb_putword
  - kernel/debug/kdb/kdb_support.c:kdb_getword
  - kernel/debug/kdb/kdb_support.c:kdb_getphysword
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdb_symbol_print
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bc
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_printbp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_remove
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_bp.c:kdb_bp_install
  - kernel/debug/kdb/kdb_keyboard.c:kdb_get_kbd_char
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_poll_knock
```
**Symbols:**

```
ffffffff8118b2e0-ffffffff8118b354: kdb_printf (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
