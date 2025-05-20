# Function: <code>get_pci_alias_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8152ae30)
Location: drivers/iommu/iommu.c:671
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:get_pci_function_alias_group
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff8152ae30-ffffffff8152af1b: get_pci_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8157e240)
Location: drivers/iommu/iommu.c:662
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_function_alias_group
```
**Symbols:**

```
ffffffff8157e240-ffffffff8157e323: get_pci_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815aa7e0)
Location: drivers/iommu/iommu.c:813
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_function_alias_group
```
**Symbols:**

```
ffffffff815aa7e0-ffffffff815aa8c3: get_pci_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815c03e0)
Location: drivers/iommu/iommu.c:857
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff815c03e0-ffffffff815c04a8: get_pci_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81626ab0)
Location: drivers/iommu/iommu.c:859
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff81626ab0-ffffffff81626b78: get_pci_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816617b0)
Location: drivers/iommu/iommu.c:860
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff816617b0-ffffffff81661874: get_pci_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167fe60)
Location: drivers/iommu/iommu.c:926
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff8167fe60-ffffffff8167ff32: get_pci_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b7280)
Location: drivers/iommu/iommu.c:1144
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff816b7280-ffffffff816b734c: get_pci_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d9e30)
Location: drivers/iommu/iommu.c:1200
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff816d9e30-ffffffff816d9efc: get_pci_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178dbc0)
Location: drivers/iommu/iommu.c:1303
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_group
```
**Symbols:**

```
ffffffff8178dbc0-ffffffff8178dc88: get_pci_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817b9930)
Location: drivers/iommu/iommu.c:1335
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_group
```
**Symbols:**

```
ffffffff817b9930-ffffffff817b99f8: get_pci_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179cae0)
Location: drivers/iommu/iommu.c:1364
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_group
```
**Symbols:**

```
ffffffff8179cae0-ffffffff8179cba5: get_pci_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff818257b0)
Location: drivers/iommu/iommu.c:1379
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_group
```
**Symbols:**

```
ffffffff818257b0-ffffffff81825875: get_pci_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81965380)
Location: drivers/iommu/iommu.c:1353
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:get_pci_function_alias_group
```
**Symbols:**

```
ffffffff81965380-ffffffff81965457: get_pci_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ace7b0)
Location: drivers/iommu/iommu.c:1474
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:get_pci_function_alias_group
```
**Symbols:**

```
ffffffff81ace7b0-ffffffff81ace887: get_pci_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1d150)
Location: drivers/iommu/iommu.c:1465
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:get_pci_function_alias_group
```
**Symbols:**

```
ffffffff81b1d150-ffffffff81b1d227: get_pci_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b736d0)
Location: drivers/iommu/iommu.c:1609
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
  - drivers/iommu/iommu.c:get_pci_alias_group
  - drivers/iommu/iommu.c:get_pci_function_alias_group
```
**Symbols:**

```
ffffffff81b736d0-ffffffff81b737a7: get_pci_alias_group (STB_LOCAL)
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
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c5058)
Location: drivers/iommu/iommu.c:1200
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffff8000108c5058-ffff8000108c5190: get_pci_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bd01c)
Location: drivers/iommu/iommu.c:1200
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
c09bd01c-c09bd0f4: get_pci_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096bcf0)
Location: drivers/iommu/iommu.c:1200
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
c00000000096bcf0-c00000000096beb4: get_pci_alias_group (STB_LOCAL)
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
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169f880)
Location: drivers/iommu/iommu.c:1200
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff8169f880-ffffffff8169f94c: get_pci_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167d270)
Location: drivers/iommu/iommu.c:1200
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff8167d270-ffffffff8167d33c: get_pci_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cdaf0)
Location: drivers/iommu/iommu.c:1200
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff816cdaf0-ffffffff816cdbbc: get_pci_alias_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *get_pci_alias_group(struct pci_dev *pdev, long unsigned int *devfns);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e8030)
Location: drivers/iommu/iommu.c:1200
Inline: True
Direct callers:
  - drivers/iommu/iommu.c:pci_device_group
```
**Symbols:**

```
ffffffff816e8030-ffffffff816e80fc: get_pci_alias_group (STB_LOCAL)
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
