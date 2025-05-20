# Function: <code>tty_port_tty_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff814eba60)
Location: drivers/tty/tty_port.c:169
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_tty_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff814eba60-ffffffff814ebae2: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8153c960)
Location: drivers/tty/tty_port.c:169
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_wakeup
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff8153c960-ffffffff8153c9e2: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81568fb0)
Location: drivers/tty/tty_port.c:169
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_wakeup
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff81568fb0-ffffffff81569032: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8157b980)
Location: drivers/tty/tty_port.c:282
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff8157b980-ffffffff8157b9c1: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff815e10e0)
Location: drivers/tty/tty_port.c:283
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff815e10e0-ffffffff815e1127: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8161a370)
Location: drivers/tty/tty_port.c:283
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff8161a370-ffffffff8161a3b7: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff816375f0)
Location: drivers/tty/tty_port.c:282
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff816375f0-ffffffff81637637: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8166b880)
Location: drivers/tty/tty_port.c:282
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff8166b880-ffffffff8166b8cd: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8168df20)
Location: drivers/tty/tty_port.c:283
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff8168df20-ffffffff8168df6d: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8173fa30)
Location: drivers/tty/tty_port.c:283
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff8173fa30-ffffffff8173faab: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8175b8b0)
Location: drivers/tty/tty_port.c:283
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff8175b8b0-ffffffff8175b92b: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8173f750)
Location: drivers/tty/tty_port.c:284
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff8173f750-ffffffff8173f7cb: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff817bffb0)
Location: drivers/tty/tty_port.c:284
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff817bffb0-ffffffff817c002b: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff818fc6f0)
Location: drivers/tty/tty_port.c:301
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff818fc6f0-ffffffff818fc76f: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81a55d30)
Location: drivers/tty/tty_port.c:322
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff81a55d30-ffffffff81a55db0: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81aa0310)
Location: drivers/tty/tty_port.c:322
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff81aa0310-ffffffff81aa0390: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81af2d60)
Location: drivers/tty/tty_port.c:322
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff81af2d60-ffffffff81af2de0: tty_port_tty_get (STB_GLOBAL)
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
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffff80001085e308)
Location: drivers/tty/tty_port.c:283
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffff80001085e308-ffff80001085e3c0: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (c0965c1c)
Location: drivers/tty/tty_port.c:283
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
c0965c1c-c0965c6c: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (c0000000008fcf30)
Location: drivers/tty/tty_port.c:283
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvsi_lib.c:hvsilib_open
  - drivers/tty/hvc/hvsi.c:hvsi_interrupt
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
c0000000008fcf30-c0000000008fcfb4: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffe000536870)
Location: drivers/tty/tty_port.c:283
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffe000536870-ffffffe0005368be: tty_port_tty_get (STB_GLOBAL)
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
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff816539a0)
Location: drivers/tty/tty_port.c:283
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff816539a0-ffffffff816539ed: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81633d80)
Location: drivers/tty/tty_port.c:283
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff81633d80-ffffffff81633dcd: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81681d60)
Location: drivers/tty/tty_port.c:283
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff81681d60-ffffffff81681dad: tty_port_tty_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tty_struct *tty_port_tty_get(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8169c3a0)
Location: drivers/tty/tty_port.c:283
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_tty_hangup
  - drivers/tty/tty_port.c:tty_port_default_wakeup
  - drivers/tty/hvc/hvc_console.c:hvc_remove
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/hvc/hvc_console.c:hvc_set_winsz
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup
```
**Symbols:**

```
ffffffff8169c3a0-ffffffff8169c3ed: tty_port_tty_get (STB_GLOBAL)
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
