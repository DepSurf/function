# Function: <code>__pci_epc_mem_init</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __pci_epc_mem_init(struct pci_epc *epc, phys_addr_t phys_base, size_t size, size_t page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff81513240)
Location: drivers/pci/endpoint/pci-epc-mem.c:59
Inline: False
```
**Symbols:**

```
ffffffff81513240-ffffffff81513319: __pci_epc_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __pci_epc_mem_init(struct pci_epc *epc, phys_addr_t phys_base, size_t size, size_t page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff81548620)
Location: drivers/pci/endpoint/pci-epc-mem.c:48
Inline: False
```
**Symbols:**

```
ffffffff81548620-ffffffff815486f9: __pci_epc_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __pci_epc_mem_init(struct pci_epc *epc, phys_addr_t phys_base, size_t size, size_t page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8155ece0)
Location: drivers/pci/endpoint/pci-epc-mem.c:48
Inline: False
```
**Symbols:**

```
ffffffff8155ece0-ffffffff8155edb9: __pci_epc_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __pci_epc_mem_init(struct pci_epc *epc, phys_addr_t phys_base, size_t size, size_t page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8158f170)
Location: drivers/pci/endpoint/pci-epc-mem.c:48
Inline: False
```
**Symbols:**

```
ffffffff8158f170-ffffffff8158f23b: __pci_epc_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __pci_epc_mem_init(struct pci_epc *epc, phys_addr_t phys_base, size_t size, size_t page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815b0d90)
Location: drivers/pci/endpoint/pci-epc-mem.c:48
Inline: False
```
**Symbols:**

```
ffffffff815b0d90-ffffffff815b0e5b: __pci_epc_mem_init (STB_GLOBAL)
```
</details>
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
int __pci_epc_mem_init(struct pci_epc *epc, phys_addr_t phys_base, size_t size, size_t page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffff80001071cee0)
Location: drivers/pci/endpoint/pci-epc-mem.c:48
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffff80001071cee0-ffff80001071cfb0: __pci_epc_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __pci_epc_mem_init(struct pci_epc *epc, phys_addr_t phys_base, size_t size, size_t page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (c08a5fa0)
Location: drivers/pci/endpoint/pci-epc-mem.c:48
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
c08a5fa0-c08a6050: __pci_epc_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __pci_epc_mem_init(struct pci_epc *epc, phys_addr_t phys_base, size_t size, size_t page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (c00000000088db40)
Location: drivers/pci/endpoint/pci-epc-mem.c:48
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
**Symbols:**

```
c00000000088db40-c00000000088dc50: __pci_epc_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __pci_epc_mem_init(struct pci_epc *epc, phys_addr_t phys_base, size_t size, size_t page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffe0004e38ba)
Location: drivers/pci/endpoint/pci-epc-mem.c:48
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffe0004e38ba-ffffffe0004e39b6: __pci_epc_mem_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __pci_epc_mem_init(struct pci_epc *epc, phys_addr_t phys_base, size_t size, size_t page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815a4550)
Location: drivers/pci/endpoint/pci-epc-mem.c:48
Inline: False
```
**Symbols:**

```
ffffffff815a4550-ffffffff815a461b: __pci_epc_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __pci_epc_mem_init(struct pci_epc *epc, phys_addr_t phys_base, size_t size, size_t page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815936f0)
Location: drivers/pci/endpoint/pci-epc-mem.c:48
Inline: False
```
**Symbols:**

```
ffffffff815936f0-ffffffff815937bb: __pci_epc_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __pci_epc_mem_init(struct pci_epc *epc, phys_addr_t phys_base, size_t size, size_t page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815a4ae0)
Location: drivers/pci/endpoint/pci-epc-mem.c:48
Inline: False
```
**Symbols:**

```
ffffffff815a4ae0-ffffffff815a4bab: __pci_epc_mem_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __pci_epc_mem_init(struct pci_epc *epc, phys_addr_t phys_base, size_t size, size_t page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815beee0)
Location: drivers/pci/endpoint/pci-epc-mem.c:48
Inline: False
```
**Symbols:**

```
ffffffff815beee0-ffffffff815befab: __pci_epc_mem_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
