# Function: <code>kernel_symbol_value</code>

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
In kernel/module.c (ffffffff8113fbac)
Location: kernel/module.c:533
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
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
In kernel/module.c (ffffffff8114aef2)
Location: kernel/module.c:529
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
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
In kernel/module.c (ffffffff81156b64)
Location: kernel/module.c:532
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
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
In kernel/module.c (ffffffff81167706)
Location: kernel/module.c:535
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:simplify_symbols
  - kernel/module.c:__symbol_get
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
In kernel/module.c (ffffffff81163f01)
Location: kernel/module.c:567
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:simplify_symbols
  - kernel/module.c:__symbol_get
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
In kernel/module.c (ffffffff81164cb1)
Location: kernel/module.c:461
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:simplify_symbols
  - kernel/module.c:__symbol_get
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
In kernel/module.c (ffffffff8118a4d1)
Location: kernel/module.c:462
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:simplify_symbols
  - kernel/module.c:__symbol_get
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
In kernel/module/main.c (ffffffff8118d4d9)
Location: kernel/module/internal.h:120
Inline: True
Inline callers:
  - kernel/module/main.c:simplify_symbols
  - kernel/module/main.c:__symbol_get
```
```
In kernel/module/kallsyms.c (ffffffff81191b59)
Location: kernel/module/internal.h:120
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:module_get_kallsym
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
In kernel/module/main.c (ffffffff811c9f77)
Location: kernel/module/internal.h:120
Inline: True
Inline callers:
  - kernel/module/main.c:simplify_symbols
  - kernel/module/main.c:__symbol_get
```
```
In kernel/module/kallsyms.c (ffffffff811cf209)
Location: kernel/module/internal.h:120
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:module_get_kallsym
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
In kernel/module/main.c (ffffffff811dd1b2)
Location: kernel/module/internal.h:131
Inline: True
Inline callers:
  - kernel/module/main.c:simplify_symbols
  - kernel/module/main.c:__symbol_get
```
```
In kernel/module/kallsyms.c (ffffffff811e33a9)
Location: kernel/module/internal.h:131
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:module_get_kallsym
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
In kernel/module/main.c (ffffffff811f2eb2)
Location: kernel/module/internal.h:131
Inline: True
Inline callers:
  - kernel/module/main.c:simplify_symbols
  - kernel/module/main.c:__symbol_get
```
```
In kernel/module/kallsyms.c (ffffffff811f9109)
Location: kernel/module/internal.h:131
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:module_get_kallsym
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
In kernel/module.c (ffff8000101c5fc0)
Location: kernel/module.c:532
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
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
In kernel/module.c (c040d140)
Location: kernel/module.c:532
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
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
Location: kernel/module.c:532
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
Location: kernel/module.c:532
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
In kernel/module.c (ffffffff8114f184)
Location: kernel/module.c:532
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
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
In kernel/module.c (ffffffff81142434)
Location: kernel/module.c:532
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
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
In kernel/module.c (ffffffff8114d034)
Location: kernel/module.c:532
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
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
In kernel/module.c (ffffffff81159d84)
Location: kernel/module.c:532
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
```
</details>
</li>
</ul>

## Differences
