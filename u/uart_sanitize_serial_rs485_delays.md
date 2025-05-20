# Function: <code>uart_sanitize_serial_rs485_delays</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uart_sanitize_serial_rs485_delays(struct uart_port *port, struct serial_rs485 *rs485);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a72fa0)
Location: drivers/tty/serial/serial_core.c:1317
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_sanitize_serial_rs485
```
**Symbols:**

```
ffffffff81a72fa0-ffffffff81a73133: uart_sanitize_serial_rs485_delays (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uart_sanitize_serial_rs485_delays(struct uart_port *port, struct serial_rs485 *rs485);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81abd860)
Location: drivers/tty/serial/serial_core.c:1338
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_sanitize_serial_rs485
```
**Symbols:**

```
ffffffff81abd860-ffffffff81abd9f3: uart_sanitize_serial_rs485_delays (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uart_sanitize_serial_rs485_delays(struct uart_port *port, struct serial_rs485 *rs485);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81b10650)
Location: drivers/tty/serial/serial_core.c:1332
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_rs485_mode
  - drivers/tty/serial/serial_core.c:uart_sanitize_serial_rs485
```
**Symbols:**

```
ffffffff81b10650-ffffffff81b107e3: uart_sanitize_serial_rs485_delays (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
