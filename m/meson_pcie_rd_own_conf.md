# Function: <code>meson_pcie_rd_own_conf</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int meson_pcie_rd_own_conf(struct pcie_port *pp, int where, int size, u32 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81560890)
Location: drivers/pci/controller/dwc/pci-meson.c:398
Inline: True
```
**Symbols:**

```
ffffffff81560890-ffffffff81560927: meson_pcie_rd_own_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int meson_pcie_rd_own_conf(struct pcie_port *pp, int where, int size, u32 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81590c80)
Location: drivers/pci/controller/dwc/pci-meson.c:398
Inline: True
```
**Symbols:**

```
ffffffff81590c80-ffffffff81590d17: meson_pcie_rd_own_conf (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int meson_pcie_rd_own_conf(struct pcie_port *pp, int where, int size, u32 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a6170)
Location: drivers/pci/controller/dwc/pci-meson.c:398
Inline: True
```
**Symbols:**

```
ffffffff815a6170-ffffffff815a6207: meson_pcie_rd_own_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int meson_pcie_rd_own_conf(struct pcie_port *pp, int where, int size, u32 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81595310)
Location: drivers/pci/controller/dwc/pci-meson.c:398
Inline: True
```
**Symbols:**

```
ffffffff81595310-ffffffff815953a7: meson_pcie_rd_own_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int meson_pcie_rd_own_conf(struct pcie_port *pp, int where, int size, u32 *val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a6700)
Location: drivers/pci/controller/dwc/pci-meson.c:398
Inline: True
```
**Symbols:**

```
ffffffff815a6700-ffffffff815a6797: meson_pcie_rd_own_conf (STB_LOCAL)
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
