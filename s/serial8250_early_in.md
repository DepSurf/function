# Function: <code>serial8250_early_in</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff81fa7536)
Location: drivers/tty/serial/8250/8250_early.c:40
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:wait_for_xmitr
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
```
**Symbols:**

```
ffffffff81fa7536-ffffffff81fa758d: serial8250_early_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff81fd39a0)
Location: drivers/tty/serial/8250/8250_early.c:40
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff81fd39a0-ffffffff81fd3a07: serial8250_early_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff82011360)
Location: drivers/tty/serial/8250/8250_early.c:40
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff82011360-ffffffff820113c7: serial8250_early_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff820f2f0a)
Location: drivers/tty/serial/8250/8250_early.c:40
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff820f2f0a-ffffffff820f2f83: serial8250_early_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff81604b20)
Location: drivers/tty/serial/8250/8250_early.c:37
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff81604b20-ffffffff81604ba5: serial8250_early_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff8163ddb0)
Location: drivers/tty/serial/8250/8250_early.c:37
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff8163ddb0-ffffffff8163de35: serial8250_early_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff8165bff0)
Location: drivers/tty/serial/8250/8250_early.c:37
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff8165bff0-ffffffff8165c076: serial8250_early_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff816916e0)
Location: drivers/tty/serial/8250/8250_early.c:37
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff816916e0-ffffffff81691766: serial8250_early_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff816b41d0)
Location: drivers/tty/serial/8250/8250_early.c:37
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff816b41d0-ffffffff816b4256: serial8250_early_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff817678d0)
Location: drivers/tty/serial/8250/8250_early.c:37
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:init_port
  - drivers/tty/serial/8250/8250_early.c:init_port
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_read
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_read
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff817678d0-ffffffff81767956: serial8250_early_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff81782630)
Location: drivers/tty/serial/8250/8250_early.c:37
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:init_port
  - drivers/tty/serial/8250/8250_early.c:init_port
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_read
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_read
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff81782630-ffffffff817826b6: serial8250_early_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff81765f30)
Location: drivers/tty/serial/8250/8250_early.c:37
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_read
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_read
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff81765f30-ffffffff81765fb6: serial8250_early_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (0)
Location: drivers/tty/serial/8250/8250_early.c:37
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_read
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_read
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff817ea840-ffffffff817ea926: serial8250_early_in (STB_LOCAL)
ffffffff81cfa316-ffffffff81cfa337: serial8250_early_in.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (0)
Location: drivers/tty/serial/8250/8250_early.c:37
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_read
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_read
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff8192a5b0-ffffffff8192a6de: serial8250_early_in (STB_LOCAL)
ffffffff81ec2547-ffffffff81ec2568: serial8250_early_in.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (0)
Location: drivers/tty/serial/8250/8250_early.c:37
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_read
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_read
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff81a879e0-ffffffff81a87b0e: serial8250_early_in (STB_LOCAL)
ffffffff8209613d-ffffffff8209615e: serial8250_early_in.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (0)
Location: drivers/tty/serial/8250/8250_early.c:37
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_read
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_read
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff81ad2dc0-ffffffff81ad2ecc: serial8250_early_in (STB_LOCAL)
ffffffff82116fce-ffffffff82116fef: serial8250_early_in.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (0)
Location: drivers/tty/serial/8250/8250_early.c:36
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_read
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_read
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff81b22800-ffffffff81b2290c: serial8250_early_in (STB_LOCAL)
ffffffff821f4cee-ffffffff821f4d0f: serial8250_early_in.cold (STB_LOCAL)
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
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffff8000108906b0)
Location: drivers/tty/serial/8250/8250_early.c:37
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffff8000108906b0-ffff8000108907fc: serial8250_early_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (c098cd34)
Location: drivers/tty/serial/8250/8250_early.c:37
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
c098cd34-c098ce0c: serial8250_early_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (c00000000093a5e0)
Location: drivers/tty/serial/8250/8250_early.c:37
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
c00000000093a5e0-c00000000093a890: serial8250_early_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffe000559708)
Location: drivers/tty/serial/8250/8250_early.c:37
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffe000559708-ffffffe000559826: serial8250_early_in (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff81679c30)
Location: drivers/tty/serial/8250/8250_early.c:37
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff81679c30-ffffffff81679cb6: serial8250_early_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff81658d20)
Location: drivers/tty/serial/8250/8250_early.c:37
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff81658d20-ffffffff81658da6: serial8250_early_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff816a8010)
Location: drivers/tty/serial/8250/8250_early.c:37
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff816a8010-ffffffff816a8096: serial8250_early_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int serial8250_early_in(struct uart_port *port, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_early.c (ffffffff816c2470)
Location: drivers/tty/serial/8250/8250_early.c:37
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_setup
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff816c2470-ffffffff816c24f6: serial8250_early_in (STB_LOCAL)
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
