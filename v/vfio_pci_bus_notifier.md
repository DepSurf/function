# Function: <code>vfio_pci_bus_notifier</code>

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
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vfio_pci_bus_notifier(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:1825
Inline: False
```
**Symbols:**

```
ffffffff818a2b50-ffffffff818a2bc6: vfio_pci_bus_notifier (STB_LOCAL)
ffffffff818a5c6f-ffffffff818a5ce9: vfio_pci_bus_notifier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vfio_pci_bus_notifier(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:1899
Inline: False
```
**Symbols:**

```
ffffffff818b18a0-ffffffff818b1916: vfio_pci_bus_notifier (STB_LOCAL)
ffffffff81c1a01d-ffffffff81c1a097: vfio_pci_bus_notifier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vfio_pci_bus_notifier(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci.c (0)
Location: drivers/vfio/pci/vfio_pci.c:1896
Inline: False
```
**Symbols:**

```
ffffffff81895400-ffffffff81895476: vfio_pci_bus_notifier (STB_LOCAL)
ffffffff81c0bee5-ffffffff81c0bf5f: vfio_pci_bus_notifier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_pci_bus_notifier(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (0)
Location: drivers/vfio/pci/vfio_pci_core.c:1686
Inline: False
```
**Symbols:**

```
ffffffff81928e20-ffffffff81928ec3: vfio_pci_bus_notifier (STB_LOCAL)
ffffffff81d11ee8-ffffffff81d11f5f: vfio_pci_bus_notifier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_pci_bus_notifier(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_core.c (0)
Location: drivers/vfio/pci/vfio_pci_core.c:1710
Inline: False
```
**Symbols:**

```
ffffffff81a7ede0-ffffffff81a7eeb0: vfio_pci_bus_notifier (STB_LOCAL)
ffffffff81edcbeb-ffffffff81edcc62: vfio_pci_bus_notifier.cold (STB_LOCAL)
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
