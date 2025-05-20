# Function: <code>__outw</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/platform-pci-unplug.c (ffffffff8102cb26)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff816f33ba)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/pci-sysfs.c (ffffffff817cc523)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81eadf3c)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (ffffffff81803198)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/acpi/osl.c (ffffffff81822f93)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81ac9976)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae4994)
Location: arch/x86/include/asm/shared/io.h:23
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
In arch/x86/pci/direct.c (ffffffff81e3d117)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/early.c (ffffffff81e41b23)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff81033ca6)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff817e530a)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/pci-sysfs.c (ffffffff818ea743)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff81904f7b)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (ffffffff81931918)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/acpi/osl.c (ffffffff81954063)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81c53df6)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c70554)
Location: arch/x86/include/asm/shared/io.h:23
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
In arch/x86/pci/direct.c (ffffffff82016437)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/early.c (ffffffff8201c203)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff81033c36)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff8182534a)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192dcb5)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff819485bb)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (ffffffff81975d88)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/acpi/osl.c (ffffffff8199a473)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81cbb2e6)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd7b45)
Location: arch/x86/include/asm/shared/io.h:23
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
In arch/x86/pci/direct.c (ffffffff820967d3)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/early.c (ffffffff8209c8a3)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_16
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
In arch/x86/xen/platform-pci-unplug.c (ffffffff81039f36)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
  - arch/x86/xen/platform-pci-unplug.c:xen_unplug_emulated_devices
```
```
In lib/iomap.c (ffffffff81876d5a)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
  - lib/iomap.c:iowrite16
```
```
In drivers/pci/pci-sysfs.c (ffffffff81976635)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
```
```
In drivers/pci/quirks.c (ffffffff8199187b)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_tigerpoint_bm_sts
```
```
In drivers/video/console/vgacon.c (ffffffff819bfdf8)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_scroll
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_deinit
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
  - drivers/video/console/vgacon.c:vgacon_scrolldelta
```
```
In drivers/acpi/osl.c (ffffffff819e28f3)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81d70316)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
  - drivers/usb/host/pci-quirks.c:uhci_reset_hc
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8cb55)
Location: arch/x86/include/asm/shared/io.h:23
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
In arch/x86/pci/direct.c (ffffffff8216dce3)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - arch/x86/pci/direct.c:pci_conf2_write
  - arch/x86/pci/direct.c:pci_conf1_write
```
```
In arch/x86/pci/early.c (ffffffff82174083)
Location: arch/x86/include/asm/shared/io.h:23
Inline: True
Inline callers:
  - arch/x86/pci/early.c:write_pci_config_16
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
