# Function: <code>add_taint_module</code>

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
In kernel/module.c (ffffffff81108544)
Location: kernel/module.c:327
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff8110ff8f)
Location: kernel/module.c:329
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void add_taint_module(struct module *mod, unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81117847)
Location: kernel/module.c:332
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff81114850-ffffffff81114874: add_taint_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void add_taint_module(struct module *mod, unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81118e06)
Location: kernel/module.c:336
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff811157c0-ffffffff811157e4: add_taint_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void add_taint_module(struct module *mod, unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811243b2)
Location: kernel/module.c:346
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff81120d70-ffffffff81120d94: add_taint_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void add_taint_module(struct module *mod, unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811328e0)
Location: kernel/module.c:345
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff8112e6a0-ffffffff8112e6c4: add_taint_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void add_taint_module(struct module *mod, unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113e20f)
Location: kernel/module.c:327
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff8113a080-ffffffff8113a0a4: add_taint_module (STB_LOCAL)
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
In kernel/module.c (ffffffff81149cfa)
Location: kernel/module.c:323
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff8115596c)
Location: kernel/module.c:325
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
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
In kernel/module.c (ffffffff81166b5b)
Location: kernel/module.c:328
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:check_module_license_and_versions
  - kernel/module.c:check_module_license_and_versions
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:set_license
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
In kernel/module.c (ffffffff811632ef)
Location: kernel/module.c:330
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:check_module_license_and_versions
  - kernel/module.c:check_module_license_and_versions
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:set_license
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
In kernel/module.c (ffffffff81163f0c)
Location: kernel/module.c:328
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
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
In kernel/module.c (ffffffff81189600)
Location: kernel/module.c:329
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void add_taint_module(struct module *mod, unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff8118f3ad)
Location: kernel/module/main.c:158
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
Direct callers:
  - kernel/module/main.c:check_modinfo
```
**Symbols:**

```
ffffffff8118b730-ffffffff8118b75e: add_taint_module (STB_LOCAL)
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
In kernel/module/main.c (ffffffff811cc2bf)
Location: kernel/module/main.c:156
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
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
In kernel/module/main.c (ffffffff811dbf48)
Location: kernel/module/main.c:163
Inline: True
Inline callers:
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
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
In kernel/module/main.c (ffffffff811f1d98)
Location: kernel/module/main.c:163
Inline: True
Inline callers:
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
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
In kernel/module.c (ffff8000101c4d50)
Location: kernel/module.c:325
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (c040c068)
Location: kernel/module.c:325
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (c00000000022c154)
Location: kernel/module.c:325
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffe0001455ae)
Location: kernel/module.c:325
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff8114df8c)
Location: kernel/module.c:325
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
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
In kernel/module.c (ffffffff8114123c)
Location: kernel/module.c:325
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
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
In kernel/module.c (ffffffff8114be3c)
Location: kernel/module.c:325
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
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
In kernel/module.c (ffffffff81158b27)
Location: kernel/module.c:325
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
