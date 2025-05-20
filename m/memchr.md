# Function: <code>memchr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *memchr(const void *s, int c, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff813f1e50)
Location: lib/string.c:863
Inline: False
Direct callers:
  - kernel/power/main.c:pm_test_store
  - kernel/power/main.c:state_store
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
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff813f1e50-ffffffff813f1e79: memchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *memchr(const void *s, int c, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff814387f0)
Location: lib/string.c:860
Inline: False
Direct callers:
  - kernel/power/main.c:state_store
  - kernel/power/main.c:pm_test_store
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
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff814387f0-ffffffff81438813: memchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *memchr(const void *s, int c, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff814557e0)
Location: lib/string.c:860
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
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
  - net/dns_resolver/dns_key.c:dns_resolver_preparse
```
**Symbols:**

```
ffffffff814557e0-ffffffff81455803: memchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *memchr(const void *p, int c, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8108cfa0)
Location: include/linux/string.h:353
Inline: True
Inline callers:
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
**Symbols:**

```
ffffffff818f6ab0-ffffffff818f6ad3: memchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *memchr(const void *p, int c, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81093c70)
Location: include/linux/string.h:388
Inline: True
Inline callers:
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
**Symbols:**

```
ffffffff8197d4b0-ffffffff8197d4d3: memchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *memchr(const void *p, int c, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810976cc)
Location: include/linux/string.h:389
Inline: True
Inline callers:
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
**Symbols:**

```
ffffffff819d99e0-ffffffff819d99fd: memchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *memchr(const void *p, int c, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8109f9ec)
Location: include/linux/string.h:396
Inline: True
Inline callers:
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
**Symbols:**

```
ffffffff81a11c00-ffffffff81a11c1d: memchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *memchr(const void *p, int c, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a410a)
Location: include/linux/string.h:403
Inline: True
Inline callers:
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
**Symbols:**

```
ffffffff81a81140-ffffffff81a8115d: memchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *memchr(const void *p, int c, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810aa6ea)
Location: include/linux/string.h:424
Inline: True
Inline callers:
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
**Symbols:**

```
ffffffff81ab8340-ffffffff81ab835d: memchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *memchr(const void *p, int c, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810b2071)
Location: include/linux/string.h:450
Inline: True
Inline callers:
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
**Symbols:**

```
ffffffff815f2f70-ffffffff815f2f8d: memchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *memchr(const void *p, int c, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810ad8a1)
Location: include/linux/string.h:491
Inline: True
Inline callers:
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
**Symbols:**

```
ffffffff81617620-ffffffff8161763d: memchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *memchr(const void *p, int c, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810aeab0)
Location: include/linux/fortify-string.h:238
Inline: True
Inline callers:
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
**Symbols:**

```
ffffffff815fac90-ffffffff815facad: memchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *memchr(const void *p, int c, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810c08dc)
Location: include/linux/fortify-string.h:238
Inline: True
Inline callers:
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
**Symbols:**

```
ffffffff81668540-ffffffff8166855d: memchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *memchr(const const void * p, int c, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810d7ea9)
Location: include/linux/fortify-string.h:424
Inline: True
Inline callers:
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
**Symbols:**

```
ffffffff817822e0-ffffffff81782311: memchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *memchr(const const void * p, int c, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810f79d3)
Location: include/linux/fortify-string.h:662
Inline: True
Inline callers:
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
**Symbols:**

```
ffffffff8203f140-ffffffff8203f171: memchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *memchr(const const void * p, int c, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81103dd3)
Location: include/linux/fortify-string.h:732
Inline: True
Inline callers:
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
**Symbols:**

```
ffffffff820bd5b0-ffffffff820bd5e1: memchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *memchr(const const void * p, int c, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8110d723)
Location: include/linux/fortify-string.h:677
Inline: True
Inline callers:
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
**Symbols:**

```
ffffffff82197eb0-ffffffff82197ee1: memchr (STB_GLOBAL)
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
void *memchr(const void *p, int c, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffff800010102988)
Location: include/linux/string.h:424
Inline: True
Inline callers:
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
Direct callers:
  - lib/fdt_ro.c:fdt_stringlist_contains
  - lib/fdt_ro.c:fdt_path_offset_namelen
  - lib/fdt_ro.c:fdt_path_offset_namelen
  - lib/fdt_ro.c:fdt_get_string
```
**Symbols:**

```
ffff800010d828f8-ffff800010d82920: memchr (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *memchr(const void *p, int c, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/armksyms.c (c035ec60)
Location: include/linux/string.h:424
Inline: True
Inline callers:
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
**Symbols:**

```
c0e7e080-c0e7e0a0: memchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *memchr(const void *p, int c, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (c00000000014a284)
Location: include/linux/string.h:424
Inline: True
Inline callers:
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
**Symbols:**

```
c0000000000a80f4-c0000000000a80f4: memchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *memchr(const void *s, int c, size_t n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bcf04)
Location: lib/string.c:997
Inline: False
Direct callers:
  - kernel/printk/printk.c:msg_print_text
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/fs_context.c:legacy_parse_param
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
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
**Symbols:**

```
ffffffe0008bcf04-ffffffe0008bcf2e: memchr (STB_GLOBAL)
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
void *memchr(const void *p, int c, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a400a)
Location: include/linux/string.h:424
Inline: True
Inline callers:
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
**Symbols:**

```
ffffffff81a57190-ffffffff81a571ad: memchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *memchr(const void *p, int c, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810929ea)
Location: include/linux/string.h:424
Inline: True
Inline callers:
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
**Symbols:**

```
ffffffff81a14270-ffffffff81a1428d: memchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *memchr(const void *p, int c, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a3fba)
Location: include/linux/string.h:424
Inline: True
Inline callers:
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
**Symbols:**

```
ffffffff81ac3580-ffffffff81ac359d: memchr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *memchr(const void *p, int c, __kernel_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810ac07a)
Location: include/linux/string.h:424
Inline: True
Inline callers:
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
**Symbols:**

```
ffffffff81acfa50-ffffffff81acfa6d: memchr (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void *p</code>
</li>
<li>
<b>Param added. </b>
<code>__kernel_size_t size</code>
</li>
<li>
<b>Param removed. </b>
<code>const void *s</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t n</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const void *p</code> ➡️ <code>const const void * p</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void *s</code>
</li>
<li>
<b>Param added. </b>
<code>size_t n</code>
</li>
<li>
<b>Param removed. </b>
<code>const void *p</code>
</li>
<li>
<b>Param removed. </b>
<code>__kernel_size_t size</code>
</li>
</ul>
</details>
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
