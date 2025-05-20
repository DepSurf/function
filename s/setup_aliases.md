# Function: <code>setup_aliases</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pci_dev *setup_aliases(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816df250)
Location: drivers/iommu/amd_iommu.c:260
Inline: False
```
**Symbols:**

```
ffffffff816df250-ffffffff816df2cb: setup_aliases (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pci_dev *setup_aliases(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81797b20)
Location: drivers/iommu/amd/iommu.c:240
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff81797b20-ffffffff81797bda: setup_aliases (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pci_dev *setup_aliases(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a6110)
Location: drivers/iommu/amd/iommu.c:249
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff817a6110-ffffffff817a61d0: setup_aliases (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pci_dev *setup_aliases(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81787d10)
Location: drivers/iommu/amd/iommu.c:205
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff81787d10-ffffffff81787dd0: setup_aliases (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pci_dev *setup_aliases(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8180e8d0)
Location: drivers/iommu/amd/iommu.c:205
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff8180e8d0-ffffffff8180e990: setup_aliases (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pci_dev *setup_aliases(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81950240)
Location: drivers/iommu/amd/iommu.c:206
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff81950240-ffffffff81950323: setup_aliases (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void setup_aliases(struct amd_iommu *iommu, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab3dc0)
Location: drivers/iommu/amd/iommu.c:260
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff81ab3dc0-ffffffff81ab3e6d: setup_aliases (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void setup_aliases(struct amd_iommu *iommu, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b008b0)
Location: drivers/iommu/amd/iommu.c:260
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff81b008b0-ffffffff81b0095d: setup_aliases (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void setup_aliases(struct amd_iommu *iommu, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b542e0)
Location: drivers/iommu/amd/iommu.c:263
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff81b542e0-ffffffff81b5438d: setup_aliases (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct pci_dev *setup_aliases(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a4ca0)
Location: drivers/iommu/amd_iommu.c:260
Inline: False
```
**Symbols:**

```
ffffffff816a4ca0-ffffffff816a4d1b: setup_aliases (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pci_dev *setup_aliases(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81682690)
Location: drivers/iommu/amd_iommu.c:260
Inline: False
```
**Symbols:**

```
ffffffff81682690-ffffffff8168270b: setup_aliases (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pci_dev *setup_aliases(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d2f10)
Location: drivers/iommu/amd_iommu.c:260
Inline: False
```
**Symbols:**

```
ffffffff816d2f10-ffffffff816d2f8b: setup_aliases (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pci_dev *setup_aliases(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ed5b0)
Location: drivers/iommu/amd_iommu.c:260
Inline: False
```
**Symbols:**

```
ffffffff816ed5b0-ffffffff816ed62b: setup_aliases (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct amd_iommu *iommu</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev</code> ➡️ <code>iommu, dev</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct pci_dev *</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
