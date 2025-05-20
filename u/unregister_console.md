# Function: <code>unregister_console</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d7f90)
Location: kernel/printk/printk.c:2653
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:register_console
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff810d7f90-ffffffff810d8085: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810dd6b0)
Location: kernel/printk/printk.c:2772
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:register_console
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff810dd6b0-ffffffff810dd7a2: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e3ce0)
Location: kernel/printk/printk.c:2598
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:register_console
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff810e3ce0-ffffffff810e3dd2: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e2c30)
Location: kernel/printk/printk.c:2572
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:register_console
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff810e2c30-ffffffff810e2d27: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810eab00)
Location: kernel/printk/printk.c:2560
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:register_console
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff810eab00-ffffffff810eabf7: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f4ea0)
Location: kernel/printk/printk.c:2729
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:register_console
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff810f4ea0-ffffffff810f4f66: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81100660)
Location: kernel/printk/printk.c:2739
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:register_console
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
```
**Symbols:**

```
ffffffff81100660-ffffffff81100726: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81108e42)
Location: kernel/printk/printk.c:2804
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:register_console
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
```
**Symbols:**

```
ffffffff81108e42-ffffffff81108f08: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81115222)
Location: kernel/printk/printk.c:2814
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:register_console
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
```
**Symbols:**

```
ffffffff81115222-ffffffff811152ea: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81120bd2)
Location: kernel/printk/printk.c:2862
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
```
**Symbols:**

```
ffffffff81120bd2-ffffffff81120ca6: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81be11e0)
Location: kernel/printk/printk.c:2943
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
```
**Symbols:**

```
ffffffff81be11e0-ffffffff81be12b4: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81bd3261)
Location: kernel/printk/printk.c:3007
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
```
**Symbols:**

```
ffffffff81bd3261-ffffffff81bd3335: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81cac261)
Location: kernel/printk/printk.c:3066
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
```
**Symbols:**

```
ffffffff81cac261-ffffffff81cac335: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81e5c797)
Location: kernel/printk/printk.c:3226
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/kgdb_nmi.c:kgdb_unregister_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
```
**Symbols:**

```
ffffffff81e5c797-ffffffff81e5c86c: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8118dac0)
Location: kernel/printk/printk.c:3483
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/kgdb_nmi.c:kgdb_unregister_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
```
**Symbols:**

```
ffffffff8118dac0-ffffffff8118dafd: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8119f270)
Location: kernel/printk/printk.c:3524
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/kgdb_nmi.c:kgdb_unregister_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
```
**Symbols:**

```
ffffffff8119f270-ffffffff8119f2ad: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811ae450)
Location: kernel/printk/printk.c:3611
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/kgdb_nmi.c:kgdb_unregister_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
```
**Symbols:**

```
ffffffff811ae450-ffffffff811ae48d: unregister_console (STB_GLOBAL)
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
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010176700)
Location: kernel/printk/printk.c:2814
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:register_console
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffff800010176700-ffff800010176800: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c85c8)
Location: kernel/printk/printk.c:2814
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:register_console
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - fs/pstore/platform.c:pstore_unregister
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
c03c85c8-c03c86b8: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001cff38)
Location: kernel/printk/printk.c:2814
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:register_console
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
c0000000001cff38-c0000000001d0070: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe0001119fc)
Location: kernel/printk/printk.c:2814
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:register_console
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffe0001119fc-ffffffe000111ad4: unregister_console (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110d802)
Location: kernel/printk/printk.c:2814
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:register_console
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff8110d802-ffffffff8110d8ca: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fe562)
Location: kernel/printk/printk.c:2814
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:register_console
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff810fe562-ffffffff810fe62a: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110b6f2)
Location: kernel/printk/printk.c:2814
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:register_console
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff8110b6f2-ffffffff8110b7ba: unregister_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int unregister_console(struct console *console);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81116bb2)
Location: kernel/printk/printk.c:2814
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:register_console
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
```
**Symbols:**

```
ffffffff81116bb2-ffffffff81116caa: unregister_console (STB_GLOBAL)
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
