# Function: <code>kstrtoll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814021c0)
Location: lib/kstrtox.c:146
Inline: True
Direct callers:
  - kernel/params.c:param_set_long
  - kernel/cgroup.c:cgroup_file_write
  - kernel/cgroup_pids.c:pids_max_write
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - lib/kstrtox.c:_kstrtol
  - lib/kstrtox.c:kstrtoint_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtol_from_user
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/rapidio/rio-sysfs.c:bus_scan_store
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/power/power_supply_sysfs.c:power_supply_store_property
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
  - drivers/md/bitmap.c:location_store
  - drivers/md/bitmap.c:location_store
```
**Symbols:**

```
ffffffff814021c0-ffffffff81402253: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81449d70)
Location: lib/kstrtox.c:146
Inline: True
Direct callers:
  - kernel/params.c:param_set_long
  - kernel/cgroup.c:cgroup_file_write
  - kernel/cgroup_pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - lib/kstrtox.c:kstrtol_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:_kstrtol
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:bus_scan_store
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/rtc/rtc-sysfs.c:offset_store
  - drivers/power/power_supply_sysfs.c:power_supply_store_property
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff81449d70-ffffffff81449e03: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81468730)
Location: lib/kstrtox.c:142
Inline: True
Direct callers:
  - kernel/params.c:param_set_long
  - kernel/cgroup.c:cgroup_file_write
  - kernel/cgroup_pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - lib/kstrtox.c:kstrtol_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:_kstrtol
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:bus_scan_store
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/rtc/rtc-sysfs.c:offset_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff81468730-ffffffff814687c3: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8146de30)
Location: lib/kstrtox.c:144
Inline: True
Direct callers:
  - kernel/params.c:param_set_long
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - lib/kstrtox.c:kstrtol_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:_kstrtol
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:bus_scan_store
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/rtc/rtc-sysfs.c:offset_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff8146de30-ffffffff8146deb7: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8149a160)
Location: lib/kstrtox.c:145
Inline: True
Direct callers:
  - kernel/params.c:param_set_long
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:replace_preds
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - lib/kstrtox.c:kstrtol_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:_kstrtol
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:bus_scan_store
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/rtc/rtc-sysfs.c:offset_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff8149a160-ffffffff8149a1e7: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814cf410)
Location: lib/kstrtox.c:145
Inline: True
Direct callers:
  - kernel/params.c:param_set_long
  - kernel/time/ntp.c:ntp_tick_adj_setup
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - lib/kstrtox.c:kstrtol_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:_kstrtol
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:bus_scan_store
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/rtc/rtc-sysfs.c:offset_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff814cf410-ffffffff814cf497: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814e3d20)
Location: lib/kstrtox.c:145
Inline: True
Direct callers:
  - kernel/params.c:param_set_long
  - kernel/time/ntp.c:ntp_tick_adj_setup
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - lib/kstrtox.c:kstrtol_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:_kstrtol
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:bus_scan_store
  - drivers/base/core.c:device_store_int
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/rtc/sysfs.c:offset_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff814e3d20-ffffffff814e3da7: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81510100)
Location: lib/kstrtox.c:145
Inline: True
Direct callers:
  - kernel/params.c:param_set_long
  - kernel/time/ntp.c:ntp_tick_adj_setup
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - lib/kstrtox.c:kstrtol_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:_kstrtol
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:scan_store
  - drivers/base/core.c:device_store_int
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/rtc/sysfs.c:offset_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff81510100-ffffffff81510187: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8152e000)
Location: lib/kstrtox.c:145
Inline: True
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:ptc_proc_write
  - kernel/params.c:param_set_long
  - kernel/time/ntp.c:ntp_tick_adj_setup
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - lib/kstrtox.c:kstrtol_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:_kstrtol
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:scan_store
  - drivers/base/core.c:device_store_int
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/rtc/sysfs.c:offset_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff8152e000-ffffffff8152e087: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8159216f)
Location: lib/kstrtox.c:145
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:_kstrtol
  - lib/kstrtox.c:_kstrtol
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:ptc_proc_write
  - kernel/params.c:param_set_long
  - kernel/time/ntp.c:ntp_tick_adj_setup
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - security/keys/trusted-keys/trusted_tpm1.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:scan_store
  - drivers/base/core.c:device_store_int
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/rtc/sysfs.c:offset_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff81591e50-ffffffff81591ed6: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815aecaf)
Location: lib/kstrtox.c:143
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:_kstrtol
  - lib/kstrtox.c:_kstrtol
Direct callers:
  - kernel/params.c:param_set_long
  - kernel/time/ntp.c:ntp_tick_adj_setup
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - security/keys/trusted-keys/trusted_tpm1.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:scan_store
  - drivers/base/core.c:device_store_int
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/rtc/sysfs.c:offset_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff815ae990-ffffffff815aea16: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815b98cf)
Location: lib/kstrtox.c:150
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:_kstrtol
  - lib/kstrtox.c:_kstrtol
Direct callers:
  - kernel/params.c:param_set_long
  - kernel/sched/core.c:setup_resched_latency_warn_ms
  - kernel/time/ntp.c:ntp_tick_adj_setup
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:scan_store
  - drivers/base/core.c:device_store_int
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/rtc/sysfs.c:offset_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff815b9490-ffffffff815b9516: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8162020d)
Location: lib/kstrtox.c:151
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:_kstrtol
  - lib/kstrtox.c:_kstrtol
Direct callers:
  - kernel/params.c:param_set_long
  - kernel/sched/core.c:setup_resched_latency_warn_ms
  - kernel/time/ntp.c:ntp_tick_adj_setup
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:scan_store
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/base/core.c:device_store_int
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/rtc/sysfs.c:offset_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff8161fd70-ffffffff8161fdf6: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff816ee1d0)
Location: lib/kstrtox.c:156
Inline: False
Direct callers:
  - kernel/params.c:param_set_long
  - kernel/sched/core.c:setup_resched_latency_warn_ms
  - kernel/time/ntp.c:ntp_tick_adj_setup
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:kstrtos8
  - lib/kstrtox.c:kstrtos16
  - lib/kstrtox.c:kstrtoint
  - lib/kstrtox.c:_kstrtol
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:scan_store
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/base/core.c:device_store_int
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/rtc/sysfs.c:offset_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff816ee1d0-ffffffff816ee25b: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff817dece0)
Location: lib/kstrtox.c:156
Inline: False
Direct callers:
  - kernel/params.c:param_set_long
  - kernel/sched/core.c:setup_resched_latency_warn_ms
  - kernel/time/ntp.c:ntp_tick_adj_setup
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:kstrtos8
  - lib/kstrtox.c:kstrtos16
  - lib/kstrtox.c:kstrtoint
  - lib/kstrtox.c:_kstrtol
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:scan_store
  - drivers/base/core.c:device_store_int
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/rtc/sysfs.c:offset_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff817dece0-ffffffff817ded6b: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8181e4c0)
Location: lib/kstrtox.c:156
Inline: False
Direct callers:
  - kernel/params.c:param_set_long
  - kernel/sched/core.c:setup_resched_latency_warn_ms
  - kernel/time/ntp.c:ntp_tick_adj_setup
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:kstrtos8
  - lib/kstrtox.c:kstrtos16
  - lib/kstrtox.c:kstrtoint
  - lib/kstrtox.c:_kstrtol
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:scan_store
  - drivers/base/core.c:device_store_int
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/rtc/sysfs.c:offset_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff8181e4c0-ffffffff8181e54b: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81864330)
Location: lib/kstrtox.c:156
Inline: False
Direct callers:
  - kernel/params.c:param_set_long
  - kernel/sched/core.c:setup_resched_latency_warn_ms
  - kernel/time/ntp.c:ntp_tick_adj_setup
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_inject.c:parse_field
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:kstrtos8
  - lib/kstrtox.c:kstrtos16
  - lib/kstrtox.c:kstrtoint
  - lib/kstrtox.c:_kstrtol
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:scan_store
  - drivers/base/core.c:device_store_int
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
  - drivers/rtc/sysfs.c:offset_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff81864330-ffffffff818643bb: kstrtoll (STB_GLOBAL)
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
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffff80001063a498)
Location: lib/kstrtox.c:145
Inline: True
Direct callers:
  - kernel/params.c:param_set_long
  - kernel/time/ntp.c:ntp_tick_adj_setup
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - lib/kstrtox.c:kstrtol_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:_kstrtol
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:scan_store
  - drivers/base/core.c:device_store_int
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/rtc/sysfs.c:offset_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/power/reset/vexpress-poweroff.c:vexpress_reset_active_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffff80001063a498-ffff80001063a534: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (c07dffb8)
Location: lib/kstrtox.c:145
Inline: True
Direct callers:
  - kernel/time/ntp.c:ntp_tick_adj_setup
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:parse_pred
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - lib/kstrtox.c:kstrtol_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
```
**Symbols:**

```
c07dffb8-c07e0074: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (c0000000007e1280)
Location: lib/kstrtox.c:145
Inline: True
Direct callers:
  - kernel/params.c:param_set_long
  - kernel/time/ntp.c:ntp_tick_adj_setup
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - lib/kstrtox.c:kstrtol_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:_kstrtol
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:scan_store
  - drivers/base/core.c:device_store_int
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/rtc/sysfs.c:offset_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
c0000000007e1280-c0000000007e134c: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffe000466b80)
Location: lib/kstrtox.c:145
Inline: True
Direct callers:
  - kernel/params.c:param_set_long
  - kernel/time/ntp.c:ntp_tick_adj_setup
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:parse_pred
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - lib/kstrtox.c:kstrtol_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:_kstrtol
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:scan_store
  - drivers/base/core.c:device_store_int
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/rtc/sysfs.c:offset_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffe000466b80-ffffffe000466bec: kstrtoll (STB_GLOBAL)
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
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815265e0)
Location: lib/kstrtox.c:145
Inline: True
Direct callers:
  - kernel/params.c:param_set_long
  - kernel/time/ntp.c:ntp_tick_adj_setup
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - lib/kstrtox.c:kstrtol_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:_kstrtol
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:scan_store
  - drivers/base/core.c:device_store_int
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/rtc/sysfs.c:offset_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff815265e0-ffffffff81526667: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815168c0)
Location: lib/kstrtox.c:145
Inline: True
Direct callers:
  - kernel/params.c:param_set_long
  - kernel/time/ntp.c:ntp_tick_adj_setup
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - lib/kstrtox.c:kstrtol_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:_kstrtol
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:scan_store
  - drivers/acpi/nfit/core.c:hw_error_scrub_store
  - drivers/base/core.c:device_store_int
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/rtc/sysfs.c:offset_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff815168c0-ffffffff81516947: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81522670)
Location: lib/kstrtox.c:145
Inline: True
Direct callers:
  - kernel/params.c:param_set_long
  - kernel/time/ntp.c:ntp_tick_adj_setup
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - lib/kstrtox.c:kstrtol_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:_kstrtol
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:scan_store
  - drivers/base/core.c:device_store_int
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/rtc/sysfs.c:offset_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff81522670-ffffffff815226f7: kstrtoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int kstrtoll(const char *s, unsigned int base, long long int *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8153bff0)
Location: lib/kstrtox.c:145
Inline: True
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:ptc_proc_write
  - kernel/params.c:param_set_long
  - kernel/time/ntp.c:ntp_tick_adj_setup
  - kernel/cgroup/cgroup.c:cgroup_file_write
  - kernel/cgroup/pids.c:pids_max_write
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - security/keys/trusted.c:datablob_parse
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
  - block/blk-sysfs.c:queue_wb_lat_store
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - lib/kstrtox.c:kstrtol_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:_kstrtol
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/rapidio/rio-sysfs.c:scan_store
  - drivers/base/core.c:device_store_int
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/rtc/sysfs.c:offset_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/hwmon/hwmon.c:hwmon_attr_store
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff8153bff0-ffffffff8153c077: kstrtoll (STB_GLOBAL)
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
