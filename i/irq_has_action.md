# Function: <code>irq_has_action</code>

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
In arch/x86/kernel/irq.c (ffffffff81030efd)
Location: include/linux/irqdesc.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/topology.c (ffffffff81035c7f)
Location: include/linux/irqdesc.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
```
```
In drivers/pci/msi.c (ffffffff814540c7)
Location: include/linux/irqdesc.h:168
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In arch/x86/kernel/irq.c (ffffffff8102ff9e)
Location: include/linux/irqdesc.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/topology.c (ffffffff81034e6f)
Location: include/linux/irqdesc.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
```
```
In drivers/pci/msi.c (ffffffff814a09ef)
Location: include/linux/irqdesc.h:175
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In arch/x86/kernel/irq.c (ffffffff8102ff63)
Location: include/linux/irqdesc.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
```
In arch/x86/kernel/topology.c (ffffffff81034b7f)
Location: include/linux/irqdesc.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
```
```
In drivers/pci/msi.c (ffffffff814c267f)
Location: include/linux/irqdesc.h:178
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In arch/x86/kernel/topology.c (ffffffff81032baf)
Location: include/linux/irqdesc.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
```
```
In drivers/pci/msi.c (ffffffff814ccc8f)
Location: include/linux/irqdesc.h:185
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In arch/x86/kernel/topology.c (ffffffff81034edf)
Location: include/linux/irqdesc.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
```
```
In drivers/pci/msi.c (ffffffff8150d1cf)
Location: include/linux/irqdesc.h:187
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In arch/x86/kernel/topology.c (ffffffff8103605f)
Location: include/linux/irqdesc.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
```
```
In drivers/pci/msi.c (ffffffff815420bc)
Location: include/linux/irqdesc.h:182
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In arch/x86/kernel/topology.c (ffffffff81037244)
Location: include/linux/irqdesc.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
```
```
In drivers/pci/msi.c (ffffffff8155940c)
Location: include/linux/irqdesc.h:182
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In arch/x86/kernel/topology.c (ffffffff81039455)
Location: include/linux/irqdesc.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
```
```
In drivers/pci/msi.c (ffffffff815894ce)
Location: include/linux/irqdesc.h:189
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In arch/x86/kernel/topology.c (ffffffff81039c25)
Location: include/linux/irqdesc.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
```
```
In drivers/pci/msi.c (ffffffff815aae6e)
Location: include/linux/irqdesc.h:189
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In arch/x86/kernel/topology.c (ffffffff8103c7c9)
Location: include/linux/irqdesc.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
```
```
In drivers/pci/msi.c (ffffffff81653d43)
Location: include/linux/irqdesc.h:189
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool irq_has_action(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111eb80)
Location: kernel/irq/manage.c:2842
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - drivers/pci/msi.c:free_msi_irqs
```
**Symbols:**

```
ffffffff8111eb80-ffffffff8111ebaf: irq_has_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool irq_has_action(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111ec30)
Location: kernel/irq/manage.c:2849
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - drivers/pci/msi.c:free_msi_irqs
```
**Symbols:**

```
ffffffff8111ec30-ffffffff8111ec5f: irq_has_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool irq_has_action(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8113f0c0)
Location: kernel/irq/manage.c:2878
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
  - drivers/pci/msi.c:free_msi_irqs
```
**Symbols:**

```
ffffffff8113f0c0-ffffffff8113f0ef: irq_has_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool irq_has_action(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81162760)
Location: kernel/irq/manage.c:2912
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
```
**Symbols:**

```
ffffffff81162760-ffffffff8116279a: irq_has_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool irq_has_action(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811963a0)
Location: kernel/irq/manage.c:2904
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
```
**Symbols:**

```
ffffffff811963a0-ffffffff811963da: irq_has_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool irq_has_action(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811a7d60)
Location: kernel/irq/manage.c:2910
Inline: False
```
**Symbols:**

```
ffffffff811a7d60-ffffffff811a7d9a: irq_has_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool irq_has_action(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811b78c0)
Location: kernel/irq/manage.c:2907
Inline: False
```
**Symbols:**

```
ffffffff811b78c0-ffffffff811b78fa: irq_has_action (STB_GLOBAL)
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
In drivers/pci/msi.c (ffff8000107145ac)
Location: include/linux/irqdesc.h:189
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In drivers/pci/msi.c (c089efa0)
Location: include/linux/irqdesc.h:189
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
In arch/powerpc/kernel/eeh_driver.c (c00000000004a634)
Location: include/linux/irqdesc.h:189
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh_driver.c:eeh_set_irq_state
```
```
In drivers/pci/msi.c (c000000000883e44)
Location: include/linux/irqdesc.h:189
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
In drivers/pci/msi.c (ffffffe0004de11c)
Location: include/linux/irqdesc.h:189
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
In arch/x86/kernel/topology.c (ffffffff81039d85)
Location: include/linux/irqdesc.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
```
```
In drivers/pci/msi.c (ffffffff8159e63e)
Location: include/linux/irqdesc.h:189
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In arch/x86/kernel/topology.c (ffffffff81029695)
Location: include/linux/irqdesc.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
```
```
In drivers/pci/msi.c (ffffffff8158d7ce)
Location: include/linux/irqdesc.h:189
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In arch/x86/kernel/topology.c (ffffffff81039be5)
Location: include/linux/irqdesc.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
```
```
In drivers/pci/msi.c (ffffffff8159ebbe)
Location: include/linux/irqdesc.h:189
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In arch/x86/kernel/topology.c (ffffffff8103abe5)
Location: include/linux/irqdesc.h:189
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
```
```
In drivers/pci/msi.c (ffffffff815b8fee)
Location: include/linux/irqdesc.h:189
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
```
</details>
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
