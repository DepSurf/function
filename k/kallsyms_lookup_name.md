# Function: <code>kallsyms_lookup_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8110b030)
Location: kernel/kallsyms.c:180
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_addr
  - kernel/kprobes.c:init_kprobes
  - kernel/trace/trace_kprobe.c:alloc_symbol_cache
```
**Symbols:**

```
ffffffff8110b030-ffffffff8110b0d0: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81112840)
Location: kernel/kallsyms.c:201
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:kprobe_addr
  - kernel/trace/trace_kprobe.c:alloc_symbol_cache
```
**Symbols:**

```
ffffffff81112840-ffffffff811128f8: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81119f60)
Location: kernel/kallsyms.c:201
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:kprobe_addr
  - kernel/trace/trace_kprobe.c:alloc_symbol_cache
```
**Symbols:**

```
ffffffff81119f60-ffffffff8111a018: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8111b9e0)
Location: kernel/kallsyms.c:196
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_lookup_name
  - kernel/trace/trace_kprobe.c:alloc_symbol_cache
```
**Symbols:**

```
ffffffff8111b9e0-ffffffff8111ba91: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81126f80)
Location: kernel/kallsyms.c:197
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_lookup_name
  - kernel/trace/trace_kprobe.c:alloc_symbol_cache
```
**Symbols:**

```
ffffffff81126f80-ffffffff81127031: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81134e60)
Location: kernel/kallsyms.c:162
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_lookup_name
  - kernel/trace/trace_kprobe.c:alloc_symbol_cache
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
```
**Symbols:**

```
ffffffff81134e60-ffffffff81134f11: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81140600)
Location: kernel/kallsyms.c:162
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_lookup_name
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
```
**Symbols:**

```
ffffffff81140600-ffffffff811406b1: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114b9f0)
Location: kernel/kallsyms.c:163
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_lookup_name
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
```
**Symbols:**

```
ffffffff8114b9f0-ffffffff8114baa1: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811576c0)
Location: kernel/kallsyms.c:163
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_lookup_name
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
```
**Symbols:**

```
ffffffff811576c0-ffffffff81157771: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81168180)
Location: kernel/kallsyms.c:164
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_lookup_name
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/bpf/verifier.c:check_attach_btf_id
```
**Symbols:**

```
ffffffff81168180-ffffffff81168231: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81164770)
Location: kernel/kallsyms.c:165
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_lookup_name
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
**Symbols:**

```
ffffffff81164770-ffffffff81164821: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81165550)
Location: kernel/kallsyms.c:186
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_lookup_name
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:add_kfunc_call
```
**Symbols:**

```
ffffffff81165550-ffffffff81165601: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8118af30)
Location: kernel/kallsyms.c:189
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_lookup_name
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:add_kfunc_call
```
**Symbols:**

```
ffffffff8118af30-ffffffff8118afe1: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811ba120)
Location: kernel/kallsyms.c:210
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_lookup_name
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/bpf/syscall.c:bpf_kallsyms_lookup_name
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/btf.c:btf_parse_kptrs
```
**Symbols:**

```
ffffffff811ba120-ffffffff811ba1ef: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811fbcb0)
Location: kernel/kallsyms.c:271
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_lookup_name
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/bpf/syscall.c:bpf_kallsyms_lookup_name
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/btf.c:btf_parse_fields
```
**Symbols:**

```
ffffffff811fbcb0-ffffffff811fbd66: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff812114d0)
Location: kernel/kallsyms.c:267
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_lookup_name
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/bpf/syscall.c:bpf_kallsyms_lookup_name
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/btf.c:btf_parse_kptr
```
**Symbols:**

```
ffffffff812114d0-ffffffff81211586: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81228b50)
Location: kernel/kallsyms.c:265
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_lookup_name
  - kernel/debug/kdb/kdb_support.c:kdbgetsymval
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/bpf/syscall.c:bpf_kallsyms_lookup_name
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/btf.c:btf_parse_kptr
```
**Symbols:**

```
ffffffff81228b50-ffffffff81228c06: kallsyms_lookup_name (STB_GLOBAL)
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
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffff8000101c6a58)
Location: kernel/kallsyms.c:163
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_lookup_name
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
```
**Symbols:**

```
ffff8000101c6a58-ffff8000101c6b2c: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (c040da18)
Location: kernel/kallsyms.c:163
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_lookup_name
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
```
**Symbols:**

```
c040da18-c040dae4: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (c00000000022e8f0)
Location: kernel/kallsyms.c:163
Inline: False
Direct callers:
  - arch/powerpc/kernel/kprobes.c:kprobe_lookup_name
  - arch/powerpc/kernel/optprobes.c:arch_prepare_optimized_kprobe
  - arch/powerpc/kernel/optprobes.c:arch_prepare_optimized_kprobe
  - arch/powerpc/xmon/xmon.c:symbol_lookup
  - arch/powerpc/xmon/xmon.c:symbol_lookup
  - arch/powerpc/xmon/xmon.c:scanhex
  - kernel/kprobes.c:kprobe_lookup_name
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
```
**Symbols:**

```
c00000000022e8f0-c00000000022ec20: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffe000146f28)
Location: kernel/kallsyms.c:163
Inline: False
```
**Symbols:**

```
ffffffe000146f28-ffffffe000146fc4: kallsyms_lookup_name (STB_GLOBAL)
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
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114fce0)
Location: kernel/kallsyms.c:163
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_lookup_name
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
```
**Symbols:**

```
ffffffff8114fce0-ffffffff8114fd91: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81142f90)
Location: kernel/kallsyms.c:163
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_lookup_name
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
```
**Symbols:**

```
ffffffff81142f90-ffffffff81143041: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114db90)
Location: kernel/kallsyms.c:163
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_lookup_name
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
```
**Symbols:**

```
ffffffff8114db90-ffffffff8114dc41: kallsyms_lookup_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int kallsyms_lookup_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8115a970)
Location: kernel/kallsyms.c:163
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_lookup_name
  - kernel/trace/trace_kprobe.c:within_notrace_func
  - kernel/trace/trace_kprobe.c:trace_kprobe_error_injectable
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
```
**Symbols:**

```
ffffffff8115a970-ffffffff8115aa21: kallsyms_lookup_name (STB_GLOBAL)
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
