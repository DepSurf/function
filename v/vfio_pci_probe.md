# Function: <code>vfio_pci_probe</code>

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
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int vfio_pci_probe(struct pci_dev *pdev, const struct pci_device_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:1292
Inline: False
```
**Symbols:**

```
ffffffff817d7540-ffffffff817d7846: vfio_pci_probe (STB_LOCAL)
ffffffff817d82bd-ffffffff817d82d7: vfio_pci_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vfio_pci_probe(struct pci_dev *pdev, const struct pci_device_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:1853
Inline: False
```
**Symbols:**

```
ffffffff818a4e80-ffffffff818a519d: vfio_pci_probe (STB_LOCAL)
ffffffff818a5de3-ffffffff818a5dfd: vfio_pci_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vfio_pci_probe(struct pci_dev *pdev, const struct pci_device_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:1927
Inline: False
```
**Symbols:**

```
ffffffff818b3f50-ffffffff818b42db: vfio_pci_probe (STB_LOCAL)
ffffffff81c1a191-ffffffff81c1a1eb: vfio_pci_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vfio_pci_probe(struct pci_dev *pdev, const struct pci_device_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:1986
Inline: False
```
**Symbols:**

```
ffffffff818970f0-ffffffff81897614: vfio_pci_probe (STB_LOCAL)
ffffffff81c0c025-ffffffff81c0c07f: vfio_pci_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_pci_probe(struct pci_dev *pdev, const struct pci_device_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:140
Inline: False
```
**Symbols:**

```
ffffffff819309b0-ffffffff81930a7e: vfio_pci_probe (STB_LOCAL)
ffffffff81d1289f-ffffffff81d128fb: vfio_pci_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_pci_probe(struct pci_dev *pdev, const struct pci_device_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:141
Inline: False
```
**Symbols:**

```
ffffffff81a87500-ffffffff81a875ed: vfio_pci_probe (STB_LOCAL)
ffffffff81edd5e1-ffffffff81edd63e: vfio_pci_probe.cold (STB_LOCAL)
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
int vfio_pci_probe(struct pci_dev *pdev, const struct pci_device_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (c000000000ab6a10)
Location: drivers/vfio/pci/vfio_pci.c:1292
Inline: False
```
**Symbols:**

```
c000000000ab6a10-c000000000ab6e28: vfio_pci_probe (STB_LOCAL)
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
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int vfio_pci_probe(struct pci_dev *pdev, const struct pci_device_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:1292
Inline: False
```
**Symbols:**

```
ffffffff817815f0-ffffffff817818f6: vfio_pci_probe (STB_LOCAL)
ffffffff8178236d-ffffffff81782387: vfio_pci_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int vfio_pci_probe(struct pci_dev *pdev, const struct pci_device_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:1292
Inline: False
```
**Symbols:**

```
ffffffff817cc3c0-ffffffff817cc6c6: vfio_pci_probe (STB_LOCAL)
ffffffff817cd13d-ffffffff817cd157: vfio_pci_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vfio_pci_probe(struct pci_dev *pdev, const struct pci_device_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:1292
Inline: False
```
**Symbols:**

```
ffffffff817e6660-ffffffff817e6966: vfio_pci_probe (STB_LOCAL)
ffffffff817e73dd-ffffffff817e73f7: vfio_pci_probe.cold (STB_LOCAL)
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
