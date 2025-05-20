# Function: <code>meson_pcie_link_up</code>

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
int meson_pcie_link_up(struct dw_pcie *pci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815606f0)
Location: drivers/pci/controller/dwc/pci-meson.c:433
Inline: False
```
**Symbols:**

```
ffffffff815606f0-ffffffff81560837: meson_pcie_link_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int meson_pcie_link_up(struct dw_pcie *pci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (0)
Location: drivers/pci/controller/dwc/pci-meson.c:433
Inline: False
```
**Symbols:**

```
ffffffff81590b10-ffffffff81590c2b: meson_pcie_link_up (STB_LOCAL)
ffffffff8159147c-ffffffff81591492: meson_pcie_link_up.cold (STB_LOCAL)
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
int meson_pcie_link_up(struct dw_pcie *pci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (0)
Location: drivers/pci/controller/dwc/pci-meson.c:433
Inline: False
```
**Symbols:**

```
ffffffff815a6000-ffffffff815a611b: meson_pcie_link_up (STB_LOCAL)
ffffffff815a696c-ffffffff815a6982: meson_pcie_link_up.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int meson_pcie_link_up(struct dw_pcie *pci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (0)
Location: drivers/pci/controller/dwc/pci-meson.c:433
Inline: False
```
**Symbols:**

```
ffffffff815951a0-ffffffff815952bb: meson_pcie_link_up (STB_LOCAL)
ffffffff81595b0c-ffffffff81595b22: meson_pcie_link_up.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int meson_pcie_link_up(struct dw_pcie *pci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (0)
Location: drivers/pci/controller/dwc/pci-meson.c:433
Inline: False
```
**Symbols:**

```
ffffffff815a6590-ffffffff815a66ab: meson_pcie_link_up (STB_LOCAL)
ffffffff815a6efc-ffffffff815a6f12: meson_pcie_link_up.cold (STB_LOCAL)
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
