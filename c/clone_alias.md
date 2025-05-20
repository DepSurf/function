# Function: <code>clone_alias</code>

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
int clone_alias(struct pci_dev *pdev, u16 alias, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816de640)
Location: drivers/iommu/amd_iommu.c:229
Inline: False
```
**Symbols:**

```
ffffffff816de640-ffffffff816de6ac: clone_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int clone_alias(struct pci_dev *pdev, u16 alias, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81794e30)
Location: drivers/iommu/amd/iommu.c:209
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:do_attach
  - drivers/iommu/amd/iommu.c:setup_aliases
```
**Symbols:**

```
ffffffff81794e30-ffffffff81794e9d: clone_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int clone_alias(struct pci_dev *pdev, u16 alias, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a32f0)
Location: drivers/iommu/amd/iommu.c:218
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:do_attach
  - drivers/iommu/amd/iommu.c:setup_aliases
```
**Symbols:**

```
ffffffff817a32f0-ffffffff817a335d: clone_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int clone_alias(struct pci_dev *pdev, u16 alias, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81786070)
Location: drivers/iommu/amd/iommu.c:174
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:setup_aliases
```
**Symbols:**

```
ffffffff81786070-ffffffff817860dd: clone_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int clone_alias(struct pci_dev *pdev, u16 alias, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8180cee0)
Location: drivers/iommu/amd/iommu.c:174
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:setup_aliases
```
**Symbols:**

```
ffffffff8180cee0-ffffffff8180cf4d: clone_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int clone_alias(struct pci_dev *pdev, u16 alias, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8194d5c0)
Location: drivers/iommu/amd/iommu.c:175
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:update_device_table
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:setup_aliases
```
**Symbols:**

```
ffffffff8194d5c0-ffffffff8194d638: clone_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int clone_alias(struct pci_dev *pdev, u16 alias, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab3c90)
Location: drivers/iommu/amd/iommu.c:220
Inline: False
```
**Symbols:**

```
ffffffff81ab3c90-ffffffff81ab3d30: clone_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int clone_alias(struct pci_dev *pdev, u16 alias, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b00780)
Location: drivers/iommu/amd/iommu.c:220
Inline: False
```
**Symbols:**

```
ffffffff81b00780-ffffffff81b00820: clone_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int clone_alias(struct pci_dev *pdev, u16 alias, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b541b0)
Location: drivers/iommu/amd/iommu.c:223
Inline: False
```
**Symbols:**

```
ffffffff81b541b0-ffffffff81b54250: clone_alias (STB_LOCAL)
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
int clone_alias(struct pci_dev *pdev, u16 alias, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a4090)
Location: drivers/iommu/amd_iommu.c:229
Inline: False
```
**Symbols:**

```
ffffffff816a4090-ffffffff816a40fc: clone_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int clone_alias(struct pci_dev *pdev, u16 alias, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81681a80)
Location: drivers/iommu/amd_iommu.c:229
Inline: False
```
**Symbols:**

```
ffffffff81681a80-ffffffff81681aec: clone_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int clone_alias(struct pci_dev *pdev, u16 alias, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d2300)
Location: drivers/iommu/amd_iommu.c:229
Inline: False
```
**Symbols:**

```
ffffffff816d2300-ffffffff816d236c: clone_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int clone_alias(struct pci_dev *pdev, u16 alias, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ec940)
Location: drivers/iommu/amd_iommu.c:229
Inline: False
```
**Symbols:**

```
ffffffff816ec940-ffffffff816ec9ac: clone_alias (STB_LOCAL)
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
