# Function: <code>cdns_pcie_ep_map_addr</code>

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
int cdns_pcie_ep_map_addr(struct pci_epc *epc, u8 fn, phys_addr_t addr, u64 pci_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071e500)
Location: drivers/pci/controller/pcie-cadence-ep.c:174
Inline: False
```
**Symbols:**

```
ffff80001071e500-ffff80001071e5e0: cdns_pcie_ep_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cdns_pcie_ep_map_addr(struct pci_epc *epc, u8 fn, phys_addr_t addr, u64 pci_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-cadence-ep.c (c08a7194)
Location: drivers/pci/controller/pcie-cadence-ep.c:174
Inline: False
```
**Symbols:**

```
c08a7194-c08a7248: cdns_pcie_ep_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cdns_pcie_ep_map_addr(struct pci_epc *epc, u8 fn, phys_addr_t addr, u64 pci_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088f220)
Location: drivers/pci/controller/pcie-cadence-ep.c:174
Inline: False
```
**Symbols:**

```
c00000000088f220-c00000000088f344: cdns_pcie_ep_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cdns_pcie_ep_map_addr(struct pci_epc *epc, u8 fn, phys_addr_t addr, u64 pci_addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-cadence-ep.c (ffffffe0004e50bc)
Location: drivers/pci/controller/pcie-cadence-ep.c:174
Inline: False
```
**Symbols:**

```
ffffffe0004e50bc-ffffffe0004e518c: cdns_pcie_ep_map_addr (STB_LOCAL)
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
