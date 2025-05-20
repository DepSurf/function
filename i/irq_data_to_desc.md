# Function: <code>irq_data_to_desc</code>

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
In kernel/irq/manage.c (0)
Location: include/linux/irqdesc.h:99
Inline: True
```
```
In kernel/irq/dummychip.c (0)
Location: include/linux/irqdesc.h:99
Inline: True
```
```
In kernel/irq/generic-chip.c (0)
Location: include/linux/irqdesc.h:99
Inline: True
```
```
In kernel/irq/migration.c (0)
Location: include/linux/irqdesc.h:99
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: include/linux/irqdesc.h:99
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (0)
Location: include/linux/irqdesc.h:99
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
In kernel/irq/manage.c (0)
Location: include/linux/irqdesc.h:106
Inline: True
```
```
In kernel/irq/dummychip.c (0)
Location: include/linux/irqdesc.h:106
Inline: True
```
```
In kernel/irq/generic-chip.c (0)
Location: include/linux/irqdesc.h:106
Inline: True
```
```
In kernel/irq/migration.c (0)
Location: include/linux/irqdesc.h:106
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: include/linux/irqdesc.h:106
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (0)
Location: include/linux/irqdesc.h:106
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
In kernel/irq/manage.c (0)
Location: include/linux/irqdesc.h:109
Inline: True
```
```
In kernel/irq/dummychip.c (0)
Location: include/linux/irqdesc.h:109
Inline: True
```
```
In kernel/irq/generic-chip.c (0)
Location: include/linux/irqdesc.h:109
Inline: True
```
```
In kernel/irq/migration.c (0)
Location: include/linux/irqdesc.h:109
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: include/linux/irqdesc.h:109
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (0)
Location: include/linux/irqdesc.h:109
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: include/linux/irqdesc.h:109
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
In kernel/irq/manage.c (0)
Location: include/linux/irqdesc.h:116
Inline: True
```
```
In kernel/irq/dummychip.c (0)
Location: include/linux/irqdesc.h:116
Inline: True
```
```
In kernel/irq/generic-chip.c (0)
Location: include/linux/irqdesc.h:116
Inline: True
```
```
In kernel/irq/migration.c (0)
Location: include/linux/irqdesc.h:116
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: include/linux/irqdesc.h:116
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (0)
Location: include/linux/irqdesc.h:116
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: include/linux/irqdesc.h:116
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
In arch/x86/kernel/apic/vector.c (0)
Location: include/linux/irqdesc.h:118
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/linux/irqdesc.h:118
Inline: True
```
```
In kernel/irq/dummychip.c (0)
Location: include/linux/irqdesc.h:118
Inline: True
```
```
In kernel/irq/generic-chip.c (0)
Location: include/linux/irqdesc.h:118
Inline: True
```
```
In kernel/irq/migration.c (0)
Location: include/linux/irqdesc.h:118
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: include/linux/irqdesc.h:118
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (0)
Location: include/linux/irqdesc.h:118
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (0)
Location: include/linux/irqdesc.h:118
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (0)
Location: include/linux/irqdesc.h:118
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
In arch/x86/kernel/apic/vector.c (ffffffff8105e5b4)
Location: include/linux/irqdesc.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff810f7cda)
Location: include/linux/irqdesc.h:118
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/dummychip.c (ffffffff810fadec)
Location: include/linux/irqdesc.h:118
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
```
In kernel/irq/generic-chip.c (ffffffff810fb58d)
Location: include/linux/irqdesc.h:118
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_alt_chip
```
```
In kernel/irq/migration.c (ffffffff810ff400)
Location: include/linux/irqdesc.h:118
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff815007b8)
Location: include/linux/irqdesc.h:118
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff815030a1)
Location: include/linux/irqdesc.h:118
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81505307)
Location: include/linux/irqdesc.h:118
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
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
In arch/x86/kernel/apic/vector.c (ffffffff81064244)
Location: include/linux/irqdesc.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff8110342a)
Location: include/linux/irqdesc.h:118
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/dummychip.c (ffffffff811065ac)
Location: include/linux/irqdesc.h:118
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
```
In kernel/irq/generic-chip.c (ffffffff81106d4d)
Location: include/linux/irqdesc.h:118
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_alt_chip
```
```
In kernel/irq/migration.c (ffffffff8110abe0)
Location: include/linux/irqdesc.h:118
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff815151ed)
Location: include/linux/irqdesc.h:118
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff815179a1)
Location: include/linux/irqdesc.h:118
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81519bf7)
Location: include/linux/irqdesc.h:118
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
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
In arch/x86/kernel/apic/vector.c (ffffffff81067904)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff8110be1c)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/dummychip.c (ffffffff8110fb6c)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
```
In kernel/irq/generic-chip.c (ffffffff811102ca)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_alt_chip
```
```
In kernel/irq/migration.c (ffffffff81114290)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff815433a7)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81545ba1)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81547d46)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816d0408)
Location: include/linux/irqdesc.h:120
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
In arch/x86/kernel/apic/vector.c (ffffffff81068244)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff8111821c)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/dummychip.c (ffffffff8111bdec)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
```
In kernel/irq/generic-chip.c (ffffffff8111c52a)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_alt_chip
```
```
In kernel/irq/migration.c (ffffffff81120400)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff815642b7)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81566ac0)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81568c66)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8157445c)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816f4228)
Location: include/linux/irqdesc.h:120
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
In arch/x86/kernel/apic/vector.c (ffffffff8106f237)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff81123a36)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/dummychip.c (ffffffff81128105)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
```
In kernel/irq/generic-chip.c (ffffffff81128858)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_alt_chip
```
```
In kernel/irq/migration.c (ffffffff8112c935)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff816067e5)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81608ed6)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8160c1a1)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff817ac918)
Location: include/linux/irqdesc.h:120
Inline: True
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
In arch/x86/kernel/apic/vector.c (ffffffff810707a4)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff8111f886)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/dummychip.c (ffffffff81123be5)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
```
In kernel/irq/generic-chip.c (ffffffff81124198)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_alt_chip
```
```
In kernel/irq/migration.c (ffffffff81128365)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8162aad2)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8162d5e6)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff816309e8)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81632012)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff817c150c)
Location: include/linux/irqdesc.h:122
Inline: True
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
In arch/x86/kernel/apic/vector.c (ffffffff81070fc4)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff8111fb46)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/dummychip.c (ffffffff81123f35)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
```
In kernel/irq/generic-chip.c (ffffffff811244e8)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_alt_chip
```
```
In kernel/irq/migration.c (ffffffff81128625)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8160e7b2)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81611256)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81614688)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81615c22)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff817a4a6c)
Location: include/linux/irqdesc.h:122
Inline: True
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
In arch/x86/kernel/apic/vector.c (ffffffff8107cca8)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff8113ffe6)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/dummychip.c (ffffffff81144515)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
```
In kernel/irq/generic-chip.c (ffffffff81144ae8)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_alt_chip
```
```
In kernel/irq/irqdomain.c (ffffffff81145f09)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_resolve_mapping
```
```
In kernel/irq/migration.c (ffffffff81148bf5)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8167d652)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81680506)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81683878)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81684ff7)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff8182e27c)
Location: include/linux/irqdesc.h:122
Inline: True
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
In arch/x86/kernel/apic/vector.c (ffffffff8108c2f8)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff811638e6)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/dummychip.c (ffffffff811683e5)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
```
In kernel/irq/generic-chip.c (ffffffff81168ad5)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_alt_chip
```
```
In kernel/irq/irqdomain.c (ffffffff8116a157)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_resolve_mapping
```
```
In kernel/irq/migration.c (ffffffff8116d735)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81799126)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8179c48e)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8179fe3b)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff817a17d7)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff8196ee4e)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc
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
In arch/x86/kernel/apic/vector.c (ffffffff810a0608)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff811975b6)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/dummychip.c (ffffffff8119cb45)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
```
In kernel/irq/generic-chip.c (ffffffff8119d2e5)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_alt_chip
```
```
In kernel/irq/irqdomain.c (ffffffff8119ebe7)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_resolve_mapping
```
```
In kernel/irq/migration.c (ffffffff811a28e5)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818af1a6)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818b2eae)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818b6c5a)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b8927)
Location: include/linux/irqdesc.h:122
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
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
In arch/x86/kernel/apic/vector.c (ffffffff810a3588)
Location: include/linux/irqdesc.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff811a915a)
Location: include/linux/irqdesc.h:125
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/dummychip.c (ffffffff811ae9c5)
Location: include/linux/irqdesc.h:125
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
```
In kernel/irq/generic-chip.c (ffffffff811af175)
Location: include/linux/irqdesc.h:125
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_alt_chip
```
```
In kernel/irq/irqdomain.c (ffffffff811b0ad9)
Location: include/linux/irqdesc.h:125
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_resolve_mapping
```
```
In kernel/irq/migration.c (ffffffff811b47e5)
Location: include/linux/irqdesc.h:125
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818f2167)
Location: include/linux/irqdesc.h:125
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818f5efe)
Location: include/linux/irqdesc.h:125
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818f9cce)
Location: include/linux/irqdesc.h:125
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fb9c3)
Location: include/linux/irqdesc.h:125
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
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
In arch/x86/kernel/apic/vector.c (ffffffff810aa558)
Location: include/linux/irqdesc.h:125
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff811b8cba)
Location: include/linux/irqdesc.h:125
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/dummychip.c (ffffffff811be5c5)
Location: include/linux/irqdesc.h:125
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
```
In kernel/irq/generic-chip.c (ffffffff811bed75)
Location: include/linux/irqdesc.h:125
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_alt_chip
```
```
In kernel/irq/irqdomain.c (ffffffff811c0859)
Location: include/linux/irqdesc.h:125
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_resolve_mapping
```
```
In kernel/irq/migration.c (ffffffff811c4665)
Location: include/linux/irqdesc.h:125
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81939997)
Location: include/linux/irqdesc.h:125
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8193e48a)
Location: include/linux/irqdesc.h:125
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff819410f0)
Location: include/linux/irqdesc.h:125
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81942ff3)
Location: include/linux/irqdesc.h:125
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
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
In kernel/irq/manage.c (ffff80001017aa88)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/irq/dummychip.c (ffff8000101803c0)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
```
In kernel/irq/generic-chip.c (ffff800010180b70)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_alt_chip
```
```
In drivers/irqchip/irq-ti-sci-inta.c (ffff80001067e2d4)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_set_type
```
```
In drivers/pinctrl/pinctrl-amd.c (ffff800010694144)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff80001069b29c)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
```
```
In drivers/pinctrl/pinctrl-ocelot.c (ffff80001069fe5c)
Location: include/linux/irqdesc.h:120
Inline: True
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (ffff8000106a12b8)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_set_type
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_set_type
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (ffff8000106a3f50)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_set_type
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106af1c4)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b606c)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_set_type
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_set_type
```
```
In drivers/gpio/gpio-ftgpio010.c (ffff8000106cec6c)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
```
```
In drivers/gpio/gpio-pl061.c (ffff8000106d3c40)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
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
In kernel/irq/manage.c (c03cbd04)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/dummychip.c (c03d0238)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
```
In kernel/irq/generic-chip.c (c03d09d0)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_alt_chip
```
```
In drivers/pinctrl/pinctrl-amd.c (c0834c0c)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/pinctrl-rockchip.c (c0838e24)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
```
```
In drivers/pinctrl/pinctrl-ocelot.c (c0844a04)
Location: include/linux/irqdesc.h:120
Inline: True
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (c084556c)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_set_type
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_set_type
```
```
In drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c (c084d7d4)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_set_irq_type
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_set_irq_type
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (c084fa04)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
```
```
In drivers/pinctrl/samsung/pinctrl-exynos.c (c0851fcc)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_set_type
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_set_type
```
```
In drivers/gpio/gpio-ftgpio010.c (c0868548)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
```
```
In drivers/gpio/gpio-omap.c (c086cc14)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_type
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_type
```
```
In drivers/gpio/gpio-pl061.c (c086effc)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
```
```
In drivers/gpio/gpio-tegra.c (c0871454)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_set_type
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_set_type
```
```
In drivers/gpio/gpio-vf610.c (c08733ac)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_set_type
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_set_type
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
In kernel/irq/manage.c (c0000000001d4f74)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/dummychip.c (c0000000001dadf0)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
```
In kernel/irq/generic-chip.c (c0000000001db824)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_alt_chip
```
```
In drivers/pinctrl/pinctrl-amd.c (c000000000830fec)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/pinctrl-ocelot.c (c00000000083879c)
Location: include/linux/irqdesc.h:120
Inline: True
```
```
In drivers/gpio/gpio-ftgpio010.c (c00000000084a1a0)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
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
In kernel/irq/manage.c (ffffffe000114878)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/dummychip.c (ffffffe000118434)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
```
In kernel/irq/generic-chip.c (ffffffe000118bc8)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_alt_chip
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffe00049e742)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/pinctrl-ocelot.c (ffffffe0004a3aa8)
Location: include/linux/irqdesc.h:120
Inline: True
```
```
In drivers/gpio/gpio-ftgpio010.c (ffffffe0004ae584)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
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
In arch/x86/kernel/apic/vector.c (ffffffff81067d34)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff811107fc)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/dummychip.c (ffffffff811143cc)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
```
In kernel/irq/generic-chip.c (ffffffff81114b0a)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_alt_chip
```
```
In kernel/irq/migration.c (ffffffff811189e0)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8155c8a7)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155df90)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816b9a18)
Location: include/linux/irqdesc.h:120
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
In arch/x86/kernel/apic/vector.c (ffffffff810580a4)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff8110152c)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/dummychip.c (ffffffff811050dc)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
```
In kernel/irq/generic-chip.c (ffffffff8110581a)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_alt_chip
```
```
In kernel/irq/migration.c (ffffffff81109a50)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8154d0d0)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8154f276)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8155aa6c)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81697658)
Location: include/linux/irqdesc.h:120
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
In arch/x86/kernel/apic/vector.c (ffffffff810681e4)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff8110e6ec)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/dummychip.c (ffffffff811122bc)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
```
In kernel/irq/generic-chip.c (ffffffff811129fa)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_alt_chip
```
```
In kernel/irq/migration.c (ffffffff811168d0)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff815585e7)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155adf0)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8155cf96)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8156878c)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff816e7ee8)
Location: include/linux/irqdesc.h:120
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
In arch/x86/kernel/apic/vector.c (ffffffff810698c4)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_update_vector
```
```
In kernel/irq/manage.c (ffffffff81119c1c)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/manage.c:irq_do_set_affinity
```
```
In kernel/irq/dummychip.c (ffffffff8111d8dc)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
```
In kernel/irq/generic-chip.c (ffffffff8111e18a)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_alt_chip
```
```
In kernel/irq/migration.c (ffffffff81121f10)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - kernel/irq/migration.c:__irq_move_irq
  - kernel/irq/migration.c:irq_move_masked_irq
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81572477)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81574c80)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81576e26)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff815826ac)
Location: include/linux/irqdesc.h:120
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff817025e8)
Location: include/linux/irqdesc.h:120
Inline: True
```
</details>
</li>
</ul>

## Differences
