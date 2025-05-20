# Function: <code>uv_global_mmr64_address</code>

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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106d48f)
Location: arch/x86/include/asm/uv/uv_hub.h:650
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_disable
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_enable
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828c9aac)
Location: arch/x86/include/asm/uv/uv_hub.h:650
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_misc_control
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_payload_first
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff81098779)
Location: arch/x86/include/asm/uv/uv_hub.h:650
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff81098aea)
Location: arch/x86/include/asm/uv/uv_hub.h:650
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
volatile void *uv_global_mmr64_address(int pnode, long unsigned int offset);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810744df)
Location: arch/x86/include/asm/uv/uv_hub.h:596
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_disable
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_enable
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109b150)
Location: arch/x86/include/asm/uv/uv_hub.h:596
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_payload_first
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:pq_init
  - arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_misc_control
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109df56)
Location: arch/x86/include/asm/uv/uv_hub.h:596
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109e1de)
Location: arch/x86/include/asm/uv/uv_hub.h:596
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
**Symbols:**

```
ffffffff8109a070-ffffffff8109a0ab: uv_global_mmr64_address (STB_LOCAL)
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075264)
Location: arch/x86/include/asm/uv/uv_hub.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff81099b27)
Location: arch/x86/include/asm/uv/uv_hub.h:577
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff81099d94)
Location: arch/x86/include/asm/uv/uv_hub.h:577
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075d04)
Location: arch/x86/include/asm/uv/uv_hub.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109a33d)
Location: arch/x86/include/asm/uv/uv_hub.h:577
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109a584)
Location: arch/x86/include/asm/uv/uv_hub.h:577
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810832a9)
Location: arch/x86/include/asm/uv/uv_hub.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810aa39c)
Location: arch/x86/include/asm/uv/uv_hub.h:577
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_program_mmr
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810aa624)
Location: arch/x86/include/asm/uv/uv_hub.h:577
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8109313d)
Location: arch/x86/include/asm/uv/uv_hub.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810bfe10)
Location: arch/x86/include/asm/uv/uv_hub.h:577
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_program_mmr
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810c0074)
Location: arch/x86/include/asm/uv/uv_hub.h:577
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810a84bd)
Location: arch/x86/include/asm/uv/uv_hub.h:577
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810dbd20)
Location: arch/x86/include/asm/uv/uv_hub.h:577
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_program_mmr
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810dbfd4)
Location: arch/x86/include/asm/uv/uv_hub.h:577
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810ab72d)
Location: arch/x86/include/asm/uv/uv_hub.h:583
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810e72f0)
Location: arch/x86/include/asm/uv/uv_hub.h:583
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_program_mmr
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810e75a4)
Location: arch/x86/include/asm/uv/uv_hub.h:583
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810b25a5)
Location: arch/x86/include/asm/uv/uv_hub.h:583
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810ef684)
Location: arch/x86/include/asm/uv/uv_hub.h:583
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810ef933)
Location: arch/x86/include/asm/uv/uv_hub.h:583
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106eb5f)
Location: arch/x86/include/asm/uv/uv_hub.h:650
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_disable
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat_enable
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828caae9)
Location: arch/x86/include/asm/uv/uv_hub.h:650
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_misc_control
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_payload_first
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff81099c49)
Location: arch/x86/include/asm/uv/uv_hub.h:650
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff81099fba)
Location: arch/x86/include/asm/uv/uv_hub.h:650
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
