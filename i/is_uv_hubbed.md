# Function: <code>is_uv_hubbed</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int is_uv_hubbed(int uvtype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce151a)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:365
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
  - arch/x86/kernel/apic/x2apic_uv_x.c:decode_uv_systab
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
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
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_tsc_check_sync
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_tsc_check_sync
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_tsc_check_sync
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_early_read_mmr
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:scan_sock
  - arch/x86/platform/uv/tlb_uv.c:scan_sock
  - arch/x86/platform/uv/tlb_uv.c:scan_sock
  - arch/x86/platform/uv/tlb_uv.c:scan_sock
  - arch/x86/platform/uv/tlb_uv.c:scan_sock
  - arch/x86/platform/uv/tlb_uv.c:scan_sock
  - arch/x86/platform/uv/tlb_uv.c:scan_sock
  - arch/x86/platform/uv/tlb_uv.c:scan_sock
  - arch/x86/platform/uv/tlb_uv.c:scan_sock
  - arch/x86/platform/uv/tlb_uv.c:scan_sock
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:pq_init
  - arch/x86/platform/uv/tlb_uv.c:pq_init
  - arch/x86/platform/uv/tlb_uv.c:pq_init
  - arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init
  - arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init
  - arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init
  - arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init
  - arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init
  - arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init
  - arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init
  - arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init
  - arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init
  - arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
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
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
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
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_misc_control
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_misc_control
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_misc_control
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first
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
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
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
```
**Symbols:**

```
ffffffff81074390-ffffffff810743a3: is_uv_hubbed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int is_uv_hubbed(int uvtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074f20)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:523
Inline: False
```
**Symbols:**

```
ffffffff81074f20-ffffffff81074f33: is_uv_hubbed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int is_uv_hubbed(int uvtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810759c0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:519
Inline: False
```
**Symbols:**

```
ffffffff810759c0-ffffffff810759d3: is_uv_hubbed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int is_uv_hubbed(int uvtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81082e90)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:519
Inline: False
```
**Symbols:**

```
ffffffff81082e90-ffffffff81082ea3: is_uv_hubbed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int is_uv_hubbed(int uvtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81092c20)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:525
Inline: False
```
**Symbols:**

```
ffffffff81092c20-ffffffff81092c39: is_uv_hubbed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int is_uv_hubbed(int uvtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810a7e20)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:525
Inline: False
```
**Symbols:**

```
ffffffff810a7e20-ffffffff810a7e39: is_uv_hubbed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int is_uv_hubbed(int uvtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810ab090)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:525
Inline: False
```
**Symbols:**

```
ffffffff810ab090-ffffffff810ab0a9: is_uv_hubbed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int is_uv_hubbed(int uvtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810b2030)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:526
Inline: False
```
**Symbols:**

```
ffffffff810b2030-ffffffff810b2049: is_uv_hubbed (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
