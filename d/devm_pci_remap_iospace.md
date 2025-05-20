# Function: <code>devm_pci_remap_iospace</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int devm_pci_remap_iospace(struct device *dev, const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151afb0)
Location: drivers/pci/pci.c:3637
Inline: False
```
**Symbols:**

```
ffffffff8151afb0-ffffffff8151b009: devm_pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int devm_pci_remap_iospace(struct device *dev, const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81530d20)
Location: drivers/pci/pci.c:3902
Inline: False
```
**Symbols:**

```
ffffffff81530d20-ffffffff81530d79: devm_pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int devm_pci_remap_iospace(struct device *dev, const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81560660)
Location: drivers/pci/pci.c:4000
Inline: False
```
**Symbols:**

```
ffffffff81560660-ffffffff815606bb: devm_pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devm_pci_remap_iospace(struct device *dev, const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81581780)
Location: drivers/pci/pci.c:3996
Inline: False
```
**Symbols:**

```
ffffffff81581780-ffffffff815817db: devm_pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devm_pci_remap_iospace(struct device *dev, const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81626160)
Location: drivers/pci/pci.c:4067
Inline: False
```
**Symbols:**

```
ffffffff81626160-ffffffff816261c8: devm_pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devm_pci_remap_iospace(struct device *dev, const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164be70)
Location: drivers/pci/pci.c:4135
Inline: False
```
**Symbols:**

```
ffffffff8164be70-ffffffff8164bed8: devm_pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devm_pci_remap_iospace(struct device *dev, const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162eaf0)
Location: drivers/pci/pci.c:4167
Inline: False
```
**Symbols:**

```
ffffffff8162eaf0-ffffffff8162eb58: devm_pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devm_pci_remap_iospace(struct device *dev, const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4217
Inline: False
```
**Symbols:**

```
ffffffff81ce46c6-ffffffff81ce46da: devm_pci_remap_iospace.cold (STB_LOCAL)
ffffffff8169ee10-ffffffff8169ee8b: devm_pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devm_pci_remap_iospace(struct device *dev, const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4313
Inline: False
```
**Symbols:**

```
ffffffff81eab054-ffffffff81eab071: devm_pci_remap_iospace.cold (STB_LOCAL)
ffffffff817c0c70-ffffffff817c0d06: devm_pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devm_pci_remap_iospace(struct device *dev, const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4256
Inline: False
```
**Symbols:**

```
ffffffff8208f085-ffffffff8208f0a2: devm_pci_remap_iospace.cold (STB_LOCAL)
ffffffff818dd560-ffffffff818dd5f6: devm_pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devm_pci_remap_iospace(struct device *dev, const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4294
Inline: False
```
**Symbols:**

```
ffffffff8210f3d0-ffffffff8210f3ed: devm_pci_remap_iospace.cold (STB_LOCAL)
ffffffff819205d0-ffffffff81920666: devm_pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int devm_pci_remap_iospace(struct device *dev, const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4404
Inline: False
```
**Symbols:**

```
ffffffff821ed057-ffffffff821ed074: devm_pci_remap_iospace.cold (STB_LOCAL)
ffffffff81968760-ffffffff819687f6: devm_pci_remap_iospace (STB_GLOBAL)
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
int devm_pci_remap_iospace(struct device *dev, const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e5da0)
Location: drivers/pci/pci.c:3996
Inline: False
Direct callers:
  - drivers/pci/of.c:pci_parse_request_of_pci_ranges
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
```
**Symbols:**

```
ffff8000106e5da0-ffff8000106e5e40: devm_pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devm_pci_remap_iospace(struct device *dev, const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087eb08)
Location: drivers/pci/pci.c:3996
Inline: False
Direct callers:
  - drivers/pci/of.c:pci_parse_request_of_pci_ranges
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
c087eb08-c087eb8c: devm_pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devm_pci_remap_iospace(struct device *dev, const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085ef90)
Location: drivers/pci/pci.c:3996
Inline: False
Direct callers:
  - drivers/pci/of.c:pci_parse_request_of_pci_ranges
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
**Symbols:**

```
c00000000085ef90-c00000000085f018: devm_pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devm_pci_remap_iospace(struct device *dev, const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004ba5ca)
Location: drivers/pci/pci.c:3996
Inline: False
Direct callers:
  - drivers/pci/of.c:pci_parse_request_of_pci_ranges
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffe0004ba5ca-ffffffe0004ba64a: devm_pci_remap_iospace (STB_GLOBAL)
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
int devm_pci_remap_iospace(struct device *dev, const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81575ca0)
Location: drivers/pci/pci.c:3996
Inline: False
```
**Symbols:**

```
ffffffff81575ca0-ffffffff81575cfb: devm_pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devm_pci_remap_iospace(struct device *dev, const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81564400)
Location: drivers/pci/pci.c:3996
Inline: False
```
**Symbols:**

```
ffffffff81564400-ffffffff8156445b: devm_pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devm_pci_remap_iospace(struct device *dev, const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815754d0)
Location: drivers/pci/pci.c:3996
Inline: False
```
**Symbols:**

```
ffffffff815754d0-ffffffff8157552b: devm_pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devm_pci_remap_iospace(struct device *dev, const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158faa0)
Location: drivers/pci/pci.c:3996
Inline: False
```
**Symbols:**

```
ffffffff8158faa0-ffffffff8158fafb: devm_pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
