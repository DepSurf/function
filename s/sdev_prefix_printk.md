# Function: <code>sdev_prefix_printk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff815b7ce0)
Location: drivers/scsi/scsi_logging.c:96
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/scsi_dh.c:store_dh_state
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
```
**Symbols:**

```
ffffffff815b7ce0-ffffffff815b7df2: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81610570)
Location: drivers/scsi/scsi_logging.c:96
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81610570-ffffffff81610675: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8163fe00)
Location: drivers/scsi/scsi_logging.c:96
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff8163fe00-ffffffff8163ff05: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81654830)
Location: drivers/scsi/scsi_logging.c:96
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81654830-ffffffff81654938: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff816bdd80)
Location: drivers/scsi/scsi_logging.c:96
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff816bdd80-ffffffff816bde88: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff816fa350)
Location: drivers/scsi/scsi_logging.c:96
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff816fa350-ffffffff816fa445: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8171cd90)
Location: drivers/scsi/scsi_logging.c:96
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff8171cd90-ffffffff8171ce85: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:95
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81759083-ffffffff81759096: sdev_prefix_printk.cold (STB_LOCAL)
ffffffff81758360-ffffffff81758458: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:53
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff8177cfd7-ffffffff8177cfde: sdev_prefix_printk.cold (STB_LOCAL)
ffffffff8177c310-ffffffff8177c41f: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:53
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_print_capacity
  - drivers/scsi/sd.c:sd_print_capacity
  - drivers/scsi/sd.c:sd_print_capacity
  - drivers/scsi/sd.c:sd_print_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl_common
  - drivers/scsi/sd.c:sd_ioctl_common
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_capacity
  - drivers/scsi/sd_zbc.c:sd_zbc_check_capacity
  - drivers/scsi/sd_zbc.c:sd_zbc_check_capacity
  - drivers/scsi/sd_zbc.c:sd_zbc_check_capacity
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81840638-ffffffff8184063f: sdev_prefix_printk.cold (STB_LOCAL)
ffffffff8183fdb0-ffffffff8183feb7: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:53
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_print_capacity
  - drivers/scsi/sd.c:sd_print_capacity
  - drivers/scsi/sd.c:sd_print_capacity
  - drivers/scsi/sd.c:sd_print_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl_common
  - drivers/scsi/sd.c:sd_ioctl_common
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:max_retries_store
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_capacity
  - drivers/scsi/sd_zbc.c:sd_zbc_check_capacity
  - drivers/scsi/sd_zbc.c:sd_zbc_check_capacity
  - drivers/scsi/sd_zbc.c:sd_zbc_check_capacity
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81c16c1e-ffffffff81c16c25: sdev_prefix_printk.cold (STB_LOCAL)
ffffffff81850410-ffffffff81850517: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:53
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl_common
  - drivers/scsi/sd.c:sd_ioctl_common
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:max_retries_store
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81c08a67-ffffffff81c08a6e: sdev_prefix_printk.cold (STB_LOCAL)
ffffffff818334a0-ffffffff818335a7: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:54
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_resume_runtime
  - drivers/scsi/sd.c:sd_resume_runtime
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:max_retries_store
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81d0cb4c-ffffffff81d0cb53: sdev_prefix_printk.cold (STB_LOCAL)
ffffffff818bf4f0-ffffffff818bf5f7: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81a0b970)
Location: drivers/scsi/scsi_logging.c:56
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_resume_runtime
  - drivers/scsi/sd.c:sd_resume_runtime
  - drivers/scsi/sd.c:sd_resume_system
  - drivers/scsi/sd.c:sd_resume_system
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:max_retries_store
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81a0b970-ffffffff81a0baa2: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81b8b1c0)
Location: drivers/scsi/scsi_logging.c:56
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_resume_runtime
  - drivers/scsi/sd.c:sd_resume_runtime
  - drivers/scsi/sd.c:sd_resume_system
  - drivers/scsi/sd.c:sd_resume_system
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:max_retries_store
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81b8b1c0-ffffffff81b8b300: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81bdf1c0)
Location: drivers/scsi/scsi_logging.c:56
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/virtio_scsi.c:virtscsi_device_reset
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_resume_runtime
  - drivers/scsi/sd.c:sd_resume_runtime
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_pr_read_reservation
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:max_retries_store
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81bdf1c0-ffffffff81bdf300: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81c340b0)
Location: drivers/scsi/scsi_logging.c:56
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_error.c:scsi_report_sense
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/virtio_scsi.c:virtscsi_device_reset
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_resume_runtime
  - drivers/scsi/sd.c:sd_resume_runtime
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_validate_opt_xfer_size
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_pr_read_reservation
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:max_retries_store
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sd_zbc.c:sd_zbc_parse_report
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81c340b0-ffffffff81c3421f: sdev_prefix_printk (STB_GLOBAL)
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
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffff800010982328)
Location: drivers/scsi/scsi_logging.c:53
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffff800010982328-ffff800010982450: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (c0a54d90)
Location: drivers/scsi/scsi_logging.c:53
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_new_write
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
c0a54d90-c0a54e9c: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (c000000000a3e930)
Location: drivers/scsi/scsi_logging.c:53
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
c000000000a3e930-c000000000a3ea5c: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffe0005e7c9c)
Location: drivers/scsi/scsi_logging.c:53
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_print_result
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_remove_scat
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffe0005e7c9c-ffffffe0005e7d68: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:53
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff817316c7-ffffffff817316ce: sdev_prefix_printk.cold (STB_LOCAL)
ffffffff81730a00-ffffffff81730b0f: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:53
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff8170aae7-ffffffff8170aaee: sdev_prefix_printk.cold (STB_LOCAL)
ffffffff81709e20-ffffffff81709f2f: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:53
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/virtio_scsi.c:virtscsi_device_reset
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81770497-ffffffff8177049e: sdev_prefix_printk.cold (STB_LOCAL)
ffffffff8176f7d0-ffffffff8176f8df: sdev_prefix_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void sdev_prefix_printk(const char *level, const struct scsi_device *sdev, const char *name, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:53
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_finish_command
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_lib.c:scsi_device_set_state
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_report_lun_scan
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:sdev_store_dh_state
  - drivers/scsi/scsi_sysfs.c:store_queue_type_field
  - drivers/scsi/scsi_dh.c:scsi_dh_release_device
  - drivers/scsi/scsi_dh.c:scsi_dh_handler_attach
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_resume
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_suspend_common
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_shutdown
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:read_capacity_error
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_spinup_disk
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_pr_command
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_check_events
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_ioctl
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_release
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd.c:sd_open
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_print_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_do_report_zones
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_check_events
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_build_reserve
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_mmap
  - drivers/scsi/sg.c:sg_vma_fault
  - drivers/scsi/sg.c:sg_fasync
  - drivers/scsi/sg.c:sg_poll
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff8178bc37-ffffffff8178bc3e: sdev_prefix_printk.cold (STB_LOCAL)
ffffffff8178af70-ffffffff8178b07f: sdev_prefix_printk (STB_GLOBAL)
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
