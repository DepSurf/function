# Function: <code>kobject_uevent_env</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff813ecad0)
Location: lib/kobject_uevent.c:164
Inline: False
Direct callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:disk_check_events
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_move
  - lib/kobject_uevent.c:kobject_uevent
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:dock_event
  - drivers/block/virtio_blk.c:virtblk_config_changed_work
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_update_state
```
**Symbols:**

```
ffffffff813ecad0-ffffffff813ed10b: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81432e80)
Location: lib/kobject_uevent.c:164
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:set_disk_ro
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:dock_event
  - drivers/block/virtio_blk.c:virtblk_config_changed_work
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_update_state
```
**Symbols:**

```
ffffffff81432e80-ffffffff81433512: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff8144f0f0)
Location: lib/kobject_uevent.c:164
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:set_disk_ro
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:dock_event
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_sync
```
**Symbols:**

```
ffffffff8144f0f0-ffffffff8144f782: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff818ef330)
Location: lib/kobject_uevent.c:305
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:set_disk_ro
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:dock_event
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_sync
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff818ef330-ffffffff818ef93f: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81975610)
Location: lib/kobject_uevent.c:384
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:set_disk_ro
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:dock_event
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_sync
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81975610-ffffffff81975d7a: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff819d1dc0)
Location: lib/kobject_uevent.c:454
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:set_disk_ro
  - drivers/pci/pci-driver.c:pci_uevent_ers
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:dock_event
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_sync
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff819d1dc0-ffffffff819d2565: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a0b160)
Location: lib/kobject_uevent.c:456
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:set_disk_ro
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/pci-driver.c:pci_uevent_ers
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:dock_event
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_sync
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81a0b160-ffffffff81a0b912: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a7ab40)
Location: lib/kobject_uevent.c:456
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:set_disk_ro
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/pci-driver.c:pci_uevent_ers
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:dock_event
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hcd.c:hcd_died_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_sync
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81a7ab40-ffffffff81a7b2f8: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81ab1ea0)
Location: lib/kobject_uevent.c:456
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:set_disk_ro
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/pci-driver.c:pci_uevent_ers
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:dock_event
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hcd.c:hcd_died_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_sync
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81ab1ea0-ffffffff81ab2658: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff815ec5f0)
Location: lib/kobject_uevent.c:456
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:set_disk_ro
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/pci-driver.c:pci_uevent_ers
  - drivers/video/backlight/backlight.c:backlight_device_set_brightness
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:dock_event
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/ata/libata-acpi.c:ata_acpi_dev_uevent
  - drivers/ata/libata-acpi.c:ata_acpi_ap_uevent
  - drivers/usb/core/hub.c:port_over_current_notify
  - drivers/usb/core/hcd.c:hcd_died_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff815ec5f0-ffffffff815eca9b: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81610dd0)
Location: lib/kobject_uevent.c:456
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:set_disk_ro
  - block/genhd.c:set_capacity_and_notify
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/pci-driver.c:pci_uevent_ers
  - drivers/video/backlight/backlight.c:backlight_device_set_brightness
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:dock_event
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/ata/libata-acpi.c:ata_acpi_dev_uevent
  - drivers/ata/libata-acpi.c:ata_acpi_ap_uevent
  - drivers/usb/core/hub.c:port_over_current_notify
  - drivers/usb/core/hcd.c:hcd_died_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81610dd0-ffffffff8161127b: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject_uevent.c (0)
Location: lib/kobject_uevent.c:457
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:set_disk_ro
  - block/genhd.c:set_capacity_and_notify
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/pci-driver.c:pci_uevent_ers
  - drivers/video/backlight/backlight.c:backlight_device_set_brightness
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:dock_event
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/ata/libata-acpi.c:ata_acpi_dev_uevent
  - drivers/ata/libata-acpi.c:ata_acpi_ap_uevent
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hcd.c:hcd_died_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81be6ae4-ffffffff81be6afe: kobject_uevent_env.cold (STB_LOCAL)
ffffffff815f4440-ffffffff815f493c: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject_uevent.c (0)
Location: lib/kobject_uevent.c:457
Inline: False
Direct callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:set_capacity_and_notify
  - block/disk-events.c:disk_event_uevent
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/pci-driver.c:pci_uevent_ers
  - drivers/video/backlight/backlight.c:backlight_device_set_brightness
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:dock_event
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/ata/libata-acpi.c:ata_acpi_dev_uevent
  - drivers/ata/libata-acpi.c:ata_acpi_ap_uevent
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hcd.c:hcd_died_work
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81cdf3d1-ffffffff81cdf3eb: kobject_uevent_env.cold (STB_LOCAL)
ffffffff816617b0-ffffffff81661d06: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff8177b580)
Location: lib/kobject_uevent.c:457
Inline: False
Direct callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:set_capacity_and_notify
  - block/disk-events.c:disk_event_uevent
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/pci-driver.c:pci_uevent_ers
  - drivers/video/backlight/backlight.c:backlight_device_set_brightness
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:dock_event
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/ata/libata-acpi.c:ata_acpi_dev_uevent
  - drivers/ata/libata-acpi.c:ata_acpi_ap_uevent
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hcd.c:hcd_died_work
  - drivers/hwmon/hwmon.c:hwmon_notify_event
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_sync
```
**Symbols:**

```
ffffffff8177b580-ffffffff8177ba09: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff820247c0)
Location: lib/kobject_uevent.c:457
Inline: False
Direct callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:set_capacity_and_notify
  - block/disk-events.c:disk_event_uevent
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/pci-driver.c:pci_uevent_ers
  - drivers/video/backlight/backlight.c:backlight_device_set_brightness
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:dock_event
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/ata/libata-acpi.c:ata_acpi_dev_uevent
  - drivers/ata/libata-acpi.c:ata_acpi_ap_uevent
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hcd.c:hcd_died_work
  - drivers/hwmon/hwmon.c:hwmon_notify_event
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_sync
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff820247c0-ffffffff82024c4c: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff820a48d0)
Location: lib/kobject_uevent.c:457
Inline: False
Direct callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:set_capacity_and_notify
  - block/disk-events.c:disk_event_uevent
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/pci-driver.c:pci_uevent_ers
  - drivers/video/backlight/backlight.c:backlight_device_set_brightness
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:dock_event
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/ata/libata-acpi.c:ata_acpi_dev_uevent
  - drivers/ata/libata-acpi.c:ata_acpi_ap_uevent
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hcd.c:hcd_died_work
  - drivers/hwmon/hwmon.c:hwmon_notify_event
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_sync
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff820a48d0-ffffffff820a4d5e: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff8217c9d0)
Location: lib/kobject_uevent.c:457
Inline: False
Direct callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:set_capacity_and_notify
  - block/disk-events.c:disk_event_uevent
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pwm/sysfs.c:pwm_export_child
  - drivers/pci/pci-driver.c:pci_uevent_ers
  - drivers/video/backlight/backlight.c:backlight_device_set_brightness
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:dock_event
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/ata/libata-acpi.c:ata_acpi_dev_uevent
  - drivers/ata/libata-acpi.c:ata_acpi_ap_uevent
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_property_event
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_hotplug_event
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_hotplug_event
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_lease_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hcd.c:hcd_died_work
  - drivers/hwmon/hwmon.c:hwmon_notify_event
  - drivers/thermal/gov_user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_sync
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff8217c9d0-ffffffff8217ce8d: kobject_uevent_env (STB_GLOBAL)
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
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffff800010d8c068)
Location: lib/kobject_uevent.c:456
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:disk_check_events
  - block/genhd.c:set_disk_ro
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/pci-driver.c:pci_uevent_ers
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:dock_event
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hcd.c:hcd_died_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_sync
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffff800010d8c068-ffff800010d8c7d8: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (c0e863f0)
Location: lib/kobject_uevent.c:456
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:set_disk_ro
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/pci-driver.c:pci_uevent_ers
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hcd.c:hcd_died_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
c0e863f0-c0e86bb8: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (c000000000ecdec0)
Location: lib/kobject_uevent.c:456
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:set_disk_ro
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/pci-driver.c:pci_uevent_ers
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hcd.c:hcd_died_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
c000000000ecdec0-c000000000ece8f0: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffe0008b52d2)
Location: lib/kobject_uevent.c:456
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:set_disk_ro
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/pci-driver.c:pci_uevent_ers
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hcd.c:hcd_died_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffe0008b52d2-ffffffe0008b5980: kobject_uevent_env (STB_GLOBAL)
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
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a50cf0)
Location: lib/kobject_uevent.c:456
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:set_disk_ro
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/pci-driver.c:pci_uevent_ers
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/nvme/host/core.c:nvme_async_event_work
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hcd.c:hcd_died_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_sync
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81a50cf0-ffffffff81a514a8: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81a0ddf0)
Location: lib/kobject_uevent.c:456
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:set_disk_ro
  - drivers/pci/pci-driver.c:pci_uevent_ers
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/nvme/host/core.c:nvme_async_event_work
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hcd.c:hcd_died_work
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81a0ddf0-ffffffff81a0e5a8: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81abd0e0)
Location: lib/kobject_uevent.c:456
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:set_disk_ro
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/pci-driver.c:pci_uevent_ers
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:dock_event
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hcd.c:hcd_died_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_sync
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81abd0e0-ffffffff81abd898: kobject_uevent_env (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kobject_uevent_env(struct kobject *kobj, enum kobject_action action, char **envp_ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81ac9560)
Location: lib/kobject_uevent.c:456
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:set_disk_ro
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/pci/pci-driver.c:pci_uevent_ers
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/acpi/scan.c:acpi_scan_is_offline
  - drivers/acpi/dock.c:dock_event
  - drivers/acpi/dock.c:dock_event
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hcd.c:hcd_died_work
  - drivers/usb/phy/phy.c:usb_phy_notify_charger_work
  - drivers/thermal/user_space.c:notify_user_space
  - drivers/md/dm-uevent.c:dm_send_uevents
  - drivers/md/dm.c:dm_kobject_uevent
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/extcon/extcon.c:extcon_sync
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81ac9560-ffffffff81ac9d18: kobject_uevent_env (STB_GLOBAL)
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
