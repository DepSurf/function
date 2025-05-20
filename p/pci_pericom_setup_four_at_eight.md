# Function: <code>pci_pericom_setup_four_at_eight</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_pericom_setup_four_at_eight(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81690520)
Location: drivers/tty/serial/8250/8250_pci.c:1383
Inline: False
```
**Symbols:**

```
ffffffff81690520-ffffffff816905d1: pci_pericom_setup_four_at_eight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_pericom_setup_four_at_eight(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816b2f60)
Location: drivers/tty/serial/8250/8250_pci.c:1398
Inline: False
```
**Symbols:**

```
ffffffff816b2f60-ffffffff816b3011: pci_pericom_setup_four_at_eight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_pericom_setup_four_at_eight(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817654d0)
Location: drivers/tty/serial/8250/8250_pci.c:1396
Inline: False
```
**Symbols:**

```
ffffffff817654d0-ffffffff8176557e: pci_pericom_setup_four_at_eight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_pericom_setup_four_at_eight(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81780430)
Location: drivers/tty/serial/8250/8250_pci.c:1396
Inline: False
```
**Symbols:**

```
ffffffff81780430-ffffffff817804de: pci_pericom_setup_four_at_eight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_pericom_setup_four_at_eight(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81763d70)
Location: drivers/tty/serial/8250/8250_pci.c:1400
Inline: False
```
**Symbols:**

```
ffffffff81763d70-ffffffff81763e23: pci_pericom_setup_four_at_eight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_pericom_setup_four_at_eight(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:1404
Inline: False
```
**Symbols:**

```
ffffffff817e8990-ffffffff817e8b29: pci_pericom_setup_four_at_eight (STB_LOCAL)
ffffffff81cfa176-ffffffff81cfa1a8: pci_pericom_setup_four_at_eight.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int pci_pericom_setup_four_at_eight(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088e800)
Location: drivers/tty/serial/8250/8250_pci.c:1398
Inline: False
```
**Symbols:**

```
ffff80001088e800-ffff80001088e8c8: pci_pericom_setup_four_at_eight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_pericom_setup_four_at_eight(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (c098a8b8)
Location: drivers/tty/serial/8250/8250_pci.c:1398
Inline: False
```
**Symbols:**

```
c098a8b8-c098a960: pci_pericom_setup_four_at_eight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_pericom_setup_four_at_eight(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (c000000000937070)
Location: drivers/tty/serial/8250/8250_pci.c:1398
Inline: False
```
**Symbols:**

```
c000000000937070-c000000000937144: pci_pericom_setup_four_at_eight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_pericom_setup_four_at_eight(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffe000558512)
Location: drivers/tty/serial/8250/8250_pci.c:1398
Inline: False
```
**Symbols:**

```
ffffffe000558512-ffffffe0005585c8: pci_pericom_setup_four_at_eight (STB_LOCAL)
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
int pci_pericom_setup_four_at_eight(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816789c0)
Location: drivers/tty/serial/8250/8250_pci.c:1398
Inline: False
```
**Symbols:**

```
ffffffff816789c0-ffffffff81678a71: pci_pericom_setup_four_at_eight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_pericom_setup_four_at_eight(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81657ab0)
Location: drivers/tty/serial/8250/8250_pci.c:1398
Inline: False
```
**Symbols:**

```
ffffffff81657ab0-ffffffff81657b61: pci_pericom_setup_four_at_eight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_pericom_setup_four_at_eight(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816a6da0)
Location: drivers/tty/serial/8250/8250_pci.c:1398
Inline: False
```
**Symbols:**

```
ffffffff816a6da0-ffffffff816a6e51: pci_pericom_setup_four_at_eight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_pericom_setup_four_at_eight(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816c1200)
Location: drivers/tty/serial/8250/8250_pci.c:1398
Inline: False
```
**Symbols:**

```
ffffffff816c1200-ffffffff816c12b1: pci_pericom_setup_four_at_eight (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
