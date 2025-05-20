# Function: <code>uart_insert_char</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81501880)
Location: drivers/tty/serial/serial_core.c:2922
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81501880-ffffffff815019df: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81552230)
Location: drivers/tty/serial/serial_core.c:3024
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81552230-ffffffff8155238f: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8157ee30)
Location: drivers/tty/serial/serial_core.c:2991
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff8157ee30-ffffffff8157ef8f: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815935f0)
Location: drivers/tty/serial/serial_core.c:2995
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff815935f0-ffffffff81593705: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815f8100)
Location: drivers/tty/serial/serial_core.c:2998
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff815f8100-ffffffff815f8215: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81630f60)
Location: drivers/tty/serial/serial_core.c:2995
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81630f60-ffffffff8163108d: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164f120)
Location: drivers/tty/serial/serial_core.c:3056
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff8164f120-ffffffff8164f24d: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81683e60)
Location: drivers/tty/serial/serial_core.c:3063
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81683e60-ffffffff81683f8f: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816a6510)
Location: drivers/tty/serial/serial_core.c:3065
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff816a6510-ffffffff816a663f: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817581d0)
Location: drivers/tty/serial/serial_core.c:3129
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff817581d0-ffffffff81758304: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81773290)
Location: drivers/tty/serial/serial_core.c:3136
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff81773290-ffffffff817733c4: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81756d00)
Location: drivers/tty/serial/serial_core.c:3133
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff81756d00-ffffffff81756e2d: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817da5e0)
Location: drivers/tty/serial/serial_core.c:3150
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff817da5e0-ffffffff817da70d: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81919380)
Location: drivers/tty/serial/serial_core.c:3199
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff81919380-ffffffff819194d5: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:3336
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff82095c5e-ffffffff82095ce6: uart_insert_char.cold (STB_LOCAL)
ffffffff81a75140-ffffffff81a752d4: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:3488
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff82116ae3-ffffffff82116b6b: uart_insert_char.cold (STB_LOCAL)
ffffffff81abf940-ffffffff81abface: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, u8 ch, u8 flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:3525
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff821f4836-ffffffff821f48c5: uart_insert_char.cold (STB_LOCAL)
ffffffff81b12780-ffffffff81b1294a: uart_insert_char (STB_GLOBAL)
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
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffff80001087dd60)
Location: drivers/tty/serial/serial_core.c:3065
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffff80001087dd60-ffff80001087dec4: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c097fd28)
Location: drivers/tty/serial/serial_core.c:3065
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
```
**Symbols:**

```
c097fd28-c097fe58: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c000000000925e80)
Location: drivers/tty/serial/serial_core.c:3065
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
c000000000925e80-c000000000926074: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffe00054cd34)
Location: drivers/tty/serial/serial_core.c:3065
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sifive.c:sifive_serial_irq
```
**Symbols:**

```
ffffffe00054cd34-ffffffe00054ce56: uart_insert_char (STB_GLOBAL)
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
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8166bf70)
Location: drivers/tty/serial/serial_core.c:3065
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff8166bf70-ffffffff8166c09f: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164b0d0)
Location: drivers/tty/serial/serial_core.c:3065
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff8164b0d0-ffffffff8164b1ff: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8169a350)
Location: drivers/tty/serial/serial_core.c:3065
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff8169a350-ffffffff8169a47f: uart_insert_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uart_insert_char(struct uart_port *port, unsigned int status, unsigned int overrun, unsigned int ch, unsigned int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816b4f50)
Location: drivers/tty/serial/serial_core.c:3065
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff816b4f50-ffffffff816b507f: uart_insert_char (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int ch</code> ➡️ <code>u8 ch</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int flag</code> ➡️ <code>u8 flag</code>
</li>
</ul>
</details>
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
