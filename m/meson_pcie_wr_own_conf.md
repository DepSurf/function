# Function: <code>meson_pcie_wr_own_conf</code>

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
int meson_pcie_wr_own_conf(struct pcie_port *pp, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81560860)
Location: drivers/pci/controller/dwc/pci-meson.c:425
Inline: False
```
**Symbols:**

```
ffffffff81560860-ffffffff81560882: meson_pcie_wr_own_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int meson_pcie_wr_own_conf(struct pcie_port *pp, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81590c50)
Location: drivers/pci/controller/dwc/pci-meson.c:425
Inline: False
```
**Symbols:**

```
ffffffff81590c50-ffffffff81590c72: meson_pcie_wr_own_conf (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int meson_pcie_wr_own_conf(struct pcie_port *pp, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a6140)
Location: drivers/pci/controller/dwc/pci-meson.c:425
Inline: False
```
**Symbols:**

```
ffffffff815a6140-ffffffff815a6162: meson_pcie_wr_own_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int meson_pcie_wr_own_conf(struct pcie_port *pp, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815952e0)
Location: drivers/pci/controller/dwc/pci-meson.c:425
Inline: False
```
**Symbols:**

```
ffffffff815952e0-ffffffff81595302: meson_pcie_wr_own_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int meson_pcie_wr_own_conf(struct pcie_port *pp, int where, int size, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a66d0)
Location: drivers/pci/controller/dwc/pci-meson.c:425
Inline: False
```
**Symbols:**

```
ffffffff815a66d0-ffffffff815a66f2: meson_pcie_wr_own_conf (STB_LOCAL)
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
