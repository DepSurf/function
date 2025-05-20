# Function: <code>register_console</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d8090)
Location: kernel/printk/printk.c:2491
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:early_console_register
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
```
**Symbols:**

```
ffffffff810d8090-ffffffff810d8404: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810dd7b0)
Location: kernel/printk/printk.c:2610
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:early_console_register
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
```
**Symbols:**

```
ffffffff810dd7b0-ffffffff810ddb24: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e3de0)
Location: kernel/printk/printk.c:2437
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:early_console_register
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
```
**Symbols:**

```
ffffffff810e3de0-ffffffff810e4148: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e2d30)
Location: kernel/printk/printk.c:2410
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:early_console_register
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff810e2d30-ffffffff810e30ad: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810eac00)
Location: kernel/printk/printk.c:2398
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:early_console_register
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff810eac00-ffffffff810eaf86: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2567
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:early_console_register
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_init
```
**Symbols:**

```
ffffffff810f4f66-ffffffff810f4fd8: register_console.cold.35 (STB_LOCAL)
ffffffff810f2f10-ffffffff810f324a: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2573
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:early_console_register
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_register_console
```
**Symbols:**

```
ffffffff81100726-ffffffff81100783: register_console.cold.36 (STB_LOCAL)
ffffffff810fe5a0-ffffffff810fe8d1: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2638
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:early_console_register
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_register_console
```
**Symbols:**

```
ffffffff81108f08-ffffffff81108f67: register_console.cold (STB_LOCAL)
ffffffff81106c90-ffffffff81106fdd: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2648
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:early_console_register
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_register_console
```
**Symbols:**

```
ffffffff811152ea-ffffffff81115349: register_console.cold (STB_LOCAL)
ffffffff81113020-ffffffff81113374: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111f220)
Location: kernel/printk/printk.c:2725
Inline: True
Direct callers:
  - arch/x86/kernel/early_printk.c:early_console_register
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_register_console
```
**Symbols:**

```
ffffffff8111efa0-ffffffff8111f215: register_console.part.0 (STB_LOCAL)
ffffffff81120ca6-ffffffff81120d05: register_console.part.0.cold (STB_LOCAL)
ffffffff8111f220-ffffffff8111f263: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81119bb0)
Location: kernel/printk/printk.c:2807
Inline: True
Direct callers:
  - arch/x86/kernel/early_printk.c:early_console_register
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/debug/debug_core.c:opt_kgdb_con
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_register_console
```
**Symbols:**

```
ffffffff81119940-ffffffff81119ba2: register_console.part.0 (STB_LOCAL)
ffffffff81be12b4-ffffffff81be1313: register_console.part.0.cold (STB_LOCAL)
ffffffff81119bb0-ffffffff81119bf3: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111a6e0)
Location: kernel/printk/printk.c:2870
Inline: True
Direct callers:
  - arch/x86/kernel/early_printk.c:early_console_register
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/debug/debug_core.c:opt_kgdb_con
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_register_console
```
**Symbols:**

```
ffffffff8111a4c0-ffffffff8111a6d1: register_console.part.0 (STB_LOCAL)
ffffffff81bd3335-ffffffff81bd3394: register_console.part.0.cold (STB_LOCAL)
ffffffff8111a6e0-ffffffff8111a723: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8113adb0)
Location: kernel/printk/printk.c:2930
Inline: True
Direct callers:
  - arch/x86/kernel/early_printk.c:early_console_register
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/debug/debug_core.c:opt_kgdb_con
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_register_console
```
**Symbols:**

```
ffffffff8113ab50-ffffffff8113ada9: register_console.part.0 (STB_LOCAL)
ffffffff81cac335-ffffffff81cac411: register_console.part.0.cold (STB_LOCAL)
ffffffff8113adb0-ffffffff8113adf3: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115d860)
Location: kernel/printk/printk.c:3104
Inline: True
Direct callers:
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/debug/debug_core.c:opt_kgdb_con
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_init
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_register_console
```
**Symbols:**

```
ffffffff8115d620-ffffffff8115d853: register_console.part.0 (STB_LOCAL)
ffffffff81e5c86c-ffffffff81e5c8cb: register_console.part.0.cold (STB_LOCAL)
ffffffff8115d860-ffffffff8115d8b7: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:3312
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/debug/debug_core.c:opt_kgdb_con
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/earlycon.c:register_earlycon
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_init
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_register_console
```
**Symbols:**

```
ffffffff82058a7a-ffffffff82058a8f: register_console.cold (STB_LOCAL)
ffffffff811904e0-ffffffff8119098f: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:3353
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/debug/debug_core.c:opt_kgdb_con
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/earlycon.c:register_earlycon
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_init
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_register_console
```
**Symbols:**

```
ffffffff820d7320-ffffffff820d7335: register_console.cold (STB_LOCAL)
ffffffff811a1e00-ffffffff811a2293: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:3422
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - arch/x86/kernel/early_printk.c:setup_early_printk
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - kernel/debug/debug_core.c:opt_kgdb_con
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/earlycon.c:register_earlycon
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_init
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_register_console
```
**Symbols:**

```
ffffffff821b26c7-ffffffff821b26dc: register_console.cold (STB_LOCAL)
ffffffff811b2b50-ffffffff811b308f: register_console (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff8000101744f8)
Location: kernel/printk/printk.c:2648
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_init
  - drivers/tty/serial/meson_uart.c:meson_serial_console_init
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_init
  - drivers/tty/serial/owl-uart.c:owl_uart_console_init
```
**Symbols:**

```
ffff8000101744f8-ffff80001017484c: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c66fc)
Location: kernel/printk/printk.c:2648
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - fs/pstore/platform.c:pstore_register
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_init
  - drivers/tty/serial/meson_uart.c:meson_serial_console_init
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_init
  - drivers/tty/serial/owl-uart.c:owl_uart_console_init
  - drivers/tty/serial/rda-uart.c:rda_uart_console_init
```
**Symbols:**

```
c03c66fc-c03c6ab4: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001cd3d0)
Location: kernel/printk/printk.c:2648
Inline: False
Direct callers:
  - arch/powerpc/kernel/udbg.c:register_early_udbg_console
  - kernel/debug/debug_core.c:kgdb_register_io_module
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvsi.c:hvsi_console_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_init
```
**Symbols:**

```
c0000000001cd3d0-c0000000001cda64: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe00010f88a)
Location: kernel/printk/printk.c:2648
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:of_setup_earlycon
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_init
  - drivers/tty/serial/sifive.c:sifive_console_init
```
**Symbols:**

```
ffffffe00010f88a-ffffffe00010fb9c: register_console (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2648
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:early_console_register
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_init
```
**Symbols:**

```
ffffffff8110d8ca-ffffffff8110d929: register_console.cold (STB_LOCAL)
ffffffff8110b600-ffffffff8110b954: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2648
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:early_console_register
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_init
```
**Symbols:**

```
ffffffff810fe62a-ffffffff810fe689: register_console.cold (STB_LOCAL)
ffffffff810fc460-ffffffff810fc7a7: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2648
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:early_console_register
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_init
```
**Symbols:**

```
ffffffff8110b7ba-ffffffff8110b819: register_console.cold (STB_LOCAL)
ffffffff811094f0-ffffffff81109844: register_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void register_console(struct console *newcon);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2648
Inline: False
Direct callers:
  - arch/x86/kernel/early_printk.c:early_console_register
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/hvc/hvc_console.c:hvc_console_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_register_console
```
**Symbols:**

```
ffffffff81116caa-ffffffff81116d09: register_console.cold (STB_LOCAL)
ffffffff81114860-ffffffff81114bf2: register_console (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
