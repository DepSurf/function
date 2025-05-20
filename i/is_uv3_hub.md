# Function: <code>is_uv3_hub</code>

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
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bc8cc)
Location: arch/x86/include/asm/uv/uv_hub.h:272
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
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
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
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
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828c9a72)
Location: arch/x86/include/asm/uv/uv_hub.h:272
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_misc_control
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_misc_control
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff81098a3a)
Location: arch/x86/include/asm/uv/uv_hub.h:272
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff828ca149)
Location: arch/x86/include/asm/uv/uv_hub.h:272
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
```
**Symbols:**

```
ffffffff8106d570-ffffffff8106d58d: is_uv3_hub.part.0 (STB_LOCAL)
ffffffff81095080-ffffffff8109509d: is_uv3_hub.part.0 (STB_LOCAL)
ffffffff81099370-ffffffff8109938d: is_uv3_hub.part.0 (STB_LOCAL)
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce1524)
Location: arch/x86/include/asm/uv/uv_hub.h:243
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff82cebf7f)
Location: arch/x86/include/asm/uv/uv_hub.h:243
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:scan_sock
  - arch/x86/platform/uv/tlb_uv.c:scan_sock
  - arch/x86/platform/uv/tlb_uv.c:scan_sock
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:pq_init
  - arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init
  - arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_misc_control
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109e192)
Location: arch/x86/include/asm/uv/uv_hub.h:243
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109f30d)
Location: arch/x86/include/asm/uv/uv_hub.h:243
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fce310)
Location: arch/x86/include/asm/uv/uv_hub.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d8df1)
Location: arch/x86/include/asm/uv/uv_hub.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832bc2b8)
Location: arch/x86/include/asm/uv/uv_hub.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346dbf2)
Location: arch/x86/include/asm/uv/uv_hub.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e93b8d)
Location: arch/x86/include/asm/uv/uv_hub.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b76f9)
Location: arch/x86/include/asm/uv/uv_hub.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e8041)
Location: arch/x86/include/asm/uv/uv_hub.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
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
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bd8f9)
Location: arch/x86/include/asm/uv/uv_hub.h:272
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
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
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
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
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828caaaf)
Location: arch/x86/include/asm/uv/uv_hub.h:272
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_misc_control
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_misc_control
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff81099f0a)
Location: arch/x86/include/asm/uv/uv_hub.h:272
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff828cb186)
Location: arch/x86/include/asm/uv/uv_hub.h:272
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
```
**Symbols:**

```
ffffffff8106ec40-ffffffff8106ec5d: is_uv3_hub.part.0 (STB_LOCAL)
ffffffff81096540-ffffffff8109655d: is_uv3_hub.part.0 (STB_LOCAL)
ffffffff8109a840-ffffffff8109a85d: is_uv3_hub.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
