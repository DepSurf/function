# Function: <code>uv_read_local_mmr</code>

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
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bd6a3)
Location: arch/x86/include/asm/uv/uv_hub.h:685
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828c87b3)
Location: arch/x86/include/asm/uv/uv_hub.h:685
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810989e5)
Location: arch/x86/include/asm/uv/uv_hub.h:685
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff828ca0fc)
Location: arch/x86/include/asm/uv/uv_hub.h:685
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82cdfebc)
Location: arch/x86/include/asm/uv/uv_hub.h:631
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109ce86)
Location: arch/x86/include/asm/uv/uv_hub.h:631
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109e139)
Location: arch/x86/include/asm/uv/uv_hub.h:631
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109eee1)
Location: arch/x86/include/asm/uv/uv_hub.h:631
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fcc6a1)
Location: arch/x86/include/asm/uv/uv_hub.h:612
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff81099cb9)
Location: arch/x86/include/asm/uv/uv_hub.h:612
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109aa23)
Location: arch/x86/include/asm/uv/uv_hub.h:612
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d6f4c)
Location: arch/x86/include/asm/uv/uv_hub.h:612
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109a4a9)
Location: arch/x86/include/asm/uv/uv_hub.h:612
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109b175)
Location: arch/x86/include/asm/uv/uv_hub.h:612
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832b9c6a)
Location: arch/x86/include/asm/uv/uv_hub.h:612
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810aa529)
Location: arch/x86/include/asm/uv/uv_hub.h:612
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ab857)
Location: arch/x86/include/asm/uv/uv_hub.h:612
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346b899)
Location: arch/x86/include/asm/uv/uv_hub.h:612
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810bffc2)
Location: arch/x86/include/asm/uv/uv_hub.h:612
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c0f4b)
Location: arch/x86/include/asm/uv/uv_hub.h:612
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e92fed)
Location: arch/x86/include/asm/uv/uv_hub.h:612
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810dbf12)
Location: arch/x86/include/asm/uv/uv_hub.h:612
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810dd52b)
Location: arch/x86/include/asm/uv/uv_hub.h:612
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b7015)
Location: arch/x86/include/asm/uv/uv_hub.h:618
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810e74e2)
Location: arch/x86/include/asm/uv/uv_hub.h:618
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e8b0b)
Location: arch/x86/include/asm/uv/uv_hub.h:618
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e7925)
Location: arch/x86/include/asm/uv/uv_hub.h:618
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810ef872)
Location: arch/x86/include/asm/uv/uv_hub.h:618
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f084b)
Location: arch/x86/include/asm/uv/uv_hub.h:618
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
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
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828be6d0)
Location: arch/x86/include/asm/uv/uv_hub.h:685
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828c97f0)
Location: arch/x86/include/asm/uv/uv_hub.h:685
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff81099eb5)
Location: arch/x86/include/asm/uv/uv_hub.h:685
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff828cb139)
Location: arch/x86/include/asm/uv/uv_hub.h:685
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
</details>
</li>
</ul>

## Differences
