# Function: <code>serial8250_read_char</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81559974)
Location: drivers/tty/serial/8250/8250_port.c:1640
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81586184)
Location: drivers/tty/serial/8250/8250_port.c:1637
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
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
In drivers/tty/serial/8250/8250_port.c (ffffffff815999c4)
Location: drivers/tty/serial/8250/8250_port.c:1653
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
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
In drivers/tty/serial/8250/8250_port.c (ffffffff815fe894)
Location: drivers/tty/serial/8250/8250_port.c:1684
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void serial8250_read_char(struct uart_8250_port *up, unsigned char lsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81638170)
Location: drivers/tty/serial/8250/8250_port.c:1685
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
**Symbols:**

```
ffffffff81638170-ffffffff8163834d: serial8250_read_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void serial8250_read_char(struct uart_8250_port *up, unsigned char lsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81654820)
Location: drivers/tty/serial/8250/8250_port.c:1684
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
**Symbols:**

```
ffffffff81654820-ffffffff816549f7: serial8250_read_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void serial8250_read_char(struct uart_8250_port *up, unsigned char lsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81689200)
Location: drivers/tty/serial/8250/8250_port.c:1690
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
**Symbols:**

```
ffffffff81689200-ffffffff816893d7: serial8250_read_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void serial8250_read_char(struct uart_8250_port *up, unsigned char lsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ab920)
Location: drivers/tty/serial/8250/8250_port.c:1639
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
**Symbols:**

```
ffffffff816ab920-ffffffff816abaf7: serial8250_read_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void serial8250_read_char(struct uart_8250_port *up, unsigned char lsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175e580)
Location: drivers/tty/serial/8250/8250_port.c:1709
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
**Symbols:**

```
ffffffff8175e580-ffffffff8175e798: serial8250_read_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void serial8250_read_char(struct uart_8250_port *up, unsigned char lsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81779400)
Location: drivers/tty/serial/8250/8250_port.c:1710
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
**Symbols:**

```
ffffffff81779400-ffffffff81779618: serial8250_read_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void serial8250_read_char(struct uart_8250_port *up, unsigned char lsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175ccc0)
Location: drivers/tty/serial/8250/8250_port.c:1710
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
**Symbols:**

```
ffffffff8175ccc0-ffffffff8175ced8: serial8250_read_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void serial8250_read_char(struct uart_8250_port *up, unsigned char lsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e0b20)
Location: drivers/tty/serial/8250/8250_port.c:1711
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
**Symbols:**

```
ffffffff817e0b20-ffffffff817e0d38: serial8250_read_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void serial8250_read_char(struct uart_8250_port *up, unsigned char lsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8191f940)
Location: drivers/tty/serial/8250/8250_port.c:1728
Inline: False
```
**Symbols:**

```
ffffffff8191f940-ffffffff8191fb56: serial8250_read_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void serial8250_read_char(struct uart_8250_port *up, u16 lsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7bee0)
Location: drivers/tty/serial/8250/8250_port.c:1725
Inline: False
```
**Symbols:**

```
ffffffff81a7bee0-ffffffff81a7c10a: serial8250_read_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void serial8250_read_char(struct uart_8250_port *up, u16 lsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81ac71d0)
Location: drivers/tty/serial/8250/8250_port.c:1703
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
```
**Symbols:**

```
ffffffff81ac71d0-ffffffff81ac743d: serial8250_read_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void serial8250_read_char(struct uart_8250_port *up, u16 lsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1a650)
Location: drivers/tty/serial/8250/8250_port.c:1703
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
```
**Symbols:**

```
ffffffff81b1a650-ffffffff81b1a8c4: serial8250_read_char (STB_GLOBAL)
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
void serial8250_read_char(struct uart_8250_port *up, unsigned char lsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffff800010886468)
Location: drivers/tty/serial/8250/8250_port.c:1639
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
**Symbols:**

```
ffff800010886468-ffff800010886620: serial8250_read_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void serial8250_read_char(struct uart_8250_port *up, unsigned char lsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c098495c)
Location: drivers/tty/serial/8250/8250_port.c:1639
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
**Symbols:**

```
c098495c-c0984b54: serial8250_read_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void serial8250_read_char(struct uart_8250_port *up, unsigned char lsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c00000000092d020)
Location: drivers/tty/serial/8250/8250_port.c:1639
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
**Symbols:**

```
c00000000092d020-c00000000092d288: serial8250_read_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void serial8250_read_char(struct uart_8250_port *up, unsigned char lsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffe000551700)
Location: drivers/tty/serial/8250/8250_port.c:1639
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
**Symbols:**

```
ffffffe000551700-ffffffe000551886: serial8250_read_char (STB_GLOBAL)
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
void serial8250_read_char(struct uart_8250_port *up, unsigned char lsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81671390)
Location: drivers/tty/serial/8250/8250_port.c:1639
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
**Symbols:**

```
ffffffff81671390-ffffffff81671567: serial8250_read_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void serial8250_read_char(struct uart_8250_port *up, unsigned char lsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81650490)
Location: drivers/tty/serial/8250/8250_port.c:1639
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
**Symbols:**

```
ffffffff81650490-ffffffff81650667: serial8250_read_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void serial8250_read_char(struct uart_8250_port *up, unsigned char lsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8169f760)
Location: drivers/tty/serial/8250/8250_port.c:1639
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
**Symbols:**

```
ffffffff8169f760-ffffffff8169f937: serial8250_read_char (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void serial8250_read_char(struct uart_8250_port *up, unsigned char lsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816b9c20)
Location: drivers/tty/serial/8250/8250_port.c:1639
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
**Symbols:**

```
ffffffff816b9c20-ffffffff816b9df7: serial8250_read_char (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned char lsr</code> ➡️ <code>u16 lsr</code>
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
