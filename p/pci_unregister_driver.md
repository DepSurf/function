# Function: <code>pci_unregister_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81438d90)
Location: drivers/pci/pci-driver.c:1305
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/char/agp/intel-agp.c:agp_intel_cleanup
  - drivers/char/agp/via-agp.c:agp_via_cleanup
  - drivers/ata/ata_piix.c:piix_exit
  - drivers/ata/pata_sis.c:sis_pci_driver_exit
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_exit
  - drivers/usb/dwc2/pci.c:dwc2_pci_driver_exit
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/xhci-pci.c:xhci_pci_exit
```
**Symbols:**

```
ffffffff81438d90-ffffffff81438e1a: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81484c50)
Location: drivers/pci/pci-driver.c:1302
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/char/agp/intel-agp.c:agp_intel_cleanup
  - drivers/char/agp/via-agp.c:agp_via_cleanup
  - drivers/ata/ata_piix.c:piix_exit
  - drivers/ata/pata_sis.c:sis_pci_driver_exit
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_exit
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/xhci-pci.c:xhci_pci_exit
```
**Symbols:**

```
ffffffff81484c50-ffffffff81484ce3: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814a63d0)
Location: drivers/pci/pci-driver.c:1311
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/char/agp/intel-agp.c:agp_intel_cleanup
  - drivers/char/agp/via-agp.c:agp_via_cleanup
  - drivers/ata/ata_piix.c:piix_exit
  - drivers/ata/pata_sis.c:sis_pci_driver_exit
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_exit
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/xhci-pci.c:xhci_pci_exit
```
**Symbols:**

```
ffffffff814a63d0-ffffffff814a6463: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814b0370)
Location: drivers/pci/pci-driver.c:1329
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/char/agp/intel-agp.c:agp_intel_cleanup
  - drivers/char/agp/via-agp.c:agp_via_cleanup
  - drivers/ata/ata_piix.c:piix_exit
  - drivers/ata/pata_sis.c:sis_pci_driver_exit
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_exit
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/xhci-pci.c:xhci_pci_exit
```
**Symbols:**

```
ffffffff814b0370-ffffffff814b040d: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff814ef8b0)
Location: drivers/pci/pci-driver.c:1398
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/char/agp/intel-agp.c:agp_intel_cleanup
  - drivers/char/agp/via-agp.c:agp_via_cleanup
  - drivers/ata/ata_piix.c:piix_exit
  - drivers/ata/pata_sis.c:sis_pci_driver_exit
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_exit
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/xhci-pci.c:xhci_pci_exit
```
**Symbols:**

```
ffffffff814ef8b0-ffffffff814ef94d: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81521580)
Location: drivers/pci/pci-driver.c:1419
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit
  - drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_cleanup
  - drivers/char/agp/via-agp.c:agp_via_cleanup
  - drivers/ata/ata_piix.c:piix_exit
  - drivers/ata/pata_sis.c:sis_pci_driver_exit
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_exit
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/xhci-pci.c:xhci_pci_exit
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_driver_exit
```
**Symbols:**

```
ffffffff81521580-ffffffff8152161c: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81536fc0)
Location: drivers/pci/pci-driver.c:1416
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit
  - drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_cleanup
  - drivers/char/agp/via-agp.c:agp_via_cleanup
  - drivers/ata/ata_piix.c:piix_exit
  - drivers/ata/pata_sis.c:sis_pci_driver_exit
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_exit
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/xhci-pci.c:xhci_pci_exit
```
**Symbols:**

```
ffffffff81536fc0-ffffffff8153705c: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81566930)
Location: drivers/pci/pci-driver.c:1450
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit
  - drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_cleanup
  - drivers/char/agp/via-agp.c:agp_via_cleanup
  - drivers/ata/ata_piix.c:piix_exit
  - drivers/ata/pata_sis.c:sis_pci_driver_exit
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_exit
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/xhci-pci.c:xhci_pci_exit
```
**Symbols:**

```
ffffffff81566930-ffffffff815669bc: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81587c90)
Location: drivers/pci/pci-driver.c:1463
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit
  - drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_cleanup
  - drivers/char/agp/via-agp.c:agp_via_cleanup
  - drivers/ata/ata_piix.c:piix_exit
  - drivers/ata/pata_sis.c:sis_pci_driver_exit
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_exit
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_cleanup
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/xhci-pci.c:xhci_pci_exit
```
**Symbols:**

```
ffffffff81587c90-ffffffff81587d1c: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8162e4f0)
Location: drivers/pci/pci-driver.c:1428
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit
  - drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_cleanup
  - drivers/char/agp/via-agp.c:agp_via_cleanup
  - drivers/ata/ata_piix.c:piix_exit
  - drivers/ata/pata_sis.c:sis_pci_driver_exit
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_exit
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_cleanup
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
```
**Symbols:**

```
ffffffff8162e4f0-ffffffff8162e57a: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81653bf0)
Location: drivers/pci/pci-driver.c:1407
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit
  - drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_cleanup
  - drivers/char/agp/via-agp.c:agp_via_cleanup
  - drivers/ata/ata_piix.c:piix_exit
  - drivers/ata/pata_sis.c:sis_pci_driver_exit
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_exit
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_cleanup
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
```
**Symbols:**

```
ffffffff81653bf0-ffffffff81653c7a: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81636a30)
Location: drivers/pci/pci-driver.c:1407
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit
  - drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_cleanup
  - drivers/char/agp/via-agp.c:agp_via_cleanup
  - drivers/ata/ata_piix.c:piix_exit
  - drivers/ata/pata_sis.c:sis_pci_driver_exit
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_exit
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_cleanup
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
```
**Symbols:**

```
ffffffff81636a30-ffffffff81636aba: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff816a6c70)
Location: drivers/pci/pci-driver.c:1421
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit
  - drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_cleanup
  - drivers/char/agp/via-agp.c:agp_via_cleanup
  - drivers/ata/ata_piix.c:piix_exit
  - drivers/ata/pata_sis.c:sis_pci_driver_exit
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_exit
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_cleanup
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
```
**Symbols:**

```
ffffffff816a6c70-ffffffff816a6cfa: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff817c78c0)
Location: drivers/pci/pci-driver.c:1450
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit
  - drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_cleanup
  - drivers/char/agp/via-agp.c:agp_via_cleanup
  - drivers/ata/ata_piix.c:piix_exit
  - drivers/ata/pata_sis.c:sis_pci_driver_exit
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_exit
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_cleanup
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
```
**Symbols:**

```
ffffffff817c78c0-ffffffff817c7950: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff818e4fe0)
Location: drivers/pci/pci-driver.c:1456
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit
  - drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/tty/serial/8250/8250_mid.c:mid8250_pci_driver_exit
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_cleanup
  - drivers/char/agp/via-agp.c:agp_via_cleanup
  - drivers/ata/ata_piix.c:piix_exit
  - drivers/ata/pata_sis.c:sis_pci_driver_exit
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_exit
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
```
**Symbols:**

```
ffffffff818e4fe0-ffffffff818e5070: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81928620)
Location: drivers/pci/pci-driver.c:1457
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit
  - drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/tty/serial/8250/8250_mid.c:mid8250_pci_driver_exit
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_cleanup
  - drivers/char/agp/via-agp.c:agp_via_cleanup
  - drivers/ata/ata_piix.c:piix_exit
  - drivers/ata/pata_sis.c:sis_pci_driver_exit
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_exit
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
```
**Symbols:**

```
ffffffff81928620-ffffffff819286b0: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81970e10)
Location: drivers/pci/pci-driver.c:1469
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit
  - drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_mid.c:mid8250_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_cleanup
  - drivers/char/agp/via-agp.c:agp_via_cleanup
  - drivers/ata/ata_piix.c:piix_exit
  - drivers/ata/pata_sis.c:sis_pci_driver_exit
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_exit
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
```
**Symbols:**

```
ffffffff81970e10-ffffffff81970ea0: pci_unregister_driver (STB_GLOBAL)
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
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffff8000106ebf40)
Location: drivers/pci/pci-driver.c:1463
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/xhci-pci.c:xhci_pci_exit
```
**Symbols:**

```
ffff8000106ebf40-ffff8000106ec020: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c0885928)
Location: drivers/pci/pci-driver.c:1463
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/mfd/sm501.c:sm501_base_exit
  - drivers/usb/dwc2/pci.c:dwc2_pci_driver_exit
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/xhci-pci.c:xhci_pci_exit
```
**Symbols:**

```
c0885928-c08859b0: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c000000000865c40)
Location: drivers/pci/pci-driver.c:1463
Inline: False
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/video/fbdev/gxt4500.c:gxt4500_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_cleanup
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/xhci-pci.c:xhci_pci_exit
```
**Symbols:**

```
c000000000865c40-c000000000865d90: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffe0004c10e6)
Location: drivers/pci/pci-driver.c:1463
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/xhci-pci.c:xhci_pci_exit
```
**Symbols:**

```
ffffffe0004c10e6-ffffffe0004c11aa: pci_unregister_driver (STB_GLOBAL)
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
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157bb20)
Location: drivers/pci/pci-driver.c:1463
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_cleanup
  - drivers/char/agp/via-agp.c:agp_via_cleanup
  - drivers/nvme/host/pci.c:nvme_exit
  - drivers/ata/ata_piix.c:piix_exit
  - drivers/ata/pata_sis.c:sis_pci_driver_exit
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_exit
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/xhci-pci.c:xhci_pci_exit
```
**Symbols:**

```
ffffffff8157bb20-ffffffff8157bbac: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8156a8f0)
Location: drivers/pci/pci-driver.c:1463
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_cleanup
  - drivers/char/agp/via-agp.c:agp_via_cleanup
  - drivers/nvme/host/pci.c:nvme_exit
  - drivers/ata/ata_piix.c:piix_exit
  - drivers/ata/pata_sis.c:sis_pci_driver_exit
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_exit
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_cleanup
  - drivers/usb/host/xhci-pci.c:xhci_pci_exit
```
**Symbols:**

```
ffffffff8156a8f0-ffffffff8156a97c: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157b9e0)
Location: drivers/pci/pci-driver.c:1463
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit
  - drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_cleanup
  - drivers/char/agp/via-agp.c:agp_via_cleanup
  - drivers/ata/ata_piix.c:piix_exit
  - drivers/ata/pata_sis.c:sis_pci_driver_exit
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_exit
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_cleanup
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/xhci-pci.c:xhci_pci_exit
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_driver_exit
```
**Symbols:**

```
ffffffff8157b9e0-ffffffff8157ba6c: pci_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_unregister_driver(struct pci_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81594760)
Location: drivers/pci/pci-driver.c:1463
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_exit
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_driver_pci_exit
  - drivers/pci/hotplug/shpchp_core.c:shpcd_cleanup
  - drivers/video/fbdev/imsttfb.c:imsttfb_exit
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_exit
  - drivers/virtio/virtio_pci_common.c:virtio_pci_driver_exit
  - drivers/tty/serial/8250/8250_pci.c:serial_pci_driver_exit
  - drivers/char/agp/amd64-agp.c:agp_amd64_cleanup
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/intel-agp.c:agp_intel_cleanup
  - drivers/char/agp/via-agp.c:agp_via_cleanup
  - drivers/ata/ata_piix.c:piix_exit
  - drivers/ata/pata_sis.c:sis_pci_driver_exit
  - drivers/ata/ata_generic.c:ata_generic_pci_driver_exit
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_cleanup
  - drivers/usb/host/ehci-pci.c:ehci_pci_cleanup
  - drivers/usb/host/ohci-pci.c:ohci_pci_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/xhci-pci.c:xhci_pci_exit
```
**Symbols:**

```
ffffffff81594760-ffffffff815947ea: pci_unregister_driver (STB_GLOBAL)
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
