# Function: <code>risky_device</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool risky_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a17e0)
Location: drivers/iommu/intel/iommu.c:6042
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
Direct callers:
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
```
**Symbols:**

```
ffffffff817a6b8e-ffffffff817a6bcc: risky_device.part.0 (STB_LOCAL)
ffffffff817a0b30-ffffffff817a0b4a: risky_device (STB_LOCAL)
ffffffff817a6bcc-ffffffff817a6bd6: risky_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool risky_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817aefa0)
Location: drivers/iommu/intel/iommu.c:5499
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
Direct callers:
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
```
**Symbols:**

```
ffffffff81c0c398-ffffffff81c0c3d6: risky_device.part.0 (STB_LOCAL)
ffffffff817adff0-ffffffff817ae00a: risky_device (STB_LOCAL)
ffffffff81c0c3d6-ffffffff81c0c3e0: risky_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool risky_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81791850)
Location: drivers/iommu/intel/iommu.c:5487
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
Direct callers:
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
```
**Symbols:**

```
ffffffff81bfdbea-ffffffff81bfdc28: risky_device.part.0 (STB_LOCAL)
ffffffff81790a50-ffffffff81790a65: risky_device (STB_LOCAL)
ffffffff81bfdc28-ffffffff81bfdc33: risky_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool risky_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff818192b0)
Location: drivers/iommu/intel/iommu.c:5548
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
Direct callers:
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
```
**Symbols:**

```
ffffffff81cff2cd-ffffffff81cff30b: risky_device.part.0 (STB_LOCAL)
ffffffff81818400-ffffffff81818415: risky_device (STB_LOCAL)
ffffffff81cff30b-ffffffff81cff316: risky_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool risky_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8195a346)
Location: drivers/iommu/intel/iommu.c:4870
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
Direct callers:
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
```
**Symbols:**

```
ffffffff81ec7a8e-ffffffff81ec7ad6: risky_device.part.0 (STB_LOCAL)
ffffffff819593a0-ffffffff819593bb: risky_device (STB_LOCAL)
ffffffff81ec7ad6-ffffffff81ec7ae7: risky_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac18b8)
Location: drivers/iommu/intel/iommu.c:4745
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b0e548)
Location: drivers/iommu/intel/iommu.c:4703
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b62df8)
Location: drivers/iommu/intel/iommu.c:4602
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/iommu/intel/iommu.c:quirk_calpella_no_shadow_gtt
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
  - drivers/iommu/intel/iommu.c:check_tylersburg_isoch
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
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
</ul>
