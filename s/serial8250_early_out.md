# Function: <code>serial8250_early_out</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff81fa75b1)
Location: drivers/tty/serial/8250/8250_early.c:56
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/8250/8250_early.c:serial_putc
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
```
**Symbols:**

```
ffffffff81fa75b1-ffffffff81fa7608: serial8250_early_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff81fd3a07)
Location: drivers/tty/serial/8250/8250_early.c:60
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff81fd3a07-ffffffff81fd3a69: serial8250_early_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff820113c7)
Location: drivers/tty/serial/8250/8250_early.c:60
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff820113c7-ffffffff82011429: serial8250_early_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff820f2ea1)
Location: drivers/tty/serial/8250/8250_early.c:63
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff820f2ea1-ffffffff820f2f0a: serial8250_early_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff81604aa0)
Location: drivers/tty/serial/8250/8250_early.c:60
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff81604aa0-ffffffff81604b16: serial8250_early_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff8163dd30)
Location: drivers/tty/serial/8250/8250_early.c:60
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff8163dd30-ffffffff8163dda5: serial8250_early_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff8165bf60)
Location: drivers/tty/serial/8250/8250_early.c:60
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff8165bf60-ffffffff8165bfec: serial8250_early_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff81691650)
Location: drivers/tty/serial/8250/8250_early.c:60
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff81691650-ffffffff816916dd: serial8250_early_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff816b4140)
Location: drivers/tty/serial/8250/8250_early.c:60
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff816b4140-ffffffff816b41cd: serial8250_early_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff817679e0)
Location: drivers/tty/serial/8250/8250_early.c:60
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:init_port
  - drivers/tty/serial/8250/8250_early.c:init_port
  - drivers/tty/serial/8250/8250_early.c:init_port
  - drivers/tty/serial/8250/8250_early.c:init_port
  - drivers/tty/serial/8250/8250_early.c:init_port
  - drivers/tty/serial/8250/8250_early.c:init_port
  - drivers/tty/serial/8250/8250_early.c:init_port
  - drivers/tty/serial/8250/8250_early.c:init_port
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff817679e0-ffffffff81767a6a: serial8250_early_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff81782740)
Location: drivers/tty/serial/8250/8250_early.c:60
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:init_port
  - drivers/tty/serial/8250/8250_early.c:init_port
  - drivers/tty/serial/8250/8250_early.c:init_port
  - drivers/tty/serial/8250/8250_early.c:init_port
  - drivers/tty/serial/8250/8250_early.c:init_port
  - drivers/tty/serial/8250/8250_early.c:init_port
  - drivers/tty/serial/8250/8250_early.c:init_port
  - drivers/tty/serial/8250/8250_early.c:init_port
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff81782740-ffffffff817827ca: serial8250_early_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff81766040)
Location: drivers/tty/serial/8250/8250_early.c:60
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff81766040-ffffffff817660ca: serial8250_early_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (0)
Location: drivers/tty/serial/8250/8250_early.c:60
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff817ea9b0-ffffffff817eaa9f: serial8250_early_out (STB_LOCAL)
ffffffff81cfa337-ffffffff81cfa358: serial8250_early_out.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (0)
Location: drivers/tty/serial/8250/8250_early.c:60
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff8192a770-ffffffff8192a891: serial8250_early_out (STB_LOCAL)
ffffffff81ec2568-ffffffff81ec258c: serial8250_early_out.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (0)
Location: drivers/tty/serial/8250/8250_early.c:60
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff81a87bc0-ffffffff81a87ce1: serial8250_early_out (STB_LOCAL)
ffffffff8209615e-ffffffff82096182: serial8250_early_out.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (0)
Location: drivers/tty/serial/8250/8250_early.c:57
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff81ad2f80-ffffffff81ad307a: serial8250_early_out (STB_LOCAL)
ffffffff82116fef-ffffffff82117013: serial8250_early_out.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (0)
Location: drivers/tty/serial/8250/8250_early.c:56
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff81b229c0-ffffffff81b22aba: serial8250_early_out (STB_LOCAL)
ffffffff821f4d0f-ffffffff821f4d33: serial8250_early_out.cold (STB_LOCAL)
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
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffff800010890588)
Location: drivers/tty/serial/8250/8250_early.c:60
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffff800010890588-ffff8000108906b0: serial8250_early_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (c098ce0c)
Location: drivers/tty/serial/8250/8250_early.c:60
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
c098ce0c-c098cefc: serial8250_early_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (c00000000093a400)
Location: drivers/tty/serial/8250/8250_early.c:60
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
c00000000093a400-c00000000093a5d4: serial8250_early_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffe00055986c)
Location: drivers/tty/serial/8250/8250_early.c:60
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffe00055986c-ffffffe000559982: serial8250_early_out (STB_LOCAL)
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
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff81679ba0)
Location: drivers/tty/serial/8250/8250_early.c:60
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff81679ba0-ffffffff81679c2d: serial8250_early_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff81658c90)
Location: drivers/tty/serial/8250/8250_early.c:60
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff81658c90-ffffffff81658d1d: serial8250_early_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff816a7f80)
Location: drivers/tty/serial/8250/8250_early.c:60
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff816a7f80-ffffffff816a800d: serial8250_early_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void serial8250_early_out(struct uart_port *port, int offset, int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff816c23e0)
Location: drivers/tty/serial/8250/8250_early.c:60
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff816c23e0-ffffffff816c246d: serial8250_early_out (STB_LOCAL)
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
