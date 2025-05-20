# Function: <code>of_pci_get_devfn</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
int of_pci_get_devfn(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (ffff8000106f9358)
Location: drivers/pci/of.c:153
Inline: False
Direct callers:
  - drivers/pci/of.c:of_pci_find_child_device
  - drivers/pci/of.c:of_pci_find_child_device
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
```
**Symbols:**

```
ffff8000106f9358-ffff8000106f93c8: of_pci_get_devfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_pci_get_devfn(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (c0891974)
Location: drivers/pci/of.c:153
Inline: False
Direct callers:
  - drivers/pci/of.c:of_pci_find_child_device
  - drivers/pci/of.c:of_pci_find_child_device
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_parse_dt
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
```
**Symbols:**

```
c0891974-c08919e8: of_pci_get_devfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_pci_get_devfn(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (c0000000008769f0)
Location: drivers/pci/of.c:153
Inline: False
Direct callers:
  - drivers/pci/of.c:of_pci_find_child_device
  - drivers/pci/of.c:of_pci_find_child_device
```
**Symbols:**

```
c0000000008769f0-c000000000876a6c: of_pci_get_devfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_pci_get_devfn(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (ffffffe0004c9824)
Location: drivers/pci/of.c:153
Inline: False
Direct callers:
  - drivers/pci/of.c:of_pci_find_child_device
  - drivers/pci/of.c:of_pci_find_child_device
```
**Symbols:**

```
ffffffe0004c9824-ffffffe0004c9866: of_pci_get_devfn (STB_GLOBAL)
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
