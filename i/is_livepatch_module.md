# Function: <code>is_livepatch_module</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: include/linux/module.h:639
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/module.h:639
Inline: True
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
In kernel/livepatch/core.c (0)
Location: include/linux/module.h:639
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/module.h:639
Inline: True
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
In kernel/livepatch/core.c (0)
Location: include/linux/module.h:631
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/module.h:631
Inline: True
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
In kernel/livepatch/core.c (0)
Location: include/linux/module.h:631
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/module.h:631
Inline: True
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
In kernel/livepatch/core.c (0)
Location: include/linux/module.h:640
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/module.h:640
Inline: True
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
In kernel/livepatch/core.c (0)
Location: include/linux/module.h:651
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/module.h:651
Inline: True
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
In kernel/livepatch/core.c (0)
Location: include/linux/module.h:674
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/module.h:674
Inline: True
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
In kernel/livepatch/core.c (0)
Location: include/linux/module.h:673
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/module.h:673
Inline: True
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
In kernel/livepatch/core.c (ffffffff8113ab0e)
Location: include/linux/module.h:694
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
```
In kernel/module.c (ffffffff81166dc4)
Location: include/linux/module.h:694
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:add_kallsyms
  - kernel/module.c:layout_symtab
  - kernel/module.c:free_module
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
In kernel/livepatch/core.c (ffffffff811355fe)
Location: include/linux/module.h:683
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
```
In kernel/module.c (ffffffff811637ca)
Location: include/linux/module.h:683
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:add_kallsyms
  - kernel/module.c:layout_symtab
  - kernel/module.c:free_module
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
In kernel/livepatch/core.c (ffffffff811364be)
Location: include/linux/module.h:655
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
```
In kernel/module.c (ffffffff81164578)
Location: include/linux/module.h:655
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:add_kallsyms
  - kernel/module.c:layout_symtab
  - kernel/module.c:free_module
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
In kernel/livepatch/core.c (ffffffff811590be)
Location: include/linux/module.h:666
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
```
In kernel/module.c (ffffffff81189c7d)
Location: include/linux/module.h:666
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:add_kallsyms
  - kernel/module.c:layout_symtab
  - kernel/module.c:free_module
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
In kernel/livepatch/core.c (ffffffff81182678)
Location: include/linux/module.h:673
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
```
In kernel/module/main.c (ffffffff8118fb9d)
Location: include/linux/module.h:673
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
```
```
In kernel/module/kallsyms.c (ffffffff81191524)
Location: include/linux/module.h:673
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:add_kallsyms
  - kernel/module/kallsyms.c:layout_symtab
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
In kernel/livepatch/core.c (ffffffff811bd366)
Location: include/linux/module.h:680
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
```
In kernel/module/main.c (ffffffff811ccb37)
Location: include/linux/module.h:680
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
```
```
In kernel/module/kallsyms.c (ffffffff811ceb4c)
Location: include/linux/module.h:680
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:add_kallsyms
  - kernel/module/kallsyms.c:layout_symtab
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
In kernel/livepatch/core.c (ffffffff811cfb76)
Location: include/linux/module.h:746
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
```
In kernel/module/main.c (ffffffff811dffc5)
Location: include/linux/module.h:746
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:free_module
```
```
In kernel/module/kallsyms.c (ffffffff811e2dac)
Location: include/linux/module.h:746
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:add_kallsyms
  - kernel/module/kallsyms.c:layout_symtab
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
In kernel/livepatch/core.c (ffffffff811e47c6)
Location: include/linux/module.h:748
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
```
In kernel/module/main.c (ffffffff811f5cf5)
Location: include/linux/module.h:748
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:free_module
```
```
In kernel/module/kallsyms.c (ffffffff811f8b0c)
Location: include/linux/module.h:748
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:add_kallsyms
  - kernel/module/kallsyms.c:layout_symtab
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
Location: include/linux/module.h:678
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
In kernel/module.c (0)
Location: include/linux/module.h:678
Inline: True
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
In kernel/livepatch/core.c (c0000000001f0418)
Location: include/linux/module.h:673
Inline: True
```
```
In kernel/module.c (c00000000022ce18)
Location: include/linux/module.h:673
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:post_relocation
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:free_module
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
Location: include/linux/module.h:678
Inline: True
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
In kernel/livepatch/core.c (0)
Location: include/linux/module.h:673
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/module.h:673
Inline: True
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
In kernel/livepatch/core.c (0)
Location: include/linux/module.h:673
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/module.h:673
Inline: True
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
In kernel/livepatch/core.c (0)
Location: include/linux/module.h:673
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/module.h:673
Inline: True
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
In kernel/livepatch/core.c (0)
Location: include/linux/module.h:673
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/module.h:673
Inline: True
```
</details>
</li>
</ul>

## Differences
