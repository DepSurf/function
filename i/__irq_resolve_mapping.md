# Function: <code>__irq_resolve_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct irq_desc *__irq_resolve_mapping(struct irq_domain *domain, irq_hw_number_t hwirq, unsigned int *irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81145ee0)
Location: kernel/irq/irqdomain.c:895
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - kernel/irq/irqdesc.c:generic_handle_domain_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff81145ee0-ffffffff81145f45: __irq_resolve_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct irq_desc *__irq_resolve_mapping(struct irq_domain *domain, irq_hw_number_t hwirq, unsigned int *irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116a120)
Location: kernel/irq/irqdomain.c:895
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - kernel/irq/irqdesc.c:generic_handle_domain_nmi
  - kernel/irq/irqdesc.c:generic_handle_domain_irq
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff8116a120-ffffffff8116a1a2: __irq_resolve_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct irq_desc *__irq_resolve_mapping(struct irq_domain *domain, irq_hw_number_t hwirq, unsigned int *irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119ebb0)
Location: kernel/irq/irqdomain.c:952
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - kernel/irq/irqdesc.c:generic_handle_domain_nmi
  - kernel/irq/irqdesc.c:generic_handle_domain_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_domain_irq
  - kernel/irq/generic-chip.c:irq_gc_get_irq_data
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff8119ebb0-ffffffff8119ec32: __irq_resolve_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct irq_desc *__irq_resolve_mapping(struct irq_domain *domain, irq_hw_number_t hwirq, unsigned int *irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b0aa0)
Location: kernel/irq/irqdomain.c:933
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - kernel/irq/irqdesc.c:generic_handle_domain_nmi
  - kernel/irq/irqdesc.c:generic_handle_domain_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_domain_irq
  - kernel/irq/generic-chip.c:irq_gc_get_irq_data
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff811b0aa0-ffffffff811b0b27: __irq_resolve_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct irq_desc *__irq_resolve_mapping(struct irq_domain *domain, irq_hw_number_t hwirq, unsigned int *irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c0820)
Location: kernel/irq/irqdomain.c:933
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - arch/x86/kernel/apic/io_apic.c:mp_map_pin_to_irq
  - kernel/irq/irqdesc.c:generic_handle_domain_nmi
  - kernel/irq/irqdesc.c:generic_handle_domain_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_domain_irq
  - kernel/irq/generic-chip.c:irq_gc_get_irq_data
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_mapping_affinity
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/twl6030-irq.c:twl6030_mmc_card_detect_config
  - drivers/mfd/lp8788-irq.c:lp8788_irq_handler
  - drivers/mfd/max8997-irq.c:max8997_irq_thread
  - drivers/mfd/max8998-irq.c:max8998_irq_thread
  - drivers/mfd/tps6586x.c:tps6586x_irq
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff811c0820-ffffffff811c08a7: __irq_resolve_mapping (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
