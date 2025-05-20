# Function: <code>pcie_enable_notification</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pcie_enable_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814511d0)
Location: drivers/pci/hotplug/pciehp_hpc.c:631
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
**Symbols:**

```
ffffffff814511d0-ffffffff81451258: pcie_enable_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pcie_enable_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8149d9e0)
Location: drivers/pci/hotplug/pciehp_hpc.c:635
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
**Symbols:**

```
ffffffff8149d9e0-ffffffff8149da68: pcie_enable_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pcie_enable_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814bf600)
Location: drivers/pci/hotplug/pciehp_hpc.c:671
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
**Symbols:**

```
ffffffff814bf600-ffffffff814bf688: pcie_enable_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pcie_enable_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814c9d80)
Location: drivers/pci/hotplug/pciehp_hpc.c:679
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
**Symbols:**

```
ffffffff814c9d80-ffffffff814c9e07: pcie_enable_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pcie_enable_notification(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8150a330)
Location: drivers/pci/hotplug/pciehp_hpc.c:676
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
**Symbols:**

```
ffffffff8150a330-ffffffff8150a3b7: pcie_enable_notification (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pcie_enable_notification(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8153a4c0)
Location: drivers/pci/hotplug/pciehp_hpc.c:649
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_reenable_notification
```
**Symbols:**

```
ffffffff8153a4c0-ffffffff8153a54c: pcie_enable_notification (STB_LOCAL)
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81552959)
Location: drivers/pci/hotplug/pciehp_hpc.c:680
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81582821)
Location: drivers/pci/hotplug/pciehp_hpc.c:682
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a4201)
Location: drivers/pci/hotplug/pciehp_hpc.c:696
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164cdf1)
Location: drivers/pci/hotplug/pciehp_hpc.c:746
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81671141)
Location: drivers/pci/hotplug/pciehp_hpc.c:749
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81653651)
Location: drivers/pci/hotplug/pciehp_hpc.c:785
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c53cd)
Location: drivers/pci/hotplug/pciehp_hpc.c:786
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817eb1ad)
Location: drivers/pci/hotplug/pciehp_hpc.c:788
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8191154d)
Location: drivers/pci/hotplug/pciehp_hpc.c:788
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81954bed)
Location: drivers/pci/hotplug/pciehp_hpc.c:779
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199e07d)
Location: drivers/pci/hotplug/pciehp_hpc.c:780
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
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
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070ce6c)
Location: drivers/pci/hotplug/pciehp_hpc.c:696
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
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
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d965c)
Location: drivers/pci/hotplug/pciehp_hpc.c:696
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81597a11)
Location: drivers/pci/hotplug/pciehp_hpc.c:696
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81586ba1)
Location: drivers/pci/hotplug/pciehp_hpc.c:696
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81597f51)
Location: drivers/pci/hotplug/pciehp_hpc.c:696
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
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
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b2391)
Location: drivers/pci/hotplug/pciehp_hpc.c:696
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
