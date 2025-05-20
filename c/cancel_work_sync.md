# Function: <code>cancel_work_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109b280)
Location: kernel/workqueue.c:2849
Inline: False
Direct callers:
  - kernel/cgroup.c:css_free_work_fn
  - block/blk-mq.c:blk_mq_cancel_requeue_work
  - block/blk-throttle.c:blk_throtl_exit
  - block/cfq-iosched.c:cfq_exit_queue
  - block/cfq-iosched.c:cfq_exit_queue
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_stop_interrupts
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/input/serio/serio.c:serio_exit
  - drivers/power/power_supply_core.c:power_supply_unregister
  - drivers/power/charger-manager.c:charger_manager_remove
  - drivers/power/charger-manager.c:charger_extcon_notifier
  - drivers/power/charger-manager.c:cm_suspend_prepare
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/ipv4/inet_fragment.c:inet_frags_fini
```
**Symbols:**

```
ffffffff8109b280-ffffffff8109b292: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109e880)
Location: kernel/workqueue.c:2949
Inline: False
Direct callers:
  - kernel/cgroup.c:css_free_work_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - crypto/drbg.c:drbg_uninstantiate
  - block/blk-mq.c:blk_mq_cancel_requeue_work
  - block/blk-throttle.c:blk_throtl_exit
  - block/cfq-iosched.c:cfq_exit_queue
  - block/cfq-iosched.c:cfq_exit_queue
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/net/phy/phy.c:phy_stop_interrupts
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/input/serio/serio.c:serio_exit
  - drivers/power/power_supply_core.c:power_supply_unregister
  - drivers/power/charger-manager.c:cm_suspend_prepare
  - drivers/power/charger-manager.c:charger_manager_remove
  - drivers/power/charger-manager.c:charger_extcon_notifier
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/ipv4/inet_fragment.c:inet_frags_fini
```
**Symbols:**

```
ffffffff8109e880-ffffffff8109e892: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a3460)
Location: kernel/workqueue.c:2963
Inline: False
Direct callers:
  - kernel/cgroup.c:css_free_work_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - crypto/drbg.c:drbg_uninstantiate
  - block/blk-core.c:blk_sync_queue
  - block/blk-throttle.c:blk_throtl_exit
  - block/cfq-iosched.c:cfq_exit_queue
  - block/cfq-iosched.c:cfq_exit_queue
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/input/serio/serio.c:serio_exit
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/ipv4/inet_fragment.c:inet_frags_fini
```
**Symbols:**

```
ffffffff810a3460-ffffffff810a3472: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a0770)
Location: kernel/workqueue.c:2962
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - crypto/drbg.c:drbg_uninstantiate
  - block/blk-throttle.c:blk_throtl_exit
  - block/cfq-iosched.c:cfq_exit_queue
  - block/cfq-iosched.c:cfq_exit_queue
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - drivers/video/console/fbcon.c:fbcon_deinit
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/input/serio/serio.c:serio_exit
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/rfkill/core.c:rfkill_exit
```
**Symbols:**

```
ffffffff810a0770-ffffffff810a0782: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a6d10)
Location: kernel/workqueue.c:2976
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_work_fn
  - kernel/bpf/sockmap.c:smap_gc_work
  - mm/memcontrol.c:mem_cgroup_css_free
  - crypto/drbg.c:drbg_uninstantiate
  - block/blk-throttle.c:blk_throtl_exit
  - block/cfq-iosched.c:cfq_exit_queue
  - block/cfq-iosched.c:cfq_exit_queue
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/input/serio/serio.c:serio_exit
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/strparser/strparser.c:strp_done
  - net/rfkill/core.c:rfkill_exit
```
**Symbols:**

```
ffffffff810a6d10-ffffffff810a6d22: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ad980)
Location: kernel/workqueue.c:3038
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/bpf/sockmap.c:smap_gc_work
  - mm/memcontrol.c:mem_cgroup_css_free
  - crypto/drbg.c:drbg_uninstantiate
  - block/blk-throttle.c:blk_throtl_exit
  - block/cfq-iosched.c:cfq_exit_queue
  - block/cfq-iosched.c:cfq_exit_queue
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/input/serio/serio.c:serio_exit
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/strparser/strparser.c:strp_done
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffff810ad980-ffffffff810ad992: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b6c70)
Location: kernel/workqueue.c:3061
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - crypto/drbg.c:drbg_uninstantiate
  - block/blk-throttle.c:blk_throtl_exit
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/input/serio/serio.c:serio_exit
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/strparser/strparser.c:strp_done
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffff810b6c70-ffffffff810b6c82: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bd0d0)
Location: kernel/workqueue.c:3161
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - crypto/drbg.c:drbg_uninstantiate
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-throttle.c:blk_throtl_exit
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/input/serio/serio.c:serio_exit
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/strparser/strparser.c:strp_done
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffff810bd0d0-ffffffff810bd0e2: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2d50)
Location: kernel/workqueue.c:3170
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - crypto/drbg.c:drbg_uninstantiate
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-throttle.c:blk_throtl_exit
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/input/serio/serio.c:serio_exit
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/strparser/strparser.c:strp_done
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffff810c2d50-ffffffff810c2d62: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ca900)
Location: kernel/workqueue.c:3167
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memory-failure.c:memory_failure_queue_kick
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-throttle.c:blk_throtl_exit
  - lib/rhashtable.c:rhashtable_destroy
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/video/fbdev/core/fbcon.c:fbcon_exit
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/input/serio/serio.c:serio_exit
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/xfrm/espintcp.c:espintcp_close
  - net/strparser/strparser.c:strp_done
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/pm.c:mptcp_pm_close
```
**Symbols:**

```
ffffffff810ca900-ffffffff810ca912: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c5a30)
Location: kernel/workqueue.c:3173
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memory-failure.c:memory_failure_queue_kick
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-throttle.c:blk_throtl_exit
  - lib/rhashtable.c:rhashtable_destroy
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/video/fbdev/core/fbcon.c:fbcon_exit
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/input/serio/serio.c:serio_exit
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/xfrm/espintcp.c:espintcp_close
  - net/strparser/strparser.c:strp_done
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/mptcp/protocol.c:mptcp_close
```
**Symbols:**

```
ffffffff810c5a30-ffffffff810c5a42: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c7360)
Location: kernel/workqueue.c:3174
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memory-failure.c:memory_failure_queue_kick
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-throttle.c:blk_throtl_exit
  - lib/rhashtable.c:rhashtable_destroy
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/video/fbdev/core/fbcon.c:fbcon_exit
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/input/serio/serio.c:serio_exit
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_stop
  - net/xfrm/espintcp.c:espintcp_close
  - net/strparser/strparser.c:strp_done
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/mptcp/protocol.c:mptcp_close
```
**Symbols:**

```
ffffffff810c7360-ffffffff810c7372: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810da080)
Location: kernel/workqueue.c:3213
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memory-failure.c:memory_failure_queue_kick
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-throttle.c:blk_throtl_exit
  - lib/rhashtable.c:rhashtable_destroy
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/video/fbdev/core/fbcon.c:fbcon_exit
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/input/serio/serio.c:serio_exit
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_stop
  - net/xfrm/espintcp.c:espintcp_close
  - net/strparser/strparser.c:strp_done
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/mptcp/protocol.c:mptcp_close
```
**Symbols:**

```
ffffffff810da080-ffffffff810da092: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f3460)
Location: kernel/workqueue.c:3196
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memory-failure.c:memory_failure_queue_kick
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-throttle.c:blk_throtl_exit
  - lib/rhashtable.c:rhashtable_destroy
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/crc64-rocksoft.c:crc64_rocksoft_mod_fini
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/input/serio/serio.c:serio_exit
  - drivers/rtc/class.c:rtc_device_release
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_stop
  - net/xfrm/espintcp.c:espintcp_close
  - net/strparser/strparser.c:strp_done
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/mptcp/protocol.c:mptcp_close
```
**Symbols:**

```
ffffffff810f3460-ffffffff810f347a: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81114ae0)
Location: kernel/workqueue.c:3194
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memory-failure.c:memory_failure_queue_kick
  - block/blk-core.c:blk_sync_queue
  - block/blk-throttle.c:blk_throtl_exit
  - lib/rhashtable.c:rhashtable_destroy
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/crc64-rocksoft.c:crc64_rocksoft_mod_fini
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/input/serio/serio.c:serio_exit
  - drivers/rtc/class.c:rtc_device_release
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/sock_map.c:sock_map_close
  - net/xfrm/espintcp.c:espintcp_close
  - net/strparser/strparser.c:strp_done
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_unregister
  - net/mptcp/protocol.c:mptcp_close
```
**Symbols:**

```
ffffffff81114ae0-ffffffff81114afa: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81120ca0)
Location: kernel/workqueue.c:3510
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memory-failure.c:memory_failure_queue_kick
  - block/blk-core.c:blk_sync_queue
  - block/blk-throttle.c:blk_throtl_exit
  - lib/rhashtable.c:rhashtable_destroy
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/crc64-rocksoft.c:crc64_rocksoft_mod_fini
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/virtio_scsi.c:virtscsi_remove
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/input/serio/serio.c:serio_exit
  - drivers/rtc/class.c:rtc_device_release
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/xfrm/espintcp.c:espintcp_close
  - net/strparser/strparser.c:strp_done
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_unregister
```
**Symbols:**

```
ffffffff81120a70-ffffffff81120a8a: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112a550)
Location: kernel/workqueue.c:3531
Inline: True
Inline callers:
  - kernel/workqueue.c:put_unbound_pool
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memory-failure.c:memory_failure_queue_kick
  - block/blk-core.c:blk_sync_queue
  - block/blk-throttle.c:blk_throtl_exit
  - lib/rhashtable.c:rhashtable_destroy
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/crc64-rocksoft.c:crc64_rocksoft_mod_fini
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/pmdomain/core.c:genpd_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/virtio_scsi.c:virtscsi_remove
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_close
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/input/serio/serio.c:serio_exit
  - drivers/rtc/class.c:rtc_device_release
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/xfrm/espintcp.c:espintcp_close
  - net/strparser/strparser.c:strp_done
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_unregister
```
**Symbols:**

```
ffffffff8112a320-ffffffff8112a33a: cancel_work_sync (STB_GLOBAL)
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
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011f6f8)
Location: kernel/workqueue.c:3170
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - crypto/drbg.c:drbg_uninstantiate
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-throttle.c:blk_throtl_exit
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_powerdown
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/input/serio/serio.c:serio_exit
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/strparser/strparser.c:strp_done
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffff80001011f6f8-ffff80001011f728: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0373bac)
Location: kernel/workqueue.c:3170
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - crypto/drbg.c:drbg_uninstantiate
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-throttle.c:blk_throtl_exit
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/input/serio/serio.c:serio_exit
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/strparser/strparser.c:strp_done
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
c0373bac-c0373bcc: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c000000000169fc0)
Location: kernel/workqueue.c:3170
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - crypto/drbg.c:drbg_uninstantiate
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-throttle.c:blk_throtl_exit
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/input/serio/serio.c:serio_exit
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/strparser/strparser.c:strp_done
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
c000000000169fc0-c000000000169fd8: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d9b46)
Location: kernel/workqueue.c:3170
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - crypto/drbg.c:drbg_uninstantiate
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-throttle.c:blk_throtl_exit
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/input/serio/serio.c:serio_exit
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/strparser/strparser.c:strp_done
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffe0000d9b46-ffffffe0000d9b72: cancel_work_sync (STB_GLOBAL)
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
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bd0c0)
Location: kernel/workqueue.c:3170
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - crypto/drbg.c:drbg_uninstantiate
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-throttle.c:blk_throtl_exit
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/nvme/host/core.c:nvme_stop_ctrl
  - drivers/nvme/host/multipath.c:nvme_mpath_stop
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/input/serio/serio.c:serio_exit
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/strparser/strparser.c:strp_done
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffff810bd0c0-ffffffff810bd0d2: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ab8f0)
Location: kernel/workqueue.c:3170
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - crypto/drbg.c:drbg_uninstantiate
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-throttle.c:blk_throtl_exit
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/scsi_transport_fc.c:fc_rport_final_delete
  - drivers/nvme/host/core.c:nvme_stop_ctrl
  - drivers/nvme/host/multipath.c:nvme_mpath_stop
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/input/serio/serio.c:serio_exit
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/strparser/strparser.c:strp_done
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffff810ab8f0-ffffffff810ab902: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bc620)
Location: kernel/workqueue.c:3170
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - crypto/drbg.c:drbg_uninstantiate
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-throttle.c:blk_throtl_exit
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/scsi/virtio_scsi.c:virtscsi_remove
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/input/serio/serio.c:serio_exit
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/strparser/strparser.c:strp_done
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffff810bc620-ffffffff810bc632: cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool cancel_work_sync(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c4230)
Location: kernel/workqueue.c:3170
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - mm/memcontrol.c:mem_cgroup_css_free
  - crypto/drbg.c:drbg_uninstantiate
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-throttle.c:blk_throtl_exit
  - lib/rhashtable.c:rhashtable_free_and_destroy
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/video/fbdev/core/fbcon.c:fbcon_deinit
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/tty_buffer.c:tty_buffer_cancel_work
  - drivers/tty/sysrq.c:sysrq_disconnect
  - drivers/tty/hvc/hvc_console.c:hvc_hangup
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/base/power/runtime.c:__pm_runtime_barrier
  - drivers/base/power/domain.c:pm_genpd_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/input/serio/serio.c:serio_exit
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_remove
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/leds/led-triggers.c:led_trigger_set
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/strparser/strparser.c:strp_done
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffff810c4230-ffffffff810c4242: cancel_work_sync (STB_GLOBAL)
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
