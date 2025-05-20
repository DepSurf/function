# Function: <code>pci_wakeup_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81433f06)
Location: drivers/pci/pci.h:86
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/pcie/pme.c (ffffffff8144b874)
Location: drivers/pci/pci.h:86
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
```
```
In drivers/pci/pci-acpi.c (ffffffff81457478)
Location: drivers/pci/pci.h:86
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81482c08)
Location: drivers/pci/pci.h:88
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pcie/pme.c (ffffffff81497fe5)
Location: drivers/pci/pci.h:88
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff814a4088)
Location: drivers/pci/pci.h:88
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a4198)
Location: drivers/pci/pci.h:88
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pcie/pme.c (ffffffff814b9895)
Location: drivers/pci/pci.h:88
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff814c5e18)
Location: drivers/pci/pci.h:88
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ae1d6)
Location: drivers/pci/pci.h:86
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pcie/pme.c (ffffffff814c4071)
Location: drivers/pci/pci.h:86
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff814cfe8f)
Location: drivers/pci/pci.h:86
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ed5b6)
Location: drivers/pci/pci.h:87
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pcie/pme.c (ffffffff815042ad)
Location: drivers/pci/pci.h:87
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff815100df)
Location: drivers/pci/pci.h:87
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151d1c9)
Location: drivers/pci/pci.h:88
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pcie/pme.c (ffffffff81535249)
Location: drivers/pci/pci.h:88
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff815451cf)
Location: drivers/pci/pci.h:88
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815328c9)
Location: drivers/pci/pci.h:96
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff8154123f)
Location: drivers/pci/pci.h:96
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffffffff8154c7f9)
Location: drivers/pci/pci.h:96
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81562005)
Location: drivers/pci/pci.h:101
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff81570b99)
Location: drivers/pci/pci.h:101
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffffffff8157c436)
Location: drivers/pci/pci.h:101
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815831a5)
Location: drivers/pci/pci.h:112
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff81591d89)
Location: drivers/pci/pci.h:112
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffffffff8159de96)
Location: drivers/pci/pci.h:112
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
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
In drivers/pci/pci.c (ffffffff81629d85)
Location: drivers/pci/pci.h:113
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pcie/pme.c (ffffffff8163d939)
Location: drivers/pci/pci.h:113
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff816405cf)
Location: drivers/pci/pci.h:113
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
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
In drivers/pci/pci.c (ffffffff816501b5)
Location: drivers/pci/pci.h:115
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/pcie/pme.c (ffffffff81663fc9)
Location: drivers/pci/pci.h:115
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff816669df)
Location: drivers/pci/pci.h:115
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
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
In drivers/pci/pci.c (ffffffff81632d75)
Location: drivers/pci/pci.h:109
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/pcie/pme.c (ffffffff81646439)
Location: drivers/pci/pci.h:109
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff81648e8f)
Location: drivers/pci/pci.h:109
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
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
In drivers/pci/pci.c (ffffffff816a2ee5)
Location: drivers/pci/pci.h:130
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/pcie/pme.c (ffffffff816b7ca9)
Location: drivers/pci/pci.h:130
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff816ba8df)
Location: drivers/pci/pci.h:130
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
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
In drivers/pci/pci.c (ffffffff817c50ac)
Location: drivers/pci/pci.h:91
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/pcie/pme.c (ffffffff817dc0a8)
Location: drivers/pci/pci.h:91
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff817df1d0)
Location: drivers/pci/pci.h:91
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
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
In drivers/pci/pci.c (ffffffff818e212c)
Location: drivers/pci/pci.h:106
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/pcie/pme.c (ffffffff818fdf0c)
Location: drivers/pci/pci.h:106
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff81901f30)
Location: drivers/pci/pci.h:106
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
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
In drivers/pci/pci.c (ffffffff8192556c)
Location: drivers/pci/pci.h:94
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/pcie/pme.c (ffffffff819413be)
Location: drivers/pci/pci.h:94
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff819454a8)
Location: drivers/pci/pci.h:94
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
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
In drivers/pci/pci.c (ffffffff8196dcc7)
Location: drivers/pci/pci.h:103
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/pcie/pme.c (ffffffff8198a61e)
Location: drivers/pci/pci.h:103
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
```
In drivers/pci/pci-acpi.c (ffffffff8198e7d8)
Location: drivers/pci/pci.h:103
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e6ff0)
Location: drivers/pci/pci.h:112
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-acpi.c (ffff8000106f7bf0)
Location: drivers/pci/pci.h:112
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffff800010706330)
Location: drivers/pci/pci.h:112
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0882230)
Location: drivers/pci/pci.h:112
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pcie/pme.c (c089d328)
Location: drivers/pci/pci.h:112
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000861630)
Location: drivers/pci/pci.h:112
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.h:112
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: drivers/pci/pci.h:112
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815776c5)
Location: drivers/pci/pci.h:112
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff81585c19)
Location: drivers/pci/pci.h:112
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffffffff81591696)
Location: drivers/pci/pci.h:112
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81565e25)
Location: drivers/pci/pci.h:112
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff815749e9)
Location: drivers/pci/pci.h:112
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffffffff8158098a)
Location: drivers/pci/pci.h:112
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81576ef5)
Location: drivers/pci/pci.h:112
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff81585ad9)
Location: drivers/pci/pci.h:112
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffffffff81591be6)
Location: drivers/pci/pci.h:112
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815913d5)
Location: drivers/pci/pci.h:112
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
```
```
In drivers/pci/pci-acpi.c (ffffffff8159ff89)
Location: drivers/pci/pci.h:112
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/pci/pcie/pme.c (ffffffff815ac259)
Location: drivers/pci/pci.h:112
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
```
</details>
</li>
</ul>

## Differences
