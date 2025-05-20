# Function: <code>strscpy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t strscpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff813f17c0)
Location: lib/string.c:177
Inline: False
```
**Symbols:**

```
ffffffff813f17c0-ffffffff813f190e: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t strscpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81438150)
Location: lib/string.c:177
Inline: False
```
**Symbols:**

```
ffffffff81438150-ffffffff814382c9: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t strscpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81455140)
Location: lib/string.c:177
Inline: False
```
**Symbols:**

```
ffffffff81455140-ffffffff814552b9: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t strscpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff818f6c50)
Location: lib/string.c:177
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_actions_logged_handler
  - kernel/seccomp.c:seccomp_actions_logged_handler
```
**Symbols:**

```
ffffffff818f6c50-ffffffff818f6da9: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t strscpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8197d650)
Location: lib/string.c:178
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_actions_logged_handler
  - kernel/seccomp.c:seccomp_actions_logged_handler
```
**Symbols:**

```
ffffffff8197d650-ffffffff8197d7a9: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t strscpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff819d9b60)
Location: lib/string.c:178
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:process_one_work
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:onmax_save
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
  - kernel/trace/trace_events_hist.c:hist_err_event
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
ffffffff819d9b60-ffffffff819d9cbc: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t strscpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a11d80)
Location: lib/string.c:179
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:process_one_work
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:onmax_save
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
  - kernel/trace/trace_events_hist.c:hist_err_event
  - fs/proc/array.c:proc_task_name
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/rng.c:crypto_rng_report
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81a11d80-ffffffff81a11edc: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t strscpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a812a0)
Location: lib/string.c:179
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:process_one_work
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:save_track_data_vars
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - fs/proc/array.c:proc_task_name
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/rng.c:crypto_rng_report
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - lib/string.c:strscpy_pad
```
**Symbols:**

```
ffffffff81a812a0-ffffffff81a813c4: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t strscpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ab88e0)
Location: lib/string.c:180
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:process_one_work
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:save_track_data_vars
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - fs/proc/array.c:proc_task_name
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/rng.c:crypto_rng_report
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - lib/string.c:strscpy_pad
```
**Symbols:**

```
ffffffff81ab88e0-ffffffff81ab8a1b: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t strscpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815f3540)
Location: lib/string.c:180
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:process_one_work
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:save_track_data_vars
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
  - fs/proc/array.c:proc_task_name
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/rng.c:crypto_rng_report
  - lib/string.c:strscpy_pad
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff815f3540-ffffffff815f3689: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t strscpy(char *p, const char *q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c72e2)
Location: include/linux/string.h:363
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:process_one_work
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:save_track_data_vars
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
  - fs/proc/array.c:proc_task_name
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/rng.c:crypto_rng_report
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
  - drivers/base/core.c:set_dev_info
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
Direct callers:
  - lib/string.c:strscpy_pad
```
**Symbols:**

```
ffffffff81617bd0-ffffffff81617d19: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t strscpy(char *p, const char *q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c8a75)
Location: include/linux/fortify-string.h:104
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:process_one_work
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:save_track_data_vars
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/proc/array.c:proc_task_name
  - fs/debugfs/file.c:debugfs_read_file_str
  - security/selinux/ima.c:selinux_ima_collect_state
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/rng.c:crypto_rng_report
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
  - drivers/base/core.c:set_dev_info
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
Direct callers:
  - lib/string.c:strscpy_pad
```
**Symbols:**

```
ffffffff815fb220-ffffffff815fb369: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t strscpy(char *p, const char *q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810db645)
Location: include/linux/fortify-string.h:104
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:process_one_work
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_events_synth.c:__synth_event_add_val
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:save_track_data_vars
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/debugfs/file.c:debugfs_read_file_str
  - security/selinux/ima.c:selinux_ima_collect_state
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/rng.c:crypto_rng_report
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
  - drivers/base/core.c:set_dev_info
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
Direct callers:
  - lib/string.c:strscpy_pad
```
**Symbols:**

```
ffffffff81668af0-ffffffff81668c39: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t strscpy(const char * p, const const char * q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff834491e2)
Location: include/linux/fortify-string.h:177
Inline: True
Inline callers:
  - init/initramfs.c:dir_add
  - arch/x86/kernel/setup.c:setup_arch
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:process_one_work
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:lookup_module_symbol_attrs
  - kernel/module/kallsyms.c:lookup_module_symbol_attrs
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:add_kallsyms
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/kprobes.c:kprobe_cache_get_kallsym
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_main.c:handle_ctrl_cmd
  - kernel/debug/kdb/kdb_main.c:handle_ctrl_cmd
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_events_synth.c:__synth_event_add_val
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:__update_field_vars
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/debugfs/file.c:debugfs_read_file_str
  - security/selinux/ima.c:selinux_ima_collect_state
  - security/integrity/ima/ima_api.c:ima_d_path
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/rng.c:crypto_rng_report
  - crypto/asymmetric_keys/public_key.c:software_key_determine_akcipher
  - lib/string_helpers.c:strscpy_pad
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
  - drivers/base/core.c:set_dev_info
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffffffff817824d0-ffffffff8178266e: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t strscpy(const char * p, const const char * q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff83e60bac)
Location: include/linux/fortify-string.h:312
Inline: True
Inline callers:
  - init/main.c:setup_boot_config
  - init/main.c:parse_early_param
  - init/do_mounts.c:root_dev_setup
  - init/initramfs.c:dir_add
  - arch/x86/kernel/setup.c:setup_arch
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:process_one_work
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:lookup_module_symbol_attrs
  - kernel/module/kallsyms.c:lookup_module_symbol_attrs
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:add_kallsyms
  - kernel/cgroup/cgroup.c:task_cgroup_path
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/kprobes.c:kprobe_cache_get_kallsym
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_main.c:handle_ctrl_cmd
  - kernel/debug/kdb/kdb_main.c:handle_ctrl_cmd
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:process_fetch_insn
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_eprobe.c:get_eprobe_size
  - kernel/trace/trace_events_synth.c:__synth_event_add_val
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_synth.c:trace_string
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:__update_field_vars
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/bpf/helpers.c:bpf_get_current_comm
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/debugfs/file.c:debugfs_read_file_str
  - security/selinux/ima.c:selinux_ima_collect_state
  - security/integrity/ima/ima_api.c:ima_d_path
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
  - crypto/api.c:crypto_larval_alloc
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/rng.c:crypto_rng_report
  - crypto/asymmetric_keys/public_key.c:software_key_determine_akcipher
  - lib/string_helpers.c:strscpy_pad
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/acpi/utils.c:acpi_dev_get_next_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/bus.c:acpi_set_modalias
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/processor_idle.c:combine_lpi_states
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/battery.c:extract_package
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/base/core.c:set_dev_info
  - drivers/base/dd.c:save_async_options
  - drivers/base/power/main.c:dpm_save_failed_dev
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_get_name
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/drop_monitor.c:net_dm_hw_trap_summary_probe
  - net/core/devlink.c:perf_trace_devlink_trap_report
  - net/core/devlink.c:trace_event_raw_event_devlink_trap_report
  - net/sched/sch_api.c:qdisc_get_default
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/arp.c:arp_req_get
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - lib/earlycpio.c:find_cpio_data
```
**Symbols:**

```
ffffffff8203f360-ffffffff8203f4fe: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t strscpy(const char * p, const const char * q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff8368108e)
Location: include/linux/fortify-string.h:292
Inline: True
Inline callers:
  - init/main.c:setup_boot_config
  - init/main.c:parse_early_param
  - init/do_mounts.c:root_dev_setup
  - init/initramfs.c:dir_add
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:process_one_work
  - kernel/params.c:param_sysfs_builtin
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:add_kallsyms
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/kallsyms.c:update_iter_mod
  - kernel/kallsyms.c:update_iter_mod
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/kprobes.c:kprobe_cache_get_kallsym
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_main.c:handle_ctrl_cmd
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_func_address_lookup
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:__trace_find_cmdline
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_events.c:setup_trace_triggers
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_events_synth.c:__synth_event_add_val
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:__update_field_vars
  - kernel/trace/trace_events_user.c:user_field_array_size
  - kernel/trace/trace_kprobe.c:set_kprobe_boot_events
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/proc/kcore.c:read_kcore_iter
  - fs/debugfs/file.c:debugfs_read_file_str
  - security/selinux/ima.c:selinux_ima_collect_state
  - security/integrity/ima/ima_api.c:ima_d_path
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
  - crypto/api.c:crypto_larval_alloc
  - crypto/aead.c:crypto_aead_report_stat
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/skcipher.c:crypto_skcipher_report_stat
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report_stat
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/sig.c:crypto_sig_report_stat
  - crypto/sig.c:crypto_sig_report
  - crypto/kpp.c:crypto_kpp_report_stat
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:__crypto_acomp_report_stat
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/rng.c:crypto_rng_report_stat
  - crypto/rng.c:crypto_rng_report
  - crypto/asymmetric_keys/public_key.c:software_key_determine_akcipher
  - block/elevator.c:elv_iosched_store
  - block/genhd.c:__register_blkdev
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - lib/string_helpers.c:strscpy_pad
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/acpi/utils.c:acpi_dev_get_next_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/bus.c:acpi_set_modalias
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/processor_idle.c:combine_lpi_states
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/battery.c:extract_package
  - drivers/acpi/battery.c:extract_package
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/base/core.c:set_dev_info
  - drivers/base/dd.c:save_async_options
  - drivers/base/power/main.c:dpm_save_failed_dev
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_get_name
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/virtio_net.c:virtnet_get_drvinfo
  - drivers/net/virtio_net.c:virtnet_get_drvinfo
  - drivers/net/virtio_net.c:virtnet_get_drvinfo
  - drivers/net/net_failover.c:nfo_ethtool_get_drvinfo
  - drivers/net/net_failover.c:nfo_ethtool_get_drvinfo
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - net/core/dev.c:dev_get_valid_name
  - net/core/dev.c:dev_alloc_name_ns
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:trace_event_raw_event_fib_table_lookup
  - net/core/drop_monitor.c:net_dm_hw_trap_summary_probe
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tc_action_load_ops
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/arp.c:arp_req_get
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/devlink/leftover.c:perf_trace_devlink_trap_report
  - net/devlink/leftover.c:trace_event_raw_event_devlink_trap_report
  - lib/earlycpio.c:find_cpio_data
```
**Symbols:**

```
ffffffff820bd7d0-ffffffff820bd974: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t strscpy(const char * p, const const char * q, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff838b00ae)
Location: include/linux/fortify-string.h:237
Inline: True
Inline callers:
  - init/main.c:setup_boot_config
  - init/main.c:parse_early_param
  - init/version.c:early_hostname
  - init/do_mounts.c:root_dev_setup
  - init/initramfs.c:dir_add
  - arch/x86/xen/efi.c:xen_efi_init
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:set_trigger
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_stringify
  - arch/x86/kernel/hpet.c:hpet_enable
  - kernel/fork.c:perf_trace_task_rename
  - kernel/fork.c:trace_event_raw_event_task_rename
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:process_one_work
  - kernel/params.c:param_sysfs_builtin
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:module_get_kallsym
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:add_kallsyms
  - kernel/time/clocksource.c:boot_override_clocksource
  - kernel/kallsyms.c:update_iter_mod
  - kernel/kallsyms.c:update_iter_mod
  - kernel/acct.c:fill_ac
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_write
  - kernel/kprobes.c:kprobe_cache_get_kallsym
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_main.c:handle_ctrl_cmd
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_mod_get_kallsym
  - kernel/trace/ftrace.c:ftrace_func_address_lookup
  - kernel/trace/ftrace.c:set_graph_notrace_function
  - kernel/trace/ftrace.c:set_graph_function
  - kernel/trace/ftrace.c:set_ftrace_filter
  - kernel/trace/ftrace.c:set_ftrace_notrace
  - kernel/trace/trace.c:__trace_find_cmdline
  - kernel/trace/trace.c:set_trace_boot_clock
  - kernel/trace/trace.c:set_trace_boot_options
  - kernel/trace/trace.c:set_cmdline_ftrace
  - kernel/trace/trace_events.c:setup_trace_event
  - kernel/trace/trace_events.c:setup_trace_triggers
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
  - kernel/trace/trace_events_synth.c:__synth_event_add_val
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:__update_field_vars
  - kernel/trace/trace_events_user.c:user_field_array_size
  - kernel/trace/trace_kprobe.c:set_kprobe_boot_events
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
  - kernel/events/core.c:perf_event_ksymbol
  - kernel/events/core.c:perf_event_mmap_event
  - mm/zswap.c:zswap_pool_create
  - mm/dmapool.c:dma_pool_create
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/char_dev.c:__register_chrdev_region
  - fs/proc/kcore.c:read_kcore_iter
  - fs/kernfs/dir.c:kernfs_walk_ns
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_path_from_node_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/kernfs/dir.c:kernfs_name_locked
  - fs/debugfs/file.c:debugfs_read_file_str
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/selinux/ima.c:selinux_ima_collect_state
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/integrity/ima/ima_api.c:ima_d_path
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
  - crypto/api.c:crypto_larval_alloc
  - crypto/aead.c:crypto_aead_report_stat
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/lskcipher.c:lskcipher_alloc_instance_simple
  - crypto/lskcipher.c:crypto_lskcipher_report_stat
  - crypto/lskcipher.c:crypto_lskcipher_report
  - crypto/lskcipher.c:crypto_lskcipher_report
  - crypto/skcipher.c:crypto_skcipher_report_stat
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report_stat
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/sig.c:crypto_sig_report_stat
  - crypto/sig.c:crypto_sig_report
  - crypto/kpp.c:crypto_kpp_report_stat
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:__crypto_acomp_report_stat
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/xts.c:xts_create
  - crypto/rng.c:crypto_rng_report_stat
  - crypto/rng.c:crypto_rng_report
  - crypto/asymmetric_keys/public_key.c:software_key_determine_akcipher
  - block/elevator.c:elv_iosched_store
  - block/genhd.c:__register_blkdev
  - block/partitions/cmdline.c:add_part
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_subpart
  - block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid
  - block/blk-wbt.c:perf_trace_wbt_timer
  - block/blk-wbt.c:perf_trace_wbt_step
  - block/blk-wbt.c:perf_trace_wbt_lat
  - block/blk-wbt.c:perf_trace_wbt_stat
  - block/blk-wbt.c:trace_event_raw_event_wbt_timer
  - block/blk-wbt.c:trace_event_raw_event_wbt_step
  - block/blk-wbt.c:trace_event_raw_event_wbt_lat
  - block/blk-wbt.c:trace_event_raw_event_wbt_stat
  - lib/string_helpers.c:strscpy_pad
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
  - drivers/video/fbdev/core/fbcon.c:fb_console_setup
  - drivers/acpi/osi.c:acpi_osi_setup
  - drivers/acpi/utils.c:acpi_backlight
  - drivers/acpi/utils.c:acpi_dev_get_next_match_dev
  - drivers/acpi/utils.c:acpi_dev_present
  - drivers/acpi/bus.c:acpi_set_modalias
  - drivers/acpi/mipi-disco-img.c:parse_csi2_resource
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/processor_idle.c:combine_lpi_states
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/battery.c:extract_package
  - drivers/acpi/battery.c:extract_package
  - drivers/clk/clkdev.c:vclkdev_alloc
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_bus_id
  - drivers/regulator/event.c:reg_generate_netlink_event
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
  - drivers/char/tpm/tpm_ppi.c:tpm_add_ppi
  - drivers/base/core.c:set_dev_info
  - drivers/base/dd.c:save_async_options
  - drivers/base/power/main.c:dpm_save_failed_dev
  - drivers/dax/bus.c:do_id_store
  - drivers/dma-buf/dma-buf.c:dmabuffs_dname
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
  - drivers/dma-buf/sync_file.c:sync_fill_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_get_name
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
  - drivers/gpu/drm/drm_client.c:drm_client_buffer_addfb
  - drivers/gpu/drm/drm_modes.c:drm_mode_parse_cmdline_named_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/spi/spi.c:spi_new_device
  - drivers/net/netkit.c:netkit_new_link
  - drivers/net/netkit.c:netkit_new_link
  - drivers/net/netkit.c:netkit_get_drvinfo
  - drivers/net/phy/phy_device.c:phy_register_fixup
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/tun.c:tun_get_drvinfo
  - drivers/net/virtio_net.c:virtnet_get_drvinfo
  - drivers/net/virtio_net.c:virtnet_get_drvinfo
  - drivers/net/virtio_net.c:virtnet_get_drvinfo
  - drivers/net/net_failover.c:nfo_ethtool_get_drvinfo
  - drivers/net/net_failover.c:nfo_ethtool_get_drvinfo
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/md/md.c:md_run
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:level_store
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_device_entry
  - drivers/md/dm-init.c:dm_parse_table_entry
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/md/dm-ioctl.c:__find_device_hash_cell
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/edac/edac_mc.c:edac_mc_handle_error
  - drivers/eisa/eisa-bus.c:eisa_name_device
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_setup
  - drivers/cpufreq/cpufreq.c:__cpufreq_offline
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:__dev_alloc_name
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_parse_options
  - net/core/net-traces.c:perf_trace_fib_table_lookup
  - net/core/net-traces.c:trace_event_raw_event_fib_table_lookup
  - net/core/drop_monitor.c:net_dm_hw_trap_summary_probe
  - net/sched/sch_api.c:qdisc_get_default
  - net/sched/act_api.c:tc_action_load_ops
  - net/ethtool/ioctl.c:ethtool_puts
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/netfilter/nf_log.c:nf_log_proc_dostring
  - net/ipv4/arp.c:arp_req_get
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_algo
  - net/ipv4/tcp_ao.c:tcp_ao_parse_crypto
  - net/ipv6/route.c:perf_trace_fib6_table_lookup
  - net/ipv6/route.c:trace_event_raw_event_fib6_table_lookup
  - net/packet/af_packet.c:packet_getname_spkt
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/devlink/core.c:perf_trace_devlink_trap_report
  - net/devlink/core.c:trace_event_raw_event_devlink_trap_report
  - lib/earlycpio.c:find_cpio_data
  - lib/kobject_uevent.c:init_uevent_argv
```
**Symbols:**

```
ffffffff82198050-ffffffff821981f4: strscpy (STB_GLOBAL)
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
ssize_t strscpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffff800010d92cf0)
Location: lib/string.c:180
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:process_one_work
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:save_track_data_vars
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - fs/proc/array.c:proc_task_name
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/rng.c:crypto_rng_report
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_init_init
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - lib/string.c:strscpy_pad
```
**Symbols:**

```
ffff800010d92cf0-ffff800010d92e08: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t strscpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c0e8f5d8)
Location: lib/string.c:180
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:process_one_work
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
  - fs/proc/array.c:proc_task_name
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/rng.c:crypto_rng_report
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_init_init
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - lib/string.c:strscpy_pad
```
**Symbols:**

```
c0e8f5d8-c0e8f730: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t strscpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c000000000ed6d60)
Location: lib/string.c:180
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:process_one_work
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:save_track_data_vars
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - fs/proc/array.c:proc_task_name
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/rng.c:crypto_rng_report
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - lib/string.c:strscpy_pad
```
**Symbols:**

```
c000000000ed6d60-c000000000ed6ea4: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t strscpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bd088)
Location: lib/string.c:180
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:process_one_work
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - fs/proc/array.c:proc_task_name
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/rng.c:crypto_rng_report
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - lib/string.c:strscpy_pad
```
**Symbols:**

```
ffffffe0008bd088-ffffffe0008bd18e: strscpy (STB_GLOBAL)
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
ssize_t strscpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a57730)
Location: lib/string.c:180
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:process_one_work
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:save_track_data_vars
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - fs/proc/array.c:proc_task_name
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/rng.c:crypto_rng_report
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - lib/string.c:strscpy_pad
```
**Symbols:**

```
ffffffff81a57730-ffffffff81a5786b: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t strscpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a14810)
Location: lib/string.c:180
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:process_one_work
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:save_track_data_vars
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - fs/proc/array.c:proc_task_name
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/rng.c:crypto_rng_report
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - lib/string.c:strscpy_pad
```
**Symbols:**

```
ffffffff81a14810-ffffffff81a1494b: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t strscpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ac3b20)
Location: lib/string.c:180
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:process_one_work
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:save_track_data_vars
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - fs/proc/array.c:proc_task_name
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/rng.c:crypto_rng_report
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - lib/string.c:strscpy_pad
```
**Symbols:**

```
ffffffff81ac3b20-ffffffff81ac3c5b: strscpy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t strscpy(char *dest, const char *src, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81acfff0)
Location: lib/string.c:180
Inline: False
Direct callers:
  - kernel/workqueue.c:wq_worker_comm
  - kernel/workqueue.c:process_one_work
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:init_cgroup_root
  - kernel/cgroup/cgroup.c:cgroup_file_name
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/gdbstub.c:gdbstub_state
  - kernel/debug/kdb/kdb_io.c:kdb_getstr
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_next
  - kernel/debug/kdb/kdb_support.c:kallsyms_symbol_complete
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:save_track_data_vars
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - fs/proc/array.c:proc_task_name
  - crypto/aead.c:crypto_aead_report
  - crypto/aead.c:crypto_aead_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/ablkcipher.c:crypto_ablkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/blkcipher.c:crypto_blkcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/skcipher.c:crypto_skcipher_report
  - crypto/ahash.c:crypto_ahash_report
  - crypto/shash.c:crypto_shash_report
  - crypto/akcipher.c:crypto_akcipher_report
  - crypto/kpp.c:crypto_kpp_report
  - crypto/acompress.c:crypto_acomp_report
  - crypto/scompress.c:crypto_scomp_report
  - crypto/rng.c:crypto_rng_report
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/acpi/event.c:acpi_bus_generate_netlink_event
  - drivers/media/cec/cec-core.c:cec_allocate_adapter
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/md/dm-init.c:dm_parse_devices
  - drivers/leds/led-core.c:led_compose_name
  - drivers/leds/led-core.c:led_compose_name
  - lib/string.c:strscpy_pad
```
**Symbols:**

```
ffffffff81acfff0-ffffffff81ad012b: strscpy (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>char *p</code>
</li>
<li>
<b>Param added. </b>
<code>const char *q</code>
</li>
<li>
<b>Param added. </b>
<code>size_t size</code>
</li>
<li>
<b>Param removed. </b>
<code>char *dest</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *src</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
</ul>
</details>
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
<code>char *p</code> ➡️ <code>const char * p</code>
</li>
<li>
<b>Param type changed. </b>
<code>const char *q</code> ➡️ <code>const const char * q</code>
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
