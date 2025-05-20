# Function: <code>within_module_core</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81106821)
Location: include/linux/module.h:506
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:lookup_module_symbol_attrs
```
```
In kernel/kprobes.c (ffffffff8112dea3)
Location: include/linux/module.h:506
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff81144de7)
Location: include/linux/module.h:506
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/jump_label.c (ffffffff8118ae2a)
Location: include/linux/module.h:506
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_module_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81111ea3)
Location: include/linux/module.h:508
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (ffffffff81136125)
Location: include/linux/module.h:508
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff8114d662)
Location: include/linux/module.h:508
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/jump_label.c (ffffffff8119d939)
Location: include/linux/module.h:508
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81119623)
Location: include/linux/module.h:508
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (ffffffff8113fea5)
Location: include/linux/module.h:508
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff811575a2)
Location: include/linux/module.h:508
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/jump_label.c (ffffffff811ad359)
Location: include/linux/module.h:508
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8111af80)
Location: include/linux/module.h:500
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (ffffffff81141259)
Location: include/linux/module.h:500
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff8115a71e)
Location: include/linux/module.h:500
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/jump_label.c (ffffffff811b47d2)
Location: include/linux/module.h:500
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81126500)
Location: include/linux/module.h:500
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (ffffffff8114e0f9)
Location: include/linux/module.h:500
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff811673ac)
Location: include/linux/module.h:500
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/jump_label.c (ffffffff811c85d6)
Location: include/linux/module.h:500
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811342b0)
Location: include/linux/module.h:506
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (ffffffff8115d109)
Location: include/linux/module.h:506
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff811760c0)
Location: include/linux/module.h:506
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/jump_label.c (ffffffff811e8ade)
Location: include/linux/module.h:506
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113fa90)
Location: include/linux/module.h:517
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (ffffffff81169b09)
Location: include/linux/module.h:517
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff81183d00)
Location: include/linux/module.h:517
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/jump_label.c (ffffffff811f980d)
Location: include/linux/module.h:517
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114adc2)
Location: include/linux/module.h:540
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (ffffffff81176133)
Location: include/linux/module.h:540
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff81190a84)
Location: include/linux/module.h:540
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/jump_label.c (ffffffff8121174b)
Location: include/linux/module.h:540
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
```
In fs/fs_context.c (ffffffff8130a0fe)
Location: include/linux/module.h:540
Inline: True
Inline callers:
  - fs/fs_context.c:logfc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81156a22)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (ffffffff81181fe3)
Location: include/linux/module.h:539
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff8119ca84)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/jump_label.c (ffffffff8121eb1b)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
```
In fs/fs_context.c (ffffffff8131d16e)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - fs/fs_context.c:logfc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811675c2)
Location: include/linux/module.h:560
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (ffffffff81197ed6)
Location: include/linux/module.h:560
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff811b2c53)
Location: include/linux/module.h:560
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/jump_label.c (ffffffff8124b1de)
Location: include/linux/module.h:560
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81163d87)
Location: include/linux/module.h:570
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (ffffffff811950e0)
Location: include/linux/module.h:570
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff811b06c3)
Location: include/linux/module.h:570
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/jump_label.c (ffffffff8125563e)
Location: include/linux/module.h:570
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81164b37)
Location: include/linux/module.h:557
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (ffffffff811960f0)
Location: include/linux/module.h:557
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff811b0fc3)
Location: include/linux/module.h:557
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/trace/trace.c (ffffffff811c00d5)
Location: include/linux/module.h:557
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_check_vprintf
```
```
In kernel/jump_label.c (ffffffff81259b3e)
Location: include/linux/module.h:557
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8118a357)
Location: include/linux/module.h:568
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (ffffffff811bf06a)
Location: include/linux/module.h:568
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff811dae53)
Location: include/linux/module.h:568
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/trace/trace.c (ffffffff811eaad8)
Location: include/linux/module.h:568
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_check_vprintf
```
```
In kernel/jump_label.c (ffffffff812958ae)
Location: include/linux/module.h:568
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff8119022a)
Location: include/linux/module.h:571
Inline: True
Inline callers:
  - kernel/module/main.c:is_module_address
```
```
In kernel/module/kallsyms.c (ffffffff811919a4)
Location: include/linux/module.h:571
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:lookup_module_symbol_attrs
  - kernel/module/kallsyms.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (ffffffff811f242c)
Location: include/linux/module.h:571
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff81210dea)
Location: include/linux/module.h:571
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/trace/trace.c (ffffffff812228f8)
Location: include/linux/module.h:571
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_check_vprintf
```
```
In kernel/jump_label.c (ffffffff812eaba1)
Location: include/linux/module.h:571
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/callthunks.c (ffffffff810bebff)
Location: include/linux/module.h:578
Inline: True
Inline callers:
  - arch/x86/kernel/callthunks.c:is_coretext
```
```
In kernel/module/main.c (ffffffff811cd57a)
Location: include/linux/module.h:578
Inline: True
Inline callers:
  - kernel/module/main.c:is_module_address
```
```
In kernel/module/kallsyms.c (ffffffff811cf034)
Location: include/linux/module.h:578
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:lookup_module_symbol_attrs
  - kernel/module/kallsyms.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (ffffffff8123914c)
Location: include/linux/module.h:578
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff8125a291)
Location: include/linux/module.h:578
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/trace/trace.c (ffffffff8126d95b)
Location: include/linux/module.h:578
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_check_vprintf
```
```
In kernel/jump_label.c (ffffffff81354b11)
Location: include/linux/module.h:578
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/callthunks.c (0)
Location: include/linux/module.h:626
Inline: True
Inline callers:
  - arch/x86/kernel/callthunks.c:is_coretext
```
```
In kernel/module/main.c (0)
Location: include/linux/module.h:626
Inline: True
Inline callers:
  - kernel/module/main.c:__module_address
```
```
In kernel/module/kallsyms.c (0)
Location: include/linux/module.h:626
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (ffffffff8124d703)
Location: include/linux/module.h:626
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff81271671)
Location: include/linux/module.h:626
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/trace/trace.c (0)
Location: include/linux/module.h:626
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_check_vprintf
```
```
In kernel/jump_label.c (0)
Location: include/linux/module.h:626
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
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
In arch/x86/kernel/callthunks.c (0)
Location: include/linux/module.h:628
Inline: True
Inline callers:
  - arch/x86/kernel/callthunks.c:is_coretext
```
```
In kernel/module/main.c (0)
Location: include/linux/module.h:628
Inline: True
Inline callers:
  - kernel/module/main.c:__module_address
```
```
In kernel/module/kallsyms.c (0)
Location: include/linux/module.h:628
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (ffffffff81267603)
Location: include/linux/module.h:628
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/linux/module.h:628
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/trace/trace.c (0)
Location: include/linux/module.h:628
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_check_vprintf
```
```
In kernel/jump_label.c (0)
Location: include/linux/module.h:628
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/ftrace.c (ffff8000100a1b80)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - arch/arm64/kernel/ftrace.c:ftrace_make_nop
```
```
In kernel/module.c (ffff8000101c5e4c)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (ffff8000101f760c)
Location: include/linux/module.h:539
Inline: True
```
```
In kernel/trace/ftrace.c (ffff8000102158d4)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/jump_label.c (ffff8000102aacc4)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
```
In fs/fs_context.c (ffff8000103d5034)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - fs/fs_context.c:logfc
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (c040d008)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (c043773c)
Location: include/linux/module.h:539
Inline: True
```
```
In kernel/trace/ftrace.c (c0454628)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In fs/fs_context.c (c05aee90)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - fs/fs_context.c:logfc
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/module_64.c (c00000000004e74c)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - arch/powerpc/kernel/module_64.c:module_trampoline_target
```
```
In kernel/module.c (c00000000022da50)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (c00000000026dc28)
Location: include/linux/module.h:539
Inline: True
```
```
In kernel/trace/ftrace.c (c0000000002972a4)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/jump_label.c (c00000000035f2fc)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
```
In fs/fs_context.c (c0000000004d7e54)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - fs/fs_context.c:logfc
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000146604)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/trace/ftrace.c (ffffffe0001755de)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In fs/fs_context.c (ffffffe00028f20a)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - fs/fs_context.c:logfc
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114f042)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (ffffffff8117a603)
Location: include/linux/module.h:539
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff811950a4)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/jump_label.c (ffffffff8121716b)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
```
In fs/fs_context.c (ffffffff8131574e)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - fs/fs_context.c:logfc
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811422f2)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (ffffffff8116d7a3)
Location: include/linux/module.h:539
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff811881b4)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/jump_label.c (ffffffff81209ecb)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
```
In fs/fs_context.c (ffffffff8130633e)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - fs/fs_context.c:logfc
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114cef2)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (ffffffff811783d3)
Location: include/linux/module.h:539
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff81192e74)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/jump_label.c (ffffffff81214f0b)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
```
In fs/fs_context.c (ffffffff8131353e)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - fs/fs_context.c:logfc
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81159c3a)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/kprobes.c (ffffffff81185ca3)
Location: include/linux/module.h:539
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff811a0a04)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/jump_label.c (ffffffff81223ebb)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
```
In fs/fs_context.c (ffffffff81324d8e)
Location: include/linux/module.h:539
Inline: True
Inline callers:
  - fs/fs_context.c:logfc
```
</details>
</li>
</ul>

## Differences
