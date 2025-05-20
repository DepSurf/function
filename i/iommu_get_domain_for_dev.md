# Function: <code>iommu_get_domain_for_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8152a1f0)
Location: drivers/iommu/iommu.c:1166
Inline: False
```
**Symbols:**

```
ffffffff8152a1f0-ffffffff8152a22e: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8157d5b0)
Location: drivers/iommu/iommu.c:1156
Inline: False
```
**Symbols:**

```
ffffffff8157d5b0-ffffffff8157d5ec: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815a9b20)
Location: drivers/iommu/iommu.c:1307
Inline: False
```
**Symbols:**

```
ffffffff815a9b20-ffffffff815a9b5c: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815bf860)
Location: drivers/iommu/iommu.c:1357
Inline: False
```
**Symbols:**

```
ffffffff815bf860-ffffffff815bf89c: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81625cc0)
Location: drivers/iommu/iommu.c:1359
Inline: False
```
**Symbols:**

```
ffffffff81625cc0-ffffffff81625cfc: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81660be0)
Location: drivers/iommu/iommu.c:1365
Inline: False
```
**Symbols:**

```
ffffffff81660be0-ffffffff81660c1c: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167f290)
Location: drivers/iommu/iommu.c:1432
Inline: False
```
**Symbols:**

```
ffffffff8167f290-ffffffff8167f2cc: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b6120)
Location: drivers/iommu/iommu.c:1649
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:find_domain
```
**Symbols:**

```
ffffffff816b6120-ffffffff816b615f: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d8e20)
Location: drivers/iommu/iommu.c:1705
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:find_domain
```
**Symbols:**

```
ffffffff816d8e20-ffffffff816d8e5f: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178e2a0)
Location: drivers/iommu/iommu.c:2018
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_page_response
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_compose_msi_msg
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
  - drivers/iommu/amd/iommu.c:amd_iommu_get_v2_domain
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize
  - drivers/iommu/intel/iommu.c:bounce_map_single
  - drivers/iommu/intel/iommu.c:intel_map_sg
  - drivers/iommu/intel/iommu.c:intel_alloc_coherent
  - drivers/iommu/intel/iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff8178d410-ffffffff8178d44f: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817ba460)
Location: drivers/iommu/iommu.c:2228
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_page_response
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_get_v2_domain
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize
  - drivers/iommu/dma-iommu.c:iommu_dma_compose_msi_msg
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
```
**Symbols:**

```
ffffffff817b8f20-ffffffff817b8f5f: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179e160)
Location: drivers/iommu/iommu.c:2259
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_page_response
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize
  - drivers/iommu/dma-iommu.c:iommu_dma_compose_msi_msg
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
```
**Symbols:**

```
ffffffff8179c130-ffffffff8179c16f: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff818271b0)
Location: drivers/iommu/iommu.c:2280
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_page_response
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_compose_msi_msg
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
```
**Symbols:**

```
ffffffff81824e20-ffffffff81824e5f: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81965ab0)
Location: drivers/iommu/iommu.c:2041
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_compose_msi_msg
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
```
**Symbols:**

```
ffffffff81965ab0-ffffffff81965af2: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81acefd0)
Location: drivers/iommu/iommu.c:2079
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_compose_msi_msg
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
```
**Symbols:**

```
ffffffff81acefd0-ffffffff81acf012: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1db40)
Location: drivers/iommu/iommu.c:2057
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_compose_msi_msg
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff81b1db40-ffffffff81b1db82: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b72420)
Location: drivers/iommu/iommu.c:2321
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_compose_msi_msg
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
```
**Symbols:**

```
ffffffff81b72420-ffffffff81b72444: iommu_get_domain_for_dev (STB_GLOBAL)
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
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c45c8)
Location: drivers/iommu/iommu.c:1705
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/dma-iommu.c:iommu_dma_compose_msi_msg
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
```
**Symbols:**

```
ffff8000108c45c8-ffff8000108c4610: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bba98)
Location: drivers/iommu/iommu.c:1705
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_page_response
```
**Symbols:**

```
c09bba98-c09bbad4: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096a340)
Location: drivers/iommu/iommu.c:1705
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_page_response
```
**Symbols:**

```
c00000000096a340-c00000000096a3a4: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169e870)
Location: drivers/iommu/iommu.c:1705
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:find_domain
```
**Symbols:**

```
ffffffff8169e870-ffffffff8169e8af: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167c260)
Location: drivers/iommu/iommu.c:1705
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:find_domain
```
**Symbols:**

```
ffffffff8167c260-ffffffff8167c29f: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816ccae0)
Location: drivers/iommu/iommu.c:1705
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:find_domain
```
**Symbols:**

```
ffffffff816ccae0-ffffffff816ccb1f: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct iommu_domain *iommu_get_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e6fc0)
Location: drivers/iommu/iommu.c:1705
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_page_response
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
  - drivers/iommu/intel-iommu.c:find_domain
```
**Symbols:**

```
ffffffff816e6fc0-ffffffff816e6fff: iommu_get_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
