# Function: <code>msi_match_device_irq_domain</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool msi_match_device_irq_domain(struct device *dev, unsigned int domid, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811a5490)
Location: kernel/irq/msi.c:1047
Inline: False
Direct callers:
  - drivers/pci/msi/irqdomain.c:pci_setup_msix_device_domain
  - drivers/pci/msi/irqdomain.c:pci_setup_msix_device_domain
  - drivers/pci/msi/irqdomain.c:pci_setup_msi_device_domain
  - drivers/pci/msi/irqdomain.c:pci_setup_msi_device_domain
```
**Symbols:**

```
ffffffff811a5490-ffffffff811a550f: msi_match_device_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool msi_match_device_irq_domain(struct device *dev, unsigned int domid, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811b76a0)
Location: kernel/irq/msi.c:1044
Inline: False
Direct callers:
  - drivers/pci/msi/irqdomain.c:pci_setup_msix_device_domain
  - drivers/pci/msi/irqdomain.c:pci_setup_msix_device_domain
  - drivers/pci/msi/irqdomain.c:pci_setup_msi_device_domain
  - drivers/pci/msi/irqdomain.c:pci_setup_msi_device_domain
```
**Symbols:**

```
ffffffff811b76a0-ffffffff811b7765: msi_match_device_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool msi_match_device_irq_domain(struct device *dev, unsigned int domid, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811c7560)
Location: kernel/irq/msi.c:1044
Inline: False
Direct callers:
  - drivers/pci/msi/irqdomain.c:pci_setup_msix_device_domain
  - drivers/pci/msi/irqdomain.c:pci_setup_msix_device_domain
  - drivers/pci/msi/irqdomain.c:pci_setup_msi_device_domain
  - drivers/pci/msi/irqdomain.c:pci_setup_msi_device_domain
```
**Symbols:**

```
ffffffff811c7560-ffffffff811c7625: msi_match_device_irq_domain (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
