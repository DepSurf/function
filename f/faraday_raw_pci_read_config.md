# Function: <code>faraday_raw_pci_read_config</code>

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
In drivers/pci/controller/pci-ftpci100.c (ffff80001071f6b8)
Location: drivers/pci/controller/pci-ftpci100.c:189
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_unmask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_mask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_ack_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_read_config
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
In drivers/pci/controller/pci-ftpci100.c (c08a82d0)
Location: drivers/pci/controller/pci-ftpci100.c:189
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_unmask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_mask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_ack_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_read_config
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
In drivers/pci/controller/pci-ftpci100.c (c000000000891308)
Location: drivers/pci/controller/pci-ftpci100.c:189
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_unmask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_mask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_ack_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_read_config
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
In drivers/pci/controller/pci-ftpci100.c (ffffffe0004e6546)
Location: drivers/pci/controller/pci-ftpci100.c:189
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_unmask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_mask_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_ack_irq
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_read_config
```
</details>
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
