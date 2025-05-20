# Function: <code>kallsyms_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8110b2e0)
Location: kernel/kallsyms.c:292
Inline: True
Direct callers:
  - kernel/kallsyms.c:__sprint_symbol
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff8110b2e0-ffffffff8110b3b5: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81112b30)
Location: kernel/kallsyms.c:316
Inline: True
Direct callers:
  - kernel/kallsyms.c:__sprint_symbol
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff81112b30-ffffffff81112c05: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8111a240)
Location: kernel/kallsyms.c:316
Inline: True
Direct callers:
  - kernel/kallsyms.c:__sprint_symbol
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff8111a240-ffffffff8111a315: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8111bd70)
Location: kernel/kallsyms.c:312
Inline: False
Direct callers:
  - kernel/kallsyms.c:__sprint_symbol
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff8111bd70-ffffffff8111be6c: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81127390)
Location: kernel/kallsyms.c:313
Inline: False
Direct callers:
  - kernel/kallsyms.c:__sprint_symbol
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff81127390-ffffffff811274b5: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81135270)
Location: kernel/kallsyms.c:278
Inline: False
Direct callers:
  - kernel/kallsyms.c:__sprint_symbol
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff81135270-ffffffff81135371: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81140790)
Location: kernel/kallsyms.c:278
Inline: False
Direct callers:
  - kernel/kallsyms.c:__sprint_symbol
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff81140790-ffffffff81140890: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114bb80)
Location: kernel/kallsyms.c:281
Inline: False
Direct callers:
  - kernel/kallsyms.c:__sprint_symbol
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff8114bb80-ffffffff8114bc80: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81157850)
Location: kernel/kallsyms.c:281
Inline: False
Direct callers:
  - kernel/kallsyms.c:__sprint_symbol
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff81157850-ffffffff81157950: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811683e0)
Location: kernel/kallsyms.c:280
Inline: False
Direct callers:
  - kernel/kallsyms.c:__sprint_symbol
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/bpf/btf.c:__btf_resolve_helper_id
```
**Symbols:**

```
ffffffff811683e0-ffffffff811684f9: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811649d0)
Location: kernel/kallsyms.c:281
Inline: False
Direct callers:
  - kernel/kallsyms.c:__sprint_symbol
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_output.c:trace_seq_print_sym
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff811649d0-ffffffff81164ae9: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811657a0)
Location: kernel/kallsyms.c:311
Inline: False
Direct callers:
  - kernel/kallsyms.c:__sprint_symbol
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_output.c:trace_seq_print_sym
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff811657a0-ffffffff811658b8: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8118b180)
Location: kernel/kallsyms.c:356
Inline: False
Direct callers:
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_output.c:trace_seq_print_sym
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff8118b180-ffffffff8118b196: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811ba3f0)
Location: kernel/kallsyms.c:380
Inline: False
Direct callers:
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_match_record
  - kernel/trace/ftrace.c:print_rec
  - kernel/trace/ftrace.c:test_for_valid_rec
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_output.c:trace_seq_print_sym
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff811ba3f0-ffffffff811ba418: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811fc0b0)
Location: kernel/kallsyms.c:453
Inline: False
Direct callers:
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_match_record
  - kernel/trace/ftrace.c:print_rec
  - kernel/trace/ftrace.c:test_for_valid_rec
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_output.c:trace_seq_print_sym
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff811fc0b0-ffffffff811fc0d8: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff812118c0)
Location: kernel/kallsyms.c:448
Inline: False
Direct callers:
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_match_record
  - kernel/trace/ftrace.c:print_rec
  - kernel/trace/ftrace.c:test_for_valid_rec
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_output.c:trace_seq_print_sym
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
```
**Symbols:**

```
ffffffff812118c0-ffffffff812118e8: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81228f40)
Location: kernel/kallsyms.c:446
Inline: False
Direct callers:
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_match_record
  - kernel/trace/ftrace.c:print_rec
  - kernel/trace/ftrace.c:test_for_valid_rec
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_output.c:trace_seq_print_sym
  - kernel/trace/trace_syscalls.c:find_syscall_meta
  - kernel/trace/trace_fprobe.c:__trace_fprobe_create
```
**Symbols:**

```
ffffffff81228f40-ffffffff81228f68: kallsyms_lookup (STB_GLOBAL)
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
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffff8000101c6c08)
Location: kernel/kallsyms.c:281
Inline: False
Direct callers:
  - kernel/kallsyms.c:__sprint_symbol
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffff8000101c6c08-ffff8000101c6d5c: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (c040dbc8)
Location: kernel/kallsyms.c:281
Inline: False
Direct callers:
  - kernel/kallsyms.c:__sprint_symbol
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:ftrace_match_record
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
c040dbc8-c040dd0c: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (c00000000022ed20)
Location: kernel/kallsyms.c:281
Inline: False
Direct callers:
  - arch/powerpc/xmon/xmon.c:xmon_print_symbol
  - arch/powerpc/xmon/xmon.c:get_function_bounds
  - kernel/kallsyms.c:__sprint_symbol
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
c00000000022ed20-c00000000022eef0: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffe000147064)
Location: kernel/kallsyms.c:281
Inline: False
Direct callers:
  - kernel/kallsyms.c:__sprint_symbol
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffe000147064-ffffffe00014715e: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114fe70)
Location: kernel/kallsyms.c:281
Inline: False
Direct callers:
  - kernel/kallsyms.c:__sprint_symbol
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff8114fe70-ffffffff8114ff70: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81143120)
Location: kernel/kallsyms.c:281
Inline: False
Direct callers:
  - kernel/kallsyms.c:__sprint_symbol
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff81143120-ffffffff81143220: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114dd20)
Location: kernel/kallsyms.c:281
Inline: False
Direct callers:
  - kernel/kallsyms.c:__sprint_symbol
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff8114dd20-ffffffff8114de20: kallsyms_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *kallsyms_lookup(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8115ab00)
Location: kernel/kallsyms.c:281
Inline: False
Direct callers:
  - kernel/kallsyms.c:__sprint_symbol
  - kernel/kprobes.c:show_kprobe_addr
  - kernel/debug/kdb/kdb_support.c:kdbnearsym
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace_output.c:seq_print_sym
  - kernel/trace/trace_syscalls.c:find_syscall_meta
```
**Symbols:**

```
ffffffff8115ab00-ffffffff8115ac00: kallsyms_lookup (STB_GLOBAL)
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
