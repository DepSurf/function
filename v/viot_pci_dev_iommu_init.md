# Function: <code>viot_pci_dev_iommu_init</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int viot_pci_dev_iommu_init(struct pci_dev *pdev, u16 dev_id, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/viot.c (ffffffff8176cd50)
Location: drivers/acpi/viot.c:308
Inline: False
```
**Symbols:**

```
ffffffff8176cd50-ffffffff8176ce2b: viot_pci_dev_iommu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int viot_pci_dev_iommu_init(struct pci_dev *pdev, u16 dev_id, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/viot.c (ffffffff818a1d80)
Location: drivers/acpi/viot.c:328
Inline: False
```
**Symbols:**

```
ffffffff818a1d80-ffffffff818a1e73: viot_pci_dev_iommu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int viot_pci_dev_iommu_init(struct pci_dev *pdev, u16 dev_id, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/viot.c (ffffffff819eb570)
Location: drivers/acpi/viot.c:327
Inline: False
```
**Symbols:**

```
ffffffff819eb570-ffffffff819eb61d: viot_pci_dev_iommu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int viot_pci_dev_iommu_init(struct pci_dev *pdev, u16 dev_id, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/viot.c (ffffffff81a33ca0)
Location: drivers/acpi/viot.c:327
Inline: False
```
**Symbols:**

```
ffffffff81a33ca0-ffffffff81a33d4a: viot_pci_dev_iommu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int viot_pci_dev_iommu_init(struct pci_dev *pdev, u16 dev_id, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/viot.c (ffffffff81a7f110)
Location: drivers/acpi/viot.c:327
Inline: False
```
**Symbols:**

```
ffffffff81a7f110-ffffffff81a7f1ba: viot_pci_dev_iommu_init (STB_LOCAL)
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
