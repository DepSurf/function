# Function: <code>offset_to_ptr</code>

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
In init/main.c (ffffffff828832b9)
Location: include/linux/compiler.h:302
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff828ada2b)
Location: include/linux/compiler.h:302
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
```
In kernel/module.c (ffffffff8113fbac)
Location: include/linux/compiler.h:302
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
  - kernel/module.c:cmp_name
```
```
In kernel/tracepoint.c (ffffffff8117d514)
Location: include/linux/compiler.h:302
Inline: True
Inline callers:
  - kernel/tracepoint.c:for_each_kernel_tracepoint
  - kernel/tracepoint.c:tracepoint_module_notify
```
```
In drivers/pci/quirks.c (ffffffff81542b88)
Location: include/linux/compiler.h:302
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
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
In init/main.c (ffffffff8289a30f)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff828c63e5)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
```
In kernel/module.c (ffffffff8114aef2)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
  - kernel/module.c:cmp_name
```
```
In kernel/tracepoint.c (ffffffff8118a6bb)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - kernel/tracepoint.c:for_each_kernel_tracepoint
  - kernel/tracepoint.c:tracepoint_module_notify
```
```
In drivers/pci/quirks.c (ffffffff8157230a)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
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
In init/main.c (ffffffff8289d2f4)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff828cea12)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
```
In kernel/module.c (ffffffff81156b64)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
  - kernel/module.c:resolve_symbol
  - kernel/module.c:cmp_name
```
```
In kernel/tracepoint.c (ffffffff811965cb)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - kernel/tracepoint.c:for_each_kernel_tracepoint
  - kernel/tracepoint.c:tracepoint_module_notify
```
```
In drivers/pci/quirks.c (ffffffff8159395a)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
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
In init/main.c (ffffffff82cc393c)
Location: include/linux/compiler.h:350
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff82cefe78)
Location: include/linux/compiler.h:350
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
```
In kernel/module.c (ffffffff81167706)
Location: include/linux/compiler.h:350
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:simplify_symbols
  - kernel/module.c:verify_exported_symbols
  - kernel/module.c:verify_exported_symbols
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
  - kernel/module.c:resolve_symbol
  - kernel/module.c:cmp_name
```
```
In kernel/tracepoint.c (ffffffff811ab5fb)
Location: include/linux/compiler.h:350
Inline: True
Inline callers:
  - kernel/tracepoint.c:for_each_kernel_tracepoint
  - kernel/tracepoint.c:tracepoint_module_notify
```
```
In drivers/pci/quirks.c (ffffffff81641eed)
Location: include/linux/compiler.h:350
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
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
In init/main.c (ffffffff82fafa4e)
Location: include/linux/compiler.h:230
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff82fdc86b)
Location: include/linux/compiler.h:230
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
```
In kernel/module.c (ffffffff81163f01)
Location: include/linux/compiler.h:230
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:simplify_symbols
  - kernel/module.c:verify_exported_symbols
  - kernel/module.c:verify_exported_symbols
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
  - kernel/module.c:resolve_symbol
  - kernel/module.c:cmp_name
```
```
In kernel/tracepoint.c (ffffffff811a8c1b)
Location: include/linux/compiler.h:230
Inline: True
Inline callers:
  - kernel/tracepoint.c:for_each_kernel_tracepoint
```
```
In drivers/pci/quirks.c (ffffffff8166834d)
Location: include/linux/compiler.h:230
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
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
In init/main.c (ffffffff831b9ab0)
Location: include/linux/compiler.h:232
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff831e75ca)
Location: include/linux/compiler.h:232
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
```
In kernel/module.c (ffffffff81164cb1)
Location: include/linux/compiler.h:232
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:complete_formation
  - kernel/module.c:complete_formation
  - kernel/module.c:simplify_symbols
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
  - kernel/module.c:resolve_symbol
  - kernel/module.c:cmp_name
```
```
In kernel/tracepoint.c (ffffffff811a94bb)
Location: include/linux/compiler.h:232
Inline: True
Inline callers:
  - kernel/tracepoint.c:for_each_kernel_tracepoint
```
```
In drivers/pci/quirks.c (ffffffff8164a856)
Location: include/linux/compiler.h:232
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_device
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
In init/main.c (ffffffff83299e8c)
Location: include/linux/compiler.h:239
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff832cb755)
Location: include/linux/compiler.h:239
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
```
In kernel/module.c (ffffffff8118a4d1)
Location: include/linux/compiler.h:239
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:complete_formation
  - kernel/module.c:complete_formation
  - kernel/module.c:simplify_symbols
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
  - kernel/module.c:resolve_symbol
  - kernel/module.c:cmp_name
```
```
In kernel/tracepoint.c (ffffffff811d30ab)
Location: include/linux/compiler.h:239
Inline: True
Inline callers:
  - kernel/tracepoint.c:for_each_kernel_tracepoint
```
```
In drivers/pci/quirks.c (ffffffff816be33e)
Location: include/linux/compiler.h:239
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_device
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
In init/main.c (ffffffff8344808f)
Location: include/linux/compiler.h:232
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff8347ee4d)
Location: include/linux/compiler.h:232
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
```
In kernel/module/main.c (ffffffff8118fab9)
Location: include/linux/compiler.h:232
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:simplify_symbols
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:resolve_symbol
  - kernel/module/main.c:resolve_symbol
  - kernel/module/main.c:cmp_name
```
```
In kernel/module/kallsyms.c (ffffffff81191b59)
Location: include/linux/compiler.h:232
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:module_get_kallsym
```
```
In kernel/tracepoint.c (ffffffff81207adb)
Location: include/linux/compiler.h:232
Inline: True
Inline callers:
  - kernel/tracepoint.c:for_each_kernel_tracepoint
  - kernel/tracepoint.c:tracepoint_module_notify
```
```
In drivers/pci/quirks.c (ffffffff817e4272)
Location: include/linux/compiler.h:232
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_device
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
In init/main.c (ffffffff83e619ba)
Location: include/linux/compiler.h:224
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff83eaaf98)
Location: include/linux/compiler.h:224
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
```
In kernel/module/main.c (ffffffff811cc646)
Location: include/linux/compiler.h:224
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:simplify_symbols
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:resolve_symbol
  - kernel/module/main.c:resolve_symbol
  - kernel/module/main.c:cmp_name
```
```
In kernel/module/kallsyms.c (ffffffff811cf209)
Location: include/linux/compiler.h:224
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:module_get_kallsym
```
```
In kernel/tracepoint.c (ffffffff8124ff2b)
Location: include/linux/compiler.h:224
Inline: True
Inline callers:
  - kernel/tracepoint.c:for_each_kernel_tracepoint
  - kernel/tracepoint.c:tracepoint_module_notify
```
```
In drivers/pci/quirks.c (ffffffff81908882)
Location: include/linux/compiler.h:224
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_device
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
In init/main.c (ffffffff83681dda)
Location: include/linux/compiler.h:223
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff836cff58)
Location: include/linux/compiler.h:223
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
```
In kernel/module/main.c (ffffffff811dfb07)
Location: include/linux/compiler.h:223
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:simplify_symbols
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:resolve_symbol
  - kernel/module/main.c:resolve_symbol
  - kernel/module/main.c:cmp_name
```
```
In kernel/module/kallsyms.c (ffffffff811e33a9)
Location: include/linux/compiler.h:223
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:module_get_kallsym
```
```
In kernel/tracepoint.c (ffffffff812672db)
Location: include/linux/compiler.h:223
Inline: True
Inline callers:
  - kernel/tracepoint.c:for_each_kernel_tracepoint
  - kernel/tracepoint.c:tracepoint_module_notify
```
```
In drivers/pci/quirks.c (ffffffff8194beb0)
Location: include/linux/compiler.h:223
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_device
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
In init/main.c (ffffffff838b0e0a)
Location: include/linux/compiler.h:220
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:do_initcalls
```
```
In kernel/printk/printk.c (ffffffff83901368)
Location: include/linux/compiler.h:220
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
```
In kernel/module/main.c (ffffffff811f5837)
Location: include/linux/compiler.h:220
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:simplify_symbols
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:resolve_symbol
  - kernel/module/main.c:resolve_symbol
  - kernel/module/main.c:cmp_name
```
```
In kernel/module/kallsyms.c (ffffffff811f9109)
Location: include/linux/compiler.h:220
Inline: True
Inline callers:
  - kernel/module/kallsyms.c:module_get_kallsym
```
```
In kernel/tracepoint.c (ffffffff8128126b)
Location: include/linux/compiler.h:220
Inline: True
Inline callers:
  - kernel/tracepoint.c:for_each_kernel_tracepoint
  - kernel/tracepoint.c:tracepoint_module_notify
```
```
In drivers/pci/quirks.c (ffffffff81995180)
Location: include/linux/compiler.h:220
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_device
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
In init/main.c (ffff8000114312c0)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffff800011446300)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
```
In kernel/module.c (ffff8000101c5fc0)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
  - kernel/module.c:resolve_symbol
  - kernel/module.c:cmp_name
```
```
In kernel/tracepoint.c (ffff80001020e608)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - kernel/tracepoint.c:for_each_kernel_tracepoint
  - kernel/tracepoint.c:tracepoint_module_notify
```
```
In drivers/pci/quirks.c (ffff8000106fa970)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
```
</details>
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8288b2f4)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff828b770a)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
```
In kernel/module.c (ffffffff8114f184)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
  - kernel/module.c:resolve_symbol
  - kernel/module.c:cmp_name
```
```
In kernel/tracepoint.c (ffffffff8118ebeb)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - kernel/tracepoint.c:for_each_kernel_tracepoint
  - kernel/tracepoint.c:tracepoint_module_notify
```
```
In drivers/pci/quirks.c (ffffffff815877ea)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
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
In init/main.c (ffffffff82889271)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff828af98a)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
```
In kernel/module.c (ffffffff81142434)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
  - kernel/module.c:resolve_symbol
  - kernel/module.c:cmp_name
```
```
In kernel/tracepoint.c (ffffffff81181d6b)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - kernel/tracepoint.c:for_each_kernel_tracepoint
  - kernel/tracepoint.c:tracepoint_module_notify
```
```
In drivers/pci/quirks.c (ffffffff8157659a)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
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
In init/main.c (ffffffff8289e2f4)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff828ca646)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
```
In kernel/module.c (ffffffff8114d034)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
  - kernel/module.c:resolve_symbol
  - kernel/module.c:cmp_name
```
```
In kernel/tracepoint.c (ffffffff8118c9bb)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - kernel/tracepoint.c:for_each_kernel_tracepoint
  - kernel/tracepoint.c:tracepoint_module_notify
```
```
In drivers/pci/quirks.c (ffffffff815876aa)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
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
In init/main.c (ffffffff8289e2f9)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
```
```
In kernel/printk/printk.c (ffffffff828cfa11)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_init
```
```
In kernel/module.c (ffffffff81159d84)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - kernel/module.c:module_get_kallsym
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
  - kernel/module.c:resolve_symbol
  - kernel/module.c:cmp_name
```
```
In kernel/tracepoint.c (ffffffff8119a34b)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - kernel/tracepoint.c:for_each_kernel_tracepoint
  - kernel/tracepoint.c:tracepoint_module_notify
```
```
In drivers/pci/quirks.c (ffffffff815a1b5a)
Location: include/linux/compiler.h:308
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
```
</details>
</li>
</ul>

## Differences
