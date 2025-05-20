# Function: <code>flush_work</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109ae60)
Location: kernel/workqueue.c:2742
Inline: False
Direct callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_cpu_down_callback
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_flush_queues
  - mm/swap.c:lru_add_drain_all
  - mm/swapfile.c:SyS_swapoff
  - mm/vmpressure.c:vmpressure_cleanup
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_read
  - drivers/base/node.c:node_device_release
  - drivers/block/virtio_blk.c:virtblk_freeze
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/block/xen-blkfront.c:xlvbd_release_gendisk
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/net/virtio_net.c:virtnet_freeze
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
**Symbols:**

```
ffffffff8109ae60-ffffffff8109b014: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109e460)
Location: kernel/workqueue.c:2842
Inline: False
Direct callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_flush_queues
  - mm/swap.c:lru_add_drain_all
  - mm/swapfile.c:SyS_swapoff
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_read
  - drivers/base/node.c:node_device_release
  - drivers/block/virtio_blk.c:virtblk_freeze
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/virtio_net.c:virtnet_freeze
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/leds/led-class.c:led_classdev_unregister
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
**Symbols:**

```
ffffffff8109e460-ffffffff8109e620: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a2fc0)
Location: kernel/workqueue.c:2847
Inline: False
Direct callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_flush_queues
  - mm/swap.c:lru_add_drain_all
  - mm/swapfile.c:SyS_swapoff
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/tpm/tpm-dev.c:tpm_release
  - drivers/char/tpm/tpm-dev.c:tpm_read
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/node.c:node_device_release
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/leds/led-class.c:led_classdev_unregister
  - net/core/dev.c:rollback_registered_many
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
**Symbols:**

```
ffffffff810a2fc0-ffffffff810a31a5: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a02c0)
Location: kernel/workqueue.c:2846
Inline: False
Direct callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_flush_queues
  - mm/swapfile.c:SyS_swapoff
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/pstore/platform.c:pstore_unregister
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/node.c:node_device_release
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/leds/led-class.c:led_classdev_unregister
  - net/core/dev.c:rollback_registered_many
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
**Symbols:**

```
ffffffff810a02c0-ffffffff810a048c: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a6850)
Location: kernel/workqueue.c:2863
Inline: False
Direct callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
  - kernel/workqueue.c:__cancel_work_timer
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_flush_queues
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:SYSC_swapoff
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/pstore/platform.c:pstore_unregister
  - drivers/pci/pcie/aer/aerdrv.c:aer_remove
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/node.c:node_device_release
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/leds/led-class.c:led_classdev_unregister
  - net/core/dev.c:rollback_registered_many
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
```
**Symbols:**

```
ffffffff810a6850-ffffffff810a6a27: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ad772)
Location: kernel/workqueue.c:2936
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_flush_queues
  - mm/page_alloc.c:drain_all_pages
  - mm/swap.c:lru_add_drain_all
  - mm/swapfile.c:__do_sys_swapoff
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/pstore/platform.c:pstore_unregister
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/node.c:node_device_release
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/leds/led-class.c:led_classdev_unregister
  - net/core/dev.c:rollback_registered_many
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_flush_gc
```
**Symbols:**

```
ffffffff810ad6a0-ffffffff810ad6b2: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b6a62)
Location: kernel/workqueue.c:2959
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_flush_queues
  - mm/page_alloc.c:drain_all_pages
  - mm/swap.c:lru_add_drain_all
  - mm/swapfile.c:__do_sys_swapoff
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/pstore/platform.c:pstore_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_timeout_work_func
  - drivers/base/node.c:node_device_release
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/leds/led-class.c:led_classdev_unregister
  - net/core/dev.c:rollback_registered_many
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_flush_gc
```
**Symbols:**

```
ffffffff810b6990-ffffffff810b69a2: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bceae)
Location: kernel/workqueue.c:3059
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/padata.c:padata_flush_queues
  - kernel/padata.c:padata_flush_queues
  - mm/swap.c:lru_add_drain_all
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapoff
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/pstore/platform.c:pstore_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_timeout_work_func
  - drivers/base/node.c:node_device_release
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:brightness_store
  - net/core/dev.c:rollback_registered_many
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_flush_gc
```
**Symbols:**

```
ffffffff810bcde0-ffffffff810bcdf2: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2b2e)
Location: kernel/workqueue.c:3068
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/swap.c:lru_add_drain_all
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapoff
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/pstore/platform.c:pstore_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_timeout_work_func
  - drivers/base/node.c:node_device_release
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/vfio/virqfd.c:virqfd_shutdown
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/leds/led-class.c:brightness_store
  - net/core/dev.c:rollback_registered_many
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_flush_gc
```
**Symbols:**

```
ffffffff810c2a60-ffffffff810c2a72: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ca2b1)
Location: kernel/workqueue.c:3065
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/swap.c:lru_add_drain_all
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapoff
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_timeout_work_func
  - drivers/base/node.c:node_device_release
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/vfio/virqfd.c:virqfd_shutdown
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/leds/led-class.c:led_suspend
  - drivers/leds/led-class.c:brightness_store
  - net/core/dev.c:rollback_registered_many
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_flush_gc
```
**Symbols:**

```
ffffffff810c8fc0-ffffffff810c902d: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c53e1)
Location: kernel/workqueue.c:3071
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/swap.c:lru_add_drain_all
  - mm/page_alloc.c:__drain_all_pages
  - mm/swapfile.c:__do_sys_swapoff
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_timeout_work_func
  - drivers/base/node.c:node_device_release
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/vfio/virqfd.c:virqfd_shutdown
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/leds/led-class.c:led_suspend
  - drivers/leds/led-class.c:brightness_store
  - net/core/dev.c:flush_all_backlogs
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_flush_gc
```
**Symbols:**

```
ffffffff810c4130-ffffffff810c419d: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c6cd1)
Location: kernel/workqueue.c:3072
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/swap.c:__lru_add_drain_all
  - mm/page_alloc.c:__drain_all_pages
  - mm/swapfile.c:__do_sys_swapoff
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_timeout_work_func
  - drivers/base/node.c:node_device_release
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/vfio/virqfd.c:virqfd_shutdown
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/leds/led-class.c:led_suspend
  - drivers/leds/led-class.c:brightness_store
  - net/core/dev.c:flush_all_backlogs
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_flush_gc
```
**Symbols:**

```
ffffffff810c5960-ffffffff810c5970: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810d9981)
Location: kernel/workqueue.c:3111
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/swap.c:__lru_add_drain_all
  - mm/page_alloc.c:__drain_all_pages
  - mm/swapfile.c:__do_sys_swapoff
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/slub.c:flush_all_cpus_locked
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_timeout_work_func
  - drivers/base/node.c:node_device_release
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/vfio/virqfd.c:virqfd_shutdown
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/leds/led-class.c:led_suspend
  - drivers/leds/led-class.c:brightness_store
  - net/core/dev.c:flush_all_backlogs
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_flush_gc
```
**Symbols:**

```
ffffffff810d85b0-ffffffff810d85c0: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f366e)
Location: kernel/workqueue.c:3094
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/swap.c:__lru_add_drain_all
  - mm/page_alloc.c:__drain_all_pages
  - mm/swapfile.c:__do_sys_swapoff
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/slub.c:flush_all_cpus_locked
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_timeout_work_func
  - drivers/base/node.c:node_device_release
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/vfio/virqfd.c:virqfd_shutdown
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:led_suspend
  - drivers/leds/led-class.c:brightness_store
  - drivers/hte/hte.c:hte_ts_put
  - net/core/dev.c:flush_all_backlogs
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_flush_gc
```
**Symbols:**

```
ffffffff810f35d0-ffffffff810f35e6: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff811150ae)
Location: kernel/workqueue.c:3092
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/swap.c:__lru_add_drain_all
  - mm/swapfile.c:__do_sys_swapoff
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/slub.c:flush_all_cpus_locked
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_put_super
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_timeout_work_func
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:led_suspend
  - drivers/leds/led-class.c:brightness_store
  - drivers/hte/hte.c:hte_ts_put
  - net/core/dev.c:flush_all_backlogs
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_flush_gc
```
**Symbols:**

```
ffffffff811136b0-ffffffff811136c6: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112107e)
Location: kernel/workqueue.c:3408
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/watchdog.c:lockup_detector_check
  - mm/swap.c:__lru_add_drain_all
  - mm/swapfile.c:__do_sys_swapoff
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/slub.c:flush_all_cpus_locked
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_put_super
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_timeout_work_func
  - drivers/base/firmware_loader/sysfs_upload.c:firmware_upload_unregister
  - drivers/block/virtio_blk.c:virtblk_freeze
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:led_suspend
  - drivers/leds/led-class.c:brightness_store
  - drivers/hte/hte.c:hte_ts_put
  - net/core/dev.c:flush_all_backlogs
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_flush_gc
```
**Symbols:**

```
ffffffff8111fcb0-ffffffff8111fcc6: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112b82e)
Location: kernel/workqueue.c:3429
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu_safe_key
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/watchdog.c:lockup_detector_check
  - mm/swap.c:__lru_add_drain_all
  - mm/slub.c:flush_all_cpus_locked
  - mm/swapfile.c:__do_sys_swapoff
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/ext4/balloc.c:ext4_should_retry_alloc
  - fs/ext4/mballoc.c:ext4_mb_release
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_load_and_init_journal
  - fs/ext4/super.c:ext4_put_super
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_remove
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_timeout_work_func
  - drivers/base/firmware_loader/sysfs_upload.c:firmware_upload_unregister
  - drivers/block/virtio_blk.c:virtblk_freeze
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/gpu/drm/drm_framebuffer.c:drm_fb_release
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_rmfb
  - drivers/gpu/drm/drm_mode_config.c:drm_mode_config_cleanup
  - drivers/net/virtio_net.c:virtnet_remove
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:action_store
  - drivers/md/md.c:stop_sync_thread
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:led_suspend
  - drivers/leds/led-class.c:brightness_store
  - drivers/hte/hte.c:hte_ts_put
  - net/core/dev.c:flush_all_backlogs
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_flush_gc
```
**Symbols:**

```
ffffffff8112a7d0-ffffffff8112a7e6: flush_work (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011f8f4)
Location: kernel/workqueue.c:3068
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_rcu_work
  - kernel/workqueue.c:flush_rcu_work
  - kernel/workqueue.c:flush_delayed_work
Direct callers:
  - virt/kvm/eventfd.c:irqfd_shutdown
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/swap.c:lru_add_drain_all
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapoff
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/pstore/platform.c:pstore_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_timeout_work_func
  - drivers/base/node.c:node_device_release
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/mmc/core/queue.c:mmc_cleanup_queue
  - drivers/leds/led-class.c:brightness_store
  - net/core/dev.c:rollback_registered_many
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_flush_gc
```
**Symbols:**

```
ffff80001011ea20-ffff80001011ea4c: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c03738ec)
Location: kernel/workqueue.c:3068
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/swap.c:lru_add_drain_all
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapoff
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/pstore/platform.c:pstore_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/omap-serial.c:serial_omap_suspend
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_timeout_work_func
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/usb/gadget/udc/core.c:usb_del_gadget_udc
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/mmc/core/queue.c:mmc_cleanup_queue
  - drivers/leds/led-class.c:brightness_store
  - net/core/dev.c:rollback_registered_many
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_flush_gc
```
**Symbols:**

```
c0373800-c0373820: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c000000000169c7c)
Location: kernel/workqueue.c:3068
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_rcu_work
  - kernel/workqueue.c:flush_rcu_work
  - kernel/workqueue.c:flush_delayed_work
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/swap.c:lru_add_drain_all
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapoff
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/pstore/platform.c:pstore_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/hvc/hvsi.c:hvsi_close
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_timeout_work_func
  - drivers/base/node.c:node_device_release
  - drivers/vfio/virqfd.c:virqfd_shutdown
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/leds/led-class.c:brightness_store
  - net/core/dev.c:rollback_registered_many
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_flush_gc
```
**Symbols:**

```
c000000000169b30-c000000000169b44: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d8824)
Location: kernel/workqueue.c:3068
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_rcu_work
  - kernel/workqueue.c:flush_rcu_work
  - kernel/workqueue.c:flush_delayed_work
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/swap.c:lru_add_drain_all
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapoff
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/pstore/platform.c:pstore_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_timeout_work_func
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/mmc/core/queue.c:mmc_cleanup_queue
  - drivers/leds/led-class.c:brightness_store
  - net/core/dev.c:rollback_registered_many
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_flush_gc
```
**Symbols:**

```
ffffffe0000d81ec-ffffffe0000d8216: flush_work (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bce9e)
Location: kernel/workqueue.c:3068
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/swap.c:lru_add_drain_all
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapoff
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/pstore/platform.c:pstore_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_timeout_work_func
  - drivers/base/node.c:node_device_release
  - drivers/block/xen-blkfront.c:blkfront_freeze
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/nvme/host/core.c:nvme_stop_ctrl
  - drivers/nvme/host/core.c:nvme_remove_namespaces
  - drivers/nvme/host/core.c:nvme_do_delete_ctrl
  - drivers/nvme/host/multipath.c:nvme_mpath_remove_disk
  - drivers/nvme/host/pci.c:nvme_error_resume
  - drivers/nvme/host/pci.c:nvme_remove
  - drivers/nvme/host/pci.c:nvme_reset_done
  - drivers/nvme/host/pci.c:nvme_async_probe
  - drivers/nvme/host/pci.c:nvme_async_probe
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - net/core/dev.c:rollback_registered_many
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_flush_gc
```
**Symbols:**

```
ffffffff810bcdd0-ffffffff810bcde2: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ab6de)
Location: kernel/workqueue.c:3068
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/swap.c:lru_add_drain_all
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapoff
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/pstore/platform.c:pstore_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_timeout_work_func
  - drivers/base/node.c:node_device_release
  - drivers/nvme/host/core.c:nvme_stop_ctrl
  - drivers/nvme/host/core.c:nvme_remove_namespaces
  - drivers/nvme/host/core.c:nvme_do_delete_ctrl
  - drivers/nvme/host/multipath.c:nvme_mpath_remove_disk
  - drivers/nvme/host/pci.c:nvme_error_resume
  - drivers/nvme/host/pci.c:nvme_remove
  - drivers/nvme/host/pci.c:nvme_reset_done
  - drivers/nvme/host/pci.c:nvme_async_probe
  - drivers/nvme/host/pci.c:nvme_async_probe
  - drivers/vfio/virqfd.c:virqfd_shutdown
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/md/dm-stripe.c:stripe_dtr
  - net/core/dev.c:rollback_registered_many
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_flush_gc
```
**Symbols:**

```
ffffffff810ab620-ffffffff810ab632: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bc3fe)
Location: kernel/workqueue.c:3068
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/swap.c:lru_add_drain_all
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapoff
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/pstore/platform.c:pstore_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_timeout_work_func
  - drivers/base/node.c:node_device_release
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/vfio/virqfd.c:virqfd_shutdown
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/leds/led-class.c:brightness_store
  - net/core/dev.c:rollback_registered_many
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_flush_gc
```
**Symbols:**

```
ffffffff810bc330-ffffffff810bc342: flush_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool flush_work(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c472e)
Location: kernel/workqueue.c:3068
Inline: True
Inline callers:
  - kernel/workqueue.c:work_on_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:flush_delayed_work
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/cgroup/cpuset.c:cpuset_wait_for_hotplug
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - mm/swap.c:lru_add_drain_all
  - mm/page_alloc.c:drain_all_pages
  - mm/swapfile.c:__do_sys_swapoff
  - mm/vmpressure.c:vmpressure_cleanup
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/pstore/platform.c:pstore_unregister
  - drivers/regulator/core.c:regulator_unregister
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_io.c:tty_flush_works
  - drivers/tty/tty_buffer.c:tty_buffer_flush_work
  - drivers/tty/serial/kgdboc.c:kgdboc_unregister_kbd
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_release
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/dd.c:wait_for_device_probe
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_timeout_work_func
  - drivers/base/node.c:node_device_release
  - drivers/block/xen-blkfront.c:blkif_free_ring
  - drivers/vfio/virqfd.c:virqfd_shutdown
  - drivers/usb/core/hub.c:hub_quiesce
  - drivers/usb/host/ohci-hcd.c:ohci_stop
  - drivers/md/dm-stripe.c:stripe_dtr
  - drivers/leds/led-class.c:brightness_store
  - net/core/dev.c:rollback_registered_many
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_state_fini
  - net/xfrm/xfrm_state.c:xfrm_flush_gc
```
**Symbols:**

```
ffffffff810c3430-ffffffff810c3442: flush_work (STB_GLOBAL)
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
