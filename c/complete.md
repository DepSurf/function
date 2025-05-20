# Function: <code>complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810c3ac0)
Location: kernel/sched/completion.c:29
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/kernel/hpet.c:hpet_work
  - kernel/fork.c:mm_release
  - kernel/exit.c:do_exit
  - kernel/exit.c:complete_and_exit
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:flush_workqueue
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:__kthread_parkme
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthreadd
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/tree.c:rcu_barrier_callback
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stop_signal_done
  - kernel/trace/ring_buffer.c:update_pages_handler
  - fs/aio.c:free_ioctx_reqs
  - fs/proc/inode.c:unuse_pde
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ext4/crypto.c:ext4_crypt_complete
  - fs/ext4/crypto_key.c:derive_crypt_complete
  - fs/ext4/crypto_fname.c:ext4_dir_crypt_complete
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/fuse/file.c:fuse_aio_complete
  - security/integrity/ima/ima_crypto.c:ahash_complete
  - block/bio.c:submit_bio_wait_endio
  - block/blk-exec.c:blk_end_sync_rq
  - block/blk-lib.c:bio_batch_end_io
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/xen/grant-table.c:unmap_refs_callback
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/lightnvm/core.c:nvm_end_io_sync
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/misc/bmp085.c:bmp085_eoc_isr
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/spi/spi.c:spi_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/misc/uinput.c:uinput_request_done
  - drivers/i2c/i2c-core.c:i2c_adapter_dev_release
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_done
  - drivers/mmc/core/core.c:__mmc_start_req
  - drivers/mailbox/mailbox.c:tx_tick
  - net/core/flow.c:flow_cache_flush_tasklet
```
**Symbols:**

```
ffffffff810c3ac0-ffffffff810c3b09: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810c77b0)
Location: kernel/sched/completion.c:29
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/kernel/hpet.c:hpet_work
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:complete_and_exit
  - kernel/exit.c:do_exit
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:rcu_barrier_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stop_signal_done
  - kernel/trace/ring_buffer.c:update_pages_handler
  - fs/aio.c:free_ioctx_reqs
  - fs/crypto/crypto.c:fscrypt_complete
  - fs/crypto/fname.c:dir_crypt_complete
  - fs/crypto/keyinfo.c:derive_crypt_complete
  - fs/proc/inode.c:unuse_pde
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - security/integrity/ima/ima_crypto.c:ahash_complete
  - crypto/drbg.c:drbg_skcipher_cb
  - crypto/asymmetric_keys/public_key.c:public_key_verify_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-exec.c:blk_end_sync_rq
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/xen/grant-table.c:unmap_refs_callback
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/lightnvm/core.c:nvm_end_io_sync
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/misc/uinput.c:uinput_request_done
  - drivers/i2c/i2c-core.c:i2c_adapter_dev_release
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:__mmc_start_req
  - drivers/mmc/core/core.c:mmc_wait_done
  - drivers/mailbox/mailbox.c:tx_tick
  - net/core/flow.c:flow_cache_flush_tasklet
```
**Symbols:**

```
ffffffff810c77b0-ffffffff810c77f9: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810cd670)
Location: kernel/sched/completion.c:29
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/kernel/hpet.c:hpet_work
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:complete_and_exit
  - kernel/exit.c:do_exit
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:rcu_barrier_callback
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stop_signal_done
  - kernel/trace/ring_buffer.c:update_pages_handler
  - fs/aio.c:free_ioctx_reqs
  - fs/crypto/crypto.c:page_crypt_complete
  - fs/crypto/fname.c:fname_crypt_complete
  - fs/crypto/keyinfo.c:derive_crypt_complete
  - fs/proc/inode.c:unuse_pde
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - security/integrity/ima/ima_crypto.c:ahash_complete
  - crypto/drbg.c:drbg_skcipher_cb
  - crypto/asymmetric_keys/public_key.c:public_key_verify_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-exec.c:blk_end_sync_rq
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/xen/grant-table.c:unmap_refs_callback
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/lightnvm/core.c:nvm_end_io_sync
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/misc/uinput.c:uinput_request_done
  - drivers/i2c/i2c-core.c:i2c_adapter_dev_release
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
  - drivers/mailbox/mailbox.c:tx_tick
  - net/core/flow.c:flow_cache_flush_tasklet
```
**Symbols:**

```
ffffffff810cd670-ffffffff810cd6b9: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810ca090)
Location: kernel/sched/completion.c:30
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/kernel/hpet.c:hpet_work
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:complete_and_exit
  - kernel/exit.c:do_exit
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:rcu_barrier_callback
  - kernel/livepatch/core.c:klp_kobj_release_patch
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stop_signal_done
  - kernel/trace/ring_buffer.c:update_pages_handler
  - fs/aio.c:free_ioctx_reqs
  - fs/crypto/crypto.c:page_crypt_complete
  - fs/crypto/fname.c:fname_crypt_complete
  - fs/crypto/keyinfo.c:derive_crypt_complete
  - fs/proc/inode.c:close_pdeo
  - fs/proc/inode.c:unuse_pde
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - security/keys/dh.c:dh_crypto_done
  - security/integrity/ima/ima_crypto.c:ahash_complete
  - crypto/drbg.c:drbg_skcipher_cb
  - crypto/asymmetric_keys/public_key.c:public_key_verify_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-exec.c:blk_end_sync_rq
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/xen/grant-table.c:unmap_refs_callback
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/lightnvm/core.c:nvm_end_io_sync
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/misc/uinput.c:uinput_request_done
  - drivers/i2c/i2c-core-base.c:i2c_adapter_dev_release
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
  - net/core/flow.c:flow_cache_flush_tasklet
```
**Symbols:**

```
ffffffff810ca090-ffffffff810ca0e4: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810d18a0)
Location: kernel/sched/completion.c:31
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/kernel/hpet.c:hpet_work
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:complete_and_exit
  - kernel/exit.c:do_exit
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:rcu_barrier_callback
  - kernel/livepatch/core.c:klp_kobj_release_patch
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stop_signal_done
  - kernel/trace/ring_buffer.c:update_pages_handler
  - mm/hmm.c:hmm_devmem_ref_release
  - fs/aio.c:free_ioctx_reqs
  - fs/proc/inode.c:close_pdeo
  - fs/proc/inode.c:unuse_pde
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - fs/debugfs/file.c:debugfs_file_put
  - security/keys/dh.c:dh_crypto_done
  - crypto/api.c:crypto_req_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-exec.c:blk_end_sync_rq
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/xen/grant-table.c:unmap_refs_callback
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
  - drivers/tty/serdev/core.c:serdev_device_write_wakeup
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/i2c/i2c-core-base.c:i2c_adapter_dev_release
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
```
**Symbols:**

```
ffffffff810d18a0-ffffffff810d18f4: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810d9e60)
Location: kernel/sched/completion.c:28
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/kernel/hpet.c:hpet_work
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:complete_and_exit
  - kernel/exit.c:do_exit
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:rcu_barrier_callback
  - kernel/livepatch/core.c:klp_kobj_release_patch
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stop_signal_done
  - kernel/trace/ring_buffer.c:update_pages_handler
  - mm/hmm.c:hmm_devmem_ref_release
  - fs/aio.c:free_ioctx_reqs
  - fs/proc/inode.c:unuse_pde
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - fs/debugfs/file.c:debugfs_file_put
  - security/keys/dh.c:dh_crypto_done
  - crypto/api.c:crypto_req_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-exec.c:blk_end_sync_rq
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/xen/grant-table.c:unmap_refs_callback
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
  - drivers/tty/serdev/core.c:serdev_device_write_wakeup
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/i2c/i2c-core-base.c:i2c_adapter_dev_release
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_connect_completion
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_write_completion
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_read_completion
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_read_completion
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_read_completion
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
```
**Symbols:**

```
ffffffff810d9e60-ffffffff810d9eb4: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810e39b0)
Location: kernel/sched/completion.c:28
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/kernel/hpet.c:hpet_work
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:complete_and_exit
  - kernel/exit.c:do_exit
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/rcu/tree.c:rcu_barrier_callback
  - kernel/livepatch/core.c:klp_kobj_release_patch
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stop_signal_done
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:softlockup_fn
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/trace/ring_buffer.c:update_pages_handler
  - mm/hmm.c:hmm_devmem_ref_release
  - fs/aio.c:free_ioctx_reqs
  - fs/proc/inode.c:unuse_pde
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - fs/debugfs/file.c:debugfs_file_put
  - security/keys/dh.c:dh_crypto_done
  - crypto/api.c:crypto_req_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-exec.c:blk_end_sync_rq
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/xen/grant-table.c:unmap_refs_callback
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
  - drivers/tty/serdev/core.c:serdev_device_write_wakeup
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/i2c/i2c-core-base.c:i2c_adapter_dev_release
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
**Symbols:**

```
ffffffff810e39b0-ffffffff810e3a04: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810ea5d0)
Location: kernel/sched/completion.c:28
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:complete_and_exit
  - kernel/exit.c:do_exit
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/livepatch/core.c:klp_kobj_release_patch
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stop_signal_done
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:softlockup_fn
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/trace/ring_buffer.c:update_pages_handler
  - mm/memremap.c:dev_pagemap_percpu_release
  - fs/aio.c:free_ioctx_reqs
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_ring_ctx_ref_free
  - fs/proc/inode.c:unuse_pde
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - fs/debugfs/file.c:debugfs_file_put
  - security/keys/dh.c:dh_crypto_done
  - crypto/api.c:crypto_req_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-exec.c:blk_end_sync_rq
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/xen/grant-table.c:unmap_refs_callback
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
  - drivers/tty/serdev/core.c:serdev_device_write_wakeup
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/i2c/i2c-core-base.c:i2c_adapter_dev_release
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffff810ea5d0-ffffffff810ea620: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810f5fa0)
Location: kernel/sched/completion.c:28
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:complete_and_exit
  - kernel/exit.c:do_exit
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/livepatch/core.c:klp_kobj_release_patch
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stop_signal_done
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:softlockup_fn
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/trace/ring_buffer.c:update_pages_handler
  - mm/memremap.c:dev_pagemap_percpu_release
  - fs/aio.c:free_ioctx_reqs
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_ring_ctx_ref_free
  - fs/proc/inode.c:unuse_pde
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - fs/debugfs/file.c:debugfs_file_put
  - security/keys/dh.c:dh_crypto_done
  - crypto/api.c:crypto_req_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-exec.c:blk_end_sync_rq
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/xen/grant-table.c:unmap_refs_callback
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
  - drivers/tty/serdev/core.c:serdev_device_write_wakeup
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/lightnvm/core.c:nvm_sync_end_io
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/i2c/i2c-core-base.c:i2c_adapter_dev_release
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffff810f5fa0-ffffffff810f5ff0: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810ff830)
Location: kernel/sched/completion.c:28
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:complete_and_exit
  - kernel/exit.c:exit_mm
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/livepatch/core.c:klp_kobj_release_patch
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:softlockup_fn
  - kernel/seccomp.c:seccomp_notify_send
  - kernel/trace/ring_buffer.c:update_pages_handler
  - kernel/padata.c:padata_mt_helper
  - mm/memremap.c:dev_pagemap_percpu_release
  - fs/aio.c:free_ioctx_reqs
  - fs/io_uring.c:io_file_ref_kill
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_ring_ctx_ref_free
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_worker_exit
  - fs/proc/inode.c:proc_put_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/proc_sysctl.c:sysctl_follow_link
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - fs/debugfs/file.c:debugfs_file_put
  - security/keys/dh.c:dh_crypto_done
  - crypto/api.c:crypto_req_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-exec.c:blk_end_sync_rq
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/xen/grant-table.c:unmap_refs_callback
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
  - drivers/tty/serdev/core.c:serdev_device_write_wakeup
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/lightnvm/core.c:nvm_sync_end_io
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/i2c/i2c-core-base.c:i2c_adapter_dev_release
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/platform/x86/intel_scu_ipc.c:ioc
  - drivers/mailbox/mailbox.c:tx_tick
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffff810ff830-ffffffff810ff876: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810fe340)
Location: kernel/sched/completion.c:28
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:complete_and_exit
  - kernel/exit.c:exit_mm
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/livepatch/core.c:klp_kobj_release_patch
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:softlockup_fn
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/seccomp.c:seccomp_notify_send
  - kernel/trace/ring_buffer.c:update_pages_handler
  - kernel/padata.c:padata_mt_helper
  - mm/memremap.c:dev_pagemap_percpu_release
  - fs/aio.c:free_ioctx_reqs
  - fs/io_uring.c:io_file_ref_kill
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_ring_ctx_ref_free
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_worker_exit
  - fs/proc/inode.c:proc_put_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/proc_sysctl.c:sysctl_follow_link
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - fs/debugfs/file.c:debugfs_file_put
  - security/keys/dh.c:dh_crypto_done
  - crypto/api.c:crypto_req_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-exec.c:blk_end_sync_rq
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/xen/grant-table.c:unmap_refs_callback
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
  - drivers/tty/serdev/core.c:serdev_device_write_wakeup
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/lightnvm/core.c:nvm_sync_end_io
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_prep_async_scan
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/i2c/i2c-core-base.c:i2c_adapter_dev_release
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/platform/x86/intel_scu_ipc.c:ioc
  - drivers/mailbox/mailbox.c:tx_tick
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_free
  - net/ipv4/inet_fragment.c:fqdir_free_fn
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffff810fe340-ffffffff810fe386: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81100720)
Location: kernel/sched/completion.c:28
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:complete_and_exit
  - kernel/exit.c:exit_mm
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/livepatch/core.c:klp_kobj_release_patch
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:softlockup_fn
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/trace/ring_buffer.c:update_pages_handler
  - kernel/padata.c:padata_mt_helper
  - mm/memremap.c:dev_pagemap_percpu_release
  - fs/aio.c:free_ioctx_reqs
  - fs/io_uring.c:io_tctx_exit_cb
  - fs/io_uring.c:io_tctx_exit_cb
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_rsrc_put_work
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_ring_ctx_ref_free
  - fs/io-wq.c:io_wq_exit_workers
  - fs/io-wq.c:io_wq_exit_workers
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:create_worker_cb
  - fs/io-wq.c:io_wqe_activate_free_worker
  - fs/io-wq.c:io_wqe_activate_free_worker
  - fs/proc/inode.c:proc_put_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/proc_sysctl.c:sysctl_follow_link
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - fs/debugfs/file.c:debugfs_file_put
  - security/keys/dh.c:dh_crypto_done
  - crypto/api.c:crypto_req_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-exec.c:blk_end_sync_rq
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/xen/grant-table.c:unmap_refs_callback
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
  - drivers/tty/serdev/core.c:serdev_device_write_wakeup
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/lightnvm/core.c:nvm_sync_end_io
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/vfio/vfio.c:vfio_device_put
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/i2c/i2c-core-base.c:i2c_adapter_dev_release
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/platform/x86/intel_scu_ipc.c:ioc
  - drivers/mailbox/mailbox.c:tx_tick
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_free
  - net/core/selftests.c:net_test_loopback_validate
  - net/ipv4/inet_fragment.c:fqdir_free_fn
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffff81100720-ffffffff81100766: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff8111c780)
Location: kernel/sched/completion.c:28
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:complete_and_exit
  - kernel/exit.c:exit_mm
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/livepatch/core.c:klp_kobj_release_patch
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:softlockup_fn
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/trace/ring_buffer.c:update_pages_handler
  - kernel/padata.c:padata_mt_helper
  - mm/swapfile.c:swap_users_ref_free
  - mm/memremap.c:dev_pagemap_percpu_release
  - fs/aio.c:free_ioctx_reqs
  - fs/io_uring.c:io_tctx_exit_cb
  - fs/io_uring.c:io_tctx_exit_cb
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_rsrc_put_work
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_ring_ctx_ref_free
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:create_worker_cont
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:io_queue_worker_create
  - fs/io-wq.c:io_queue_worker_create
  - fs/io-wq.c:io_queue_worker_create
  - fs/io-wq.c:create_worker_cb
  - fs/io-wq.c:io_worker_cancel_cb
  - fs/io-wq.c:io_worker_release
  - fs/proc/inode.c:proc_put_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/proc_sysctl.c:sysctl_follow_link
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - fs/debugfs/file.c:debugfs_file_put
  - security/keys/dh.c:dh_crypto_done
  - crypto/api.c:crypto_req_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-exec.c:blk_end_sync_rq
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/xen/grant-table.c:unmap_refs_callback
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
  - drivers/tty/serdev/core.c:serdev_device_write_wakeup
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:drop_current_rng
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/vfio/vfio.c:vfio_device_put
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/core/devio.c:usbfs_blocking_completion
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/i2c/i2c-core-base.c:i2c_adapter_dev_release
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/platform/x86/intel_scu_ipc.c:ioc
  - drivers/mailbox/mailbox.c:tx_tick
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_free
  - net/core/selftests.c:net_test_loopback_validate
  - net/core/devlink.c:devlink_put
  - net/ipv4/inet_fragment.c:fqdir_free_fn
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffff8111c780-ffffffff8111c7c6: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113eec0)
Location: kernel/sched/completion.c:28
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:do_exit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:__flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread_complete_and_exit
  - kernel/kthread.c:__kthread_parkme
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/update.c:rcu_barrier_tasks_generic_cb
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/livepatch/core.c:klp_kobj_release_patch
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:softlockup_fn
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/trace/ring_buffer.c:update_pages_handler
  - kernel/padata.c:padata_mt_helper
  - mm/swapfile.c:swap_users_ref_free
  - mm/memremap.c:dev_pagemap_percpu_release
  - fs/aio.c:free_ioctx_reqs
  - fs/proc/inode.c:proc_put_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/proc_sysctl.c:sysctl_follow_link
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - fs/debugfs/file.c:debugfs_file_put
  - security/keys/dh.c:dh_crypto_done
  - crypto/api.c:crypto_req_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-mq.c:blk_end_sync_rq
  - io_uring/io_uring.c:io_tctx_exit_cb
  - io_uring/io_uring.c:io_sq_offload_create
  - io_uring/io_uring.c:io_rsrc_put_work
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io_uring.c:io_ring_ctx_ref_free
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
  - io_uring/io-wq.c:io_worker_release
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/acpi/acpi_pcc.c:pcc_rx_callback
  - drivers/xen/grant-table.c:unmap_refs_callback
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
  - drivers/tty/serdev/core.c:serdev_device_write_wakeup
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:drop_current_rng
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/vfio/vfio.c:vfio_device_put
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/core/devio.c:usbfs_blocking_completion
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/i2c/i2c-core-base.c:i2c_adapter_dev_release
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/platform/x86/intel_scu_ipc.c:ioc
  - drivers/mailbox/mailbox.c:tx_tick
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_free
  - net/core/selftests.c:net_test_loopback_validate
  - net/core/devlink.c:devlink_put
  - net/ipv4/inet_fragment.c:fqdir_free_fn
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffff8113eec0-ffffffff8113ef39: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81169320)
Location: kernel/sched/completion.c:28
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:do_exit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:__flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread_complete_and_exit
  - kernel/kthread.c:__kthread_parkme
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/update.c:rcu_barrier_tasks_generic_cb
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/livepatch/core.c:klp_kobj_release_patch
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:softlockup_fn
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/padata.c:padata_mt_helper
  - mm/swapfile.c:swap_users_ref_free
  - mm/memremap.c:dev_pagemap_percpu_release
  - fs/aio.c:free_ioctx_reqs
  - fs/proc/inode.c:proc_put_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/proc_sysctl.c:sysctl_follow_link
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - fs/debugfs/file.c:debugfs_file_put
  - security/keys/dh.c:dh_crypto_done
  - security/apparmor/notify.c:__listener_complete_user_pending
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - crypto/api.c:crypto_req_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-mq.c:blk_end_sync_rq
  - io_uring/io_uring.c:io_tctx_exit_cb
  - io_uring/io_uring.c:io_tctx_exit_cb
  - io_uring/io_uring.c:io_ring_ctx_ref_free
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/rsrc.c:io_rsrc_put_work
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
  - io_uring/io-wq.c:io_worker_release
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
  - drivers/pci/doe.c:pci_doe_task_complete
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/acpi/acpi_pcc.c:pcc_rx_callback
  - drivers/xen/grant-table.c:unmap_refs_callback
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
  - drivers/tty/serdev/core.c:serdev_device_write_wakeup
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:drop_current_rng
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_lib.c:scsi_mq_free_tags
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/core/devio.c:usbfs_blocking_completion
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/i2c/i2c-core-base.c:i2c_adapter_dev_release
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/platform/x86/intel_scu_ipc.c:ioc
  - drivers/mailbox/mailbox.c:tx_tick
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_free
  - net/core/selftests.c:net_test_loopback_validate
  - net/core/devlink.c:__devlink_put_rcu
  - net/ipv4/inet_fragment.c:fqdir_free_fn
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffff81169320-ffffffff81169399: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81179a20)
Location: kernel/sched/completion.c:28
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:do_exit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:__flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread_complete_and_exit
  - kernel/kthread.c:__kthread_parkme
  - kernel/vhost_task.c:vhost_task_fn
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/update.c:rcu_barrier_tasks_generic_cb
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/livepatch/core.c:klp_kobj_release_patch
  - kernel/module/main.c:idempotent_init_module
  - kernel/module/main.c:idempotent_init_module
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:softlockup_fn
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/padata.c:padata_mt_helper
  - mm/swapfile.c:swap_users_ref_free
  - mm/memremap.c:dev_pagemap_percpu_release
  - fs/aio.c:free_ioctx_reqs
  - fs/proc/inode.c:proc_put_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/proc_sysctl.c:sysctl_follow_link
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - fs/debugfs/file.c:debugfs_file_put
  - security/apparmor/notify.c:__listener_complete_held_user_pending
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - crypto/api.c:crypto_req_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-mq.c:blk_end_sync_rq
  - io_uring/io_uring.c:io_tctx_exit_cb
  - io_uring/io_uring.c:io_tctx_exit_cb
  - io_uring/io_uring.c:io_ring_ctx_ref_free
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
  - io_uring/io-wq.c:io_worker_release
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
  - drivers/pci/doe.c:pci_doe_task_complete
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/acpi/acpi_pcc.c:pcc_rx_callback
  - drivers/xen/grant-table.c:unmap_refs_callback
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
  - drivers/tty/serdev/core.c:serdev_device_write_wakeup
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:drop_current_rng
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_lib.c:scsi_mq_free_tags
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/virtio_scsi.c:virtscsi_ctrl_done
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/core/devio.c:usbfs_blocking_completion
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/i2c/i2c-core-base.c:i2c_adapter_dev_release
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/md/md-bitmap.c:md_bitmap_unplug_fn
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/platform/x86/intel_scu_ipc.c:ioc
  - drivers/mailbox/mailbox.c:tx_tick
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_free
  - net/core/selftests.c:net_test_loopback_validate
  - net/ipv4/inet_fragment.c:fqdir_free_fn
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffff81179a20-ffffffff81179a99: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81187450)
Location: kernel/sched/completion.c:45
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/platform/efi/quirks.c:efi_crash_gracefully_on_page_fault
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:do_exit
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/umh.c:call_usermodehelper_exec_async
  - kernel/workqueue.c:__flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread_complete_and_exit
  - kernel/kthread.c:__kthread_parkme
  - kernel/vhost_task.c:vhost_task_fn
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/update.c:rcu_barrier_tasks_generic_cb
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/livepatch/core.c:klp_kobj_release_patch
  - kernel/module/main.c:idempotent_init_module
  - kernel/module/main.c:idempotent_init_module
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:softlockup_fn
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_addfd
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/padata.c:padata_mt_helper
  - mm/shrinker.c:shrinker_free
  - mm/shrinker.c:shrink_slab
  - mm/shrinker.c:shrink_slab_memcg
  - mm/swapfile.c:swap_users_ref_free
  - mm/memremap.c:dev_pagemap_percpu_release
  - fs/aio.c:free_ioctx_reqs
  - fs/proc/inode.c:proc_put_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
  - fs/proc/proc_sysctl.c:sysctl_follow_link
  - fs/proc/proc_sysctl.c:proc_sys_getattr
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_poll
  - fs/proc/proc_sysctl.c:proc_sys_open
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - fs/debugfs/file.c:debugfs_enter_cancellation
  - fs/debugfs/file.c:debugfs_file_put
  - security/apparmor/notify.c:__listener_complete_held_user_pending
  - security/apparmor/notify.c:free_listener
  - security/apparmor/notify.c:free_listener
  - crypto/api.c:crypto_req_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-mq.c:blk_end_sync_rq
  - io_uring/io_uring.c:io_tctx_exit_cb
  - io_uring/io_uring.c:io_tctx_exit_cb
  - io_uring/io_uring.c:io_ring_ctx_ref_free
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_worker_cancel_cb
  - io_uring/io-wq.c:io_worker_release
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
  - drivers/pci/doe.c:pci_doe_task_complete
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/acpi/acpi_pcc.c:pcc_rx_callback
  - drivers/xen/grant-table.c:unmap_refs_callback
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
  - drivers/tty/serdev/core.c:serdev_device_write_wakeup
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:drop_current_rng
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/base/devtmpfs.c:devtmpfsd
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_lib.c:scsi_mq_free_tags
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/virtio_scsi.c:virtscsi_ctrl_done
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/usb/core/message.c:usb_sg_cancel
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/core/devio.c:usbfs_blocking_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/i2c/i2c-core-base.c:i2c_adapter_dev_release
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
  - drivers/thermal/thermal_core.c:thermal_release
  - drivers/md/md-bitmap.c:md_bitmap_unplug_fn
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/platform/x86/intel_scu_ipc.c:ioc
  - drivers/mailbox/mailbox.c:tx_tick
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_free
  - net/core/selftests.c:net_test_loopback_validate
  - net/ipv4/inet_fragment.c:fqdir_free_fn
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffff81187450-ffffffff811874d0: complete (STB_GLOBAL)
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
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffff800010159a78)
Location: kernel/sched/completion.c:28
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/arm64/kernel/smp.c:secondary_start_kernel
  - virt/kvm/kvm_main.c:kvm_vm_worker_thread
  - virt/kvm/kvm_main.c:kvm_vm_worker_thread
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:complete_and_exit
  - kernel/exit.c:do_exit
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stop_signal_done
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:softlockup_fn
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/trace/ring_buffer.c:update_pages_handler
  - fs/aio.c:free_ioctx_reqs
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_ring_ctx_ref_free
  - fs/proc/inode.c:unuse_pde
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - fs/debugfs/file.c:debugfs_file_put
  - security/keys/dh.c:dh_crypto_done
  - crypto/api.c:crypto_req_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-exec.c:blk_end_sync_rq
  - drivers/video/fbdev/mx3fb.c:mx3fb_dma_done
  - drivers/video/fbdev/mx3fb.c:mx3fb_dma_done
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/soc/qcom/rpmh.c:rpmh_tx_done
  - drivers/xen/grant-table.c:unmap_refs_callback
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
  - drivers/tty/serdev/core.c:serdev_device_write_wakeup
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/lightnvm/core.c:nvm_sync_end_io
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_slave_abort
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_slave_abort
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_slave_abort
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_irq_handler
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_tx_callback
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_callback
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_interrupt
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/i2c/i2c-core-base.c:i2c_adapter_dev_release
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_isr_thread
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_isr_thread
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_driver_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
  - drivers/firmware/raspberrypi.c:response_callback
  - drivers/firmware/ti_sci.c:ti_sci_rx_callback
  - drivers/firmware/arm_scmi/driver.c:scmi_rx_callback
  - drivers/firmware/arm_scmi/driver.c:scmi_rx_callback
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/imx/imx-scu.c:imx_scu_probe
  - drivers/firmware/imx/imx-scu.c:imx_scu_rx_callback
  - drivers/firmware/imx/imx-scu.c:imx_scu_tx_done
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffff800010159a78-ffff800010159b40: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (c03a6a74)
Location: kernel/sched/completion.c:28
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:secondary_start_kernel
  - arch/arm/common/bL_switcher.c:bL_switcher_thread
  - arch/arm/mach-vexpress/spc.c:ve_spc_irq_handler
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:complete_and_exit
  - kernel/exit.c:do_exit
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stop_signal_done
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:softlockup_fn
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/trace/ring_buffer.c:update_pages_handler
  - fs/aio.c:free_ioctx_reqs
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_ring_ctx_ref_free
  - fs/proc/inode.c:unuse_pde
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - fs/debugfs/file.c:debugfs_file_put
  - security/keys/dh.c:dh_crypto_done
  - crypto/api.c:crypto_req_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-exec.c:blk_end_sync_rq
  - drivers/video/fbdev/mx3fb.c:mx3fb_dma_done
  - drivers/soc/tegra/fuse/fuse-tegra20.c:apb_dma_complete
  - drivers/tty/serdev/core.c:serdev_device_write_wakeup
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/lightnvm/core.c:nvm_sync_end_io
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/mtd/nand/raw/omap2.c:omap_nand_irq
  - drivers/mtd/nand/raw/omap2.c:omap_nand_dma_callback
  - drivers/mtd/nand/raw/omap_elm.c:elm_isr
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_slave_abort
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_slave_abort
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_slave_abort
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_irq_handler
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_tx_callback
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_callback
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_interrupt
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_port_status
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/i2c/i2c-core-base.c:i2c_adapter_dev_release
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_dma_callback
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_isr_thread
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_driver_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
  - drivers/firmware/arm_scmi/driver.c:scmi_rx_callback
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/imx/imx-scu.c:imx_scu_probe
  - drivers/firmware/imx/imx-scu.c:imx_scu_rx_callback
  - drivers/firmware/imx/imx-scu.c:imx_scu_tx_done
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_handle_rx
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_isr
  - sound/core/init.c:release_card_device
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
c03a6a74-c03a6acc: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (c0000000001add40)
Location: kernel/sched/completion.c:28
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/powerpc/kernel/rtas.c:__rtas_suspend_cpu
  - arch/powerpc/kernel/rtas.c:__rtas_suspend_last_cpu
  - arch/powerpc/kernel/eeh_event.c:__eeh_send_failure_event
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:complete_and_exit
  - kernel/exit.c:do_exit
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/livepatch/core.c:klp_kobj_release_patch
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stop_signal_done
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:softlockup_fn
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/trace/ring_buffer.c:update_pages_handler
  - mm/memremap.c:dev_pagemap_percpu_release
  - fs/aio.c:free_ioctx_reqs
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_ring_ctx_ref_free
  - fs/proc/inode.c:unuse_pde
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - fs/debugfs/file.c:debugfs_file_put
  - security/keys/dh.c:dh_crypto_done
  - crypto/api.c:crypto_req_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-exec.c:blk_end_sync_rq
  - drivers/tty/serdev/core.c:serdev_device_write_wakeup
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:drop_current_rng
  - drivers/lightnvm/core.c:nvm_sync_end_io
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/i2c/i2c-core-base.c:i2c_adapter_dev_release
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
c0000000001add40-c0000000001addd4: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffe0000ff6c2)
Location: kernel/sched/completion.c:28
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/riscv/kernel/smpboot.c:smp_callin
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:complete_and_exit
  - kernel/exit.c:do_exit
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:softlockup_fn
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/trace/ring_buffer.c:update_pages_handler
  - fs/aio.c:free_ioctx_reqs
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_ring_ctx_ref_free
  - fs/proc/inode.c:proc_put_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
  - security/keys/dh.c:dh_crypto_done
  - crypto/api.c:crypto_req_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-exec.c:blk_end_sync_rq
  - drivers/tty/serdev/core.c:serdev_device_write_wakeup
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/lightnvm/core.c:nvm_sync_end_io
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/i2c/i2c-core-base.c:i2c_adapter_dev_release
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffe0000ff6c2-ffffffe0000ff720: complete (STB_GLOBAL)
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
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810ef3a0)
Location: kernel/sched/completion.c:28
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:complete_and_exit
  - kernel/exit.c:do_exit
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/livepatch/core.c:klp_kobj_release_patch
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stop_signal_done
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:softlockup_fn
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/trace/ring_buffer.c:update_pages_handler
  - mm/memremap.c:dev_pagemap_percpu_release
  - fs/aio.c:free_ioctx_reqs
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_ring_ctx_ref_free
  - fs/proc/inode.c:unuse_pde
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - fs/debugfs/file.c:debugfs_file_put
  - security/keys/dh.c:dh_crypto_done
  - crypto/api.c:crypto_req_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-exec.c:blk_end_sync_rq
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/xen/grant-table.c:unmap_refs_callback
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
  - drivers/tty/serdev/core.c:serdev_device_write_wakeup
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/lightnvm/core.c:nvm_sync_end_io
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/nvme/host/core.c:nvme_end_sync_rq
  - drivers/nvme/host/pci.c:nvme_del_cq_end
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffff810ef3a0-ffffffff810ef3f0: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810df410)
Location: kernel/sched/completion.c:28
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:complete_and_exit
  - kernel/exit.c:do_exit
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/livepatch/core.c:klp_kobj_release_patch
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stop_signal_done
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:softlockup_fn
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/trace/ring_buffer.c:update_pages_handler
  - mm/memremap.c:dev_pagemap_percpu_release
  - fs/aio.c:free_ioctx_reqs
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_ring_ctx_ref_free
  - fs/proc/inode.c:unuse_pde
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - fs/debugfs/file.c:debugfs_file_put
  - security/keys/dh.c:dh_crypto_done
  - crypto/api.c:crypto_req_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-exec.c:blk_end_sync_rq
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/storvsc_drv.c:storvsc_on_channel_callback
  - drivers/nvme/host/core.c:nvme_end_sync_rq
  - drivers/nvme/host/pci.c:nvme_del_cq_end
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/hv/vmbus_drv.c:vmbus_acpi_add
  - drivers/hv/vmbus_drv.c:vmbus_acpi_add
  - drivers/hv/channel_mgmt.c:vmbus_onversion_response
  - drivers/hv/channel_mgmt.c:vmbus_ongpadl_torndown
  - drivers/hv/channel_mgmt.c:vmbus_ongpadl_created
  - drivers/hv/channel_mgmt.c:vmbus_onopen_result
  - drivers/hv/channel_mgmt.c:vmbus_onoffer_rescind
  - drivers/hv/channel_mgmt.c:vmbus_onoffer_rescind
  - drivers/hv/channel_mgmt.c:check_ready_for_suspend_event
  - drivers/hv/channel_mgmt.c:check_ready_for_resume_event
  - drivers/hv/channel_mgmt.c:vmbus_initiate_unload
  - drivers/hv/channel_mgmt.c:vmbus_unload_response
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffff810df410-ffffffff810df460: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810ec4d0)
Location: kernel/sched/completion.c:28
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:complete_and_exit
  - kernel/exit.c:do_exit
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/livepatch/core.c:klp_kobj_release_patch
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stop_signal_done
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:softlockup_fn
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/trace/ring_buffer.c:update_pages_handler
  - mm/memremap.c:dev_pagemap_percpu_release
  - fs/aio.c:free_ioctx_reqs
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_ring_ctx_ref_free
  - fs/proc/inode.c:unuse_pde
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - fs/debugfs/file.c:debugfs_file_put
  - security/keys/dh.c:dh_crypto_done
  - crypto/api.c:crypto_req_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-exec.c:blk_end_sync_rq
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/xen/grant-table.c:unmap_refs_callback
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
  - drivers/tty/serdev/core.c:serdev_device_write_wakeup
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/lightnvm/core.c:nvm_sync_end_io
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_free
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/i2c/i2c-core-base.c:i2c_adapter_dev_release
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_cmd_completion
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_cmd_completion
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffff810ec4d0-ffffffff810ec520: complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void complete(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff810f7510)
Location: kernel/sched/completion.c:28
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
  - kernel/fork.c:mm_release
  - kernel/cpu.c:cpuhp_online_idle
  - kernel/cpu.c:cpuhp_complete_idle_dead
  - kernel/cpu.c:cpuhp_thread_fun
  - kernel/exit.c:complete_and_exit
  - kernel/exit.c:do_exit
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:wq_barrier_func
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/params.c:module_kobj_release
  - kernel/kthread.c:kthread_flush_work_fn
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:__kthread_parkme
  - kernel/rcu/update.c:wakeme_after_rcu
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
  - kernel/livepatch/core.c:klp_kobj_release_patch
  - kernel/smp.c:smp_call_on_cpu_callback
  - kernel/acct.c:close_work
  - kernel/stop_machine.c:cpu_stop_signal_done
  - kernel/watchdog.c:watchdog_enable
  - kernel/watchdog.c:softlockup_fn
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/trace/ring_buffer.c:update_pages_handler
  - mm/memremap.c:dev_pagemap_percpu_release
  - fs/aio.c:free_ioctx_reqs
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_ring_ctx_ref_free
  - fs/proc/inode.c:unuse_pde
  - fs/ext4/sysfs.c:ext4_sb_release
  - fs/ecryptfs/crypto.c:extent_crypt_complete
  - fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - fs/fuse/file.c:fuse_aio_complete
  - fs/debugfs/file.c:debugfs_file_put
  - security/keys/dh.c:dh_crypto_done
  - crypto/api.c:crypto_req_done
  - block/bio.c:submit_bio_wait_endio
  - block/blk-exec.c:blk_end_sync_rq
  - arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu
  - drivers/acpi/device_sysfs.c:acpi_data_node_release
  - drivers/xen/grant-table.c:unmap_refs_callback
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
  - drivers/tty/serdev/core.c:serdev_device_write_wakeup
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:put_rng
  - drivers/lightnvm/core.c:nvm_sync_end_io
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
  - drivers/mfd/wm8350-core.c:wm8350_auxadc_irq
  - drivers/mfd/twl6040.c:twl6040_readyint_handler
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync_cb
  - drivers/mfd/da9052-irq.c:da9052_auxadc_irq
  - drivers/scsi/scsi_error.c:scsi_eh_done
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
  - drivers/ata/libata-core.c:ata_qc_complete_internal
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/spi/spi.c:spi_complete
  - drivers/spi/spi.c:spi_finalize_current_transfer
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:sg_complete
  - drivers/usb/core/message.c:usb_api_blocking_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_command_queue
  - drivers/input/serio/i8042.c:i8042_aux_test_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/misc/uinput.c:uinput_destroy_device
  - drivers/i2c/i2c-core-base.c:i2c_adapter_dev_release
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/md/dm-io.c:sync_io_complete
  - drivers/md/dm-builtin.c:dm_kobject_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpufreq/cpufreq.c:cpufreq_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_state_sysfs_release
  - drivers/cpuidle/sysfs.c:cpuidle_sysfs_release
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_done
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffff810f7510-ffffffff810f7560: complete (STB_GLOBAL)
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
