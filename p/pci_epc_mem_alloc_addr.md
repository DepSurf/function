# Function: <code>pci_epc_mem_alloc_addr</code>

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
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff814d2cd0)
Location: drivers/pci/endpoint/pci-epc-mem.c:98
Inline: False
```
**Symbols:**

```
ffffffff814d2cd0-ffffffff814d2d7f: pci_epc_mem_alloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff81513100)
Location: drivers/pci/endpoint/pci-epc-mem.c:132
Inline: False
```
**Symbols:**

```
ffffffff81513100-ffffffff815131c4: pci_epc_mem_alloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815484f0)
Location: drivers/pci/endpoint/pci-epc-mem.c:121
Inline: False
```
**Symbols:**

```
ffffffff815484f0-ffffffff815485ac: pci_epc_mem_alloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8155ebb0)
Location: drivers/pci/endpoint/pci-epc-mem.c:121
Inline: False
```
**Symbols:**

```
ffffffff8155ebb0-ffffffff8155ec6c: pci_epc_mem_alloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8158f040)
Location: drivers/pci/endpoint/pci-epc-mem.c:121
Inline: False
```
**Symbols:**

```
ffffffff8158f040-ffffffff8158f0f8: pci_epc_mem_alloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815b0c60)
Location: drivers/pci/endpoint/pci-epc-mem.c:121
Inline: False
```
**Symbols:**

```
ffffffff815b0c60-ffffffff815b0d18: pci_epc_mem_alloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8165a000)
Location: drivers/pci/endpoint/pci-epc-mem.c:168
Inline: False
```
**Symbols:**

```
ffffffff8165a000-ffffffff8165a112: pci_epc_mem_alloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8167a600)
Location: drivers/pci/endpoint/pci-epc-mem.c:168
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffff8167a600-ffffffff8167a720: pci_epc_mem_alloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8165d100)
Location: drivers/pci/endpoint/pci-epc-mem.c:168
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffff8165d100-ffffffff8165d220: pci_epc_mem_alloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: drivers/pci/endpoint/pci-epc-mem.c:168
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffff81ceb2af-ffffffff81ceb307: pci_epc_mem_alloc_addr.cold (STB_LOCAL)
ffffffff816cfb40-ffffffff816cfc85: pci_epc_mem_alloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: drivers/pci/endpoint/pci-epc-mem.c:168
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffff81eb26d5-ffffffff81eb26f9: pci_epc_mem_alloc_addr.cold (STB_LOCAL)
ffffffff817f8630-ffffffff817f874f: pci_epc_mem_alloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: drivers/pci/endpoint/pci-epc-mem.c:168
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffff820901c1-ffffffff820901e5: pci_epc_mem_alloc_addr.cold (STB_LOCAL)
ffffffff819243d0-ffffffff819244ef: pci_epc_mem_alloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: drivers/pci/endpoint/pci-epc-mem.c:168
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffff8211055f-ffffffff82110583: pci_epc_mem_alloc_addr.cold (STB_LOCAL)
ffffffff81968080-ffffffff8196819f: pci_epc_mem_alloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: drivers/pci/endpoint/pci-epc-mem.c:178
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffff821ee270-ffffffff821ee2e2: pci_epc_mem_alloc_addr.cold (STB_LOCAL)
ffffffff819b16e0-ffffffff819b1894: pci_epc_mem_alloc_addr (STB_GLOBAL)
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
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffff80001071cca8)
Location: drivers/pci/endpoint/pci-epc-mem.c:121
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffff80001071cca8-ffff80001071ce44: pci_epc_mem_alloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (c08a5e80)
Location: drivers/pci/endpoint/pci-epc-mem.c:121
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
c08a5e80-c08a5f28: pci_epc_mem_alloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (c00000000088d940)
Location: drivers/pci/endpoint/pci-epc-mem.c:121
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
**Symbols:**

```
c00000000088d940-c00000000088da90: pci_epc_mem_alloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffe0004e3a70)
Location: drivers/pci/endpoint/pci-epc-mem.c:121
Inline: False
Direct callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffe0004e3a70-ffffffe0004e3b60: pci_epc_mem_alloc_addr (STB_GLOBAL)
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
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815a4420)
Location: drivers/pci/endpoint/pci-epc-mem.c:121
Inline: False
```
**Symbols:**

```
ffffffff815a4420-ffffffff815a44d8: pci_epc_mem_alloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815935c0)
Location: drivers/pci/endpoint/pci-epc-mem.c:121
Inline: False
```
**Symbols:**

```
ffffffff815935c0-ffffffff81593678: pci_epc_mem_alloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815a49b0)
Location: drivers/pci/endpoint/pci-epc-mem.c:121
Inline: False
```
**Symbols:**

```
ffffffff815a49b0-ffffffff815a4a68: pci_epc_mem_alloc_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *pci_epc_mem_alloc_addr(struct pci_epc *epc, phys_addr_t *phys_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815bedb0)
Location: drivers/pci/endpoint/pci-epc-mem.c:121
Inline: False
```
**Symbols:**

```
ffffffff815bedb0-ffffffff815bee68: pci_epc_mem_alloc_addr (STB_GLOBAL)
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
