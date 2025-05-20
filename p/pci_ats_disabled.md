# Function: <code>pci_ats_disabled</code>

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
bool pci_ats_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151c200)
Location: drivers/pci/pci.c:118
Inline: False
Direct callers:
  - drivers/pci/ats.c:pci_ats_init
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff8151c200-ffffffff8151c212: pci_ats_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool pci_ats_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81531ad0)
Location: drivers/pci/pci.c:122
Inline: False
Direct callers:
  - drivers/pci/ats.c:pci_ats_init
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81531ad0-ffffffff81531ae2: pci_ats_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool pci_ats_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81561170)
Location: drivers/pci/pci.c:122
Inline: False
Direct callers:
  - drivers/pci/ats.c:pci_ats_init
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81561170-ffffffff81561182: pci_ats_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool pci_ats_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81582330)
Location: drivers/pci/pci.c:122
Inline: False
Direct callers:
  - drivers/pci/ats.c:pci_ats_init
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81582330-ffffffff81582342: pci_ats_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool pci_ats_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816242b0)
Location: drivers/pci/pci.c:130
Inline: False
Direct callers:
  - drivers/pci/ats.c:pci_ats_init
```
**Symbols:**

```
ffffffff816242b0-ffffffff816242c2: pci_ats_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool pci_ats_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81649e70)
Location: drivers/pci/pci.c:139
Inline: False
Direct callers:
  - drivers/pci/ats.c:pci_ats_init
```
**Symbols:**

```
ffffffff81649e70-ffffffff81649e82: pci_ats_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool pci_ats_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162ca20)
Location: drivers/pci/pci.c:139
Inline: False
Direct callers:
  - drivers/pci/ats.c:pci_ats_init
```
**Symbols:**

```
ffffffff8162ca20-ffffffff8162ca32: pci_ats_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_ats_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169fbdc)
Location: drivers/pci/pci.c:145
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/ats.c:pci_ats_init
```
**Symbols:**

```
ffffffff81ce4491-ffffffff81ce44b1: pci_ats_disabled.cold (STB_LOCAL)
ffffffff8169d900-ffffffff8169d918: pci_ats_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_ats_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c19d6)
Location: drivers/pci/pci.c:145
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/ats.c:pci_ats_init
```
**Symbols:**

```
ffffffff81eaaec4-ffffffff81eaaeee: pci_ats_disabled.cold (STB_LOCAL)
ffffffff817bff70-ffffffff817bff92: pci_ats_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_ats_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff818de3c6)
Location: drivers/pci/pci.c:149
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/ats.c:pci_ats_init
```
**Symbols:**

```
ffffffff8208ef9a-ffffffff8208efc4: pci_ats_disabled.cold (STB_LOCAL)
ffffffff818dc5a0-ffffffff818dc5c2: pci_ats_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_ats_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81921826)
Location: drivers/pci/pci.c:164
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/ats.c:pci_ats_init
```
**Symbols:**

```
ffffffff8210f2e2-ffffffff8210f30c: pci_ats_disabled.cold (STB_LOCAL)
ffffffff8191f8d0-ffffffff8191f8f2: pci_ats_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_ats_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81969786)
Location: drivers/pci/pci.c:164
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_acs
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/ats.c:pci_ats_init
```
**Symbols:**

```
ffffffff821ecf8a-ffffffff821ecfb4: pci_ats_disabled.cold (STB_LOCAL)
ffffffff81967a40-ffffffff81967a62: pci_ats_disabled (STB_GLOBAL)
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
bool pci_ats_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e5e40)
Location: drivers/pci/pci.c:122
Inline: False
Direct callers:
  - drivers/pci/ats.c:pci_ats_init
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_attach_dev
```
**Symbols:**

```
ffff8000106e5e40-ffff8000106e5e60: pci_ats_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool pci_ats_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0881168)
Location: drivers/pci/pci.c:122
Inline: False
Direct callers:
  - drivers/pci/ats.c:pci_ats_init
```
**Symbols:**

```
c0881168-c088118c: pci_ats_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool pci_ats_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085fea0)
Location: drivers/pci/pci.c:122
Inline: False
Direct callers:
  - drivers/pci/ats.c:pci_ats_init
```
**Symbols:**

```
c00000000085fea0-c00000000085febc: pci_ats_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool pci_ats_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bc9fa)
Location: drivers/pci/pci.c:122
Inline: False
Direct callers:
  - drivers/pci/ats.c:pci_ats_init
```
**Symbols:**

```
ffffffe0004bc9fa-ffffffe0004bca1c: pci_ats_disabled (STB_GLOBAL)
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
bool pci_ats_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81576850)
Location: drivers/pci/pci.c:122
Inline: False
Direct callers:
  - drivers/pci/ats.c:pci_ats_init
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81576850-ffffffff81576862: pci_ats_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool pci_ats_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81564fb0)
Location: drivers/pci/pci.c:122
Inline: False
Direct callers:
  - drivers/pci/ats.c:pci_ats_init
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81564fb0-ffffffff81564fc2: pci_ats_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool pci_ats_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81576080)
Location: drivers/pci/pci.c:122
Inline: False
Direct callers:
  - drivers/pci/ats.c:pci_ats_init
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81576080-ffffffff81576092: pci_ats_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool pci_ats_disabled();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81590560)
Location: drivers/pci/pci.c:122
Inline: False
Direct callers:
  - drivers/pci/ats.c:pci_ats_init
  - drivers/iommu/amd_iommu.c:amd_iommu_device_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81590560-ffffffff81590572: pci_ats_disabled (STB_GLOBAL)
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
