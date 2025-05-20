# Function: <code>vfio_pci_walk_wrapper</code>

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
int vfio_pci_walk_wrapper(struct pci_dev *pdev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d5e60)
Location: drivers/vfio/pci/vfio_pci.c:630
Inline: False
```
**Symbols:**

```
ffffffff817d5e60-ffffffff817d5eb8: vfio_pci_walk_wrapper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_pci_walk_wrapper(struct pci_dev *pdev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a26b0)
Location: drivers/vfio/pci/vfio_pci.c:693
Inline: False
```
**Symbols:**

```
ffffffff818a26b0-ffffffff818a270e: vfio_pci_walk_wrapper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_pci_walk_wrapper(struct pci_dev *pdev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b1650)
Location: drivers/vfio/pci/vfio_pci.c:733
Inline: False
```
**Symbols:**

```
ffffffff818b1650-ffffffff818b16ae: vfio_pci_walk_wrapper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_pci_walk_wrapper(struct pci_dev *pdev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff81894af0)
Location: drivers/vfio/pci/vfio_pci.c:715
Inline: False
```
**Symbols:**

```
ffffffff81894af0-ffffffff81894b4e: vfio_pci_walk_wrapper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_pci_walk_wrapper(struct pci_dev *pdev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (0)
Location: drivers/vfio/pci/vfio_pci_core.c:575
Inline: False
```
**Symbols:**

```
ffffffff81928f60-ffffffff81928fd9: vfio_pci_walk_wrapper (STB_LOCAL)
ffffffff81d11f5f-ffffffff81d11f74: vfio_pci_walk_wrapper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_pci_walk_wrapper(struct pci_dev *pdev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (0)
Location: drivers/vfio/pci/vfio_pci_core.c:612
Inline: False
```
**Symbols:**

```
ffffffff81a7eed0-ffffffff81a7ef61: vfio_pci_walk_wrapper (STB_LOCAL)
ffffffff81edcc62-ffffffff81edcc77: vfio_pci_walk_wrapper.cold (STB_LOCAL)
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
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfio_pci_walk_wrapper(struct pci_dev *pdev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (c000000000ab48e0)
Location: drivers/vfio/pci/vfio_pci.c:630
Inline: False
```
**Symbols:**

```
c000000000ab48e0-c000000000ab49a0: vfio_pci_walk_wrapper (STB_LOCAL)
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
<summary>In <code>azure</code>: ✅</summary>

```c
int vfio_pci_walk_wrapper(struct pci_dev *pdev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff8177ff10)
Location: drivers/vfio/pci/vfio_pci.c:630
Inline: False
```
**Symbols:**

```
ffffffff8177ff10-ffffffff8177ff68: vfio_pci_walk_wrapper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_pci_walk_wrapper(struct pci_dev *pdev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817cace0)
Location: drivers/vfio/pci/vfio_pci.c:630
Inline: False
```
**Symbols:**

```
ffffffff817cace0-ffffffff817cad38: vfio_pci_walk_wrapper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_pci_walk_wrapper(struct pci_dev *pdev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e4f80)
Location: drivers/vfio/pci/vfio_pci.c:630
Inline: False
```
**Symbols:**

```
ffffffff817e4f80-ffffffff817e4fd8: vfio_pci_walk_wrapper (STB_LOCAL)
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
