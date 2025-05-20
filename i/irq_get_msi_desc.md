# Function: <code>irq_get_msi_desc</code>

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
In kernel/irq/msi.c (ffffffff810e2a8d)
Location: include/linux/irq.h:641
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi.c (ffffffff814539c0)
Location: include/linux/irq.h:641
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
  - drivers/pci/msi.c:default_restore_msi_irq
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_write_msi_msg
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
In kernel/irq/msi.c (ffffffff810e851d)
Location: include/linux/irq.h:670
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi.c (ffffffff814a02d0)
Location: include/linux/irq.h:670
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_write_msi_msg
  - drivers/pci/msi.c:default_restore_msi_irq
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
In kernel/irq/msi.c (ffffffff810eef4d)
Location: include/linux/irq.h:687
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi.c (ffffffff814c1e50)
Location: include/linux/irq.h:687
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_write_msi_msg
  - drivers/pci/msi.c:default_restore_msi_irq
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
In kernel/irq/msi.c (ffffffff810eed7d)
Location: include/linux/irq.h:737
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi.c (ffffffff814cc500)
Location: include/linux/irq.h:737
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_write_msi_msg
  - drivers/pci/msi.c:default_restore_msi_irq
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
In kernel/irq/msi.c (ffffffff810f782d)
Location: include/linux/irq.h:766
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi.c (ffffffff8150ca30)
Location: include/linux/irq.h:766
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_write_msi_msg
  - drivers/pci/msi.c:default_restore_msi_irq
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
In kernel/irq/msi.c (ffffffff810ffb85)
Location: include/linux/irq.h:768
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi.c (ffffffff81541880)
Location: include/linux/irq.h:768
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_write_msi_msg
  - drivers/pci/msi.c:default_restore_msi_irq
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
In kernel/irq/msi.c (ffffffff8110b365)
Location: include/linux/irq.h:769
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi.c (ffffffff81558bd0)
Location: include/linux/irq.h:769
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_write_msi_msg
  - drivers/pci/msi.c:default_restore_msi_irq
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
In kernel/irq/msi.c (ffffffff81114a45)
Location: include/linux/irq.h:782
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi.c (ffffffff81588c72)
Location: include/linux/irq.h:782
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_write_msi_msg
  - drivers/pci/msi.c:default_restore_msi_irq
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
In kernel/irq/msi.c (ffffffff81120c45)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi.c (ffffffff815aa592)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_write_msi_msg
  - drivers/pci/msi.c:default_restore_msi_irq
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
In kernel/irq/msi.c (ffffffff8112d215)
Location: include/linux/irq.h:830
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi.c (ffffffff81653620)
Location: include/linux/irq.h:830
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_write_msi_msg
  - drivers/pci/msi.c:default_restore_msi_irqs
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
In kernel/irq/msi.c (ffffffff81128c95)
Location: include/linux/irq.h:843
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi.c (ffffffff8165d520)
Location: include/linux/irq.h:843
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_write_msi_msg
  - drivers/pci/msi.c:default_restore_msi_irqs
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
In kernel/irq/msi.c (ffffffff81128f15)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi.c (ffffffff8163f980)
Location: include/linux/irq.h:845
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_write_msi_msg
  - drivers/pci/msi.c:default_restore_msi_irqs
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
In kernel/irq/msi.c (ffffffff81149587)
Location: include/linux/irq.h:847
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_mode_show
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi.c (ffffffff816b1d30)
Location: include/linux/irq.h:847
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_write_msi_msg
  - drivers/pci/msi.c:default_restore_msi_irqs
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
In kernel/irq/msi.c (ffffffff8116e135)
Location: include/linux/irq.h:851
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi/msi.c (ffffffff817d3daa)
Location: include/linux/irq.h:851
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_irq_get_affinity
  - drivers/pci/msi/msi.c:pci_restore_msi_state
  - drivers/pci/msi/msi.c:pci_write_msi_msg
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
In kernel/irq/msi.c (ffffffff811a3655)
Location: include/linux/irq.h:853
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi/api.c (ffffffff818f47aa)
Location: include/linux/irq.h:853
Inline: True
Inline callers:
  - drivers/pci/msi/api.c:pci_irq_get_affinity
```
```
In drivers/pci/msi/msi.c (ffffffff818f5781)
Location: include/linux/irq.h:853
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:pci_write_msi_msg
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
In kernel/irq/msi.c (ffffffff811b5525)
Location: include/linux/irq.h:866
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi/api.c (ffffffff81937bda)
Location: include/linux/irq.h:866
Inline: True
Inline callers:
  - drivers/pci/msi/api.c:pci_irq_get_affinity
```
```
In drivers/pci/msi/msi.c (ffffffff81938bb1)
Location: include/linux/irq.h:866
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:pci_write_msi_msg
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
In kernel/irq/msi.c (ffffffff811c53a5)
Location: include/linux/irq.h:848
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi/api.c (ffffffff81980a3a)
Location: include/linux/irq.h:848
Inline: True
Inline callers:
  - drivers/pci/msi/api.c:pci_irq_get_affinity
```
```
In drivers/pci/msi/msi.c (ffffffff81981a11)
Location: include/linux/irq.h:848
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:pci_write_msi_msg
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
In kernel/irq/msi.c (ffff800010186d34)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi.c (ffff800010713b5c)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_write_msi_msg
  - drivers/pci/msi.c:default_restore_msi_irq
```
```
In drivers/pci/controller/pcie-xilinx.c (ffff800010723548)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_msi_teardown_irq
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
In kernel/irq/msi.c (c03d5938)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi.c (c089e5f0)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_write_msi_msg
  - drivers/pci/msi.c:default_restore_msi_irq
```
```
In drivers/pci/controller/pcie-xilinx.c (c08b0018)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_msi_teardown_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (c0000000001e14e0)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi.c (c0000000008834c0)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_write_msi_msg
  - drivers/pci/msi.c:default_restore_msi_irq
```
```
In drivers/pci/controller/pcie-xilinx.c (c000000000891b04)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_msi_teardown_irq
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
In kernel/irq/msi.c (ffffffe00011cb26)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi.c (ffffffe0004dd6c8)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_write_msi_msg
  - drivers/pci/msi.c:default_restore_msi_irq
```
```
In drivers/pci/controller/pcie-xilinx.c (ffffffe0004e6bb0)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_msi_teardown_irq
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
In kernel/irq/msi.c (ffffffff81119225)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi.c (ffffffff8159dd62)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_write_msi_msg
  - drivers/pci/msi.c:default_restore_msi_irq
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
In kernel/irq/msi.c (ffffffff8110a295)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi.c (ffffffff8158cef2)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_write_msi_msg
  - drivers/pci/msi.c:default_restore_msi_irq
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
In kernel/irq/msi.c (ffffffff81117115)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi.c (ffffffff8159e2e2)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_write_msi_msg
  - drivers/pci/msi.c:default_restore_msi_irq
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
In kernel/irq/msi.c (ffffffff811227a5)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - kernel/irq/msi.c:get_cached_msi_msg
```
```
In drivers/pci/msi.c (ffffffff815b8712)
Location: include/linux/irq.h:800
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_mode_show
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_write_msi_msg
  - drivers/pci/msi.c:default_restore_msi_irq
```
</details>
</li>
</ul>

## Differences
