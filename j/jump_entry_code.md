# Function: <code>jump_entry_code</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81a1fdf4)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:__jump_label_transform
```
```
In kernel/jump_label.c (ffffffff811f9b75)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
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
In arch/x86/kernel/jump_label.c (ffffffff810373d6)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:__jump_label_set_jump_code
```
```
In kernel/jump_label.c (ffffffff81211ab6)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
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
In arch/x86/kernel/jump_label.c (ffffffff81037ba6)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:__jump_label_set_jump_code
```
```
In kernel/jump_label.c (ffffffff8121f2b6)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
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
In arch/x86/kernel/jump_label.c (ffffffff81039ab4)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:jump_label_transform
  - arch/x86/kernel/jump_label.c:__jump_label_set_jump_code
```
```
In kernel/jump_label.c (ffffffff8124b576)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
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
In arch/x86/kernel/jump_label.c (ffffffff8103a2e4)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:jump_label_transform
  - arch/x86/kernel/jump_label.c:jump_label_transform
  - arch/x86/kernel/jump_label.c:__jump_label_set_jump_code
```
```
In kernel/jump_label.c (ffffffff812559c7)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:__jump_label_mod_text_reserved
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
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
In arch/x86/kernel/jump_label.c (ffffffff8103bd6e)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:jump_label_transform
  - arch/x86/kernel/jump_label.c:jump_label_transform
  - arch/x86/kernel/jump_label.c:__jump_label_set_jump_code
```
```
In kernel/jump_label.c (ffffffff81259ed4)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
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
In arch/x86/kernel/jump_label.c (ffffffff81041844)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:jump_label_transform
  - arch/x86/kernel/jump_label.c:jump_label_transform
  - arch/x86/kernel/jump_label.c:__jump_label_patch
  - arch/x86/kernel/jump_label.c:arch_jump_entry_size
```
```
In kernel/jump_label.c (ffffffff81295c70)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
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
In arch/x86/kernel/jump_label.c (ffffffff81049503)
Location: include/linux/jump_label.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:jump_label_transform
  - arch/x86/kernel/jump_label.c:jump_label_transform
  - arch/x86/kernel/jump_label.c:__jump_label_patch
  - arch/x86/kernel/jump_label.c:arch_jump_entry_size
```
```
In kernel/jump_label.c (ffffffff812eb990)
Location: include/linux/jump_label.h:123
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
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
In arch/x86/kernel/jump_label.c (ffffffff81054573)
Location: include/linux/jump_label.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:__jump_label_patch
  - arch/x86/kernel/jump_label.c:arch_jump_entry_size
```
```
In kernel/jump_label.c (ffffffff81355a60)
Location: include/linux/jump_label.h:123
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
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
In arch/x86/kernel/jump_label.c (ffffffff810555d3)
Location: include/linux/jump_label.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:__jump_label_patch
  - arch/x86/kernel/jump_label.c:arch_jump_entry_size
```
```
In kernel/jump_label.c (ffffffff813870c7)
Location: include/linux/jump_label.h:123
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
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
In arch/x86/kernel/jump_label.c (ffffffff8105c843)
Location: include/linux/jump_label.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:__jump_label_patch
  - arch/x86/kernel/jump_label.c:arch_jump_entry_size
```
```
In kernel/jump_label.c (ffffffff813b05d7)
Location: include/linux/jump_label.h:123
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
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
In arch/arm64/kernel/jump_label.c (ffff8000100a7190)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - arch/arm64/kernel/jump_label.c:arch_jump_label_transform
```
```
In kernel/jump_label.c (ffff8000102ab774)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (0)
Location: include/linux/jump_label.h:147
Inline: True
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81037d06)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:__jump_label_set_jump_code
```
```
In kernel/jump_label.c (ffffffff81217906)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
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
In arch/x86/kernel/jump_label.c (ffffffff810276e6)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:__jump_label_set_jump_code
```
```
In kernel/jump_label.c (ffffffff8120a666)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
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
In arch/x86/kernel/jump_label.c (ffffffff81037b66)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:__jump_label_set_jump_code
```
```
In kernel/jump_label.c (ffffffff812156a6)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
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
In arch/x86/kernel/jump_label.c (ffffffff81038b66)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/jump_label.c:__jump_label_set_jump_code
```
```
In kernel/jump_label.c (ffffffff81224696)
Location: include/linux/jump_label.h:128
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_text_reserved
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_init
  - kernel/jump_label.c:__jump_label_update
  - kernel/jump_label.c:__jump_label_update
```
</details>
</li>
</ul>

## Differences
