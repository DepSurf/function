# Function: <code>numachip2_lcsr_address</code>

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
In arch/x86/kernel/apic/apic_numachip.c (0)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
```
```
In drivers/clocksource/numachip.c (ffffffff816d54fc)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip_timer_each
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
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810593f9)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_apic_icr_write
```
```
In drivers/clocksource/numachip.c (ffffffff81fe5045)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip2_timer_read
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
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105c189)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_apic_icr_write
```
```
In drivers/clocksource/numachip.c (ffffffff820239da)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip2_timer_read
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
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105b889)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_apic_icr_write
```
```
In drivers/clocksource/numachip.c (ffffffff82106718)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip2_timer_read
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
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105f979)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_apic_icr_write
```
```
In drivers/clocksource/numachip.c (ffffffff8270fe71)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip2_timer_read
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
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81062a97)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_apic_icr_write
```
```
In drivers/clocksource/numachip.c (ffffffff8273a109)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip2_timer_read
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
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81068797)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_apic_icr_write
```
```
In drivers/clocksource/numachip.c (ffffffff828f40d8)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip2_timer_read
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
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106bfa7)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_apic_icr_write
```
```
In drivers/clocksource/numachip.c (ffffffff8290fb07)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip2_timer_read
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
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106cb57)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_apic_icr_write
```
```
In drivers/clocksource/numachip.c (ffffffff829197e2)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip2_timer_read
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
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81073e37)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_apic_icr_write
```
```
In drivers/clocksource/numachip.c (ffffffff82d2befb)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip2_timer_read
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
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81074997)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_apic_icr_write
```
```
In drivers/clocksource/numachip.c (ffffffff8301a8c3)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip2_timer_read
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
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81075487)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_apic_icr_write
```
```
In drivers/clocksource/numachip.c (ffffffff83225911)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip2_timer_read
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
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81082957)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_apic_icr_write
```
```
In drivers/clocksource/numachip.c (ffffffff8330fad2)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip2_timer_read
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
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810925c7)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_apic_icr_write
```
```
In drivers/clocksource/numachip.c (ffffffff834c98f5)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip2_timer_read
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
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810a7647)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_apic_icr_write
```
```
In drivers/clocksource/numachip.c (ffffffff83f0afee)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip2_timer_read
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
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810aa8a7)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_apic_icr_write
```
```
In drivers/clocksource/numachip.c (ffffffff837311be)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip2_timer_read
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
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810b18e7)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_apic_icr_write
```
```
In drivers/clocksource/numachip.c (ffffffff8396575e)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip2_timer_read
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
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106c647)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_apic_icr_write
```
```
In drivers/clocksource/numachip.c (ffffffff828fe94e)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip2_timer_read
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
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105c8f7)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_apic_icr_write
```
```
In drivers/clocksource/numachip.c (ffffffff828f6484)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip2_timer_read
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
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106caf7)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_apic_icr_write
```
```
In drivers/clocksource/numachip.c (ffffffff82913b7d)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip2_timer_read
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
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106e1f7)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip2_apic_icr_write
```
```
In drivers/clocksource/numachip.c (ffffffff8291a844)
Location: arch/x86/include/asm/numachip/numachip_csr.h:67
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip2_timer_read
```
</details>
</li>
</ul>

## Differences
