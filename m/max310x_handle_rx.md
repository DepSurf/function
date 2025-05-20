# Function: <code>max310x_handle_rx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8150d616)
Location: drivers/tty/serial/max310x.c:592
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8155f83d)
Location: drivers/tty/serial/max310x.c:600
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8158bf90)
Location: drivers/tty/serial/max310x.c:600
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff815a010f)
Location: drivers/tty/serial/max310x.c:600
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8160583f)
Location: drivers/tty/serial/max310x.c:596
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void max310x_handle_rx(struct uart_port *port, unsigned int rxlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8163fcc0)
Location: drivers/tty/serial/max310x.c:627
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
**Symbols:**

```
ffffffff8163fcc0-ffffffff8163ffd4: max310x_handle_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void max310x_handle_rx(struct uart_port *port, unsigned int rxlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8165ded0)
Location: drivers/tty/serial/max310x.c:633
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
**Symbols:**

```
ffffffff8165ded0-ffffffff8165e1eb: max310x_handle_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81692c2b)
Location: drivers/tty/serial/max310x.c:654
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff816b57cb)
Location: drivers/tty/serial/max310x.c:654
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void max310x_handle_rx(struct uart_port *port, unsigned int rxlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:654
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
**Symbols:**

```
ffffffff81768670-ffffffff81768a40: max310x_handle_rx (STB_LOCAL)
ffffffff81769efc-ffffffff81769f2c: max310x_handle_rx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void max310x_handle_rx(struct uart_port *port, unsigned int rxlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:654
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
**Symbols:**

```
ffffffff81783410-ffffffff817837e0: max310x_handle_rx (STB_LOCAL)
ffffffff81c0817c-ffffffff81c081ac: max310x_handle_rx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void max310x_handle_rx(struct uart_port *port, unsigned int rxlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:654
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
**Symbols:**

```
ffffffff81766d10-ffffffff817670c2: max310x_handle_rx (STB_LOCAL)
ffffffff81bf9d40-ffffffff81bf9d70: max310x_handle_rx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void max310x_handle_rx(struct uart_port *port, unsigned int rxlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:654
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
**Symbols:**

```
ffffffff817eb6e0-ffffffff817eba92: max310x_handle_rx (STB_LOCAL)
ffffffff81cfa3df-ffffffff81cfa40f: max310x_handle_rx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void max310x_handle_rx(struct uart_port *port, unsigned int rxlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:654
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
**Symbols:**

```
ffffffff8192c550-ffffffff8192c91a: max310x_handle_rx (STB_LOCAL)
ffffffff81ec2678-ffffffff81ec26a8: max310x_handle_rx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void max310x_handle_rx(struct uart_port *port, unsigned int rxlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81a88f00)
Location: drivers/tty/serial/max310x.c:664
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
**Symbols:**

```
ffffffff81a88f00-ffffffff81a892c4: max310x_handle_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void max310x_handle_rx(struct uart_port *port, unsigned int rxlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81ad4600)
Location: drivers/tty/serial/max310x.c:669
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
**Symbols:**

```
ffffffff81ad4600-ffffffff81ad4a73: max310x_handle_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void max310x_handle_rx(struct uart_port *port, unsigned int rxlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81b27ad0)
Location: drivers/tty/serial/max310x.c:685
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
**Symbols:**

```
ffffffff81b27ad0-ffffffff81b27f32: max310x_handle_rx (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffff800010898fec)
Location: drivers/tty/serial/max310x.c:654
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (c0994590)
Location: drivers/tty/serial/max310x.c:654
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:654
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffe00055b92c)
Location: drivers/tty/serial/max310x.c:654
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8167b22b)
Location: drivers/tty/serial/max310x.c:654
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8165a31b)
Location: drivers/tty/serial/max310x.c:654
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff816a960b)
Location: drivers/tty/serial/max310x.c:654
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff816c3a6b)
Location: drivers/tty/serial/max310x.c:654
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
