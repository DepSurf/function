# Function: <code>vfio_pci_aer_err_detected</code>

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
pci_ers_result_t vfio_pci_aer_err_detected(struct pci_dev *pdev, pci_channel_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d5ec0)
Location: drivers/vfio/pci/vfio_pci.c:1399
Inline: False
```
**Symbols:**

```
ffffffff817d5ec0-ffffffff817d5f4c: vfio_pci_aer_err_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pci_ers_result_t vfio_pci_aer_err_detected(struct pci_dev *pdev, pci_channel_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a2a10)
Location: drivers/vfio/pci/vfio_pci.c:1995
Inline: False
```
**Symbols:**

```
ffffffff818a2a10-ffffffff818a2a9c: vfio_pci_aer_err_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pci_ers_result_t vfio_pci_aer_err_detected(struct pci_dev *pdev, pci_channel_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b1760)
Location: drivers/vfio/pci/vfio_pci.c:2073
Inline: False
```
**Symbols:**

```
ffffffff818b1760-ffffffff818b17ec: vfio_pci_aer_err_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pci_ers_result_t vfio_pci_aer_err_detected(struct pci_dev *pdev, pci_channel_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff81894c00)
Location: drivers/vfio/pci/vfio_pci.c:2103
Inline: False
```
**Symbols:**

```
ffffffff81894c00-ffffffff81894c68: vfio_pci_aer_err_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pci_ers_result_t vfio_pci_aer_err_detected(struct pci_dev *pdev, pci_channel_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81928c90)
Location: drivers/vfio/pci/vfio_pci_core.c:1903
Inline: False
```
**Symbols:**

```
ffffffff81928c90-ffffffff81928cf8: vfio_pci_aer_err_detected (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
pci_ers_result_t vfio_pci_aer_err_detected(struct pci_dev *pdev, pci_channel_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (c000000000ab49a0)
Location: drivers/vfio/pci/vfio_pci.c:1399
Inline: False
```
**Symbols:**

```
c000000000ab49a0-c000000000ab4a98: vfio_pci_aer_err_detected (STB_LOCAL)
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
pci_ers_result_t vfio_pci_aer_err_detected(struct pci_dev *pdev, pci_channel_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff8177ff70)
Location: drivers/vfio/pci/vfio_pci.c:1399
Inline: False
```
**Symbols:**

```
ffffffff8177ff70-ffffffff8177fffc: vfio_pci_aer_err_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pci_ers_result_t vfio_pci_aer_err_detected(struct pci_dev *pdev, pci_channel_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817cad40)
Location: drivers/vfio/pci/vfio_pci.c:1399
Inline: False
```
**Symbols:**

```
ffffffff817cad40-ffffffff817cadcc: vfio_pci_aer_err_detected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pci_ers_result_t vfio_pci_aer_err_detected(struct pci_dev *pdev, pci_channel_state_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e4fe0)
Location: drivers/vfio/pci/vfio_pci.c:1399
Inline: False
```
**Symbols:**

```
ffffffff817e4fe0-ffffffff817e506c: vfio_pci_aer_err_detected (STB_LOCAL)
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
