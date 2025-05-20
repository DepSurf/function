# Function: <code>get_jiffies_64</code>

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
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff810493f5)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:therm_throt_process
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In kernel/sys.c (ffffffff81094b64)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - kernel/sys.c:SyS_times
```
```
In fs/fuse/dir.c (ffffffff81311b75)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_permission
```
```
In drivers/ata/libata-eh.c (ffffffff815d6058)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816ae93d)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_stats.c (ffffffff816b2ad6)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_update
  - drivers/cpufreq/cpufreq_stats.c:__cpufreq_stats_create_table
```
```
In net/ipv4/syncookies.c (ffffffff817aaf5f)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv4/syncookies.c:__cookie_v4_check
```
```
In net/ipv6/syncookies.c (ffffffff817ff09f)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_check
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
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104983c)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:therm_throt_process
```
```
In kernel/sys.c (ffffffff81097d74)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - kernel/sys.c:SyS_times
```
```
In fs/fuse/dir.c (ffffffff81348ac7)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/ata/libata-eh.c (ffffffff8162fab8)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817101ed)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_stats.c (ffffffff81714f98)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_update
```
```
In net/ipv4/syncookies.c (ffffffff81818b4e)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff8186eb26)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104bc3c)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:therm_throt_process
```
```
In kernel/sys.c (ffffffff8109cd24)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - kernel/sys.c:SyS_times
```
```
In fs/fuse/dir.c (ffffffff8135e31a)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/ata/libata-eh.c (ffffffff81660c08)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817421cd)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_stats.c (ffffffff81746d98)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_update
```
```
In net/ipv4/syncookies.c (ffffffff8184a3ae)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff818a1a76)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104b479)
Location: include/linux/jiffies.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:therm_throt_process
```
```
In kernel/sys.c (ffffffff81099ac4)
Location: include/linux/jiffies.h:82
Inline: True
Inline callers:
  - kernel/sys.c:SyS_times
```
```
In fs/fuse/dir.c (ffffffff81372e0a)
Location: include/linux/jiffies.h:82
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/ata/libata-eh.c (ffffffff81675bf8)
Location: include/linux/jiffies.h:82
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81760835)
Location: include/linux/jiffies.h:82
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_stats.c (ffffffff817653ef)
Location: include/linux/jiffies.h:82
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_update
```
```
In net/ipv4/syncookies.c (ffffffff8186dd5b)
Location: include/linux/jiffies.h:82
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff818c8033)
Location: include/linux/jiffies.h:82
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104ee86)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:therm_throt_process
```
```
In kernel/sys.c (ffffffff810a07a4)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - kernel/sys.c:SyS_times
```
```
In fs/fuse/dir.c (ffffffff81397a6d)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/ata/libata-eh.c (ffffffff816df28e)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_ering_record
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817d6805)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_stats.c (ffffffff817db3ff)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_update
```
```
In net/ipv4/syncookies.c (ffffffff818ee6ab)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff8194b5e3)
Location: include/linux/jiffies.h:83
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81051b44)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:therm_throt_process
```
```
In kernel/sys.c (ffffffff810a3964)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
```
In fs/fuse/dir.c (ffffffff813c6d22)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/ata/libata-eh.c (ffffffff8171ba87)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_ering_record
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8181f4f1)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_stats.c (ffffffff81824076)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_update
```
```
In net/ipv4/syncookies.c (ffffffff81945065)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff819a48b2)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8104f1e9)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_process
```
```
In kernel/sys.c (ffffffff810ac574)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
```
In fs/fuse/dir.c (ffffffff813dff2a)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/acpi/osl.c (ffffffff81584315)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_timer
```
```
In drivers/ata/libata-eh.c (ffffffff8173e357)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_ering_record
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8184b391)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_stats.c (ffffffff8184ff36)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_update
```
```
In net/ipv4/syncookies.c (ffffffff81975355)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff819db3c2)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff810522ad)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_process
```
```
In kernel/sys.c (ffffffff810b1b36)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
```
In fs/fuse/dir.c (ffffffff8140bb23)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/acpi/osl.c (ffffffff815b4f15)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_timer
```
```
In drivers/ata/libata-eh.c (ffffffff81779ec7)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_ering_record
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8188e415)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_stats.c (ffffffff8189354d)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
```
In net/ipv4/syncookies.c (ffffffff819deef0)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81a4a02d)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052b9d)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_process
```
```
In kernel/sys.c (ffffffff810b8206)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
```
In mm/memcontrol.c (ffffffff812c7930)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fuse/dir.c (ffffffff814255d3)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_delete
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/acpi/osl.c (ffffffff815d6145)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_timer
```
```
In drivers/ata/libata-eh.c (ffffffff8179dd48)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818c05a5)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_stats.c (ffffffff818c556d)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
```
In net/ipv4/syncookies.c (ffffffff81a15f90)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81a80bed)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81057c13)
Location: include/linux/jiffies.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:notify_package_thresholds
  - arch/x86/kernel/cpu/mce/therm_throt.c:notify_package_thresholds
  - arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work
```
```
In kernel/sys.c (ffffffff810bfbd6)
Location: include/linux/jiffies.h:84
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
```
In kernel/bpf/helpers.c (ffffffff81214825)
Location: include/linux/jiffies.h:84
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_jiffies64
```
```
In mm/memcontrol.c (ffffffff812fd3c0)
Location: include/linux/jiffies.h:84
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fuse/dir.c (ffffffff814738a8)
Location: include/linux/jiffies.h:84
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_delete
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/acpi/osl.c (ffffffff8167fe45)
Location: include/linux/jiffies.h:84
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_timer
```
```
In drivers/ata/libata-eh.c (ffffffff8186288d)
Location: include/linux/jiffies.h:84
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down_verdict
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81992535)
Location: include/linux/jiffies.h:84
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_stats.c (ffffffff819976fd)
Location: include/linux/jiffies.h:84
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
```
In drivers/devfreq/devfreq.c (ffffffff819d051b)
Location: include/linux/jiffies.h:84
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_update_status
```
```
In net/ipv4/syncookies.c (ffffffff81b07000)
Location: include/linux/jiffies.h:84
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81b7b76a)
Location: include/linux/jiffies.h:84
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81056993)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:notify_package_thresholds
  - arch/x86/kernel/cpu/mce/therm_throt.c:notify_package_thresholds
  - arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work
```
```
In kernel/sys.c (ffffffff810bad96)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
```
In kernel/bpf/helpers.c (ffffffff81216305)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_jiffies64
```
```
In mm/memcontrol.c (ffffffff81309842)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fuse/dir.c (ffffffff8148f6d2)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_delete
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/acpi/osl.c (ffffffff8169e8f5)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_timer
```
```
In drivers/xen/events/events_base.c (ffffffff81735c20)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
  - drivers/xen/events/events_base.c:lateeoi_list_add
```
```
In drivers/ata/libata-eh.c (ffffffff8187169d)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down_verdict
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81995745)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/devfreq/devfreq.c (ffffffff819cff8a)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_update_status
```
```
In net/ipv4/syncookies.c (ffffffff81b151f0)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81b8a7aa)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In kernel/sys.c (ffffffff810bc6c6)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
```
In kernel/bpf/helpers.c (ffffffff81219015)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_jiffies64
```
```
In mm/memcontrol.c (ffffffff8130fe86)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fuse/dir.c (ffffffff814950f2)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_delete
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/acpi/osl.c (ffffffff816815a5)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_timer
```
```
In drivers/xen/events/events_base.c (ffffffff8171940f)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
```
```
In drivers/ata/libata-eh.c (ffffffff81853daa)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff819471db)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197a5b5)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/devfreq/devfreq.c (ffffffff819b50e2)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_update_status
```
```
In net/ipv4/syncookies.c (ffffffff81b02ff7)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81b79606)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In kernel/sys.c (ffffffff810cf0a6)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
```
In kernel/bpf/helpers.c (ffffffff8124f785)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_jiffies64
```
```
In mm/memcontrol.c (ffffffff8135b12c)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fuse/dir.c (ffffffff814ecb82)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_delete
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/acpi/osl.c (ffffffff816f6695)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_timer
```
```
In drivers/xen/events/events_base.c (ffffffff817972b3)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
```
```
In drivers/ata/libata-eh.c (ffffffff818e1fc3)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff819ebe8d)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a235b1)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/devfreq/devfreq.c (ffffffff81a63c52)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_update_status
```
```
In net/ipv4/syncookies.c (ffffffff81bc5227)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81c44286)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In kernel/sys.c (ffffffff810e7c04)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
```
In kernel/bpf/helpers.c (ffffffff81296915)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_jiffies64
```
```
In mm/memcontrol.c (ffffffff813d47dc)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fuse/dir.c (ffffffff8157b91c)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_delete
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/acpi/osl.c (ffffffff818234c5)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_timer
```
```
In drivers/xen/events/events_base.c (ffffffff818d028d)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
```
```
In drivers/ata/libata-eh.c (ffffffff81a33048)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81b52106)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b8c849)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd2fab)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:trans_stat_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_update_status
```
```
In net/ipv4/syncookies.c (ffffffff81d5a3ad)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81de31f0)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In kernel/sys.c (ffffffff811088f4)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
```
In kernel/bpf/helpers.c (ffffffff812f18d5)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_jiffies64
```
```
In mm/memcontrol.c (ffffffff8145a20c)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fuse/dir.c (ffffffff816212dc)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_delete
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/acpi/osl.c (ffffffff819546f5)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_timer
```
```
In drivers/xen/events/events_base.c (ffffffff81a21a2d)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
```
```
In drivers/ata/libata-eh.c (ffffffff81bb77a8)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81cea29e)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d2c289)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/devfreq/devfreq.c (ffffffff81d7ee1b)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:trans_stat_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_update_status
```
```
In net/ipv4/syncookies.c (ffffffff81f247bd)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81fb5840)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In kernel/sys.c (ffffffff81114c04)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
```
In kernel/bpf/helpers.c (ffffffff8131e4b5)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_jiffies64
```
```
In mm/memcontrol.c (ffffffff8148fe6c)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fuse/dir.c (ffffffff8165972c)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_delete
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/acpi/osl.c (ffffffff8199ab05)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_timer
```
```
In drivers/xen/events/events_base.c (ffffffff81a6adbd)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
```
```
In drivers/ata/libata-eh.c (ffffffff81c0edc7)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81d52dde)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d95519)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/devfreq/devfreq.c (ffffffff81ded1ab)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:trans_stat_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_update_status
```
```
In net/ipv4/syncookies.c (ffffffff81f84352)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff82015f60)
Location: include/linux/jiffies.h:85
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In kernel/sys.c (ffffffff8111e5f4)
Location: include/linux/jiffies.h:99
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
```
In kernel/bpf/helpers.c (ffffffff813408d5)
Location: include/linux/jiffies.h:99
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_jiffies64
```
```
In mm/memcontrol.c (ffffffff814bf67c)
Location: include/linux/jiffies.h:99
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fuse/dir.c (ffffffff81693ffd)
Location: include/linux/jiffies.h:99
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_get_attr
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_statx
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_delete
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/acpi/osl.c (ffffffff819e2f85)
Location: include/linux/jiffies.h:99
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_timer
```
```
In drivers/xen/events/events_base.c (ffffffff81abcff7)
Location: include/linux/jiffies.h:99
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
```
```
In drivers/ata/libata-eh.c (ffffffff81c64007)
Location: include/linux/jiffies.h:99
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81e09b3e)
Location: include/linux/jiffies.h:99
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:throttle_active_work
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e4d043)
Location: include/linux/jiffies.h:99
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea354b)
Location: include/linux/jiffies.h:99
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:trans_stat_store
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_update_status
```
```
In net/ipv4/syncookies.c (ffffffff8204aa09)
Location: include/linux/jiffies.h:99
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff820e50ae)
Location: include/linux/jiffies.h:99
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In kernel/sys.c (ffff800010116c48)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_times
```
```
In mm/memcontrol.c (ffff80001036a764)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fuse/dir.c (ffff800010508d84)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_delete
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/acpi/osl.c (ffff800010763a60)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_timer
```
```
In drivers/ata/libata-eh.c (ffff8000109a930c)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b1d004)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_stats.c (ffff800010b23310)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
```
In net/ipv4/syncookies.c (ffff800010cd1bd8)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffff800010d4c44c)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 get_jiffies_64();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/jiffies.c (c03f27f4)
Location: kernel/time/jiffies.c:64
Inline: False
Direct callers:
  - arch/arm/kernel/smp_twd.c:twd_timer_setup
  - arch/arm/kernel/smp_twd.c:twd_timer_setup
  - arch/arm/kernel/smp_twd.c:twd_timer_setup
  - kernel/sys.c:__se_sys_times
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_dentry_delete
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_update
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
**Symbols:**

```
c03f27f4-c03f2878: get_jiffies_64 (STB_GLOBAL)
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
In kernel/sys.c (c00000000015c544)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_times
```
```
In mm/memcontrol.c (c0000000004599b8)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fuse/dir.c (c00000000064e8a0)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_delete
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/ata/libata-eh.c (c000000000a6fc68)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/cpufreq/cpufreq.c (c000000000c0fad4)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_stats.c (c000000000c17898)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
```
In drivers/cpufreq/powernv-cpufreq.c (c000000000c1c48c)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_target_index
```
```
In net/ipv4/syncookies.c (c000000000defea0)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (c000000000e82aa4)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In kernel/sys.c (ffffffe0000d3ce8)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_times
```
```
In mm/memcontrol.c (ffffffe000247fa8)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fuse/dir.c (ffffffe0003748ea)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_delete
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/ata/libata-eh.c (ffffffe000607302)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In net/ipv4/syncookies.c (ffffffe000822ff2)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffe000885192)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052c9d)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_process
```
```
In kernel/sys.c (ffffffff810b2576)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
```
In mm/memcontrol.c (ffffffff812bff10)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fuse/dir.c (ffffffff8141dbb3)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_delete
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/acpi/osl.c (ffffffff815c9ea5)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_timer
```
```
In drivers/ata/libata-eh.c (ffffffff81762e38)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81864cc5)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_stats.c (ffffffff81869c8d)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
```
In net/ipv4/syncookies.c (ffffffff819b5620)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81a2027d)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8104273b)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_process
```
```
In kernel/sys.c (ffffffff810a0e96)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
```
In mm/memcontrol.c (ffffffff812b0fe0)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fuse/dir.c (ffffffff8140e633)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_delete
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/acpi/osl.c (ffffffff815b2f25)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_timer
```
```
In drivers/ata/libata-eh.c (ffffffff81742c98)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8182d975)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_stats.c (ffffffff8183293d)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
```
In net/ipv4/syncookies.c (ffffffff81972410)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff819dd03d)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052b4d)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_process
```
```
In kernel/sys.c (ffffffff810b1ad6)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
```
In mm/memcontrol.c (ffffffff812bdd20)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fuse/dir.c (ffffffff81419d53)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_delete
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/acpi/osl.c (ffffffff815ca425)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_timer
```
```
In drivers/ata/libata-eh.c (ffffffff81792bc8)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818b5a55)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_stats.c (ffffffff818baa1d)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
```
In net/ipv4/syncookies.c (ffffffff81a1fec0)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81a8acfd)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
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
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81053fcd)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:therm_throt_process
```
```
In kernel/sys.c (ffffffff810b9fc6)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
```
```
In mm/memcontrol.c (ffffffff812ce679)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fuse/dir.c (ffffffff81430ac3)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_dentry_delete
  - fs/fuse/dir.c:fuse_dentry_revalidate
```
```
In drivers/acpi/osl.c (ffffffff815e4285)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_timer
```
```
In drivers/ata/libata-eh.c (ffffffff817aca08)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d1d05)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:get_cpu_idle_time
```
```
In drivers/cpufreq/cpufreq_stats.c (ffffffff818d6cfd)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_record_transition
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
  - drivers/cpufreq/cpufreq_stats.c:store_reset
  - drivers/cpufreq/cpufreq_stats.c:show_time_in_state
```
```
In net/ipv4/syncookies.c (ffffffff81a2b3c0)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:__cookie_v4_check
  - net/ipv4/syncookies.c:__cookie_v4_init_sequence
```
```
In net/ipv6/syncookies.c (ffffffff81a9795d)
Location: include/linux/jiffies.h:86
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:__cookie_v6_check
  - net/ipv6/syncookies.c:__cookie_v6_init_sequence
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
