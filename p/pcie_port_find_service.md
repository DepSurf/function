# Function: <code>pcie_port_find_service</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pcie_port_service_driver *pcie_port_find_service(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff81530860)
Location: drivers/pci/pcie/portdrv_core.c:435
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_fatal_recovery
```
**Symbols:**

```
ffffffff81530860-ffffffff815308b8: pcie_port_find_service (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pcie_port_service_driver *pcie_port_find_service(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff81547e70)
Location: drivers/pci/pcie/portdrv_core.c:455
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff81547e70-ffffffff81547ec8: pcie_port_find_service (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pcie_port_service_driver *pcie_port_find_service(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff81577f00)
Location: drivers/pci/pcie/portdrv_core.c:463
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff81577f00-ffffffff81577f58: pcie_port_find_service (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pcie_port_service_driver *pcie_port_find_service(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff81599690)
Location: drivers/pci/pcie/portdrv_core.c:468
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff81599690-ffffffff815996e8: pcie_port_find_service (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct pcie_port_service_driver *pcie_port_find_service(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffff800010700d70)
Location: drivers/pci/pcie/portdrv_core.c:468
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffff800010700d70-ffff800010700de4: pcie_port_find_service (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pcie_port_service_driver *pcie_port_find_service(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (c0898b08)
Location: drivers/pci/pcie/portdrv_core.c:468
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
c0898b08-c0898b80: pcie_port_find_service (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pcie_port_service_driver *pcie_port_find_service(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffe0004cfb88)
Location: drivers/pci/pcie/portdrv_core.c:468
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffe0004cfb88-ffffffe0004cfbd2: pcie_port_find_service (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct pcie_port_service_driver *pcie_port_find_service(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff8158d520)
Location: drivers/pci/pcie/portdrv_core.c:468
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff8158d520-ffffffff8158d578: pcie_port_find_service (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pcie_port_service_driver *pcie_port_find_service(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff8157c060)
Location: drivers/pci/pcie/portdrv_core.c:468
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff8157c060-ffffffff8157c0b8: pcie_port_find_service (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pcie_port_service_driver *pcie_port_find_service(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff8158d3e0)
Location: drivers/pci/pcie/portdrv_core.c:468
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff8158d3e0-ffffffff8158d438: pcie_port_find_service (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pcie_port_service_driver *pcie_port_find_service(struct pci_dev *dev, u32 service);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff815a7890)
Location: drivers/pci/pcie/portdrv_core.c:468
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
```
**Symbols:**

```
ffffffff815a7890-ffffffff815a78e8: pcie_port_find_service (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
