# Function: <code>pci_epc_mem_free_addr</code>

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
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff814d2d80)
Location: drivers/pci/endpoint/pci-epc-mem.c:128
Inline: False
```
**Symbols:**

```
ffffffff814d2d80-ffffffff814d2dd2: pci_epc_mem_free_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815131d0)
Location: drivers/pci/endpoint/pci-epc-mem.c:166
Inline: False
```
**Symbols:**

```
ffffffff815131d0-ffffffff8151323a: pci_epc_mem_free_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815485b0)
Location: drivers/pci/endpoint/pci-epc-mem.c:155
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff815485b0-ffffffff8154861a: pci_epc_mem_free_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8155ec70)
Location: drivers/pci/endpoint/pci-epc-mem.c:155
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff8155ec70-ffffffff8155ecda: pci_epc_mem_free_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8158f100)
Location: drivers/pci/endpoint/pci-epc-mem.c:155
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff8158f100-ffffffff8158f16d: pci_epc_mem_free_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815b0d20)
Location: drivers/pci/endpoint/pci-epc-mem.c:155
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff815b0d20-ffffffff815b0d8d: pci_epc_mem_free_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff81659f30)
Location: drivers/pci/endpoint/pci-epc-mem.c:234
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff81659f30-ffffffff81659ff4: pci_epc_mem_free_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8167a2b0)
Location: drivers/pci/endpoint/pci-epc-mem.c:234
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff8167a2b0-ffffffff8167a38a: pci_epc_mem_free_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff8165cdb0)
Location: drivers/pci/endpoint/pci-epc-mem.c:234
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff8165cdb0-ffffffff8165ce8a: pci_epc_mem_free_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: drivers/pci/endpoint/pci-epc-mem.c:234
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff81ceb260-ffffffff81ceb293: pci_epc_mem_free_addr.cold (STB_LOCAL)
ffffffff816cf7d0-ffffffff816cf8c1: pci_epc_mem_free_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: drivers/pci/endpoint/pci-epc-mem.c:234
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff81eb26be-ffffffff81eb26d5: pci_epc_mem_free_addr.cold (STB_LOCAL)
ffffffff817f8540-ffffffff817f8622: pci_epc_mem_free_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: drivers/pci/endpoint/pci-epc-mem.c:234
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff820901aa-ffffffff820901c1: pci_epc_mem_free_addr.cold (STB_LOCAL)
ffffffff819242d0-ffffffff819243b2: pci_epc_mem_free_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: drivers/pci/endpoint/pci-epc-mem.c:234
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff82110548-ffffffff8211055f: pci_epc_mem_free_addr.cold (STB_LOCAL)
ffffffff81967f80-ffffffff81968062: pci_epc_mem_free_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (0)
Location: drivers/pci/endpoint/pci-epc-mem.c:244
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff821ee2fe-ffffffff821ee32e: pci_epc_mem_free_addr.cold (STB_LOCAL)
ffffffff819b1b40-ffffffff819b1c3a: pci_epc_mem_free_addr (STB_GLOBAL)
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
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffff80001071ce48)
Location: drivers/pci/endpoint/pci-epc-mem.c:155
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffff80001071ce48-ffff80001071cee0: pci_epc_mem_free_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (c08a5f28)
Location: drivers/pci/endpoint/pci-epc-mem.c:155
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
c08a5f28-c08a5fa0: pci_epc_mem_free_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (c00000000088da90)
Location: drivers/pci/endpoint/pci-epc-mem.c:155
Inline: False
```
**Symbols:**

```
c00000000088da90-c00000000088db38: pci_epc_mem_free_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffe0004e3b60)
Location: drivers/pci/endpoint/pci-epc-mem.c:155
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffe0004e3b60-ffffffe0004e3c20: pci_epc_mem_free_addr (STB_GLOBAL)
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
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815a44e0)
Location: drivers/pci/endpoint/pci-epc-mem.c:155
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff815a44e0-ffffffff815a454d: pci_epc_mem_free_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff81593680)
Location: drivers/pci/endpoint/pci-epc-mem.c:155
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff81593680-ffffffff815936ed: pci_epc_mem_free_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815a4a70)
Location: drivers/pci/endpoint/pci-epc-mem.c:155
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff815a4a70-ffffffff815a4add: pci_epc_mem_free_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_epc_mem_free_addr(struct pci_epc *epc, phys_addr_t phys_addr, void *virt_addr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff815bee70)
Location: drivers/pci/endpoint/pci-epc-mem.c:155
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_exit
```
**Symbols:**

```
ffffffff815bee70-ffffffff815beedd: pci_epc_mem_free_addr (STB_GLOBAL)
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
