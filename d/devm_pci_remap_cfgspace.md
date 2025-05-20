# Function: <code>devm_pci_remap_cfgspace</code>

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
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ab5e0)
Location: drivers/pci/pci.c:3469
Inline: False
```
**Symbols:**

```
ffffffff814ab5e0-ffffffff814ab662: devm_pci_remap_cfgspace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ea800)
Location: drivers/pci/pci.c:3484
Inline: False
```
**Symbols:**

```
ffffffff814ea800-ffffffff814ea882: devm_pci_remap_cfgspace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81519ca0)
Location: drivers/pci/pci.c:3668
Inline: False
```
**Symbols:**

```
ffffffff81519ca0-ffffffff81519d2c: devm_pci_remap_cfgspace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8152fa30)
Location: drivers/pci/pci.c:3933
Inline: False
```
**Symbols:**

```
ffffffff8152fa30-ffffffff8152fabc: devm_pci_remap_cfgspace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8155f190)
Location: drivers/pci/pci.c:4031
Inline: False
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
```
**Symbols:**

```
ffffffff8155f190-ffffffff8155f216: devm_pci_remap_cfgspace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815802d0)
Location: drivers/pci/pci.c:4027
Inline: False
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
```
**Symbols:**

```
ffffffff815802d0-ffffffff81580356: devm_pci_remap_cfgspace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81625800)
Location: drivers/pci/pci.c:4098
Inline: False
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
```
**Symbols:**

```
ffffffff81625800-ffffffff81625886: devm_pci_remap_cfgspace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164b600)
Location: drivers/pci/pci.c:4166
Inline: False
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff8164b600-ffffffff8164b686: devm_pci_remap_cfgspace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162e1e0)
Location: drivers/pci/pci.c:4198
Inline: False
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
```
**Symbols:**

```
ffffffff8162e1e0-ffffffff8162e266: devm_pci_remap_cfgspace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169d4a0)
Location: drivers/pci/pci.c:4248
Inline: False
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
```
**Symbols:**

```
ffffffff8169d4a0-ffffffff8169d52d: devm_pci_remap_cfgspace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817bf7b0)
Location: drivers/pci/pci.c:4344
Inline: False
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
```
**Symbols:**

```
ffffffff817bf7b0-ffffffff817bf83c: devm_pci_remap_cfgspace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818dbdc0)
Location: drivers/pci/pci.c:4287
Inline: False
```
**Symbols:**

```
ffffffff818dbdc0-ffffffff818dbe4c: devm_pci_remap_cfgspace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8191ee90)
Location: drivers/pci/pci.c:4325
Inline: False
```
**Symbols:**

```
ffffffff8191ee90-ffffffff8191ef1c: devm_pci_remap_cfgspace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81966fd0)
Location: drivers/pci/pci.c:4435
Inline: False
```
**Symbols:**

```
ffffffff81966fd0-ffffffff8196705c: devm_pci_remap_cfgspace (STB_GLOBAL)
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
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e5a38)
Location: drivers/pci/pci.c:4027
Inline: False
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_platform_init
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_init
```
**Symbols:**

```
ffff8000106e5a38-ffff8000106e5b84: devm_pci_remap_cfgspace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087eb8c)
Location: drivers/pci/pci.c:4027
Inline: False
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
c087eb8c-c087ec10: devm_pci_remap_cfgspace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085c900)
Location: drivers/pci/pci.c:4027
Inline: False
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
```
**Symbols:**

```
c00000000085c900-c00000000085c9e8: devm_pci_remap_cfgspace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004ba64a)
Location: drivers/pci/pci.c:4027
Inline: False
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffe0004ba64a-ffffffe0004ba6ca: devm_pci_remap_cfgspace (STB_GLOBAL)
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
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815747f0)
Location: drivers/pci/pci.c:4027
Inline: False
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
```
**Symbols:**

```
ffffffff815747f0-ffffffff81574876: devm_pci_remap_cfgspace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81562f50)
Location: drivers/pci/pci.c:4027
Inline: False
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
```
**Symbols:**

```
ffffffff81562f50-ffffffff81562fd6: devm_pci_remap_cfgspace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81574020)
Location: drivers/pci/pci.c:4027
Inline: False
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
```
**Symbols:**

```
ffffffff81574020-ffffffff815740a6: devm_pci_remap_cfgspace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *devm_pci_remap_cfgspace(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158e500)
Location: drivers/pci/pci.c:4027
Inline: False
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
```
**Symbols:**

```
ffffffff8158e500-ffffffff8158e586: devm_pci_remap_cfgspace (STB_GLOBAL)
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
