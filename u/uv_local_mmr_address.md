# Function: <code>uv_local_mmr_address</code>

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
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int *uv_local_mmr_address(long unsigned int offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106d851)
Location: arch/x86/include/asm/uv/uv_hub.h:680
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat
Direct callers:
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
In arch/x86/platform/uv/tlb_uv.c (ffffffff810976e5)
Location: arch/x86/include/asm/uv/uv_hub.h:680
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810989e5)
Location: arch/x86/include/asm/uv/uv_hub.h:680
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff81099ba5)
Location: arch/x86/include/asm/uv/uv_hub.h:680
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
```
**Symbols:**

```
ffffffff8106d730-ffffffff8106d7b4: uv_local_mmr_address (STB_LOCAL)
ffffffff81095df0-ffffffff81095e74: uv_local_mmr_address (STB_LOCAL)
ffffffff810995e0-ffffffff81099664: uv_local_mmr_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int *uv_local_mmr_address(long unsigned int offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82cdfebc)
Location: arch/x86/include/asm/uv/uv_hub.h:626
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat
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
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109ca8b)
Location: arch/x86/include/asm/uv/uv_hub.h:626
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109e139)
Location: arch/x86/include/asm/uv/uv_hub.h:626
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109f29e)
Location: arch/x86/include/asm/uv/uv_hub.h:626
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
**Symbols:**

```
ffffffff8109a190-ffffffff8109a1e0: uv_local_mmr_address (STB_LOCAL)
ffffffff8109e9c0-ffffffff8109ea10: uv_local_mmr_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int *uv_local_mmr_address(long unsigned int offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81bd75bb)
Location: arch/x86/include/asm/uv/uv_hub.h:607
Inline: False
Direct callers:
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
Location: arch/x86/include/asm/uv/uv_hub.h:607
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ada5)
Location: arch/x86/include/asm/uv/uv_hub.h:607
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
**Symbols:**

```
ffffffff81bd75bb-ffffffff81bd7628: uv_local_mmr_address (STB_LOCAL)
ffffffff8109a3f0-ffffffff8109a455: uv_local_mmr_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int *uv_local_mmr_address(long unsigned int offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81bc9759)
Location: arch/x86/include/asm/uv/uv_hub.h:607
Inline: False
Direct callers:
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
Location: arch/x86/include/asm/uv/uv_hub.h:607
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109b4e1)
Location: arch/x86/include/asm/uv/uv_hub.h:607
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
**Symbols:**

```
ffffffff81bc9759-ffffffff81bc97c0: uv_local_mmr_address (STB_LOCAL)
ffffffff8109abb0-ffffffff8109ac15: uv_local_mmr_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int *uv_local_mmr_address(long unsigned int offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81c9e2cb)
Location: arch/x86/include/asm/uv/uv_hub.h:607
Inline: False
Direct callers:
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
Location: arch/x86/include/asm/uv/uv_hub.h:607
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ab857)
Location: arch/x86/include/asm/uv/uv_hub.h:607
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
**Symbols:**

```
ffffffff81c9e2cb-ffffffff81c9e332: uv_local_mmr_address (STB_LOCAL)
ffffffff810aae40-ffffffff810aaea5: uv_local_mmr_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int *uv_local_mmr_address(long unsigned int offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81e4d78d)
Location: arch/x86/include/asm/uv/uv_hub.h:607
Inline: False
Direct callers:
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
Location: arch/x86/include/asm/uv/uv_hub.h:607
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c1333)
Location: arch/x86/include/asm/uv/uv_hub.h:607
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
**Symbols:**

```
ffffffff81e4d78d-ffffffff81e4d7d4: uv_local_mmr_address (STB_LOCAL)
ffffffff810c08b0-ffffffff810c08f5: uv_local_mmr_address (STB_LOCAL)
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
Location: arch/x86/include/asm/uv/uv_hub.h:607
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
Location: arch/x86/include/asm/uv/uv_hub.h:607
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ddb73)
Location: arch/x86/include/asm/uv/uv_hub.h:607
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b7015)
Location: arch/x86/include/asm/uv/uv_hub.h:613
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
Location: arch/x86/include/asm/uv/uv_hub.h:613
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e9222)
Location: arch/x86/include/asm/uv/uv_hub.h:613
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e7925)
Location: arch/x86/include/asm/uv/uv_hub.h:613
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
Location: arch/x86/include/asm/uv/uv_hub.h:613
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f1577)
Location: arch/x86/include/asm/uv/uv_hub.h:613
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
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
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int *uv_local_mmr_address(long unsigned int offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106ef21)
Location: arch/x86/include/asm/uv/uv_hub.h:680
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat
Direct callers:
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
In arch/x86/platform/uv/tlb_uv.c (ffffffff81098bb5)
Location: arch/x86/include/asm/uv/uv_hub.h:680
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff81099eb5)
Location: arch/x86/include/asm/uv/uv_hub.h:680
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109b073)
Location: arch/x86/include/asm/uv/uv_hub.h:680
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
```
**Symbols:**

```
ffffffff8106ee00-ffffffff8106ee84: uv_local_mmr_address (STB_LOCAL)
ffffffff81097380-ffffffff81097404: uv_local_mmr_address (STB_LOCAL)
ffffffff8109aab0-ffffffff8109ab34: uv_local_mmr_address (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
