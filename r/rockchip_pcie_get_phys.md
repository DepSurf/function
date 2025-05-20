# Function: <code>rockchip_pcie_get_phys</code>

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
int rockchip_pcie_get_phys(struct rockchip_pcie *rockchip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-rockchip.c (ffff8000107287b8)
Location: drivers/pci/controller/pcie-rockchip.c:298
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
```
**Symbols:**

```
ffff8000107287b8-ffff8000107288fc: rockchip_pcie_get_phys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rockchip_pcie_get_phys(struct rockchip_pcie *rockchip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-rockchip.c (c08b3688)
Location: drivers/pci/controller/pcie-rockchip.c:298
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
```
**Symbols:**

```
c08b3688-c08b37c0: rockchip_pcie_get_phys (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
