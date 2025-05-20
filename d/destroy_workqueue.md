# Function: <code>destroy_workqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81099500)
Location: kernel/workqueue.c:3910
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/crypto.c:ext4_exit_crypto
  - crypto/crypto_wq.c:crypto_wq_exit
  - block/bio.c:bioset_free
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/thermal.c:acpi_thermal_exit
  - drivers/block/virtio_blk.c:fini
  - drivers/block/virtio_blk.c:init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/power/charger-manager.c:charger_manager_cleanup
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/mmc/core/core.c:mmc_exit
  - drivers/mmc/core/core.c:mmc_init
  - drivers/devfreq/devfreq.c:devfreq_exit
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_cleanup
```
**Symbols:**

```
ffffffff81099500-ffffffff81099710: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109ca80)
Location: kernel/workqueue.c:4008
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/crypto/crypto.c:fscrypt_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - crypto/crypto_wq.c:crypto_wq_exit
  - block/bio.c:bioset_free
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_exit
  - drivers/block/virtio_blk.c:fini
  - drivers/block/virtio_blk.c:init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/power/charger-manager.c:charger_manager_cleanup
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
```
**Symbols:**

```
ffffffff8109ca80-ffffffff8109cc93: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a5040)
Location: kernel/workqueue.c:4036
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/crypto/crypto.c:fscrypt_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - crypto/crypto_wq.c:crypto_wq_exit
  - block/bio.c:bioset_free
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
```
**Symbols:**

```
ffffffff810a5040-ffffffff810a5249: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a21c0)
Location: kernel/workqueue.c:4055
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/crypto/crypto.c:fscrypt_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - crypto/crypto_wq.c:crypto_wq_exit
  - block/bio.c:bioset_free
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/thermal.c:acpi_thermal_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
```
**Symbols:**

```
ffffffff810a21c0-ffffffff810a23b1: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a8a50)
Location: kernel/workqueue.c:4066
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/crypto/crypto.c:fscrypt_exit
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - crypto/crypto_wq.c:crypto_wq_exit
  - block/bio.c:bioset_free
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/thermal.c:acpi_thermal_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/strparser/strparser.c:strp_mod_exit
```
**Symbols:**

```
ffffffff810a8a50-ffffffff810a8c41: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810af0c0)
Location: kernel/workqueue.c:4149
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/crypto/crypto.c:fscrypt_exit
  - fs/crypto/crypto.c:fscrypt_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - crypto/crypto_wq.c:crypto_wq_exit
  - block/bio.c:bioset_exit
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/thermal.c:acpi_thermal_exit
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/strparser/strparser.c:strp_mod_exit
```
**Symbols:**

```
ffffffff810af0c0-ffffffff810af2ad: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b8230)
Location: kernel/workqueue.c:4172
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/crypto/crypto.c:fscrypt_exit
  - fs/crypto/crypto.c:fscrypt_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - crypto/crypto_wq.c:crypto_wq_exit
  - block/bio.c:bioset_exit
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/thermal.c:acpi_thermal_exit
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/strparser/strparser.c:strp_mod_exit
```
**Symbols:**

```
ffffffff810b8230-ffffffff810b841d: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4314
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/io_uring.c:io_finish_async
  - fs/crypto/crypto.c:fscrypt_exit
  - fs/crypto/crypto.c:fscrypt_init
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bio.c:bioset_exit
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/thermal.c:acpi_thermal_exit
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
```
**Symbols:**

```
ffffffff810bf502-ffffffff810bf562: destroy_workqueue.cold (STB_LOCAL)
ffffffff810bdd50-ffffffff810bdf11: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c42a0)
Location: kernel/workqueue.c:4332
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/io_uring.c:io_finish_async
  - fs/io_uring.c:io_finish_async
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_exit_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bio.c:bioset_exit
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_exit
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/vfio/virqfd.c:vfio_virqfd_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
```
**Symbols:**

```
ffffffff810c42a0-ffffffff810c44b9: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4357
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/padata.c:__padata_free
  - kernel/padata.c:__padata_free
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_exit_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bio.c:bioset_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_exit
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/vfio/virqfd.c:vfio_virqfd_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
```
**Symbols:**

```
ffffffff810cd273-ffffffff810cd2c3: destroy_workqueue.cold (STB_LOCAL)
ffffffff810cbf10-ffffffff810cc174: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4370
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/trace/trace.c:trace_eval_sync
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_exit_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bio.c:bioset_init
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_exit
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/vfio/virqfd.c:vfio_virqfd_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
```
**Symbols:**

```
ffffffff81bdc0d4-ffffffff81bdc124: destroy_workqueue.cold (STB_LOCAL)
ffffffff810c7050-ffffffff810c72b4: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4377
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/trace/trace.c:trace_eval_sync
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_exit_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bio.c:bioset_exit
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_exit
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/vfio/virqfd.c:vfio_virqfd_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/mcast.c:igmp6_cleanup
```
**Symbols:**

```
ffffffff81bce1f9-ffffffff81bce249: destroy_workqueue.cold (STB_LOCAL)
ffffffff810c87f0-ffffffff810c8a43: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4416
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/trace/trace.c:trace_eval_sync
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_exit_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bio.c:bioset_exit
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_exit
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit
  - drivers/iommu/io-pgfault.c:iopf_queue_free
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/vfio/virqfd.c:vfio_virqfd_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/mcast.c:igmp6_cleanup
```
**Symbols:**

```
ffffffff81ca5417-ffffffff81ca5467: destroy_workqueue.cold (STB_LOCAL)
ffffffff810db3f0-ffffffff810db61e: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f4b00)
Location: kernel/workqueue.c:4399
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/trace/ftrace.c:ftrace_check_sync
  - kernel/trace/trace.c:trace_eval_sync
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:init_zswap
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_exit_workqueue
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bio.c:bioset_exit
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_exit
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit
  - drivers/iommu/io-pgfault.c:iopf_queue_free
  - drivers/block/loop.c:lo_free_disk
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/vfio/virqfd.c:vfio_virqfd_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/mcast.c:igmp6_cleanup
```
**Symbols:**

```
ffffffff810f4b00-ffffffff810f4d99: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81116f80)
Location: kernel/workqueue.c:4408
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/trace/ftrace.c:ftrace_check_sync
  - kernel/trace/trace.c:trace_eval_sync
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:init_zswap
  - mm/zswap.c:init_zswap
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_exit_workqueue
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bio.c:bioset_exit
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/doe.c:pcim_doe_create_mb
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_exit
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit
  - drivers/iommu/io-pgfault.c:iopf_queue_free
  - drivers/block/loop.c:lo_free_disk
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/remoteproc/remoteproc_core.c:remoteproc_exit
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/mcast.c:igmp6_cleanup
```
**Symbols:**

```
ffffffff81116f80-ffffffff811171e9: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81123f10)
Location: kernel/workqueue.c:4741
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/trace/ftrace.c:ftrace_check_sync
  - kernel/trace/trace.c:trace_eval_sync
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - mm/zswap.c:zswap_setup
  - mm/zswap.c:zswap_setup
  - fs/super.c:sb_init_dio_done_wq
  - fs/super.c:generic_shutdown_super
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_exit_workqueue
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bio.c:bioset_exit
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/doe.c:pci_doe_destroy
  - drivers/pci/doe.c:pci_doe_init
  - drivers/pci/doe.c:pci_doe_create_mb
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_exit
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit
  - drivers/iommu/io-pgfault.c:iopf_queue_free
  - drivers/block/loop.c:lo_free_disk
  - drivers/block/virtio_blk.c:virtio_blk_fini
  - drivers/block/virtio_blk.c:virtio_blk_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-stripe.c:dm_stripe_exit
  - drivers/md/dm-stripe.c:dm_stripe_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/remoteproc/remoteproc_core.c:remoteproc_exit
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/mcast.c:igmp6_cleanup
```
**Symbols:**

```
ffffffff81123f10-ffffffff81124194: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112e590)
Location: kernel/workqueue.c:4776
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/trace/ftrace.c:ftrace_check_sync
  - kernel/trace/trace.c:trace_eval_sync
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - fs/super.c:sb_init_dio_done_wq
  - fs/super.c:generic_shutdown_super
  - fs/crypto/crypto.c:fscrypt_init
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bio.c:bioset_exit
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/pci/hotplug/shpchp_core.c:init_slots
  - drivers/pci/doe.c:pci_doe_destroy
  - drivers/pci/doe.c:pci_doe_init
  - drivers/pci/doe.c:pci_doe_create_mb
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_exit
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit
  - drivers/iommu/io-pgfault.c:iopf_queue_free
  - drivers/block/loop.c:lo_free_disk
  - drivers/block/virtio_blk.c:virtio_blk_fini
  - drivers/block/virtio_blk.c:virtio_blk_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-stripe.c:dm_stripe_exit
  - drivers/md/dm-stripe.c:dm_stripe_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/remoteproc/remoteproc_core.c:remoteproc_exit
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/mcast.c:igmp6_cleanup
```
**Symbols:**

```
ffffffff8112e590-ffffffff8112e89a: destroy_workqueue (STB_GLOBAL)
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
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff800010122538)
Location: kernel/workqueue.c:4332
Inline: False
Direct callers:
  - virt/kvm/eventfd.c:kvm_irqfd_exit
  - kernel/workqueue.c:alloc_workqueue
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/io_uring.c:io_finish_async
  - fs/io_uring.c:io_finish_async
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_exit_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bio.c:bioset_exit
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_exit
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/mmc/core/block.c:mmc_blk_remove
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
```
**Symbols:**

```
ffff800010122538-ffff8000101227a8: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0375f18)
Location: kernel/workqueue.c:4332
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/io_uring.c:io_finish_async
  - fs/io_uring.c:io_finish_async
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_exit_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bio.c:bioset_exit
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/host/sdhci.c:sdhci_remove_host
  - drivers/mmc/host/sdhci.c:__sdhci_add_host
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
```
**Symbols:**

```
c0375f18-c0376128: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c00000000016bfe0)
Location: kernel/workqueue.c:4332
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/io_uring.c:io_finish_async
  - fs/io_uring.c:io_finish_async
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_exit_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bio.c:bioset_exit
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/vfio/virqfd.c:vfio_virqfd_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
```
**Symbols:**

```
c00000000016bfe0-c00000000016c2f4: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000dafa8)
Location: kernel/workqueue.c:4332
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/io_uring.c:io_finish_async
  - fs/io_uring.c:io_finish_async
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_exit_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bio.c:bioset_exit
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/mmc/core/block.c:mmc_blk_remove
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
```
**Symbols:**

```
ffffffe0000dafa8-ffffffe0000db16c: destroy_workqueue (STB_GLOBAL)
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
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810be610)
Location: kernel/workqueue.c:4332
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/io_uring.c:io_finish_async
  - fs/io_uring.c:io_finish_async
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_exit_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bio.c:bioset_exit
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/nvme/host/core.c:nvme_core_exit
  - drivers/nvme/host/core.c:nvme_core_exit
  - drivers/nvme/host/core.c:nvme_core_exit
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
```
**Symbols:**

```
ffffffff810be610-ffffffff810be829: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ace40)
Location: kernel/workqueue.c:4332
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/io_uring.c:io_finish_async
  - fs/io_uring.c:io_finish_async
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_exit_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bio.c:bioset_exit
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/nfit/core.c:nfit_exit
  - drivers/acpi/nfit/core.c:nfit_init
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_transport_fc.c:fc_remove_host
  - drivers/scsi/scsi_transport_fc.c:fc_remove_host
  - drivers/scsi/scsi_transport_fc.c:fc_host_setup
  - drivers/scsi/storvsc_drv.c:storvsc_remove
  - drivers/scsi/storvsc_drv.c:storvsc_probe
  - drivers/nvme/host/core.c:nvme_core_exit
  - drivers/nvme/host/core.c:nvme_core_exit
  - drivers/nvme/host/core.c:nvme_core_exit
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/nvme/host/core.c:nvme_core_init
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/vfio/virqfd.c:vfio_virqfd_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - drivers/hv/connection.c:vmbus_disconnect
  - drivers/hv/connection.c:vmbus_disconnect
  - drivers/hv/connection.c:vmbus_disconnect
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
```
**Symbols:**

```
ffffffff810ace40-ffffffff810ad053: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bdb70)
Location: kernel/workqueue.c:4332
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/io_uring.c:io_finish_async
  - fs/io_uring.c:io_finish_async
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_exit_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bio.c:bioset_exit
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_exit
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/vfio/virqfd.c:vfio_virqfd_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
```
**Symbols:**

```
ffffffff810bdb70-ffffffff810bdd89: destroy_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void destroy_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c5f00)
Location: kernel/workqueue.c:4332
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/padata.c:padata_sysfs_release
  - kernel/padata.c:padata_sysfs_release
  - fs/super.c:generic_shutdown_super
  - fs/direct-io.c:sb_init_dio_done_wq
  - fs/io_uring.c:io_finish_async
  - fs/io_uring.c:io_finish_async
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/verify.c:fsverity_exit_workqueue
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - block/bio.c:bioset_exit
  - drivers/pci/hotplug/shpchp_core.c:cleanup_slots
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/rapidio/rio.c:rio_init_mports
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/osl.c:acpi_os_terminate
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/ec.c:acpi_ec_init
  - drivers/acpi/thermal.c:acpi_thermal_exit
  - drivers/acpi/thermal.c:acpi_thermal_init
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/char/tpm/tpm-dev-common.c:tpm_dev_common_exit
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-sff.c:ata_sff_exit
  - drivers/vfio/virqfd.c:vfio_virqfd_exit
  - drivers/usb/core/hub.c:usb_hub_cleanup
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/power/supply/charger-manager.c:charger_manager_cleanup
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_exit
  - drivers/md/md.c:md_init
  - drivers/md/md.c:md_init
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/edac/wq.c:edac_workqueue_teardown
  - net/sched/cls_api.c:tc_filter_init
  - net/ipv6/addrconf.c:addrconf_cleanup
  - net/ipv6/addrconf.c:addrconf_init
```
**Symbols:**

```
ffffffff810c5f00-ffffffff810c6110: destroy_workqueue (STB_GLOBAL)
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
