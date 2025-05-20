# Function: <code>mutex_trylock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81821990)
Location: kernel/locking/mutex.c:900
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/rcu/tree.c:synchronize_sched_expedited
  - kernel/kexec_core.c:crash_kexec
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec.c:compat_SyS_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/stop_machine.c:try_stop_cpus
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/memcontrol.c:try_charge
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:d_splice_alias
  - fs/aio.c:aio_migratepage
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/md/md.c:md_notify_reboot
  - drivers/clk/clk.c:clk_prepare_lock
  - drivers/vme/vme.c:vme_dma_list_add
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_free
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
ffffffff81821990-ffffffff818219c1: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8189bdf0)
Location: kernel/locking/mutex.c:904
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec.c:compat_SyS_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:try_stop_cpus
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - fs/dcache.c:d_splice_alias
  - fs/aio.c:aio_migratepage
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/md/md.c:md_notify_reboot
  - drivers/clk/clk.c:clk_prepare_lock
  - drivers/vme/vme.c:vme_dma_free
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
ffffffff8189bdf0-ffffffff8189be1e: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff818d05d0)
Location: kernel/locking/mutex.c:1005
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec.c:compat_SyS_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:try_stop_cpus
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - fs/dcache.c:d_splice_alias
  - fs/aio.c:aio_migratepage
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - drivers/clk/clk.c:clk_prepare_lock
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/md/md.c:md_notify_reboot
  - drivers/vme/vme.c:vme_dma_free
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
ffffffff818d05d0-ffffffff818d0614: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81907b10)
Location: kernel/locking/mutex.c:1177
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:__crash_kexec
  - kernel/kexec.c:compat_SyS_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:try_stop_cpus
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - fs/dcache.c:d_splice_alias
  - fs/aio.c:aio_migratepage
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - drivers/clk/clk.c:clk_prepare_lock
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/md/md.c:md_notify_reboot
  - drivers/vme/vme.c:vme_dma_free
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
ffffffff81907b10-ffffffff81907b6e: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81991c00)
Location: kernel/locking/mutex.c:1177
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:__crash_kexec
  - kernel/kexec.c:compat_SyS_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:try_stop_cpus
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:drain_all_pages
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - fs/dcache.c:d_splice_alias
  - fs/aio.c:aio_migratepage
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - drivers/clk/clk.c:clk_prepare_lock
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/md/md.c:md_notify_reboot
  - drivers/vme/vme.c:vme_dma_free
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
ffffffff81991c00-ffffffff81991c5e: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff819ee090)
Location: kernel/locking/mutex.c:1201
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:__crash_kexec
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:try_stop_cpus
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:drain_all_pages
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/vmalloc.c:free_vmap_area_noflush
  - fs/aio.c:aio_migratepage
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - drivers/clk/clk.c:clk_prepare_lock
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_notify_reboot
  - drivers/vme/vme.c:vme_dma_free
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
ffffffff819ee090-ffffffff819ee0e7: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a29300)
Location: kernel/locking/mutex.c:1379
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:__crash_kexec
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:try_stop_cpus
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:drain_all_pages
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/vmalloc.c:free_vmap_area_noflush
  - fs/aio.c:aio_migratepage
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - drivers/clk/clk.c:clk_prepare_lock
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_unregister
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/vme/vme.c:vme_dma_free
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
ffffffff81a29300-ffffffff81a29357: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a99990)
Location: kernel/locking/mutex.c:1384
Inline: False
Direct callers:
  - kernel/power/user.c:snapshot_ioctl
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:__crash_kexec
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:try_stop_cpus
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:drain_all_pages
  - fs/dcache.c:d_splice_alias
  - fs/aio.c:aio_migratepage
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - drivers/clk/clk.c:clk_prepare_lock
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/vme/vme.c:vme_dma_free
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
ffffffff81a99990-ffffffff81a999e7: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff811035ee)
Location: kernel/locking/mutex.c:1410
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
Direct callers:
  - kernel/power/user.c:snapshot_ioctl
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:__crash_kexec
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:try_stop_cpus
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:drain_all_pages
  - fs/dcache.c:d_splice_alias
  - fs/aio.c:aio_migratepage
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/vme/vme.c:vme_dma_free
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
ffffffff81ad12e0-ffffffff81ad1337: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8110e10e)
Location: kernel/locking/mutex.c:1410
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/user.c:snapshot_ioctl
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:__crash_kexec
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/page_alloc.c:drain_all_pages
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
  - fs/dcache.c:d_splice_alias
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/aio.c:aio_migratepage
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/clk/clk.c:clk_prepare_lock
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_opmode_show
  - drivers/regulator/core.c:regulator_uA_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/base/core.c:online_store
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/vme/vme.c:vme_dma_free
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
ffffffff81bc94c0-ffffffff81bc9517: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8110b3ce)
Location: kernel/locking/mutex.c:1413
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/user.c:snapshot_ioctl
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:__crash_kexec
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/page_alloc.c:__drain_all_pages
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
  - fs/dcache.c:d_splice_alias
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/aio.c:aio_migratepage
  - fs/io_uring.c:__io_uring_show_fdinfo
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/clk/clk.c:clk_prepare_lock
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:destroy_regulator
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_opmode_show
  - drivers/regulator/core.c:regulator_uA_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/base/core.c:online_store
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/vme/vme.c:vme_dma_free
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
ffffffff81c422e0-ffffffff81c42337: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81c34250)
Location: kernel/locking/mutex.c:1411
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/user.c:snapshot_ioctl
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:__crash_kexec
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/page_alloc.c:__drain_all_pages
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge
  - fs/dcache.c:d_splice_alias
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/aio.c:aio_migratepage
  - fs/io_uring.c:__io_uring_show_fdinfo
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/clk/clk.c:clk_prepare_lock
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_opmode_show
  - drivers/regulator/core.c:regulator_uA_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/base/core.c:online_store
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/vme/vme.c:vme_dma_free
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
ffffffff81c34250-ffffffff81c342a7: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81d52b40)
Location: kernel/locking/mutex.c:1025
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/user.c:snapshot_ioctl
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:__crash_kexec
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/page_alloc.c:__drain_all_pages
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
  - fs/dcache.c:d_splice_alias
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/aio.c:aio_migratepage
  - fs/io_uring.c:__io_uring_show_fdinfo
  - fs/io_uring.c:tctx_task_work
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/clk/clk.c:clk_prepare_lock
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:regulator_sync_voltage_rdev
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:print_constraints_debug
  - drivers/regulator/core.c:requested_microamps_show
  - drivers/regulator/core.c:state_show
  - drivers/regulator/core.c:opmode_show
  - drivers/regulator/core.c:microamps_show
  - drivers/regulator/core.c:microvolts_show
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/base/core.c:online_store
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/vme/vme.c:vme_dma_free
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
ffffffff81d52b40-ffffffff81d52b98: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8114dc4a)
Location: kernel/locking/mutex.c:1081
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_trylock
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/user.c:snapshot_ioctl
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:__crash_kexec
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/page_alloc.c:__alloc_pages_may_oom
  - mm/page_alloc.c:__drain_all_pages
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
  - fs/dcache.c:d_splice_alias
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/aio.c:aio_migratepage
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - io_uring/io_uring.c:__io_uring_show_fdinfo
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:handle_prev_tw_list
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/clk/clk.c:clk_prepare_lock
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/base/core.c:online_store
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/vme/vme.c:vme_dma_free
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
ffffffff81f23670-ffffffff81f236e6: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8117cdfa)
Location: kernel/locking/mutex.c:1081
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_trylock
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/user.c:snapshot_ioctl
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/bpf/trampoline.c:bpf_tramp_ftrace_ops_func
  - mm/vmscan.c:lru_gen_age_node
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/page_alloc.c:__alloc_pages_may_oom
  - mm/page_alloc.c:__drain_all_pages
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
  - fs/dcache.c:d_splice_alias
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/aio.c:aio_migrate_folio
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - io_uring/io_uring.c:io_run_local_work
  - io_uring/io_uring.c:handle_tw_list
  - io_uring/io_uring.c:handle_tw_list
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/msg_ring.c:io_msg_install_complete
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/clk/clk.c:clk_prepare_lock
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/base/core.c:online_store
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/staging/vme_user/vme.c:vme_dma_free
  - drivers/staging/vme_user/vme.c:vme_dma_list_free
  - drivers/staging/vme_user/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
  - net/core/devlink.c:devl_trylock
```
**Symbols:**

```
ffffffff820ceb40-ffffffff820cebb6: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8118dab9)
Location: kernel/locking/mutex.c:1081
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_trylock
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/user.c:snapshot_ioctl
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/bpf/trampoline.c:bpf_tramp_ftrace_ops_func
  - mm/vmscan.c:lru_gen_age_node
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/page_alloc.c:__alloc_pages_may_oom
  - mm/page_alloc.c:__drain_all_pages
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
  - fs/dcache.c:d_splice_alias
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/aio.c:aio_migrate_folio
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - io_uring/io_uring.c:io_run_local_work
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/msg_ring.c:io_msg_install_complete
  - io_uring/msg_ring.c:io_msg_ring_data
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/clk/clk.c:clk_prepare_lock
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:do_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/base/core.c:online_store
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/staging/vme_user/vme.c:vme_dma_free
  - drivers/staging/vme_user/vme.c:vme_dma_list_free
  - drivers/staging/vme_user/vme.c:vme_dma_list_add
  - drivers/platform/x86/intel/pmc/mtl.c:mtl_set_device_d3
  - net/core/rtnetlink.c:rtnl_trylock
  - net/devlink/core.c:devl_trylock
```
**Symbols:**

```
ffffffff82152fe0-ffffffff8215303b: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8119c469)
Location: kernel/locking/mutex.c:1086
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_trylock
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/user.c:snapshot_ioctl
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/bpf/trampoline.c:bpf_tramp_ftrace_ops_func
  - mm/vmscan.c:lru_gen_age_node
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/page_alloc.c:__alloc_pages_may_oom
  - mm/page_alloc.c:__drain_all_pages
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_resize_max
  - mm/memcontrol.c:try_charge_memcg
  - fs/dcache.c:d_splice_alias
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:do_epoll_ctl
  - fs/aio.c:aio_migrate_folio
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - io_uring/io_uring.c:io_run_local_work
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/msg_ring.c:io_msg_install_complete
  - io_uring/msg_ring.c:io_msg_ring_data
  - io_uring/fdinfo.c:io_uring_show_fdinfo
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
  - drivers/clk/clk.c:clk_prepare_lock
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:iterate_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/base/core.c:online_store
  - drivers/gpu/drm/drm_probe_helper.c:output_poll_execute
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/staging/vme_user/vme.c:vme_dma_free
  - drivers/staging/vme_user/vme.c:vme_dma_list_free
  - drivers/staging/vme_user/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
  - net/devlink/core.c:devlink_rel_nested_in_notify_work
```
**Symbols:**

```
ffffffff82235e20-ffffffff82235e7b: mutex_trylock (STB_GLOBAL)
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
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffff8000101687ac)
Location: kernel/locking/mutex.c:1410
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
Direct callers:
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_create
  - virt/kvm/arm/vgic/vgic-kvm-device.c:lock_all_vcpus
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:__crash_kexec
  - kernel/kexec.c:__arm64_compat_sys_kexec_load
  - kernel/kexec.c:__arm64_sys_kexec_load
  - kernel/kexec_file.c:__arm64_sys_kexec_file_load
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:try_stop_cpus
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:drain_all_pages
  - fs/dcache.c:d_splice_alias
  - fs/aio.c:aio_migratepage
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - drivers/clk/clk.c:clk_prepare_lock
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_notify_reboot
  - drivers/vme/vme.c:vme_dma_free
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
ffff800010da2d30-ffff800010da2dc0: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c03b4ec0)
Location: kernel/locking/mutex.c:1410
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
Direct callers:
  - kernel/power/user.c:snapshot_ioctl
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:__crash_kexec
  - kernel/kexec.c:__se_sys_kexec_load
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:try_stop_cpus
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:drain_all_pages
  - fs/dcache.c:d_splice_alias
  - fs/aio.c:aio_migratepage
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - drivers/clk/clk.c:clk_prepare_lock
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/mtd/mtd_blkdevs.c:del_mtd_blktrans_dev
  - drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/vme/vme.c:vme_dma_free
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_list_add
  - sound/core/pcm_native.c:snd_pcm_stream_group_ref
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
c0e9b700-c0e9b794: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c0000000001c056c)
Location: kernel/locking/mutex.c:1410
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:__crash_kexec
  - kernel/kexec.c:__se_compat_sys_kexec_load
  - kernel/kexec.c:__se_sys_kexec_load
  - kernel/kexec_file.c:__se_sys_kexec_file_load
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:try_stop_cpus
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:drain_all_pages
  - fs/dcache.c:d_splice_alias
  - fs/aio.c:aio_migratepage
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/vme/vme.c:vme_dma_free
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
c000000000ee53c0-c000000000ee5444: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffe00010a4ca)
Location: kernel/locking/mutex.c:1410
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:try_stop_cpus
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:drain_all_pages
  - fs/dcache.c:d_splice_alias
  - fs/aio.c:aio_migratepage
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - drivers/clk/clk.c:clk_prepare_lock
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_resolve_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_notify_reboot
  - drivers/vme/vme.c:vme_dma_free
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
ffffffe0008c69d2-ffffffe0008c6a32: mutex_trylock (STB_GLOBAL)
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
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810fc8fe)
Location: kernel/locking/mutex.c:1410
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
Direct callers:
  - kernel/power/user.c:snapshot_ioctl
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:__crash_kexec
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:try_stop_cpus
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:drain_all_pages
  - fs/dcache.c:d_splice_alias
  - fs/aio.c:aio_migratepage
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/vme/vme.c:vme_dma_free
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
ffffffff81a70150-ffffffff81a701a7: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810ecb0e)
Location: kernel/locking/mutex.c:1410
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
Direct callers:
  - kernel/power/user.c:snapshot_ioctl
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:__crash_kexec
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:try_stop_cpus
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:drain_all_pages
  - fs/dcache.c:d_splice_alias
  - fs/aio.c:aio_migratepage
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/vme/vme.c:vme_dma_free
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
ffffffff81a2c540-ffffffff81a2c597: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810f9abe)
Location: kernel/locking/mutex.c:1410
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
Direct callers:
  - kernel/power/user.c:snapshot_ioctl
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:__crash_kexec
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:try_stop_cpus
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:drain_all_pages
  - fs/dcache.c:d_splice_alias
  - fs/aio.c:aio_migratepage
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/vme/vme.c:vme_dma_free
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
ffffffff81adc560-ffffffff81adc5b7: mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int mutex_trylock(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81104c2e)
Location: kernel/locking/mutex.c:1410
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
Direct callers:
  - kernel/power/user.c:snapshot_ioctl
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/kexec_core.c:kernel_kexec
  - kernel/kexec_core.c:__crash_kexec
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:try_stop_cpus
  - mm/oom_kill.c:pagefault_out_of_memory
  - mm/slab_common.c:dump_unreclaimable_slab
  - mm/vmalloc.c:free_vmap_area_noflush
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:drain_all_pages
  - fs/dcache.c:d_splice_alias
  - fs/aio.c:aio_migratepage
  - fs/ecryptfs/messaging.c:ecryptfs_send_message
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/regulator/core.c:regulator_late_cleanup
  - drivers/regulator/core.c:regulator_summary_lock_one
  - drivers/regulator/core.c:regulator_resume
  - drivers/regulator/core.c:regulator_suspend
  - drivers/regulator/core.c:regulator_remove_coupling
  - drivers/regulator/core.c:regulator_allow_bypass
  - drivers/regulator/core.c:regulator_set_load
  - drivers/regulator/core.c:regulator_get_error_flags
  - drivers/regulator/core.c:_regulator_get_mode
  - drivers/regulator/core.c:regulator_set_mode
  - drivers/regulator/core.c:_regulator_get_current_limit
  - drivers/regulator/core.c:regulator_set_current_limit
  - drivers/regulator/core.c:regulator_sync_voltage
  - drivers/regulator/core.c:_regulator_list_voltage
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:regulator_total_uA_show
  - drivers/regulator/core.c:regulator_state_show
  - drivers/regulator/core.c:regulator_uV_show
  - drivers/regulator/core.c:regulator_lock_recursive
  - drivers/tty/tty_io.c:tty_write_lock
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/spi/spi.c:spi_write_then_read
  - drivers/net/ppp/ppp_generic.c:ppp_nl_newlink
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
  - drivers/power/supply/power_supply_core.c:power_supply_deferred_register_work
  - drivers/md/md.c:md_notify_reboot
  - drivers/md/md.c:md_check_recovery
  - drivers/vme/vme.c:vme_dma_free
  - drivers/vme/vme.c:vme_dma_list_free
  - drivers/vme/vme.c:vme_dma_list_add
  - net/core/rtnetlink.c:rtnl_trylock
```
**Symbols:**

```
ffffffff81ae8bc0-ffffffff81ae8c17: mutex_trylock (STB_GLOBAL)
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
