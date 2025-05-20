# Function: <code>xen_pv_teardown_msi_irqs</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_pv_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff81bcb9c0)
Location: arch/x86/pci/xen.c:396
Inline: False
```
**Symbols:**

```
ffffffff81bcb9c0-ffffffff81bcba67: xen_pv_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_pv_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff81bbf030)
Location: arch/x86/pci/xen.c:396
Inline: False
```
**Symbols:**

```
ffffffff81bbf030-ffffffff81bbf0d7: xen_pv_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_pv_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff81c8efa0)
Location: arch/x86/pci/xen.c:396
Inline: False
```
**Symbols:**

```
ffffffff81c8efa0-ffffffff81c8f047: xen_pv_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_pv_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff81e3dab0)
Location: arch/x86/pci/xen.c:398
Inline: False
```
**Symbols:**

```
ffffffff81e3dab0-ffffffff81e3db1d: xen_pv_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_pv_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff82017080)
Location: arch/x86/pci/xen.c:399
Inline: False
```
**Symbols:**

```
ffffffff82017080-ffffffff820170ed: xen_pv_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_pv_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff82097440)
Location: arch/x86/pci/xen.c:401
Inline: False
```
**Symbols:**

```
ffffffff82097440-ffffffff820974ad: xen_pv_teardown_msi_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_pv_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff8216e920)
Location: arch/x86/pci/xen.c:401
Inline: False
```
**Symbols:**

```
ffffffff8216e920-ffffffff8216e98d: xen_pv_teardown_msi_irqs (STB_LOCAL)
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
