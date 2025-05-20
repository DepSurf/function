# Function: <code>within_module</code>

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
In kernel/module.c (ffffffff81106815)
Location: include/linux/module.h:520
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:lookup_module_symbol_attrs
```
```
In kernel/jump_label.c (ffffffff8118ae10)
Location: include/linux/module.h:520
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
In kernel/module.c (ffffffff81111e39)
Location: include/linux/module.h:522
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/jump_label.c (ffffffff8119d8f0)
Location: include/linux/module.h:522
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
In kernel/module.c (ffffffff811195b9)
Location: include/linux/module.h:522
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/jump_label.c (ffffffff811ad310)
Location: include/linux/module.h:522
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
In kernel/module.c (ffffffff8111af10)
Location: include/linux/module.h:514
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/jump_label.c (ffffffff811b477e)
Location: include/linux/module.h:514
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
In kernel/module.c (ffffffff81126490)
Location: include/linux/module.h:514
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/jump_label.c (ffffffff811c858e)
Location: include/linux/module.h:514
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
In kernel/module.c (ffffffff81134240)
Location: include/linux/module.h:520
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/jump_label.c (ffffffff811e8ad2)
Location: include/linux/module.h:520
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
In kernel/module.c (ffffffff8113fa20)
Location: include/linux/module.h:531
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/jump_label.c (ffffffff811f97fc)
Location: include/linux/module.h:531
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
In kernel/module.c (ffffffff8114ad59)
Location: include/linux/module.h:554
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/jump_label.c (ffffffff8121173f)
Location: include/linux/module.h:554
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
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
In kernel/module.c (ffffffff811569b9)
Location: include/linux/module.h:553
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/jump_label.c (ffffffff8121eb0b)
Location: include/linux/module.h:553
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
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
In kernel/module.c (ffffffff81167559)
Location: include/linux/module.h:574
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/jump_label.c (ffffffff8124b1c1)
Location: include/linux/module.h:574
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
In kernel/module.c (ffffffff81163cec)
Location: include/linux/module.h:584
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/jump_label.c (ffffffff81255621)
Location: include/linux/module.h:584
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
In kernel/module.c (ffffffff81164a9c)
Location: include/linux/module.h:571
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/jump_label.c (ffffffff81259b21)
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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8118a2bc)
Location: include/linux/module.h:582
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/jump_label.c (ffffffff81295891)
Location: include/linux/module.h:582
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
In kernel/module/main.c (ffffffff811901e7)
Location: include/linux/module.h:590
Inline: True
Inline callers:
  - kernel/module/main.c:is_module_address
```
```
In kernel/module/kallsyms.c (ffffffff81191910)
Location: include/linux/module.h:590
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:lookup_module_symbol_attrs
  - kernel/module/kallsyms.c:lookup_module_symbol_name
```
```
In kernel/jump_label.c (ffffffff812eab83)
Location: include/linux/module.h:590
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
In kernel/module/main.c (ffffffff811cd537)
Location: include/linux/module.h:597
Inline: True
Inline callers:
  - kernel/module/main.c:is_module_address
```
```
In kernel/module/kallsyms.c (ffffffff811cefa0)
Location: include/linux/module.h:597
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:lookup_module_symbol_attrs
  - kernel/module/kallsyms.c:lookup_module_symbol_name
```
```
In kernel/jump_label.c (ffffffff81354af3)
Location: include/linux/module.h:597
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
In kernel/module/main.c (0)
Location: include/linux/module.h:646
Inline: True
Inline callers:
  - kernel/module/main.c:__module_address
```
```
In kernel/module/kallsyms.c (0)
Location: include/linux/module.h:646
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:lookup_module_symbol_name
```
```
In kernel/jump_label.c (0)
Location: include/linux/module.h:646
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
In kernel/module/main.c (0)
Location: include/linux/module.h:648
Inline: True
Inline callers:
  - kernel/module/main.c:__module_address
```
```
In kernel/module/kallsyms.c (0)
Location: include/linux/module.h:648
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:lookup_module_symbol_name
```
```
In kernel/trace/ftrace.c (ffffffff8128baf1)
Location: include/linux/module.h:648
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_release_mod
```
```
In kernel/jump_label.c (0)
Location: include/linux/module.h:648
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
In arch/arm64/kernel/ftrace.c (ffff8000100a1b58)
Location: include/linux/module.h:553
Inline: True
Inline callers:
  - arch/arm64/kernel/ftrace.c:ftrace_make_nop
```
```
In kernel/module.c (ffff8000101c5dc8)
Location: include/linux/module.h:553
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/jump_label.c (ffff8000102aacb8)
Location: include/linux/module.h:553
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (c040cf88)
Location: include/linux/module.h:553
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
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
In kernel/module.c (c00000000022d9a0)
Location: include/linux/module.h:553
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/jump_label.c (c00000000035f2f0)
Location: include/linux/module.h:553
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe0001465aa)
Location: include/linux/module.h:553
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
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
In kernel/module.c (ffffffff8114efd9)
Location: include/linux/module.h:553
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/jump_label.c (ffffffff8121715b)
Location: include/linux/module.h:553
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
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
In kernel/module.c (ffffffff81142289)
Location: include/linux/module.h:553
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/jump_label.c (ffffffff81209ebb)
Location: include/linux/module.h:553
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
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
In kernel/module.c (ffffffff8114ce89)
Location: include/linux/module.h:553
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/jump_label.c (ffffffff81214efb)
Location: include/linux/module.h:553
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
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
In kernel/module.c (ffffffff81159bc0)
Location: include/linux/module.h:553
Inline: True
Inline callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
```
```
In kernel/jump_label.c (ffffffff81223eab)
Location: include/linux/module.h:553
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
```
</details>
</li>
</ul>

## Differences
