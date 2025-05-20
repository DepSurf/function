# Function: <code>get_port_device_capability</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff81448a13)
Location: drivers/pci/pcie/portdrv_core.c:254
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff81494c29)
Location: drivers/pci/pcie/portdrv_core.c:255
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff814b65d9)
Location: drivers/pci/pcie/portdrv_core.c:255
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff814c0f39)
Location: drivers/pci/pcie/portdrv_core.c:230
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff81501369)
Location: drivers/pci/pcie/portdrv_core.c:210
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff815302f9)
Location: drivers/pci/pcie/portdrv_core.c:202
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff815477b9)
Location: drivers/pci/pcie/portdrv_core.c:202
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff81577899)
Location: drivers/pci/pcie/portdrv_core.c:206
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff81599019)
Location: drivers/pci/pcie/portdrv_core.c:206
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_port_device_capability(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff81638590)
Location: drivers/pci/pcie/portdrv_core.c:206
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
**Symbols:**

```
ffffffff81638590-ffffffff816386c9: get_port_device_capability (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_port_device_capability(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff8165f080)
Location: drivers/pci/pcie/portdrv_core.c:206
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
**Symbols:**

```
ffffffff8165f080-ffffffff8165f1d5: get_port_device_capability (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_port_device_capability(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff81641570)
Location: drivers/pci/pcie/portdrv_core.c:206
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
**Symbols:**

```
ffffffff81641570-ffffffff816416c4: get_port_device_capability (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int get_port_device_capability(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (0)
Location: drivers/pci/pcie/portdrv_core.c:206
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
**Symbols:**

```
ffffffff816b2540-ffffffff816b2708: get_port_device_capability (STB_LOCAL)
ffffffff81ce5be6-ffffffff81ce5c39: get_port_device_capability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int get_port_device_capability(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (0)
Location: drivers/pci/pcie/portdrv_core.c:206
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
**Symbols:**

```
ffffffff817d5c00-ffffffff817d5dde: get_port_device_capability (STB_LOCAL)
ffffffff81eac66b-ffffffff81eac6bf: get_port_device_capability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int get_port_device_capability(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/portdrv.c (0)
Location: drivers/pci/pcie/portdrv.c:217
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
**Symbols:**

```
ffffffff818f7470-ffffffff818f767c: get_port_device_capability (STB_LOCAL)
ffffffff8208f4be-ffffffff8208f512: get_port_device_capability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int get_port_device_capability(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/portdrv.c (0)
Location: drivers/pci/pcie/portdrv.c:217
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
**Symbols:**

```
ffffffff8193ab30-ffffffff8193ad47: get_port_device_capability (STB_LOCAL)
ffffffff8210f86a-ffffffff8210f8be: get_port_device_capability.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int get_port_device_capability(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/portdrv.c (0)
Location: drivers/pci/pcie/portdrv.c:218
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
**Symbols:**

```
ffffffff81983990-ffffffff81983ba7: get_port_device_capability (STB_LOCAL)
ffffffff821ed500-ffffffff821ed554: get_port_device_capability.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffff8000107006f4)
Location: drivers/pci/pcie/portdrv_core.c:206
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (c0898408)
Location: drivers/pci/pcie/portdrv_core.c:206
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffe0004cf666)
Location: drivers/pci/pcie/portdrv_core.c:206
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff8158cea9)
Location: drivers/pci/pcie/portdrv_core.c:206
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff8157b9e9)
Location: drivers/pci/pcie/portdrv_core.c:206
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff8158cd69)
Location: drivers/pci/pcie/portdrv_core.c:206
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/portdrv_core.c (ffffffff815a7219)
Location: drivers/pci/pcie/portdrv_core.c:206
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
```
</details>
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
