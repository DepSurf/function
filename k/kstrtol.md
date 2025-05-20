# Function: <code>kstrtol</code>

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
In kernel/params.c (ffffffff8109ee96)
Location: include/linux/kernel.h:319
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/time/ntp.c (ffffffff81f80597)
Location: include/linux/kernel.h:319
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff8114575c)
Location: include/linux/kernel.h:319
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
```
```
In kernel/trace/trace_probe.c (ffffffff8116da69)
Location: include/linux/kernel.h:319
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
```
```
In security/keys/trusted.c (ffffffff81336e88)
Location: include/linux/kernel.h:319
Inline: True
Inline callers:
  - security/keys/trusted.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81339365)
Location: include/linux/kernel.h:319
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (ffffffff814025fa)
Location: include/linux/kernel.h:319
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtol_from_user
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff814279af)
Location: include/linux/kernel.h:319
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff8145c099)
Location: include/linux/kernel.h:319
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:bus_scan_store
```
```
In drivers/base/power/sysfs.c (ffffffff81553827)
Location: include/linux/kernel.h:319
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffffffff815d1a46)
Location: include/linux/kernel.h:319
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/power/power_supply_sysfs.c (ffffffff8167f8a1)
Location: include/linux/kernel.h:319
Inline: True
Inline callers:
  - drivers/power/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/md/md.c (ffffffff8168d06f)
Location: include/linux/kernel.h:319
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
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
In kernel/params.c (ffffffff810a2556)
Location: include/linux/kernel.h:326
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/time/ntp.c (ffffffff81fa9603)
Location: include/linux/kernel.h:326
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff8117b039)
Location: include/linux/kernel.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
```
```
In security/keys/trusted.c (ffffffff8136c40a)
Location: include/linux/kernel.h:326
Inline: True
Inline callers:
  - security/keys/trusted.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8136ea48)
Location: include/linux/kernel.h:326
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (ffffffff8144a2ad)
Location: include/linux/kernel.h:326
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtol_from_user
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81473269)
Location: include/linux/kernel.h:326
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff814aa229)
Location: include/linux/kernel.h:326
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:bus_scan_store
```
```
In drivers/base/power/sysfs.c (ffffffff815a5827)
Location: include/linux/kernel.h:326
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffffffff8162aee6)
Location: include/linux/kernel.h:326
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff816d6a06)
Location: include/linux/kernel.h:326
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:offset_store
```
```
In drivers/power/power_supply_sysfs.c (ffffffff816e0711)
Location: include/linux/kernel.h:326
Inline: True
Inline callers:
  - drivers/power/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/md/md.c (ffffffff816ee74f)
Location: include/linux/kernel.h:326
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
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
In kernel/params.c (ffffffff810a7616)
Location: include/linux/kernel.h:328
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/time/ntp.c (ffffffff81fe512e)
Location: include/linux/kernel.h:328
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff81186c49)
Location: include/linux/kernel.h:328
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
```
```
In security/keys/trusted.c (ffffffff81382c2a)
Location: include/linux/kernel.h:328
Inline: True
Inline callers:
  - security/keys/trusted.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81384da8)
Location: include/linux/kernel.h:328
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (ffffffff81468c6d)
Location: include/linux/kernel.h:328
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtol_from_user
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81495489)
Location: include/linux/kernel.h:328
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff814cc339)
Location: include/linux/kernel.h:328
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:bus_scan_store
```
```
In drivers/base/power/sysfs.c (ffffffff815d3fe7)
Location: include/linux/kernel.h:328
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffffffff8165dab6)
Location: include/linux/kernel.h:328
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff817066e6)
Location: include/linux/kernel.h:328
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:offset_store
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81710b81)
Location: include/linux/kernel.h:328
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (ffffffff81713d94)
Location: include/linux/kernel.h:328
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (ffffffff8171fecf)
Location: include/linux/kernel.h:328
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
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
In kernel/params.c (ffffffff810a4556)
Location: include/linux/kernel.h:341
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/time/ntp.c (ffffffff820c5db2)
Location: include/linux/kernel.h:341
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff811898d9)
Location: include/linux/kernel.h:341
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
```
```
In security/keys/trusted.c (ffffffff813972dc)
Location: include/linux/kernel.h:341
Inline: True
Inline callers:
  - security/keys/trusted.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81399425)
Location: include/linux/kernel.h:341
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (ffffffff8146e356)
Location: include/linux/kernel.h:341
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtol_from_user
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8149ee89)
Location: include/linux/kernel.h:341
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff814d8299)
Location: include/linux/kernel.h:341
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:bus_scan_store
```
```
In drivers/base/power/sysfs.c (ffffffff815e8b50)
Location: include/linux/kernel.h:341
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffffffff816724f6)
Location: include/linux/kernel.h:341
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff8171c2c6)
Location: include/linux/kernel.h:341
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:offset_store
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81728f39)
Location: include/linux/kernel.h:341
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (ffffffff8172c244)
Location: include/linux/kernel.h:341
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (ffffffff81737c2f)
Location: include/linux/kernel.h:341
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810aaba6)
Location: include/linux/kernel.h:378
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/time/ntp.c (ffffffff826ce458)
Location: include/linux/kernel.h:378
Inline: True
```
```
In kernel/audit.c (ffffffff826d096a)
Location: include/linux/kernel.h:378
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff8119755f)
Location: include/linux/kernel.h:378
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
```
```
In security/keys/trusted.c (ffffffff813bcabc)
Location: include/linux/kernel.h:378
Inline: True
Inline callers:
  - security/keys/trusted.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813bec35)
Location: include/linux/kernel.h:378
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (ffffffff8149a686)
Location: include/linux/kernel.h:378
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtol_from_user
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff814dd9c9)
Location: include/linux/kernel.h:378
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81518479)
Location: include/linux/kernel.h:378
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:bus_scan_store
```
```
In drivers/base/power/sysfs.c (ffffffff8164fe60)
Location: include/linux/kernel.h:378
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffffffff816dbae6)
Location: include/linux/kernel.h:378
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff8178d546)
Location: include/linux/kernel.h:378
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:offset_store
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff8179a6bf)
Location: include/linux/kernel.h:378
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (ffffffff8179da14)
Location: include/linux/kernel.h:378
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (ffffffff817a9c7f)
Location: include/linux/kernel.h:378
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
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
In kernel/params.c (ffffffff810b1815)
Location: include/linux/kernel.h:394
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/time/ntp.c (ffffffff826f8ba6)
Location: include/linux/kernel.h:394
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_tick_adj_setup
```
```
In kernel/trace/trace_probe.c (ffffffff811acd73)
Location: include/linux/kernel.h:394
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
```
```
In security/keys/trusted.c (ffffffff813ed8ca)
Location: include/linux/kernel.h:394
Inline: True
Inline callers:
  - security/keys/trusted.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813efa4d)
Location: include/linux/kernel.h:394
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (ffffffff814cf945)
Location: include/linux/kernel.h:394
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtol_from_user
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8150cbdb)
Location: include/linux/kernel.h:394
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff8154e069)
Location: include/linux/kernel.h:394
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:bus_scan_store
```
```
In drivers/base/power/sysfs.c (ffffffff8168b78c)
Location: include/linux/kernel.h:394
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffffffff81718295)
Location: include/linux/kernel.h:394
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff817cfba1)
Location: include/linux/kernel.h:394
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:offset_store
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff817e1b61)
Location: include/linux/kernel.h:394
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (ffffffff817e4fa6)
Location: include/linux/kernel.h:394
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (ffffffff817f1fc1)
Location: include/linux/kernel.h:394
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
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
In kernel/params.c (ffffffff810ba955)
Location: include/linux/kernel.h:427
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/trace/trace_probe.c (ffffffff811bb9b3)
Location: include/linux/kernel.h:427
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
```
```
In security/keys/trusted.c (ffffffff814090cb)
Location: include/linux/kernel.h:427
Inline: True
Inline callers:
  - security/keys/trusted.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140aca4)
Location: include/linux/kernel.h:427
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (ffffffff814e4255)
Location: include/linux/kernel.h:427
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtol_from_user
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8152223b)
Location: include/linux/kernel.h:427
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815654c9)
Location: include/linux/kernel.h:427
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:bus_scan_store
```
```
In drivers/base/core.c (ffffffff8169c44e)
Location: include/linux/kernel.h:427
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_int
```
```
In drivers/base/power/sysfs.c (ffffffff816ab9bc)
Location: include/linux/kernel.h:427
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffffffff8173a8e5)
Location: include/linux/kernel.h:427
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/rtc/sysfs.c (ffffffff817f6b61)
Location: include/linux/kernel.h:427
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:offset_store
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff8180d2e6)
Location: include/linux/kernel.h:427
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (ffffffff8181085a)
Location: include/linux/kernel.h:427
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (ffffffff8181dec1)
Location: include/linux/kernel.h:427
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
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
In kernel/params.c (ffffffff810c0865)
Location: include/linux/kernel.h:386
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/trace/trace_probe.c (ffffffff811cb183)
Location: include/linux/kernel.h:386
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
```
```
In security/keys/trusted.c (ffffffff81435c31)
Location: include/linux/kernel.h:386
Inline: True
Inline callers:
  - security/keys/trusted.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81438754)
Location: include/linux/kernel.h:386
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (ffffffff81510635)
Location: include/linux/kernel.h:386
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtol_from_user
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8155074b)
Location: include/linux/kernel.h:386
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81595869)
Location: include/linux/kernel.h:386
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:scan_store
```
```
In drivers/base/core.c (ffffffff816d51fe)
Location: include/linux/kernel.h:386
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_int
```
```
In drivers/base/power/sysfs.c (ffffffff816e555c)
Location: include/linux/kernel.h:386
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffffffff81776535)
Location: include/linux/kernel.h:386
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/rtc/sysfs.c (ffffffff81837851)
Location: include/linux/kernel.h:386
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:offset_store
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff8184f073)
Location: include/linux/kernel.h:386
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (ffffffff818528fa)
Location: include/linux/kernel.h:386
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (ffffffff818600e1)
Location: include/linux/kernel.h:386
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
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
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109538a)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:ptc_proc_write
```
```
In kernel/params.c (ffffffff810c6c65)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/trace/trace_probe.c (ffffffff811d7093)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
```
```
In security/keys/trusted.c (ffffffff8144f9d1)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - security/keys/trusted.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81452594)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (ffffffff8152e535)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtol_from_user
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81571bfb)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815b6ae9)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:scan_store
```
```
In drivers/base/core.c (ffffffff816f8fae)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_int
```
```
In drivers/base/power/sysfs.c (ffffffff8170983c)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffffffff8179a495)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/rtc/sysfs.c (ffffffff818691c1)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:offset_store
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81880a83)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (ffffffff8188433a)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (ffffffff81891d11)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
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
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109b6a9)
Location: include/linux/kernel.h:379
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:ptc_proc_write
```
```
In kernel/params.c (ffffffff810cec85)
Location: include/linux/kernel.h:379
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/trace/trace_probe.c (ffffffff811f3efa)
Location: include/linux/kernel.h:379
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_update_arg
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814a11cc)
Location: include/linux/kernel.h:379
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814a43b4)
Location: include/linux/kernel.h:379
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (0)
Location: include/linux/kernel.h:379
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81615f2b)
Location: include/linux/kernel.h:379
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81660289)
Location: include/linux/kernel.h:379
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:scan_store
```
```
In drivers/base/core.c (ffffffff817b1e7e)
Location: include/linux/kernel.h:379
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_int
```
```
In drivers/base/power/sysfs.c (ffffffff817c492c)
Location: include/linux/kernel.h:379
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffffffff8185e907)
Location: include/linux/kernel.h:379
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-sata.c (ffffffff81868735)
Location: include/linux/kernel.h:379
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
```
```
In drivers/rtc/sysfs.c (ffffffff8193ce51)
Location: include/linux/kernel.h:379
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:offset_store
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff8194f1f0)
Location: include/linux/kernel.h:379
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (ffffffff81952e9a)
Location: include/linux/kernel.h:379
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (ffffffff819601c1)
Location: include/linux/kernel.h:379
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810c97b5)
Location: include/linux/kernel.h:231
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/trace/trace_probe.c (ffffffff811f28aa)
Location: include/linux/kernel.h:231
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_update_arg
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814beb8c)
Location: include/linux/kernel.h:231
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c1bb4)
Location: include/linux/kernel.h:231
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (0)
Location: include/linux/kernel.h:231
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8163c8ab)
Location: include/linux/kernel.h:231
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81681549)
Location: include/linux/kernel.h:231
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:scan_store
```
```
In drivers/base/core.c (ffffffff817c674e)
Location: include/linux/kernel.h:231
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_int
```
```
In drivers/base/power/sysfs.c (ffffffff817d93bc)
Location: include/linux/kernel.h:231
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffffffff8186d927)
Location: include/linux/kernel.h:231
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-sata.c (ffffffff81877545)
Location: include/linux/kernel.h:231
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
```
```
In drivers/rtc/sysfs.c (ffffffff81942e61)
Location: include/linux/kernel.h:231
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:offset_store
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81954c10)
Location: include/linux/kernel.h:231
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (ffffffff81957d36)
Location: include/linux/kernel.h:231
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (ffffffff81966ab1)
Location: include/linux/kernel.h:231
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
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
In kernel/params.c (ffffffff810cb2c5)
Location: include/linux/kernel.h:241
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/sched/core.c (ffffffff831e5615)
Location: include/linux/kernel.h:241
Inline: True
Inline callers:
  - kernel/sched/core.c:setup_resched_latency_warn_ms
```
```
In kernel/trace/trace_probe.c (ffffffff811f373a)
Location: include/linux/kernel.h:241
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_update_arg
```
```
In security/keys/trusted-keys/trusted_core.c (ffffffff814c4629)
Location: include/linux/kernel.h:241
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c8034)
Location: include/linux/kernel.h:241
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (0)
Location: include/linux/kernel.h:241
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff816203eb)
Location: include/linux/kernel.h:241
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81664399)
Location: include/linux/kernel.h:241
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:scan_store
```
```
In drivers/base/core.c (ffffffff817a9c3e)
Location: include/linux/kernel.h:241
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_int
```
```
In drivers/base/power/sysfs.c (ffffffff817bd78c)
Location: include/linux/kernel.h:241
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffffffff8184d2e7)
Location: include/linux/kernel.h:241
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-sata.c (ffffffff81859d25)
Location: include/linux/kernel.h:241
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
```
```
In drivers/rtc/sysfs.c (ffffffff81926681)
Location: include/linux/kernel.h:241
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:offset_store
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81938a7b)
Location: include/linux/kernel.h:241
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (ffffffff8193b976)
Location: include/linux/kernel.h:241
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (ffffffff8194ac11)
Location: include/linux/kernel.h:241
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
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
In kernel/params.c (ffffffff810de425)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/sched/core.c (ffffffff832c950d)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:setup_resched_latency_warn_ms
```
```
In kernel/trace/trace_probe.c (ffffffff812249fa)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_update_arg
```
```
In security/keys/trusted-keys/trusted_core.c (ffffffff8151d009)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81520b24)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (0)
Location: include/linux/kstrtox.h:58
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8168f90b)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff816d7279)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:scan_store
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8170c063)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
```
In drivers/base/core.c (ffffffff81832dbe)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_int
```
```
In drivers/base/power/sysfs.c (ffffffff81847b0c)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffffffff818da917)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-sata.c (ffffffff818e7c05)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
```
```
In drivers/rtc/sysfs.c (ffffffff819c95c1)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:offset_store
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff819dd02b)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (ffffffff819e01a6)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (ffffffff819efcc1)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
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
In kernel/params.c (ffffffff810f8155)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/sched/core.c (ffffffff8347c6d1)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:setup_resched_latency_warn_ms
```
```
In kernel/trace/trace_probe.c (ffffffff81264802)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_update_arg
```
```
In security/keys/trusted-keys/trusted_core.c (ffffffff815b02fd)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff815b4279)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (0)
Location: include/linux/kstrtox.h:58
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff817aec83)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81800c71)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:scan_store
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8183a663)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
```
```
In drivers/base/core.c (ffffffff81974616)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_int
```
```
In drivers/base/power/sysfs.c (ffffffff8198c6e4)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2eddf)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-sata.c (ffffffff81a3951b)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
```
```
In drivers/rtc/sysfs.c (ffffffff81b2a8d9)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:offset_store
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81b4149a)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (ffffffff81b4492e)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (ffffffff81b57389)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
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
In kernel/params.c (ffffffff8111ab25)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/sched/core.c (ffffffff83ea7aca)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:setup_resched_latency_warn_ms
```
```
In kernel/trace/trace_probe.c (ffffffff812b6352)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_update_arg
```
```
In security/keys/trusted-keys/trusted_core.c (ffffffff8165abbd)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8165f0f9)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (0)
Location: include/linux/kstrtox.h:58
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff818c81f3)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff8192e2a1)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:scan_store
```
```
In drivers/base/core.c (ffffffff81adfd76)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_int
```
```
In drivers/base/power/sysfs.c (ffffffff81afc284)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffffffff81bb22ff)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-sata.c (ffffffff81bbe62b)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
```
```
In drivers/rtc/sysfs.c (ffffffff81cbe529)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:offset_store
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81cd7a2a)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (ffffffff81cdb9fe)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (ffffffff81cf03b9)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
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
In kernel/params.c (ffffffff81127d95)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/sched/core.c (ffffffff836cc43a)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:setup_resched_latency_warn_ms
```
```
In kernel/trace/trace_probe.c (ffffffff812d9842)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_update_arg
```
```
In security/keys/trusted-keys/trusted_core.c (ffffffff816934bd)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81697a49)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (0)
Location: include/linux/kstrtox.h:58
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8190b9e5)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81972531)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:scan_store
```
```
In drivers/base/core.c (ffffffff81b2df96)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_int
```
```
In drivers/base/power/sysfs.c (ffffffff81b4a674)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffffffff81c0982f)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-sata.c (ffffffff81c15e8b)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
```
```
In drivers/rtc/sysfs.c (ffffffff81d25e39)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:offset_store
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81d3fa5a)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (ffffffff81d43d5e)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (ffffffff81d59199)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
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
In kernel/params.c (ffffffff81132375)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/sched/core.c (ffffffff838fd83a)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:setup_resched_latency_warn_ms
```
```
In kernel/trace/trace_probe.c (ffffffff812f77a2)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_update_arg
```
```
In security/keys/trusted-keys/trusted_core.c (ffffffff816cfa8d)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff816d40c9)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (0)
Location: include/linux/kstrtox.h:58
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81953705)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff819bc5a1)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:scan_store
```
```
In drivers/base/core.c (ffffffff81b85796)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_int
```
```
In drivers/base/power/sysfs.c (ffffffff81ba2a64)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-sata.c (ffffffff81c6b06b)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_ncq_prio_enable_store
```
```
In drivers/rtc/sysfs.c (ffffffff81ddbba9)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:offset_store
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81df640a)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (ffffffff81dfa72e)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (ffffffff81e10009)
Location: include/linux/kstrtox.h:58
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
</details>
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
In kernel/params.c (ffff800010125ac4)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/trace/trace_probe.c (ffff800010257340)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
```
```
In security/keys/trusted.c (ffff80001053b090)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - security/keys/trusted.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffff80001053cc30)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (ffff80001063aa7c)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtol_from_user
```
```
In drivers/gpio/gpiolib-sysfs.c (ffff8000106c95b0)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffff80001073f300)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:scan_store
```
```
In drivers/base/core.c (ffff8000108e3034)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_int
```
```
In drivers/base/power/sysfs.c (ffff8000108f7754)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffff8000109a3c30)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/rtc/sysfs.c (ffff800010aab9bc)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:offset_store
```
```
In drivers/power/reset/vexpress-poweroff.c (ffff800010aca2fc)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/power/reset/vexpress-poweroff.c:vexpress_reset_active_store
```
```
In drivers/power/supply/power_supply_sysfs.c (ffff800010acce00)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (ffff800010ad0e94)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (ffff800010ae38d4)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
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
In kernel/params.c (c03786f0)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/trace/trace_probe.c (c0489608)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
```
```
In security/keys/trusted.c (c06f0bc0)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - security/keys/trusted.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (c06f36f4)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (c07e01b0)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtol_from_user
```
```
In drivers/gpio/gpiolib-sysfs.c (c0866a90)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (c08c3e40)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:scan_store
```
```
In drivers/base/core.c (c09d1bac)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_int
```
```
In drivers/base/power/sysfs.c (c09e3618)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (c0a74508)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/rtc/sysfs.c (c0b89fd4)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:offset_store
```
```
In drivers/power/reset/vexpress-poweroff.c (c0bab33c)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/power/reset/vexpress-poweroff.c:vexpress_reset_active_store
```
```
In drivers/power/supply/power_supply_sysfs.c (c0bad680)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (c0bb1944)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (c0bc5338)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
```
In sound/soc/soc-core.c (c0ca0db8)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - sound/soc/soc-core.c:pmdown_time_set
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
In kernel/params.c (c00000000016f9cc)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/trace/trace_probe.c (c0000000002f8c9c)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
```
```
In security/keys/trusted.c (c000000000689938)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - security/keys/trusted.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (c00000000068d404)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (c0000000007e1a24)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtol_from_user
```
```
In drivers/gpio/gpiolib-sysfs.c (c000000000847180)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (c000000000898e6c)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:scan_store
```
```
In drivers/base/core.c (c000000000977dc4)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_int
```
```
In drivers/base/power/sysfs.c (c0000000009930b4)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (c000000000a6a7d0)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/rtc/sysfs.c (c000000000b8da94)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:offset_store
```
```
In drivers/power/supply/power_supply_sysfs.c (c000000000baf480)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (c000000000bb5304)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (c000000000bccd08)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
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
In kernel/params.c (ffffffe0000dd6f8)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In security/keys/trusted.c (ffffffe000398f2a)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - security/keys/trusted.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039ac32)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (ffffffe000466f50)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtol_from_user
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffe0004aca1a)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffe0004ee85a)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:scan_store
```
```
In drivers/base/core.c (ffffffe0005784bc)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_int
```
```
In drivers/base/power/sysfs.c (ffffffe00058826e)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffffffe000603c9e)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/rtc/sysfs.c (ffffffe0006b648e)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:offset_store
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffe0006c9eac)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (ffffffe0006cd81e)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (ffffffe0006da08c)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
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
In kernel/params.c (ffffffff810c0fe5)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/trace/trace_probe.c (ffffffff811cf6b3)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
```
```
In security/keys/trusted.c (ffffffff81447fb1)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - security/keys/trusted.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8144ab74)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (ffffffff81526b15)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtol_from_user
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff815673bb)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815aad59)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:scan_store
```
```
In drivers/base/core.c (ffffffff816be79e)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_int
```
```
In drivers/base/power/sysfs.c (ffffffff816cef8c)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffffffff8175f585)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/rtc/sysfs.c (ffffffff8181be71)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:offset_store
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81828ff3)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (ffffffff8182a1ba)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (ffffffff81837b91)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
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
In kernel/params.c (ffffffff810af7d5)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/trace/trace_probe.c (ffffffff811c2483)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
```
```
In security/keys/trusted.c (ffffffff81438a01)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - security/keys/trusted.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8143b5c4)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (ffffffff81516df5)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtol_from_user
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8155820b)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81599ef9)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:scan_store
```
```
In drivers/acpi/nfit/core.c (ffffffff815f4760)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:hw_error_scrub_store
```
```
In drivers/base/core.c (ffffffff81699a4e)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_int
```
```
In drivers/base/power/sysfs.c (ffffffff816aa2bc)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffffffff8173f3f5)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/rtc/sysfs.c (ffffffff817e3561)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:offset_store
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff817f0683)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (ffffffff817f184a)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (ffffffff817ff201)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
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
In kernel/params.c (ffffffff810c0535)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/trace/trace_probe.c (ffffffff811cd483)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
```
```
In security/keys/trusted.c (ffffffff81444051)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - security/keys/trusted.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81446c14)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (ffffffff81522ba5)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtol_from_user
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81565f2b)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815ab2e9)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:scan_store
```
```
In drivers/base/core.c (ffffffff816ecc6e)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_int
```
```
In drivers/base/power/sysfs.c (ffffffff816fd4fc)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffffffff8178f315)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/rtc/sysfs.c (ffffffff8185d351)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:offset_store
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81875f33)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (ffffffff818797ea)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (ffffffff818871c1)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
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
In arch/x86/platform/uv/tlb_uv.c (ffffffff810968fa)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:ptc_proc_write
```
```
In kernel/params.c (ffffffff810c8965)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - kernel/params.c:param_set_long
```
```
In kernel/trace/trace_probe.c (ffffffff811db6e3)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
```
```
In security/keys/trusted.c (ffffffff8145b381)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - security/keys/trusted.c:datablob_parse
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8145df44)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_alloc
```
```
In lib/kstrtox.c (ffffffff8153c525)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtol_from_user
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8157fe4b)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815c4c79)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:scan_store
```
```
In drivers/base/core.c (ffffffff817074ae)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/base/core.c:device_store_int
```
```
In drivers/base/power/sysfs.c (ffffffff81717d8c)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:autosuspend_delay_ms_store
```
```
In drivers/ata/libata-scsi.c (ffffffff817a8893)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/rtc/sysfs.c (ffffffff818785c1)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:offset_store
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffff818918d3)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
```
In drivers/hwmon/hwmon.c (ffffffff818951ca)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:hwmon_attr_store
```
```
In drivers/md/md.c (ffffffff818a3321)
Location: include/linux/kernel.h:390
Inline: True
Inline callers:
  - drivers/md/md.c:sync_force_parallel_store
  - drivers/md/md.c:level_store
```
</details>
</li>
</ul>

## Differences
