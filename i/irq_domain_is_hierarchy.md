# Function: <code>irq_domain_is_hierarchy</code>

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
In kernel/irq/irqdomain.c (0)
Location: include/linux/irqdomain.h:395
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/irqdomain.h:395
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/irqdomain.h:429
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/irqdomain.h:429
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/irqdomain.h:436
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/irqdomain.h:436
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/irqdomain.h:471
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/irqdomain.h:471
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/irqdomain.h:483
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/irqdomain.h:483
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
In kernel/irq/irqdomain.c (ffffffff810fd6fe)
Location: include/linux/irqdomain.h:489
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pci/msi.c (ffffffff81541f9b)
Location: include/linux/irqdomain.h:489
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/msi.c:pci_msi_setup_msi_irqs
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
In kernel/irq/irqdomain.c (ffffffff81108b4e)
Location: include/linux/irqdomain.h:492
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pci/msi.c (ffffffff815592eb)
Location: include/linux/irqdomain.h:492
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/msi.c:pci_msi_setup_msi_irqs
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
In kernel/irq/irqdomain.c (ffffffff8111213a)
Location: include/linux/irqdomain.h:499
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/pci/msi.c (ffffffff815893ab)
Location: include/linux/irqdomain.h:499
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/msi.c:pci_msi_setup_msi_irqs
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
In kernel/irq/irqdomain.c (ffffffff8111e3ba)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff8156a968)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/pci/msi.c (ffffffff815aad4b)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/msi.c:pci_msi_setup_msi_irqs
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
In kernel/irq/irqdomain.c (ffffffff8112b09a)
Location: include/linux/irqdomain.h:512
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff8161003b)
Location: include/linux/irqdomain.h:512
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/pci/msi.c (ffffffff8165456b)
Location: include/linux/irqdomain.h:512
Inline: True
Inline callers:
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:free_msi_irqs
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
In kernel/irq/irqdomain.c (ffffffff81126b2a)
Location: include/linux/irqdomain.h:528
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff8163650b)
Location: include/linux/irqdomain.h:528
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/pci/msi.c (ffffffff8165dc4f)
Location: include/linux/irqdomain.h:528
Inline: True
Inline callers:
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:free_msi_irqs
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
In kernel/irq/irqdomain.c (ffffffff81126b6a)
Location: include/linux/irqdomain.h:524
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff816192e8)
Location: include/linux/irqdomain.h:524
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/pci/msi.c (ffffffff8163feb4)
Location: include/linux/irqdomain.h:524
Inline: True
Inline callers:
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:free_msi_irqs
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
In kernel/irq/irqdomain.c (ffffffff811470da)
Location: include/linux/irqdomain.h:533
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff816885b8)
Location: include/linux/irqdomain.h:533
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/pci/msi.c (ffffffff816b0c9d)
Location: include/linux/irqdomain.h:533
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:free_msi_irqs
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
In kernel/irq/irqdomain.c (ffffffff8116b94a)
Location: include/linux/irqdomain.h:548
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff817a588f)
Location: include/linux/irqdomain.h:548
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/pci/msi/irqdomain.c (ffffffff817d581d)
Location: include/linux/irqdomain.h:548
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_teardown_msi_irqs
  - drivers/pci/msi/irqdomain.c:pci_msi_setup_msi_irqs
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
In kernel/irq/irqdomain.c (ffffffff811a0b1a)
Location: include/linux/irqdomain.h:536
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff818bd526)
Location: include/linux/irqdomain.h:536
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/pci/msi/irqdomain.c (ffffffff818f6c65)
Location: include/linux/irqdomain.h:536
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_supports
  - drivers/pci/msi/irqdomain.c:pci_msi_teardown_msi_irqs
  - drivers/pci/msi/irqdomain.c:pci_msi_setup_msi_irqs
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
In kernel/irq/irqdomain.c (ffffffff811b29ca)
Location: include/linux/irqdomain.h:539
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff819015cf)
Location: include/linux/irqdomain.h:539
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/pci/msi/irqdomain.c (ffffffff8193a0c5)
Location: include/linux/irqdomain.h:539
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_supports
  - drivers/pci/msi/irqdomain.c:pci_msi_teardown_msi_irqs
  - drivers/pci/msi/irqdomain.c:pci_msi_setup_msi_irqs
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
In kernel/irq/irqdomain.c (ffffffff811c27ba)
Location: include/linux/irqdomain.h:539
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff81948ecf)
Location: include/linux/irqdomain.h:539
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/pci/msi/irqdomain.c (ffffffff81982f25)
Location: include/linux/irqdomain.h:539
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_supports
  - drivers/pci/msi/irqdomain.c:pci_msi_teardown_msi_irqs
  - drivers/pci/msi/irqdomain.c:pci_msi_setup_msi_irqs
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
In kernel/irq/irqdomain.c (ffff800010183b8c)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib.c (ffff8000106be0a0)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/pci/msi.c (ffff80001071448c)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/msi.c:pci_msi_setup_msi_irqs
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
In kernel/irq/irqdomain.c (c03d2df8)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib.c (c085ddf8)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/pci/msi.c (c089ee88)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/msi.c:pci_msi_setup_msi_irqs
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/irqdomain.h:549
Inline: True
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
In kernel/irq/irqdomain.c (ffffffe00011ad9e)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a4ff6)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/pci/msi.c (ffffffe0004de022)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/msi.c:pci_msi_setup_msi_irqs
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
In kernel/irq/irqdomain.c (ffffffff8111699a)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff81560128)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/pci/msi.c (ffffffff8159e51b)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/msi.c:pci_msi_setup_msi_irqs
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
In kernel/irq/irqdomain.c (ffffffff8110768a)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff81550f78)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/pci/msi.c (ffffffff8158d6ab)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/msi.c:pci_msi_setup_msi_irqs
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
In kernel/irq/irqdomain.c (ffffffff8111488a)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff8155ec98)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/pci/msi.c (ffffffff8159ea9b)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/msi.c:pci_msi_setup_msi_irqs
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
In kernel/irq/irqdomain.c (ffffffff8111feba)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_dispose_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff81578b28)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
```
```
In drivers/pci/msi.c (ffffffff815b8ecb)
Location: include/linux/irqdomain.h:506
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/msi.c:pci_msi_setup_msi_irqs
```
</details>
</li>
</ul>

## Differences
