# Function: <code>__pci_register_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81438d40)
Location: drivers/pci/pci-driver.c:1278
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/gpio/gpio-intel-mid.c:intel_gpio_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/xen/platform-pci.c:platform_pci_module_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/char/agp/intel-agp.c:agp_intel_init
  - drivers/char/agp/via-agp.c:agp_via_init
  - drivers/ata/ata_piix.c:piix_init
  - drivers/ata/pata_sis.c:sis_pci_driver_init
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_init
  - drivers/usb/dwc2/pci.c:dwc2_pci_driver_init
  - drivers/usb/host/xhci-pci.c:xhci_pci_init
```
**Symbols:**

```
ffffffff81438d40-ffffffff81438d8e: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81484c00)
Location: drivers/pci/pci-driver.c:1275
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/xen/platform-pci.c:platform_pci_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/char/agp/intel-agp.c:agp_intel_init
  - drivers/char/agp/via-agp.c:agp_via_init
  - drivers/ata/ata_piix.c:piix_init
  - drivers/ata/pata_sis.c:sis_pci_driver_init
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_init
  - drivers/usb/host/xhci-pci.c:xhci_pci_init
  - drivers/platform/x86/intel_pmc_core.c:intel_pmc_core_driver_init
```
**Symbols:**

```
ffffffff81484c00-ffffffff81484c4e: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814a6380)
Location: drivers/pci/pci-driver.c:1284
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/xen/platform-pci.c:platform_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/char/agp/intel-agp.c:agp_intel_init
  - drivers/char/agp/via-agp.c:agp_via_init
  - drivers/ata/ata_piix.c:piix_init
  - drivers/ata/pata_sis.c:sis_pci_driver_init
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_init
  - drivers/usb/host/xhci-pci.c:xhci_pci_init
  - drivers/platform/x86/intel_pmc_core.c:intel_pmc_core_driver_init
```
**Symbols:**

```
ffffffff814a6380-ffffffff814a63ce: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814b0320)
Location: drivers/pci/pci-driver.c:1302
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/xen/platform-pci.c:platform_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/char/agp/intel-agp.c:agp_intel_init
  - drivers/char/agp/via-agp.c:agp_via_init
  - drivers/ata/ata_piix.c:piix_init
  - drivers/ata/pata_sis.c:sis_pci_driver_init
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_init
  - drivers/usb/host/xhci-pci.c:xhci_pci_init
  - drivers/platform/x86/intel_pmc_core.c:intel_pmc_core_driver_init
```
**Symbols:**

```
ffffffff814b0320-ffffffff814b036e: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814ef850)
Location: drivers/pci/pci-driver.c:1370
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/xen/platform-pci.c:platform_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/char/agp/intel-agp.c:agp_intel_init
  - drivers/char/agp/via-agp.c:agp_via_init
  - drivers/ata/ata_piix.c:piix_init
  - drivers/ata/pata_sis.c:sis_pci_driver_init
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_init
  - drivers/usb/host/xhci-pci.c:xhci_pci_init
```
**Symbols:**

```
ffffffff814ef850-ffffffff814ef8ac: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8151f930)
Location: drivers/pci/pci-driver.c:1391
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/pci/hotplug/shpchp_core.c:shpcd_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/xen/platform-pci.c:platform_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_init
  - drivers/char/agp/via-agp.c:agp_via_init
  - drivers/ata/ata_piix.c:piix_init
  - drivers/ata/pata_sis.c:sis_pci_driver_init
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-pci.c:xhci_pci_init
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_driver_init
```
**Symbols:**

```
ffffffff8151f930-ffffffff8151f989: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81535740)
Location: drivers/pci/pci-driver.c:1388
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/pci/hotplug/shpchp_core.c:shpcd_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/xen/platform-pci.c:platform_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_init
  - drivers/char/agp/via-agp.c:agp_via_init
  - drivers/ata/ata_piix.c:piix_init
  - drivers/ata/pata_sis.c:sis_pci_driver_init
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-pci.c:xhci_pci_init
```
**Symbols:**

```
ffffffff81535740-ffffffff81535799: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff815650f0)
Location: drivers/pci/pci-driver.c:1422
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/pci/hotplug/shpchp_core.c:shpcd_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/xen/platform-pci.c:platform_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_init
  - drivers/char/agp/via-agp.c:agp_via_init
  - drivers/ata/ata_piix.c:piix_init
  - drivers/ata/pata_sis.c:sis_pci_driver_init
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-pci.c:xhci_pci_init
```
**Symbols:**

```
ffffffff815650f0-ffffffff81565149: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81586430)
Location: drivers/pci/pci-driver.c:1435
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/pci/hotplug/shpchp_core.c:shpcd_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/xen/platform-pci.c:platform_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_init
  - drivers/char/agp/via-agp.c:agp_via_init
  - drivers/ata/ata_piix.c:piix_init
  - drivers/ata/pata_sis.c:sis_pci_driver_init
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_init
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-pci.c:xhci_pci_init
```
**Symbols:**

```
ffffffff81586430-ffffffff81586489: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8162cf80)
Location: drivers/pci/pci-driver.c:1400
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/pci/hotplug/shpchp_core.c:shpcd_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/xen/platform-pci.c:platform_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_init
  - drivers/char/agp/via-agp.c:agp_via_init
  - drivers/ata/ata_piix.c:piix_init
  - drivers/ata/pata_sis.c:sis_pci_driver_init
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_init
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_driver_init
```
**Symbols:**

```
ffffffff8162cf80-ffffffff8162cfd6: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81652670)
Location: drivers/pci/pci-driver.c:1379
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/pci/hotplug/shpchp_core.c:shpcd_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/xen/platform-pci.c:platform_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_init
  - drivers/char/agp/via-agp.c:agp_via_init
  - drivers/ata/ata_piix.c:piix_init
  - drivers/ata/pata_sis.c:sis_pci_driver_init
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_init
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_driver_init
```
**Symbols:**

```
ffffffff81652670-ffffffff816526c6: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81635130)
Location: drivers/pci/pci-driver.c:1379
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/pci/hotplug/shpchp_core.c:shpcd_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/xen/platform-pci.c:platform_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_init
  - drivers/char/agp/via-agp.c:agp_via_init
  - drivers/ata/ata_piix.c:piix_init
  - drivers/ata/pata_sis.c:sis_pci_driver_init
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_init
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_driver_init
```
**Symbols:**

```
ffffffff81635130-ffffffff81635189: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff816a5290)
Location: drivers/pci/pci-driver.c:1392
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/pci/hotplug/shpchp_core.c:shpcd_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/xen/platform-pci.c:platform_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_init
  - drivers/char/agp/via-agp.c:agp_via_init
  - drivers/ata/ata_piix.c:piix_init
  - drivers/ata/pata_sis.c:sis_pci_driver_init
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_init
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_driver_init
```
**Symbols:**

```
ffffffff816a5290-ffffffff816a52fa: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff817c7850)
Location: drivers/pci/pci-driver.c:1421
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/pci/hotplug/shpchp_core.c:shpcd_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/xen/platform-pci.c:platform_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_init
  - drivers/char/agp/via-agp.c:agp_via_init
  - drivers/ata/ata_piix.c:piix_init
  - drivers/ata/pata_sis.c:sis_pci_driver_init
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_init
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_driver_init
```
**Symbols:**

```
ffffffff817c7850-ffffffff817c78be: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff818e4f60)
Location: drivers/pci/pci-driver.c:1427
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_init
  - drivers/pci/hotplug/shpchp_core.c:shpcd_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/xen/platform-pci.c:platform_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/tty/serial/8250/8250_mid.c:mid8250_pci_driver_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_init
  - drivers/char/agp/via-agp.c:agp_via_init
  - drivers/ata/ata_piix.c:piix_init
  - drivers/ata/pata_sis.c:sis_pci_driver_init
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_driver_init
```
**Symbols:**

```
ffffffff818e4f60-ffffffff818e4fce: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff819285a0)
Location: drivers/pci/pci-driver.c:1428
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_init
  - drivers/pci/hotplug/shpchp_core.c:shpcd_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/xen/platform-pci.c:platform_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/tty/serial/8250/8250_mid.c:mid8250_pci_driver_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_init
  - drivers/char/agp/via-agp.c:agp_via_init
  - drivers/ata/ata_piix.c:piix_init
  - drivers/ata/pata_sis.c:sis_pci_driver_init
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_driver_init
```
**Symbols:**

```
ffffffff819285a0-ffffffff8192860e: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81970d90)
Location: drivers/pci/pci-driver.c:1440
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_init
  - drivers/pci/hotplug/shpchp_core.c:shpcd_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/xen/platform-pci.c:platform_driver_init
  - drivers/tty/serial/8250/8250_mid.c:mid8250_pci_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_init
  - drivers/char/agp/via-agp.c:agp_via_init
  - drivers/ata/ata_piix.c:piix_init
  - drivers/ata/pata_sis.c:sis_pci_driver_init
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/platform/x86/intel_scu_pcidrv.c:intel_scu_pci_driver_init
```
**Symbols:**

```
ffffffff81970d90-ffffffff81970dfa: __pci_register_driver (STB_GLOBAL)
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
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffff8000106eaa68)
Location: drivers/pci/pci-driver.c:1435
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/pci/hotplug/shpchp_core.c:shpcd_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-pci.c:xhci_pci_init
```
**Symbols:**

```
ffff8000106eaa68-ffff8000106eaad0: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c08858cc)
Location: drivers/pci/pci-driver.c:1435
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/mfd/sm501.c:sm501_base_init
  - drivers/usb/dwc2/pci.c:dwc2_pci_driver_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-pci.c:xhci_pci_init
```
**Symbols:**

```
c08858cc-c0885928: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c000000000865bc0)
Location: drivers/pci/pci-driver.c:1435
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/video/fbdev/gxt4500.c:gxt4500_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-pci.c:xhci_pci_init
```
**Symbols:**

```
c000000000865bc0-c000000000865c34: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffe0004c097c)
Location: drivers/pci/pci-driver.c:1435
Inline: False
Direct callers:
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/pci/hotplug/shpchp_core.c:shpcd_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-pci.c:xhci_pci_init
```
**Symbols:**

```
ffffffe0004c097c-ffffffe0004c09de: __pci_register_driver (STB_GLOBAL)
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
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157a950)
Location: drivers/pci/pci-driver.c:1435
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/pci/hotplug/shpchp_core.c:shpcd_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/xen/platform-pci.c:platform_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_init
  - drivers/char/agp/via-agp.c:agp_via_init
  - drivers/nvme/host/pci.c:nvme_init
  - drivers/ata/ata_piix.c:piix_init
  - drivers/ata/pata_sis.c:sis_pci_driver_init
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-pci.c:xhci_pci_init
```
**Symbols:**

```
ffffffff8157a950-ffffffff8157a9a9: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81569090)
Location: drivers/pci/pci-driver.c:1435
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/pci/hotplug/shpchp_core.c:shpcd_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_init
  - drivers/char/agp/via-agp.c:agp_via_init
  - drivers/nvme/host/pci.c:nvme_init
  - drivers/ata/ata_piix.c:piix_init
  - drivers/ata/pata_sis.c:sis_pci_driver_init
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_init
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
  - drivers/usb/host/xhci-pci.c:xhci_pci_init
```
**Symbols:**

```
ffffffff81569090-ffffffff815690e9: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157a180)
Location: drivers/pci/pci-driver.c:1435
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/pci/hotplug/shpchp_core.c:shpcd_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/xen/platform-pci.c:platform_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_init
  - drivers/char/agp/via-agp.c:agp_via_init
  - drivers/ata/ata_piix.c:piix_init
  - drivers/ata/pata_sis.c:sis_pci_driver_init
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_init
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-pci.c:xhci_pci_init
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_driver_init
```
**Symbols:**

```
ffffffff8157a180-ffffffff8157a1d9: __pci_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __pci_register_driver(struct pci_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81594700)
Location: drivers/pci/pci-driver.c:1435
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore.c:intel_uncore_init
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_init
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_init
  - drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_init
  - drivers/pci/hotplug/shpchp_core.c:shpcd_init
  - drivers/video/fbdev/imsttfb.c:imsttfb_init
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_init
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_init
  - drivers/xen/platform-pci.c:platform_driver_init
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_init
  - drivers/char/agp/via-agp.c:agp_via_init
  - drivers/ata/ata_piix.c:piix_init
  - drivers/ata/pata_sis.c:sis_pci_driver_init
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_init
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_init
  - drivers/usb/host/ehci-pci.c:ehci_pci_init
  - drivers/usb/host/ohci-pci.c:ohci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/usb/host/xhci-pci.c:xhci_pci_init
```
**Symbols:**

```
ffffffff81594700-ffffffff81594759: __pci_register_driver (STB_GLOBAL)
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
