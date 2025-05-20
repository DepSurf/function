# Function: <code>__builtin_memchr</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:mem_sleep_store
  - kernel/power/hibernate.c:disk_store
  - kernel/printk/printk.c:msg_print_text
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - lib/nlattr.c:validate_nla
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:wake_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/cpufreq/intel_pstate.c:store_status
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:mem_sleep_store
  - kernel/power/hibernate.c:disk_store
  - kernel/printk/printk.c:msg_print_text
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - lib/nlattr.c:validate_nla
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/base/power/sysfs.c:async_store
  - drivers/base/power/sysfs.c:wake_store
  - drivers/base/power/sysfs.c:control_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/cpufreq/intel_pstate.c:store_status
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:mem_sleep_store
  - kernel/power/hibernate.c:disk_store
  - kernel/printk/printk.c:msg_print_text
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - lib/nlattr.c:validate_nla
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/usb/core/sysfs.c:level_store
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/cpufreq/intel_pstate.c:store_status
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:mem_sleep_store
  - kernel/power/hibernate.c:disk_store
  - kernel/printk/printk.c:msg_print_text
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - lib/nlattr.c:validate_nla
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/spi/spi.c:driver_override_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/cpufreq/intel_pstate.c:store_status
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:mem_sleep_store
  - kernel/power/hibernate.c:disk_store
  - kernel/printk/printk.c:msg_print_text
  - fs/fs_context.c:legacy_parse_param
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - lib/nlattr.c:validate_nla
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/spi/spi.c:driver_override_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/cpufreq/intel_pstate.c:store_status
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:mem_sleep_store
  - kernel/power/hibernate.c:disk_store
  - kernel/printk/printk.c:msg_print_text
  - fs/readdir.c:verify_dirent_name
  - fs/fs_context.c:legacy_parse_param
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - lib/nlattr.c:validate_nla
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/spi/spi.c:driver_override_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/cpufreq/intel_pstate.c:store_status
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/main.c:decode_state
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:decode_suspend_state
  - kernel/power/hibernate.c:disk_store
  - kernel/printk/printk.c:msg_print_text
  - fs/readdir.c:verify_dirent_name
  - fs/fs_context.c:legacy_parse_param
  - fs/fuse/readdir.c:fuse_parse_cache
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:parse_dirplusfile
  - lib/nlattr.c:validate_nla
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/spi/spi.c:driver_override_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/cpufreq/intel_pstate.c:store_status
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/main.c:decode_state
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:decode_suspend_state
  - kernel/power/hibernate.c:disk_store
  - kernel/printk/printk.c:record_print_text
  - kernel/printk/printk_ringbuffer.c:prb_read
  - fs/readdir.c:verify_dirent_name
  - fs/fs_context.c:legacy_parse_param
  - fs/fuse/readdir.c:fuse_parse_cache
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:parse_dirplusfile
  - security/tomoyo/util.c:tomoyo_correct_path2
  - security/tomoyo/util.c:tomoyo_correct_path2
  - lib/nlattr.c:validate_nla
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/spi/spi.c:driver_override_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/cpufreq/intel_pstate.c:store_status
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:mem_sleep_store
  - kernel/power/hibernate.c:disk_store
  - kernel/printk/printk.c:record_print_text
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - fs/readdir.c:verify_dirent_name
  - fs/fs_context.c:legacy_parse_param
  - fs/fuse/readdir.c:fuse_parse_cache
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - security/tomoyo/util.c:tomoyo_correct_path2
  - security/tomoyo/util.c:tomoyo_correct_path2
  - lib/nlattr.c:validate_nla
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/spi/spi.c:driver_override_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/cpufreq/intel_pstate.c:store_status
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:mem_sleep_store
  - kernel/power/hibernate.c:disk_store
  - kernel/printk/printk.c:record_print_text
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - fs/readdir.c:verify_dirent_name
  - fs/fs_context.c:legacy_parse_param
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - security/tomoyo/util.c:tomoyo_correct_path2
  - security/tomoyo/util.c:tomoyo_correct_path2
  - lib/nlattr.c:validate_nla
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/spi/spi.c:driver_override_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/cpufreq/intel_pstate.c:store_status
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:mem_sleep_store
  - kernel/power/hibernate.c:disk_store
  - kernel/printk/printk.c:record_print_text
  - kernel/printk/printk_ringbuffer.c:_prb_read_valid
  - fs/readdir.c:verify_dirent_name
  - fs/fs_context.c:legacy_parse_param
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - security/tomoyo/util.c:tomoyo_correct_path2
  - security/tomoyo/util.c:tomoyo_correct_path2
  - lib/nlattr.c:validate_nla
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/usb/core/sysfs.c:level_store
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/cpufreq/intel_pstate.c:store_status
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/main.c:decode_state
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:mem_sleep_store
  - kernel/power/hibernate.c:disk_store
  - kernel/printk/printk.c:record_print_text
  - kernel/printk/printk_ringbuffer.c:copy_data
  - fs/readdir.c:verify_dirent_name
  - fs/fs_context.c:legacy_parse_param
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - security/tomoyo/util.c:tomoyo_correct_path2
  - security/tomoyo/util.c:tomoyo_correct_path2
  - lib/nlattr.c:validate_nla
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/usb/core/sysfs.c:level_store
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/cpufreq/intel_pstate.c:store_status
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/main.c:decode_state
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:mem_sleep_store
  - kernel/power/hibernate.c:disk_store
  - kernel/printk/printk.c:record_print_text
  - kernel/printk/printk_ringbuffer.c:copy_data
  - fs/readdir.c:verify_dirent_name
  - fs/fs_context.c:legacy_parse_param
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - security/tomoyo/util.c:tomoyo_correct_path2
  - security/tomoyo/util.c:tomoyo_correct_path2
  - lib/nlattr.c:validate_nla
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/usb/core/sysfs.c:level_store
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/md/dm-ioctl.c:populate_table
  - drivers/cpufreq/amd-pstate.c:status_store
  - drivers/cpufreq/intel_pstate.c:store_status
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/main.c:decode_state
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:mem_sleep_store
  - kernel/power/hibernate.c:disk_store
  - kernel/printk/printk.c:record_print_text
  - kernel/printk/printk_ringbuffer.c:copy_data
  - fs/readdir.c:verify_dirent_name
  - fs/fs_context.c:legacy_parse_param
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - security/tomoyo/util.c:tomoyo_correct_path2
  - security/tomoyo/util.c:tomoyo_correct_path2
  - lib/nlattr.c:validate_nla
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/scsi/scsi.c:scsi_get_vpd_size
  - drivers/usb/core/sysfs.c:level_store
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/md/dm-ioctl.c:populate_table
  - drivers/cpufreq/amd-pstate.c:status_store
  - drivers/cpufreq/intel_pstate.c:store_status
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:mem_sleep_store
  - kernel/printk/printk.c:msg_print_text
  - fs/readdir.c:verify_dirent_name
  - fs/fs_context.c:legacy_parse_param
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:parse_dirplusfile
  - lib/nlattr.c:validate_nla
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/spi/spi.c:driver_override_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/input/serio/libps2.c:__ps2_command
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - lib/fdt_ro.c:fdt_stringlist_contains
  - lib/fdt_ro.c:fdt_path_offset_namelen
  - lib/fdt_ro.c:fdt_path_offset_namelen
  - lib/fdt_ro.c:fdt_get_string
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:mem_sleep_store
  - kernel/power/hibernate.c:disk_store
  - kernel/printk/printk.c:msg_print_text
  - fs/readdir.c:verify_dirent_name
  - fs/fs_context.c:legacy_parse_param
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:parse_dirplusfile
  - lib/nlattr.c:validate_nla
  - drivers/spi/spi.c:driver_override_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/input/serio/libps2.c:__ps2_command
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - lib/fdt_ro.c:fdt_stringlist_contains
  - lib/fdt_ro.c:fdt_path_offset_namelen
  - lib/fdt_ro.c:fdt_path_offset_namelen
  - lib/fdt_ro.c:fdt_get_string
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:mem_sleep_store
  - kernel/printk/printk.c:msg_print_text
  - fs/readdir.c:verify_dirent_name
  - fs/fs_context.c:legacy_parse_param
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:parse_dirplusfile
  - lib/nlattr.c:validate_nla
  - drivers/spi/spi.c:driver_override_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/input/serio/libps2.c:__ps2_command
  - net/netlink/genetlink.c:genl_validate_assign_mc_groups
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - lib/fdt_ro.c:fdt_stringlist_contains
  - lib/fdt_ro.c:fdt_path_offset_namelen
  - lib/fdt_ro.c:fdt_path_offset_namelen
  - lib/fdt_ro.c:fdt_get_string
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
  - kernel/power/main.c:pm_test_store
  - kernel/power/hibernate.c:disk_store
  - kernel/printk/printk.c:msg_print_text
  - fs/readdir.c:verify_dirent_name
  - fs/fs_context.c:legacy_parse_param
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - lib/nlattr.c:validate_nla
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/spi/spi.c:driver_override_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/cpufreq/intel_pstate.c:store_status
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:mem_sleep_store
  - kernel/power/hibernate.c:disk_store
  - kernel/printk/printk.c:msg_print_text
  - fs/readdir.c:verify_dirent_name
  - fs/fs_context.c:legacy_parse_param
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - lib/nlattr.c:validate_nla
  - drivers/spi/spi.c:driver_override_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/cpufreq/intel_pstate.c:store_status
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:mem_sleep_store
  - kernel/power/hibernate.c:disk_store
  - kernel/printk/printk.c:msg_print_text
  - fs/readdir.c:verify_dirent_name
  - fs/fs_context.c:legacy_parse_param
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - lib/nlattr.c:validate_nla
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/spi/spi.c:driver_override_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/cpufreq/intel_pstate.c:store_status
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:mem_sleep_store
  - kernel/power/hibernate.c:disk_store
  - kernel/printk/printk.c:msg_print_text
  - fs/readdir.c:verify_dirent_name
  - fs/fs_context.c:legacy_parse_param
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - lib/nlattr.c:validate_nla
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/spi/spi.c:driver_override_store
  - drivers/usb/core/sysfs.c:level_store
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/cpufreq/intel_pstate.c:store_status
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
</details>
</li>
</ul>

## Differences
