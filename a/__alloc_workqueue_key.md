# Function: <code>__alloc_workqueue_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct workqueue_struct *__alloc_workqueue_key(const char *fmt, unsigned int flags, int max_active, struct lock_class_key *key, const char *lock_name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109d5c0)
Location: kernel/workqueue.c:3797
Inline: False
Direct callers:
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/cpuset.c:cpuset_init_smp
  - kernel/events/core.c:perf_workqueue_init
  - mm/vmstat.c:setup_vmstat
  - mm/backing-dev.c:default_bdi_init
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/crypto.c:ext4_init_crypto
  - crypto/crypto_wq.c:crypto_wq_init
  - block/bio.c:__bioset_create
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/block/virtio_blk.c:init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/charger-manager.c:charger_manager_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:dm_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/mmc/core/core.c:mmc_init
  - net/core/net_namespace.c:net_ns_init
  - net/ipv6/addrconf.c:addrconf_init
```
**Symbols:**

```
ffffffff8109d5c0-ffffffff8109da98: __alloc_workqueue_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct workqueue_struct *__alloc_workqueue_key(const char *fmt, unsigned int flags, int max_active, struct lock_class_key *key, const char *lock_name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a0c10)
Location: kernel/workqueue.c:3895
Inline: False
Direct callers:
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:init_workqueues
  - kernel/cpuset.c:cpuset_init_smp
  - mm/swap.c:lru_init
  - mm/vmstat.c:setup_vmstat
  - mm/backing-dev.c:default_bdi_init
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/ext4/super.c:ext4_fill_super
  - crypto/crypto_wq.c:crypto_wq_init
  - block/bio.c:__bioset_create
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/block/virtio_blk.c:init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/charger-manager.c:charger_manager_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - net/core/net_namespace.c:net_ns_init
  - net/ipv6/addrconf.c:addrconf_init
```
**Symbols:**

```
ffffffff810a0c10-ffffffff810a10f5: __alloc_workqueue_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct workqueue_struct *__alloc_workqueue_key(const char *fmt, unsigned int flags, int max_active, struct lock_class_key *key, const char *lock_name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a5ce0)
Location: kernel/workqueue.c:3923
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/cpuset.c:cpuset_init_smp
  - mm/swap.c:lru_init
  - mm/vmstat.c:setup_vmstat
  - mm/backing-dev.c:default_bdi_init
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/ext4/super.c:ext4_fill_super
  - crypto/crypto_wq.c:crypto_wq_init
  - block/bio.c:__bioset_create
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - net/core/net_namespace.c:net_ns_init
  - net/ipv6/addrconf.c:addrconf_init
```
**Symbols:**

```
ffffffff810a5ce0-ffffffff810a61bf: __alloc_workqueue_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct workqueue_struct *__alloc_workqueue_key(const char *fmt, unsigned int flags, int max_active, struct lock_class_key *key, const char *lock_name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a2d40)
Location: kernel/workqueue.c:3932
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:default_bdi_init
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/ext4/super.c:ext4_fill_super
  - crypto/crypto_wq.c:crypto_wq_init
  - block/bio.c:bioset_create
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - net/core/net_namespace.c:net_ns_init
  - net/ipv6/addrconf.c:addrconf_init
```
**Symbols:**

```
ffffffff810a2d40-ffffffff810a319a: __alloc_workqueue_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct workqueue_struct *__alloc_workqueue_key(const char *fmt, unsigned int flags, int max_active, struct lock_class_key *key, const char *lock_name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a9670)
Location: kernel/workqueue.c:3943
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:default_bdi_init
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/ext4/super.c:ext4_fill_super
  - crypto/crypto_wq.c:crypto_wq_init
  - block/bio.c:bioset_create
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - net/core/net_namespace.c:net_ns_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/strparser/strparser.c:strp_mod_init
```
**Symbols:**

```
ffffffff810a9670-ffffffff810a9aaf: __alloc_workqueue_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct workqueue_struct *__alloc_workqueue_key(const char *fmt, unsigned int flags, int max_active, struct lock_class_key *key, const char *lock_name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810afda0)
Location: kernel/workqueue.c:4047
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/power/main.c:pm_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/cgroup/cgroup.c:cgroup_wq_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_wq_init
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:cgwb_init
  - mm/backing-dev.c:default_bdi_init
  - mm/memcontrol.c:mem_cgroup_init
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/crypto/crypto.c:fscrypt_init
  - fs/ext4/super.c:ext4_fill_super
  - crypto/crypto_wq.c:crypto_wq_init
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - drivers/devfreq/devfreq.c:devfreq_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sock_diag.c:sock_diag_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/strparser/strparser.c:strp_mod_init
```
**Symbols:**

```
ffffffff810afda0-ffffffff810b0164: __alloc_workqueue_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct workqueue_struct *__alloc_workqueue_key(const char *fmt, unsigned int flags, int max_active, struct lock_class_key *key, const char *lock_name, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b8f10)
Location: kernel/workqueue.c:4070
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/power/main.c:pm_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init
  - kernel/cgroup/cgroup.c:cgroup_wq_init
  - kernel/cgroup/cgroup-v1.c:cgroup1_wq_init
  - kernel/cgroup/cpuset.c:cpuset_init_smp
  - mm/vmstat.c:init_mm_internals
  - mm/backing-dev.c:cgwb_init
  - mm/backing-dev.c:default_bdi_init
  - mm/memcontrol.c:mem_cgroup_init
  - fs/fs-writeback.c:cgroup_writeback_init
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/crypto/crypto.c:fscrypt_init
  - fs/ext4/super.c:ext4_fill_super
  - crypto/crypto_wq.c:crypto_wq_init
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_dev_init
  - block/blk-throttle.c:throtl_init
  - block/bio-integrity.c:bio_integrity_init
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/osl.c:acpi_os_initialize1
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_init
  - drivers/usb/core/hub.c:usb_hub_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/power/supply/charger-manager.c:charger_manager_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:dm_create
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_setup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/devfreq/devfreq.c:devfreq_init
  - net/core/net_namespace.c:net_ns_init
  - net/core/sock_diag.c:sock_diag_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_init
  - net/strparser/strparser.c:strp_mod_init
```
**Symbols:**

```
ffffffff810b8f10-ffffffff810b92d4: __alloc_workqueue_key (STB_GLOBAL)
```
</details>
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
</ul>
