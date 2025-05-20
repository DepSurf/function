# Function: <code>vfio_pci_remove</code>

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
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void vfio_pci_remove(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d7460)
Location: drivers/vfio/pci/vfio_pci.c:1371
Inline: True
```
**Symbols:**

```
ffffffff817d7460-ffffffff817d753e: vfio_pci_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vfio_pci_remove(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a4d50)
Location: drivers/vfio/pci/vfio_pci.c:1956
Inline: False
```
**Symbols:**

```
ffffffff818a4d50-ffffffff818a4e78: vfio_pci_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vfio_pci_remove(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b3e20)
Location: drivers/vfio/pci/vfio_pci.c:2034
Inline: False
```
**Symbols:**

```
ffffffff818b3e20-ffffffff818b3f48: vfio_pci_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vfio_pci_remove(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff81896fd0)
Location: drivers/vfio/pci/vfio_pci.c:2080
Inline: False
```
**Symbols:**

```
ffffffff81896fd0-ffffffff818970e3: vfio_pci_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vfio_pci_remove(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff819308c0)
Location: drivers/vfio/pci/vfio_pci.c:165
Inline: False
```
**Symbols:**

```
ffffffff819308c0-ffffffff819308f0: vfio_pci_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vfio_pci_remove(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff81a873f0)
Location: drivers/vfio/pci/vfio_pci.c:166
Inline: False
```
**Symbols:**

```
ffffffff81a873f0-ffffffff81a87425: vfio_pci_remove (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void vfio_pci_remove(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (c000000000ab6850)
Location: drivers/vfio/pci/vfio_pci.c:1371
Inline: True
```
**Symbols:**

```
c000000000ab6850-c000000000ab6a04: vfio_pci_remove (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void vfio_pci_remove(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff81781510)
Location: drivers/vfio/pci/vfio_pci.c:1371
Inline: True
```
**Symbols:**

```
ffffffff81781510-ffffffff817815ee: vfio_pci_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void vfio_pci_remove(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817cc2e0)
Location: drivers/vfio/pci/vfio_pci.c:1371
Inline: True
```
**Symbols:**

```
ffffffff817cc2e0-ffffffff817cc3be: vfio_pci_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void vfio_pci_remove(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e6580)
Location: drivers/vfio/pci/vfio_pci.c:1371
Inline: True
```
**Symbols:**

```
ffffffff817e6580-ffffffff817e665e: vfio_pci_remove (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
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
