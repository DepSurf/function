# Function: <code>meson_pcie_probe</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int meson_pcie_probe(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81560ad0)
Location: drivers/pci/controller/dwc/pci-meson.c:525
Inline: False
```
**Symbols:**

```
ffffffff81560ad0-ffffffff815611c5: meson_pcie_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int meson_pcie_probe(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (0)
Location: drivers/pci/controller/dwc/pci-meson.c:525
Inline: False
```
**Symbols:**

```
ffffffff81590ed0-ffffffff8159147c: meson_pcie_probe (STB_LOCAL)
ffffffff81591492-ffffffff815915b3: meson_pcie_probe.cold (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int meson_pcie_probe(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (0)
Location: drivers/pci/controller/dwc/pci-meson.c:525
Inline: False
```
**Symbols:**

```
ffffffff815a63c0-ffffffff815a696c: meson_pcie_probe (STB_LOCAL)
ffffffff815a6982-ffffffff815a6aa3: meson_pcie_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int meson_pcie_probe(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (0)
Location: drivers/pci/controller/dwc/pci-meson.c:525
Inline: False
```
**Symbols:**

```
ffffffff81595560-ffffffff81595b0c: meson_pcie_probe (STB_LOCAL)
ffffffff81595b22-ffffffff81595c43: meson_pcie_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int meson_pcie_probe(struct platform_device *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (0)
Location: drivers/pci/controller/dwc/pci-meson.c:525
Inline: False
```
**Symbols:**

```
ffffffff815a6950-ffffffff815a6efc: meson_pcie_probe (STB_LOCAL)
ffffffff815a6f12-ffffffff815a7033: meson_pcie_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
</ul>
