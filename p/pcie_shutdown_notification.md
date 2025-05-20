# Function: <code>pcie_shutdown_notification</code>

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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8145181c)
Location: drivers/pci/hotplug/pciehp_hpc.c:733
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8149e02c)
Location: drivers/pci/hotplug/pciehp_hpc.c:737
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814bfc5c)
Location: drivers/pci/hotplug/pciehp_hpc.c:773
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814ca3cc)
Location: drivers/pci/hotplug/pciehp_hpc.c:781
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8150a97c)
Location: drivers/pci/hotplug/pciehp_hpc.c:777
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pcie_shutdown_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8153b4e0)
Location: drivers/pci/hotplug/pciehp_hpc.c:761
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
```
**Symbols:**

```
ffffffff8153b4e0-ffffffff8153b578: pcie_shutdown_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pcie_shutdown_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81552a60)
Location: drivers/pci/hotplug/pciehp_hpc.c:811
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff81552a60-ffffffff81552aa6: pcie_shutdown_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pcie_shutdown_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81582910)
Location: drivers/pci/hotplug/pciehp_hpc.c:813
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff81582910-ffffffff81582956: pcie_shutdown_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pcie_shutdown_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a42f0)
Location: drivers/pci/hotplug/pciehp_hpc.c:827
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff815a42f0-ffffffff815a4336: pcie_shutdown_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pcie_shutdown_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164cee0)
Location: drivers/pci/hotplug/pciehp_hpc.c:877
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff8164cee0-ffffffff8164cf2c: pcie_shutdown_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pcie_shutdown_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81671230)
Location: drivers/pci/hotplug/pciehp_hpc.c:880
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff81671230-ffffffff8167127c: pcie_shutdown_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pcie_shutdown_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81653740)
Location: drivers/pci/hotplug/pciehp_hpc.c:916
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff81653740-ffffffff8165378c: pcie_shutdown_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pcie_shutdown_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:917
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff81ce9045-ffffffff81ce905a: pcie_shutdown_notification.cold (STB_LOCAL)
ffffffff816c54c0-ffffffff816c551b: pcie_shutdown_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pcie_shutdown_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:945
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff81eb00e1-ffffffff81eb00f6: pcie_shutdown_notification.cold (STB_LOCAL)
ffffffff817eb2b0-ffffffff817eb329: pcie_shutdown_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pcie_shutdown_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:947
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff8208f972-ffffffff8208f987: pcie_shutdown_notification.cold (STB_LOCAL)
ffffffff81911690-ffffffff81911709: pcie_shutdown_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pcie_shutdown_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:938
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff8210fcd2-ffffffff8210fce7: pcie_shutdown_notification.cold (STB_LOCAL)
ffffffff81954d30-ffffffff81954da9: pcie_shutdown_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void pcie_shutdown_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:939
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff821ed9fa-ffffffff821eda0f: pcie_shutdown_notification.cold (STB_LOCAL)
ffffffff8199e1c0-ffffffff8199e239: pcie_shutdown_notification (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pcie_shutdown_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070cf78)
Location: drivers/pci/hotplug/pciehp_hpc.c:827
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffff80001070cf78-ffff80001070cfec: pcie_shutdown_notification (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pcie_shutdown_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d974a)
Location: drivers/pci/hotplug/pciehp_hpc.c:827
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffe0004d974a-ffffffe0004d97b4: pcie_shutdown_notification (STB_GLOBAL)
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
void pcie_shutdown_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81597b00)
Location: drivers/pci/hotplug/pciehp_hpc.c:827
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff81597b00-ffffffff81597b46: pcie_shutdown_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pcie_shutdown_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81586c90)
Location: drivers/pci/hotplug/pciehp_hpc.c:827
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff81586c90-ffffffff81586cd6: pcie_shutdown_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pcie_shutdown_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81598040)
Location: drivers/pci/hotplug/pciehp_hpc.c:827
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff81598040-ffffffff81598086: pcie_shutdown_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pcie_shutdown_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b2480)
Location: drivers/pci/hotplug/pciehp_hpc.c:827
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_remove
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
**Symbols:**

```
ffffffff815b2480-ffffffff815b24c6: pcie_shutdown_notification (STB_GLOBAL)
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
