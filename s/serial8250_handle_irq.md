# Function: <code>serial8250_handle_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81508c30)
Location: drivers/tty/serial/8250/8250_port.c:1555
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
```
**Symbols:**

```
ffffffff81508c30-ffffffff81508ce1: serial8250_handle_irq.part.20 (STB_LOCAL)
ffffffff81508cf0-ffffffff81508d09: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8155aa71)
Location: drivers/tty/serial/8250/8250_port.c:1812
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
```
**Symbols:**

```
ffffffff8155a940-ffffffff8155aa2d: serial8250_handle_irq.part.24 (STB_LOCAL)
ffffffff8155aa30-ffffffff8155aa49: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff815872fc)
Location: drivers/tty/serial/8250/8250_port.c:1809
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
```
**Symbols:**

```
ffffffff815870e0-ffffffff815871cd: serial8250_handle_irq.part.25 (STB_LOCAL)
ffffffff815871d0-ffffffff815871e9: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8159b94c)
Location: drivers/tty/serial/8250/8250_port.c:1827
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:exar_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:exar_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
```
**Symbols:**

```
ffffffff8159b770-ffffffff8159b82b: serial8250_handle_irq.part.23 (STB_LOCAL)
ffffffff8159b830-ffffffff8159b849: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81600c08)
Location: drivers/tty/serial/8250/8250_port.c:1858
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:exar_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:exar_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
```
**Symbols:**

```
ffffffff81600a10-ffffffff81600ada: serial8250_handle_irq.part.23 (STB_LOCAL)
ffffffff81600ae0-ffffffff81600af9: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81639b58)
Location: drivers/tty/serial/8250/8250_port.c:1860
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
```
**Symbols:**

```
ffffffff816399c0-ffffffff81639a96: serial8250_handle_irq.part.24 (STB_LOCAL)
ffffffff81639aa0-ffffffff81639ab9: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81657fc8)
Location: drivers/tty/serial/8250/8250_port.c:1859
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
```
**Symbols:**

```
ffffffff81657e00-ffffffff81657f07: serial8250_handle_irq.part.23 (STB_LOCAL)
ffffffff81657f10-ffffffff81657f29: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8168c14a)
Location: drivers/tty/serial/8250/8250_port.c:1865
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
```
**Symbols:**

```
ffffffff8168bf80-ffffffff8168c08e: serial8250_handle_irq.part.0 (STB_LOCAL)
ffffffff8168c090-ffffffff8168c0a9: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ae70a)
Location: drivers/tty/serial/8250/8250_port.c:1814
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
```
**Symbols:**

```
ffffffff816ae540-ffffffff816ae64e: serial8250_handle_irq.part.0 (STB_LOCAL)
ffffffff816ae650-ffffffff816ae669: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff817605da)
Location: drivers/tty/serial/8250/8250_port.c:1884
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
```
**Symbols:**

```
ffffffff81760370-ffffffff817604e5: serial8250_handle_irq.part.0 (STB_LOCAL)
ffffffff817604f0-ffffffff81760509: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177b45a)
Location: drivers/tty/serial/8250/8250_port.c:1885
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
```
**Symbols:**

```
ffffffff8177b1f0-ffffffff8177b365: serial8250_handle_irq.part.0 (STB_LOCAL)
ffffffff8177b370-ffffffff8177b389: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175eada)
Location: drivers/tty/serial/8250/8250_port.c:1897
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
```
**Symbols:**

```
ffffffff8175e870-ffffffff8175e9ea: serial8250_handle_irq.part.0 (STB_LOCAL)
ffffffff8175e9f0-ffffffff8175ea09: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e2f3a)
Location: drivers/tty/serial/8250/8250_port.c:1898
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
```
**Symbols:**

```
ffffffff817e2cd0-ffffffff817e2e4a: serial8250_handle_irq.part.0 (STB_LOCAL)
ffffffff817e2e50-ffffffff817e2e69: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81923c78)
Location: drivers/tty/serial/8250/8250_port.c:1913
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
```
**Symbols:**

```
ffffffff819238b0-ffffffff81923b71: serial8250_handle_irq.part.0 (STB_LOCAL)
ffffffff81923b80-ffffffff81923ba9: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a807c8)
Location: drivers/tty/serial/8250/8250_port.c:1914
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_mid.c:dnv_handle_irq
  - drivers/tty/serial/8250/8250_mid.c:tng_handle_irq
```
**Symbols:**

```
ffffffff81a803a0-ffffffff81a80691: serial8250_handle_irq.part.0 (STB_LOCAL)
ffffffff81a806b0-ffffffff81a806d9: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81acb9c0)
Location: drivers/tty/serial/8250/8250_port.c:1903
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_mid.c:dnv_handle_irq
  - drivers/tty/serial/8250/8250_mid.c:tng_handle_irq
```
**Symbols:**

```
ffffffff81acb9c0-ffffffff81acbd07: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1e160)
Location: drivers/tty/serial/8250/8250_port.c:1902
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_mid.c:dnv_handle_irq
  - drivers/tty/serial/8250/8250_mid.c:tng_handle_irq
```
**Symbols:**

```
ffffffff81b1e160-ffffffff81b1e4ab: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffff800010889730)
Location: drivers/tty/serial/8250/8250_port.c:1814
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_dw.c:dw8250_handle_irq
```
**Symbols:**

```
ffff800010888ce8-ffff800010888e48: serial8250_handle_irq.part.0 (STB_LOCAL)
ffff800010888e48-ffff800010888e84: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c0987650)
Location: drivers/tty/serial/8250/8250_port.c:1814
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
```
**Symbols:**

```
c098746c-c0987574: serial8250_handle_irq.part.0 (STB_LOCAL)
c0987574-c09875a0: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c0000000009316f0)
Location: drivers/tty/serial/8250/8250_port.c:1814
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
```
**Symbols:**

```
c000000000931410-c0000000009315c0: serial8250_handle_irq.part.0 (STB_LOCAL)
c0000000009315c0-c0000000009315e4: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffe000553c90)
Location: drivers/tty/serial/8250/8250_port.c:1814
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
```
**Symbols:**

```
ffffffe000553ac2-ffffffe000553bb4: serial8250_handle_irq.part.0 (STB_LOCAL)
ffffffe000553bb4-ffffffe000553bee: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8167417a)
Location: drivers/tty/serial/8250/8250_port.c:1814
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
```
**Symbols:**

```
ffffffff81673fb0-ffffffff816740be: serial8250_handle_irq.part.0 (STB_LOCAL)
ffffffff816740c0-ffffffff816740d9: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8165345a)
Location: drivers/tty/serial/8250/8250_port.c:1814
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
```
**Symbols:**

```
ffffffff81653290-ffffffff8165339e: serial8250_handle_irq.part.0 (STB_LOCAL)
ffffffff816533a0-ffffffff816533b9: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816a254a)
Location: drivers/tty/serial/8250/8250_port.c:1814
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
```
**Symbols:**

```
ffffffff816a2380-ffffffff816a248e: serial8250_handle_irq.part.0 (STB_LOCAL)
ffffffff816a2490-ffffffff816a24a9: serial8250_handle_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int serial8250_handle_irq(struct uart_port *port, unsigned int iir);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816bcbda)
Location: drivers/tty/serial/8250/8250_port.c:1814
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
```
**Symbols:**

```
ffffffff816bca10-ffffffff816bcb1e: serial8250_handle_irq.part.0 (STB_LOCAL)
ffffffff816bcb20-ffffffff816bcb39: serial8250_handle_irq (STB_GLOBAL)
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
