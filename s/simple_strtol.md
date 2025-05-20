# Function: <code>simple_strtol</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (0)
Location: lib/vsprintf.c:89
Inline: True
Direct callers:
  - init/do_mounts.c:load_ramdisk
  - init/do_mounts_rd.c:prompt_ramdisk
  - init/do_mounts_rd.c:ramdisk_start_setup
  - kernel/audit.c:audit_enable
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/watchdog.c:softlockup_all_cpu_backtrace_setup
  - kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - crypto/algboss.c:cryptomgr_notify
  - block/deadline-iosched.c:deadline_fifo_batch_store
  - block/deadline-iosched.c:deadline_front_merges_store
  - block/deadline-iosched.c:deadline_writes_starved_store
  - block/deadline-iosched.c:deadline_write_expire_store
  - block/deadline-iosched.c:deadline_read_expire_store
  - lib/cmdline.c:get_option
  - lib/cmdline.c:get_options
  - lib/parser.c:match_token
  - lib/parser.c:match_number
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/base/core.c:device_store_int
  - drivers/base/firmware_class.c:timeout_store
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/brd.c:ramdisk_size
  - drivers/block/loop.c:max_loop_setup
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
```
**Symbols:**

```
ffffffff813f3850-ffffffff813f385b: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8143ae40)
Location: lib/vsprintf.c:95
Inline: True
Direct callers:
  - init/do_mounts.c:load_ramdisk
  - init/do_mounts_rd.c:ramdisk_start_setup
  - init/do_mounts_rd.c:prompt_ramdisk
  - kernel/audit.c:audit_enable
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup
  - kernel/watchdog.c:softlockup_all_cpu_backtrace_setup
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - crypto/algboss.c:cryptomgr_notify
  - block/deadline-iosched.c:deadline_fifo_batch_store
  - block/deadline-iosched.c:deadline_front_merges_store
  - block/deadline-iosched.c:deadline_writes_starved_store
  - block/deadline-iosched.c:deadline_write_expire_store
  - block/deadline-iosched.c:deadline_read_expire_store
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_option
  - lib/vsprintf.c:vsscanf
  - lib/parser.c:match_number
  - lib/parser.c:match_token
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/base/core.c:device_store_int
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/brd.c:ramdisk_size
  - drivers/block/loop.c:max_loop_setup
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
```
**Symbols:**

```
ffffffff8143ae40-ffffffff8143ae5e: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81457e20)
Location: lib/vsprintf.c:95
Inline: True
Direct callers:
  - init/do_mounts.c:load_ramdisk
  - kernel/audit.c:audit_enable
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup
  - kernel/watchdog.c:softlockup_all_cpu_backtrace_setup
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - crypto/algboss.c:cryptomgr_notify
  - block/deadline-iosched.c:deadline_fifo_batch_store
  - block/deadline-iosched.c:deadline_front_merges_store
  - block/deadline-iosched.c:deadline_writes_starved_store
  - block/deadline-iosched.c:deadline_write_expire_store
  - block/deadline-iosched.c:deadline_read_expire_store
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_option
  - lib/vsprintf.c:vsscanf
  - lib/parser.c:match_number
  - lib/parser.c:match_token
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/base/core.c:device_store_int
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
```
**Symbols:**

```
ffffffff81457e20-ffffffff81457e3e: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff818f9790)
Location: lib/vsprintf.c:96
Inline: True
Direct callers:
  - init/do_mounts.c:load_ramdisk
  - kernel/audit.c:audit_enable
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup
  - kernel/watchdog.c:softlockup_all_cpu_backtrace_setup
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - crypto/algboss.c:cryptomgr_notify
  - block/deadline-iosched.c:deadline_fifo_batch_store
  - block/deadline-iosched.c:deadline_front_merges_store
  - block/deadline-iosched.c:deadline_writes_starved_store
  - block/deadline-iosched.c:deadline_write_expire_store
  - block/deadline-iosched.c:deadline_read_expire_store
  - lib/parser.c:match_number
  - lib/parser.c:match_token
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/base/core.c:device_store_int
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_option
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff818f9790-ffffffff818f97ae: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81980400)
Location: lib/vsprintf.c:98
Inline: True
Direct callers:
  - init/do_mounts.c:load_ramdisk
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/watchdog.c:softlockup_all_cpu_backtrace_setup
  - kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - crypto/algboss.c:cryptomgr_notify
  - block/deadline-iosched.c:deadline_fifo_batch_store
  - block/deadline-iosched.c:deadline_front_merges_store
  - block/deadline-iosched.c:deadline_writes_starved_store
  - block/deadline-iosched.c:deadline_write_expire_store
  - block/deadline-iosched.c:deadline_read_expire_store
  - lib/parser.c:match_number
  - lib/parser.c:match_token
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/base/core.c:device_store_int
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_option
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff81980400-ffffffff8198041e: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff819dc120)
Location: lib/vsprintf.c:97
Inline: True
Direct callers:
  - init/do_mounts.c:load_ramdisk
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/watchdog.c:softlockup_all_cpu_backtrace_setup
  - kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - crypto/algboss.c:cryptomgr_notify
  - block/deadline-iosched.c:deadline_fifo_batch_store
  - block/deadline-iosched.c:deadline_front_merges_store
  - block/deadline-iosched.c:deadline_writes_starved_store
  - block/deadline-iosched.c:deadline_write_expire_store
  - block/deadline-iosched.c:deadline_read_expire_store
  - lib/parser.c:match_token
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/base/core.c:device_store_int
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_option
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff819dc120-ffffffff819dc13e: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a14590)
Location: lib/vsprintf.c:98
Inline: True
Direct callers:
  - init/do_mounts.c:load_ramdisk
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/watchdog.c:softlockup_all_cpu_backtrace_setup
  - kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - crypto/algboss.c:cryptomgr_notify
  - block/mq-deadline.c:deadline_fifo_batch_store
  - block/mq-deadline.c:deadline_front_merges_store
  - block/mq-deadline.c:deadline_writes_starved_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/parser.c:match_token
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_option
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff81a14590-ffffffff81a145ae: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a83ea0)
Location: lib/vsprintf.c:100
Inline: True
Direct callers:
  - init/do_mounts.c:load_ramdisk
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/watchdog.c:softlockup_all_cpu_backtrace_setup
  - kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - crypto/algboss.c:cryptomgr_notify
  - block/mq-deadline.c:deadline_fifo_batch_store
  - block/mq-deadline.c:deadline_front_merges_store
  - block/mq-deadline.c:deadline_writes_starved_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/parser.c:match_token
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_option
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff81a83ea0-ffffffff81a83ebe: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81abb110)
Location: lib/vsprintf.c:100
Inline: True
Direct callers:
  - init/do_mounts.c:load_ramdisk
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/watchdog.c:softlockup_all_cpu_backtrace_setup
  - kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - crypto/algboss.c:cryptomgr_notify
  - block/mq-deadline.c:deadline_fifo_batch_store
  - block/mq-deadline.c:deadline_front_merges_store
  - block/mq-deadline.c:deadline_writes_starved_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/parser.c:match_token
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_option
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff81abb110-ffffffff81abb12e: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f4bb0)
Location: lib/vsprintf.c:103
Inline: True
Direct callers:
  - init/do_mounts.c:load_ramdisk
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - crypto/algboss.c:cryptomgr_schedule_probe
  - block/mq-deadline.c:deadline_fifo_batch_store
  - block/mq-deadline.c:deadline_front_merges_store
  - block/mq-deadline.c:deadline_writes_starved_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/parser.c:match_number
  - lib/parser.c:match_one
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_options
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
```
**Symbols:**

```
ffffffff815f4bb0-ffffffff815f4c5b: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81619220)
Location: lib/vsprintf.c:103
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - crypto/algboss.c:cryptomgr_schedule_probe
  - block/mq-deadline.c:deadline_fifo_batch_store
  - block/mq-deadline.c:deadline_front_merges_store
  - block/mq-deadline.c:deadline_writes_starved_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/parser.c:match_number
  - lib/parser.c:match_one
  - lib/cmdline.c:get_options
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
```
**Symbols:**

```
ffffffff81619220-ffffffff816192cb: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815fd230)
Location: lib/vsprintf.c:117
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - crypto/algboss.c:cryptomgr_schedule_probe
  - block/mq-deadline.c:deadline_fifo_batch_store
  - block/mq-deadline.c:deadline_front_merges_store
  - block/mq-deadline.c:deadline_writes_starved_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/parser.c:match_number
  - lib/parser.c:match_one
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_options
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
```
**Symbols:**

```
ffffffff815fd230-ffffffff815fd2e8: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166ad70)
Location: lib/vsprintf.c:118
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - lib/parser.c:match_number
  - lib/parser.c:match_one
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_options
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
```
**Symbols:**

```
ffffffff8166ad70-ffffffff8166ad8e: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81784260)
Location: lib/vsprintf.c:122
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - lib/parser.c:match_number
  - lib/parser.c:match_one
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_options
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
```
**Symbols:**

```
ffffffff81784260-ffffffff81784292: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82041220)
Location: lib/vsprintf.c:123
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - lib/parser.c:match_number
  - lib/parser.c:match_one
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_options
```
**Symbols:**

```
ffffffff82041220-ffffffff82041252: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820bf730)
Location: lib/vsprintf.c:123
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - lib/parser.c:match_number
  - lib/parser.c:match_one
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_options
```
**Symbols:**

```
ffffffff820bf730-ffffffff820bf762: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8219a9e0)
Location: lib/vsprintf.c:125
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - lib/parser.c:match_number
  - lib/parser.c:match_one
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - drivers/gpu/drm/drm_modes.c:drm_mode_parse_command_line_for_connector
  - drivers/gpu/drm/drm_modes.c:drm_mode_parse_command_line_for_connector
  - drivers/gpu/drm/drm_modes.c:drm_mode_parse_command_line_for_connector
  - drivers/gpu/drm/drm_modes.c:drm_mode_parse_command_line_for_connector
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_options
```
**Symbols:**

```
ffffffff8219a9e0-ffffffff8219aa12: simple_strtol (STB_GLOBAL)
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
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffff800010d95f78)
Location: lib/vsprintf.c:100
Inline: True
Direct callers:
  - init/do_mounts.c:load_ramdisk
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/watchdog.c:softlockup_all_cpu_backtrace_setup
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - crypto/algboss.c:cryptomgr_notify
  - block/mq-deadline.c:deadline_fifo_batch_store
  - block/mq-deadline.c:deadline_front_merges_store
  - block/mq-deadline.c:deadline_writes_starved_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/parser.c:match_token
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_option
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffff800010d95f78-ffff800010d95fac: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e92ff4)
Location: lib/vsprintf.c:100
Inline: True
Direct callers:
  - init/do_mounts.c:load_ramdisk
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/watchdog.c:softlockup_all_cpu_backtrace_setup
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - crypto/algboss.c:cryptomgr_notify
  - block/mq-deadline.c:deadline_fifo_batch_store
  - block/mq-deadline.c:deadline_front_merges_store
  - block/mq-deadline.c:deadline_writes_starved_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/parser.c:match_number
  - lib/parser.c:match_token
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_option
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
c0e92ff4-c0e93024: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c000000000edb560)
Location: lib/vsprintf.c:100
Inline: True
Direct callers:
  - init/do_mounts.c:load_ramdisk
  - arch/powerpc/kernel/sysfs.c:setup_smt_snooze_delay
  - arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports
  - arch/powerpc/platforms/pseries/setup.c:pSeries_cmo_feature_init
  - arch/powerpc/platforms/pseries/setup.c:pSeries_cmo_feature_init
  - arch/powerpc/platforms/pseries/setup.c:pSeries_cmo_feature_init
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/watchdog.c:softlockup_all_cpu_backtrace_setup
  - kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - crypto/algboss.c:cryptomgr_notify
  - block/mq-deadline.c:deadline_fifo_batch_store
  - block/mq-deadline.c:deadline_front_merges_store
  - block/mq-deadline.c:deadline_writes_starved_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/parser.c:match_token
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_option
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
c000000000edb560-c000000000edb5a8: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffe0008bfab6)
Location: lib/vsprintf.c:100
Inline: True
Direct callers:
  - init/do_mounts.c:load_ramdisk
  - kernel/watchdog.c:softlockup_all_cpu_backtrace_setup
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - crypto/algboss.c:cryptomgr_notify
  - block/mq-deadline.c:deadline_fifo_batch_store
  - block/mq-deadline.c:deadline_front_merges_store
  - block/mq-deadline.c:deadline_writes_starved_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/parser.c:match_token
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_option
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffe0008bfab6-ffffffe0008bfaf0: simple_strtol (STB_GLOBAL)
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
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a59f60)
Location: lib/vsprintf.c:100
Inline: True
Direct callers:
  - init/do_mounts.c:load_ramdisk
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/watchdog.c:softlockup_all_cpu_backtrace_setup
  - kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - crypto/algboss.c:cryptomgr_notify
  - block/mq-deadline.c:deadline_fifo_batch_store
  - block/mq-deadline.c:deadline_front_merges_store
  - block/mq-deadline.c:deadline_writes_starved_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/parser.c:match_token
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_option
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff81a59f60-ffffffff81a59f7e: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a17040)
Location: lib/vsprintf.c:100
Inline: True
Direct callers:
  - init/do_mounts.c:load_ramdisk
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/watchdog.c:softlockup_all_cpu_backtrace_setup
  - kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - crypto/algboss.c:cryptomgr_notify
  - block/mq-deadline.c:deadline_fifo_batch_store
  - block/mq-deadline.c:deadline_front_merges_store
  - block/mq-deadline.c:deadline_writes_starved_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/parser.c:match_token
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/block/loop.c:max_loop_setup
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_option
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff81a17040-ffffffff81a1705e: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac6350)
Location: lib/vsprintf.c:100
Inline: True
Direct callers:
  - init/do_mounts.c:load_ramdisk
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/watchdog.c:softlockup_all_cpu_backtrace_setup
  - kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - crypto/algboss.c:cryptomgr_notify
  - block/mq-deadline.c:deadline_fifo_batch_store
  - block/mq-deadline.c:deadline_front_merges_store
  - block/mq-deadline.c:deadline_writes_starved_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/parser.c:match_token
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_option
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff81ac6350-ffffffff81ac636e: simple_strtol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int simple_strtol(const char *cp, char **endp, unsigned int base);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad2830)
Location: lib/vsprintf.c:100
Inline: True
Direct callers:
  - init/do_mounts.c:load_ramdisk
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_kill
  - kernel/debug/kdb/kdb_main.c:kdb_dmesg
  - kernel/watchdog.c:softlockup_all_cpu_backtrace_setup
  - kernel/watchdog.c:hardlockup_all_cpu_backtrace_setup
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/main.c:ecryptfs_parse_options
  - fs/ecryptfs/crypto.c:ecryptfs_from_hex
  - crypto/algboss.c:cryptomgr_notify
  - block/mq-deadline.c:deadline_fifo_batch_store
  - block/mq-deadline.c:deadline_front_merges_store
  - block/mq-deadline.c:deadline_writes_starved_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/parser.c:match_token
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/video/fbdev/core/modedb.c:fb_find_mode
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:timeout_store
  - drivers/base/devcoredump.c:disabled_store
  - drivers/block/loop.c:max_loop_setup
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
  - lib/cmdline.c:get_options
  - lib/cmdline.c:get_option
  - lib/vsprintf.c:vsscanf
```
**Symbols:**

```
ffffffff81ad2830-ffffffff81ad284e: simple_strtol (STB_GLOBAL)
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
