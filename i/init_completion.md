# Function: <code>init_completion</code>

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
In arch/x86/kernel/hpet.c (ffffffff81062632)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_notify
```
```
In kernel/fork.c (ffffffff8108031e)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/workqueue.c (ffffffff81098dc6)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_work
```
```
In kernel/kthread.c (ffffffff810a0456)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
  - kernel/kthread.c:flush_kthread_worker
  - kernel/kthread.c:flush_kthread_work
```
```
In kernel/rcu/update.c (ffffffff810e34fa)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcu.c (ffffffff810e3fe7)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:__synchronize_srcu
```
```
In kernel/rcu/tree.c (ffffffff810e4b50)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/rcu/tree.c:_rcu_barrier
```
```
In kernel/acct.c (ffffffff8110bfd9)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
```
```
In kernel/stop_machine.c (ffffffff8111fea3)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/trace/ring_buffer.c (ffffffff81149d4b)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In fs/aio.c (ffffffff8125c84b)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
  - fs/aio.c:SyS_io_destroy
```
```
In fs/coredump.c (ffffffff8126f108)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/proc_sysctl.c (ffffffff812848cd)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffff812e3c56)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffff813052d6)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffff8130af29)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81397de0)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/api.c (ffffffff8139c840)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In block/bio.c (ffffffff813b04a6)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - block/bio.c:submit_bio_wait
```
```
In drivers/acpi/device_sysfs.c (ffffffff8147c41e)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/xen/grant-table.c (ffffffff814c5f36)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff814cf394)
Location: include/linux/completion.h:73
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff8151ae10)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/base/devtmpfs.c (ffffffff815530d7)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_create_node
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
```
```
In drivers/base/power/main.c (ffffffff815599d6)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_class.c (ffffffff8155f544)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
```
```
In drivers/misc/bmp085.c (ffffffff81579062)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/misc/bmp085.c:bmp085_update_raw_temperature
  - drivers/misc/bmp085.c:show_pressure
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff81583c87)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (ffffffff815847f0)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (ffffffff81589e0f)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8158b53a)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffff8158d34a)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff815b346d)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (ffffffff815cf99e)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffffffff815e8e44)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_master
```
```
In drivers/usb/core/message.c (ffffffff81610d7f)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81654e33)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/input/serio/i8042.c (ffffffff81fb163e)
Location: include/linux/completion.h:73
Inline: True
```
```
In drivers/input/misc/uinput.c (ffffffff81671ac3)
Location: include/linux/completion.h:73
Inline: True
```
```
In drivers/i2c/i2c-core.c (ffffffff8167b271)
Location: include/linux/completion.h:73
Inline: True
```
```
In drivers/md/dm.c (ffffffff816a352c)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-io.c (ffffffff816ab321)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816b1d9b)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpuidle/sysfs.c (ffffffff816bca85)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
```
```
In drivers/mmc/core/core.c (ffffffff816bf256)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_req
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/completion.h:73
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff816eba84)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
```
```
In net/core/flow.c (ffffffff81735285)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
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
In arch/x86/kernel/hpet.c (ffffffff8106245c)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/fork.c (ffffffff8108215a)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff810833aa)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_create
```
```
In kernel/workqueue.c (ffffffff8109e50b)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/kthread.c (ffffffff810a3cdb)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/kthread.c:flush_kthread_worker
  - kernel/kthread.c:flush_kthread_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
```
```
In kernel/rcu/update.c (ffffffff810e928a)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcu.c (ffffffff810ea2e7)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:__synchronize_srcu
```
```
In kernel/rcu/tree.c (ffffffff810eaf53)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/rcu/tree.c:_rcu_barrier
```
```
In kernel/acct.c (ffffffff8111383a)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
```
```
In kernel/stop_machine.c (ffffffff81127de6)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/trace/ring_buffer.c (ffffffff8115075b)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In fs/aio.c (ffffffff81286040)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/coredump.c (ffffffff8129a8ff)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/proc_sysctl.c (ffffffff812b199d)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffff81313c16)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffff81339574)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffff8133f189)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In security/integrity/ima/ima_crypto.c (ffffffff813d4947)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/api.c (ffffffff813d9720)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/drbg.c (ffffffff813eb8a0)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff813f077c)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/bio.c (ffffffff813f3ef6)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - block/bio.c:submit_bio_wait
```
```
In drivers/acpi/device_sysfs.c (ffffffff814cab5b)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/xen/grant-table.c (ffffffff815165c6)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8151ff9a)
Location: include/linux/completion.h:73
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff8156db40)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/base/devtmpfs.c (ffffffff815a51c6)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
```
In drivers/base/power/main.c (ffffffff815abb46)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_class.c (ffffffff815b40a5)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff815d9d47)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (ffffffff815da8dd)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (ffffffff815debcf)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff815e07ba)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffff815e255a)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff8160b8cf)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (ffffffff816285e4)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffffffff816473be)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_master
```
```
In drivers/usb/core/message.c (ffffffff816711ae)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816b6f3c)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
```
```
In drivers/input/serio/i8042.c (ffffffff81fde16c)
Location: include/linux/completion.h:73
Inline: True
```
```
In drivers/input/misc/uinput.c (ffffffff816d20fd)
Location: include/linux/completion.h:73
Inline: True
```
```
In drivers/i2c/i2c-core.c (ffffffff816dc9a1)
Location: include/linux/completion.h:73
Inline: True
```
```
In drivers/md/dm.c (ffffffff81703dd5)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-io.c (ffffffff8170b861)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81713f2b)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpuidle/sysfs.c (ffffffff8171e57c)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
```
```
In drivers/mmc/core/core.c (ffffffff81721c66)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_req
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/completion.h:73
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff8175057e)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
```
```
In net/core/flow.c (ffffffff817a140c)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
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
In arch/x86/kernel/hpet.c (ffffffff810654cc)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/fork.c (ffffffff81086bba)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff81087fba)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_create
```
```
In kernel/workqueue.c (ffffffff810a3078)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/kthread.c (ffffffff810a8ffb)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
```
```
In kernel/rcu/update.c (ffffffff810f015a)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcu.c (ffffffff810f11c7)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:__synchronize_srcu
```
```
In kernel/rcu/tree.c (ffffffff810f2903)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/rcu/tree.c:_rcu_barrier
```
```
In kernel/smp.c (ffffffff811128b7)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (ffffffff8111af4a)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
```
```
In kernel/stop_machine.c (ffffffff81131a76)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/trace/ring_buffer.c (ffffffff8115b8bb)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In fs/aio.c (ffffffff8129a320)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/coredump.c (ffffffff812af48f)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/proc_sysctl.c (ffffffff812c723d)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffff81329bc6)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffff8134f314)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffff81354f09)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In security/integrity/ima/ima_crypto.c (ffffffff813ec397)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/api.c (ffffffff813f1050)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/drbg.c (ffffffff8140501f)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8140a001)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/bio.c (ffffffff8140d896)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - block/bio.c:submit_bio_wait
```
```
In drivers/acpi/device_sysfs.c (ffffffff814eca7f)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/xen/grant-table.c (ffffffff81542a36)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8154c44a)
Location: include/linux/completion.h:73
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff8159a284)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/base/devtmpfs.c (ffffffff815d3976)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
```
In drivers/base/power/main.c (ffffffff815da8e6)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff81606a37)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (ffffffff816075cd)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (ffffffff8160b85f)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8160d45a)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffff8160f20b)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff8163b16f)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (ffffffff81659254)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffffffff816784ae)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_master
```
```
In drivers/usb/core/message.c (ffffffff8169ee5e)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816e4bdd)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/serio/i8042.c (ffffffff8201bd83)
Location: include/linux/completion.h:73
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81700f55)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff81701f4d)
Location: include/linux/completion.h:73
Inline: True
```
```
In drivers/i2c/i2c-core.c (ffffffff8170cd24)
Location: include/linux/completion.h:73
Inline: True
```
```
In drivers/md/dm.c (ffffffff81735c9a)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-io.c (ffffffff8173d66b)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81745cc2)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpuidle/sysfs.c (ffffffff817510d3)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
```
```
In drivers/mmc/core/core.c (ffffffff81754d54)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_req
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/completion.h:73
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff8177c4cd)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
```
```
In net/core/flow.c (ffffffff817cfd26)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
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
In arch/x86/kernel/hpet.c (ffffffff810643f9)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/fork.c (ffffffff81083903)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/cpu.c (ffffffff81084f3a)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_create
```
```
In kernel/workqueue.c (ffffffff810a03a5)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/kthread.c (ffffffff810a5d9b)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
```
```
In kernel/rcu/update.c (ffffffff810f0108)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (ffffffff810f1601)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff810f452e)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/rcu/tree.c:_rcu_barrier
```
```
In kernel/livepatch/core.c (ffffffff810f80f3)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_register_patch
```
```
In kernel/smp.c (ffffffff81113da7)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (ffffffff8111cb6a)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
```
```
In kernel/stop_machine.c (ffffffff81133046)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/trace/ring_buffer.c (ffffffff8115e7fb)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In fs/aio.c (ffffffff812a805e)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/crypto/crypto.c (ffffffff812ac28f)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812acf28)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
```
In fs/crypto/keyinfo.c (ffffffff812ad898)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_key_aes
```
```
In fs/coredump.c (ffffffff812bc8cf)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/proc_sysctl.c (ffffffff812d44b2)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffff813397b6)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffff81363db5)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffff81369ac9)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In security/keys/dh.c (ffffffff8139608f)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffffffff813f8759)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In crypto/api.c (ffffffff813fd2e0)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/drbg.c (ffffffff81412887)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff81417ac2)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
```
```
In block/bio.c (ffffffff8141b606)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - block/bio.c:submit_bio_wait
```
```
In drivers/acpi/device_sysfs.c (ffffffff814f9153)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/xen/grant-table.c (ffffffff815568f6)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815606f3)
Location: include/linux/completion.h:73
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff815ae254)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/base/devtmpfs.c (ffffffff815e84f6)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_delete_node
  - drivers/base/devtmpfs.c:devtmpfs_create_node
```
```
In drivers/base/power/main.c (ffffffff815ef486)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_class.c (ffffffff815f7d2f)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff8161a837)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (ffffffff8161b4da)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (ffffffff8161f96f)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8162156a)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffff81623309)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff8164ff81)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (ffffffff8166da2e)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffffffff8168cbee)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/usb/core/message.c (ffffffff816b40ed)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816f8b1e)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/serio/i8042.c (ffffffff820fe6f6)
Location: include/linux/completion.h:73
Inline: True
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817167a5)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff817178dd)
Location: include/linux/completion.h:73
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81720180)
Location: include/linux/completion.h:73
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81726e66)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/md/dm.c (ffffffff8174f0d1)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/md/dm-io.c (ffffffff8175732b)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81764332)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
```
In drivers/cpuidle/sysfs.c (ffffffff8176fb73)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_device_sysfs
```
```
In drivers/mmc/core/core.c (ffffffff817728e4)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_areq
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/completion.h:73
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff8179b02d)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
```
```
In net/core/flow.c (ffffffff817ef124)
Location: include/linux/completion.h:73
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush
```
</details>
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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a30f9)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/cpu.c (ffffffff810a4979)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
```
```
In kernel/workqueue.c (ffffffff810c2d4d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/kthread.c (ffffffff810cb046)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
```
```
In kernel/sched/core.c (ffffffff810e0197)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/rcu/update.c (ffffffff8112bcf9)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (ffffffff8112dc94)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff81131e81)
Location: include/linux/completion.h:84
Inline: True
```
```
In kernel/livepatch/core.c (ffffffff811356d2)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
```
In kernel/smp.c (ffffffff8115b250)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (ffffffff81165594)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/stop_machine.c (ffffffff811834ed)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_one_cpu
```
```
In kernel/watchdog.c (ffffffff811a19cf)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/seccomp.c (ffffffff811a2b6e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_addfd
```
```
In kernel/trace/ring_buffer.c (ffffffff811b4899)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/padata.c (ffffffff82fe4ef1)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_multithreaded
```
```
In mm/zswap.c (ffffffff812ccb2e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/memremap.c (ffffffff813166ac)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/aio.c (ffffffff81386b8e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/io_uring.c (ffffffff8138e2f6)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_files_register
  - fs/io_uring.c:io_ring_ctx_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In fs/io-wq.c (ffffffff8139c5eb)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
```
```
In fs/crypto/crypto.c (ffffffff813a1587)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813a1c83)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813a563a)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff813a8ab8)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/coredump.c (ffffffff813b8c20)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/proc_sysctl.c (ffffffff813d9fdd)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffff8144e016)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffff8147f425)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffff81484bd1)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/debugfs/file.c (ffffffff8149fc07)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/keys/dh.c (ffffffff814bdd45)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffffffff815340fa)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/api.c (ffffffff8153b736)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/gcm.c (ffffffff8154d19a)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff81552ac9)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815560e1)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In block/blk-crypto-fallback.c (ffffffff8159f373)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In arch/x86/lib/msr-smp.c (ffffffff8160bd41)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
```
```
In drivers/acpi/device_sysfs.c (ffffffff816a2344)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/xen/grant-table.c (ffffffff8172f699)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8173b4a7)
Location: include/linux/completion.h:84
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff81788c69)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_alloc
```
```
In drivers/char/hw_random/core.c (ffffffff81794416)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/iommu/intel/svm.c (ffffffff817b653c)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/base/devtmpfs.c (ffffffff817d8d55)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_submit_req
```
```
In drivers/base/power/main.c (ffffffff817e128b)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff817ea02e)
Location: include/linux/completion.h:84
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff8180d8eb)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (ffffffff81c125fc)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (ffffffff818123ff)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81813a75)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffff818153a7)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff8184a2b4)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_prep_async_scan
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (ffffffff81868ddf)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffffffff81889c88)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/usb/core/message.c (ffffffff818ce4e1)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8191750d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/serio/i8042.c (ffffffff83011af8)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_check_aux
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193c71a)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff8193dc4a)
Location: include/linux/completion.h:84
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81947995)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8194f385)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/md/dm.c (ffffffff8197e9db)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-io.c (ffffffff819875b3)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81996b49)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
```
In drivers/cpuidle/sysfs.c (ffffffff819a5e30)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
```
```
In drivers/mmc/core/core.c (ffffffff819a8bf1)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819c1530)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819c5784)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/completion.h:84
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff819c7cc6)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
```
```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff819cafee)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
```
In net/ipv4/inet_fragment.c (ffffffff81b01e0f)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/packet/af_packet.c (ffffffff81b98bc9)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In kernel/fork.c (ffffffff810a3c77)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/cpu.c (ffffffff810a563e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
```
```
In kernel/workqueue.c (ffffffff810c4b5d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/kthread.c (ffffffff810cc9b6)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
```
```
In kernel/sched/core.c (ffffffff810e1f7e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/rcu/update.c (ffffffff8112c189)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (ffffffff8112e1e4)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff81132611)
Location: include/linux/completion.h:84
Inline: True
```
```
In kernel/livepatch/core.c (ffffffff81136582)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
```
In kernel/smp.c (ffffffff8115c5e0)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (ffffffff81166364)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/stop_machine.c (ffffffff8118461d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_one_cpu
```
```
In kernel/watchdog.c (ffffffff811a269f)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/seccomp.c (ffffffff811a363d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_addfd
```
```
In kernel/trace/ring_buffer.c (ffffffff811b3c59)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/padata.c (ffffffff831ef61c)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_multithreaded
```
```
In mm/zswap.c (ffffffff812d36fe)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/memremap.c (ffffffff8131c8fc)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/aio.c (ffffffff8138e00e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/io_uring.c (ffffffff8139b0b2)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_exit_work
  - fs/io_uring.c:io_get_sq_data
  - fs/io_uring.c:io_rsrc_data_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In fs/io-wq.c (ffffffff813a3965)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:create_io_worker
```
```
In fs/crypto/crypto.c (ffffffff813a871a)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813a8e23)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813ac71a)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff813afb28)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/coredump.c (ffffffff813bfd20)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/proc_sysctl.c (ffffffff813e0e2d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffff81453ad6)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffff81484db8)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffff8148a681)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/debugfs/file.c (ffffffff814a5bff)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/keys/dh.c (ffffffff814c3bb5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153d0f2)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/api.c (ffffffff81543e2d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/gcm.c (ffffffff81555115)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8155b389)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8155e843)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In block/blk-crypto-fallback.c (ffffffff815a607a)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In arch/x86/lib/msr-smp.c (ffffffff815ef021)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
```
```
In drivers/acpi/device_sysfs.c (ffffffff81685034)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/xen/grant-table.c (ffffffff817130e9)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171eff7)
Location: include/linux/completion.h:84
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff8176c459)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_alloc
```
```
In drivers/char/hw_random/core.c (ffffffff817770e6)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/iommu/intel/svm.c (ffffffff817997cf)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/base/devtmpfs.c (ffffffff817bd125)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_submit_req
```
```
In drivers/base/power/main.c (ffffffff817c569b)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff817ce73e)
Location: include/linux/completion.h:84
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff817f20cb)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (ffffffff81c04778)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (ffffffff817f6b3f)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff817f8195)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffff817f9a87)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff8182e1d6)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (ffffffff8184b80f)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffffffff8186c598)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/vfio/vfio.c (ffffffff8188ce05)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init_group_dev
```
```
In drivers/usb/core/message.c (ffffffff818b17b4)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818fa99d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/serio/i8042.c (ffffffff8321cab6)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_check_aux
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8191ffb1)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff8192157a)
Location: include/linux/completion.h:84
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8192b2a5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819337f5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/md/dm.c (ffffffff8196282b)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-io.c (ffffffff8196bc83)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197b8a9)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
```
In drivers/cpuidle/sysfs.c (ffffffff8198aaa0)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
```
```
In drivers/mmc/core/core.c (ffffffff8198d8c1)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819a5920)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819aa754)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/completion.h:84
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff819acc06)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
```
```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff819b01a3)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
```
In net/core/selftests.c (ffffffff81a36695)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/core/selftests.c:__net_test_loopback
```
```
In net/ipv4/inet_fragment.c (ffffffff81aed71f)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/packet/af_packet.c (ffffffff81b87abd)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In kernel/fork.c (ffffffff810b5494)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/cpu.c (ffffffff810b6e5c)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_create
  - kernel/cpu.c:cpuhp_create
```
```
In kernel/workqueue.c (ffffffff810d779d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/kthread.c (ffffffff810e0036)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread
  - kernel/kthread.c:kthread
```
```
In kernel/sched/core.c (ffffffff810f822f)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/rcu/update.c (ffffffff8114cd19)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (ffffffff8114f694)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff81154375)
Location: include/linux/completion.h:84
Inline: True
```
```
In kernel/livepatch/core.c (ffffffff81159191)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
```
In kernel/smp.c (ffffffff81181700)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (ffffffff8118bb24)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/stop_machine.c (ffffffff811ac94d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_one_cpu
```
```
In kernel/watchdog.c (ffffffff811cbe7f)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/seccomp.c (ffffffff811ccd1d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_addfd
```
```
In kernel/trace/ring_buffer.c (ffffffff811ddc1e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/padata.c (ffffffff832d4d4d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_multithreaded
```
```
In mm/swapfile.c (ffffffff81312ed0)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/zswap.c (ffffffff813191e1)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/memremap.c (ffffffff81369c3c)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/aio.c (ffffffff813db87e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/io_uring.c (ffffffff813e9d7e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_exit_work
  - fs/io_uring.c:io_get_sq_data
  - fs/io_uring.c:io_rsrc_data_alloc
  - fs/io_uring.c:io_ring_ctx_alloc
```
```
In fs/io-wq.c (ffffffff813f2eb7)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:create_io_worker
```
```
In fs/crypto/crypto.c (ffffffff813f7e5a)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff813f85b3)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff813fc08a)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff813ff718)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/coredump.c (ffffffff8140fb50)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/proc_sysctl.c (ffffffff814328dd)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffff814a7b76)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffff814dc438)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffff814e1e81)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/debugfs/file.c (ffffffff814fdd9f)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/keys/dh.c (ffffffff8151c585)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8159bf72)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/api.c (ffffffff815a45cd)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/gcm.c (ffffffff815b6145)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff815bbd29)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff815bfb9c)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In block/blk-crypto-fallback.c (ffffffff8160eb9a)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In arch/x86/lib/msr-smp.c (ffffffff8165c131)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
```
```
In drivers/acpi/device_sysfs.c (ffffffff816fa2f4)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/xen/grant-table.c (ffffffff8178fba9)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8179de17)
Location: include/linux/completion.h:84
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff817f1b99)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_alloc
```
```
In drivers/char/hw_random/core.c (ffffffff817fce76)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/iommu/intel/svm.c (ffffffff81821d1c)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/base/devtmpfs.c (ffffffff818474a5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_submit_req
```
```
In drivers/base/power/main.c (ffffffff8184fa1b)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff81858fee)
Location: include/linux/completion.h:84
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff8187ad3b)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (ffffffff81d078be)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (ffffffff8187fe4f)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff818815a5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffff81882f37)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff818b9fa6)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (ffffffff818d8ccf)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffffffff818fc40e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/vfio/vfio.c (ffffffff819202e5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init_group_dev
```
```
In drivers/usb/core/message.c (ffffffff81946a04)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8199974d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/serio/i8042.c (ffffffff819b356b)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_check_aux
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c2c51)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff819c43b8)
Location: include/linux/completion.h:84
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819ce486)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d6bc5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/md/dm.c (ffffffff81a09a63)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-io.c (ffffffff81a14143)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a24c39)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
```
In drivers/cpuidle/sysfs.c (ffffffff81a3557c)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
```
```
In drivers/mmc/core/core.c (ffffffff81a38f15)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81a52f43)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81a58194)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/completion.h:84
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff81a5b116)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_request_channel
```
```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81a5e813)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
```
In net/core/selftests.c (ffffffff81aec375)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/core/selftests.c:__net_test_loopback
```
```
In net/core/devlink.c (ffffffff81af6136)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff81badadf)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/packet/af_packet.c (ffffffff81c53fdd)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810cb800)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/cpu.c (ffffffff8347abd0)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/cpu.c:cpuhp_threads_init
```
```
In kernel/workqueue.c (ffffffff810f1fcd)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_workqueue
```
```
In kernel/kthread.c (ffffffff810fadb5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:set_kthread_struct
  - kernel/kthread.c:set_kthread_struct
```
```
In kernel/sched/core.c (ffffffff811144f4)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/rcu/update.c (ffffffff811731d5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (ffffffff811771c8)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__synchronize_srcu
```
```
In kernel/rcu/tree.c (ffffffff8117a49e)
Location: include/linux/completion.h:84
Inline: True
```
```
In kernel/livepatch/core.c (ffffffff8118275f)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
```
In kernel/smp.c (ffffffff811b7d10)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (ffffffff811baec7)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/stop_machine.c (ffffffff811de483)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_one_cpu
```
```
In kernel/watchdog.c (ffffffff811ffc1e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/seccomp.c (ffffffff81200aa1)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_addfd
```
```
In kernel/trace/ring_buffer.c (ffffffff81214d65)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/padata.c (0)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_multithreaded
```
```
In mm/swapfile.c (ffffffff8137db14)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/zswap.c (ffffffff81384421)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/memremap.c (ffffffff813e7909)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/aio.c (ffffffff814630ad)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/crypto/crypto.c (ffffffff8146ab9a)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff8146b253)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8146f4ab)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff81473361)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/coredump.c (ffffffff81484707)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/proc_sysctl.c (ffffffff814abf89)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffff8152f426)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffff8156a240)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffff815700bc)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/debugfs/file.c (ffffffff8158e9ab)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/keys/dh.c (ffffffff815af64c)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81640f4c)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/api.c (ffffffff8164afe5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/gcm.c (ffffffff8165f403)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff816655e8)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff8166a0e6)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In block/blk-mq.c (ffffffff816849a1)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - block/blk-mq.c:blk_execute_rq
```
```
In block/blk-crypto-fallback.c (ffffffff816c333e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In io_uring/io_uring.c (ffffffff81e92252)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_get_sq_data
  - io_uring/io_uring.c:io_rsrc_data_alloc
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In io_uring/io-wq.c (ffffffff816dba10)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:create_io_worker
```
```
In arch/x86/lib/msr-smp.c (ffffffff817750e1)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
```
```
In drivers/acpi/device_sysfs.c (ffffffff818276d4)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/acpi/acpi_pcc.c (ffffffff81843064)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup
```
```
In drivers/xen/grant-table.c (ffffffff818c80b0)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff818d780a)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node
```
```
In drivers/tty/serdev/core.c (ffffffff819322e5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_alloc
```
```
In drivers/char/hw_random/core.c (ffffffff8193bda5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/iommu/intel/svm.c (ffffffff81961ecc)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/base/devtmpfs.c (ffffffff8198bb75)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_submit_req
```
```
In drivers/base/power/main.c (ffffffff819952cb)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff8199f7d5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff819c3527)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (ffffffff81ed01be)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (ffffffff819c844f)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff819c9ddd)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffff819cb907)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/scsi_scan.c (ffffffff81a059b5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (ffffffff81a29e33)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffffffff81a4dab9)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/vfio/vfio.c (ffffffff81a76025)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_init_group_dev
```
```
In drivers/usb/core/message.c (ffffffff81a9f4e5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af6747)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/serio/i8042.c (ffffffff81b127bd)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_check_aux
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b230a5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff81b23f02)
Location: include/linux/completion.h:84
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b2ff2e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b39705)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/md/dm.c (ffffffff81b7138b)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-io.c (ffffffff81b7c971)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b8e3cb)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
```
In drivers/cpuidle/sysfs.c (ffffffff81ba1f6c)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
```
```
In drivers/mmc/core/core.c (ffffffff81ba5fc4)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81bc18cf)
Location: include/linux/completion.h:84
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
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81bc7d46)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/completion.h:84
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff81bcae0a)
Location: include/linux/completion.h:84
Inline: True
```
```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81bceab5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
```
In net/core/selftests.c (ffffffff81c6ed25)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/core/selftests.c:__net_test_loopback
```
```
In net/core/devlink.c (ffffffff81c762aa)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff81d40b3f)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/packet/af_packet.c (ffffffff81df3383)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In kernel/fork.c (ffffffff810e8dd1)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/cpu.c (ffffffff83ea56cc)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/cpu.c:cpuhp_threads_init
```
```
In kernel/workqueue.c (ffffffff81112dfd)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_workqueue
```
```
In kernel/kthread.c (ffffffff8111dc15)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:set_kthread_struct
  - kernel/kthread.c:set_kthread_struct
```
```
In kernel/sched/core.c (ffffffff8113b834)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/rcu/update.c (ffffffff811aae55)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (ffffffff811ae8b8)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__synchronize_srcu
```
```
In kernel/rcu/tree.c (ffffffff811b334e)
Location: include/linux/completion.h:84
Inline: True
```
```
In kernel/livepatch/core.c (ffffffff811bd45c)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
```
In kernel/smp.c (ffffffff811f8fb0)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (ffffffff811fcc87)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/stop_machine.c (ffffffff81223fd3)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_machine_from_inactive_cpu
  - kernel/stop_machine.c:stop_core_cpuslocked
  - kernel/stop_machine.c:stop_machine_cpuslocked
  - kernel/stop_machine.c:stop_two_cpus
  - kernel/stop_machine.c:stop_one_cpu
```
```
In kernel/watchdog.c (ffffffff8124767e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/seccomp.c (ffffffff812487d1)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_addfd
```
```
In kernel/trace/ring_buffer.c (ffffffff8125e425)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/padata.c (ffffffff83eb9ad1)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_multithreaded
```
```
In mm/swapfile.c (ffffffff813fadcc)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/zswap.c (ffffffff81401f71)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/memremap.c (ffffffff8146f582)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/aio.c (ffffffff814f377d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/crypto/crypto.c (ffffffff814fbcb7)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff814fc6d3)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff81500c2b)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/verity/hash_algs.c (ffffffff815051f1)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_hash_page
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In fs/coredump.c (ffffffff81517c07)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/proc_sysctl.c (ffffffff81542769)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffff815cd626)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffff8160dfd0)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffff81614fac)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/debugfs/file.c (ffffffff81635a3b)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/keys/dh.c (ffffffff81659e6d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/apparmor/notify.c (ffffffff816eadd8)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_do_notification
```
```
In security/integrity/ima/ima_crypto.c (ffffffff816f8ebc)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/api.c (ffffffff817041f6)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/gcm.c (ffffffff81718833)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff817203f8)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In crypto/asymmetric_keys/public_key.c (ffffffff817246b1)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
```
```
In block/blk-mq.c (ffffffff81742d31)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - block/blk-mq.c:blk_execute_rq
```
```
In block/blk-crypto-fallback.c (ffffffff817847ce)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In io_uring/io_uring.c (ffffffff8178f748)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In io_uring/sqpoll.c (ffffffff8179a11b)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In io_uring/rsrc.c (ffffffff817a0717)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_data_alloc
```
```
In io_uring/io-wq.c (ffffffff817a7af1)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:create_io_worker
```
```
In arch/x86/lib/msr-smp.c (ffffffff818a5c51)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
```
```
In drivers/acpi/device_sysfs.c (ffffffff81959684)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/acpi/acpi_pcc.c (ffffffff8197a229)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup
```
```
In drivers/xen/grant-table.c (ffffffff81a196a0)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a29dba)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node
```
```
In drivers/tty/serdev/core.c (ffffffff81a90db5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_alloc
```
```
In drivers/char/hw_random/core.c (ffffffff81a9c5c5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/iommu/intel/svm.c (ffffffff81acac20)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/base/devtmpfs.c (ffffffff81afb225)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_submit_req
```
```
In drivers/base/power/main.c (ffffffff81b05dab)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b11275)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff81b399a7)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (ffffffff81b3a9fb)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (ffffffff81b3f06f)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81b4124d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffff81b43482)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/hosts.c (ffffffff81b76e7e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b84709)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (ffffffff81baca3e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffffffff81bd7fd9)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/usb/core/message.c (ffffffff81c24965)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c840e7)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/serio/i8042.c (ffffffff81ca34ed)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_check_aux
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb5937)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff81cb72d2)
Location: include/linux/completion.h:84
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc44ce)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81cced95)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/md/dm.c (ffffffff81d0e1c2)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-io.c (ffffffff81d1a82d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d2ddf8)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
```
In drivers/cpuidle/sysfs.c (ffffffff81d43e5c)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
```
```
In drivers/mmc/core/core.c (ffffffff81d48314)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81d66219)
Location: include/linux/completion.h:84
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
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81d70967)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/completion.h:84
Inline: True
```
```
In drivers/mailbox/pcc.c (ffffffff81d745a7)
Location: include/linux/completion.h:84
Inline: True
```
```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81d79a35)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
```
In net/core/selftests.c (ffffffff81e26a75)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/core/selftests.c:__net_test_loopback
```
```
In net/core/devlink.c (ffffffff81e2ea3e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc_ns
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0986f)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/packet/af_packet.c (ffffffff81fc8143)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In kernel/fork.c (ffffffff810f49d0)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/cpu.c (ffffffff836c9afc)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/cpu.c:cpuhp_threads_init
```
```
In kernel/workqueue.c (ffffffff8111f18d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_workqueue
```
```
In kernel/kthread.c (ffffffff8112ae05)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:set_kthread_struct
  - kernel/kthread.c:set_kthread_struct
```
```
In kernel/vhost_task.c (ffffffff8113915d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/vhost_task.c:vhost_task_create
```
```
In kernel/sched/core.c (ffffffff8114eca0)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/rcu/update.c (ffffffff811bcd5c)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (ffffffff811c0886)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__synchronize_srcu
```
```
In kernel/rcu/tree.c (ffffffff811c4eae)
Location: include/linux/completion.h:84
Inline: True
```
```
In kernel/livepatch/core.c (ffffffff811cfc67)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
```
In kernel/module/main.c (ffffffff811e05b5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/module/main.c:idempotent_init_module
```
```
In kernel/smp.c (ffffffff8120dc60)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (ffffffff81211e23)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/stop_machine.c (ffffffff812393c5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/watchdog.c (ffffffff8125eaae)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/seccomp.c (ffffffff8125fbc1)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_addfd
```
```
In kernel/trace/ring_buffer.c (ffffffff81275605)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/bpf/cpumap.c (ffffffff8134fa65)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/padata.c (ffffffff836df11f)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_multithreaded
```
```
In mm/swapfile.c (ffffffff8142de1c)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/zswap.c (ffffffff81434e71)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/memremap.c (ffffffff814a3d72)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/aio.c (ffffffff8152a54d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/crypto/crypto.c (ffffffff81532fe7)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
```
```
In fs/crypto/fname.c (ffffffff81533c43)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff815382ba)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/coredump.c (ffffffff8154f4f7)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/proc_sysctl.c (ffffffff8157a8cb)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffff81605106)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffff81645e3c)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffff8164d02c)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/debugfs/file.c (ffffffff8166dd43)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/keys/dh.c (ffffffff816923ff)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/apparmor/notify.c (ffffffff81724a70)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_do_notification
```
```
In security/integrity/ima/ima_crypto.c (ffffffff817330c3)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/api.c (ffffffff8173e0f6)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/akcipher.c (ffffffff81747667)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_prep
```
```
In crypto/gcm.c (ffffffff817541a3)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8175bced)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-mq.c (ffffffff81780527)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - block/blk-mq.c:blk_execute_rq
```
```
In block/blk-crypto-fallback.c (ffffffff817c4b4e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In io_uring/io_uring.c (ffffffff817d0a78)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In io_uring/sqpoll.c (ffffffff817db17b)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In io_uring/io-wq.c (ffffffff817e89ab)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:create_io_worker
```
```
In arch/x86/lib/msr-smp.c (ffffffff818e8a71)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
```
```
In drivers/acpi/device_sysfs.c (ffffffff8199fae4)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/acpi/acpi_pcc.c (ffffffff819c0cb9)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup
```
```
In drivers/xen/grant-table.c (ffffffff81a625c0)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a73520)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node
```
```
In drivers/tty/serdev/core.c (ffffffff81adc5c5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_alloc
```
```
In drivers/char/hw_random/core.c (ffffffff81ae7f25)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/iommu/intel/svm.c (ffffffff81b17770)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/base/devtmpfs.c (ffffffff81b49615)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_submit_req
```
```
In drivers/base/power/main.c (ffffffff81b53dbb)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b5f5aa)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff81b8cdf5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (ffffffff81b8de66)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (ffffffff81b924ef)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81b945bd)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffff81b967f2)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/hosts.c (ffffffff81bcab0e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd8479)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (ffffffff81c03beb)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/spi/spi.c (ffffffff81c2ea09)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/usb/core/message.c (ffffffff81c8bab7)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81ceade7)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/serio/i8042.c (ffffffff81d0abad)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_check_aux
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1cfa5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff81d1e972)
Location: include/linux/completion.h:84
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2c13e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d36e76)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/md/dm.c (ffffffff81d777c2)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-io.c (ffffffff81d8398d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d97068)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
```
In drivers/cpuidle/sysfs.c (ffffffff81dae0cc)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
```
```
In drivers/mmc/core/core.c (ffffffff81db2c14)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81dd1329)
Location: include/linux/completion.h:84
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
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81dde627)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
```
```
In drivers/mailbox/mailbox.c (ffffffff81de1d65)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_bind_client
```
```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81de7a65)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
```
In net/core/selftests.c (ffffffff81e9c015)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/core/selftests.c:__net_test_loopback
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6937f)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/packet/af_packet.c (ffffffff82028273)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In kernel/fork.c (ffffffff810fdd70)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/cpu.c (ffffffff838fa76c)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/cpu.c:cpuhp_threads_init
```
```
In kernel/workqueue.c (ffffffff8112943d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_workqueue
```
```
In kernel/kthread.c (ffffffff81135525)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:set_kthread_struct
  - kernel/kthread.c:set_kthread_struct
```
```
In kernel/vhost_task.c (ffffffff81143f1c)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/vhost_task.c:vhost_task_create
```
```
In kernel/sched/core.c (ffffffff8115ab2b)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/rcu/update.c (ffffffff811cd17c)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/update.c:__wait_rcu_gp
```
```
In kernel/rcu/srcutree.c (ffffffff811d0d66)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__synchronize_srcu
```
```
In kernel/rcu/tree.c (ffffffff811d7e5e)
Location: include/linux/completion.h:84
Inline: True
```
```
In kernel/livepatch/core.c (ffffffff811e48b7)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
```
In kernel/module/main.c (ffffffff811f62e5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/module/main.c:idempotent_init_module
```
```
In kernel/smp.c (ffffffff812253f0)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_on_cpu
```
```
In kernel/acct.c (ffffffff812294ce)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/stop_machine.c (ffffffff81253095)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stop_init_done
```
```
In kernel/watchdog.c (ffffffff81278abe)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
```
In kernel/seccomp.c (ffffffff81279d11)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_addfd
```
```
In kernel/trace/ring_buffer.c (ffffffff8128fcb5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/bpf/cpumap.c (ffffffff81376f75)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
```
In kernel/padata.c (ffffffff8391175f)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_multithreaded
```
```
In mm/shrinker.c (ffffffff813e3aa0)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - mm/shrinker.c:shrinker_register
```
```
In mm/swapfile.c (ffffffff814678dc)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
```
```
In mm/zswap.c (ffffffff8146ddd4)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
```
In mm/memremap.c (ffffffff814d4c12)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/aio.c (ffffffff8155f41d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:exit_aio
```
```
In fs/crypto/crypto.c (ffffffff81567ee7)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_crypt_data_unit
```
```
In fs/crypto/fname.c (ffffffff81568bd3)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d40a)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
```
```
In fs/coredump.c (ffffffff81585337)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/proc_sysctl.c (ffffffff815b31af)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
```
In fs/ext4/sysfs.c (ffffffff8163ddc6)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_register_sysfs
```
```
In fs/ecryptfs/crypto.c (ffffffff8167f2fc)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/kthread.c (ffffffff8168655c)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_privileged_open
```
```
In fs/debugfs/file.c (ffffffff816a84d8)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In security/keys/dh.c (ffffffff816ce9cf)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/apparmor/notify.c (ffffffff81765ba0)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_do_notification
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81773ad3)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
```
```
In crypto/api.c (ffffffff8177ef85)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/akcipher.c (ffffffff817894d7)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/akcipher.c:crypto_akcipher_sync_prep
```
```
In crypto/gcm.c (ffffffff81795b13)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
```
In crypto/drbg.c (ffffffff8179dbed)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_init_sym_kernel
```
```
In block/blk-mq.c (ffffffff817c2af7)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - block/blk-mq.c:blk_execute_rq
```
```
In block/blk-crypto-fallback.c (ffffffff8180983e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
```
In io_uring/io_uring.c (ffffffff81814368)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In io_uring/sqpoll.c (ffffffff8181f49a)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In io_uring/io-wq.c (ffffffff8182e78c)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:create_io_worker
```
```
In arch/x86/lib/msr-smp.c (ffffffff8192ff11)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - arch/x86/lib/msr-smp.c:rdmsr_safe_on_cpu
```
```
In drivers/acpi/device_sysfs.c (ffffffff819e8164)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
```
```
In drivers/acpi/acpi_pcc.c (ffffffff81a0b6d9)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup
```
```
In drivers/xen/grant-table.c (ffffffff81ab4df0)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_unmap_refs_sync
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81ac567f)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node
```
```
In drivers/tty/serdev/core.c (ffffffff81b2f8e4)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_alloc
```
```
In drivers/char/hw_random/core.c (ffffffff81b3b395)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_register
```
```
In drivers/iommu/intel/svm.c (ffffffff81b6cd60)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/base/devtmpfs.c (ffffffff81ba1a05)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/base/devtmpfs.c:devtmpfs_submit_req
```
```
In drivers/base/power/main.c (ffffffff81bac50b)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_sleep_init
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb2fb9)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff81be0d24)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/wm8350-core.c (ffffffff81be1d86)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/twl6040.c (ffffffff81be648f)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81be858d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_sync
```
```
In drivers/mfd/da9052-core.c (ffffffff81bea7c2)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mfd/da9052-core.c:da9052_device_init
```
```
In drivers/scsi/hosts.c (ffffffff81c1f73e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2d178)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/ata/libata-core.c (ffffffff81c593cb)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_alloc
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc3e5e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
```
```
In drivers/spi/spi.c (ffffffff81ce178e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/usb/core/message.c (ffffffff81d40567)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81da05b5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
```
```
In drivers/input/serio/i8042.c (ffffffff81dc083d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_check_aux
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd2cf7)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff81dd4672)
Location: include/linux/completion.h:84
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de2011)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ded086)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/thermal/thermal_core.c (ffffffff81dff05e)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
```
```
In drivers/md/dm.c (ffffffff81e2e9f2)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/md/dm-io.c (ffffffff81e3b06d)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/md/dm-io.c:sync_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e4ecf7)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
```
In drivers/cpuidle/sysfs.c (ffffffff81e661eb)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
```
```
In drivers/mmc/core/core.c (ffffffff81e6afa4)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req
  - drivers/mmc/core/core.c:mmc_start_request
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81e8a0a2)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:__efi_queue_work
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81e94536)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
```
```
In drivers/mailbox/mailbox.c (ffffffff81e97d25)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_bind_client
```
```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81e9dcc5)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump
```
```
In net/core/selftests.c (ffffffff81f5e7a4)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/core/selftests.c:__net_test_loopback
```
```
In net/ipv4/inet_fragment.c (ffffffff8202f9ff)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/packet/af_packet.c (ffffffff820f7ad3)
Location: include/linux/completion.h:84
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
