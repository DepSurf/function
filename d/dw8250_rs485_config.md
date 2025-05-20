# Function: <code>dw8250_rs485_config</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dw8250_rs485_config(struct uart_port *p, struct serial_rs485 *rs485);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff81926320)
Location: drivers/tty/serial/8250/8250_dwlib.c:88
Inline: False
```
**Symbols:**

```
ffffffff81926320-ffffffff819264c9: dw8250_rs485_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dw8250_rs485_config(struct uart_port *p, struct ktermios *termios, struct serial_rs485 *rs485);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff81a83140)
Location: drivers/tty/serial/8250/8250_dwlib.c:180
Inline: False
```
**Symbols:**

```
ffffffff81a83140-ffffffff81a83450: dw8250_rs485_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dw8250_rs485_config(struct uart_port *p, struct ktermios *termios, struct serial_rs485 *rs485);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff81ace7a0)
Location: drivers/tty/serial/8250/8250_dwlib.c:180
Inline: False
```
**Symbols:**

```
ffffffff81ace7a0-ffffffff81aceaac: dw8250_rs485_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dw8250_rs485_config(struct uart_port *p, struct ktermios *termios, struct serial_rs485 *rs485);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff81b21860)
Location: drivers/tty/serial/8250/8250_dwlib.c:180
Inline: False
```
**Symbols:**

```
ffffffff81b21860-ffffffff81b21b6c: dw8250_rs485_config (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ktermios *termios</code>
</li>
<li>
<b>Param reordered. </b>
<code>p, rs485</code> ➡️ <code>p, termios, rs485</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
