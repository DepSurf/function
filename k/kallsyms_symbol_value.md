# Function: <code>kallsyms_symbol_value</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: include/linux/module.h:494
Inline: True
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
In kernel/module.c (0)
Location: include/linux/module.h:517
Inline: True
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
In kernel/module.c (0)
Location: include/linux/module.h:516
Inline: True
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
In kernel/module.c (ffffffff8116786a)
Location: include/linux/module.h:537
Inline: True
Inline callers:
  - kernel/module.c:module_kallsyms_on_each_symbol
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_kallsyms_symbol
  - kernel/module.c:find_kallsyms_symbol
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
In kernel/module.c (ffffffff8116406a)
Location: include/linux/module.h:547
Inline: True
Inline callers:
  - kernel/module.c:module_kallsyms_on_each_symbol
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_kallsyms_symbol
  - kernel/module.c:find_kallsyms_symbol
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
In kernel/module.c (ffffffff81164e26)
Location: include/linux/module.h:536
Inline: True
Inline callers:
  - kernel/module.c:module_kallsyms_on_each_symbol
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_kallsyms_symbol
  - kernel/module.c:find_kallsyms_symbol
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
In kernel/module.c (ffffffff8118a636)
Location: include/linux/module.h:547
Inline: True
Inline callers:
  - kernel/module.c:module_kallsyms_on_each_symbol
  - kernel/module.c:find_kallsyms_symbol_value
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_kallsyms_symbol
  - kernel/module.c:find_kallsyms_symbol
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module/kallsyms.c (ffffffff81191d9c)
Location: include/linux/module.h:550
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:module_kallsyms_on_each_symbol
  - kernel/module/kallsyms.c:find_kallsyms_symbol_value
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:find_kallsyms_symbol
  - kernel/module/kallsyms.c:find_kallsyms_symbol
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module/kallsyms.c (ffffffff811cf48c)
Location: include/linux/module.h:557
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:module_kallsyms_on_each_symbol
  - kernel/module/kallsyms.c:find_kallsyms_symbol_value
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:find_kallsyms_symbol
  - kernel/module/kallsyms.c:find_kallsyms_symbol
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module/kallsyms.c (ffffffff811e3608)
Location: include/linux/module.h:594
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:module_kallsyms_on_each_symbol
  - kernel/module/kallsyms.c:__find_kallsyms_symbol_value
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:find_kallsyms_symbol
  - kernel/module/kallsyms.c:find_kallsyms_symbol
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module/kallsyms.c (ffffffff811f9368)
Location: include/linux/module.h:596
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:module_kallsyms_on_each_symbol
  - kernel/module/kallsyms.c:__find_kallsyms_symbol_value
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:find_kallsyms_symbol
  - kernel/module/kallsyms.c:find_kallsyms_symbol
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
In kernel/module.c (0)
Location: include/linux/module.h:516
Inline: True
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
In kernel/module.c (c040d29c)
Location: include/linux/module.h:516
Inline: True
Inline callers:
  - kernel/module.c:module_kallsyms_on_each_symbol
  - kernel/module.c:find_kallsyms_symbol_value
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:find_kallsyms_symbol
  - kernel/module.c:find_kallsyms_symbol
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
In kernel/module.c (0)
Location: include/linux/module.h:516
Inline: True
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
In kernel/module.c (0)
Location: include/linux/module.h:516
Inline: True
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
In kernel/module.c (0)
Location: include/linux/module.h:516
Inline: True
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
In kernel/module.c (0)
Location: include/linux/module.h:516
Inline: True
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
In kernel/module.c (0)
Location: include/linux/module.h:516
Inline: True
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
In kernel/module.c (0)
Location: include/linux/module.h:516
Inline: True
```
</details>
</li>
</ul>

## Differences
