# Function: <code>iosf_mbi_probe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int iosf_mbi_probe(struct pci_dev *pdev, const struct pci_device_id *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8107a4b0)
Location: arch/x86/platform/intel/iosf_mbi.c:276
Inline: False
```
**Symbols:**

```
ffffffff8107a4b0-ffffffff8107a502: iosf_mbi_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int iosf_mbi_probe(struct pci_dev *pdev, const struct pci_device_id *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8107bd70)
Location: arch/x86/platform/intel/iosf_mbi.c:276
Inline: False
```
**Symbols:**

```
ffffffff8107bd70-ffffffff8107bdc2: iosf_mbi_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iosf_mbi_probe(struct pci_dev *pdev, const struct pci_device_id *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81080310)
Location: arch/x86/platform/intel/iosf_mbi.c:276
Inline: False
```
**Symbols:**

```
ffffffff81080310-ffffffff81080362: iosf_mbi_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_probe(struct pci_dev *pdev, const struct pci_device_id *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8107e890)
Location: arch/x86/platform/intel/iosf_mbi.c:325
Inline: True
```
**Symbols:**

```
ffffffff8107e890-ffffffff8107e8e2: iosf_mbi_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int iosf_mbi_probe(struct pci_dev *pdev, const struct pci_device_id *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810850c0)
Location: arch/x86/platform/intel/iosf_mbi.c:325
Inline: True
```
**Symbols:**

```
ffffffff810850c0-ffffffff81085112: iosf_mbi_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iosf_mbi_probe(struct pci_dev *pdev, const struct pci_device_id *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810881b0)
Location: arch/x86/platform/intel/iosf_mbi.c:340
Inline: False
```
**Symbols:**

```
ffffffff810881b0-ffffffff81088202: iosf_mbi_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iosf_mbi_probe(struct pci_dev *pdev, const struct pci_device_id *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8108fa00)
Location: arch/x86/platform/intel/iosf_mbi.c:514
Inline: False
```
**Symbols:**

```
ffffffff8108fa00-ffffffff8108fa66: iosf_mbi_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int iosf_mbi_probe(struct pci_dev *pdev, const struct pci_device_id *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: arch/x86/platform/intel/iosf_mbi.c:490
Inline: False
```
**Symbols:**

```
ffffffff810936c0-ffffffff81093707: iosf_mbi_probe (STB_LOCAL)
ffffffff81093baa-ffffffff81093bc9: iosf_mbi_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int iosf_mbi_probe(struct pci_dev *pdev, const struct pci_device_id *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: arch/x86/platform/intel/iosf_mbi.c:514
Inline: False
```
**Symbols:**

```
ffffffff810944c0-ffffffff81094507: iosf_mbi_probe (STB_LOCAL)
ffffffff81094b61-ffffffff81094b80: iosf_mbi_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int iosf_mbi_probe(struct pci_dev *pdev, const struct pci_device_id *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: arch/x86/platform/intel/iosf_mbi.c:514
Inline: False
```
**Symbols:**

```
ffffffff81099800-ffffffff81099847: iosf_mbi_probe (STB_LOCAL)
ffffffff81099e85-ffffffff81099ea4: iosf_mbi_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int iosf_mbi_probe(struct pci_dev *pdev, const struct pci_device_id *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: arch/x86/platform/intel/iosf_mbi.c:514
Inline: False
```
**Symbols:**

```
ffffffff810988f0-ffffffff81098937: iosf_mbi_probe (STB_LOCAL)
ffffffff81bda3e8-ffffffff81bda407: iosf_mbi_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int iosf_mbi_probe(struct pci_dev *pdev, const struct pci_device_id *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: arch/x86/platform/intel/iosf_mbi.c:514
Inline: False
```
**Symbols:**

```
ffffffff81099130-ffffffff81099177: iosf_mbi_probe (STB_LOCAL)
ffffffff81bcc510-ffffffff81bcc52f: iosf_mbi_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int iosf_mbi_probe(struct pci_dev *pdev, const struct pci_device_id *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: arch/x86/platform/intel/iosf_mbi.c:514
Inline: False
```
**Symbols:**

```
ffffffff810a9280-ffffffff810a92c7: iosf_mbi_probe (STB_LOCAL)
ffffffff81ca27bc-ffffffff81ca27db: iosf_mbi_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int iosf_mbi_probe(struct pci_dev *pdev, const struct pci_device_id *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: arch/x86/platform/intel/iosf_mbi.c:514
Inline: False
```
**Symbols:**

```
ffffffff810bea90-ffffffff810beae0: iosf_mbi_probe (STB_LOCAL)
ffffffff81e52022-ffffffff81e52040: iosf_mbi_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iosf_mbi_probe(struct pci_dev *pdev, const struct pci_device_id *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810da630)
Location: arch/x86/platform/intel/iosf_mbi.c:514
Inline: False
```
**Symbols:**

```
ffffffff810da630-ffffffff810da6a6: iosf_mbi_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iosf_mbi_probe(struct pci_dev *pdev, const struct pci_device_id *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810e5bd0)
Location: arch/x86/platform/intel/iosf_mbi.c:514
Inline: False
```
**Symbols:**

```
ffffffff810e5bd0-ffffffff810e5c46: iosf_mbi_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iosf_mbi_probe(struct pci_dev *pdev, const struct pci_device_id *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810edfc0)
Location: arch/x86/platform/intel/iosf_mbi.c:514
Inline: False
```
**Symbols:**

```
ffffffff810edfc0-ffffffff810ee036: iosf_mbi_probe (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int iosf_mbi_probe(struct pci_dev *pdev, const struct pci_device_id *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: arch/x86/platform/intel/iosf_mbi.c:514
Inline: False
```
**Symbols:**

```
ffffffff81093480-ffffffff810934c7: iosf_mbi_probe (STB_LOCAL)
ffffffff81093b21-ffffffff81093b40: iosf_mbi_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int iosf_mbi_probe(struct pci_dev *pdev, const struct pci_device_id *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: arch/x86/platform/intel/iosf_mbi.c:514
Inline: False
```
**Symbols:**

```
ffffffff81081f10-ffffffff81081f57: iosf_mbi_probe (STB_LOCAL)
ffffffff810825b1-ffffffff810825d0: iosf_mbi_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int iosf_mbi_probe(struct pci_dev *pdev, const struct pci_device_id *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: arch/x86/platform/intel/iosf_mbi.c:514
Inline: False
```
**Symbols:**

```
ffffffff81093430-ffffffff81093477: iosf_mbi_probe (STB_LOCAL)
ffffffff81093ad1-ffffffff81093af0: iosf_mbi_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int iosf_mbi_probe(struct pci_dev *pdev, const struct pci_device_id *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: arch/x86/platform/intel/iosf_mbi.c:514
Inline: False
```
**Symbols:**

```
ffffffff81095980-ffffffff810959c7: iosf_mbi_probe (STB_LOCAL)
ffffffff8109601f-ffffffff8109603e: iosf_mbi_probe.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct pci_device_id *dev_id</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct pci_device_id *unused</code>
</li>
</ul>
</details>
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
