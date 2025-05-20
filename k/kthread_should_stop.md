# Function: <code>kthread_should_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a0060)
Location: kernel/kthread.c:79
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_worker_fn
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/wait.c:wait_woken
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/virtio/virtio_balloon.c:balloon
  - drivers/virtio/virtio_balloon.c:balloon
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff810a0060-ffffffff810a0085: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a4174)
Location: kernel/kthread.c:79
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/wait.c:wait_woken
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff810a3750-ffffffff810a3775: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a8810)
Location: kernel/kthread.c:88
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/wait.c:wait_woken
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff810a8810-ffffffff810a884f: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a5660)
Location: kernel/kthread.c:91
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/wait.c:wait_woken
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff810a5660-ffffffff810a568e: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810abd30)
Location: kernel/kthread.c:99
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/wait.c:wait_woken
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff810abd30-ffffffff810abd5e: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b3ae8)
Location: kernel/kthread.c:98
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/wait.c:wait_woken
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff810b3600-ffffffff810b362e: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bc7f8)
Location: kernel/kthread.c:98
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/wait.c:wait_woken
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff810bc930-ffffffff810bc95e: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kthread.c (ffffffff810c270b)
Location: kernel/kthread.c:101
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/wait.c:wait_woken
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff810c331d-ffffffff810c3330: kthread_should_stop.cold (STB_LOCAL)
ffffffff810c28c0-ffffffff810c28f0: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c90b9)
Location: kernel/kthread.c:101
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/wait.c:wait_woken
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff810c7e30-ffffffff810c7e5e: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d14db)
Location: kernel/kthread.c:108
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/wait.c:wait_woken
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/irq/manage.c:irq_wait_for_interrupt
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_do_scan
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_wq_manager
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff810d0700-ffffffff810d072e: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cbe9d)
Location: kernel/kthread.c:109
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:sgx_sanitize_section
  - kernel/workqueue.c:rescuer_thread
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/irq/manage.c:irq_wait_for_interrupt
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_do_scan
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_wq_manager
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff810cb160-ffffffff810cb18e: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cd7ed)
Location: kernel/kthread.c:134
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/workqueue.c:rescuer_thread
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/vfio/vfio_iommu_type1.c:vfio_wait
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_threaded_poll
```
**Symbols:**

```
ffffffff810cca90-ffffffff810ccabe: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e09c8)
Location: kernel/kthread.c:134
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/workqueue.c:rescuer_thread
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/vfio/vfio_iommu_type1.c:vfio_wait
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_threaded_poll
```
**Symbols:**

```
ffffffff810df5f0-ffffffff810df61e: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fab54)
Location: kernel/kthread.c:155
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/workqueue.c:rescuer_thread
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:wait_woken
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/vfio/vfio_iommu_type1.c:vfio_wait
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_threaded_poll
```
**Symbols:**

```
ffffffff810f9630-ffffffff810f9662: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111d9bc)
Location: kernel/kthread.c:155
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/workqueue.c:rescuer_thread
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:wait_woken
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_threaded_poll
```
**Symbols:**

```
ffffffff8111c290-ffffffff8111c2c2: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112abac)
Location: kernel/kthread.c:156
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/workqueue.c:rescuer_thread
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/build_utility.c:psi_rtpoll_worker
  - kernel/sched/build_utility.c:psi_rtpoll_worker
  - kernel/sched/build_utility.c:psi_rtpoll_worker
  - kernel/sched/build_utility.c:psi_rtpoll_worker
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_osnoise.c:timerlat_main
  - kernel/trace/trace_osnoise.c:osnoise_main
  - kernel/trace/trace_osnoise.c:osnoise_sleep
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_threaded_poll
```
**Symbols:**

```
ffffffff811294e0-ffffffff81129512: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff811352cc)
Location: kernel/kthread.c:156
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/workqueue.c:rescuer_thread
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/build_utility.c:psi_rtpoll_worker
  - kernel/sched/build_utility.c:psi_rtpoll_worker
  - kernel/sched/build_utility.c:psi_rtpoll_worker
  - kernel/sched/build_utility.c:psi_rtpoll_worker
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_osnoise.c:timerlat_main
  - kernel/trace/trace_osnoise.c:osnoise_main
  - kernel/trace/trace_osnoise.c:osnoise_sleep
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/balloon.c:balloon_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/dev.c:napi_threaded_poll
  - net/core/dev.c:napi_threaded_poll
```
**Symbols:**

```
ffffffff81133b60-ffffffff81133b92: kthread_should_stop (STB_GLOBAL)
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
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff8000101270b8)
Location: kernel/kthread.c:101
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_vm_worker_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/wait.c:wait_woken
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffff8000101270b8-ffff800010127100: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c0379a48)
Location: kernel/kthread.c:101
Inline: False
Direct callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_thread
  - arch/arm/common/bL_switcher.c:bL_switcher_thread
  - arch/arm/common/bL_switcher.c:bL_switcher_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/wait.c:wait_woken
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
c0379a48-c0379aa0: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c000000000172d14)
Location: kernel/kthread.c:101
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
Direct callers:
  - arch/powerpc/kernel/eeh_event.c:eeh_event_handler
  - arch/powerpc/kernel/eeh_event.c:eeh_event_handler
  - arch/powerpc/platforms/powernv/opal.c:kopald
  - arch/powerpc/platforms/powernv/opal.c:kopald
  - kernel/workqueue.c:rescuer_thread
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/wait.c:wait_woken
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
c000000000172f30-c000000000172f5c: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000de916)
Location: kernel/kthread.c:101
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/wait.c:wait_woken
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffe0000de916-ffffffe0000de95c: kthread_should_stop (STB_GLOBAL)
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
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c3439)
Location: kernel/kthread.c:101
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/wait.c:wait_woken
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff810c21b0-ffffffff810c21de: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b1c79)
Location: kernel/kthread.c:101
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/wait.c:wait_woken
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810b0a00-ffffffff810b0a2e: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2989)
Location: kernel/kthread.c:101
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/wait.c:wait_woken
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff810c1700-ffffffff810c172e: kthread_should_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool kthread_should_stop();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ca21e)
Location: kernel/kthread.c:101
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/smpboot.c:smpboot_thread_fn
  - kernel/sched/wait.c:wait_woken
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_decompress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:lzo_compress_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/power/swap.c:crc32_threadfn
  - kernel/irq/manage.c:irq_thread
  - kernel/freezer.c:__refrigerator
  - kernel/audit.c:kauditd_thread
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/cpci_hotplug_core.c:event_thread
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
  - drivers/media/cec/cec-pin.c:cec_pin_thread_func
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
```
**Symbols:**

```
ffffffff810c9b30-ffffffff810c9b5e: kthread_should_stop (STB_GLOBAL)
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
