# Function: <code>pci_epc_mem_exit</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff814d2ca0)
Location: drivers/pci/endpoint/pci-epc-mem.c:79
Inline: False
```
**Symbols:**

```
ffffffff814d2ca0-ffffffff814d2cd0: pci_epc_mem_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815130a0)
Location: drivers/pci/endpoint/pci-epc-mem.c:113
Inline: False
```
**Symbols:**

```
ffffffff815130a0-ffffffff815130d0: pci_epc_mem_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff81548490)
Location: drivers/pci/endpoint/pci-epc-mem.c:102
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff81548490-ffffffff815484c0: pci_epc_mem_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8155eb50)
Location: drivers/pci/endpoint/pci-epc-mem.c:102
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff8155eb50-ffffffff8155eb80: pci_epc_mem_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8158efd0)
Location: drivers/pci/endpoint/pci-epc-mem.c:102
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff8158efd0-ffffffff8158f003: pci_epc_mem_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815b0bf0)
Location: drivers/pci/endpoint/pci-epc-mem.c:102
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff815b0bf0-ffffffff815b0c23: pci_epc_mem_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff81659e70)
Location: drivers/pci/endpoint/pci-epc-mem.c:138
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff81659e70-ffffffff81659ef3: pci_epc_mem_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8167a220)
Location: drivers/pci/endpoint/pci-epc-mem.c:138
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff8167a220-ffffffff8167a2a3: pci_epc_mem_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8165cd20)
Location: drivers/pci/endpoint/pci-epc-mem.c:138
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff8165cd20-ffffffff8165cda3: pci_epc_mem_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff816cf740)
Location: drivers/pci/endpoint/pci-epc-mem.c:138
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff816cf740-ffffffff816cf7c3: pci_epc_mem_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff817f8460)
Location: drivers/pci/endpoint/pci-epc-mem.c:138
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff817f8460-ffffffff817f84f7: pci_epc_mem_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff819241d0)
Location: drivers/pci/endpoint/pci-epc-mem.c:138
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff819241d0-ffffffff81924267: pci_epc_mem_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff81967e80)
Location: drivers/pci/endpoint/pci-epc-mem.c:138
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff81967e80-ffffffff81967f17: pci_epc_mem_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff819b15e0)
Location: drivers/pci/endpoint/pci-epc-mem.c:148
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff819b15e0-ffffffff819b1677: pci_epc_mem_exit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffff80001071cbf0)
Location: drivers/pci/endpoint/pci-epc-mem.c:102
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffff80001071cbf0-ffff80001071cc2c: pci_epc_mem_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (c08a5e10)
Location: drivers/pci/endpoint/pci-epc-mem.c:102
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
c08a5e10-c08a5e44: pci_epc_mem_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (c00000000088d8b0)
Location: drivers/pci/endpoint/pci-epc-mem.c:102
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
**Symbols:**

```
c00000000088d8b0-c00000000088d908: pci_epc_mem_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffe0004e3878)
Location: drivers/pci/endpoint/pci-epc-mem.c:102
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffe0004e3878-ffffffe0004e38ba: pci_epc_mem_exit (STB_GLOBAL)
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
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815a43b0)
Location: drivers/pci/endpoint/pci-epc-mem.c:102
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff815a43b0-ffffffff815a43e3: pci_epc_mem_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff81593550)
Location: drivers/pci/endpoint/pci-epc-mem.c:102
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff81593550-ffffffff81593583: pci_epc_mem_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815a4940)
Location: drivers/pci/endpoint/pci-epc-mem.c:102
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff815a4940-ffffffff815a4973: pci_epc_mem_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_epc_mem_exit(struct pci_epc *epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815bed40)
Location: drivers/pci/endpoint/pci-epc-mem.c:102
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff815bed40-ffffffff815bed73: pci_epc_mem_exit (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
