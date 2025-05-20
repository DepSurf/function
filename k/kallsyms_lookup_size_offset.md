# Function: <code>kallsyms_lookup_size_offset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8110b230)
Location: kernel/kallsyms.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - kernel/kprobes.c:register_jprobes
  - kernel/kprobes.c:init_kprobes
```
**Symbols:**

```
ffffffff8110b230-ffffffff8110b2d8: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81112a80)
Location: kernel/kallsyms.c:299
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:register_jprobes
```
**Symbols:**

```
ffffffff81112a80-ffffffff81112b28: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8111a190)
Location: kernel/kallsyms.c:299
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:register_jprobes
```
**Symbols:**

```
ffffffff8111a190-ffffffff8111a238: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8111bca0)
Location: kernel/kallsyms.c:294
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:register_jprobe
```
**Symbols:**

```
ffffffff8111bca0-ffffffff8111bd68: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811272c0)
Location: kernel/kallsyms.c:295
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:kprobe_on_func_entry
```
**Symbols:**

```
ffffffff811272c0-ffffffff81127388: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811351a0)
Location: kernel/kallsyms.c:260
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:kprobe_on_func_entry
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff811351a0-ffffffff81135268: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811406c0)
Location: kernel/kallsyms.c:260
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/kprobes.c:kprobe_on_func_entry
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff811406c0-ffffffff81140788: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114bab0)
Location: kernel/kallsyms.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/kprobes.c:kprobe_on_func_entry
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff8114bab0-ffffffff8114bb76: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81157780)
Location: kernel/kallsyms.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:__within_notrace_func
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff81157780-ffffffff81157846: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81168310)
Location: kernel/kallsyms.c:260
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:__within_notrace_func
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff81168310-ffffffff811683d8: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81164900)
Location: kernel/kallsyms.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:__within_notrace_func
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff81164900-ffffffff811649c8: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811656d0)
Location: kernel/kallsyms.c:291
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:__within_notrace_func
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff811656d0-ffffffff81165798: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8118b0b0)
Location: kernel/kallsyms.c:294
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:__within_notrace_func
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff8118b0b0-ffffffff8118b17b: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811ba2e0)
Location: kernel/kallsyms.c:318
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/trace/ftrace.c:ftrace_location
  - kernel/trace/trace_kprobe.c:__within_notrace_func
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff811ba2e0-ffffffff811ba3e3: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811fbf90)
Location: kernel/kallsyms.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/trace/ftrace.c:ftrace_location
  - kernel/trace/trace_kprobe.c:__within_notrace_func
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff811fbf90-ffffffff811fc093: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff812117a0)
Location: kernel/kallsyms.c:386
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/trace/ftrace.c:ftrace_location
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_kprobe.c:__within_notrace_func
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff812117a0-ffffffff812118a3: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81228e20)
Location: kernel/kallsyms.c:384
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/trace/ftrace.c:ftrace_location
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_kprobe.c:__within_notrace_func
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff81228e20-ffffffff81228f23: kallsyms_lookup_size_offset (STB_GLOBAL)
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
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffff8000101c6b30)
Location: kernel/kallsyms.c:261
Inline: False
Direct callers:
  - arch/arm64/kernel/probes/decode-insn.c:arm_kprobe_decode_insn
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/kprobes.c:kprobe_on_func_entry
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffff8000101c6b30-ffff8000101c6c08: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (c040dae4)
Location: kernel/kallsyms.c:261
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/kprobes.c:kprobe_on_func_entry
```
**Symbols:**

```
c040dae4-c040dbc8: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (c00000000022ec20)
Location: kernel/kallsyms.c:261
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:__within_notrace_func
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
c00000000022ec20-c00000000022ed1c: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffe000146fc4)
Location: kernel/kallsyms.c:261
Inline: False
```
**Symbols:**

```
ffffffe000146fc4-ffffffe000147064: kallsyms_lookup_size_offset (STB_GLOBAL)
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
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114fda0)
Location: kernel/kallsyms.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:__within_notrace_func
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff8114fda0-ffffffff8114fe66: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81143050)
Location: kernel/kallsyms.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:__within_notrace_func
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff81143050-ffffffff81143116: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114dc50)
Location: kernel/kallsyms.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:__within_notrace_func
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff8114dc50-ffffffff8114dd16: kallsyms_lookup_size_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kallsyms_lookup_size_offset(long unsigned int addr, long unsigned int *symbolsize, long unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8115aa30)
Location: kernel/kallsyms.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:__within_notrace_func
  - lib/error-inject.c:populate_error_injection_list
```
**Symbols:**

```
ffffffff8115aa30-ffffffff8115aaf6: kallsyms_lookup_size_offset (STB_GLOBAL)
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
