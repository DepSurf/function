# Function: <code>serial8250_setup_port</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct uart_8250_port *serial8250_setup_port(int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff81ac4b10)
Location: drivers/tty/serial/8250/8250_core.c:491
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_setup
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
```
**Symbols:**

```
ffffffff81ac4b10-ffffffff81ac4be4: serial8250_setup_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct uart_8250_port *serial8250_setup_port(int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff81b17b10)
Location: drivers/tty/serial/8250/8250_core.c:491
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_console_setup
  - drivers/tty/serial/8250/8250_core.c:serial8250_isa_init_ports
```
**Symbols:**

```
ffffffff81b17b10-ffffffff81b17be4: serial8250_setup_port (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
