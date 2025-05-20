# Function: <code>text_poke_bp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *text_poke_bp(void *addr, const void *opcode, size_t len, void *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81036c80)
Location: arch/x86/kernel/alternative.c:772
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
```
**Symbols:**

```
ffffffff81036c80-ffffffff81036d62: text_poke_bp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *text_poke_bp(void *addr, const void *opcode, size_t len, void *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81035e80)
Location: arch/x86/kernel/alternative.c:773
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
**Symbols:**

```
ffffffff81035e80-ffffffff81035f62: text_poke_bp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *text_poke_bp(void *addr, const void *opcode, size_t len, void *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81035bb0)
Location: arch/x86/kernel/alternative.c:778
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobes
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
**Symbols:**

```
ffffffff81035bb0-ffffffff81035c92: text_poke_bp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *text_poke_bp(void *addr, const void *opcode, size_t len, void *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81033b60)
Location: arch/x86/kernel/alternative.c:783
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
**Symbols:**

```
ffffffff81033b60-ffffffff81033c42: text_poke_bp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *text_poke_bp(void *addr, const void *opcode, size_t len, void *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81035ea0)
Location: arch/x86/kernel/alternative.c:781
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
**Symbols:**

```
ffffffff81035ea0-ffffffff81035f82: text_poke_bp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *text_poke_bp(void *addr, const void *opcode, size_t len, void *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81036d30)
Location: arch/x86/kernel/alternative.c:781
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
**Symbols:**

```
ffffffff81036d30-ffffffff81036e12: text_poke_bp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *text_poke_bp(void *addr, const void *opcode, size_t len, void *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81037f40)
Location: arch/x86/kernel/alternative.c:790
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:__jump_label_transform
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
**Symbols:**

```
ffffffff81037f40-ffffffff81038022: text_poke_bp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void text_poke_bp(void *addr, const void *opcode, size_t len, void *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103a4b0)
Location: arch/x86/kernel/alternative.c:1101
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:__jump_label_transform
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
**Symbols:**

```
ffffffff8103a4b0-ffffffff8103a538: text_poke_bp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void text_poke_bp(void *addr, const void *opcode, size_t len, void *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103ac90)
Location: arch/x86/kernel/alternative.c:1101
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:__jump_label_transform
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
**Symbols:**

```
ffffffff8103ac90-ffffffff8103ad18: text_poke_bp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void text_poke_bp(void *addr, const void *opcode, size_t len, const void *emulate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81bc0400)
Location: arch/x86/kernel/alternative.c:1332
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:jump_label_transform
  - arch/x86/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
```
**Symbols:**

```
ffffffff81bc0400-ffffffff81bc0466: text_poke_bp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void text_poke_bp(void *addr, const void *opcode, size_t len, const void *emulate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81c393c0)
Location: arch/x86/kernel/alternative.c:1383
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:jump_label_transform
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
```
**Symbols:**

```
ffffffff81c393c0-ffffffff81c39426: text_poke_bp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void text_poke_bp(void *addr, const void *opcode, size_t len, const void *emulate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81c2b810)
Location: arch/x86/kernel/alternative.c:1304
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:jump_label_transform
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
```
**Symbols:**

```
ffffffff81c2b810-ffffffff81c2b876: text_poke_bp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void text_poke_bp(void *addr, const void *opcode, size_t len, const void *emulate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81d49f00)
Location: arch/x86/kernel/alternative.c:1304
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:jump_label_transform
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
```
**Symbols:**

```
ffffffff81d49f00-ffffffff81d49f66: text_poke_bp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void text_poke_bp(void *addr, const void *opcode, size_t len, const void *emulate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81f19490)
Location: arch/x86/kernel/alternative.c:1696
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:jump_label_transform
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
```
**Symbols:**

```
ffffffff81f19490-ffffffff81f19517: text_poke_bp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void text_poke_bp(void *addr, const void *opcode, size_t len, const void *emulate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff820c0f80)
Location: arch/x86/kernel/alternative.c:2194
Inline: False
Direct callers:
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
```
**Symbols:**

```
ffffffff820c0f80-ffffffff820c0ff6: text_poke_bp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void text_poke_bp(void *addr, const void *opcode, size_t len, const void *emulate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff82144c40)
Location: arch/x86/kernel/alternative.c:2429
Inline: False
Direct callers:
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
```
**Symbols:**

```
ffffffff82144c40-ffffffff82144cb6: text_poke_bp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void text_poke_bp(void *addr, const void *opcode, size_t len, const void *emulate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff82227360)
Location: arch/x86/kernel/alternative.c:2519
Inline: False
Direct callers:
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/ftrace.c:ftrace_update_ftrace_func
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
```
**Symbols:**

```
ffffffff82227360-ffffffff822273d6: text_poke_bp (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void text_poke_bp(void *addr, const void *opcode, size_t len, void *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103adf0)
Location: arch/x86/kernel/alternative.c:1101
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:__jump_label_transform
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
**Symbols:**

```
ffffffff8103adf0-ffffffff8103ae78: text_poke_bp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void text_poke_bp(void *addr, const void *opcode, size_t len, void *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8102a600)
Location: arch/x86/kernel/alternative.c:1101
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:__jump_label_transform
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
**Symbols:**

```
ffffffff8102a600-ffffffff8102a688: text_poke_bp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void text_poke_bp(void *addr, const void *opcode, size_t len, void *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103ac50)
Location: arch/x86/kernel/alternative.c:1101
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:__jump_label_transform
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
**Symbols:**

```
ffffffff8103ac50-ffffffff8103acd8: text_poke_bp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void text_poke_bp(void *addr, const void *opcode, size_t len, void *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103bc50)
Location: arch/x86/kernel/alternative.c:1101
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:__jump_label_transform
  - arch/x86/kernel/kprobes/opt.c:arch_unoptimize_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
**Symbols:**

```
ffffffff8103bc50-ffffffff8103bcd8: text_poke_bp (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void *</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void *emulate</code>
</li>
<li>
<b>Param removed. </b>
<code>void *handler</code>
</li>
</ul>
</details>
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
