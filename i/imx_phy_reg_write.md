# Function: <code>imx_phy_reg_write</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int imx_phy_reg_write(u16 val, void *mmio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/ahci_imx.c (ffff8000109b7668)
Location: drivers/ata/ahci_imx.c:163
Inline: True
Direct callers:
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:sata_ahci_read_temperature
  - drivers/ata/ahci_imx.c:sata_ahci_read_temperature
  - drivers/ata/ahci_imx.c:sata_ahci_read_temperature
  - drivers/ata/ahci_imx.c:sata_ahci_read_temperature
  - drivers/ata/ahci_imx.c:sata_ahci_read_temperature
  - drivers/ata/ahci_imx.c:sata_ahci_read_temperature
  - drivers/ata/ahci_imx.c:sata_ahci_read_temperature
  - drivers/ata/ahci_imx.c:sata_ahci_read_temperature
  - drivers/ata/ahci_imx.c:read_adc_sum
```
**Symbols:**

```
ffff8000109b7668-ffff8000109b7714: imx_phy_reg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int imx_phy_reg_write(u16 val, void *mmio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/ahci_imx.c (c0a89b04)
Location: drivers/ata/ahci_imx.c:163
Inline: True
Direct callers:
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:sata_ahci_read_temperature
  - drivers/ata/ahci_imx.c:sata_ahci_read_temperature
  - drivers/ata/ahci_imx.c:sata_ahci_read_temperature
  - drivers/ata/ahci_imx.c:sata_ahci_read_temperature
  - drivers/ata/ahci_imx.c:sata_ahci_read_temperature
  - drivers/ata/ahci_imx.c:sata_ahci_read_temperature
  - drivers/ata/ahci_imx.c:sata_ahci_read_temperature
  - drivers/ata/ahci_imx.c:sata_ahci_read_temperature
  - drivers/ata/ahci_imx.c:read_adc_sum
```
**Symbols:**

```
c0a89b04-c0a89bc0: imx_phy_reg_write (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
