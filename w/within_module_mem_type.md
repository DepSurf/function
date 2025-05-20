# Function: <code>within_module_mem_type</code>

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
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/callthunks.c (ffffffff810c22fd)
Location: include/linux/module.h:615
Inline: True
Inline callers:
  - arch/x86/kernel/callthunks.c:is_coretext
```
```
In kernel/module/main.c (ffffffff811e10fe)
Location: include/linux/module.h:615
Inline: True
Inline callers:
  - kernel/module/main.c:is_module_text_address
  - kernel/module/main.c:is_module_text_address
  - kernel/module/main.c:__module_address
  - kernel/module/main.c:__module_address
  - kernel/module/main.c:symbol_put_addr
  - kernel/module/main.c:symbol_put_addr
```
```
In kernel/module/kallsyms.c (ffffffff811e30e1)
Location: include/linux/module.h:615
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:find_kallsyms_symbol
```
```
In kernel/kprobes.c (ffffffff8124f758)
Location: include/linux/module.h:615
Inline: True
Inline callers:
  - kernel/kprobes.c:check_kprobe_address_safe
```
```
In kernel/trace/ftrace.c (ffffffff81271845)
Location: include/linux/module.h:615
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/trace/trace.c (ffffffff81284e62)
Location: include/linux/module.h:615
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_check_vprintf
```
```
In kernel/static_call_inline.c (ffffffff8136425c)
Location: include/linux/module.h:615
Inline: True
Inline callers:
  - kernel/static_call_inline.c:__static_call_init
```
```
In kernel/jump_label.c (ffffffff81385ea1)
Location: include/linux/module.h:615
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_add_module
```
```
In lib/extable.c (ffffffff820a02a1)
Location: include/linux/module.h:615
Inline: True
Inline callers:
  - lib/extable.c:trim_init_extable
  - lib/extable.c:trim_init_extable
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/callthunks.c (ffffffff810c976d)
Location: include/linux/module.h:617
Inline: True
Inline callers:
  - arch/x86/kernel/callthunks.c:is_coretext
```
```
In kernel/module/main.c (ffffffff811f6e2e)
Location: include/linux/module.h:617
Inline: True
Inline callers:
  - kernel/module/main.c:is_module_text_address
  - kernel/module/main.c:is_module_text_address
  - kernel/module/main.c:__module_address
  - kernel/module/main.c:__module_address
  - kernel/module/main.c:symbol_put_addr
  - kernel/module/main.c:symbol_put_addr
```
```
In kernel/module/kallsyms.c (ffffffff811f8e41)
Location: include/linux/module.h:617
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:find_kallsyms_symbol
```
```
In kernel/kprobes.c (ffffffff81269688)
Location: include/linux/module.h:617
Inline: True
Inline callers:
  - kernel/kprobes.c:check_kprobe_address_safe
```
```
In kernel/trace/ftrace.c (ffffffff8128bb05)
Location: include/linux/module.h:617
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/trace/trace.c (ffffffff8129ff5a)
Location: include/linux/module.h:617
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_check_vprintf
```
```
In kernel/static_call_inline.c (ffffffff8138d12c)
Location: include/linux/module.h:617
Inline: True
Inline callers:
  - kernel/static_call_inline.c:__static_call_init
```
```
In kernel/jump_label.c (ffffffff813af361)
Location: include/linux/module.h:617
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_add_module
```
```
In lib/extable.c (ffffffff82178271)
Location: include/linux/module.h:617
Inline: True
Inline callers:
  - lib/extable.c:trim_init_extable
  - lib/extable.c:trim_init_extable
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
