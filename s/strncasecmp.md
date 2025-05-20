# Function: <code>strncasecmp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff813f2030)
Location: lib/string.c:41
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/thermal/thermal_core.c:thermal_zone_get_zone_by_name
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/thermal/thermal_core.c:thermal_unregister_governor
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/cpufreq/cpufreq.c:find_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffff813f2030-ffffffff813f20b9: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff814389d0)
Location: lib/string.c:41
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/thermal/thermal_core.c:thermal_zone_get_zone_by_name
  - drivers/thermal/thermal_core.c:thermal_unregister_governor
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/cpufreq/cpufreq.c:find_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffff814389d0-ffffffff81438a5c: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff814559c0)
Location: lib/string.c:41
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/thermal/thermal_core.c:thermal_zone_get_zone_by_name
  - drivers/thermal/thermal_core.c:thermal_unregister_governor
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/cpufreq/cpufreq.c:find_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffff814559c0-ffffffff81455a4c: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff818f72f0)
Location: lib/string.c:41
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/thermal/thermal_core.c:thermal_unregister_governor
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/cpufreq/cpufreq.c:find_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffff818f72f0-ffffffff818f737f: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8197dcf0)
Location: lib/string.c:42
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/thermal/thermal_core.c:thermal_unregister_governor
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/cpufreq/cpufreq.c:find_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffff8197dcf0-ffffffff8197dd7f: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff819da1d0)
Location: lib/string.c:42
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_unregister_governor
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/cpufreq/cpufreq.c:find_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffff819da1d0-ffffffff819da26c: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a123f0)
Location: lib/string.c:43
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_unregister_governor
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/cpufreq/cpufreq.c:find_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffff81a123f0-ffffffff81a1248c: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a818c0)
Location: lib/string.c:43
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/cpufreq/cpufreq.c:find_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffff81a818c0-ffffffff81a8195c: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ab8ac0)
Location: lib/string.c:43
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/cpufreq/cpufreq.c:cpufreq_parse_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_parse_policy
  - drivers/cpufreq/cpufreq.c:find_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_find_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffff81ab8ac0-ffffffff81ab8b5c: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815f3780)
Location: lib/string.c:43
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_parsebp
  - kernel/debug/kdb/kdb_bp.c:kdb_parsebp
  - kernel/debug/kdb/kdb_bp.c:kdb_parsebp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - drivers/acpi/battery.c:acpi_battery_quirks
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/cpufreq/cpufreq.c:cpufreq_register_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:get_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffff815f3780-ffffffff815f3847: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81617e10)
Location: lib/string.c:43
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_parsebp
  - kernel/debug/kdb/kdb_bp.c:kdb_parsebp
  - kernel/debug/kdb/kdb_bp.c:kdb_parsebp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - drivers/acpi/battery.c:acpi_battery_quirks
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/cpufreq/cpufreq.c:cpufreq_register_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:get_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffff81617e10-ffffffff81617ed4: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815fb460)
Location: lib/string.c:43
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - drivers/acpi/battery.c:acpi_battery_quirks
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/cpufreq/cpufreq.c:cpufreq_register_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:get_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffff815fb460-ffffffff815fb500: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81668d30)
Location: lib/string.c:44
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - lib/bitmap.c:bitmap_parse_region
  - drivers/acpi/battery.c:acpi_battery_quirks
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/cpufreq/cpufreq.c:cpufreq_register_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:get_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffff81668d30-ffffffff81668dd0: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81782700)
Location: lib/string.c:39
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - lib/bitmap.c:bitmap_parselist
  - drivers/acpi/battery.c:acpi_battery_quirks
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/cpufreq/cpufreq.c:cpufreq_register_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:get_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffff81782700-ffffffff81782808: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8203f5b0)
Location: lib/string.c:39
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - lib/bitmap.c:bitmap_parselist
  - drivers/acpi/battery.c:acpi_battery_quirks
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/cpufreq/cpufreq.c:cpufreq_register_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:get_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffff8203f5b0-ffffffff8203f707: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff820bda30)
Location: lib/string.c:39
Inline: True
Direct callers:
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - block/early-lookup.c:match_dev_by_uuid
  - lib/bitmap.c:bitmap_parselist
  - drivers/acpi/battery.c:acpi_battery_quirks
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/cpufreq/cpufreq.c:cpufreq_register_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:get_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffff820bda30-ffffffff820bdb87: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff821982b0)
Location: lib/string.c:39
Inline: True
Direct callers:
  - kernel/workqueue.c:parse_affn_scope
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - block/early-lookup.c:match_dev_by_uuid
  - lib/bitmap-str.c:bitmap_parselist
  - drivers/acpi/battery.c:acpi_battery_quirks
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/cpufreq/cpufreq.c:cpufreq_register_governor
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:store_scaling_governor
  - drivers/cpufreq/cpufreq.c:get_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffff821982b0-ffffffff82198407: strncasecmp (STB_GLOBAL)
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
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffff800010d93178)
Location: lib/string.c:43
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/cpufreq/cpufreq.c:cpufreq_parse_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_parse_policy
  - drivers/cpufreq/cpufreq.c:find_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_find_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffff800010d93178-ffff800010d931f8: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (c0e8f7c8)
Location: lib/string.c:43
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/cpufreq/cpufreq.c:cpufreq_parse_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_parse_policy
  - drivers/cpufreq/cpufreq.c:find_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_find_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
c0e8f7c8-c0e8f880: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (c000000000ed7270)
Location: lib/string.c:43
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - block/partitions/mac.c:mac_partition
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/cpufreq/cpufreq.c:cpufreq_parse_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_parse_policy
  - drivers/cpufreq/cpufreq.c:find_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_find_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
c000000000ed7270-c000000000ed7344: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bd1d6)
Location: lib/string.c:43
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - block/partitions/mac.c:mac_partition
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:dm_stats_message
  - net/netfilter/nf_log.c:__find_logger
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffe0008bd1d6-ffffffe0008bd26a: strncasecmp (STB_GLOBAL)
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
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a57910)
Location: lib/string.c:43
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/cpufreq/cpufreq.c:cpufreq_parse_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_parse_policy
  - drivers/cpufreq/cpufreq.c:find_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_find_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffff81a57910-ffffffff81a579ac: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a149f0)
Location: lib/string.c:43
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/cpufreq/cpufreq.c:cpufreq_parse_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_parse_policy
  - drivers/cpufreq/cpufreq.c:find_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_find_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffff81a149f0-ffffffff81a14a8c: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ac3d00)
Location: lib/string.c:43
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/cpufreq/cpufreq.c:cpufreq_parse_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_parse_policy
  - drivers/cpufreq/cpufreq.c:find_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_find_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffff81ac3d00-ffffffff81ac3d9c: strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int strncasecmp(const char *s1, const char *s2, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ad01d0)
Location: lib/string.c:43
Inline: True
Direct callers:
  - init/do_mounts.c:match_dev_by_uuid
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - kernel/debug/kdb/kdb_bp.c:kdb_bp
  - fs/efivarfs/super.c:efivarfs_d_compare
  - block/partitions/mac.c:mac_partition
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/interface.c:resources_store
  - drivers/ata/libata-core.c:ata_parse_force_param
  - drivers/thermal/thermal_core.c:thermal_register_governor
  - drivers/md/dm-stats.c:message_stats_create
  - drivers/cpufreq/cpufreq.c:cpufreq_parse_policy
  - drivers/cpufreq/cpufreq.c:cpufreq_parse_policy
  - drivers/cpufreq/cpufreq.c:find_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_register_governor
  - drivers/cpuidle/governor.c:cpuidle_find_governor
  - net/netfilter/nf_log.c:__find_logger
  - net/netfilter/nf_log.c:__find_logger
  - net/dns_resolver/dns_key.c:dns_resolver_cmp
```
**Symbols:**

```
ffffffff81ad01d0-ffffffff81ad026c: strncasecmp (STB_GLOBAL)
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
