# Function: <code>pci_default_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150aac0)
Location: drivers/tty/serial/8250/8250_pci.c:1316
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17c154_setup
  - drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:byt_serial_setup
```
**Symbols:**

```
ffffffff8150aac0-ffffffff8150ab56: pci_default_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155d8f0)
Location: drivers/tty/serial/8250/8250_pci.c:1315
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch355_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17c154_setup
  - drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:byt_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
```
**Symbols:**

```
ffffffff8155d8f0-ffffffff8155d97e: pci_default_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8158a0c0)
Location: drivers/tty/serial/8250/8250_pci.c:1312
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch355_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_xr17c154_setup
  - drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
```
**Symbols:**

```
ffffffff8158a0c0-ffffffff8158a14e: pci_default_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8159e380)
Location: drivers/tty/serial/8250/8250_pci.c:1312
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup
  - drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
```
**Symbols:**

```
ffffffff8159e380-ffffffff8159e410: pci_default_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81603870)
Location: drivers/tty/serial/8250/8250_pci.c:1309
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup
  - drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
```
**Symbols:**

```
ffffffff81603870-ffffffff81603900: pci_default_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8163cc50)
Location: drivers/tty/serial/8250/8250_pci.c:1309
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup
  - drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
```
**Symbols:**

```
ffffffff8163cc50-ffffffff8163cce5: pci_default_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8165aed0)
Location: drivers/tty/serial/8250/8250_pci.c:1309
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup
  - drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
```
**Symbols:**

```
ffffffff8165aed0-ffffffff8165af65: pci_default_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81690630)
Location: drivers/tty/serial/8250/8250_pci.c:1309
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch355_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup
  - drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
```
**Symbols:**

```
ffffffff81690630-ffffffff816906ca: pci_default_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816b3070)
Location: drivers/tty/serial/8250/8250_pci.c:1324
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch355_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup
  - drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
```
**Symbols:**

```
ffffffff816b3070-ffffffff816b310a: pci_default_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817655d0)
Location: drivers/tty/serial/8250/8250_pci.c:1322
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
```
**Symbols:**

```
ffffffff817655d0-ffffffff81765667: pci_default_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81780530)
Location: drivers/tty/serial/8250/8250_pci.c:1322
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
```
**Symbols:**

```
ffffffff81780530-ffffffff817805c7: pci_default_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81763e80)
Location: drivers/tty/serial/8250/8250_pci.c:1326
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
```
**Symbols:**

```
ffffffff81763e80-ffffffff81763f17: pci_default_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:1326
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
```
**Symbols:**

```
ffffffff817e8b30-ffffffff817e8cb4: pci_default_setup (STB_LOCAL)
ffffffff81cfa1a8-ffffffff81cfa1e2: pci_default_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:1493
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup
```
**Symbols:**

```
ffffffff81928840-ffffffff819289dc: pci_default_setup (STB_LOCAL)
ffffffff81ec2403-ffffffff81ec243d: pci_default_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:1498
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup
```
**Symbols:**

```
ffffffff81a854d0-ffffffff81a8566c: pci_default_setup (STB_LOCAL)
ffffffff82096103-ffffffff8209613d: pci_default_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:1470
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
```
**Symbols:**

```
ffffffff81ad0be0-ffffffff81ad0d38: pci_default_setup (STB_LOCAL)
ffffffff82116f94-ffffffff82116fce: pci_default_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: drivers/tty/serial/8250/8250_pci.c:1551
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
```
**Symbols:**

```
ffffffff81b24a40-ffffffff81b24b98: pci_default_setup (STB_LOCAL)
ffffffff821f4d59-ffffffff821f4d93: pci_default_setup.cold (STB_LOCAL)
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
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088e938)
Location: drivers/tty/serial/8250/8250_pci.c:1324
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup
  - drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
```
**Symbols:**

```
ffff80001088e938-ffff80001088e9e4: pci_default_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (c098a9c0)
Location: drivers/tty/serial/8250/8250_pci.c:1324
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup
  - drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
```
**Symbols:**

```
c098a9c0-c098aa50: pci_default_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (c0000000009371c0)
Location: drivers/tty/serial/8250/8250_pci.c:1324
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch355_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup
  - drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup
  - drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
```
**Symbols:**

```
c0000000009371c0-c000000000937284: pci_default_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffe000558630)
Location: drivers/tty/serial/8250/8250_pci.c:1324
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup
  - drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
```
**Symbols:**

```
ffffffe000558630-ffffffe0005586de: pci_default_setup (STB_LOCAL)
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
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81678ad0)
Location: drivers/tty/serial/8250/8250_pci.c:1324
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch355_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup
  - drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
```
**Symbols:**

```
ffffffff81678ad0-ffffffff81678b6a: pci_default_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81657bc0)
Location: drivers/tty/serial/8250/8250_pci.c:1324
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch355_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup
  - drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
```
**Symbols:**

```
ffffffff81657bc0-ffffffff81657c5a: pci_default_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816a6eb0)
Location: drivers/tty/serial/8250/8250_pci.c:1324
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch355_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup
  - drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
```
**Symbols:**

```
ffffffff816a6eb0-ffffffff816a6f4a: pci_default_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private *priv, const struct pciserial_board *board, struct uart_8250_port *port, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816c1310)
Location: drivers/tty/serial/8250/8250_pci.c:1324
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch355_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup
  - drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_asix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
```
**Symbols:**

```
ffffffff816c1310-ffffffff816c13aa: pci_default_setup (STB_LOCAL)
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
