# Function: <code>setup_port</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int setup_port(struct serial_private *priv, struct uart_8250_port *port, int bar, int offset, int regshift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150a740)
Location: drivers/tty/serial/8250/8250_pci.c:79
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
```
**Symbols:**

```
ffffffff8150a740-ffffffff8150a85b: setup_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155d5a0)
Location: drivers/tty/serial/8250/8250_pci.c:78
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffffffff8155d5a0-ffffffff8155d693: setup_port.isra.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81589cd0)
Location: drivers/tty/serial/8250/8250_pci.c:75
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffffffff81589cd0-ffffffff81589dc3: setup_port.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8159e020)
Location: drivers/tty/serial/8250/8250_pci.c:75
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffffffff8159e020-ffffffff8159e115: setup_port.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81603510)
Location: drivers/tty/serial/8250/8250_pci.c:72
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffffffff81603510-ffffffff81603603: setup_port.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8163c8e0)
Location: drivers/tty/serial/8250/8250_pci.c:72
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffffffff8163c8e0-ffffffff8163c9d3: setup_port.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8165ab60)
Location: drivers/tty/serial/8250/8250_pci.c:72
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffffffff8165ab60-ffffffff8165ac55: setup_port.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81690190)
Location: drivers/tty/serial/8250/8250_pci.c:72
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffffffff81690190-ffffffff8169027d: setup_port.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816b2b60)
Location: drivers/tty/serial/8250/8250_pci.c:87
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffffffff816b2b60-ffffffff816b2c53: setup_port.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int setup_port(struct serial_private *priv, struct uart_8250_port *port, int bar, int offset, int regshift);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8176750b)
Location: drivers/tty/serial/8250/8250_pci.c:85
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffffffff81765180-ffffffff81765281: setup_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int setup_port(struct serial_private *priv, struct uart_8250_port *port, int bar, int offset, int regshift);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8178244b)
Location: drivers/tty/serial/8250/8250_pci.c:85
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffffffff817800e0-ffffffff817801e1: setup_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int setup_port(struct serial_private *priv, struct uart_8250_port *port, int bar, int offset, int regshift);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81765d4b)
Location: drivers/tty/serial/8250/8250_pci.c:89
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffffffff81763a10-ffffffff81763b08: setup_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int setup_port(struct serial_private *priv, struct uart_8250_port *port, u8 bar, unsigned int offset, int regshift);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817ea65b)
Location: drivers/tty/serial/8250/8250_pci.c:89
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffffffff817e7df0-ffffffff817e7f90: setup_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int setup_port(struct serial_private *priv, struct uart_8250_port *port, u8 bar, unsigned int offset, int regshift);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8192a3cb)
Location: drivers/tty/serial/8250/8250_pci.c:89
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffffffff819279a0-ffffffff81927b14: setup_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int setup_port(struct serial_private *priv, struct uart_8250_port *port, u8 bar, unsigned int offset, int regshift);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81a8755b)
Location: drivers/tty/serial/8250/8250_pci.c:89
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffffffff81a848b0-ffffffff81a84a24: setup_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81ad00d7)
Location: drivers/tty/serial/8250/8250_pci.c:90
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b23f37)
Location: drivers/tty/serial/8250/8250_pci.c:171
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088e280)
Location: drivers/tty/serial/8250/8250_pci.c:87
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffff80001088e280-ffff80001088e37c: setup_port.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int setup_port(struct serial_private *priv, struct uart_8250_port *port, int bar, int offset, int regshift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (c098a50c)
Location: drivers/tty/serial/8250/8250_pci.c:87
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
c098a50c-c098a5e8: setup_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (c000000000936ad0)
Location: drivers/tty/serial/8250/8250_pci.c:87
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
c000000000936ad0-c000000000936c38: setup_port.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffe0005580b6)
Location: drivers/tty/serial/8250/8250_pci.c:87
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffffffe0005580b6-ffffffe000558180: setup_port.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816785d0)
Location: drivers/tty/serial/8250/8250_pci.c:87
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffffffff816785d0-ffffffff816786bd: setup_port.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816576b0)
Location: drivers/tty/serial/8250/8250_pci.c:87
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffffffff816576b0-ffffffff816577a3: setup_port.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816a69a0)
Location: drivers/tty/serial/8250/8250_pci.c:87
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffffffff816a69a0-ffffffff816a6a93: setup_port.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816c0e00)
Location: drivers/tty/serial/8250/8250_pci.c:87
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup
  - drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight
  - drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_default_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup
  - drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_siig_setup
  - drivers/tty/serial/8250/8250_pci.c:sbs_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup
  - drivers/tty/serial/8250/8250_pci.c:afavlab_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffffffff816c0e00-ffffffff816c0ef3: setup_port.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int bar</code> ➡️ <code>u8 bar</code>
</li>
<li>
<b>Param type changed. </b>
<code>int offset</code> ➡️ <code>unsigned int offset</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
