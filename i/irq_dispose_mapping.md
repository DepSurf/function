# Function: <code>irq_dispose_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e0ea0)
Location: kernel/irq/irqdomain.c:632
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_remove
```
**Symbols:**

```
ffffffff810e0ea0-ffffffff810e0eec: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e6f70)
Location: kernel/irq/irqdomain.c:671
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_remove
```
**Symbols:**

```
ffffffff810e6f70-ffffffff810e6fd1: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ed960)
Location: kernel/irq/irqdomain.c:694
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_remove
```
**Symbols:**

```
ffffffff810ed960-ffffffff810ed9c1: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ed340)
Location: kernel/irq/irqdomain.c:832
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff810ed340-ffffffff810ed392: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f5d40)
Location: kernel/irq/irqdomain.c:846
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff810f5d40-ffffffff810f5d92: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fe0e0)
Location: kernel/irq/irqdomain.c:848
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff810fe0e0-ffffffff810fe132: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811098b0)
Location: kernel/irq/irqdomain.c:848
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff811098b0-ffffffff81109902: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:865
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff811133a1-ffffffff811133b4: irq_dispose_mapping.cold (STB_LOCAL)
ffffffff81112ea0-ffffffff81112efa: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111f130)
Location: kernel/irq/irqdomain.c:867
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff8111f130-ffffffff8111f18a: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112b670)
Location: kernel/irq/irqdomain.c:852
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
**Symbols:**

```
ffffffff8112b670-ffffffff8112b6ce: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81127130)
Location: kernel/irq/irqdomain.c:876
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
**Symbols:**

```
ffffffff81127130-ffffffff8112718e: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81127320)
Location: kernel/irq/irqdomain.c:843
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
**Symbols:**

```
ffffffff81127320-ffffffff8112744b: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81147880)
Location: kernel/irq/irqdomain.c:866
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
**Symbols:**

```
ffffffff81147880-ffffffff811479ae: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116bce0)
Location: kernel/irq/irqdomain.c:866
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
**Symbols:**

```
ffffffff8116bce0-ffffffff8116be21: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811a0ee0)
Location: kernel/irq/irqdomain.c:923
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
**Symbols:**

```
ffffffff811a0ee0-ffffffff811a103c: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b2d50)
Location: kernel/irq/irqdomain.c:904
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
**Symbols:**

```
ffffffff811b2d50-ffffffff811b2e9d: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c2b70)
Location: kernel/irq/irqdomain.c:904
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
**Symbols:**

```
ffffffff811c2b70-ffffffff811c2cbd: irq_dispose_mapping (STB_GLOBAL)
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
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010184c78)
Location: kernel/irq/irqdomain.c:867
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_release_resources
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_unmap_msi
  - drivers/pci/controller/pcie-xilinx.c:xilinx_msi_teardown_irq
  - drivers/pci/controller/pcie-xilinx.c:xilinx_msi_teardown_irq
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_exit
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/pci/controller/pcie-altera.c:altera_pcie_remove
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_remove
  - drivers/acpi/irq.c:acpi_unregister_gsi
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_remove
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_remove
```
**Symbols:**

```
ffff800010184c78-ffff800010184cf4: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d3d1c)
Location: kernel/irq/irqdomain.c:867
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_gpio_request_free
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_msi_teardown
  - drivers/pci/controller/pci-tegra.c:tegra_msi_teardown_irq
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_unmap_msi
  - drivers/pci/controller/pcie-xilinx.c:xilinx_msi_teardown_irq
  - drivers/pci/controller/pcie-altera.c:altera_pcie_remove
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_remove
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/tps65217.c:tps65217_remove
  - drivers/clocksource/timer-tegra.c:tegra_init_timer
  - drivers/clocksource/timer-tegra.c:tegra_init_timer
  - drivers/memory/omap-gpmc.c:gpmc_remove
```
**Symbols:**

```
c03d3d1c-c03d3da0: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c0000000001decb0)
Location: kernel/irq/irqdomain.c:867
Inline: False
Direct callers:
  - arch/powerpc/sysdev/mpic_u3msi.c:u3msi_teardown_msi_irqs
  - arch/powerpc/platforms/powernv/pci.c:pnv_teardown_msi_irqs
  - arch/powerpc/platforms/powernv/pci.c:pnv_setup_msi_irqs
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_post_init
  - arch/powerpc/platforms/pseries/msi.c:rtas_teardown_msi_irqs
  - arch/powerpc/platforms/pseries/vio.c:vio_unregister_device
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/pci/controller/pcie-xilinx.c:xilinx_msi_teardown_irq
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_ppc_of_remove
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_ppc_of_remove
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_ppc_of_probe
```
**Symbols:**

```
c0000000001decb0-c0000000001ded30: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011bb18)
Location: kernel/irq/irqdomain.c:867
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/pci/controller/pcie-xilinx.c:xilinx_msi_teardown_irq
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffe00011bb18-ffffffe00011bb82: irq_dispose_mapping (STB_GLOBAL)
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
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81117710)
Location: kernel/irq/irqdomain.c:867
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff81117710-ffffffff8111776a: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81108400)
Location: kernel/irq/irqdomain.c:867
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff81108400-ffffffff8110845a: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81115600)
Location: kernel/irq/irqdomain.c:867
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff81115600-ffffffff8111565a: irq_dispose_mapping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_dispose_mapping(unsigned int virq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81120c30)
Location: kernel/irq/irqdomain.c:867
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_remove
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_exit
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff81120c30-ffffffff81120c8a: irq_dispose_mapping (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
