# Function: <code>platform_get_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8154d800)
Location: drivers/base/platform.c:87
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
```
**Symbols:**

```
ffffffff8154d800-ffffffff8154d8a1: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8159f610)
Location: drivers/base/platform.c:87
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/base/platform.c:platform_irq_count
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
```
**Symbols:**

```
ffffffff8159f610-ffffffff8159f6a3: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815cdc10)
Location: drivers/base/platform.c:87
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/base/platform.c:platform_irq_count
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
```
**Symbols:**

```
ffffffff815cdc10-ffffffff815cdce2: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815e2640)
Location: drivers/base/platform.c:87
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/base/platform.c:platform_irq_count
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff815e2640-ffffffff815e2712: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816497e0)
Location: drivers/base/platform.c:87
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/base/platform.c:platform_irq_count
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff816497e0-ffffffff816498d0: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81684da0)
Location: drivers/base/platform.c:86
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/base/platform.c:platform_irq_count
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81684da0-ffffffff81684e89: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a49f0)
Location: drivers/base/platform.c:87
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/base/platform.c:platform_irq_count
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff816a49f0-ffffffff816a4ad9: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816dd960)
Location: drivers/base/platform.c:107
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/base/platform.c:platform_irq_count
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff816dd960-ffffffff816ddaa8: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:165
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81702b8a-ffffffff81702ba8: platform_get_irq.cold (STB_LOCAL)
ffffffff81701b60-ffffffff81701b93: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:246
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_remove
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/gpio/gpio-msic.c:platform_msic_gpio_probe
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817bcf6b-ffffffff817bcf89: platform_get_irq.cold (STB_LOCAL)
ffffffff817bc9f0-ffffffff817bca23: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff817d1a11)
Location: drivers/base/platform.c:277
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/gpio/gpio-msic.c:platform_msic_gpio_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81c0e590-ffffffff81c0e5ae: platform_get_irq.cold (STB_LOCAL)
ffffffff817d18f0-ffffffff817d1923: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff817b5446)
Location: drivers/base/platform.c:276
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81c009a4-ffffffff81c009c2: platform_get_irq.cold (STB_LOCAL)
ffffffff817b5320-ffffffff817b5353: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff8183e73d)
Location: drivers/base/platform.c:256
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81d03320-ffffffff81d0333e: platform_get_irq.cold (STB_LOCAL)
ffffffff8183e610-ffffffff8183e643: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff819815a8)
Location: drivers/base/platform.c:259
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
  - drivers/virtio/virtio_mmio.c:vm_synchronize_cbs
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81981450-ffffffff819814a2: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81aef128)
Location: drivers/base/platform.c:259
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
  - drivers/virtio/virtio_mmio.c:vm_synchronize_cbs
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81aeefc0-ffffffff81aef012: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b3d518)
Location: drivers/base/platform.c:259
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
  - drivers/virtio/virtio_mmio.c:vm_synchronize_cbs
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81b3d3b0-ffffffff81b3d402: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b95058)
Location: drivers/base/platform.c:260
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_mmio.c:vm_find_vqs
  - drivers/virtio/virtio_mmio.c:vm_synchronize_cbs
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81b94ef0-ffffffff81b94f42: platform_get_irq (STB_GLOBAL)
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
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffff8000108edd28)
Location: drivers/base/platform.c:165
Inline: False
Direct callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
  - drivers/irqchip/qcom-irq-combiner.c:combiner_probe
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/gpio/gpio-davinci.c:davinci_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mxs-dma.c:mxs_dma_filter_fn
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
  - drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_probe
  - drivers/soc/xilinx/zynqmp_power.c:zynqmp_pm_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/amba-pl011.c:sbsa_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/tty/serial/owl-uart.c:owl_uart_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_shutdown
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe
  - drivers/ata/libahci_platform.c:ahci_platform_init_host
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/net/ethernet/broadcom/bgmac-platform.c:bgmac_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_probe
  - drivers/rtc/rtc-xgene.c:xgene_rtc_resume
  - drivers/rtc/rtc-xgene.c:xgene_rtc_suspend
  - drivers/rtc/rtc-xgene.c:xgene_rtc_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/edac/altera_edac.c:altr_edac_a10_probe
  - drivers/edac/altera_edac.c:altr_edac_device_probe
  - drivers/edac/altera_edac.c:altr_edac_device_probe
  - drivers/edac/altera_edac.c:altr_sdram_probe
  - drivers/edac/altera_edac.c:altr_sdram_probe
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_probe
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm_pmu_platform.c:pmu_parse_irqs
  - drivers/perf/arm_pmu_platform.c:pmu_parse_irqs
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_probe
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe_cluster
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
```
**Symbols:**

```
ffff8000108edd28-ffff8000108edd94: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c09dbbe4)
Location: drivers/base/platform.c:165
Inline: False
Direct callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/bus/omap_l3_smx.c:omap3_l3_probe
  - drivers/bus/omap_l3_smx.c:omap3_l3_probe
  - drivers/bus/omap_l3_noc.c:omap_l3_probe
  - drivers/bus/omap_l3_noc.c:omap_l3_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
  - drivers/gpio/gpio-tegra.c:tegra_gpio_probe
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mxs-dma.c:mxs_dma_filter_fn
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ti/omap-dma.c:omap_dma_remove
  - drivers/dma/ti/omap-dma.c:omap_dma_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/amba-pl011.c:sbsa_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/tty/serial/owl-uart.c:owl_uart_probe
  - drivers/tty/serial/rda-uart.c:rda_uart_probe
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_probe
  - drivers/iommu/omap-iommu.c:omap_iommu_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_shutdown
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe
  - drivers/mfd/sm501.c:sm501_plat_probe
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
  - drivers/mfd/tc6387xb.c:tc6387xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/ata/libahci_platform.c:ahci_platform_init_host
  - drivers/ata/sata_highbank.c:ahci_highbank_probe
  - drivers/mtd/nand/raw/omap2.c:omap_nand_attach_chip
  - drivers/mtd/nand/raw/omap2.c:omap_nand_attach_chip
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/auxdisplay/arm-charlcd.c:charlcd_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_tmio_drv_probe
  - drivers/usb/host/ohci-hcd.c:ohci_hcd_sm501_drv_probe
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_probe
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
  - drivers/rtc/rtc-twl.c:twl_rtc_probe
  - drivers/rtc/rtc-twl.c:twl_rtc_alarm_irq_enable
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/watchdog/npcm_wdt.c:npcm_wdt_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_init
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
  - drivers/clocksource/em_sti.c:em_sti_probe
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_probe
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
  - drivers/memory/tegra/mc.c:tegra_mc_probe
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
```
**Symbols:**

```
c09dbbe4-c09dbc3c: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c000000000986280)
Location: drivers/base/platform.c:165
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
c000000000986280-c000000000986304: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffe000580eb0)
Location: drivers/base/platform.c:165
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sifive.c:sifive_serial_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffe000580eb0-ffffffe000580f0e: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:165
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
```
**Symbols:**

```
ffffffff816c82da-ffffffff816c82f8: platform_get_irq.cold (STB_LOCAL)
ffffffff816c72b0-ffffffff816c72e3: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:165
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
```
**Symbols:**

```
ffffffff816a35da-ffffffff816a35f8: platform_get_irq.cold (STB_LOCAL)
ffffffff816a25b0-ffffffff816a25e3: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:165
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff816f684a-ffffffff816f6868: platform_get_irq.cold (STB_LOCAL)
ffffffff816f5820-ffffffff816f5853: platform_get_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:165
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/virtio/virtio_mmio.c:vm_del_vqs
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/rtc/rtc-cmos.c:cmos_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817110ea-ffffffff81711108: platform_get_irq.cold (STB_LOCAL)
ffffffff817100b0-ffffffff817100e3: platform_get_irq (STB_GLOBAL)
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
