# Function: <code>outw</code>

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
In arch/x86/xen/platform-pci-unplug.c (ffffffff81024569)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff814027c2)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/pci-sysfs.c (ffffffff8143af9a)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_resource_io
```
```
In drivers/pci/quirks.c (ffffffff8144349a)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (ffffffff8145deb4)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
```
```
In drivers/acpi/osl.c (ffffffff81479ae5)
Location: arch/x86/include/asm/io.h:317
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81630408)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8164468e)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
```
In arch/x86/pci/direct.c (ffffffff816f6ab0)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf1_write
  - arch/x86/pci/direct.c:pci_conf2_write
```
```
In arch/x86/pci/early.c (ffffffff816fa9c3)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff81023829)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff8144a54b)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/pci-sysfs.c (ffffffff8148843e)
Location: arch/x86/include/asm/io.h:317
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8148f33a)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (ffffffff814ac667)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
```
```
In drivers/acpi/osl.c (ffffffff814c80aa)
Location: arch/x86/include/asm/io.h:317
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81691068)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816aa4ed)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In arch/x86/pci/direct.c (ffffffff8175b89e)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/early.c (ffffffff8175f845)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff81023f59)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff81468f0b)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/pci-sysfs.c (ffffffff814a9c1e)
Location: arch/x86/include/asm/io.h:317
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff814b0b8a)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (ffffffff814ce727)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/acpi/osl.c (ffffffff814e9fba)
Location: arch/x86/include/asm/io.h:317
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816bf118)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d862d)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In arch/x86/pci/direct.c (ffffffff81787e0e)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/early.c (ffffffff8178bd85)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101b76a)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff8146e5eb)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/pci-sysfs.c (ffffffff814b3fdf)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
```
```
In drivers/pci/quirks.c (ffffffff814bb1c3)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (ffffffff814da487)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/acpi/osl.c (ffffffff814f5c91)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816d39c1)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816ecb1d)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In arch/x86/pci/direct.c (ffffffff817a6ec7)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/early.c (ffffffff817aad45)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101c44a)
Location: arch/x86/include/asm/io.h:349
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff8149a91f)
Location: arch/x86/include/asm/io.h:349
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/pci-sysfs.c (ffffffff814f37eb)
Location: arch/x86/include/asm/io.h:349
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
```
```
In drivers/pci/quirks.c (ffffffff814fb633)
Location: arch/x86/include/asm/io.h:349
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (ffffffff8151a617)
Location: arch/x86/include/asm/io.h:349
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/acpi/osl.c (ffffffff815365d1)
Location: arch/x86/include/asm/io.h:349
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817400b1)
Location: arch/x86/include/asm/io.h:349
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81759313)
Location: arch/x86/include/asm/io.h:349
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In arch/x86/pci/direct.c (ffffffff8181e127)
Location: arch/x86/include/asm/io.h:349
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/early.c (ffffffff81822235)
Location: arch/x86/include/asm/io.h:349
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101ce4d)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff814cfbd8)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/pci-sysfs.c (ffffffff81523a36)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
```
```
In drivers/pci/quirks.c (ffffffff8152c589)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (ffffffff81550209)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/acpi/osl.c (ffffffff8156c22c)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81780c21)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817993d4)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In arch/x86/pci/direct.c (ffffffff81868516)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/early.c (ffffffff8186c503)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101cad6)
Location: arch/x86/include/asm/io.h:343
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff814e44e8)
Location: arch/x86/include/asm/io.h:343
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/pci-sysfs.c (ffffffff81539896)
Location: arch/x86/include/asm/io.h:343
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
```
```
In drivers/pci/quirks.c (ffffffff815433d9)
Location: arch/x86/include/asm/io.h:343
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (ffffffff81567b29)
Location: arch/x86/include/asm/io.h:343
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/acpi/osl.c (ffffffff81583e5c)
Location: arch/x86/include/asm/io.h:343
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817a7441)
Location: arch/x86/include/asm/io.h:343
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817bfd44)
Location: arch/x86/include/asm/io.h:343
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In arch/x86/pci/direct.c (ffffffff81888596)
Location: arch/x86/include/asm/io.h:343
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/early.c (ffffffff8188c5e3)
Location: arch/x86/include/asm/io.h:343
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101e616)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff81510d73)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/pci-sysfs.c (ffffffff815691b6)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
```
```
In drivers/pci/quirks.c (ffffffff8157692c)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (ffffffff815980b1)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/acpi/osl.c (ffffffff815b4a4a)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817e6651)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817ff5f8)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In arch/x86/pci/direct.c (ffffffff818d2d56)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/early.c (ffffffff818d6f23)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101ef96)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff815317e3)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/pci-sysfs.c (ffffffff8158a1ed)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8159801a)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (ffffffff815b9451)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/acpi/osl.c (ffffffff815d5cca)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81817511)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81830458)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In arch/x86/pci/direct.c (ffffffff81905106)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/early.c (ffffffff819092a3)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff810215a6)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff81595c6e)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/pci-sysfs.c (ffffffff816312de)
Location: arch/x86/include/asm/io.h:335
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8164694f)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (ffffffff81663633)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/acpi/osl.c (ffffffff8167f85a)
Location: arch/x86/include/asm/io.h:335
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818e8591)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81901338)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In arch/x86/pci/direct.c (ffffffff81bb56c6)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/early.c (ffffffff81bb9b83)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff81021d66)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff815b16fe)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/pci-sysfs.c (ffffffff8165697e)
Location: arch/x86/include/asm/io.h:335
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81bfa520)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (ffffffff816842c3)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/acpi/osl.c (ffffffff8169e31a)
Location: arch/x86/include/asm/io.h:335
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818f1571)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81909c08)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In arch/x86/pci/direct.c (ffffffff81bca8a6)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/early.c (ffffffff81bce483)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff810240f6)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff815bc50e)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/pci-sysfs.c (ffffffff8163959e)
Location: arch/x86/include/asm/io.h:335
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81bec37d)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (ffffffff81666f23)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/acpi/osl.c (ffffffff8168105a)
Location: arch/x86/include/asm/io.h:335
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818d4d76)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818ee328)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In arch/x86/pci/direct.c (ffffffff81bbe1f5)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/early.c (ffffffff81bc1e31)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff810284ba)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff8162335e)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a9a8d)
Location: arch/x86/include/asm/io.h:335
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81ce6f48)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (ffffffff816da383)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/acpi/osl.c (ffffffff816f613a)
Location: arch/x86/include/asm/io.h:335
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8196f496)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8198aaf8)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In arch/x86/pci/direct.c (ffffffff81c8e135)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/early.c (ffffffff81c92441)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_16
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (c0000000007e5364)
Location: arch/powerpc/include/asm/io-defs.h:27
Inline: True
```
```
In drivers/pci/pci-sysfs.c (c00000000086b5f8)
Location: arch/powerpc/include/asm/io-defs.h:27
Inline: True
```
```
In drivers/pci/quirks.c (c0000000008791d8)
Location: arch/powerpc/include/asm/io-defs.h:27
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (c00000000089c0fc)
Location: arch/powerpc/include/asm/io-defs.h:27
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/usb/host/pci-quirks.c (c000000000b18a98)
Location: arch/powerpc/include/asm/io-defs.h:27
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b3e514)
Location: arch/powerpc/include/asm/io-defs.h:27
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:start_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:configure_hc
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101f0f6)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff81529dc3)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157e07d)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8158beaa)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (ffffffff815ad5a1)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/acpi/osl.c (ffffffff815c9a2a)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817cf8f1)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817e8838)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In arch/x86/pci/direct.c (ffffffff818a4536)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/early.c (ffffffff818a8663)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_16
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
In lib/iomap.c (ffffffff8151a0a3)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156ce4d)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8157a9ea)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (ffffffff8159c741)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/acpi/osl.c (ffffffff815b2aba)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817ad821)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In arch/x86/pci/direct.c (ffffffff8185fca6)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/early.c (ffffffff81863073)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101ef56)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff81525e53)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157df3d)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8158bd6a)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (ffffffff815adb31)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/acpi/osl.c (ffffffff815c9faa)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8180c391)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818252d8)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In arch/x86/pci/direct.c (ffffffff818f5b26)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/early.c (ffffffff818f9cc3)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101f1a6)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff8153f7d3)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/pci-sysfs.c (ffffffff815983ed)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff815a621a)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (ffffffff815c75e1)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/acpi/osl.c (ffffffff815e3e0a)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818264a1)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183ad18)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_resume
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:finish_reset
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
```
```
In arch/x86/pci/direct.c (ffffffff81916c16)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/early.c (ffffffff8191ae23)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_16
```
</details>
</li>
</ul>

## Differences
