# Function: <code>pci_ecam_map_bus</code>

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
void *pci_ecam_map_bus(struct pci_bus *bus, unsigned int devfn, int where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ecam.c (ffff800010719818)
Location: drivers/pci/ecam.c:128
Inline: False
Direct callers:
  - drivers/pci/controller/pci-host-generic.c:pci_dw_ecam_map_bus
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_map_bus
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_map_bus
```
**Symbols:**

```
ffff800010719818-ffff8000107198a8: pci_ecam_map_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *pci_ecam_map_bus(struct pci_bus *bus, unsigned int devfn, int where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ecam.c (c08a337c)
Location: drivers/pci/ecam.c:128
Inline: False
Direct callers:
  - drivers/pci/controller/pci-host-generic.c:pci_dw_ecam_map_bus
```
**Symbols:**

```
c08a337c-c08a33dc: pci_ecam_map_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *pci_ecam_map_bus(struct pci_bus *bus, unsigned int devfn, int where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ecam.c (c0000000008895c0)
Location: drivers/pci/ecam.c:128
Inline: False
Direct callers:
  - drivers/pci/controller/pci-host-generic.c:pci_dw_ecam_map_bus
```
**Symbols:**

```
c0000000008895c0-c000000000889628: pci_ecam_map_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *pci_ecam_map_bus(struct pci_bus *bus, unsigned int devfn, int where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ecam.c (ffffffe0004e1458)
Location: drivers/pci/ecam.c:128
Inline: False
Direct callers:
  - drivers/pci/controller/pci-host-generic.c:pci_dw_ecam_map_bus
```
**Symbols:**

```
ffffffe0004e1458-ffffffe0004e14ca: pci_ecam_map_bus (STB_GLOBAL)
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
