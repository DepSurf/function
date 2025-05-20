# Function: <code>msi_domain_free_msi_descs_range</code>

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
void msi_domain_free_msi_descs_range(struct device *dev, unsigned int domid, unsigned int first, unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811a4e70)
Location: kernel/irq/msi.c:209
Inline: False
Direct callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_teardown_msi_irqs
  - drivers/base/platform-msi.c:platform_msi_device_domain_free
```
**Symbols:**

```
ffffffff811a4e70-ffffffff811a4ec9: msi_domain_free_msi_descs_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void msi_domain_free_msi_descs_range(struct device *dev, unsigned int domid, unsigned int first, unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811b6de0)
Location: kernel/irq/msi.c:209
Inline: False
Direct callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_teardown_msi_irqs
  - drivers/base/platform-msi.c:platform_msi_device_domain_free
```
**Symbols:**

```
ffffffff811b6de0-ffffffff811b6e39: msi_domain_free_msi_descs_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void msi_domain_free_msi_descs_range(struct device *dev, unsigned int domid, unsigned int first, unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811c6ca0)
Location: kernel/irq/msi.c:209
Inline: False
Direct callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_teardown_msi_irqs
  - drivers/base/platform-msi.c:platform_msi_device_domain_free
```
**Symbols:**

```
ffffffff811c6ca0-ffffffff811c6cf9: msi_domain_free_msi_descs_range (STB_GLOBAL)
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
