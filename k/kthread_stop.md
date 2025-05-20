# Function: <code>kthread_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a07f0)
Location: kernel/kthread.c:491
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - mm/vmscan.c:kswapd_stop
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/block/loop.c:loop_clr_fd
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/md/md.c:md_unregister_thread
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
ffffffff810a07f0-ffffffff810a08fa: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a3ee0)
Location: kernel/kthread.c:491
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/block/loop.c:loop_clr_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/md.c:md_unregister_thread
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
ffffffff810a3ee0-ffffffff810a3fd3: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a9530)
Location: kernel/kthread.c:519
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/block/loop.c:loop_clr_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/md.c:md_unregister_thread
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
ffffffff810a9530-ffffffff810a9637: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a6220)
Location: kernel/kthread.c:523
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/block/loop.c:loop_clr_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/md.c:md_unregister_thread
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
ffffffff810a6220-ffffffff810a6314: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ac7b0)
Location: kernel/kthread.c:530
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/block/loop.c:loop_clr_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/md.c:md_unregister_thread
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
ffffffff810ac7b0-ffffffff810ac8aa: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b37b0)
Location: kernel/kthread.c:548
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/block/loop.c:loop_clr_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/md.c:md_unregister_thread
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
ffffffff810b37b0-ffffffff810b38b3: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bcab0)
Location: kernel/kthread.c:550
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/md.c:md_unregister_thread
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
ffffffff810bcab0-ffffffff810bcbb3: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kthread.c (0)
Location: kernel/kthread.c:559
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_finish_async
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/spi/spi.c:spi_destroy_queue
  - drivers/md/md.c:md_unregister_thread
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
ffffffff810c3356-ffffffff810c3369: kthread_stop.cold (STB_LOCAL)
ffffffff810c2aa0-ffffffff810c2ba7: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c8e10)
Location: kernel/kthread.c:559
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/io_uring.c:io_finish_async
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/spi/spi.c:spi_destroy_queue
  - drivers/md/md.c:md_unregister_thread
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
ffffffff810c8e10-ffffffff810c8f1e: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d0a20)
Location: kernel/kthread.c:595
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/smpboot.c:smpboot_destroy_threads
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_sq_offload_start
  - fs/io-wq.c:__io_wq_destroy
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/tty/hvc/hvc_console.c:hvc_init
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_init
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/md/md.c:md_unregister_thread
```
**Symbols:**

```
ffffffff810d0a20-ffffffff810d0ba4: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cb2a0)
Location: kernel/kthread.c:621
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/smpboot.c:smpboot_destroy_threads
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/io_uring.c:io_sq_thread_stop
  - fs/io-wq.c:__io_wq_destroy
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/tty/hvc/hvc_console.c:hvc_init
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_init
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/md.c:md_unregister_thread
```
**Symbols:**

```
ffffffff810cb2a0-ffffffff810cb403: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cccd0)
Location: kernel/kthread.c:648
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/smpboot.c:smpboot_destroy_threads
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
  - kernel/sched/psi.c:psi_trigger_destroy
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/mmp.c:ext4_stop_mmpd
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/md.c:md_unregister_thread
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
ffffffff810cccd0-ffffffff810cce2f: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810dfe10)
Location: kernel/kthread.c:648
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/smpboot.c:smpboot_destroy_threads
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
  - kernel/trace/trace_hwlat.c:hwlat_cpu_die
  - kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/mmp.c:ext4_stop_mmpd
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:set_current_rng
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/md.c:md_unregister_thread
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
ffffffff810dfe10-ffffffff810dff6c: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fa910)
Location: kernel/kthread.c:708
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/smpboot.c:smpboot_destroy_threads
  - kernel/sched/build_utility.c:sugov_exit
  - kernel/sched/build_utility.c:sugov_init
  - kernel/sched/build_utility.c:sugov_kthread_create
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
  - kernel/trace/trace_hwlat.c:hwlat_cpu_die
  - kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/mmp.c:ext4_stop_mmpd
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/md.c:md_unregister_thread
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
ffffffff810fa910-ffffffff810faa8c: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111d760)
Location: kernel/kthread.c:708
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/smpboot.c:smpboot_destroy_threads
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:sugov_exit
  - kernel/sched/build_utility.c:sugov_init
  - kernel/sched/build_utility.c:sugov_kthread_create
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
  - kernel/trace/trace_hwlat.c:hwlat_cpu_die
  - kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/mmp.c:ext4_stop_mmpd
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/md.c:md_unregister_thread
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
ffffffff8111d760-ffffffff8111d8e1: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112a950)
Location: kernel/kthread.c:709
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/smpboot.c:smpboot_destroy_threads
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:sugov_exit
  - kernel/sched/build_utility.c:sugov_init
  - kernel/sched/build_utility.c:sugov_kthread_create
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
  - kernel/trace/trace_hwlat.c:hwlat_cpu_die
  - kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads
  - kernel/trace/trace_osnoise.c:stop_kthread
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/mmp.c:ext4_stop_mmpd
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/md.c:md_unregister_thread
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
ffffffff8112a950-ffffffff8112aad1: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81134fe0)
Location: kernel/kthread.c:708
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/kthread.c:kthread_stop_put
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:sugov_exit
  - kernel/sched/build_utility.c:sugov_init
  - kernel/sched/build_utility.c:sugov_kthread_create
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
  - kernel/trace/trace_hwlat.c:hwlat_cpu_die
  - kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads
  - kernel/trace/trace_osnoise.c:stop_kthread
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/ext4/mmp.c:ext4_stop_mmpd
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/md/md.c:md_unregister_thread
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
ffffffff81134fe0-ffffffff81135161: kthread_stop (STB_GLOBAL)
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
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010128528)
Location: kernel/kthread.c:559
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/io_uring.c:io_finish_async
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/spi/spi.c:spi_destroy_queue
  - drivers/media/cec/cec-pin.c:cec_pin_adap_enable
  - drivers/md/md.c:md_unregister_thread
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
ffff800010128528-ffff8000101286b8: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037aa4c)
Location: kernel/kthread.c:559
Inline: False
Direct callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_active_store
  - arch/arm/common/bL_switcher.c:bL_switcher_active_store
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/smpboot.c:smpboot_destroy_threads
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/ksm.c:ksm_init
  - fs/io_uring.c:io_finish_async
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/spi/spi.c:spi_destroy_queue
  - drivers/md/md.c:md_unregister_thread
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
c037aa4c-c037abdc: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c000000000173170)
Location: kernel/kthread.c:559
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/io_uring.c:io_finish_async
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:set_current_rng
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/spi/spi.c:spi_destroy_queue
  - drivers/md/md.c:md_unregister_thread
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
c000000000173170-c000000000173358: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000df34c)
Location: kernel/kthread.c:559
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/ksm.c:ksm_init
  - fs/io_uring.c:io_finish_async
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/spi/spi.c:spi_destroy_queue
  - drivers/md/md.c:md_unregister_thread
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
ffffffe0000df34c-ffffffe0000df484: kthread_stop (STB_GLOBAL)
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
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c3190)
Location: kernel/kthread.c:559
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/io_uring.c:io_finish_async
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/spi/spi.c:spi_destroy_queue
  - drivers/md/md.c:md_unregister_thread
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
ffffffff810c3190-ffffffff810c329e: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b19d0)
Location: kernel/kthread.c:559
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/io_uring.c:io_finish_async
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/spi/spi.c:spi_destroy_queue
  - drivers/md/md.c:md_unregister_thread
```
**Symbols:**

```
ffffffff810b19d0-ffffffff810b1ade: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c26e0)
Location: kernel/kthread.c:559
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/io_uring.c:io_finish_async
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/spi/spi.c:spi_destroy_queue
  - drivers/md/md.c:md_unregister_thread
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
ffffffff810c26e0-ffffffff810c27ee: kthread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kthread_stop(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810caca0)
Location: kernel/kthread.c:559
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
  - kernel/bpf/cpumap.c:cpu_map_kthread_stop
  - mm/vmscan.c:kswapd_stop
  - mm/compaction.c:kcompactd_stop
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:start_stop_khugepaged
  - fs/io_uring.c:io_finish_async
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/spi/spi.c:spi_destroy_queue
  - drivers/media/cec/cec-pin.c:cec_pin_adap_enable
  - drivers/md/md.c:md_unregister_thread
  - drivers/mmc/core/sdio_irq.c:sdio_release_irq
```
**Symbols:**

```
ffffffff810caca0-ffffffff810cadd4: kthread_stop (STB_GLOBAL)
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
