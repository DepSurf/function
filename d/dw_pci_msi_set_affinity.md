# Function: <code>dw_pci_msi_set_affinity</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dw_pci_msi_set_affinity(struct irq_data *irq_data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81548e80)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:149
Inline: False
```
**Symbols:**

```
ffffffff81548e80-ffffffff81548e90: dw_pci_msi_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dw_pci_msi_set_affinity(struct irq_data *irq_data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8155f560)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:146
Inline: False
```
**Symbols:**

```
ffffffff8155f560-ffffffff8155f570: dw_pci_msi_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:140
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:141
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:142
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dw_pci_msi_set_affinity(struct irq_data *d, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8167b4a0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:119
Inline: False
```
**Symbols:**

```
ffffffff8167b4a0-ffffffff8167b4b0: dw_pci_msi_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dw_pci_msi_set_affinity(struct irq_data *d, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165e330)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:119
Inline: False
```
**Symbols:**

```
ffffffff8165e330-ffffffff8165e340: dw_pci_msi_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dw_pci_msi_set_affinity(struct irq_data *d, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d0e00)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:118
Inline: False
```
**Symbols:**

```
ffffffff816d0e00-ffffffff816d0e10: dw_pci_msi_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dw_pci_msi_set_affinity(struct irq_data *d, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817f9d80)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:118
Inline: False
```
**Symbols:**

```
ffffffff817f9d80-ffffffff817f9d94: dw_pci_msi_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dw_pci_msi_set_affinity(struct irq_data *d, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819261e0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:117
Inline: False
```
**Symbols:**

```
ffffffff819261e0-ffffffff819261f4: dw_pci_msi_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dw_pci_msi_set_affinity(struct irq_data *d, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8196a3c0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:117
Inline: False
```
**Symbols:**

```
ffffffff8196a3c0-ffffffff8196a3d4: dw_pci_msi_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dw_pci_msi_set_affinity(struct irq_data *d, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b3b80)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:119
Inline: False
```
**Symbols:**

```
ffffffff819b3b80-ffffffff819b3b94: dw_pci_msi_set_affinity (STB_LOCAL)
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
int dw_pci_msi_set_affinity(struct irq_data *d, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072dc70)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:141
Inline: False
```
**Symbols:**

```
ffff80001072dc70-ffff80001072dc8c: dw_pci_msi_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dw_pci_msi_set_affinity(struct irq_data *d, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b73c8)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:141
Inline: False
```
**Symbols:**

```
c08b73c8-c08b73e4: dw_pci_msi_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dw_pci_msi_set_affinity(struct irq_data *d, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e82e0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:141
Inline: False
```
**Symbols:**

```
ffffffe0004e82e0-ffffffe0004e82fc: dw_pci_msi_set_affinity (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:141
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:141
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:141
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: drivers/pci/controller/dwc/pcie-designware-host.c:141
Inline: False
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
</ul>
