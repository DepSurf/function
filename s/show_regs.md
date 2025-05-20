# Function: <code>show_regs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (ffffffff810315e0)
Location: arch/x86/kernel/dumpstack_64.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/doublefault.c:df_debug
  - kernel/signal.c:get_signal
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/watchdog.c:watchdog_timer_fn
  - lib/bug.c:report_bug
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
**Symbols:**

```
ffffffff810315e0-ffffffff81031781: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (ffffffff81030700)
Location: arch/x86/kernel/dumpstack_64.c:308
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/watchdog.c:watchdog_timer_fn
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
**Symbols:**

```
ffffffff81030700-ffffffff8103089c: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (ffffffff81030370)
Location: arch/x86/kernel/dumpstack_64.c:139
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/watchdog.c:watchdog_timer_fn
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
**Symbols:**

```
ffffffff81030370-ffffffff810304fd: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (ffffffff8102e5c0)
Location: arch/x86/kernel/dumpstack_64.c:140
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff8102e5c0-ffffffff8102e74d: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack_64.c (ffffffff81030460)
Location: arch/x86/kernel/dumpstack_64.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff81030460-ffffffff810305ed: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:417
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:__die
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/kprobes/core.c:longjmp_break_handler
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff81032316-ffffffff81032335: show_regs.cold.11 (STB_LOCAL)
ffffffff81031d70-ffffffff81031db1: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810335db)
Location: arch/x86/kernel/dumpstack.c:408
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:__die
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff810335db-ffffffff810335fa: show_regs.cold.12 (STB_LOCAL)
ffffffff810330e0-ffffffff81033121: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103540b)
Location: arch/x86/kernel/dumpstack.c:408
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:__die
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog_hld.c:watchdog_overflow_callback
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff8103540b-ffffffff8103542a: show_regs.cold (STB_LOCAL)
ffffffff81034f40-ffffffff81034f87: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81035c3b)
Location: arch/x86/kernel/dumpstack.c:413
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:__die
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/mm/extable.c:early_fixup_exception
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state_cpu
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog_hld.c:watchdog_overflow_callback
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff81035c3b-ffffffff81035c5a: show_regs.cold (STB_LOCAL)
ffffffff81035770-ffffffff810357b7: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81037665)
Location: arch/x86/kernel/dumpstack.c:445
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:__die_body
Direct callers:
  - arch/x86/kernel/dumpstack.c:__die_body
  - arch/x86/mm/extable.c:early_fixup_exception
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state_cpu
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/watchdog.c:watchdog_timer_fn
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
**Symbols:**

```
ffffffff81037c94-ffffffff81037cb9: show_regs.part.0 (STB_LOCAL)
ffffffff81037d76-ffffffff81037d83: show_regs.cold (STB_LOCAL)
ffffffff810377a0-ffffffff810377e9: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810386ef)
Location: arch/x86/kernel/dumpstack.c:462
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:__die_body
Direct callers:
  - arch/x86/kernel/dumpstack.c:__die_body
  - arch/x86/kernel/sev-es.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication
  - arch/x86/mm/extable.c:early_fixup_exception
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state_cpu
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/watchdog.c:watchdog_timer_fn
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
**Symbols:**

```
ffffffff81bd3859-ffffffff81bd387e: show_regs.part.0 (STB_LOCAL)
ffffffff81bd393b-ffffffff81bd3948: show_regs.cold (STB_LOCAL)
ffffffff81038820-ffffffff81038870: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103a20f)
Location: arch/x86/kernel/dumpstack.c:462
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:__die_body
Direct callers:
  - arch/x86/kernel/dumpstack.c:__die_body
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
  - arch/x86/mm/extable.c:early_fixup_exception
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state_cpu
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/watchdog.c:watchdog_timer_fn
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
**Symbols:**

```
ffffffff81bc5ccb-ffffffff81bc5cf0: show_regs.part.0 (STB_LOCAL)
ffffffff81bc5dad-ffffffff81bc5dba: show_regs.cold (STB_LOCAL)
ffffffff8103a340-ffffffff8103a390: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103fbbf)
Location: arch/x86/kernel/dumpstack.c:462
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:__die_body
Direct callers:
  - arch/x86/kernel/dumpstack.c:__die_body
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
  - arch/x86/mm/extable.c:early_fixup_exception
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state_cpu
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/kfence/report.c:kfence_report_error
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
**Symbols:**

```
ffffffff81c98a15-ffffffff81c98a3a: show_regs.part.0 (STB_LOCAL)
ffffffff81c98af7-ffffffff81c98b04: show_regs.cold (STB_LOCAL)
ffffffff8103fcf0-ffffffff8103fd40: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8104734e)
Location: arch/x86/kernel/dumpstack.c:456
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:__die_body
Direct callers:
  - arch/x86/kernel/dumpstack.c:__die_body
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
  - arch/x86/mm/extable.c:early_fixup_exception
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state_cpu
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/kfence/report.c:kfence_report_error
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
**Symbols:**

```
ffffffff81e47f9e-ffffffff81e47fcf: show_regs.part.0 (STB_LOCAL)
ffffffff81e480a9-ffffffff81e480b6: show_regs.cold (STB_LOCAL)
ffffffff810474b0-ffffffff81047505: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81051c00)
Location: arch/x86/kernel/dumpstack.c:462
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
  - arch/x86/mm/extable.c:early_fixup_exception
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state_cpu
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/sched/core.c:dump_cpu_task
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/kfence/report.c:kfence_report_error
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff81051c00-ffffffff81051c7f: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81052940)
Location: arch/x86/kernel/dumpstack.c:465
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
  - arch/x86/mm/extable.c:early_fixup_exception
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state_cpu
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/sched/core.c:dump_cpu_task
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_hardlockup_check
  - mm/kfence/report.c:kfence_report_error
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff81052940-ffffffff810529bf: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81059b60)
Location: arch/x86/kernel/dumpstack.c:465
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:kernel_exc_vmm_communication
  - arch/x86/mm/extable.c:early_fixup_exception
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state_cpu
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/sched/core.c:dump_cpu_task
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_hardlockup_check
  - mm/kfence/report.c:kfence_report_error
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff81059b60-ffffffff81059bdf: show_regs (STB_GLOBAL)
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
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/process.c (ffff8000100890f0)
Location: arch/arm64/kernel/process.c:291
Inline: False
Direct callers:
  - arch/arm64/kernel/traps.c:die
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
**Symbols:**

```
ffff8000100890f0-ffff800010089128: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/process.c (c030b220)
Location: arch/arm/kernel/process.c:186
Inline: False
Direct callers:
  - arch/arm/mm/alignment.c:do_alignment_ldmstm
  - kernel/signal.c:get_signal
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
c030b220-c030b240: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/process.c (c000000000023024)
Location: arch/powerpc/kernel/process.c:1388
Inline: False
Direct callers:
  - arch/powerpc/kernel/traps.c:StackOverflow
  - arch/powerpc/kernel/traps.c:__die
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
  - arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending
  - arch/powerpc/kernel/watchdog.c:wd_lockup_ipi
  - arch/powerpc/platforms/powernv/opal.c:pnv_platform_error_reboot
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
c000000000023024-c000000000023400: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/process.c (ffffffe0000b582a)
Location: arch/riscv/kernel/process.c:34
Inline: False
Direct callers:
  - arch/riscv/kernel/traps.c:do_trap
  - arch/riscv/kernel/traps.c:die
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
```
**Symbols:**

```
ffffffe0000b582a-ffffffe0000b5966: show_regs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81035d9b)
Location: arch/x86/kernel/dumpstack.c:413
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:__die
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog_hld.c:watchdog_overflow_callback
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff81035d9b-ffffffff81035dba: show_regs.cold (STB_LOCAL)
ffffffff810358d0-ffffffff81035917: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810256eb)
Location: arch/x86/kernel/dumpstack.c:413
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:__die
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog_hld.c:watchdog_overflow_callback
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff810256eb-ffffffff8102570a: show_regs.cold (STB_LOCAL)
ffffffff81025220-ffffffff81025267: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81035bfb)
Location: arch/x86/kernel/dumpstack.c:413
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:__die
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog_hld.c:watchdog_overflow_callback
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff81035bfb-ffffffff81035c1a: show_regs.cold (STB_LOCAL)
ffffffff81035730-ffffffff81035777: show_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void show_regs(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81036bdb)
Location: arch/x86/kernel/dumpstack.c:413
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:__die
  - arch/x86/kernel/doublefault.c:df_debug
  - arch/x86/mm/extable.c:early_fixup_exception
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state_cpu
  - kernel/panic.c:__warn
  - kernel/signal.c:get_signal
  - kernel/debug/kdb/kdb_main.c:kdb_ef
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog_hld.c:watchdog_overflow_callback
  - drivers/tty/sysrq.c:sysrq_handle_showregs
  - drivers/tty/vt/keyboard.c:fn_show_ptregs
  - lib/nmi_backtrace.c:nmi_cpu_backtrace
```
**Symbols:**

```
ffffffff81036bdb-ffffffff81036bfa: show_regs.cold (STB_LOCAL)
ffffffff81036710-ffffffff81036757: show_regs (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
