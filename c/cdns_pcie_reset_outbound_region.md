# Function: <code>cdns_pcie_reset_outbound_region</code>

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
void cdns_pcie_reset_outbound_region(struct cdns_pcie *pcie, u32 r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-cadence.c (ffff80001071d208)
Location: drivers/pci/controller/pcie-cadence.c:116
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_unmap_addr
```
**Symbols:**

```
ffff80001071d208-ffff80001071d2ac: cdns_pcie_reset_outbound_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cdns_pcie_reset_outbound_region(struct cdns_pcie *pcie, u32 r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-cadence.c (c08a62bc)
Location: drivers/pci/controller/pcie-cadence.c:116
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_unmap_addr
```
**Symbols:**

```
c08a62bc-c08a6374: cdns_pcie_reset_outbound_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cdns_pcie_reset_outbound_region(struct cdns_pcie *pcie, u32 r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-cadence.c (c00000000088ded0)
Location: drivers/pci/controller/pcie-cadence.c:116
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_unmap_addr
```
**Symbols:**

```
c00000000088ded0-c00000000088dfa4: cdns_pcie_reset_outbound_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cdns_pcie_reset_outbound_region(struct cdns_pcie *pcie, u32 r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-cadence.c (ffffffe0004e3ff0)
Location: drivers/pci/controller/pcie-cadence.c:116
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_unmap_addr
```
**Symbols:**

```
ffffffe0004e3ff0-ffffffe0004e4118: cdns_pcie_reset_outbound_region (STB_GLOBAL)
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
