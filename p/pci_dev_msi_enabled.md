# Function: <code>pci_dev_msi_enabled</code>

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
In arch/x86/pci/common.c (0)
Location: include/linux/pci.h:533
Inline: True
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
In arch/x86/pci/common.c (0)
Location: include/linux/pci.h:532
Inline: True
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
In arch/x86/pci/common.c (0)
Location: include/linux/pci.h:562
Inline: True
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
In arch/x86/pci/common.c (0)
Location: include/linux/pci.h:589
Inline: True
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
In arch/x86/pci/common.c (0)
Location: include/linux/pci.h:614
Inline: True
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
In arch/x86/pci/common.c (ffffffff8186c31b)
Location: include/linux/pci.h:618
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_enable_device
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
In arch/x86/pci/common.c (ffffffff8188c3fb)
Location: include/linux/pci.h:639
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_enable_device
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
In arch/x86/pci/common.c (ffffffff818d6d37)
Location: include/linux/pci.h:656
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_enable_device
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
In arch/x86/pci/common.c (ffffffff819090b7)
Location: include/linux/pci.h:653
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_enable_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164be6b)
Location: include/linux/pci.h:680
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In arch/x86/pci/common.c (ffffffff81bb9978)
Location: include/linux/pci.h:680
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_enable_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816701bb)
Location: include/linux/pci.h:696
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In arch/x86/pci/common.c (ffffffff81bce288)
Location: include/linux/pci.h:696
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_enable_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816526bb)
Location: include/linux/pci.h:694
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In arch/x86/pci/common.c (ffffffff81bc1c48)
Location: include/linux/pci.h:694
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_enable_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c442a)
Location: include/linux/pci.h:710
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In arch/x86/pci/common.c (ffffffff81c92258)
Location: include/linux/pci.h:710
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_enable_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817ea082)
Location: include/linux/pci.h:723
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In arch/x86/pci/common.c (ffffffff81e418d0)
Location: include/linux/pci.h:723
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_enable_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81910122)
Location: include/linux/pci.h:727
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In arch/x86/pci/common.c (ffffffff8201bf30)
Location: include/linux/pci.h:727
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_enable_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81953842)
Location: include/linux/pci.h:732
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In arch/x86/pci/common.c (ffffffff8209c5d0)
Location: include/linux/pci.h:732
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_enable_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199ccd2)
Location: include/linux/pci.h:755
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In arch/x86/pci/common.c (ffffffff82173db0)
Location: include/linux/pci.h:755
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_enable_device
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/common.c (ffffffff818a8477)
Location: include/linux/pci.h:653
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_enable_device
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
In arch/x86/pci/common.c (ffffffff81862e87)
Location: include/linux/pci.h:653
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_enable_device
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
In arch/x86/pci/common.c (ffffffff818f9ad7)
Location: include/linux/pci.h:653
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_enable_device
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
In arch/x86/pci/common.c (ffffffff8191ac37)
Location: include/linux/pci.h:653
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
  - arch/x86/pci/common.c:pcibios_enable_device
```
</details>
</li>
</ul>

## Differences
