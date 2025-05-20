# Function: <code>inw</code>

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
In arch/x86/xen/platform-pci-unplug.c (ffffffff81024544)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff81402702)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - lib/iomap.c:ioread16
  - lib/iomap.c:ioread16be
```
```
In drivers/pci/pci-sysfs.c (ffffffff8143afc5)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_resource_io
```
```
In drivers/pci/quirks.c (ffffffff81443481)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/acpi/osl.c (ffffffff81479a9c)
Location: arch/x86/include/asm/io.h:317
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8163041e)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8164471f)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
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
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
```
```
In arch/x86/pci/direct.c (ffffffff816f69c0)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf1_read
  - arch/x86/pci/direct.c:pci_conf2_read
```
```
In arch/x86/pci/early.c (ffffffff816fa8e3)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff81023804)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff8144a4f5)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/pci-sysfs.c (ffffffff8148846c)
Location: arch/x86/include/asm/io.h:317
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8148f321)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/acpi/osl.c (ffffffff814c8061)
Location: arch/x86/include/asm/io.h:317
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81691132)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816a622c)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In arch/x86/pci/direct.c (ffffffff8175ba11)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8175f76e)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff81023f34)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff81468eb5)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/pci-sysfs.c (ffffffff814a9c4c)
Location: arch/x86/include/asm/io.h:317
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff814b0b71)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/acpi/osl.c (ffffffff814e9f71)
Location: arch/x86/include/asm/io.h:317
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816bf1e2)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d432c)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In arch/x86/pci/direct.c (ffffffff81787f81)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8178bcae)
Location: arch/x86/include/asm/io.h:317
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101b745)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff8146e595)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/pci-sysfs.c (ffffffff814b41d1)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/quirks.c (ffffffff814bb1aa)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/acpi/osl.c (ffffffff814f5c54)
Location: arch/x86/include/asm/io.h:341
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816d3a8b)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816e8a1c)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In arch/x86/pci/direct.c (ffffffff817a7017)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff817aac6e)
Location: arch/x86/include/asm/io.h:341
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101c425)
Location: arch/x86/include/asm/io.h:349
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff8149a8c9)
Location: arch/x86/include/asm/io.h:349
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/pci-sysfs.c (ffffffff814f39e1)
Location: arch/x86/include/asm/io.h:349
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/quirks.c (ffffffff814fb61a)
Location: arch/x86/include/asm/io.h:349
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/acpi/osl.c (ffffffff81536594)
Location: arch/x86/include/asm/io.h:349
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8174017b)
Location: arch/x86/include/asm/io.h:349
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817551fc)
Location: arch/x86/include/asm/io.h:349
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In arch/x86/pci/direct.c (ffffffff8181e277)
Location: arch/x86/include/asm/io.h:349
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8182215e)
Location: arch/x86/include/asm/io.h:349
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101ce1f)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff814cfb76)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/pci-sysfs.c (ffffffff81523c25)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/quirks.c (ffffffff8152c55a)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/acpi/osl.c (ffffffff8156c1ef)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81780cb3)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817957e9)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In arch/x86/pci/direct.c (ffffffff818683c8)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8186c423)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - arch/x86/pci/early.c:read_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101caa8)
Location: arch/x86/include/asm/io.h:343
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff814e4486)
Location: arch/x86/include/asm/io.h:343
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/pci-sysfs.c (ffffffff81539a85)
Location: arch/x86/include/asm/io.h:343
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/quirks.c (ffffffff815433aa)
Location: arch/x86/include/asm/io.h:343
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/acpi/osl.c (ffffffff81583e1f)
Location: arch/x86/include/asm/io.h:343
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817a74d3)
Location: arch/x86/include/asm/io.h:343
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817bbcb9)
Location: arch/x86/include/asm/io.h:343
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In arch/x86/pci/direct.c (ffffffff81888448)
Location: arch/x86/include/asm/io.h:343
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8188c637)
Location: arch/x86/include/asm/io.h:343
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101e5e8)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff81510d12)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/pci-sysfs.c (ffffffff815693a5)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/quirks.c (ffffffff815729fa)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/acpi/osl.c (ffffffff815b4a0b)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817e66d5)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817faed9)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In arch/x86/pci/direct.c (ffffffff818d2e88)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff818d6f78)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101ef68)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff81531782)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/pci-sysfs.c (ffffffff8158a3d5)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/quirks.c (ffffffff8159404a)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/acpi/osl.c (ffffffff815d5c8b)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81817595)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8182bd29)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In arch/x86/pci/direct.c (ffffffff81905238)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff819092f8)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff81021578)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff81595912)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/pci-sysfs.c (ffffffff81631558)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/quirks.c (ffffffff816425ca)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/acpi/osl.c (ffffffff8167f81b)
Location: arch/x86/include/asm/io.h:335
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818e8615)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818ff8c4)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_shutdown
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In arch/x86/pci/direct.c (ffffffff81bb57f9)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff81bb9bd6)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff81021d38)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff815b13a2)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/pci-sysfs.c (ffffffff81656bf8)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/quirks.c (ffffffff81668a2a)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/acpi/osl.c (ffffffff8169e2db)
Location: arch/x86/include/asm/io.h:335
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818f15f5)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81908194)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_shutdown
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_submit_isochronous
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In arch/x86/pci/direct.c (ffffffff81bca9d9)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff81bce4d6)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff810240c8)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff815bc1b2)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/pci-sysfs.c (ffffffff81639668)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/quirks.c (ffffffff8164aeda)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/acpi/osl.c (ffffffff8168101b)
Location: arch/x86/include/asm/io.h:335
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818d4df5)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818eb784)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_shutdown
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In arch/x86/pci/direct.c (ffffffff81bbe318)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff81bc1e88)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8102849e)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff81623002)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a9c10)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/quirks.c (ffffffff816bc8aa)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/acpi/osl.c (ffffffff816f5fab)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_port
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8196f515)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81987e94)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_shutdown
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
```
```
In arch/x86/pci/direct.c (ffffffff81c8e258)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff81c92498)
Location: arch/x86/include/asm/io.h:335
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
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
In lib/iomap.c (c0000000007e5408)
Location: arch/powerpc/include/asm/io-defs.h:24
Inline: True
```
```
In drivers/pci/pci-sysfs.c (c00000000086b7f8)
Location: arch/powerpc/include/asm/io-defs.h:24
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/quirks.c (c000000000879114)
Location: arch/powerpc/include/asm/io-defs.h:24
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/usb/host/pci-quirks.c (c000000000b18d64)
Location: arch/powerpc/include/asm/io-defs.h:24
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b39fd0)
Location: arch/powerpc/include/asm/io-defs.h:24
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
  - drivers/usb/host/uhci-hcd.c:uhci_show_status
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101f0c8)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff81529d62)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157e265)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/quirks.c (ffffffff81587eda)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/acpi/osl.c (ffffffff815c99eb)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817cf975)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817e4109)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In arch/x86/pci/direct.c (ffffffff818a4668)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff818a86b8)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
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
In lib/iomap.c (ffffffff8151a042)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156d035)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/quirks.c (ffffffff81576c8a)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/acpi/osl.c (ffffffff815b2a7b)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817ad8a5)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In arch/x86/pci/direct.c (ffffffff8185fdd8)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff818630c8)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101ef28)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff81525df2)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157e125)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/quirks.c (ffffffff81587d9a)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/acpi/osl.c (ffffffff815c9f6b)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8180c415)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81820ba9)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In arch/x86/pci/direct.c (ffffffff818f5c58)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff818f9d18)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff8101f178)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff8153f772)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
  - lib/iomap.c:ioread16
```
```
In drivers/pci/pci-sysfs.c (ffffffff815985d5)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
```
In drivers/pci/quirks.c (ffffffff815a224a)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/acpi/osl.c (ffffffff815e3dcb)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81826525)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_check_and_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183b009)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_pci_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_get_frame_number
  - drivers/usb/host/uhci-hcd.c:uhci_irq
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:wakeup_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:suspend_rh
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_control
  - drivers/usb/host/uhci-hcd.c:uhci_hub_status_data
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_check_ports
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:uhci_finish_suspend
  - drivers/usb/host/uhci-hcd.c:any_ports_active
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
  - drivers/usb/host/uhci-hcd.c:uhci_sprint_schedule
```
```
In arch/x86/pci/direct.c (ffffffff81916d48)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_read
  - arch/x86/pci/direct.c:pci_conf1_read
```
```
In arch/x86/pci/early.c (ffffffff8191ae78)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - arch/x86/pci/early.c:pci_early_find_cap
```
</details>
</li>
</ul>

## Differences
