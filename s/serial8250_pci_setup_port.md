# Function: <code>serial8250_pci_setup_port</code>

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
int serial8250_pci_setup_port(struct pci_dev *dev, struct uart_8250_port *port, u8 bar, unsigned int offset, int regshift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pcilib.c (ffffffff81acf570)
Location: drivers/tty/serial/8250/8250_pcilib.c:15
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
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
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffffffff81acf570-ffffffff81acf6eb: serial8250_pci_setup_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int serial8250_pci_setup_port(struct pci_dev *dev, struct uart_8250_port *port, u8 bar, unsigned int offset, int regshift);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pcilib.c (ffffffff81b22630)
Location: drivers/tty/serial/8250/8250_pcilib.c:15
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup
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
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
  - drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup
```
**Symbols:**

```
ffffffff81b22630-ffffffff81b227ab: serial8250_pci_setup_port (STB_GLOBAL)
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
