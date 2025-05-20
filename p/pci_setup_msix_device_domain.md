# Function: <code>pci_setup_msix_device_domain</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool pci_setup_msix_device_domain(struct pci_dev *pdev, unsigned int hwsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/irqdomain.c (ffffffff818f6b60)
Location: drivers/pci/msi/irqdomain.c:303
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
```
**Symbols:**

```
ffffffff818f6b60-ffffffff818f6c34: pci_setup_msix_device_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool pci_setup_msix_device_domain(struct pci_dev *pdev, unsigned int hwsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/irqdomain.c (ffffffff81939fc0)
Location: drivers/pci/msi/irqdomain.c:303
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
```
**Symbols:**

```
ffffffff81939fc0-ffffffff8193a094: pci_setup_msix_device_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool pci_setup_msix_device_domain(struct pci_dev *pdev, unsigned int hwsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/irqdomain.c (ffffffff81982e20)
Location: drivers/pci/msi/irqdomain.c:303
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
```
**Symbols:**

```
ffffffff81982e20-ffffffff81982ef4: pci_setup_msix_device_domain (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
