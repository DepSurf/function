# Function: <code>serial8250_rpm_put_tx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81506080)
Location: drivers/tty/serial/8250/8250_port.c:549
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
```
**Symbols:**

```
ffffffff81506080-ffffffff815060c8: serial8250_rpm_put_tx (STB_LOCAL)
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8155a7be)
Location: drivers/tty/serial/8250/8250_port.c:651
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff815856a0)
Location: drivers/tty/serial/8250/8250_port.c:653
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
**Symbols:**

```
ffffffff815856a0-ffffffff815856d1: serial8250_rpm_put_tx.part.21 (STB_LOCAL)
ffffffff81586040-ffffffff81586067: serial8250_rpm_put_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81599300)
Location: drivers/tty/serial/8250/8250_port.c:669
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
**Symbols:**

```
ffffffff81598de0-ffffffff81598e11: serial8250_rpm_put_tx.part.16 (STB_LOCAL)
ffffffff81599300-ffffffff81599327: serial8250_rpm_put_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff815fe170)
Location: drivers/tty/serial/8250/8250_port.c:688
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
**Symbols:**

```
ffffffff815fdbf0-ffffffff815fdc21: serial8250_rpm_put_tx.part.16 (STB_LOCAL)
ffffffff815fe170-ffffffff815fe199: serial8250_rpm_put_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81637a90)
Location: drivers/tty/serial/8250/8250_port.c:689
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
**Symbols:**

```
ffffffff81637530-ffffffff81637561: serial8250_rpm_put_tx.part.16 (STB_LOCAL)
ffffffff81637a90-ffffffff81637ab8: serial8250_rpm_put_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81656590)
Location: drivers/tty/serial/8250/8250_port.c:689
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
**Symbols:**

```
ffffffff81655b10-ffffffff81655b49: serial8250_rpm_put_tx.part.20 (STB_LOCAL)
ffffffff81656590-ffffffff816565b8: serial8250_rpm_put_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8168a2a0)
Location: drivers/tty/serial/8250/8250_port.c:697
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
**Symbols:**

```
ffffffff8168a2a0-ffffffff8168a2f4: serial8250_rpm_put_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ac820)
Location: drivers/tty/serial/8250/8250_port.c:690
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
**Symbols:**

```
ffffffff816ac820-ffffffff816ac874: serial8250_rpm_put_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81760319)
Location: drivers/tty/serial/8250/8250_port.c:725
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
**Symbols:**

```
ffffffff8175ec90-ffffffff8175ece4: serial8250_rpm_put_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177b19b)
Location: drivers/tty/serial/8250/8250_port.c:726
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
**Symbols:**

```
ffffffff81779b10-ffffffff81779b64: serial8250_rpm_put_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175e818)
Location: drivers/tty/serial/8250/8250_port.c:730
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
**Symbols:**

```
ffffffff8175d440-ffffffff8175d494: serial8250_rpm_put_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e2c49)
Location: drivers/tty/serial/8250/8250_port.c:731
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
**Symbols:**

```
ffffffff817e1200-ffffffff817e1254: serial8250_rpm_put_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81923805)
Location: drivers/tty/serial/8250/8250_port.c:718
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
**Symbols:**

```
ffffffff8191ffa0-ffffffff81920012: serial8250_rpm_put_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a80185)
Location: drivers/tty/serial/8250/8250_port.c:712
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
**Symbols:**

```
ffffffff81a7c640-ffffffff81a7c6b2: serial8250_rpm_put_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81acbc8c)
Location: drivers/tty/serial/8250/8250_port.c:656
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
**Symbols:**

```
ffffffff81ac7cb0-ffffffff81ac7d22: serial8250_rpm_put_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1e430)
Location: drivers/tty/serial/8250/8250_port.c:657
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
```
**Symbols:**

```
ffffffff81b1ad60-ffffffff81b1add2: serial8250_rpm_put_tx (STB_GLOBAL)
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
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffff800010887528)
Location: drivers/tty/serial/8250/8250_port.c:690
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
**Symbols:**

```
ffff800010886ff0-ffff80001088702c: serial8250_rpm_put_tx.part.0 (STB_LOCAL)
ffff800010887528-ffff80001088758c: serial8250_rpm_put_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c0985d0c)
Location: drivers/tty/serial/8250/8250_port.c:690
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
**Symbols:**

```
c09854bc-c09854fc: serial8250_rpm_put_tx.part.0 (STB_LOCAL)
c0985d0c-c0985d60: serial8250_rpm_put_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c00000000092e950)
Location: drivers/tty/serial/8250/8250_port.c:690
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
**Symbols:**

```
c00000000092e950-c00000000092e9f4: serial8250_rpm_put_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffe0005523ce)
Location: drivers/tty/serial/8250/8250_port.c:690
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
**Symbols:**

```
ffffffe000551f66-ffffffe000551fa8: serial8250_rpm_put_tx.part.0 (STB_LOCAL)
ffffffe0005523ce-ffffffe00055241e: serial8250_rpm_put_tx (STB_GLOBAL)
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
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81672290)
Location: drivers/tty/serial/8250/8250_port.c:690
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
**Symbols:**

```
ffffffff81672290-ffffffff816722e4: serial8250_rpm_put_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81651390)
Location: drivers/tty/serial/8250/8250_port.c:690
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
**Symbols:**

```
ffffffff81651390-ffffffff816513e4: serial8250_rpm_put_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816a0660)
Location: drivers/tty/serial/8250/8250_port.c:690
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
**Symbols:**

```
ffffffff816a0660-ffffffff816a06b4: serial8250_rpm_put_tx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void serial8250_rpm_put_tx(struct uart_8250_port *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816bab20)
Location: drivers/tty/serial/8250/8250_port.c:690
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
**Symbols:**

```
ffffffff816bab20-ffffffff816bab74: serial8250_rpm_put_tx (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
