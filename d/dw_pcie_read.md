# Function: <code>dw_pcie_read</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_read(void *addr, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware.c (ffffffff814d2e90)
Location: drivers/pci/dwc/pcie-designware.c:26
Inline: True
```
**Symbols:**

```
ffffffff814d2e90-ffffffff814d2ede: dw_pcie_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_read(void *addr, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware.c (ffffffff81513320)
Location: drivers/pci/dwc/pcie-designware.c:26
Inline: True
```
**Symbols:**

```
ffffffff81513320-ffffffff8151337a: dw_pcie_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_read(void *addr, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81548700)
Location: drivers/pci/controller/dwc/pcie-designware.c:23
Inline: True
```
**Symbols:**

```
ffffffff81548700-ffffffff8154875a: dw_pcie_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_read(void *addr, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8155edc0)
Location: drivers/pci/controller/dwc/pcie-designware.c:23
Inline: True
```
**Symbols:**

```
ffffffff8155edc0-ffffffff8155ee1a: dw_pcie_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_read(void *addr, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8158f240)
Location: drivers/pci/controller/dwc/pcie-designware.c:17
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi2
```
**Symbols:**

```
ffffffff8158f240-ffffffff8158f290: dw_pcie_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_read(void *addr, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815b0e60)
Location: drivers/pci/controller/dwc/pcie-designware.c:97
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi2
```
**Symbols:**

```
ffffffff815b0e60-ffffffff815b0eb0: dw_pcie_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_read(void *addr, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165a9b4)
Location: drivers/pci/controller/dwc/pcie-designware.c:98
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi2
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi2
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_handle_msi_irq
```
**Symbols:**

```
ffffffff8165a390-ffffffff8165a3e0: dw_pcie_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_read(void *addr, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8167a720)
Location: drivers/pci/controller/dwc/pcie-designware.c:99
Inline: True
```
**Symbols:**

```
ffffffff8167a720-ffffffff8167a770: dw_pcie_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_read(void *addr, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165d220)
Location: drivers/pci/controller/dwc/pcie-designware.c:99
Inline: True
```
**Symbols:**

```
ffffffff8165d220-ffffffff8165d27e: dw_pcie_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_read(void *addr, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff816cfc90)
Location: drivers/pci/controller/dwc/pcie-designware.c:99
Inline: True
```
**Symbols:**

```
ffffffff816cfc90-ffffffff816cfcee: dw_pcie_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_read(void *addr, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff817f8c79)
Location: drivers/pci/controller/dwc/pcie-designware.c:99
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi
```
**Symbols:**

```
ffffffff817f89a0-ffffffff817f8a26: dw_pcie_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_read(void *addr, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81924bf2)
Location: drivers/pci/controller/dwc/pcie-designware.c:271
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_readl_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi
```
**Symbols:**

```
ffffffff81924770-ffffffff819247f6: dw_pcie_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_read(void *addr, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81969d06)
Location: drivers/pci/controller/dwc/pcie-designware.c:284
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_readl_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi
```
**Symbols:**

```
ffffffff81968410-ffffffff81968496: dw_pcie_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_read(void *addr, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b3424)
Location: drivers/pci/controller/dwc/pcie-designware.c:284
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_edma_detect
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_readl_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi
```
**Symbols:**

```
ffffffff819b1c50-ffffffff819b1cd6: dw_pcie_read (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_read(void *addr, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072cd28)
Location: drivers/pci/controller/dwc/pcie-designware.c:97
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi2
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_am654_read_dbi2
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_rd_other_conf
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_read_dbi
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_rd_own_conf
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_rd_own_conf
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_read_dbi
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_rd_other_conf
```
**Symbols:**

```
ffff80001072cd28-ffff80001072ce18: dw_pcie_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_read(void *addr, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (c08b65b0)
Location: drivers/pci/controller/dwc/pcie-designware.c:97
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi2
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_access_other_conf
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_establish_link
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_establish_link
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_rd_own_conf
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_read_dbi
```
**Symbols:**

```
c08b65b0-c08b663c: dw_pcie_read (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_read(void *addr, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e75a0)
Location: drivers/pci/controller/dwc/pcie-designware.c:97
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi2
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_access_other_conf
```
**Symbols:**

```
ffffffe0004e75a0-ffffffe0004e7648: dw_pcie_read (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_read(void *addr, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a4620)
Location: drivers/pci/controller/dwc/pcie-designware.c:97
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi2
```
**Symbols:**

```
ffffffff815a4620-ffffffff815a4670: dw_pcie_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_read(void *addr, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815937c0)
Location: drivers/pci/controller/dwc/pcie-designware.c:97
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi2
```
**Symbols:**

```
ffffffff815937c0-ffffffff81593810: dw_pcie_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_read(void *addr, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a4bb0)
Location: drivers/pci/controller/dwc/pcie-designware.c:97
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi2
```
**Symbols:**

```
ffffffff815a4bb0-ffffffff815a4c00: dw_pcie_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_read(void *addr, int size, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815befb0)
Location: drivers/pci/controller/dwc/pcie-designware.c:97
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_read_dbi2
```
**Symbols:**

```
ffffffff815befb0-ffffffff815bf000: dw_pcie_read (STB_GLOBAL)
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
