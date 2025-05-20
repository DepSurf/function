# Function: <code>of_msi_get_domain</code>

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
struct irq_domain *of_msi_get_domain(struct device *dev, struct device_node *np, enum irq_domain_bus_token token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (ffff800010b75410)
Location: drivers/of/irq.c:641
Inline: True
Direct callers:
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_subset_probe
  - drivers/bus/fsl-mc/fsl-mc-msi.c:fsl_mc_find_msi_domain
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
  - drivers/of/irq.c:of_msi_configure
```
**Symbols:**

```
ffff800010b75410-ffff800010b75538: of_msi_get_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *of_msi_get_domain(struct device *dev, struct device_node *np, enum irq_domain_bus_token token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (c0c57874)
Location: drivers/of/irq.c:641
Inline: True
Direct callers:
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
  - drivers/of/irq.c:of_msi_configure
```
**Symbols:**

```
c0c57874-c0c579a0: of_msi_get_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *of_msi_get_domain(struct device *dev, struct device_node *np, enum irq_domain_bus_token token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (c000000000c52950)
Location: drivers/of/irq.c:641
Inline: True
Direct callers:
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
  - drivers/of/irq.c:of_msi_configure
```
**Symbols:**

```
c000000000c52950-c000000000c52acc: of_msi_get_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *of_msi_get_domain(struct device *dev, struct device_node *np, enum irq_domain_bus_token token);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (ffffffe000728bb2)
Location: drivers/of/irq.c:641
Inline: True
Direct callers:
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
  - drivers/of/irq.c:of_msi_configure
```
**Symbols:**

```
ffffffe000728bb2-ffffffe000728cae: of_msi_get_domain (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
