# Function: <code>safe_apic_wait_icr_idle</code>

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
In arch/x86/kernel/smpboot.c (ffffffff810517bb)
Location: arch/x86/include/asm/apic.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81054bf1)
Location: arch/x86/include/asm/apic.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81059413)
Location: arch/x86/include/asm/apic.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a5ec)
Location: arch/x86/include/asm/apic.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
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
In arch/x86/kernel/smpboot.c (ffffffff81052159)
Location: arch/x86/include/asm/apic.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81054d52)
Location: arch/x86/include/asm/apic.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/smpboot.c (ffffffff81054a66)
Location: arch/x86/include/asm/apic.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81057b12)
Location: arch/x86/include/asm/apic.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/smpboot.c (ffffffff810543c0)
Location: arch/x86/include/asm/apic.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81057292)
Location: arch/x86/include/asm/apic.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/smpboot.c (ffffffff810581be)
Location: arch/x86/include/asm/apic.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8105af22)
Location: arch/x86/include/asm/apic.h:425
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/smpboot.c (ffffffff8105ae98)
Location: arch/x86/include/asm/apic.h:420
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8105df32)
Location: arch/x86/include/asm/apic.h:420
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/smpboot.c (ffffffff81060b18)
Location: arch/x86/include/asm/apic.h:420
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81063bc2)
Location: arch/x86/include/asm/apic.h:420
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/smpboot.c (ffffffff810630aa)
Location: arch/x86/include/asm/apic.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81067287)
Location: arch/x86/include/asm/apic.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/smpboot.c (ffffffff8106375a)
Location: arch/x86/include/asm/apic.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81067d6d)
Location: arch/x86/include/asm/apic.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/smpboot.c (ffffffff81069a8a)
Location: arch/x86/include/asm/apic.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8106eabd)
Location: arch/x86/include/asm/apic.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/smpboot.c (ffffffff8106b75a)
Location: arch/x86/include/asm/apic.h:416
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8106ff3d)
Location: arch/x86/include/asm/apic.h:416
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/smpboot.c (ffffffff8106c13a)
Location: arch/x86/include/asm/apic.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81070a8d)
Location: arch/x86/include/asm/apic.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/smpboot.c (ffffffff81076d4a)
Location: arch/x86/include/asm/apic.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8107c70d)
Location: arch/x86/include/asm/apic.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/smpboot.c (ffffffff81085be6)
Location: arch/x86/include/asm/apic.h:419
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8108bad5)
Location: arch/x86/include/asm/apic.h:419
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/smpboot.c (ffffffff81098e86)
Location: arch/x86/include/asm/apic.h:416
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8109ff55)
Location: arch/x86/include/asm/apic.h:416
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/smpboot.c (ffffffff8109c23f)
Location: arch/x86/include/asm/apic.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:send_init_sequence
  - arch/x86/kernel/smpboot.c:send_init_sequence
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a2ed5)
Location: arch/x86/include/asm/apic.h:417
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/smpboot.c (ffffffff810a3700)
Location: arch/x86/include/asm/apic.h:459
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106324a)
Location: arch/x86/include/asm/apic.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8106785d)
Location: arch/x86/include/asm/apic.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/smpboot.c (ffffffff8105355a)
Location: arch/x86/include/asm/apic.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81057bcd)
Location: arch/x86/include/asm/apic.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/smpboot.c (ffffffff810636fa)
Location: arch/x86/include/asm/apic.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81067d0d)
Location: arch/x86/include/asm/apic.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/smpboot.c (ffffffff81064cba)
Location: arch/x86/include/asm/apic.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_nmi
  - arch/x86/kernel/smpboot.c:__inquire_remote_apic
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810692ed)
Location: arch/x86/include/asm/apic.h:426
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
</details>
</li>
</ul>

## Differences
