# Function: <code>irq_desc_has_action</code>

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
In arch/x86/kernel/irq.c (0)
Location: include/linux/irqdesc.h:163
Inline: True
```
```
In arch/x86/kernel/topology.c (0)
Location: include/linux/irqdesc.h:163
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/irqdesc.h:163
Inline: True
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
In arch/x86/kernel/irq.c (0)
Location: include/linux/irqdesc.h:170
Inline: True
```
```
In arch/x86/kernel/topology.c (0)
Location: include/linux/irqdesc.h:170
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/irqdesc.h:170
Inline: True
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
In arch/x86/kernel/irq.c (0)
Location: include/linux/irqdesc.h:173
Inline: True
```
```
In arch/x86/kernel/topology.c (0)
Location: include/linux/irqdesc.h:173
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/irqdesc.h:173
Inline: True
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
In arch/x86/kernel/irq.c (0)
Location: include/linux/irqdesc.h:180
Inline: True
```
```
In arch/x86/kernel/topology.c (0)
Location: include/linux/irqdesc.h:180
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/irqdesc.h:180
Inline: True
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
In arch/x86/kernel/topology.c (0)
Location: include/linux/irqdesc.h:182
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/irqdesc.h:182
Inline: True
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
In arch/x86/kernel/topology.c (0)
Location: include/linux/irqdesc.h:177
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/irqdesc.h:177
Inline: True
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
In arch/x86/kernel/topology.c (0)
Location: include/linux/irqdesc.h:177
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/irqdesc.h:177
Inline: True
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
In arch/x86/kernel/topology.c (0)
Location: include/linux/irqdesc.h:184
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/irqdesc.h:184
Inline: True
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
In arch/x86/kernel/topology.c (0)
Location: include/linux/irqdesc.h:184
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/irqdesc.h:184
Inline: True
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
In arch/x86/kernel/topology.c (ffffffff8103c7d1)
Location: include/linux/irqdesc.h:184
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
```
```
In drivers/pci/msi.c (ffffffff81653d4b)
Location: include/linux/irqdesc.h:184
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In kernel/irq/manage.c (ffffffff8111eb90)
Location: include/linux/irqdesc.h:186
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_has_action
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
In kernel/irq/manage.c (ffffffff8111ec40)
Location: include/linux/irqdesc.h:186
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_has_action
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
In kernel/irq/manage.c (ffffffff8113f0d0)
Location: include/linux/irqdesc.h:182
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_has_action
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
In kernel/irq/manage.c (ffffffff8116277a)
Location: include/linux/irqdesc.h:176
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_has_action
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
In kernel/irq/manage.c (ffffffff811963ba)
Location: include/linux/irqdesc.h:177
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_has_action
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
In kernel/irq/manage.c (ffffffff811a7d7a)
Location: include/linux/irqdesc.h:180
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_has_action
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
In kernel/irq/manage.c (ffffffff811b78da)
Location: include/linux/irqdesc.h:180
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_has_action
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
In drivers/pci/msi.c (0)
Location: include/linux/irqdesc.h:184
Inline: True
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
In drivers/pci/msi.c (c089efa8)
Location: include/linux/irqdesc.h:184
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In arch/powerpc/kernel/eeh_driver.c (c00000000004a640)
Location: include/linux/irqdesc.h:184
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh_driver.c:eeh_set_irq_state
```
```
In drivers/pci/msi.c (c000000000883e54)
Location: include/linux/irqdesc.h:184
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004de128)
Location: include/linux/irqdesc.h:184
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In arch/x86/kernel/topology.c (0)
Location: include/linux/irqdesc.h:184
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/irqdesc.h:184
Inline: True
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
In arch/x86/kernel/topology.c (0)
Location: include/linux/irqdesc.h:184
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/irqdesc.h:184
Inline: True
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
In arch/x86/kernel/topology.c (0)
Location: include/linux/irqdesc.h:184
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/irqdesc.h:184
Inline: True
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
In arch/x86/kernel/topology.c (0)
Location: include/linux/irqdesc.h:184
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/irqdesc.h:184
Inline: True
```
</details>
</li>
</ul>

## Differences
