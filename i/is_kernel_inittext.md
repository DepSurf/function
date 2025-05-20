# Function: <code>is_kernel_inittext</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8110ade0)
Location: kernel/kallsyms.c:55
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811125ae)
Location: kernel/kallsyms.c:59
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81119cce)
Location: kernel/kallsyms.c:59
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8111b777)
Location: kernel/kallsyms.c:54
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81126cf7)
Location: kernel/kallsyms.c:55
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81134bdb)
Location: include/linux/kallsyms.h:23
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811403ca)
Location: include/linux/kallsyms.h:23
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114b7bc)
Location: include/linux/kallsyms.h:23
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8115748c)
Location: include/linux/kallsyms.h:23
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81168015)
Location: include/linux/kallsyms.h:24
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81164605)
Location: include/linux/kallsyms.h:24
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811653e8)
Location: include/linux/kallsyms.h:24
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8118ab08)
Location: include/linux/kallsyms.h:27
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
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
In kernel/extable.c (ffffffff810f7cdb)
Location: include/asm-generic/sections.h:191
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:__kernel_text_address
```
```
In kernel/kallsyms.c (ffffffff811b9c16)
Location: include/asm-generic/sections.h:191
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
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
In kernel/extable.c (ffffffff8111a52b)
Location: include/asm-generic/sections.h:191
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:__kernel_text_address
```
```
In kernel/kallsyms.c (ffffffff811fb326)
Location: include/asm-generic/sections.h:191
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
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
In kernel/extable.c (ffffffff8112779b)
Location: include/asm-generic/sections.h:191
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:__kernel_text_address
```
```
In kernel/kallsyms.c (ffffffff812106c6)
Location: include/asm-generic/sections.h:191
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
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
In kernel/extable.c (ffffffff81131d7b)
Location: include/asm-generic/sections.h:191
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
  - kernel/extable.c:__kernel_text_address
```
```
In kernel/kallsyms.c (ffffffff81227d46)
Location: include/asm-generic/sections.h:191
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffff8000101c67cc)
Location: include/linux/kallsyms.h:23
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
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
In kernel/kallsyms.c (c040d718)
Location: include/linux/kallsyms.h:23
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (c00000000022e580)
Location: include/linux/kallsyms.h:23
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
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
In kernel/kallsyms.c (ffffffe000146cf4)
Location: include/linux/kallsyms.h:23
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114faac)
Location: include/linux/kallsyms.h:23
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81142d5c)
Location: include/linux/kallsyms.h:23
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114d95c)
Location: include/linux/kallsyms.h:23
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8115a73c)
Location: include/linux/kallsyms.h:23
Inline: True
Inline callers:
  - kernel/kallsyms.c:get_symbol_pos
```
</details>
</li>
</ul>

## Differences
