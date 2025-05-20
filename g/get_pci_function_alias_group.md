# Function: <code>get_pci_function_alias_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8152af20)
Location: drivers/iommu/iommu.c:637
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff8152af20-ffffffff8152afcd: get_pci_function_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8157e330)
Location: drivers/iommu/iommu.c:628
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff8157e330-ffffffff8157e3e6: get_pci_function_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815aa8d0)
Location: drivers/iommu/iommu.c:779
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff815aa8d0-ffffffff815aa986: get_pci_function_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815c04b0)
Location: drivers/iommu/iommu.c:823
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff815c04b0-ffffffff815c0564: get_pci_function_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81626b80)
Location: drivers/iommu/iommu.c:825
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff81626b80-ffffffff81626c34: get_pci_function_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81661880)
Location: drivers/iommu/iommu.c:826
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff81661880-ffffffff81661934: get_pci_function_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167ff40)
Location: drivers/iommu/iommu.c:892
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff8167ff40-ffffffff8167fff4: get_pci_function_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b7350)
Location: drivers/iommu/iommu.c:1110
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff816b7350-ffffffff816b73ff: get_pci_function_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d9f00)
Location: drivers/iommu/iommu.c:1166
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff816d9f00-ffffffff816d9faf: get_pci_function_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178db10)
Location: drivers/iommu/iommu.c:1269
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_group
```
**Symbols:**

```
ffffffff8178db10-ffffffff8178dbbf: get_pci_function_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817b9880)
Location: drivers/iommu/iommu.c:1301
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_group
```
**Symbols:**

```
ffffffff817b9880-ffffffff817b992f: get_pci_function_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179ca30)
Location: drivers/iommu/iommu.c:1330
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_group
```
**Symbols:**

```
ffffffff8179ca30-ffffffff8179cadf: get_pci_function_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81825700)
Location: drivers/iommu/iommu.c:1345
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_group
```
**Symbols:**

```
ffffffff81825700-ffffffff818257af: get_pci_function_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff819652b0)
Location: drivers/iommu/iommu.c:1319
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_group
```
**Symbols:**

```
ffffffff819652b0-ffffffff81965372: get_pci_function_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ace6d0)
Location: drivers/iommu/iommu.c:1440
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_group
```
**Symbols:**

```
ffffffff81ace6d0-ffffffff81ace792: get_pci_function_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1d070)
Location: drivers/iommu/iommu.c:1431
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_group
```
**Symbols:**

```
ffffffff81b1d070-ffffffff81b1d132: get_pci_function_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b735f0)
Location: drivers/iommu/iommu.c:1575
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_group
```
**Symbols:**

```
ffffffff81b735f0-ffffffff81b736b2: get_pci_function_alias_group (STB_LOCAL)
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
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c5190)
Location: drivers/iommu/iommu.c:1166
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffff8000108c5190-ffff8000108c5260: get_pci_function_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bd0f4)
Location: drivers/iommu/iommu.c:1166
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
c09bd0f4-c09bd1b0: get_pci_function_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096bec0)
Location: drivers/iommu/iommu.c:1166
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
c00000000096bec0-c00000000096c024: get_pci_function_alias_group (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169f950)
Location: drivers/iommu/iommu.c:1166
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff8169f950-ffffffff8169f9ff: get_pci_function_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167d340)
Location: drivers/iommu/iommu.c:1166
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff8167d340-ffffffff8167d3ef: get_pci_function_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cdbc0)
Location: drivers/iommu/iommu.c:1166
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff816cdbc0-ffffffff816cdc6f: get_pci_function_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_function_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e8100)
Location: drivers/iommu/iommu.c:1166
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff816e8100-ffffffff816e81af: get_pci_function_alias_group (STB_LOCAL)
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
