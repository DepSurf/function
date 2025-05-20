# Function: <code>has_acpi_companion</code>

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
In drivers/pci/probe.c (ffffffff814315da)
Location: include/linux/acpi.h:70
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/acpi/glue.c (ffffffff8147f11d)
Location: include/linux/acpi.h:70
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/iommu/intel-iommu.c (ffffffff815354ce)
Location: include/linux/acpi.h:70
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/mfd/mfd-core.c (ffffffff8158aa1f)
Location: include/linux/acpi.h:70
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/i2c/i2c-core.c (ffffffff8167cf19)
Location: include/linux/acpi.h:70
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_register_adapter
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
In drivers/pci/probe.c (ffffffff8147ccfd)
Location: include/linux/acpi.h:72
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/acpi/glue.c (ffffffff814cd9a5)
Location: include/linux/acpi.h:72
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/dma/dmaengine.c (ffffffff8150d4a9)
Location: include/linux/acpi.h:72
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/iommu/intel-iommu.c (ffffffff81589ef6)
Location: include/linux/acpi.h:72
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/mfd/mfd-core.c (ffffffff815dfbc3)
Location: include/linux/acpi.h:72
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/i2c/i2c-core.c (ffffffff816ddc5d)
Location: include/linux/acpi.h:72
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_register_adapter
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
In drivers/gpio/gpiolib.c (ffffffff814903b0)
Location: include/linux/acpi.h:93
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
```
```
In drivers/pci/probe.c (ffffffff8149e25d)
Location: include/linux/acpi.h:93
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/acpi/glue.c (ffffffff814ef874)
Location: include/linux/acpi.h:93
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/dma/dmaengine.c (ffffffff815395d9)
Location: include/linux/acpi.h:93
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/iommu/intel-iommu.c (ffffffff815b75a6)
Location: include/linux/acpi.h:93
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/base/platform.c (ffffffff815cdc7d)
Location: include/linux/acpi.h:93
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq
```
```
In drivers/mfd/mfd-core.c (ffffffff8160c863)
Location: include/linux/acpi.h:93
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/i2c/i2c-core.c (ffffffff8170dfd2)
Location: include/linux/acpi.h:93
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:i2c_acpi_find_bus_speed
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
In drivers/gpio/gpiolib.c (ffffffff81499ac0)
Location: include/linux/acpi.h:98
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
```
```
In drivers/acpi/glue.c (ffffffff814fc9d2)
Location: include/linux/acpi.h:98
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/dma/dmaengine.c (ffffffff8154cef9)
Location: include/linux/acpi.h:98
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/iommu/intel-iommu.c (ffffffff815cd420)
Location: include/linux/acpi.h:98
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/base/platform.c (ffffffff815e26ad)
Location: include/linux/acpi.h:98
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq
```
```
In drivers/base/dma-mapping.c (ffffffff815f635c)
Location: include/linux/acpi.h:98
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_configure
```
```
In drivers/mfd/mfd-core.c (ffffffff81620949)
Location: include/linux/acpi.h:98
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81724107)
Location: include/linux/acpi.h:98
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817274c8)
Location: include/linux/acpi.h:98
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/platform/x86/silead_dmi.c (ffffffff81798a2c)
Location: include/linux/acpi.h:98
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
In drivers/gpio/gpiolib.c (ffffffff814d7a60)
Location: include/linux/acpi.h:94
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/acpi/glue.c (ffffffff8153e70c)
Location: include/linux/acpi.h:94
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/dma/dmaengine.c (ffffffff815b0369)
Location: include/linux/acpi.h:94
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/iommu/intel-iommu.c (ffffffff8163421f)
Location: include/linux/acpi.h:94
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/base/platform.c (ffffffff81649838)
Location: include/linux/acpi.h:94
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq
```
```
In drivers/base/dma-mapping.c (ffffffff8165e275)
Location: include/linux/acpi.h:94
Inline: True
Inline callers:
  - drivers/base/dma-mapping.c:dma_configure
```
```
In drivers/mfd/mfd-core.c (ffffffff816892da)
Location: include/linux/acpi.h:94
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81795fed)
Location: include/linux/acpi.h:94
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81798a78)
Location: include/linux/acpi.h:94
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/platform/x86/silead_dmi.c (ffffffff8180f0a5)
Location: include/linux/acpi.h:94
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
In drivers/gpio/gpiolib.c (ffffffff81506e10)
Location: include/linux/acpi.h:96
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/pci/pci-driver.c (ffffffff81520b57)
Location: include/linux/acpi.h:96
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/acpi/glue.c (ffffffff81574652)
Location: include/linux/acpi.h:96
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/dma/dmaengine.c (ffffffff815e8731)
Location: include/linux/acpi.h:96
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/iommu/intel-iommu.c (ffffffff8166f72f)
Location: include/linux/acpi.h:96
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/base/platform.c (ffffffff81684df8)
Location: include/linux/acpi.h:96
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq
```
```
In drivers/mfd/mfd-core.c (ffffffff816c53f1)
Location: include/linux/acpi.h:96
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff817d8b45)
Location: include/linux/acpi.h:96
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817db4d5)
Location: include/linux/acpi.h:96
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/platform/x86/silead_dmi.c (ffffffff81858f25)
Location: include/linux/acpi.h:96
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
In drivers/gpio/gpiolib.c (ffffffff8151b4a0)
Location: include/linux/acpi.h:96
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/pci/pci-driver.c (ffffffff8153698a)
Location: include/linux/acpi.h:96
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/acpi/glue.c (ffffffff8158c0c2)
Location: include/linux/acpi.h:96
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/dma/dmaengine.c (ffffffff81603457)
Location: include/linux/acpi.h:96
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168dc8f)
Location: include/linux/acpi.h:96
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/base/platform.c (ffffffff816a4a48)
Location: include/linux/acpi.h:96
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq
```
```
In drivers/mfd/mfd-core.c (ffffffff816e67e3)
Location: include/linux/acpi.h:96
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff817ffce5)
Location: include/linux/acpi.h:96
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81802885)
Location: include/linux/acpi.h:96
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff81877ed5)
Location: include/linux/acpi.h:96
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
In drivers/gpio/gpiolib.c (ffffffff81549781)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/pci/pci-driver.c (ffffffff8156627b)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/acpi/glue.c (ffffffff815bced2)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/dma/dmaengine.c (ffffffff81635aa2)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81687b3e)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c65ed)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/base/platform.c (ffffffff816dd9bf)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq
  - drivers/base/platform.c:platform_get_irq
```
```
In drivers/mfd/mfd-core.c (ffffffff8171ff99)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81840ef5)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81843d45)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff818bcb56)
Location: include/linux/acpi.h:84
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
In drivers/gpio/gpiolib.c (ffffffff8156bd71)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/pci/pci-driver.c (ffffffff815875db)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/acpi/glue.c (ffffffff815de192)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/dma/dmaengine.c (ffffffff816577c2)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff816aa1ee)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e955d)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/base/platform.c (ffffffff81701a71)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
```
```
In drivers/mfd/mfd-core.c (ffffffff8174426c)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81872855)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff818756b5)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff818ef676)
Location: include/linux/acpi.h:84
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
In drivers/gpio/gpiolib.c (ffffffff8160d431)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
```
```
In drivers/pci/pci-driver.c (ffffffff8162d3db)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/acpi/glue.c (ffffffff81688b72)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/dma/dmaengine.c (ffffffff81707eb4)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8175cb20)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
```
In drivers/tty/serdev/core.c (ffffffff8176ddbe)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a0317)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/base/platform.c (ffffffff817bc885)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
```
```
In drivers/mfd/mfd-core.c (ffffffff81801e3a)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff819469e5)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a115)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff819c3416)
Location: include/linux/acpi.h:84
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
In drivers/gpio/gpiolib.c (ffffffff81634675)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
```
```
In drivers/pci/pci-driver.c (ffffffff81652acb)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/acpi/glue.c (ffffffff816a6742)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/dma/dmaengine.c (ffffffff817250f0)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff817779f0)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
```
In drivers/tty/serdev/core.c (ffffffff8178877e)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/iommu/intel/iommu.c (ffffffff817b0fa5)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/base/platform.c (ffffffff817d1242)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
```
```
In drivers/mfd/mfd-core.c (ffffffff81812bfe)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff8194c945)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194fca5)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff819c37f6)
Location: include/linux/acpi.h:84
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
In drivers/pci/pci-driver.c (ffffffff8163558b)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/acpi/glue.c (ffffffff816893d2)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/dma/dmaengine.c (ffffffff817063a4)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8175b3b6)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
```
In drivers/tty/serdev/core.c (ffffffff8176c0ce)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/iommu/intel/iommu.c (ffffffff81793b35)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/base/platform.c (ffffffff817b4c62)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
```
```
In drivers/mfd/mfd-core.c (ffffffff817f730f)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/spi/spi.c (ffffffff8186bdc1)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff819304b5)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933b65)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff819a7d36)
Location: include/linux/acpi.h:84
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
In drivers/pci/pci-driver.c (ffffffff816a549b)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/acpi/glue.c (ffffffff816fe812)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/dma/dmaengine.c (ffffffff81781c64)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff817def51)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
```
In drivers/tty/serdev/core.c (ffffffff817f18a0)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181b9d5)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/base/platform.c (ffffffff8183e042)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
```
```
In drivers/mfd/mfd-core.c (ffffffff81880629)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/spi/spi.c (ffffffff818fbcad)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff819d3795)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d6e95)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff81a57566)
Location: include/linux/acpi.h:84
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
In drivers/pci/pci-driver.c (ffffffff817c819c)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/acpi/glue.c (ffffffff8182c1ea)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/dma/dmaengine.c (ffffffff818b8694)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8191ddf0)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
```
In drivers/tty/serdev/core.c (ffffffff81931fbe)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195c766)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/base/platform.c (ffffffff819809f7)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_dma_configure
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
```
```
In drivers/base/physical_location.c (ffffffff819b4833)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/base/physical_location.c:dev_add_physical_location
```
```
In drivers/mfd/mfd-core.c (ffffffff819c8cde)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/spi/spi.c (ffffffff81a4d388)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81b34f0a)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b399f5)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff81bc701f)
Location: include/linux/acpi.h:84
Inline: True
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
In drivers/pci/pci-driver.c (ffffffff818e59dc)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/acpi/glue.c (ffffffff8195eb6a)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/dma/dmaengine.c (ffffffff81a05b94)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81a79d9c)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
```
In drivers/tty/serdev/core.c (ffffffff81a90a1e)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac4246)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/base/platform.c (ffffffff81aee537)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_dma_configure
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
```
```
In drivers/base/physical_location.c (ffffffff81b29813)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/base/physical_location.c:dev_add_physical_location
```
```
In drivers/mfd/mfd-core.c (ffffffff81b400ca)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/spi/spi.c (ffffffff81bd5d38)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81cca04a)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf355)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff81d6f85f)
Location: include/linux/acpi.h:84
Inline: True
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
In drivers/pci/pci-driver.c (ffffffff8192901c)
Location: include/linux/acpi.h:73
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/acpi/glue.c (ffffffff819a513a)
Location: include/linux/acpi.h:73
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/dma/dmaengine.c (ffffffff81a4ea54)
Location: include/linux/acpi.h:73
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81ac5576)
Location: include/linux/acpi.h:73
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
```
In drivers/tty/serdev/core.c (ffffffff81adc22e)
Location: include/linux/acpi.h:73
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b10c06)
Location: include/linux/acpi.h:73
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
```
In drivers/base/platform.c (ffffffff81b3c8f7)
Location: include/linux/acpi.h:73
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_dma_configure
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq_optional
```
```
In drivers/base/physical_location.c (ffffffff81b799c3)
Location: include/linux/acpi.h:73
Inline: True
Inline callers:
  - drivers/base/physical_location.c:dev_add_physical_location
```
```
In drivers/mfd/mfd-core.c (ffffffff81b9344a)
Location: include/linux/acpi.h:73
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/spi/spi.c (ffffffff81c2caf8)
Location: include/linux/acpi.h:73
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81d31d9a)
Location: include/linux/acpi.h:73
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d37425)
Location: include/linux/acpi.h:73
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff81ddd51e)
Location: include/linux/acpi.h:73
Inline: True
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
In drivers/pci/pci-driver.c (ffffffff8197181c)
Location: include/linux/acpi.h:85
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/acpi/glue.c (ffffffff819eda8a)
Location: include/linux/acpi.h:85
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/dma/dmaengine.c (ffffffff81a9a6f4)
Location: include/linux/acpi.h:85
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81b18576)
Location: include/linux/acpi.h:85
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
```
In drivers/tty/serdev/core.c (ffffffff81b2f511)
Location: include/linux/acpi.h:85
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b61516)
Location: include/linux/acpi.h:85
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:device_lookup_iommu
```
```
In drivers/base/physical_location.c (ffffffff81bcd8f3)
Location: include/linux/acpi.h:85
Inline: True
Inline callers:
  - drivers/base/physical_location.c:dev_add_physical_location
```
```
In drivers/mfd/mfd-core.c (ffffffff81be73ea)
Location: include/linux/acpi.h:85
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/spi/spi.c (ffffffff81cdf461)
Location: include/linux/acpi.h:85
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81de7d7a)
Location: include/linux/acpi.h:85
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ded6a5)
Location: include/linux/acpi.h:85
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff81e93230)
Location: include/linux/acpi.h:85
Inline: True
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
In drivers/gpio/gpiolib.c (ffff8000106bf0ac)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/pci/pci-driver.c (ffff8000106eb2b4)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/acpi/glue.c (ffff80001076a578)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/dma/dmaengine.c (ffff8000107fdfc8)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/tty/serial/8250/8250_core.c (ffff800010884578)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
```
In drivers/base/platform.c (ffff8000108edbf8)
Location: include/linux/acpi.h:84
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffff800010940310)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffff800010ab60e0)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010aba470)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9cccc)
Location: include/linux/acpi.h:84
Inline: True
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
In drivers/gpio/gpiolib.c (0)
Location: include/linux/acpi.h:725
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/acpi.h:725
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/acpi.h:725
Inline: True
```
```
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/linux/acpi.h:725
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:725
Inline: True
```
```
In drivers/mfd/mfd-core.c (0)
Location: include/linux/acpi.h:725
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/acpi.h:725
Inline: True
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
In drivers/gpio/gpiolib.c (0)
Location: include/linux/acpi.h:725
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/acpi.h:725
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/acpi.h:725
Inline: True
```
```
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/linux/acpi.h:725
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:725
Inline: True
```
```
In drivers/mfd/mfd-core.c (0)
Location: include/linux/acpi.h:725
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/acpi.h:725
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
In drivers/gpio/gpiolib.c (0)
Location: include/linux/acpi.h:725
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/acpi.h:725
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/acpi.h:725
Inline: True
```
```
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/linux/acpi.h:725
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/linux/acpi.h:725
Inline: True
```
```
In drivers/mfd/mfd-core.c (0)
Location: include/linux/acpi.h:725
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/acpi.h:725
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
In drivers/gpio/gpiolib.c (ffffffff81561531)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/pci/pci-driver.c (ffffffff8157b60b)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/acpi/glue.c (ffffffff815d0672)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/dma/dmaengine.c (ffffffff8161d662)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8166fc5e)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
```
In drivers/iommu/intel-iommu.c (ffffffff816af03d)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/base/platform.c (ffffffff816c71c1)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
```
```
In drivers/mfd/mfd-core.c (ffffffff8170230c)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
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
In drivers/gpio/gpiolib.c (ffffffff81552381)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/pci/pci-driver.c (ffffffff8156a23b)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/acpi/glue.c (ffffffff815ba232)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/dma/dmaengine.c (ffffffff81611d52)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8164ed7e)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168c99d)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/base/platform.c (ffffffff816a24c1)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
```
```
In drivers/mfd/mfd-core.c (ffffffff816d611c)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
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
In drivers/gpio/gpiolib.c (ffffffff815600a1)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/pci/pci-driver.c (ffffffff8157b32b)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/acpi/glue.c (ffffffff815d2472)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/dma/dmaengine.c (ffffffff8164b602)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8169e02e)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
```
In drivers/iommu/intel-iommu.c (ffffffff816dd21d)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/base/platform.c (ffffffff816f5731)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
```
```
In drivers/mfd/mfd-core.c (ffffffff8173772c)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff818669e5)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186ab65)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff818e44a6)
Location: include/linux/acpi.h:84
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
In drivers/gpio/gpiolib.c (ffffffff81579f11)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/pci/pci-driver.c (ffffffff8159593b)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_dma_configure
```
```
In drivers/acpi/glue.c (ffffffff815ec332)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/dma/dmaengine.c (ffffffff81665ba2)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dma_request_chan
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff816b84fe)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
```
In drivers/iommu/intel-iommu.c (ffffffff816f770d)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:device_to_iommu
```
```
In drivers/base/platform.c (ffffffff8170ffc1)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:__platform_get_irq
```
```
In drivers/mfd/mfd-core.c (ffffffff81752b6c)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81881c95)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81884af5)
Location: include/linux/acpi.h:84
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/platform/x86/touchscreen_dmi.c (ffffffff81901106)
Location: include/linux/acpi.h:84
Inline: True
```
</details>
</li>
</ul>

## Differences
