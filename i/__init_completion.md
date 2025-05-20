# Function: <code>__init_completion</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8106857c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/fork.c (ffffffff8108a1e6)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff8108b9b8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
```
```
In kernel/workqueue.c (ffffffff810a690b)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/kthread.c (ffffffff810ac36b)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
```
```
In kernel/rcu/update.c (ffffffff810f9dc8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (ffffffff810fb367)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff810fe404)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/tree.c:_rcu_barrier
```
```
In kernel/livepatch/core.c (ffffffff81102395)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_register_patch
```
```
In kernel/smp.c (ffffffff8111f367)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (ffffffff8112828a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
```
```
In kernel/stop_machine.c (ffffffff8113fdf6)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/trace/ring_buffer.c (ffffffff8116b7fb)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In mm/hmm.c (ffffffff8126dcd4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_add
```
```
In fs/aio.c (ffffffff812cb60e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/crypto/crypto.c (ffffffff812cfad8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812d06f8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812d0d88)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/coredump.c (ffffffff812e01bc)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/proc_sysctl.c (ffffffff812f8ce2)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffff8135db06)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffff81388b25)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffff8138e689)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/debugfs/file.c (ffffffff813a253e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/keys/dh.c (ffffffff813bb80d)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81420ad4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/api.c (ffffffff81425860)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/gcm.c (ffffffff8143a3f5)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8143cfd0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814424fc)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In drivers/acpi/device_sysfs.c (ffffffff8153a883)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/xen/grant-table.c (ffffffff815ba3f6)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815c49b3)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff81609c2c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_alloc
```
```
In drivers/char/hw_random/core.c (ffffffff81614cf4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/base/devtmpfs.c (ffffffff8164f876)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
```
In drivers/base/power/main.c (ffffffff816568e6)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_class.c (ffffffff8165fd00)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff81682f17)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (ffffffff81683bba)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (ffffffff816881af)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81689d8a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffff8168bb79)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff816b8b41)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (ffffffff816d706d)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffffffff816f6599)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/usb/core/message.c (ffffffff8171f91d)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817656ff)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/serio/i8042.c (ffffffff82707f9b)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817879aa)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff81788a6a)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817914b5)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817984b6)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/md/dm.c (ffffffff817c12f5)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-io.c (ffffffff817c957b)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817da31b)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpuidle/sysfs.c (ffffffff817e5403)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
```
```
In drivers/mmc/core/core.c (ffffffff817e8454)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_areq
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff8181140d)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
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
In arch/x86/kernel/hpet.c (ffffffff8106b0cc)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/fork.c (ffffffff8108da49)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff8108f2a9)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
```
```
In kernel/workqueue.c (ffffffff810ad57c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/kthread.c (ffffffff810b2ced)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
```
```
In kernel/rcu/update.c (ffffffff8110232a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (ffffffff811038aa)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff81105352)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/tree.c:_rcu_barrier
```
```
In kernel/livepatch/core.c (ffffffff8110a724)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_register_patch
```
```
In kernel/smp.c (ffffffff8112c6a8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (ffffffff811360d3)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/stop_machine.c (ffffffff8114e725)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/trace/ring_buffer.c (ffffffff8117acc0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In mm/hmm.c (ffffffff812923ca)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_add
```
```
In fs/aio.c (ffffffff812f5173)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/crypto/crypto.c (ffffffff812fa3e6)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812fadcf)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812fb8f7)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/coredump.c (ffffffff8130c3f2)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/proc_sysctl.c (ffffffff813265d9)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffff8138c366)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffff813b7975)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffff813bd75d)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/debugfs/file.c (ffffffff813d1984)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/keys/dh.c (ffffffff813ec652)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81452f7c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/api.c (ffffffff81458210)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/gcm.c (ffffffff8146cdbf)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8146fe14)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81475462)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In arch/x86/lib/msr-smp.c (ffffffff814f94e3)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
```
```
In drivers/acpi/device_sysfs.c (ffffffff8157071a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/xen/grant-table.c (ffffffff815f2278)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815fd04e)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff81643477)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_alloc
```
```
In drivers/char/hw_random/core.c (ffffffff8164e914)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/base/devtmpfs.c (ffffffff8168b242)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
```
In drivers/base/power/main.c (ffffffff816924cb)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff8169a9df)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff816befab)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (ffffffff816bfc7c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (ffffffff816c432a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816c5ec1)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffff816c7c3b)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff816f4e97)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (ffffffff81712afd)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffffffff817319f0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/usb/core/message.c (ffffffff8175f5c4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a5a62)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/serio/i8042.c (ffffffff82732313)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c8a4b)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff817ca49a)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817d3f15)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817db185)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-amd-platdrv.c (ffffffff817dd954)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_probe
```
```
In drivers/md/dm.c (ffffffff8180996f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-io.c (ffffffff818122ea)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81822d74)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpuidle/sysfs.c (ffffffff8182e75f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
```
```
In drivers/mmc/core/core.c (ffffffff81831860)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff8185b29e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
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
In arch/x86/kernel/hpet.c (ffffffff81070e5c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/fork.c (ffffffff81095cd9)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff810975a9)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
```
```
In kernel/workqueue.c (ffffffff810b6862)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/kthread.c (ffffffff810bbf6d)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
```
```
In kernel/rcu/update.c (ffffffff8110dd20)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (ffffffff8110f1c5)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff81110b67)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/livepatch/core.c (ffffffff81115ef4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_register_patch
```
```
In kernel/smp.c (ffffffff81137f78)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (ffffffff81141863)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/stop_machine.c (ffffffff8115b415)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/watchdog.c (ffffffff8117714e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/seccomp.c (ffffffff81178275)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff81187730)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In mm/hmm.c (ffffffff812a6ee8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_add
```
```
In fs/aio.c (ffffffff8130a263)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/crypto/crypto.c (ffffffff8130f736)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff81310186)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff81310e4d)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/coredump.c (ffffffff81321c52)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/proc_sysctl.c (ffffffff8133d4b0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffff813a4f96)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffff813d0e83)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffff813d6d9d)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/debugfs/file.c (ffffffff813ec084)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/keys/dh.c (ffffffff8140721a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814700cc)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/api.c (ffffffff81475650)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/gcm.c (ffffffff81489380)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff81490151)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814932dc)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In arch/x86/lib/msr-smp.c (ffffffff8150dd83)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
```
```
In drivers/acpi/device_sysfs.c (ffffffff815882da)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/xen/grant-table.c (ffffffff8160d1d8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8161812e)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff816617b7)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_alloc
```
```
In drivers/char/hw_random/core.c (ffffffff8166cba4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/base/devtmpfs.c (ffffffff816ab472)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
```
In drivers/base/power/main.c (ffffffff816b2b3b)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff816bb1d5)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff816e037b)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (ffffffff816e104c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (ffffffff816e571a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816e72c1)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffff816e90fb)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff817177f7)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (ffffffff81734fad)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffffffff817543e0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/usb/core/message.c (ffffffff81783ba4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817cbb52)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/serio/i8042.c (ffffffff828eb824)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817f00eb)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff817f1b5a)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817fb055)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81801eb5)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/media/cec/cec-adap.c (ffffffff81803c3d)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
```
```
In drivers/md/dm.c (ffffffff81835a57)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-io.c (ffffffff8183e26a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8184ed4f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpuidle/sysfs.c (ffffffff8185a95f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
```
```
In drivers/mmc/core/core.c (ffffffff8185d840)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff818758a0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff8187a6fe)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
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
In kernel/fork.c (ffffffff81099f6d)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff8109bb19)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
```
```
In kernel/workqueue.c (ffffffff810bcccf)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/kthread.c (ffffffff810c20be)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
```
```
In kernel/rcu/update.c (ffffffff811173b6)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (ffffffff81118f2f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff8111a5da)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/livepatch/core.c (ffffffff8111fbe3)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/smp.c (ffffffff81143110)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (ffffffff8114cbc4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/stop_machine.c (ffffffff81167aa5)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/watchdog.c (ffffffff81183f2f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/seccomp.c (ffffffff81185000)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff81194c59)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In mm/memremap.c (ffffffff812c2975)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In fs/aio.c (ffffffff8132c0da)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/io_uring.c (ffffffff81330f7d)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
```
In fs/crypto/crypto.c (ffffffff81336c17)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813375f2)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff813385cb)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/coredump.c (ffffffff81349a7e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/proc_sysctl.c (ffffffff813657b8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffff813cf1d6)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffff813fba74)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffff81401781)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/debugfs/file.c (ffffffff814182aa)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/keys/dh.c (ffffffff81434383)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8149dacf)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/api.c (ffffffff814a3356)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/gcm.c (ffffffff814b6fc7)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814bd309)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c0f28)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In arch/x86/lib/msr-smp.c (ffffffff8153c401)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
```
```
In drivers/acpi/device_sysfs.c (ffffffff815b8f91)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/xen/grant-table.c (ffffffff81640999)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8164be03)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff816972e9)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_alloc
```
```
In drivers/char/hw_random/core.c (ffffffff816a2766)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/base/devtmpfs.c (ffffffff816e501e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
```
In drivers/base/power/main.c (ffffffff816ec98b)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff816f5a57)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff81719a2b)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (ffffffff8171a7a9)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (ffffffff8171ee1f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81720a95)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffff817229d7)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff81753326)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (ffffffff8177091f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffffffff8178fb7e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/usb/core/message.c (ffffffff817c1ebe)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8180beff)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/serio/i8042.c (ffffffff82905dd7)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8183054a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff81831e0a)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8183bcb5)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818436e5)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/media/cec/cec-adap.c (ffffffff81845297)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
```
```
In drivers/md/dm.c (ffffffff81878027)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-io.c (ffffffff81880f93)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81892162)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpuidle/sysfs.c (ffffffff8189e2b1)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
```
```
In drivers/mmc/core/core.c (ffffffff818a1481)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff818b9a90)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff818bfd16)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
```
```
In drivers/soundwire/bus.c (ffffffff818c11e1)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/soundwire/bus.c:sdw_transfer_defer
```
```
In drivers/soundwire/mipi_disco.c (ffffffff818c31e8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
```
```
In net/ipv4/inet_fragment.c (ffffffff819cecdf)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/packet/af_packet.c (ffffffff81a550a9)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In kernel/fork.c (ffffffff810a054d)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff810a2099)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
```
```
In kernel/workqueue.c (ffffffff810c294f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/kthread.c (ffffffff810c861e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
```
```
In kernel/rcu/update.c (ffffffff81123786)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (ffffffff811252ff)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff811269da)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/livepatch/core.c (ffffffff8112c333)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/smp.c (ffffffff8114ec50)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (ffffffff81158894)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/stop_machine.c (ffffffff81173965)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/watchdog.c (ffffffff8118fdaf)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/seccomp.c (ffffffff81190eea)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff811a0719)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In mm/memremap.c (ffffffff812d485c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/aio.c (ffffffff8133ef2a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/io_uring.c (ffffffff81344b09)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
```
In fs/crypto/crypto.c (ffffffff8134a7e7)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8134b1b2)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134e3da)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff813504c3)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/coredump.c (ffffffff81361d1e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/proc_sysctl.c (ffffffff8137da48)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffff813e88a6)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffff814158d5)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffff8141b671)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/debugfs/file.c (ffffffff8143216a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/keys/dh.c (ffffffff8144e0d3)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b7f0f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/api.c (ffffffff814bdf66)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/gcm.c (ffffffff814d01e7)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814d5f9a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d9d58)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In arch/x86/lib/msr-smp.c (ffffffff8155d211)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
```
```
In drivers/acpi/device_sysfs.c (ffffffff815da1d1)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/xen/grant-table.c (ffffffff81663359)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8166e293)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff816b9e99)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_alloc
```
```
In drivers/char/hw_random/core.c (ffffffff816c5506)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/base/devtmpfs.c (ffffffff817092fe)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
```
In drivers/base/power/main.c (ffffffff817109fb)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff81719e57)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff8173dd1b)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (ffffffff8173ea99)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (ffffffff817430ef)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81744d65)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffff81746c77)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff817775a6)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (ffffffff8179497f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffffffff817b375e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/usb/core/message.c (ffffffff817f283e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8183ceff)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/serio/i8042.c (ffffffff8290f812)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81861e7a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff8186374a)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186d645)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81875065)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/media/cec/cec-adap.c (ffffffff81876b65)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
```
```
In drivers/md/dm.c (ffffffff818a9e5b)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-io.c (ffffffff818b2e53)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818c4170)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpuidle/sysfs.c (ffffffff818d0751)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
```
```
In drivers/mmc/core/core.c (ffffffff818d3771)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff818ec530)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff818f2836)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
```
```
In net/ipv4/inet_fragment.c (ffffffff81a0586f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/packet/af_packet.c (ffffffff81a8bc99)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In kernel/fork.c (ffffffff810a741c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff810a8f29)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
```
```
In kernel/workqueue.c (ffffffff810c7c2d)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/kthread.c (ffffffff810d0626)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
```
```
In kernel/rcu/update.c (ffffffff8112fe02)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (ffffffff811324a4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff81136611)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/livepatch/core.c (ffffffff8113abe2)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
```
In kernel/smp.c (ffffffff8115f2b0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (ffffffff81168f04)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/stop_machine.c (ffffffff8118635d)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_one_cpu
```
```
In kernel/watchdog.c (ffffffff811a492f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/seccomp.c (ffffffff811a626a)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff811b6cf9)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/padata.c (ffffffff82cf81f8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_multithreaded
```
```
In mm/memremap.c (ffffffff8130a315)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/aio.c (ffffffff81378e5a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/io_uring.c (ffffffff81380e6d)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In fs/io-wq.c (ffffffff8138b413)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
```
```
In fs/crypto/crypto.c (ffffffff8138ff47)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81390803)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8139417a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff81396e88)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/coredump.c (ffffffff813a7d9c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/proc_sysctl.c (ffffffff813c7fed)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffff814355d6)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffff81463c65)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffff8146a161)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/debugfs/file.c (ffffffff81482577)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/keys/dh.c (ffffffff814a0335)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81516f3a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/api.c (ffffffff8151ec16)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/gcm.c (ffffffff8153024a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff81535b59)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815392ef)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In block/blk-crypto-fallback.c (ffffffff815823ca)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In arch/x86/lib/msr-smp.c (ffffffff815e6bf1)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
```
```
In drivers/acpi/device_sysfs.c (ffffffff81684581)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/xen/grant-table.c (ffffffff81712909)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171e527)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff8176e299)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_alloc
```
```
In drivers/char/hw_random/core.c (ffffffff81779ca6)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/iommu/intel/svm.c (ffffffff817aa09c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/base/devtmpfs.c (ffffffff817c3bb5)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_submit_req
```
```
In drivers/base/power/main.c (ffffffff817cc85b)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff817d4f57)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff817fb6ab)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (ffffffff817fc458)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (ffffffff818014af)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81802be5)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffff81804977)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff8183a4b6)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (ffffffff81858b86)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffffffff8187af58)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/usb/core/message.c (ffffffff818c21f1)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8190f9ad)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/serio/i8042.c (ffffffff82d23aa4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_check_aux
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819356aa)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff8193785a)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819415c5)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819497c5)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/md/dm.c (ffffffff8197a3ab)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-io.c (ffffffff81983493)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81993aa9)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
```
In drivers/cpuidle/sysfs.c (ffffffff819a2e50)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
```
```
In drivers/mmc/core/core.c (ffffffff819a5e41)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819bfe60)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819c5554)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff819c7df6)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
```
```
In net/ipv4/inet_fragment.c (ffffffff81af500f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/packet/af_packet.c (ffffffff81b890c9)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In virt/kvm/kvm_main.c (ffff8000100bfa40)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_vm_create_worker_thread
```
```
In kernel/fork.c (ffff8000100f4e28)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffff8000100f6fec)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
```
```
In kernel/workqueue.c (ffff80001011ce88)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/kthread.c (ffff800010128064)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
```
```
In kernel/rcu/update.c (ffff8000101888d0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (ffff80001018a550)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffff80001018c410)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/smp.c (ffff8000101bcbc8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (ffff8000101c78d4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/acct.c:__arm64_sys_acct
```
```
In kernel/stop_machine.c (ffff8000101e7e68)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/watchdog.c (ffff8000102075c4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/seccomp.c (0)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffff800010219f20)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In fs/aio.c (ffff8000103fc354)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/aio.c:__arm64_sys_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/io_uring.c (ffff800010402f44)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
```
In fs/crypto/crypto.c (ffff80001040afd8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffff80001040bba8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffff80001040f5e0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffff80001041217c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/coredump.c (ffff80001042841c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/proc_sysctl.c (ffff80001044ab94)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffff8000104c161c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffff8000104f6ea0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffff8000104fcac0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/debugfs/file.c (ffff800010517048)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/keys/dh.c (ffff800010538904)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffff8000105b02d4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/api.c (ffff8000105b6d18)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/gcm.c (ffff8000105cc6f8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffff8000105d1dc4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffff8000105d5b64)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In drivers/video/fbdev/mx3fb.c (ffff800010760ac0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_pan_display
```
```
In drivers/acpi/device_sysfs.c (ffff80001076663c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/soc/qcom/rpmh.c (ffff80001081cd60)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh.c:rpmh_write_batch
```
```
In drivers/xen/grant-table.c (ffff80001082c7c8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffff800010838f9c)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/tty/serdev/core.c (ffff8000108a9808)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_alloc
```
```
In drivers/char/hw_random/core.c (ffff8000108b75f0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/base/devtmpfs.c (ffff8000108f705c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
```
In drivers/base/power/main.c (ffff800010901218)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_loader/main.c (ffff80001090d5d4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/mfd/wm831x-auxadc.c (ffff8000109390e0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (ffff800010939d50)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (ffff80001093f23c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffff800010941930)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffff8000109436dc)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (ffff80001097c220)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (ffff80001099f190)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffff8000109c7820)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/spi/spi-fsl-lib.c (ffff8000109cb6f8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-lib.c:mpc8xxx_spi_probe
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109cd80c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e9ed0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/usb/core/message.c (ffff800010a22a24)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a7acc4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/misc/uinput.c (ffff800010aa47f8)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffff800010ab23c8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010ab9e2c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-omap.c (ffff800010abb7a0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abce34)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
```
```
In drivers/media/cec/cec-adap.c (ffff800010abe4dc)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
```
```
In drivers/md/dm.c (ffff800010affa38)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-io.c (ffff800010b0a590)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b21790)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpuidle/sysfs.c (ffff800010b29068)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
```
```
In drivers/mmc/core/core.c (ffff800010b2ccc8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
```
```
In drivers/firmware/raspberrypi.c (ffff800010b4e90c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/firmware/raspberrypi.c:rpi_firmware_probe
```
```
In drivers/firmware/ti_sci.c (ffff800010b5120c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/firmware/ti_sci.c:ti_sci_probe
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b5647c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffff800010b5f710)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/firmware/imx/imx-scu.c (ffff800010b62318)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/firmware/imx/imx-scu.c:imx_scu_probe
  - drivers/firmware/imx/imx-scu.c:imx_scu_probe
```
```
In drivers/mailbox/mailbox.c (ffff800010b7a95c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_request_channel
```
```
In drivers/mailbox/pl320-ipc.c (ffff800010b7ae94)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mailbox/pl320-ipc.c:pl320_ipc_transmit
```
```
In drivers/mailbox/pcc.c (ffff800010b7bcb8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
```
```
In net/ipv4/inet_fragment.c (ffff800010cbe500)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/packet/af_packet.c (ffff800010d585d0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/common/bL_switcher.c (c0327488)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_active_store
  - arch/arm/common/bL_switcher.c:bL_switch_to
```
```
In arch/arm/mach-vexpress/spc.c (c034d200)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - arch/arm/mach-vexpress/spc.c:spc_set_rate
  - arch/arm/mach-vexpress/spc.c:ve_spc_populate_opps
  - arch/arm/mach-vexpress/spc.c:ve_spc_init
```
```
In kernel/fork.c (c0353564)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (c0355464)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
```
```
In kernel/workqueue.c (c037365c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/kthread.c (c037a274)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
```
```
In kernel/rcu/update.c (c03d7238)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (c03d8c5c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (c03dd650)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/smp.c (c04052a0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (c040ef04)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/acct.c:__se_sys_acct
```
```
In kernel/stop_machine.c (c04280fc)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/watchdog.c (c0446370)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/seccomp.c (c0447560)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/trace/ring_buffer.c (c045741c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In fs/aio.c (c05d0fe8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/io_uring.c (c05d63d8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
```
In fs/crypto/crypto.c (c05d8148)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (c05d89c0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (c05dc2d4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/verity/hash_algs.c (c05de808)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/coredump.c (c05f10a4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/proc_sysctl.c (c060f9e8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (c068523c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (c06b4b84)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_extent
```
```
In fs/ecryptfs/kthread.c (c06ba120)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/debugfs/file.c (c06d2db8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/keys/dh.c (c06ef2ec)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (c075f9ec)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/api.c (c0765c98)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/gcm.c (c077a5ec)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (c077f664)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (c078366c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In drivers/video/fbdev/mx3fb.c (c08e33f0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_pan_display
```
```
In drivers/soc/tegra/fuse/fuse-tegra20.c (c093aa0c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_probe
```
```
In drivers/tty/serdev/core.c (c09a5ff0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_alloc
```
```
In drivers/char/hw_random/core.c (c09b125c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/base/devtmpfs.c (c09e3084)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
```
In drivers/base/power/main.c (c09eb408)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_loader/main.c (c09f65d8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/mfd/wm831x-auxadc.c (c0a214cc)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (c0a21ffc)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (c0a28950)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (c0a2a470)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (c0a2c664)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (c0a4fbc0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (c0a6f874)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/mtd/nand/raw/omap2.c (c0aaa400)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_irq_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_irq_pref
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf_dma_pref
  - drivers/mtd/nand/raw/omap2.c:omap_read_buf_dma_pref
```
```
In drivers/mtd/nand/raw/omap_elm.c (c0aad154)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap_elm.c:elm_probe
```
```
In drivers/spi/spi.c (c0ab07a8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/spi/spi-fsl-lib.c (c0ab49b8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-lib.c:mpc8xxx_spi_probe
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab7ca4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acb1ac)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/auxdisplay/arm-charlcd.c (c0ae859c)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/usb/core/message.c (c0af989c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (c0b4e5e0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/misc/uinput.c (c0b83bf8)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (c0b93afc)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/busses/i2c-designware-master.c (c0b994d8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9c1c8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
```
```
In drivers/i2c/busses/i2c-omap.c (c0b9ca74)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
```
```
In drivers/media/cec/cec-adap.c (c0ba01f8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
```
```
In drivers/md/dm.c (c0bde6fc)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-io.c (c0be8c34)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
```
```
In drivers/cpufreq/cpufreq.c (c0bfbdd0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpuidle/sysfs.c (c0c03a34)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
```
```
In drivers/mmc/core/core.c (c0c08020)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
```
```
In drivers/mmc/host/cqhci.c (c0c2f918)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mmc/host/cqhci.c:cqhci_init
```
```
In drivers/firmware/arm_scmi/driver.c (c0c37c40)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
```
```
In drivers/firmware/efi/runtime-wrappers.c (c0c3edac)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/firmware/imx/imx-scu.c (c0c40aa8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/firmware/imx/imx-scu.c:imx_scu_probe
  - drivers/firmware/imx/imx-scu.c:imx_scu_probe
```
```
In drivers/mailbox/mailbox.c (c0c5fe10)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_request_channel
```
```
In drivers/mailbox/pl320-ipc.c (c0c60270)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mailbox/pl320-ipc.c:pl320_ipc_transmit
```
```
In drivers/memory/tegra/tegra20-emc.c (c0c74b2c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
```
```
In sound/core/init.c (c0c83b90)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - sound/core/init.c:snd_card_free
```
```
In net/ipv4/inet_fragment.c (c0dc9efc)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/packet/af_packet.c (c0e58054)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c00000000013aef4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (c00000000013d51c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
```
```
In kernel/workqueue.c (c0000000001670a4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/kthread.c (c000000000171f08)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
```
```
In kernel/rcu/update.c (c0000000001e2a98)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (c0000000001e5460)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (c0000000001eac34)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/livepatch/core.c (c0000000001f04fc)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/smp.c (c00000000022340c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (c0000000002304cc)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/acct.c:__se_sys_acct
```
```
In kernel/stop_machine.c (c000000000258798)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/watchdog.c (c000000000283c90)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/seccomp.c (c0000000002852e8)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/trace/ring_buffer.c (c00000000029c018)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In mm/memremap.c (c00000000046e0dc)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/aio.c (c0000000005048cc)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/io_uring.c (c00000000050f8a8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
```
In fs/crypto/crypto.c (c000000000517a94)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (c0000000005188c8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (c00000000051d080)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (c00000000051fee8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/coredump.c (c0000000005385e0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/proc_sysctl.c (c000000000561340)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (c0000000005f81fc)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (c000000000638198)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (c00000000063fb50)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/debugfs/file.c (c00000000065ffc0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/keys/dh.c (c000000000687508)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (c00000000072fd9c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/api.c (c00000000073c1d4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/gcm.c (c000000000757b58)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (c00000000075ed70)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (c00000000076435c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In drivers/tty/serdev/core.c (c000000000941348)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_alloc
```
```
In drivers/char/hw_random/core.c (c000000000951cc4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/base/devtmpfs.c (c000000000992754)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
```
In drivers/base/power/main.c (c00000000099eda0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_loader/main.c (c0000000009adb3c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/mfd/wm831x-auxadc.c (c0000000009dffe8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (c0000000009e1038)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (c0000000009e82c0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (c0000000009e9c14)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (c0000000009eca6c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (c000000000a36cc8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (c000000000a637a0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (c000000000a8823c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/spi/spi-fsl-lib.c (c000000000a8d4d0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-lib.c:mpc8xxx_spi_probe
```
```
In drivers/usb/core/message.c (c000000000adda44)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (c000000000b52904)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/serio/i8042.c (c0000000013b33f4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
```
In drivers/input/misc/uinput.c (c000000000b85b50)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (c000000000b95be0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/busses/i2c-designware-master.c (c000000000b9cd94)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/media/cec/cec-adap.c (c000000000b9faa4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
```
```
In drivers/md/dm.c (c000000000beb6ac)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-io.c (c000000000bfc0d8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/cpufreq/cpufreq.c (c000000000c15754)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpuidle/sysfs.c (c000000000c20a20)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
```
```
In drivers/mmc/core/core.c (c000000000c25b04)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
```
```
In drivers/mailbox/mailbox.c (c000000000c59764)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_request_channel
```
```
In net/ipv4/inet_fragment.c (c000000000dd8bf4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/packet/af_packet.c (c000000000e90be0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c14a4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffe0000c2cb0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
```
```
In kernel/workqueue.c (ffffffe0000d74ce)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/kthread.c (ffffffe0000def5e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
```
```
In kernel/rcu/update.c (ffffffe00011de46)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (ffffffe00011f2a8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffe0001214ba)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/smp.c (ffffffe000140e6c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (ffffffe000147eae)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/acct.c:__se_sys_acct
```
```
In kernel/stop_machine.c (ffffffe00015d0ec)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/watchdog.c (ffffffe000169d76)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/seccomp.c (ffffffe00016aa86)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffe000177c8e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In fs/aio.c (ffffffe0002ac0c2)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/io_uring.c (ffffffe0002b076c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
```
In fs/crypto/crypto.c (ffffffe0002b4cf8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffe0002b564a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b84a2)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/verity/hash_algs.c (ffffffe0002ba1e2)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/coredump.c (ffffffe0002c665a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/proc_sysctl.c (ffffffe0002dfe70)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffe00033cb78)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffe000365a68)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffe00036b16c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/debugfs/file.c (ffffffe000380630)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/keys/dh.c (ffffffe0003975aa)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffffffe0003f7f5e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/api.c (ffffffe0003fddce)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/gcm.c (ffffffe000410634)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffe000415542)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffe000419cc8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In drivers/tty/serdev/core.c (ffffffe00055f19e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_alloc
```
```
In drivers/char/hw_random/core.c (ffffffe0005682fe)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/base/devtmpfs.c (ffffffe000587e84)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
```
In drivers/base/firmware_loader/main.c (ffffffe000592054)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffe0005add4a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (ffffffe0005ae8ac)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (ffffffe0005b2f0e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffe0005b469e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffe0005b61fc)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (ffffffe0005e2c02)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (ffffffe0005ff028)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffffffe000617f98)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/spi/spi-fsl-lib.c (ffffffe00061ada6)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-lib.c:mpc8xxx_spi_probe
```
```
In drivers/spi/spi-sifive.c (ffffffe00061c2c8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/spi/spi-sifive.c:sifive_spi_probe
```
```
In drivers/usb/core/message.c (ffffffe00064594a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffffffe0006922f8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/misc/uinput.c (ffffffe0006b24e2)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006ba13a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffe0006be746)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/media/cec/cec-adap.c (ffffffe0006c00a0)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
```
```
In drivers/md/dm.c (ffffffe0006f02b2)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-io.c (ffffffe0006f8546)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/mmc/core/core.c (ffffffe000706d22)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
```
```
In drivers/mailbox/mailbox.c (ffffffe00072c1b2)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_request_channel
```
```
In net/ipv4/inet_fragment.c (ffffffe00081460a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/packet/af_packet.c (ffffffe00089057e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
</details>
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
In kernel/fork.c (ffffffff81099e6d)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff8109b9b9)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
```
```
In kernel/workqueue.c (ffffffff810bccbf)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/kthread.c (ffffffff810c299e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
```
```
In kernel/rcu/update.c (ffffffff8111bd66)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (ffffffff8111d8df)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff8111efba)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/livepatch/core.c (ffffffff81124913)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/smp.c (ffffffff81147270)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (ffffffff81150eb4)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/stop_machine.c (ffffffff8116bf85)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/watchdog.c (ffffffff811883cf)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/seccomp.c (ffffffff8118950a)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff81198d39)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In mm/memremap.c (ffffffff812cce3c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/aio.c (ffffffff8133750a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/io_uring.c (ffffffff8133d0e9)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
```
In fs/crypto/crypto.c (ffffffff81342dc7)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81343792)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813469ba)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff81348aa3)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/coredump.c (ffffffff8135a2fe)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/proc_sysctl.c (ffffffff81376028)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffff813e0e86)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffff8140deb5)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffff81413c51)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/debugfs/file.c (ffffffff8142a74a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/keys/dh.c (ffffffff814466b3)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b04ef)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/api.c (ffffffff814b6546)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/gcm.c (ffffffff814c87c7)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814ce57a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814d2338)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In arch/x86/lib/msr-smp.c (ffffffff81555801)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
```
```
In drivers/acpi/device_sysfs.c (ffffffff815cc9a1)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/xen/grant-table.c (ffffffff816291c9)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff816340b3)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff8167f8f9)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_alloc
```
```
In drivers/char/hw_random/core.c (ffffffff8168af56)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/base/devtmpfs.c (ffffffff816cea4e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
```
In drivers/base/power/main.c (ffffffff816d6d7b)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff816e0187)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/block/xen-blkfront.c (ffffffff816f79bc)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff817017fb)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81702e05)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffff81703ce7)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff8172bc96)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/nvme/host/pci.c (ffffffff8174ccc8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:__nvme_disable_io_queues
```
```
In drivers/ata/libata-core.c (ffffffff81759a8f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffffffff8177823e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/net/xen-netfront.c (ffffffff817917a3)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/usb/core/message.c (ffffffff817aac1e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817f52af)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/serio/i8042.c (ffffffff828f65b1)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
```
In drivers/input/misc/uinput.c (ffffffff818163fa)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/media/cec/cec-adap.c (ffffffff8181f0d5)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
```
```
In drivers/md/dm.c (ffffffff8184fcdb)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-io.c (ffffffff81858cd3)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81868890)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpuidle/sysfs.c (ffffffff81874141)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
```
```
In drivers/mmc/core/core.c (ffffffff81877131)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8188e110)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff81893b66)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
```
```
In net/ipv4/inet_fragment.c (ffffffff819a560f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/packet/af_packet.c (ffffffff81a2b329)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In kernel/fork.c (ffffffff810888ad)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff8108a3e9)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
```
```
In kernel/workqueue.c (ffffffff810ab50f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/kthread.c (ffffffff810b11ee)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
```
```
In kernel/rcu/update.c (ffffffff8110cdd6)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (ffffffff8110e97f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff811109ca)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/livepatch/core.c (ffffffff81117373)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/smp.c (ffffffff8113a550)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (ffffffff81144164)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/stop_machine.c (ffffffff8115f185)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/watchdog.c (ffffffff8117b50f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/seccomp.c (ffffffff8117c64a)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff8118c579)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In mm/memremap.c (ffffffff812bdcac)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/aio.c (ffffffff8132823a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/io_uring.c (ffffffff8132dda9)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
```
In fs/crypto/crypto.c (ffffffff81333aa7)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81334472)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8133769a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff81339783)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/coredump.c (ffffffff8134afae)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/proc_sysctl.c (ffffffff81366af8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffff813d1906)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffff813fe935)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffff814046d1)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/debugfs/file.c (ffffffff8141b1ca)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/keys/dh.c (ffffffff81437103)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814a0f0f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/api.c (ffffffff814a6f66)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/gcm.c (ffffffff814b91e7)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814bef9a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814c2d58)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In arch/x86/lib/msr-smp.c (ffffffff81545ad1)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
```
```
In drivers/acpi/device_sysfs.c (ffffffff815b6521)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/char/hw_random/core.c (ffffffff81668956)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/base/devtmpfs.c (ffffffff816a9d7e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
```
In drivers/base/power/main.c (ffffffff816b13db)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff816ba7c7)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff816d560b)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816d6c15)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffff816d7ae7)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff817050b6)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/scsi/storvsc_drv.c (ffffffff81712a76)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/scsi/storvsc_drv.c:storvsc_host_reset_handler
  - drivers/scsi/storvsc_drv.c:storvsc_channel_init
```
```
In drivers/nvme/host/pci.c (ffffffff8172cb68)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:__nvme_disable_io_queues
```
```
In drivers/ata/libata-core.c (ffffffff8173992f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffffffff81757fee)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/usb/core/message.c (ffffffff8179c61e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817ba44f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/serio/i8042.c (ffffffff828eda18)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
```
In drivers/input/misc/uinput.c (ffffffff817ddafa)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/media/cec/cec-adap.c (ffffffff817e6775)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
```
```
In drivers/md/dm.c (ffffffff818172eb)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-io.c (ffffffff818202e3)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81831540)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpuidle/sysfs.c (ffffffff8183dfe1)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81846c30)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff8184c066)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
```
```
In drivers/hv/vmbus_drv.c (ffffffff828f6d21)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/hv/vmbus_drv.c:hv_acpi_init
```
```
In drivers/hv/connection.c (ffffffff81850175)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/hv/connection.c:vmbus_negotiate_version
```
```
In drivers/hv/channel.c (ffffffff818507d5)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/hv/channel.c:vmbus_teardown_gpadl
  - drivers/hv/channel.c:vmbus_establish_gpadl
  - drivers/hv/channel.c:__vmbus_open
```
```
In drivers/hv/channel_mgmt.c (ffffffff81852698)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:vmbus_onoffer
  - drivers/hv/channel_mgmt.c:vmbus_initiate_unload
```
```
In net/ipv4/inet_fragment.c (ffffffff8195f0cf)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/packet/af_packet.c (ffffffff819e8519)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In kernel/fork.c (ffffffff81099e1d)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff8109b969)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
```
```
In kernel/workqueue.c (ffffffff810bc21f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/kthread.c (ffffffff810c1eee)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
```
```
In kernel/rcu/update.c (ffffffff81119c56)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (ffffffff8111b7cf)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff8111ceaa)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/livepatch/core.c (ffffffff81122803)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/smp.c (ffffffff81145120)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (ffffffff8114ed64)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/stop_machine.c (ffffffff81169d55)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/watchdog.c (ffffffff8118619f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/seccomp.c (ffffffff811872da)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff81196b09)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In mm/memremap.c (ffffffff812cac4c)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/aio.c (ffffffff81334fda)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/io_uring.c (ffffffff8133abb9)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
```
In fs/crypto/crypto.c (ffffffff81340897)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81341262)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134448a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff81346573)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/coredump.c (ffffffff81357dce)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/proc_sysctl.c (ffffffff81373af8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffff813de206)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffff8140b235)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffff81410fd1)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/debugfs/file.c (ffffffff814268ea)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/keys/dh.c (ffffffff81442753)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814ac57f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/api.c (ffffffff814b25d6)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/gcm.c (ffffffff814c4857)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814ca60a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814ce3c8)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In arch/x86/lib/msr-smp.c (ffffffff81551541)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
```
```
In drivers/acpi/device_sysfs.c (ffffffff815ce4b1)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/xen/grant-table.c (ffffffff81657199)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff816620d3)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff816adcd9)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_alloc
```
```
In drivers/char/hw_random/core.c (ffffffff816b91c6)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/base/devtmpfs.c (ffffffff816fcfbe)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
```
In drivers/base/power/main.c (ffffffff817046bb)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff8170d701)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff817311db)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (ffffffff81731f59)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (ffffffff817365af)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81738225)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffff8173a137)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff8176aa66)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (ffffffff817897ff)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffffffff817a85de)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/usb/core/message.c (ffffffff817e76be)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81831d7f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/serio/i8042.c (ffffffff8290a3a9)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8185600a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff818578da)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff818617d5)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff81868cee)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8186a515)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/media/cec/cec-adap.c (ffffffff8186c015)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
```
```
In drivers/md/dm.c (ffffffff8189f30b)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-io.c (ffffffff818a8303)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818b9620)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpuidle/sysfs.c (ffffffff818c5c01)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
```
```
In drivers/mmc/core/core.c (ffffffff818c85d1)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff818e1390)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff818e7666)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
```
```
In net/ipv4/inet_fragment.c (ffffffff81a0feaf)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/packet/af_packet.c (ffffffff81a96ed9)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In kernel/fork.c (ffffffff810a1a86)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff810a35d9)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
```
```
In kernel/workqueue.c (ffffffff810c3321)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/kthread.c (ffffffff810ca4ce)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
```
```
In kernel/rcu/update.c (ffffffff811253c2)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (ffffffff81126a2f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff8112a44a)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/livepatch/core.c (ffffffff8112ee13)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/smp.c (ffffffff81151d00)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (ffffffff8115bb44)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/stop_machine.c (ffffffff81177475)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/watchdog.c (ffffffff81193aef)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/seccomp.c (ffffffff81194c2a)
Location: include/linux/completion.h:85
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff811a4719)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In mm/memremap.c (ffffffff812db980)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/aio.c (ffffffff813451de)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/io_uring.c (ffffffff8134dd69)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
```
In fs/crypto/crypto.c (ffffffff81353b97)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81354562)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8135776a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff81359853)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/coredump.c (ffffffff8136b4ae)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/proc_sysctl.c (ffffffff81387099)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffff813f3626)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffff81420ed5)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffff81426c41)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/debugfs/file.c (ffffffff8143d7aa)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/keys/dh.c (ffffffff81459a83)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814c4fcf)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/api.c (ffffffff814cb056)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/gcm.c (ffffffff814dd327)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff814e30da)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff814e6e98)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In arch/x86/lib/msr-smp.c (ffffffff8156b3a1)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
```
```
In drivers/acpi/device_sysfs.c (ffffffff815e8371)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/xen/grant-table.c (ffffffff81671799)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8167c6a3)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff816c8139)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_alloc
```
```
In drivers/char/hw_random/core.c (ffffffff816d3796)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/base/devtmpfs.c (ffffffff8171784e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
```
In drivers/base/power/main.c (ffffffff8171ef2b)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff817284bb)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff8174c61b)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (ffffffff8174d399)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (ffffffff817519ef)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81753665)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffff81755577)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff817861b6)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (ffffffff817a364f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffffffff817c246e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/usb/core/message.c (ffffffff8180190e)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8184bf5f)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/serio/i8042.c (ffffffff82910874)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8187113a)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff81872948)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187c9e5)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818844a5)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/media/cec/cec-adap.c (ffffffff81885fa5)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_claim_log_addrs
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
```
```
In drivers/md/dm.c (ffffffff818ba433)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-io.c (ffffffff818c4543)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d5900)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpuidle/sysfs.c (ffffffff818e2061)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
```
```
In drivers/mmc/core/core.c (ffffffff818e50f1)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff818fde30)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/completion.h:85
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff819042e6)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1a6ff)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/packet/af_packet.c (ffffffff81aa1f69)
Location: include/linux/completion.h:85
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
</details>
</li>
</ul>

## Differences
