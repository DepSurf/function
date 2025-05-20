# Function: <code>msi_remove_device_irq_domain</code>

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
void msi_remove_device_irq_domain(struct device *dev, unsigned int domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811a5310)
Location: kernel/irq/msi.c:1014
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_device_data_release
  - kernel/irq/msi.c:msi_device_data_release
  - drivers/pci/msi/irqdomain.c:pci_setup_msix_device_domain
  - drivers/pci/msi/irqdomain.c:pci_setup_msi_device_domain
```
**Symbols:**

```
ffffffff811a5310-ffffffff811a53f2: msi_remove_device_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void msi_remove_device_irq_domain(struct device *dev, unsigned int domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811b74f0)
Location: kernel/irq/msi.c:1011
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_device_data_release
  - kernel/irq/msi.c:msi_device_data_release
  - drivers/pci/msi/irqdomain.c:pci_setup_msix_device_domain
  - drivers/pci/msi/irqdomain.c:pci_setup_msi_device_domain
```
**Symbols:**

```
ffffffff811b74f0-ffffffff811b7606: msi_remove_device_irq_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void msi_remove_device_irq_domain(struct device *dev, unsigned int domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811c73b0)
Location: kernel/irq/msi.c:1011
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_device_data_release
  - kernel/irq/msi.c:msi_device_data_release
  - drivers/pci/msi/irqdomain.c:pci_setup_msix_device_domain
  - drivers/pci/msi/irqdomain.c:pci_setup_msi_device_domain
```
**Symbols:**

```
ffffffff811c73b0-ffffffff811c74c6: msi_remove_device_irq_domain (STB_GLOBAL)
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
