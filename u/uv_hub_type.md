# Function: <code>uv_hub_type</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fce2dc)
Location: arch/x86/include/asm/uv/uv_hub.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_tsc_check_sync
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_tsc_check_sync
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_tsc_check_sync
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_tsc_check_sync
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_tsc_check_sync
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_local_mmr_address
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_local_mmr_address
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_local_mmr_address
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_local_mmr_address
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff81099c8d)
Location: arch/x86/include/asm/uv/uv_hub.h:211
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ada5)
Location: arch/x86/include/asm/uv/uv_hub.h:211
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d8dbd)
Location: arch/x86/include/asm/uv/uv_hub.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_local_mmr_address
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_local_mmr_address
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_local_mmr_address
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_local_mmr_address
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109a47d)
Location: arch/x86/include/asm/uv/uv_hub.h:211
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109b4e1)
Location: arch/x86/include/asm/uv/uv_hub.h:211
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832bc284)
Location: arch/x86/include/asm/uv/uv_hub.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_local_mmr_address
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_local_mmr_address
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_local_mmr_address
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_local_mmr_address
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810aa4fd)
Location: arch/x86/include/asm/uv/uv_hub.h:211
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ab857)
Location: arch/x86/include/asm/uv/uv_hub.h:211
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346dbd6)
Location: arch/x86/include/asm/uv/uv_hub.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_local_mmr_address
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_local_mmr_address
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_local_mmr_address
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_local_mmr_address
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810bffa2)
Location: arch/x86/include/asm/uv/uv_hub.h:211
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c1333)
Location: arch/x86/include/asm/uv/uv_hub.h:211
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e93961)
Location: arch/x86/include/asm/uv/uv_hub.h:211
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810dbef2)
Location: arch/x86/include/asm/uv/uv_hub.h:211
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ddb73)
Location: arch/x86/include/asm/uv/uv_hub.h:211
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b7431)
Location: arch/x86/include/asm/uv/uv_hub.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810e74c2)
Location: arch/x86/include/asm/uv/uv_hub.h:212
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e9222)
Location: arch/x86/include/asm/uv/uv_hub.h:212
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e7d41)
Location: arch/x86/include/asm/uv/uv_hub.h:212
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_low_mmrs
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810ef852)
Location: arch/x86/include/asm/uv/uv_hub.h:212
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f1577)
Location: arch/x86/include/asm/uv/uv_hub.h:212
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
