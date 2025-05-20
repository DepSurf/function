# Function: <code>uart_try_toggle_sysrq</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool uart_try_toggle_sysrq(struct uart_port *port, unsigned int ch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81756b50)
Location: drivers/tty/serial/serial_core.c:3172
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff81756b50-ffffffff81756b5d: uart_try_toggle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool uart_try_toggle_sysrq(struct uart_port *port, unsigned int ch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81771cd0)
Location: drivers/tty/serial/serial_core.c:3179
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff81771cd0-ffffffff81771cdd: uart_try_toggle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool uart_try_toggle_sysrq(struct uart_port *port, unsigned int ch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81755790)
Location: drivers/tty/serial/serial_core.c:3176
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff81755790-ffffffff8175579d: uart_try_toggle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool uart_try_toggle_sysrq(struct uart_port *port, unsigned int ch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817d8e50)
Location: drivers/tty/serial/serial_core.c:3193
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff817d8e50-ffffffff817d8e5d: uart_try_toggle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool uart_try_toggle_sysrq(struct uart_port *port, unsigned int ch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff819172e0)
Location: drivers/tty/serial/serial_core.c:3242
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff819172e0-ffffffff819172f1: uart_try_toggle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool uart_try_toggle_sysrq(struct uart_port *port, unsigned int ch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a72770)
Location: drivers/tty/serial/serial_core.c:3379
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff81a72770-ffffffff81a72781: uart_try_toggle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool uart_try_toggle_sysrq(struct uart_port *port, unsigned int ch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81abd030)
Location: drivers/tty/serial/serial_core.c:3531
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff81abd030-ffffffff81abd041: uart_try_toggle_sysrq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool uart_try_toggle_sysrq(struct uart_port *port, u8 ch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81b0fe20)
Location: drivers/tty/serial/serial_core.c:3568
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff81b0fe20-ffffffff81b0fe31: uart_try_toggle_sysrq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
</details>
</li>
</ul>
