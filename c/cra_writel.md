# Function: <code>cra_writel</code>

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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-altera.c (ffff800010727540)
Location: drivers/pci/controller/pcie-altera.c:126
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_isr
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
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
In drivers/pci/controller/pcie-altera.c (c08b281c)
Location: drivers/pci/controller/pcie-altera.c:126
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_isr
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:s10_tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
  - drivers/pci/controller/pcie-altera.c:tlp_write_packet
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
